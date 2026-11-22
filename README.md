<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>CÔNG TY TNHH TƯ VẤN KỸ THUẬT XÂY DỰNG 36 | Thiết Kế & Thi Công Xây Dựng Đà Nẵng</title>
  <meta name="description" content="CÔNG TY TNHH TƯ VẤN KỸ THUẬT XÂY DỰNG 36 (xaydung36.com) chuyên tư vấn kỹ thuật, thiết kế kiến trúc - nội thất, thi công phần thô, hoàn thiện và xây dựng trọn gói tại Đà Nẵng. Hotline: 0934.280.484." />

  <!-- Meta Open Graph & Thumbnail Logo khi chia sẻ link trên Zalo, Facebook -->
  <meta property="og:type" content="website" />
  <meta property="og:site_name" content="CÔNG TY TNHH TƯ VẤN KỸ THUẬT XÂY DỰNG 36" />
  <meta property="og:url" content="https://xaydung36.com/" />
  <meta property="og:title" content="CÔNG TY TNHH TƯ VẤN KỸ THUẬT XÂY DỰNG 36 - xaydung36.com" />
  <meta property="og:description" content="Chuyên Tư vấn kỹ thuật, Thiết kế Kiến trúc - Nội thất, Thi công xây dựng trọn gói tại Đà Nẵng. Hotline: 0934.280.484" />
  <meta property="og:image" content="https://xaydung36.com/wp-content/uploads/logo-xaydung36-thumbnail.png" />
  <meta property="og:image:alt" content="Logo Công ty TNHH Tư vấn Kỹ thuật Xây dựng 36" />
  <meta property="og:image:width" content="1200" />
  <meta property="og:image:height" content="630" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="CÔNG TY TNHH TƯ VẤN KỸ THUẬT XÂY DỰNG 36" />
  <meta name="twitter:description" content="Thiết kế kiến trúc, thi công xây dựng & tư vấn kỹ thuật chuyên nghiệp tại Đà Nẵng." />
  <meta name="twitter:image" content="https://xaydung36.com/wp-content/uploads/logo-xaydung36-thumbnail.png" />

  <!-- Favicon Logo công ty -->
  <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 64 64'%3E%3Crect width='64' height='64' rx='12' fill='%230F2C59'/%3E%3Cpath d='M12 46V24L32 12L52 24V46' fill='none' stroke='%23E08E0B' stroke-width='4' stroke-linejoin='round'/%3E%3Ctext x='32' y='43' text-anchor='middle' font-family='Arial,sans-serif' font-weight='800' font-size='22' fill='%23FFFFFF'%3E36%3C/text%3E%3C/svg%3E" />

  <!-- Google Fonts: Inter & Roboto (Chuẩn Flatsome tiếng Việt sắc nét) -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet" />

  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'system-ui', '-apple-system', 'sans-serif'],
          },
          colors: {
            brand: {
              navy: '#0F2C59',      /* Màu chính theo Logo: Xanh Navy Kỹ Thuật */
              navyDark: '#091D3D',
              navyLight: '#1B427E',
              gold: '#D9820B',      /* Màu nhấn theo Logo: Vàng Cam Kiến Trúc */
              goldLight: '#F59E0B',
              bgSoft: '#F5F7FA',
            }
          }
        }
      }
    };
  </script>

  <style>
    /* =========================================================================
       RESET & CHỐNG TRÀN VIỀN / LỆCH SANG PHẢI TRÊN MỌI THIẾT BỊ
       ========================================================================= */
    *, *::before, *::after {
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
      width: 100%;
      max-width: 100%;
      overflow-x: hidden;
      font-family: 'Inter', system-ui, -apple-system, sans-serif;
    }

    body {
      margin: 0;
      padding: 0;
      width: 100%;
      max-width: 100%;
      overflow-x: hidden;
      background-color: #ffffff;
      color: #1e293b;
      -webkit-font-smoothing: antialiased;
    }

    /* Chiều ngang giao diện trên máy tính đúng bằng 95% kích thước màn hình */
    .site-container {
      width: 100%;
      max-width: 100%;
      margin-left: auto;
      margin-right: auto;
      padding-left: 12px;
      padding-right: 12px;
    }

    @media (min-width: 768px) {
      .site-container {
        width: 95%;
        max-width: 95%;
        padding-left: 0;
        padding-right: 0;
      }
    }

    /* =========================================================================
       CHUẨN FLATSOME: TIÊU ĐỀ MỤC, MENU DROPDOWN & HIỆU ỨNG NHẸ NHÀNG
       ========================================================================= */
    .flatsome-heading {
      position: relative;
      display: inline-block;
      padding-bottom: 10px;
    }

    .flatsome-heading::after {
      content: "";
      position: absolute;
      left: 50%;
      bottom: 0;
      transform: translateX(-50%);
      width: 64px;
      height: 3px;
      background: linear-gradient(90deg, #0F2C59 0%, #D9820B 100%);
      border-radius: 99px;
    }

    .flatsome-heading-left::after {
      left: 0;
      transform: none;
    }

    /* Menu Dropdown Desktop */
    .nav-item {
      position: relative;
    }

    .nav-dropdown {
      opacity: 0;
      visibility: hidden;
      transform: translateY(8px);
      transition: all 0.2s ease;
      pointer-events: none;
    }

    .nav-item:hover .nav-dropdown,
    .nav-item:focus-within .nav-dropdown {
      opacity: 1;
      visibility: visible;
      transform: translateY(0);
      pointer-events: auto;
    }

    /* Slider Banner 2 ảnh kích thước bằng nhau tuyệt đối */
    .hero-slider-wrapper {
      position: relative;
      width: 100%;
      overflow: hidden;
      background-color: #091D3D;
    }

    .hero-slides-track {
      display: flex;
      width: 200%;
      transition: transform 0.65s cubic-bezier(0.4, 0, 0.2, 1);
    }

    .hero-slide-item {
      width: 50%;
      flex-shrink: 0;
      position: relative;
      /* Chiều cao đồng nhất tuyệt đối giữa 2 banner trên từng màn hình */
      height: 340px;
    }

    @media (min-width: 640px) {
      .hero-slide-item {
        height: 410px;
      }
    }

    @media (min-width: 1024px) {
      .hero-slide-item {
        height: 490px;
      }
    }

    @media (min-width: 1280px) {
      .hero-slide-item {
        height: 520px;
      }
    }

    /* Hiệu ứng card ảnh Flatsome phóng nhẹ khi hover */
    .card-img-zoom {
      transition: transform 0.45s ease;
    }

    .group:hover .card-img-zoom {
      transform: scale(1.05);
    }

    /* Nút liên hệ nổi bật rung nhẹ thu hút chú ý */
    @keyframes subtlePulse {
      0%, 100% {
        box-shadow: 0 0 0 0 rgba(217, 130, 11, 0.5);
      }
      50% {
        box-shadow: 0 0 0 10px rgba(217, 130, 11, 0);
      }
    }

    .hotline-pulse {
      animation: subtlePulse 2.2s infinite;
    }

    /* Ẩn thanh cuộn phụ nhưng vẫn cuộn mượt trên mobile */
    .no-scrollbar::-webkit-scrollbar {
      display: none;
    }
    .no-scrollbar {
      -ms-overflow-style: none;
      scrollbar-width: none;
    }
  </style>
</head>

<body class="bg-white text-slate-800">

  <!-- =========================================================================
       TOP BAR THÔNG TIN CƠ BẢN (PHONG CÁCH FLATSOME)
       ========================================================================= -->
  <div class="bg-brand-navy text-white text-[11px] sm:text-xs py-1.5 border-b border-white/10">
    <div class="site-container flex flex-wrap items-center justify-between gap-y-1">
      <div class="flex items-center gap-3 min-w-0">
        <span class="truncate font-medium">CÔNG TY TNHH TƯ VẤN KỸ THUẬT XÂY DỰNG 36</span>
        <span class="hidden md:inline text-white/40">|</span>
        <span class="hidden md:inline text-white/85">MST: 0402187735</span>
      </div>
      <div class="flex items-center gap-3 sm:gap-4 shrink-0">
        <a href="tel:0934280484" class="hover:text-brand-goldLight transition-colors font-medium">0934.280.484</a>
        <span class="text-white/40">|</span>
        <a href="https://xaydung36.com" class="hover:text-brand-goldLight transition-colors">xaydung36.com</a>
      </div>
    </div>
  </div>

  <!-- =========================================================================
       HEADER CHÍNH (FLATSOME STICKY HEADER - KHÔNG CÓ NÚT GỌI NGAY TRÁNH TRÀN VIỀN)
       ========================================================================= -->
  <header id="site-header" class="sticky top-0 z-40 bg-white/98 backdrop-blur-md border-b border-slate-200 shadow-sm">
    <div class="site-container flex items-center justify-between gap-3 py-2.5">

      <!-- LOGO CÔNG TY CHUYÊN NGHIỆP - GỌN NHỎ -->
      <a href="#trang-chu" class="flex items-center gap-2 shrink-0 group focus:outline-none" aria-label="Trang chủ Xây Dựng 36">
        <!-- Biểu tượng SVG Logo gọn đẹp -->
        <svg class="w-9 h-9 sm:w-10 sm:h-10 shrink-0" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Logo Xây Dựng 36">
          <rect x="2" y="2" width="60" height="60" rx="12" fill="#0F2C59" />
          <path d="M12 46V25L32 12L52 25V46" stroke="#E08E0B" stroke-width="3.6" stroke-linecap="round" stroke-linejoin="round" />
          <path d="M22 46V31L32 24.5L42 31V46" stroke="#FFFFFF" stroke-opacity="0.25" stroke-width="2" />
          <rect x="11" y="46" width="42" height="4" rx="2" fill="#E08E0B" />
          <text x="32" y="42" text-anchor="middle" font-family="Inter, Arial, sans-serif" font-weight="800" font-size="20" fill="#FFFFFF" letter-spacing="-0.5">36</text>
        </svg>
        <div class="leading-tight">
          <div class="text-[14px] sm:text-[15px] font-extrabold tracking-tight text-brand-navy group-hover:text-brand-gold transition-colors whitespace-nowrap">
            XÂY DỰNG 36
          </div>
          <div class="text-[9.5px] sm:text-[10px] font-semibold tracking-wider text-brand-gold uppercase whitespace-nowrap">
            Tư vấn kỹ thuật xây dựng
          </div>
        </div>
      </a>

      <!-- MENU ĐIỀU HƯỚNG MÁY TÍNH: CHỮ NHỎ GỌN, VIẾT LIỀN 1 HÀNG, KHÔNG XUỐNG DÒNG TÊN DANH MỤC -->
      <nav class="hidden lg:flex flex-wrap items-center justify-end gap-x-3.5 xl:gap-x-5 gap-y-1 flex-1" aria-label="Danh mục chính">
        <a href="#trang-chu" class="text-[12.5px] xl:text-[13px] font-semibold text-brand-navy hover:text-brand-gold transition-colors whitespace-nowrap py-1">
          Trang chủ
        </a>
        <a href="#gioi-thieu" class="text-[12.5px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold transition-colors whitespace-nowrap py-1">
          Giới thiệu
        </a>

        <!-- Dropdown Công trình thực tế (theo web mẫu tintruongthinh.com) -->
        <div class="nav-item">
          <a href="#cong-trinh-thuc-te" class="inline-flex items-center gap-1 text-[12.5px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold transition-colors whitespace-nowrap py-1">
            <span>Công trình thực tế</span>
            <svg class="w-3 h-3 opacity-70" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
          </a>
          <div class="nav-dropdown absolute left-0 top-full pt-2 w-56 z-50">
            <div class="bg-white rounded-lg shadow-xl border border-slate-100 py-2">
              <a href="#cong-trinh-thuc-te" onclick="filterProjects('khach-san-can-ho')" class="block px-4 py-2 text-[12.5px] text-slate-700 hover:bg-brand-bgSoft hover:text-brand-navy font-medium">Khách sạn – Căn hộ – Phòng trọ</a>
              <a href="#cong-trinh-thuc-te" onclick="filterProjects('biet-thu')" class="block px-4 py-2 text-[12.5px] text-slate-700 hover:bg-brand-bgSoft hover:text-brand-navy font-medium">Biệt thự</a>
              <a href="#cong-trinh-thuc-te" onclick="filterProjects('nha-pho')" class="block px-4 py-2 text-[12.5px] text-slate-700 hover:bg-brand-bgSoft hover:text-brand-navy font-medium">Nhà phố</a>
              <a href="#cong-trinh-thuc-te" onclick="filterProjects('van-phong')" class="block px-4 py-2 text-[12.5px] text-slate-700 hover:bg-brand-bgSoft hover:text-brand-navy font-medium">Văn phòng – Hạ tầng</a>
            </div>
          </div>
        </div>

        <!-- Dropdown Lĩnh vực hoạt động (theo web mẫu tintruongthinh.com) -->
        <div class="nav-item">
          <a href="#dich-vu" class="inline-flex items-center gap-1 text-[12.5px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold transition-colors whitespace-nowrap py-1">
            <span>Lĩnh vực hoạt động</span>
            <svg class="w-3 h-3 opacity-70" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
          </a>
          <div class="nav-dropdown absolute left-0 top-full pt-2 w-56 z-50">
            <div class="bg-white rounded-lg shadow-xl border border-slate-100 py-2">
              <a href="#dich-vu" class="block px-4 py-2 text-[12.5px] text-slate-700 hover:bg-brand-bgSoft hover:text-brand-navy font-medium">Thiết kế Kiến trúc – Nội thất</a>
              <a href="#dich-vu" class="block px-4 py-2 text-[12.5px] text-slate-700 hover:bg-brand-bgSoft hover:text-brand-navy font-medium">Thi công phần thô</a>
              <a href="#dich-vu" class="block px-4 py-2 text-[12.5px] text-slate-700 hover:bg-brand-bgSoft hover:text-brand-navy font-medium">Thi công hoàn thiện</a>
              <a href="#dich-vu" class="block px-4 py-2 text-[12.5px] text-slate-700 hover:bg-brand-bgSoft hover:text-brand-navy font-medium">Tư vấn kỹ thuật & Giám sát</a>
            </div>
          </div>
        </div>

        <a href="#du-an-da-nang" class="text-[12.5px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold transition-colors whitespace-nowrap py-1">
          Dự án Đà Nẵng
        </a>

        <!-- Dropdown Báo giá -->
        <div class="nav-item">
          <a href="#bao-gia" class="inline-flex items-center gap-1 text-[12.5px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold transition-colors whitespace-nowrap py-1">
            <span>Báo giá</span>
            <svg class="w-3 h-3 opacity-70" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
          </a>
          <div class="nav-dropdown absolute right-0 top-full pt-2 w-56 z-50">
            <div class="bg-white rounded-lg shadow-xl border border-slate-100 py-2">
              <a href="#bao-gia" class="block px-4 py-2 text-[12.5px] text-slate-700 hover:bg-brand-bgSoft hover:text-brand-navy font-medium">Báo giá thiết kế kiến trúc</a>
              <a href="#bao-gia" class="block px-4 py-2 text-[12.5px] text-slate-700 hover:bg-brand-bgSoft hover:text-brand-navy font-medium">Báo giá thi công phần thô</a>
              <a href="#bao-gia" class="block px-4 py-2 text-[12.5px] text-slate-700 hover:bg-brand-bgSoft hover:text-brand-navy font-medium">Báo giá thi công hoàn thiện</a>
              <a href="#bao-gia" class="block px-4 py-2 text-[12.5px] text-slate-700 hover:bg-brand-bgSoft hover:text-brand-navy font-medium">Báo giá thi công trọn gói</a>
            </div>
          </div>
        </div>

        <a href="#doi-tac" class="text-[12.5px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold transition-colors whitespace-nowrap py-1">
          Đối tác
        </a>
        <a href="#tin-tuc" class="text-[12.5px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold transition-colors whitespace-nowrap py-1">
          Tin tức
        </a>
        <a href="#lien-he" class="text-[12.5px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold transition-colors whitespace-nowrap py-1">
          Liên hệ
        </a>
      </nav>

      <!-- NÚT MENU MOBILE -->
      <button id="mobile-menu-btn" type="button" class="lg:hidden inline-flex items-center justify-center p-2 rounded-lg text-brand-navy hover:bg-slate-100 focus:outline-none" aria-label="Mở danh mục">
        <svg id="menu-icon-open" class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" d="M4 6h16M4 12h16M4 18h16" />
        </svg>
        <svg id="menu-icon-close" class="w-6 h-6 hidden" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12" />
        </svg>
      </button>
    </div>

    <!-- NGĂN KÉO DANH MỤC MOBILE (FLATSOME OFF-CANVAS STYLE) -->
    <div id="mobile-menu-panel" class="hidden lg:hidden bg-white border-t border-slate-200 shadow-lg">
      <div class="site-container py-3 flex flex-col divide-y divide-slate-100 text-sm font-semibold text-slate-700">
        <a href="#trang-chu" onclick="closeMobileMenu()" class="py-2.5 hover:text-brand-gold">Trang chủ</a>
        <a href="#gioi-thieu" onclick="closeMobileMenu()" class="py-2.5 hover:text-brand-gold">Giới thiệu</a>
        <a href="#dich-vu" onclick="closeMobileMenu()" class="py-2.5 hover:text-brand-gold">Lĩnh vực hoạt động</a>
        <a href="#cong-trinh-thuc-te" onclick="closeMobileMenu()" class="py-2.5 hover:text-brand-gold">Công trình thực tế</a>
        <a href="#du-an-da-nang" onclick="closeMobileMenu()" class="py-2.5 hover:text-brand-gold">Dự án tại Đà Nẵng</a>
        <a href="#doi-tac" onclick="closeMobileMenu()" class="py-2.5 hover:text-brand-gold">Đối tác chiến lược</a>
        <a href="#bao-gia" onclick="closeMobileMenu()" class="py-2.5 hover:text-brand-gold">Yêu cầu báo giá</a>
        <a href="#tin-tuc" onclick="closeMobileMenu()" class="py-2.5 hover:text-brand-gold">Bài viết & Tin tức</a>
        <a href="#lien-he" onclick="closeMobileMenu()" class="py-2.5 hover:text-brand-gold">Bản đồ & Liên hệ</a>
      </div>
    </div>
  </header>

  <!-- =========================================================================
       SECTION 1: 2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP - KÍCH THƯỚC BẰNG NHAU
       HÌNH ẢNH & CHỮ NẰM GỌN TRONG BANNER, CÁCH XA VIỀN, KHÔNG THIẾU CHỮ TRÊN MOBILE & PC
       ========================================================================= -->
  <section id="trang-chu" class="w-full">
    <div class="hero-slider-wrapper" aria-label="Banner nổi bật Xây Dựng 36">
      <div id="hero-track" class="hero-slides-track">

        <!-- BANNER 1 -->
        <div class="hero-slide-item flex items-center">
          <img
            src="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w1600"
            data-drive-id="13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz"
            onerror="handleDriveImgError(this, '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz')"
            referrerpolicy="no-referrer"
            alt="Thi công công trình thực tế Xây Dựng 36"
            class="absolute inset-0 w-full h-full object-cover object-center"
          />
          <div class="absolute inset-0 bg-gradient-to-r from-[#091D3D]/92 via-[#0F2C59]/80 to-[#0F2C59]/55"></div>

          <!-- Vùng nội dung an toàn: padding lớn cách xa viền trái/phải/trên/dưới trên cả điện thoại & máy tính -->
          <div class="relative z-10 w-full h-full flex items-center justify-center px-10 sm:px-16 md:px-24 lg:px-28 py-8 sm:py-12">
            <div class="w-full max-w-4xl text-center md:text-left">
              <p class="text-[11px] sm:text-xs md:text-sm font-semibold uppercase tracking-[0.16em] text-brand-goldLight mb-2 sm:mb-3">
                XAYDUNG36.COM • ĐÀ NẴNG
              </p>
              <h1 class="text-lg sm:text-2xl md:text-4xl lg:text-[42px] font-extrabold text-white leading-snug sm:leading-tight mb-3 sm:mb-4">
                CÔNG TY TNHH TƯ VẤN KỸ THUẬT XÂY DỰNG 36
              </h1>
              <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed max-w-2xl mx-auto md:mx-0 mb-5 sm:mb-7">
                Chuyên Thiết kế Kiến trúc – Nội thất, Thi công Phần thô, Hoàn thiện trọn gói và Tư vấn Giám sát kỹ thuật công trình dân dụng &amp; hạ tầng tại Đà Nẵng.
              </p>
              <div class="flex flex-wrap items-center justify-center md:justify-start gap-2.5 sm:gap-3">
                <a href="#bao-gia" class="inline-flex items-center justify-center px-4 sm:px-6 py-2 sm:py-2.5 rounded-lg bg-brand-gold hover:bg-brand-goldLight text-white text-xs sm:text-sm font-bold shadow-md transition-colors">
                  Nhận tư vấn &amp; Báo giá
                </a>
                <a href="#du-an-da-nang" class="inline-flex items-center justify-center px-4 sm:px-6 py-2 sm:py-2.5 rounded-lg bg-white/15 hover:bg-white/25 text-white border border-white/35 text-xs sm:text-sm font-semibold backdrop-blur-sm transition-colors">
                  Xem dự án Đà Nẵng
                </a>
              </div>
            </div>
          </div>
        </div>

        <!-- BANNER 2 -->
        <div class="hero-slide-item flex items-center">
          <img
            src="https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w1600"
            data-drive-id="157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT"
            onerror="handleDriveImgError(this, '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT')"
            referrerpolicy="no-referrer"
            alt="Dự án xây dựng tiêu biểu tại Đà Nẵng"
            class="absolute inset-0 w-full h-full object-cover object-center"
          />
          <div class="absolute inset-0 bg-gradient-to-r from-[#091D3D]/92 via-[#0F2C59]/80 to-[#0F2C59]/55"></div>

          <!-- Vùng nội dung an toàn cách xa viền ảnh banner -->
          <div class="relative z-10 w-full h-full flex items-center justify-center px-10 sm:px-16 md:px-24 lg:px-28 py-8 sm:py-12">
            <div class="w-full max-w-4xl text-center md:text-left">
              <p class="text-[11px] sm:text-xs md:text-sm font-semibold uppercase tracking-[0.16em] text-brand-goldLight mb-2 sm:mb-3">
                AN TOÀN • CHẤT LƯỢNG • ĐÚNG TIẾN ĐỘ
              </p>
              <h2 class="text-lg sm:text-2xl md:text-4xl lg:text-[42px] font-extrabold text-white leading-snug sm:leading-tight mb-3 sm:mb-4">
                KIẾN TẠO CÔNG TRÌNH VỮNG BỀN THEO THỜI GIAN
              </h2>
              <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed max-w-2xl mx-auto md:mx-0 mb-5 sm:mb-7">
                Đội ngũ kỹ sư kết cấu và kiến trúc sư dày dặn kinh nghiệm trực tiếp khảo sát, lập dự toán minh bạch và giám sát chặt chẽ từng hạng mục thi công.
              </p>
              <div class="flex flex-wrap items-center justify-center md:justify-start gap-2.5 sm:gap-3">
                <a href="#cong-trinh-thuc-te" class="inline-flex items-center justify-center px-4 sm:px-6 py-2 sm:py-2.5 rounded-lg bg-brand-gold hover:bg-brand-goldLight text-white text-xs sm:text-sm font-bold shadow-md transition-colors">
                  Công trình thực tế
                </a>
                <a href="tel:0934280484" class="inline-flex items-center justify-center px-4 sm:px-6 py-2 sm:py-2.5 rounded-lg bg-white/15 hover:bg-white/25 text-white border border-white/35 text-xs sm:text-sm font-semibold backdrop-blur-sm transition-colors">
                  Hotline: 0934.280.484
                </a>
              </div>
            </div>
          </div>
        </div>

      </div>

      <!-- Nút điều hướng Trái / Phải gọn sát mép không đè chữ -->
      <button type="button" onclick="prevSlide()" aria-label="Banner trước" class="absolute left-2 sm:left-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-brand-gold text-white flex items-center justify-center transition-colors">
        <svg class="w-4 h-4 sm:w-5 sm:h-5" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M15 19l-7-7 7-7"/></svg>
      </button>
      <button type="button" onclick="nextSlide()" aria-label="Banner tiếp theo" class="absolute right-2 sm:right-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-brand-gold text-white flex items-center justify-center transition-colors">
        <svg class="w-4 h-4 sm:w-5 sm:h-5" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M9 5l7 7-7 7"/></svg>
      </button>

      <!-- Chấm tròn chỉ báo 2 banner -->
      <div class="absolute bottom-3.5 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
        <button id="dot-0" type="button" onclick="goToSlide(0)" aria-label="Chuyển đến Banner 1" class="w-7 h-2 rounded-full bg-brand-gold transition-all"></button>
        <button id="dot-1" type="button" onclick="goToSlide(1)" aria-label="Chuyển đến Banner 2" class="w-2.5 h-2 rounded-full bg-white/60 hover:bg-white transition-all"></button>
      </div>
    </div>
  </section>

  <!-- =========================================================================
       SECTION 2: DỊCH VỤ TIÊU BIỂU (CHUẨN CẤU TRÚC WEB MẪU TINTRUONGTHINH.COM)
       ========================================================================= -->
  <section id="dich-vu" class="py-10 sm:py-14 bg-white">
    <div class="site-container">
      <div class="text-center mb-8">
        <h2 class="flatsome-heading text-lg sm:text-2xl font-extrabold uppercase text-brand-navy tracking-wide">
          Dịch Vụ Tiêu Biểu
        </h2>
        <p class="mt-3 text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto">
          Giải pháp toàn diện từ tư vấn lập dự án, thiết kế kiến trúc đến thi công hoàn thiện công trình dân dụng và hạ tầng kỹ thuật.
        </p>
      </div>

      <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
      <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">

        <!-- Dịch vụ 1 -->
        <a href="#bao-gia" class="group bg-brand-bgSoft rounded-xl overflow-hidden border border-slate-200/80 hover:border-brand-gold/60 hover:shadow-md transition-all flex flex-col">
          <div class="aspect-[4/3] w-full overflow-hidden bg-slate-200">
            <img
              src="https://drive.google.com/thumbnail?id=1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR&sz=w800"
              onerror="handleDriveImgError(this, '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR')"
              referrerpolicy="no-referrer"
              alt="Thiết kế Kiến trúc Nội thất"
              class="w-full h-full object-cover card-img-zoom"
            />
          </div>
          <div class="p-3 sm:p-4 text-center flex-1 flex flex-col justify-center">
            <h3 class="text-xs sm:text-[15px] font-bold text-brand-navy group-hover:text-brand-gold transition-colors uppercase leading-snug">
              Thiết Kế Kiến Trúc – Nội Thất
            </h3>
            <p class="mt-1.5 text-[11px] sm:text-xs text-slate-600 leading-relaxed hidden sm:block">
              Tối ưu công năng, chuẩn phong thủy, hồ sơ bản vẽ kỹ thuật thi công chi tiết.
            </p>
          </div>
        </a>

        <!-- Dịch vụ 2 -->
        <a href="#bao-gia" class="group bg-brand-bgSoft rounded-xl overflow-hidden border border-slate-200/80 hover:border-brand-gold/60 hover:shadow-md transition-all flex flex-col">
          <div class="aspect-[4/3] w-full overflow-hidden bg-slate-200">
            <img
              src="https://drive.google.com/thumbnail?id=1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv&sz=w800"
              onerror="handleDriveImgError(this, '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv')"
              referrerpolicy="no-referrer"
              alt="Thi công phần thô chuẩn kỹ thuật"
              class="w-full h-full object-cover card-img-zoom"
            />
          </div>
          <div class="p-3 sm:p-4 text-center flex-1 flex flex-col justify-center">
            <h3 class="text-xs sm:text-[15px] font-bold text-brand-navy group-hover:text-brand-gold transition-colors uppercase leading-snug">
              Thi Công Phần Thô
            </h3>
            <p class="mt-1.5 text-[11px] sm:text-xs text-slate-600 leading-relaxed hidden sm:block">
              Kết cấu móng, cột, dầm, sàn bền vững, vật tư chính hãng đúng cam kết.
            </p>
          </div>
        </a>

        <!-- Dịch vụ 3 -->
        <a href="#bao-gia" class="group bg-brand-bgSoft rounded-xl overflow-hidden border border-slate-200/80 hover:border-brand-gold/60 hover:shadow-md transition-all flex flex-col">
          <div class="aspect-[4/3] w-full overflow-hidden bg-slate-200">
            <img
              src="https://drive.google.com/thumbnail?id=1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_&sz=w800"
              onerror="handleDriveImgError(this, '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_')"
              referrerpolicy="no-referrer"
              alt="Thi công hoàn thiện trọn gói"
              class="w-full h-full object-cover card-img-zoom"
            />
          </div>
          <div class="p-3 sm:p-4 text-center flex-1 flex flex-col justify-center">
            <h3 class="text-xs sm:text-[15px] font-bold text-brand-navy group-hover:text-brand-gold transition-colors uppercase leading-snug">
              Thi Công Hoàn Thiện Trọn Gói
            </h3>
            <p class="mt-1.5 text-[11px] sm:text-xs text-slate-600 leading-relaxed hidden sm:block">
              Chìa khóa trao tay từ xây tô, điện nước MEP đến hoàn thiện nội thất tinh tế.
            </p>
          </div>
        </a>

        <!-- Dịch vụ 4 -->
        <a href="#bao-gia" class="group bg-brand-bgSoft rounded-xl overflow-hidden border border-slate-200/80 hover:border-brand-gold/60 hover:shadow-md transition-all flex flex-col">
          <div class="aspect-[4/3] w-full overflow-hidden bg-slate-200">
            <img
              src="https://drive.google.com/thumbnail?id=1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO&sz=w800"
              onerror="handleDriveImgError(this, '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO')"
              referrerpolicy="no-referrer"
              alt="Tư vấn kỹ thuật và giám sát thi công"
              class="w-full h-full object-cover card-img-zoom"
            />
          </div>
          <div class="p-3 sm:p-4 text-center flex-1 flex flex-col justify-center">
            <h3 class="text-xs sm:text-[15px] font-bold text-brand-navy group-hover:text-brand-gold transition-colors uppercase leading-snug">
              Tư Vấn Kỹ Thuật &amp; Giám Sát
            </h3>
            <p class="mt-1.5 text-[11px] sm:text-xs text-slate-600 leading-relaxed hidden sm:block">
              Khảo sát địa chất, thẩm tra thiết kế dự toán và giám sát chất lượng công trình.
            </p>
          </div>
        </a>

      </div>
    </div>
  </section>

  <!-- =========================================================================
       SECTION 3: GIỚI THIỆU CÔNG TY & THẾ MẠNH (CHUẨN BỐ CỤC TINTRUONGTHINH.COM)
       ========================================================================= -->
  <section id="gioi-thieu" class="py-10 sm:py-14 bg-brand-bgSoft border-y border-slate-200/70">
    <div class="site-container">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-7 lg:gap-10 items-center mb-10 sm:mb-12">
        <!-- Nội dung giới thiệu -->
        <div class="lg:col-span-7">
          <h2 class="flatsome-heading flatsome-heading-left text-lg sm:text-2xl font-extrabold uppercase text-brand-navy leading-snug">
            CÔNG TY TNHH TƯ VẤN KỸ THUẬT XÂY DỰNG 36
          </h2>
          <p class="mt-4 text-xs sm:text-sm text-slate-700 leading-relaxed text-justify">
            <strong>CÔNG TY TNHH TƯ VẤN KỸ THUẬT XÂY DỰNG 36</strong> (xaydung36.com) là đơn vị uy tín chuyên hoạt động trong lĩnh vực Tư vấn kỹ thuật, Thiết kế Kiến trúc – Nội thất, Thi công xây dựng nhà phố, biệt thự, khách sạn, căn hộ, văn phòng và công trình hạ tầng kỹ thuật tại khu vực Đà Nẵng &amp; Miền Trung.
          </p>
          <p class="mt-3 text-xs sm:text-sm text-slate-700 leading-relaxed text-justify">
            Với phương châm đặt cái <strong>“TÂM”</strong> và chuẩn mực kỹ thuật lên hàng đầu, mỗi công trình do Xây Dựng 36 thực hiện luôn cam kết đạt 4 tiêu chí cốt lõi: <strong>AN TOÀN – CHẤT LƯỢNG – TIẾN ĐỘ – MINH BẠCH CHI PHÍ</strong>, mang lại sự an tâm tuyệt đối cho Quý chủ đầu tư.
          </p>

          <!-- Chỉ số năng lực gọn đẹp -->
          <div class="mt-6 grid grid-cols-3 gap-3">
            <div class="bg-white rounded-xl p-3 sm:p-4 text-center border border-slate-200">
              <div class="text-lg sm:text-2xl font-extrabold text-brand-navy">100%</div>
              <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5">Chuẩn kỹ thuật</div>
            </div>
            <div class="bg-white rounded-xl p-3 sm:p-4 text-center border border-slate-200">
              <div class="text-lg sm:text-2xl font-extrabold text-brand-gold">50+</div>
              <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5">Công trình thực tế</div>
            </div>
            <div class="bg-white rounded-xl p-3 sm:p-4 text-center border border-slate-200">
              <div class="text-lg sm:text-2xl font-extrabold text-brand-navy">24/7</div>
              <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5">Tư vấn &amp; Bảo hành</div>
            </div>
          </div>
        </div>

        <!-- Ảnh thực tế giới thiệu -->
        <div class="lg:col-span-5">
          <div class="rounded-xl overflow-hidden shadow-md border border-slate-200 bg-white">
            <img
              src="https://drive.google.com/thumbnail?id=1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t&sz=w1000"
              onerror="handleDriveImgError(this, '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t')"
              referrerpolicy="no-referrer"
              alt="Đội ngũ kỹ sư Xây Dựng 36 tại công trường"
              class="w-full h-64 sm:h-80 object-cover"
            />
          </div>
        </div>
      </div>

      <!-- 6 THẾ MẠNH CỦA CHÚNG TÔI (ĐỒNG BỘ MẪU TINTRUONGTHINH.COM) -->
      <div class="text-center mb-7">
        <h3 class="flatsome-heading text-base sm:text-xl font-extrabold uppercase text-brand-navy">
          Thế Mạnh Của Chúng Tôi
        </h3>
      </div>

      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-5">
        <div class="bg-white rounded-xl p-4 sm:p-5 border border-slate-200/90 flex items-start gap-3.5">
          <div class="w-10 h-10 rounded-lg bg-brand-navy text-brand-goldLight flex items-center justify-center shrink-0">
            <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
          </div>
          <div>
            <h4 class="text-sm font-bold text-brand-navy">Đội ngũ kỹ sư, kiến trúc sư chuyên nghiệp</h4>
            <p class="mt-1 text-xs text-slate-600 leading-relaxed">Giàu kinh nghiệm thực chiến từ khảo sát, thiết kế, thẩm tra đến trực tiếp chỉ huy thi công tại công trình.</p>
          </div>
        </div>

        <div class="bg-white rounded-xl p-4 sm:p-5 border border-slate-200/90 flex items-start gap-3.5">
          <div class="w-10 h-10 rounded-lg bg-brand-navy text-brand-goldLight flex items-center justify-center shrink-0">
            <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 21V5a2 2 0 00-2-2H7a2 2 0 00-2 2v16m14 0h2m-2 0h-5m-9 0H3m2 0h5M9 7h1m-1 4h1m4-4h1m-1 4h1m-5 10v-5a1 1 0 011-1h2a1 1 0 011 1v5m-4 0h4"/></svg>
          </div>
          <div>
            <h4 class="text-sm font-bold text-brand-navy">Cập nhật xu hướng thiết kế hiện đại</h4>
            <p class="mt-1 text-xs text-slate-600 leading-relaxed">Ứng dụng công nghệ, vật liệu xây dựng tiên tiến và giải pháp thi công tối ưu công năng, thẩm mỹ cao.</p>
          </div>
        </div>

        <div class="bg-white rounded-xl p-4 sm:p-5 border border-slate-200/90 flex items-start gap-3.5">
          <div class="w-10 h-10 rounded-lg bg-brand-navy text-brand-goldLight flex items-center justify-center shrink-0">
            <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"/></svg>
          </div>
          <div>
            <h4 class="text-sm font-bold text-brand-navy">Giám sát tiến độ &amp; kỹ thuật chuẩn xác</h4>
            <p class="mt-1 text-xs text-slate-600 leading-relaxed">Báo cáo tiến độ thường xuyên, nghiệm thu từng giai đoạn rõ ràng giúp chủ đầu tư dễ dàng theo dõi từ xa.</p>
          </div>
        </div>

        <div class="bg-white rounded-xl p-4 sm:p-5 border border-slate-200/90 flex items-start gap-3.5">
          <div class="w-10 h-10 rounded-lg bg-brand-navy text-brand-goldLight flex items-center justify-center shrink-0">
            <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z"/></svg>
          </div>
          <div>
            <h4 class="text-sm font-bold text-brand-navy">Bảo hành công trình dài hạn</h4>
            <p class="mt-1 text-xs text-slate-600 leading-relaxed">Chế độ bảo hành kết cấu &amp; hoàn thiện rõ ràng bằng hợp đồng, hỗ trợ xử lý kỹ thuật nhanh chóng.</p>
          </div>
        </div>

        <div class="bg-white rounded-xl p-4 sm:p-5 border border-slate-200/90 flex items-start gap-3.5">
          <div class="w-10 h-10 rounded-lg bg-brand-navy text-brand-goldLight flex items-center justify-center shrink-0">
            <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M12 8c-1.657 0-3 .895-3 2s1.343 2 3 2 3 .895 3 2-1.343 2-3 2m0-8c1.11 0 2.08.402 2.599 1M12 8V7m0 1v8m0 0v1m0-1c-1.11 0-2.08-.402-2.599-1M21 12a9 9 0 11-18 0 9 9 0 0118 0z"/></svg>
          </div>
          <div>
            <h4 class="text-sm font-bold text-brand-navy">Dự toán minh bạch – Chi phí hợp lý</h4>
            <p class="mt-1 text-xs text-slate-600 leading-relaxed">Bóc tách khối lượng chi tiết từng hạng mục, cam kết không phát sinh chi phí bất hợp lý trong quá trình thi công.</p>
          </div>
        </div>

        <div class="bg-white rounded-xl p-4 sm:p-5 border border-slate-200/90 flex items-start gap-3.5">
          <div class="w-10 h-10 rounded-lg bg-brand-navy text-brand-goldLight flex items-center justify-center shrink-0">
            <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
          </div>
          <div>
            <h4 class="text-sm font-bold text-brand-navy">Hỗ trợ tư vấn kỹ thuật 24/7</h4>
            <p class="mt-1 text-xs text-slate-600 leading-relaxed">Luôn sẵn sàng lắng nghe, tư vấn phương án thiết kế, pháp lý giấy phép xây dựng miễn phí qua Hotline &amp; Zalo.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- =========================================================================
       SECTION 4: CÔNG TRÌNH THỰC TẾ & SẢN PHẨM THI CÔNG (9 ẢNH THỰC TẾ GOOGLE DRIVE)
       DANH MỤC GỌN 1 HÀNG TRÊN PC, CHIA 2 CỘT TRÊN MOBILE, KHÔNG NHÃN DÁN, KHÔNG CẮT CHỮ
       ========================================================================= -->
  <section id="cong-trinh-thuc-te" class="py-10 sm:py-14 bg-white">
    <div class="site-container">
      <div class="text-center mb-6">
        <h2 class="flatsome-heading text-lg sm:text-2xl font-extrabold uppercase text-brand-navy">
          Công Trình Thực Tế &amp; Sản Phẩm Thi Công
        </h2>
        <p class="mt-3 text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto">
          Hình ảnh thực tế các hạng mục thi công phần thô, kết cấu, hoàn thiện và nội thất do đội ngũ kỹ sư Xây Dựng 36 trực tiếp triển khai.
        </p>
      </div>

      <!-- Thanh lọc danh mục chuẩn web mẫu: Chữ nhỏ gọn, không xuống dòng tên danh mục -->
      <div id="project-tabs" class="flex flex-wrap items-center justify-center gap-2 mb-7">
        <button type="button" data-cat="all" onclick="filterProjects('all')" class="project-tab px-3 sm:px-4 py-1.5 rounded-lg text-[11.5px] sm:text-[13px] font-semibold whitespace-nowrap bg-brand-navy text-white transition-colors">
          Tất cả
        </button>
        <button type="button" data-cat="nha-pho" onclick="filterProjects('nha-pho')" class="project-tab px-3 sm:px-4 py-1.5 rounded-lg text-[11.5px] sm:text-[13px] font-semibold whitespace-nowrap bg-slate-100 text-slate-700 hover:bg-brand-navy/10 transition-colors">
          Nhà phố
        </button>
        <button type="button" data-cat="biet-thu" onclick="filterProjects('biet-thu')" class="project-tab px-3 sm:px-4 py-1.5 rounded-lg text-[11.5px] sm:text-[13px] font-semibold whitespace-nowrap bg-slate-100 text-slate-700 hover:bg-brand-navy/10 transition-colors">
          Biệt thự
        </button>
        <button type="button" data-cat="khach-san-can-ho" onclick="filterProjects('khach-san-can-ho')" class="project-tab px-3 sm:px-4 py-1.5 rounded-lg text-[11.5px] sm:text-[13px] font-semibold whitespace-nowrap bg-slate-100 text-slate-700 hover:bg-brand-navy/10 transition-colors">
          Khách sạn – Căn hộ – Phòng trọ
        </button>
        <button type="button" data-cat="van-phong" onclick="filterProjects('van-phong')" class="project-tab px-3 sm:px-4 py-1.5 rounded-lg text-[11.5px] sm:text-[13px] font-semibold whitespace-nowrap bg-slate-100 text-slate-700 hover:bg-brand-navy/10 transition-colors">
          Văn phòng – Hạ tầng
        </button>
      </div>

      <!-- Lưới sản phẩm thi công: 2 cột trên điện thoại, 3 cột trên máy tính, không nhãn dán -->
      <div id="construction-grid" class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-5">
        <!-- Dữ liệu 9 ảnh thực tế được render bằng JS để lọc mượt mà và mở ảnh lớn -->
      </div>
    </div>
  </section>

  <!-- =========================================================================
       SECTION 5: DANH MỤC CÁC DỰ ÁN TẠI ĐÀ NẴNG (10 ẢNH DỰ ÁN GOOGLE DRIVE)
       CHIA 2 CỘT TRÊN MOBILE, 5 CỘT TRÊN PC (2 HÀNG ĐỀU ĐẸP), KHÔNG NHÃN DÁN
       ========================================================================= -->
  <section id="du-an-da-nang" class="py-10 sm:py-14 bg-brand-bgSoft border-y border-slate-200/70">
    <div class="site-container">
      <div class="text-center mb-8">
        <h2 class="flatsome-heading text-lg sm:text-2xl font-extrabold uppercase text-brand-navy">
          Các Dự Án Tiêu Biểu Tại Đà Nẵng
        </h2>
        <p class="mt-3 text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto">
          Tổng hợp hình ảnh các dự án thiết kế, thi công và tư vấn giám sát mà Công ty TNHH Tư vấn Kỹ thuật Xây dựng 36 đã và đang thực hiện tại TP Đà Nẵng.
        </p>
      </div>

      <!-- Lưới 10 dự án Đà Nẵng: 2 cột điện thoại, 3 cột tablet, 5 cột desktop -->
      <div id="danang-projects-grid" class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-5 gap-3 sm:gap-4">
        <!-- Render 10 ảnh Google Drive từ mảng dữ liệu chuẩn -->
      </div>
    </div>
  </section>

  <!-- =========================================================================
       SECTION 6: DANH MỤC CÁC ĐỐI TÁC CHIẾN LƯỢC
       ========================================================================= -->
  <section id="doi-tac" class="py-10 sm:py-14 bg-white">
    <div class="site-container">
      <div class="text-center mb-8">
        <h2 class="flatsome-heading text-lg sm:text-2xl font-extrabold uppercase text-brand-navy">
          Đối Tác &amp; Nhà Cung Cấp Chiến Lược
        </h2>
        <p class="mt-3 text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto">
          Hợp tác chặt chẽ cùng các thương hiệu vật liệu xây dựng và thiết bị hàng đầu nhằm đảm bảo chất lượng bền vững cho mọi công trình.
        </p>
      </div>

      <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-3">
        <!-- Đối tác 1 -->
        <div class="bg-brand-bgSoft rounded-xl border border-slate-200 p-3 sm:p-4 flex flex-col items-center justify-center text-center hover:border-brand-gold transition-colors">
          <div class="text-sm sm:text-base font-extrabold text-brand-navy tracking-tight">HÒA PHÁT</div>
          <div class="text-[10px] text-slate-500 mt-0.5">Thép xây dựng</div>
        </div>
        <!-- Đối tác 2 -->
        <div class="bg-brand-bgSoft rounded-xl border border-slate-200 p-3 sm:p-4 flex flex-col items-center justify-center text-center hover:border-brand-gold transition-colors">
          <div class="text-sm sm:text-base font-extrabold text-brand-navy tracking-tight">SÔNG GIANH</div>
          <div class="text-[10px] text-slate-500 mt-0.5">Xi măng cao cấp</div>
        </div>
        <!-- Đối tác 3 -->
        <div class="bg-brand-bgSoft rounded-xl border border-slate-200 p-3 sm:p-4 flex flex-col items-center justify-center text-center hover:border-brand-gold transition-colors">
          <div class="text-sm sm:text-base font-extrabold text-brand-navy tracking-tight">JOTUN</div>
          <div class="text-[10px] text-slate-500 mt-0.5">Sơn nội ngoại thất</div>
        </div>
        <!-- Đối tác 4 -->
        <div class="bg-brand-bgSoft rounded-xl border border-slate-200 p-3 sm:p-4 flex flex-col items-center justify-center text-center hover:border-brand-gold transition-colors">
          <div class="text-sm sm:text-base font-extrabold text-brand-navy tracking-tight">DULUX</div>
          <div class="text-[10px] text-slate-500 mt-0.5">Sơn &amp; Chống thấm</div>
        </div>
        <!-- Đối tác 5 -->
        <div class="bg-brand-bgSoft rounded-xl border border-slate-200 p-3 sm:p-4 flex flex-col items-center justify-center text-center hover:border-brand-gold transition-colors">
          <div class="text-sm sm:text-base font-extrabold text-brand-navy tracking-tight">XINGFA</div>
          <div class="text-[10px] text-slate-500 mt-0.5">Nhôm kính cao cấp</div>
        </div>
        <!-- Đối tác 6 -->
        <div class="bg-brand-bgSoft rounded-xl border border-slate-200 p-3 sm:p-4 flex flex-col items-center justify-center text-center hover:border-brand-gold transition-colors">
          <div class="text-sm sm:text-base font-extrabold text-brand-navy tracking-tight">CADIVI</div>
          <div class="text-[10px] text-slate-500 mt-0.5">Dây cáp điện</div>
        </div>
        <!-- Đối tác 7 -->
        <div class="bg-brand-bgSoft rounded-xl border border-slate-200 p-3 sm:p-4 flex flex-col items-center justify-center text-center hover:border-brand-gold transition-colors">
          <div class="text-sm sm:text-base font-extrabold text-brand-navy tracking-tight">BÌNH MINH</div>
          <div class="text-[10px] text-slate-500 mt-0.5">Ống cấp thoát nước</div>
        </div>
        <!-- Đối tác 8 -->
        <div class="bg-brand-bgSoft rounded-xl border border-slate-200 p-3 sm:p-4 flex flex-col items-center justify-center text-center hover:border-brand-gold transition-colors">
          <div class="text-sm sm:text-base font-extrabold text-brand-navy tracking-tight">INAX</div>
          <div class="text-[10px] text-slate-500 mt-0.5">Thiết bị vệ sinh</div>
        </div>
      </div>
    </div>
  </section>

  <!-- =========================================================================
       SECTION 7: FORM YÊU CẦU TƯ VẤN & BÁO GIÁ TRANG CHỦ (MẪU TINTRUONGTHINH.COM)
       ========================================================================= -->
  <section id="bao-gia" class="py-10 sm:py-14 bg-brand-navy text-white">
    <div class="site-container">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-7 lg:gap-10 items-center">

        <!-- Cột trái: Thông điệp tư vấn -->
        <div class="lg:col-span-5">
          <p class="text-xs font-bold uppercase tracking-widest text-brand-goldLight mb-2">
            MIỄN PHÍ KHẢO SÁT &amp; DỰ TOÁN
          </p>
          <h2 class="text-xl sm:text-3xl font-extrabold leading-tight mb-4">
            Đăng Ký Yêu Cầu Tư Vấn &amp; Báo Giá Xây Dựng
          </h2>
          <p class="text-xs sm:text-sm text-slate-200 leading-relaxed mb-5">
            Quý khách vui lòng để lại thông tin loại công trình và nhu cầu dự kiến. Kỹ sư của <strong>Xây Dựng 36</strong> sẽ liên hệ tư vấn giải pháp kết cấu, thiết kế và gửi bảng dự toán chi tiết hoàn toàn miễn phí.
          </p>

          <div class="space-y-2.5 text-xs sm:text-sm text-slate-100">
            <div class="flex items-start gap-2.5">
              <span class="text-brand-goldLight font-bold">✓</span>
              <span>Báo giá chi tiết từng hạng mục: Thiết kế, Phần thô, Hoàn thiện trọn gói.</span>
            </div>
            <div class="flex items-start gap-2.5">
              <span class="text-brand-goldLight font-bold">✓</span>
              <span>Hỗ trợ tư vấn xin giấy phép xây dựng và hồ sơ kỹ thuật tại Đà Nẵng.</span>
            </div>
            <div class="flex items-start gap-2.5">
              <span class="text-brand-goldLight font-bold">✓</span>
              <span>Hotline kỹ sư hỗ trợ nhanh: <a href="tel:0934280484" class="text-brand-goldLight font-bold underline">0934.280.484</a></span>
            </div>
          </div>
        </div>

        <!-- Cột phải: Form gửi yêu cầu -->
        <div class="lg:col-span-7">
          <form id="quote-form" class="bg-white text-slate-800 rounded-xl p-5 sm:p-7 shadow-xl" onsubmit="handleQuoteSubmit(event)">
            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5 sm:gap-4">
              <div>
                <label for="q-name" class="block text-xs font-semibold text-slate-700 mb-1">Họ và tên *</label>
                <input id="q-name" name="name" type="text" required placeholder="Nhập họ tên của bạn" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-xs sm:text-sm focus:outline-none focus:border-brand-navy focus:ring-2 focus:ring-brand-navy/15" />
              </div>
              <div>
                <label for="q-phone" class="block text-xs font-semibold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                <input id="q-phone" name="phone" type="tel" required placeholder="VD: 0934.280.484" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-xs sm:text-sm focus:outline-none focus:border-brand-navy focus:ring-2 focus:ring-brand-navy/15" />
              </div>
              <div>
                <label for="q-type" class="block text-xs font-semibold text-slate-700 mb-1">Loại công trình</label>
                <select id="q-type" name="type" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-xs sm:text-sm bg-white focus:outline-none focus:border-brand-navy">
                  <option value="Nhà phố">Nhà phố</option>
                  <option value="Biệt thự">Biệt thự</option>
                  <option value="Khách sạn – Căn hộ – Phòng trọ">Khách sạn – Căn hộ – Phòng trọ</option>
                  <option value="Văn phòng – Nhà xưởng">Văn phòng – Nhà xưởng</option>
                  <option value="Cải tạo sửa chữa">Cải tạo sửa chữa</option>
                  <option value="Tư vấn thiết kế & Giám sát">Tư vấn thiết kế &amp; Giám sát</option>
                </select>
              </div>
              <div>
                <label for="q-budget" class="block text-xs font-semibold text-slate-700 mb-1">Mức đầu tư dự kiến</label>
                <select id="q-budget" name="budget" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-xs sm:text-sm bg-white focus:outline-none focus:border-brand-navy">
                  <option value="Chưa xác định">Chưa xác định</option>
                  <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                  <option value="500 triệu – 1 tỷ">500 triệu – 1 tỷ</option>
                  <option value="1 – 2 tỷ">1 – 2 tỷ</option>
                  <option value="2 – 3 tỷ">2 – 3 tỷ</option>
                  <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                </select>
              </div>
              <div class="sm:col-span-2">
                <label for="q-email" class="block text-xs font-semibold text-slate-700 mb-1">Email (không bắt buộc)</label>
                <input id="q-email" name="email" type="email" placeholder="Nhập email nhận bảng báo giá" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-xs sm:text-sm focus:outline-none focus:border-brand-navy focus:ring-2 focus:ring-brand-navy/15" />
              </div>
              <div class="sm:col-span-2">
                <label for="q-note" class="block text-xs font-semibold text-slate-700 mb-1">Mô tả nhu cầu (Diện tích, số tầng, địa điểm xây dựng)</label>
                <textarea id="q-note" name="note" rows="3" placeholder="VD: Xây nhà phố 3 tầng diện tích 5x20m tại Hòa Xuân, Đà Nẵng..." class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-xs sm:text-sm focus:outline-none focus:border-brand-navy focus:ring-2 focus:ring-brand-navy/15"></textarea>
              </div>
            </div>

            <button type="submit" class="mt-4 w-full py-3 rounded-lg bg-brand-gold hover:bg-brand-goldLight text-white font-bold text-sm shadow-md transition-colors">
              GỬI YÊU CẦU BÁO GIÁ MIỄN PHÍ
            </button>

            <!-- Hộp thông báo phản hồi ngay trên trang (không dùng alert) -->
            <div id="quote-feedback" class="hidden mt-3 p-3 rounded-lg bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs sm:text-sm font-medium"></div>
          </form>
        </div>

      </div>
    </div>
  </section>

  <!-- =========================================================================
       SECTION 8: DANH MỤC CÁC BÀI VIẾT & TIN TỨC TRANG CHỦ
       ========================================================================= -->
  <section id="tin-tuc" class="py-10 sm:py-14 bg-white">
    <div class="site-container">
      <div class="text-center mb-8">
        <h2 class="flatsome-heading text-lg sm:text-2xl font-extrabold uppercase text-brand-navy">
          Bài Viết &amp; Cẩm Nang Xây Dựng
        </h2>
        <p class="mt-3 text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto">
          Chia sẻ kiến thức kỹ thuật thi công, kinh nghiệm xây nhà trọn gói và giải pháp tối ưu chi phí từ đội ngũ kỹ sư Xây Dựng 36.
        </p>
      </div>

      <!-- 2 cột trên điện thoại, 4 cột trên máy tính -->
      <div id="articles-grid" class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
        <!-- Render danh sách bài viết chuyên môn -->
      </div>
    </div>
  </section>

  <!-- =========================================================================
       SECTION 9: GOOGLE MAPS & FANPAGE FACEBOOK NGOÀI TRANG CHỦ
       ========================================================================= -->
  <section id="lien-he" class="py-10 sm:py-14 bg-brand-bgSoft border-t border-slate-200/80">
    <div class="site-container">
      <div class="text-center mb-8">
        <h2 class="flatsome-heading text-lg sm:text-2xl font-extrabold uppercase text-brand-navy">
          Bản Đồ Chỉ Đường &amp; Kết Nối Fanpage
        </h2>
        <p class="mt-3 text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto">
          Trụ sở: Thửa đất số 633, tờ bản đồ số 43, Tổ dân phố Quang Châu, Phường Hòa Xuân, TP Đà Nẵng.
        </p>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 sm:gap-6 items-stretch">

        <!-- Cột trái: Google Map ngoài trang chủ -->
        <div class="lg:col-span-7 bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm flex flex-col">
          <div class="px-4 py-3 border-b border-slate-100 flex flex-wrap items-center justify-between gap-2">
            <h3 class="text-xs sm:text-sm font-bold text-brand-navy">
              Bản đồ trụ sở Công ty Xây Dựng 36 – Hòa Xuân, Đà Nẵng
            </h3>
            <a
              href="https://www.google.com/maps/search/?api=1&query=Quang+Ch%C3%A2u,+H%C3%B2a+Xu%C3%A2n,+%C4%90%C3%A0+N%E1%BA%B5ng"
              target="_blank"
              rel="noopener noreferrer"
              class="text-[11px] sm:text-xs font-semibold text-brand-gold hover:underline"
            >
              Mở Google Maps →
            </a>
          </div>
          <div class="w-full h-72 sm:h-80 lg:flex-1 min-h-[300px]">
            <iframe
              title="Bản đồ Công ty TNHH Tư vấn Kỹ thuật Xây dựng 36 tại Quang Châu, Hòa Xuân, Đà Nẵng"
              src="https://maps.google.com/maps?q=Quang+Chau,+Hoa+Xuan,+Da+Nang,+Vietnam&t=&z=15&ie=UTF8&iwloc=&output=embed"
              class="w-full h-full border-0"
              loading="lazy"
              referrerpolicy="no-referrer-when-downgrade"
              allowfullscreen
            ></iframe>
          </div>
        </div>

        <!-- Cột phải: Fanpage Facebook ngoài trang chủ -->
        <div class="lg:col-span-5 bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm flex flex-col">
          <div class="px-4 py-3 border-b border-slate-100 flex items-center justify-between">
            <h3 class="text-xs sm:text-sm font-bold text-brand-navy">
              Fanpage Facebook Chính Thức
            </h3>
            <span class="text-[11px] font-semibold text-blue-600">Facebook</span>
          </div>

          <!-- Thẻ Fanpage chuẩn hiển thị đẹp trên mọi trình duyệt (không lỗi chặn iframe) -->
          <div class="p-4 flex-1 flex flex-col justify-between">
            <div class="rounded-xl overflow-hidden border border-slate-200">
              <!-- Ảnh bìa Fanpage -->
              <div class="relative h-32 sm:h-36 bg-brand-navy">
                <img
                  src="https://drive.google.com/thumbnail?id=1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_&sz=w800"
                  onerror="handleDriveImgError(this, '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_')"
                  referrerpolicy="no-referrer"
                  alt="Ảnh bìa Fanpage Xây Dựng 36"
                  class="w-full h-full object-cover opacity-80"
                />
                <div class="absolute inset-0 bg-gradient-to-t from-black/75 via-black/30 to-transparent"></div>
                <div class="absolute bottom-3 left-3 right-3 flex items-center gap-3">
                  <!-- Avatar Logo công ty -->
                  <div class="w-12 h-12 rounded-lg bg-brand-navy border-2 border-white flex items-center justify-center shrink-0 shadow">
                    <span class="text-white font-extrabold text-base">36</span>
                  </div>
                  <div class="min-w-0 text-white">
                    <div class="text-xs sm:text-sm font-bold leading-snug">
                      Công Ty TNHH Tư Vấn Kỹ Thuật Xây Dựng 36
                    </div>
                    <div class="text-[11px] text-slate-200">
                      Thiết kế &amp; Thi công xây dựng Đà Nẵng
                    </div>
                  </div>
                </div>
              </div>

              <!-- Nội dung cập nhật mới trên Fanpage -->
              <div class="p-3.5 bg-slate-50 space-y-2.5 text-xs text-slate-700">
                <p class="leading-relaxed">
                  Cập nhật liên tục hình ảnh công trường thực tế, tiến độ thi công các dự án tại Hòa Xuân &amp; TP Đà Nẵng, bảng báo giá xây dựng trọn gói mới nhất.
                </p>
                <div class="flex flex-wrap items-center gap-2 pt-1">
                  <a
                    href="https://www.facebook.com/"
                    target="_blank"
                    rel="noopener noreferrer"
                    class="inline-flex items-center gap-1.5 px-3.5 py-2 rounded-lg bg-[#1877F2] hover:bg-[#166FE5] text-white text-xs font-semibold transition-colors"
                  >
                    <svg class="w-3.5 h-3.5 fill-current" viewBox="0 0 24 24"><path d="M22.675 0h-21.35C.597 0 0 .597 0 1.326v21.348C0 23.403.597 24 1.326 24H12.82v-9.294H9.692v-3.622h3.128V8.413c0-3.1 1.893-4.788 4.659-4.788 1.325 0 2.463.099 2.795.143v3.24l-1.918.001c-1.504 0-1.795.715-1.795 1.763v2.313h3.587l-.467 3.622h-3.12V24h6.116c.73 0 1.323-.597 1.323-1.326V1.326C24 .597 23.403 0 22.675 0z"/></svg>
                    <span>Theo dõi Fanpage</span>
                  </a>
                  <a
                    href="https://zalo.me/0934280484"
                    target="_blank"
                    rel="noopener noreferrer"
                    class="inline-flex items-center gap-1.5 px-3.5 py-2 rounded-lg bg-brand-navy hover:bg-brand-navyLight text-white text-xs font-semibold transition-colors"
                  >
                    <span>Nhắn tin Zalo</span>
                  </a>
                </div>
              </div>
            </div>

            <!-- Thông tin liên hệ nhanh dưới Fanpage -->
            <div class="mt-4 pt-3 border-t border-slate-100 text-xs text-slate-600 space-y-1.5">
              <div><strong class="text-brand-navy">Địa chỉ:</strong> Thửa đất số 633, tờ bản đồ số 43, Tổ dân phố Quang Châu, Phường Hòa Xuân, TP Đà Nẵng</div>
              <div><strong class="text-brand-navy">Hotline:</strong> <a href="tel:0934280484" class="text-brand-gold font-bold">0934.280.484</a> &nbsp;|&nbsp; <strong class="text-brand-navy">Website:</strong> xaydung36.com</div>
            </div>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- =========================================================================
       FOOTER CHUYÊN NGHIỆP (PHONG CÁCH FLATSOME ĐỒNG BỘ MÀU LOGO)
       ========================================================================= -->
  <footer class="bg-brand-navyDark text-slate-300 pt-10 pb-20 sm:pb-8 border-t-4 border-brand-gold">
    <div class="site-container">
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-7 pb-8 border-b border-white/10">

        <!-- Cột 1: Thông tin doanh nghiệp -->
        <div class="sm:col-span-2 lg:col-span-1">
          <div class="flex items-center gap-2.5 mb-3">
            <svg class="w-9 h-9 shrink-0" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
              <rect x="2" y="2" width="60" height="60" rx="12" fill="#0F2C59" stroke="#E08E0B" stroke-width="2"/>
              <path d="M12 46V25L32 12L52 25V46" stroke="#E08E0B" stroke-width="3.5" stroke-linejoin="round"/>
              <text x="32" y="42" text-anchor="middle" font-family="Inter, Arial, sans-serif" font-weight="800" font-size="20" fill="#FFFFFF">36</text>
            </svg>
            <div>
              <div class="text-sm font-extrabold text-white leading-tight">XÂY DỰNG 36</div>
              <div class="text-[10px] text-brand-goldLight uppercase font-semibold">xaydung36.com</div>
            </div>
          </div>
          <p class="text-xs leading-relaxed text-slate-300 mb-3">
            <strong>CÔNG TY TNHH TƯ VẤN KỸ THUẬT XÂY DỰNG 36</strong> – Chuyên tư vấn kỹ thuật, thiết kế kiến trúc và thi công xây dựng chuyên nghiệp tại TP Đà Nẵng.
          </p>
          <ul class="text-xs space-y-1.5 text-slate-300">
            <li><strong class="text-white">MST:</strong> 0402187735</li>
            <li><strong class="text-white">Địa chỉ:</strong> Thửa đất số 633, tờ bản đồ số 43, Tổ dân phố Quang Châu, Phường Hòa Xuân, TP Đà Nẵng</li>
            <li><strong class="text-white">Hotline:</strong> <a href="tel:0934280484" class="text-brand-goldLight font-bold hover:underline">0934.280.484</a></li>
            <li><strong class="text-white">Website:</strong> xaydung36.com</li>
          </ul>
        </div>

        <!-- Cột 2: Lĩnh vực hoạt động -->
        <div>
          <h4 class="text-xs sm:text-sm font-bold text-white uppercase tracking-wider mb-3 pb-2 border-b border-white/10">
            Lĩnh Vực Hoạt Động
          </h4>
          <ul class="space-y-2 text-xs">
            <li><a href="#dich-vu" class="hover:text-brand-goldLight transition-colors">Thiết kế Kiến trúc – Nội thất</a></li>
            <li><a href="#dich-vu" class="hover:text-brand-goldLight transition-colors">Thi công phần thô chuẩn kỹ thuật</a></li>
            <li><a href="#dich-vu" class="hover:text-brand-goldLight transition-colors">Thi công hoàn thiện trọn gói</a></li>
            <li><a href="#dich-vu" class="hover:text-brand-goldLight transition-colors">Tư vấn giám sát thi công xây dựng</a></li>
            <li><a href="#dich-vu" class="hover:text-brand-goldLight transition-colors">Khảo sát, lập &amp; thẩm tra dự toán</a></li>
          </ul>
        </div>

        <!-- Cột 3: Danh mục công trình -->
        <div>
          <h4 class="text-xs sm:text-sm font-bold text-white uppercase tracking-wider mb-3 pb-2 border-b border-white/10">
            Danh Mục Công Trình
          </h4>
          <ul class="space-y-2 text-xs">
            <li><a href="#cong-trinh-thuc-te" onclick="filterProjects('nha-pho')" class="hover:text-brand-goldLight transition-colors">Thi công Nhà phố hiện đại</a></li>
            <li><a href="#cong-trinh-thuc-te" onclick="filterProjects('biet-thu')" class="hover:text-brand-goldLight transition-colors">Thiết kế &amp; Xây dựng Biệt thự</a></li>
            <li><a href="#cong-trinh-thuc-te" onclick="filterProjects('khach-san-can-ho')" class="hover:text-brand-goldLight transition-colors">Khách sạn – Căn hộ – Phòng trọ</a></li>
            <li><a href="#cong-trinh-thuc-te" onclick="filterProjects('van-phong')" class="hover:text-brand-goldLight transition-colors">Văn phòng &amp; Hạ tầng kỹ thuật</a></li>
            <li><a href="#du-an-da-nang" class="hover:text-brand-goldLight transition-colors">Dự án tiêu biểu tại Đà Nẵng</a></li>
          </ul>
        </div>

        <!-- Cột 4: Hỗ trợ khách hàng -->
        <div>
          <h4 class="text-xs sm:text-sm font-bold text-white uppercase tracking-wider mb-3 pb-2 border-b border-white/10">
            Hỗ Trợ Khách Hàng
          </h4>
          <ul class="space-y-2 text-xs">
            <li><a href="#bao-gia" class="hover:text-brand-goldLight transition-colors">Báo giá thiết kế kiến trúc</a></li>
            <li><a href="#bao-gia" class="hover:text-brand-goldLight transition-colors">Báo giá thi công phần thô</a></li>
            <li><a href="#bao-gia" class="hover:text-brand-goldLight transition-colors">Báo giá thi công hoàn thiện</a></li>
            <li><a href="#tin-tuc" class="hover:text-brand-goldLight transition-colors">Cẩm nang &amp; Tin tức xây dựng</a></li>
            <li><a href="#lien-he" class="hover:text-brand-goldLight transition-colors">Bản đồ &amp; Thông tin liên hệ</a></li>
          </ul>
        </div>

      </div>

      <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-[11px] sm:text-xs text-slate-400 text-center sm:text-left">
        <div>Copyright © 2026 <strong>CÔNG TY TNHH TƯ VẤN KỸ THUẬT XÂY DỰNG 36</strong>. All rights reserved.</div>
        <div>Website: <a href="https://xaydung36.com" class="text-brand-goldLight hover:underline">xaydung36.com</a></div>
      </div>
    </div>
  </footer>

  <!-- =========================================================================
       CÁC NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE
       TƯƠNG THÍCH MƯỢT MÀ TRÊN CẢ MÁY TÍNH VÀ ĐIỆN THOẠI, KHÔNG TRÀN VIỀN
       ========================================================================= -->
  <!-- Cột nút nổi góc dưới bên phải trên Máy tính & Tablet -->
  <div class="hidden sm:flex fixed right-4 bottom-6 z-50 flex-col gap-2.5">
    <!-- Zalo -->
    <a
      href="https://zalo.me/0934280484"
      target="_blank"
      rel="noopener noreferrer"
      class="flex items-center gap-2 pl-3 pr-4 py-2 rounded-full bg-[#0068FF] hover:bg-[#0055D4] text-white shadow-lg transition-transform hover:scale-105"
      aria-label="Chat Zalo 0934.280.484"
    >
      <span class="w-6 h-6 rounded-full bg-white text-[#0068FF] font-extrabold text-[11px] flex items-center justify-center">Zalo</span>
      <span class="text-xs font-bold whitespace-nowrap">Chat Zalo</span>
    </a>

    <!-- Facebook -->
    <a
      href="https://www.facebook.com/"
      target="_blank"
      rel="noopener noreferrer"
      class="flex items-center gap-2 pl-3 pr-4 py-2 rounded-full bg-[#1877F2] hover:bg-[#1464CC] text-white shadow-lg transition-transform hover:scale-105"
      aria-label="Fanpage Facebook Xây Dựng 36"
    >
      <span class="w-6 h-6 rounded-full bg-white text-[#1877F2] flex items-center justify-center">
        <svg class="w-3.5 h-3.5 fill-current" viewBox="0 0 24 24"><path d="M22.675 0h-21.35C.597 0 0 .597 0 1.326v21.348C0 23.403.597 24 1.326 24H12.82v-9.294H9.692v-3.622h3.128V8.413c0-3.1 1.893-4.788 4.659-4.788 1.325 0 2.463.099 2.795.143v3.24l-1.918.001c-1.504 0-1.795.715-1.795 1.763v2.313h3.587l-.467 3.622h-3.12V24h6.116c.73 0 1.323-.597 1.323-1.326V1.326C24 .597 23.403 0 22.675 0z"/></svg>
      </span>
      <span class="text-xs font-bold whitespace-nowrap">Facebook</span>
    </a>

    <!-- Hotline -->
    <a
      href="tel:0934280484"
      class="hotline-pulse flex items-center gap-2 pl-3 pr-4 py-2 rounded-full bg-brand-gold hover:bg-brand-goldLight text-white shadow-lg transition-transform hover:scale-105"
      aria-label="Gọi Hotline 0934.280.484"
    >
      <span class="w-6 h-6 rounded-full bg-white text-brand-gold flex items-center justify-center">
        <svg class="w-3.5 h-3.5" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
      </span>
      <span class="text-xs font-bold whitespace-nowrap">0934.280.484</span>
    </a>
  </div>

  <!-- Thanh liên hệ cố định dưới đáy trên Điện thoại (3 nút đều nhau, dễ chạm) -->
  <div class="sm:hidden fixed bottom-0 left-0 right-0 z-50 bg-white/95 backdrop-blur border-t border-slate-200 px-2 py-2 grid grid-cols-3 gap-2 shadow-[0_-4px_12px_rgba(0,0,0,0.08)]">
    <a
      href="https://zalo.me/0934280484"
      target="_blank"
      rel="noopener noreferrer"
      class="flex items-center justify-center gap-1.5 py-2 rounded-lg bg-[#0068FF] text-white text-xs font-bold"
    >
      <span>Zalo</span>
    </a>
    <a
      href="https://www.facebook.com/"
      target="_blank"
      rel="noopener noreferrer"
      class="flex items-center justify-center gap-1.5 py-2 rounded-lg bg-[#1877F2] text-white text-xs font-bold"
    >
      <span>Facebook</span>
    </a>
    <a
      href="tel:0934280484"
      class="flex items-center justify-center gap-1.5 py-2 rounded-lg bg-brand-gold text-white text-xs font-bold"
    >
      <span>Gọi Hotline</span>
    </a>
  </div>

  <!-- =========================================================================
       MODAL XEM CHI TIẾT ẢNH CÔNG TRÌNH & ĐỌC BÀI VIẾT
       ========================================================================= -->
  <div id="detail-modal" class="hidden fixed inset-0 z-50 bg-black/75 backdrop-blur-sm flex items-center justify-center p-4" onclick="closeDetailModal(event)">
    <div class="bg-white rounded-xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl relative" onclick="event.stopPropagation()">
      <button type="button" onclick="closeDetailModal()" aria-label="Đóng cửa sổ" class="absolute top-3 right-3 z-10 w-8 h-8 rounded-full bg-black/60 hover:bg-brand-gold text-white flex items-center justify-center">
        <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12"/></svg>
      </button>
      <div class="w-full bg-slate-100">
        <img id="modal-img" src="" alt="" referrerpolicy="no-referrer" class="w-full max-h-[55vh] object-contain bg-slate-900" />
      </div>
      <div class="p-4 sm:p-6">
        <h3 id="modal-title" class="text-base sm:text-lg font-extrabold text-brand-navy leading-snug"></h3>
        <p id="modal-meta" class="text-xs font-semibold text-brand-gold mt-1"></p>
        <p id="modal-desc" class="text-xs sm:text-sm text-slate-700 leading-relaxed mt-3"></p>
        <div class="mt-5 flex flex-wrap gap-2.5">
          <a href="#bao-gia" onclick="closeDetailModal()" class="px-4 py-2 rounded-lg bg-brand-navy hover:bg-brand-navyLight text-white text-xs font-bold">
            Yêu cầu tư vấn hạng mục này
          </a>
          <a href="tel:0934280484" class="px-4 py-2 rounded-lg bg-brand-gold hover:bg-brand-goldLight text-white text-xs font-bold">
            Hotline: 0934.280.484
          </a>
        </div>
      </div>
    </div>
  </div>

  <!-- =========================================================================
       JAVASCRIPT: QUẢN LÝ SLIDER, ẢNH GOOGLE DRIVE, BỘ LỌC DANH MỤC & FORM
       ========================================================================= -->
  <script>
    /**
     * Hàm dự phòng khi tải ảnh từ Google Drive:
     * Bước 1: Thử đường dẫn thumbnail độ phân giải cao.
     * Bước 2: Chuyển sang lh3.googleusercontent.com/d/{ID} nếu bị giới hạn.
     * Bước 3: Chuyển sang ảnh placeholder đồng bộ màu thương hiệu nếu link Drive chưa mở công khai.
     */
    function handleDriveImgError(imgEl, driveId) {
      const attempt = parseInt(imgEl.getAttribute('data-attempt') || '0', 10);
      if (attempt === 0 && driveId) {
        imgEl.setAttribute('data-attempt', '1');
        imgEl.src = 'https://lh3.googleusercontent.com/d/' + driveId + '=w1000';
      } else if (attempt === 1) {
        imgEl.setAttribute('data-attempt', '2');
        imgEl.src = 'https://placehold.co/800x600/0F2C59/FFFFFF?text=Xay+Dung+36+-+Da+Nang';
      }
    }

    function driveThumb(id) {
      return 'https://drive.google.com/thumbnail?id=' + id + '&sz=w900';
    }

    /* =========================================================================
       DỮ LIỆU 9 ẢNH THỰC TẾ THI CÔNG XÂY DỰNG (TỪ LINK GOOGLE DRIVE CỦA BẠN)
       ========================================================================= */
    const constructionProducts = [
      {
        id: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
        category: 'nha-pho',
        categoryLabel: 'Nhà phố',
        title: 'Thi công phần thô và kết cấu bê tông cốt thép nhà phố',
        location: 'Hòa Xuân, TP Đà Nẵng',
        desc: 'Triển khai thi công hệ khung kết cấu móng, cột, dầm sàn bê tông cốt thép theo đúng bản vẽ kỹ thuật, đảm bảo độ bền vững và tiến độ cam kết.'
      },
      {
        id: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
        category: 'nha-pho',
        categoryLabel: 'Nhà phố',
        title: 'Hoàn thiện mặt tiền và kiến trúc nhà phố hiện đại',
        location: 'Cẩm Lệ, TP Đà Nẵng',
        desc: 'Thi công hoàn thiện mặt đứng, hệ cửa nhôm kính và vật liệu ốp lát hiện đại, tối ưu ánh sáng tự nhiên và khả năng chống thấm bền bỉ.'
      },
      {
        id: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
        category: 'biet-thu',
        categoryLabel: 'Biệt thự',
        title: 'Thi công cốt thép sàn và hệ dầm chịu lực công trình biệt thự',
        location: 'Nam Hòa Xuân, TP Đà Nẵng',
        desc: 'Gia công lắp dựng cốt thép đúng tiêu chuẩn kỹ thuật, kiểm tra lớp bảo vệ bê tông và nghiệm thu chặt chẽ trước khi đổ bê tông thương phẩm.'
      },
      {
        id: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
        category: 'khach-san-can-ho',
        categoryLabel: 'Khách sạn – Căn hộ – Phòng trọ',
        title: 'Thi công xây tô hoàn thiện công trình căn hộ cho thuê',
        location: 'Ngũ Hành Sơn, TP Đà Nẵng',
        desc: 'Thi công xây tường bao, vách ngăn chuẩn thẳng đứng, trát tường phẳng mịn và đi âm hệ thống điện nước đồng bộ cho căn hộ dịch vụ.'
      },
      {
        id: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
        category: 'van-phong',
        categoryLabel: 'Văn phòng – Hạ tầng',
        title: 'Tư vấn giám sát và thi công hạ tầng kỹ thuật công trình',
        location: 'TP Đà Nẵng',
        desc: 'Kỹ sư Xây Dựng 36 trực tiếp giám sát chất lượng vật tư, cao độ trắc đạc và quy trình thi công an toàn tại hiện trường.'
      },
      {
        id: '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t',
        category: 'biet-thu',
        categoryLabel: 'Biệt thự',
        title: 'Thi công hoàn thiện trọn gói biệt thự hai mặt tiền',
        location: 'Hải Châu, TP Đà Nẵng',
        desc: 'Gói thi công chìa khóa trao tay bao gồm phần thô, sơn bả ngoại thất cao cấp, trần thạch cao và hoàn thiện cảnh quan sân vườn.'
      },
      {
        id: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
        category: 'khach-san-can-ho',
        categoryLabel: 'Khách sạn – Căn hộ – Phòng trọ',
        title: 'Thi công hoàn thiện khách sạn và căn hộ dịch vụ cao tầng',
        location: 'Sơn Trà, TP Đà Nẵng',
        desc: 'Thi công đồng bộ kết cấu cao tầng, hệ thống PCCC, cấp thoát nước và hoàn thiện nội thất tiêu chuẩn lưu trú du lịch.'
      },
      {
        id: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
        category: 'nha-pho',
        categoryLabel: 'Nhà phố',
        title: 'Thi công hoàn thiện nội thất và hạng mục cơ điện MEP',
        location: 'Thanh Khê, TP Đà Nẵng',
        desc: 'Lắp đặt hệ thống chiếu sáng, thiết bị điện nước an toàn, ốp lát gạch men cao cấp mang lại không gian sống tiện nghi.'
      },
      {
        id: '1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn',
        category: 'van-phong',
        categoryLabel: 'Văn phòng – Hạ tầng',
        title: 'Cải tạo nâng cấp và thi công hoàn thiện văn phòng làm việc',
        location: 'Liên Chiểu, TP Đà Nẵng',
        desc: 'Thiết kế và thi công cải tạo không gian văn phòng hiện đại, tối ưu công năng làm việc, cách âm tốt và tiến độ bàn giao nhanh chóng.'
      }
    ];

    /* =========================================================================
       DỮ LIỆU 10 DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (TỪ LINK GOOGLE DRIVE CỦA BẠN)
       ========================================================================= */
    const daNangProjects = [
      {
        id: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
        title: 'Dự án Nhà phố Khu đô thị Hòa Xuân – Cẩm Lệ',
        location: 'Phường Hòa Xuân, TP Đà Nẵng',
        desc: 'Thiết kế kiến trúc và thi công trọn gói nhà phố 3 tầng hiện đại tại Khu đô thị Hòa Xuân, tối ưu thông gió tự nhiên và ánh sáng.'
      },
      {
        id: '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff',
        title: 'Dự án Biệt thự ven sông Nam Hòa Xuân',
        location: 'Nam Hòa Xuân, TP Đà Nẵng',
        desc: 'Công trình biệt thự sân vườn với kết cấu kiên cố, hoàn thiện mặt tiền sang trọng và hệ vật liệu cao cấp bền vững với khí hậu miền Trung.'
      },
      {
        id: '1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz',
        title: 'Dự án Căn hộ dịch vụ Quận Ngũ Hành Sơn',
        location: 'Ngũ Hành Sơn, TP Đà Nẵng',
        desc: 'Thi công phần thô và hoàn thiện tòa nhà căn hộ cho thuê gần biển Mỹ Khê, đáp ứng tiêu chuẩn kỹ thuật và thẩm mỹ hiện đại.'
      },
      {
        id: '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k',
        title: 'Dự án Nhà ở kết hợp kinh doanh Quận Hải Châu',
        location: 'Hải Châu, TP Đà Nẵng',
        desc: 'Thiết kế không gian thương mại tầng trệt kết hợp nhà ở tiện nghi các tầng trên, thi công đảm bảo an toàn khu dân cư trung tâm.'
      },
      {
        id: '1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N',
        title: 'Dự án Khách sạn mini & Homestay Sơn Trà',
        location: 'Sơn Trà, TP Đà Nẵng',
        desc: 'Thi công trọn gói công trình lưu trú du lịch với kiến trúc trẻ trung, tối ưu số lượng phòng và chi phí đầu tư hiệu quả.'
      },
      {
        id: '1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML',
        title: 'Dự án Nhà phố hiện đại Quận Thanh Khê',
        location: 'Thanh Khê, TP Đà Nẵng',
        desc: 'Cải tạo và xây mới nhà phố liền kề với giải pháp chống nóng, chống thấm triệt để và bố trí công năng khoa học.'
      },
      {
        id: '1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF',
        title: 'Dự án Văn phòng & Showroom Quận Liên Chiểu',
        location: 'Liên Chiểu, TP Đà Nẵng',
        desc: 'Tư vấn thiết kế kết cấu, thẩm tra dự toán và thi công hoàn thiện trụ sở văn phòng kết hợp khu trưng bày sản phẩm.'
      },
      {
        id: '1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A',
        title: 'Dự án Nhà phố Khu đô thị Phước Lý – Đà Nẵng',
        location: 'KĐT Phước Lý, TP Đà Nẵng',
        desc: 'Thi công phần thô và nhân công hoàn thiện nhà phố 3 tầng, nghiệm thu chuẩn xác từng giai đoạn móng, dầm, sàn, mái.'
      },
      {
        id: '1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80',
        title: 'Dự án Công trình dân dụng & Hạ tầng Hòa Vang',
        location: 'Hòa Vang, TP Đà Nẵng',
        desc: 'Tư vấn giám sát kỹ thuật và triển khai thi công hạng mục công trình dân dụng kết hợp hạ tầng cấp thoát nước đồng bộ.'
      },
      {
        id: '1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4',
        title: 'Dự án Nhà phố Quang Châu – Phường Hòa Xuân',
        location: 'Quang Châu, Hòa Xuân, TP Đà Nẵng',
        desc: 'Công trình nhà ở gia đình tiêu chuẩn chất lượng cao do Công ty TNHH Tư vấn Kỹ thuật Xây dựng 36 trực tiếp thiết kế và thi công.'
      }
    ];

    /* =========================================================================
       DỮ LIỆU BÀI VIẾT CHUYÊN MÔN TRANG CHỦ
       ========================================================================= */
    const articlesData = [
      {
        imgId: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
        title: 'Hướng dẫn bảo dưỡng bê tông móng đúng chuẩn kỹ thuật xây dựng',
        date: 'Kỹ thuật thi công',
        excerpt: 'Quy trình giữ ẩm, che chắn và thời gian bảo dưỡng bê tông sau khi đổ giúp kết cấu móng đạt cường độ tối đa, hạn chế rạn nứt bề mặt.',
        fullContent: 'Bảo dưỡng bê tông móng là công đoạn bắt buộc nhằm đảm bảo quá trình thủy hóa xi măng diễn ra hoàn toàn. Trong 7 ngày đầu sau khi đổ bê tông, cần duy trì độ ẩm liên tục bằng cách phủ bao tải ướt hoặc tưới nước phun sương định kỳ, tránh ánh nắng trực tiếp và hạn chế tác động rung chấn mạnh lên kết cấu.'
      },
      {
        imgId: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
        title: 'Những lưu ý quan trọng khi chọn nhà thầu xây nhà trọn gói tại Đà Nẵng',
        date: 'Kinh nghiệm xây nhà',
        excerpt: 'Cách kiểm tra năng lực pháp lý, bảng dự toán vật tư chi tiết và điều khoản bảo hành để chủ đầu tư an tâm tuyệt đối khi khởi công.',
        fullContent: 'Khi lựa chọn nhà thầu xây dựng trọn gói tại Đà Nẵng, chủ đầu tư nên kiểm tra rõ giấy phép kinh doanh, chứng chỉ năng lực hoạt động xây dựng, công trình thực tế đã thi công và bảng chủng loại vật tư cam kết rõ ràng trong hợp đồng. Việc có kỹ sư giám sát độc lập hoặc quy trình nghiệm thu từng giai đoạn sẽ đảm bảo chất lượng công trình bền vững.'
      },
      {
        imgId: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
        title: 'Vai trò của tư vấn giám sát kỹ thuật đối với chất lượng công trình',
        date: 'Tư vấn kỹ thuật',
        excerpt: 'Kỹ sư tư vấn giám sát giúp kiểm soát vật liệu đầu vào, nghiệm thu cốt thép, kiểm tra sai số kích thước và tối ưu tiến độ thi công.',
        fullContent: 'Tư vấn giám sát thi công đóng vai trò đại diện chủ đầu tư kiểm tra tính tuân thủ bản vẽ thiết kế, tiêu chuẩn xây dựng Việt Nam (TCVN) và an toàn lao động. Nhờ đó, mọi sai sót về kết cấu, chống thấm hay điện nước đều được phát hiện và xử lý kịp thời trước khi hoàn thiện.'
      },
      {
        imgId: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
        title: 'Kinh nghiệm dự toán chi phí thi công phần thô và hoàn thiện hiệu quả',
        date: 'Dự toán & Báo giá',
        excerpt: 'Phân biệt rõ hạng mục phần thô và hoàn thiện giúp gia chủ chủ động kế hoạch tài chính, kiểm soát tốt phát sinh trong suốt quá trình xây dựng.',
        fullContent: 'Một bảng dự toán xây dựng khoa học cần tách bạch rõ chi phí thiết kế, chi phí thi công phần thô (móng, khung kết cấu, xây tô, đi âm điện nước) và chi phí vật tư hoàn thiện (gạch ốp lát, sơn nước, cửa, thiết bị vệ sinh). Chủ đầu tư nên dự phòng khoảng 5–10% ngân sách để linh hoạt khi có nhu cầu nâng cấp vật liệu hoàn thiện.'
      }
    ];

    /* =========================================================================
       RENDER DANH SÁCH CÔNG TRÌNH THỰC TẾ (9 ẢNH GOOGLE DRIVE - KHÔNG NHÃN DÁN)
       ========================================================================= */
    function renderConstructionGrid(filterCat = 'all') {
      const container = document.getElementById('construction-grid');
      if (!container) return;

      const list = filterCat === 'all'
        ? constructionProducts
        : constructionProducts.filter(item => item.category === filterCat);

      container.innerHTML = list.map((item, idx) => `
        <article
          onclick="openDetailModal('${item.id}', ${JSON.stringify(item.title).replace(/"/g, '&quot;')}, ${JSON.stringify(item.categoryLabel + ' • ' + item.location).replace(/"/g, '&quot;')}, ${JSON.stringify(item.desc).replace(/"/g, '&quot;')})"
          class="group cursor-pointer bg-white rounded-xl overflow-hidden border border-slate-200 hover:border-brand-gold/70 hover:shadow-md transition-all flex flex-col"
        >
          <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
            <img
              src="${driveThumb(item.id)}"
              onerror="handleDriveImgError(this, '${item.id}')"
              referrerpolicy="no-referrer"
              loading="lazy"
              alt="${item.title}"
              class="w-full h-full object-cover card-img-zoom"
            />
          </div>
          <div class="p-2.5 sm:p-4 flex-1 flex flex-col justify-between">
            <h3 class="text-xs sm:text-sm font-bold text-brand-navy group-hover:text-brand-gold transition-colors leading-snug break-words">
              ${item.title}
            </h3>
            <p class="mt-1.5 text-[11px] sm:text-xs text-slate-500 break-words">
              ${item.location}
            </p>
          </div>
        </article>
      `).join('');
    }

    function filterProjects(cat) {
      renderConstructionGrid(cat);
      const buttons = document.querySelectorAll('.project-tab');
      buttons.forEach(btn => {
        if (btn.getAttribute('data-cat') === cat) {
          btn.classList.remove('bg-slate-100', 'text-slate-700');
          btn.classList.add('bg-brand-navy', 'text-white');
        } else {
          btn.classList.remove('bg-brand-navy', 'text-white');
          btn.classList.add('bg-slate-100', 'text-slate-700');
        }
      });
    }

    /* =========================================================================
       RENDER 10 DỰ ÁN TẠI ĐÀ NẴNG (KHÔNG NHÃN DÁN, KHÔNG CẮT TÊN SẢN PHẨM)
       ========================================================================= */
    function renderDaNangProjects() {
      const container = document.getElementById('danang-projects-grid');
      if (!container) return;

      container.innerHTML = daNangProjects.map(item => `
        <article
          onclick="openDetailModal('${item.id}', ${JSON.stringify(item.title).replace(/"/g, '&quot;')}, ${JSON.stringify(item.location).replace(/"/g, '&quot;')}, ${JSON.stringify(item.desc).replace(/"/g, '&quot;')})"
          class="group cursor-pointer bg-white rounded-xl overflow-hidden border border-slate-200 hover:border-brand-gold/70 hover:shadow-md transition-all flex flex-col"
        >
          <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
            <img
              src="${driveThumb(item.id)}"
              onerror="handleDriveImgError(this, '${item.id}')"
              referrerpolicy="no-referrer"
              loading="lazy"
              alt="${item.title}"
              class="w-full h-full object-cover card-img-zoom"
            />
          </div>
          <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
            <h3 class="text-xs sm:text-[13px] font-bold text-brand-navy group-hover:text-brand-gold transition-colors leading-snug break-words">
              ${item.title}
            </h3>
            <p class="mt-1 text-[11px] text-slate-500 break-words">
              ${item.location}
            </p>
          </div>
        </article>
      `).join('');
    }

    /* =========================================================================
       RENDER BÀI VIẾT TRANG CHỦ
       ========================================================================= */
    function renderArticles() {
      const container = document.getElementById('articles-grid');
      if (!container) return;

      container.innerHTML = articlesData.map(post => `
        <article
          onclick="openDetailModal('${post.imgId}', ${JSON.stringify(post.title).replace(/"/g, '&quot;')}, ${JSON.stringify(post.date + ' • Xây Dựng 36').replace(/"/g, '&quot;')}, ${JSON.stringify(post.fullContent).replace(/"/g, '&quot;')})"
          class="group cursor-pointer bg-white rounded-xl overflow-hidden border border-slate-200 hover:border-brand-gold/70 hover:shadow-md transition-all flex flex-col"
        >
          <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
            <img
              src="${driveThumb(post.imgId)}"
              onerror="handleDriveImgError(this, '${post.imgId}')"
              referrerpolicy="no-referrer"
              loading="lazy"
              alt="${post.title}"
              class="w-full h-full object-cover card-img-zoom"
            />
          </div>
          <div class="p-3 sm:p-4 flex-1 flex flex-col">
            <h3 class="text-xs sm:text-sm font-bold text-brand-navy group-hover:text-brand-gold transition-colors leading-snug break-words">
              ${post.title}
            </h3>
            <p class="mt-2 text-[11px] sm:text-xs text-slate-600 leading-relaxed flex-1">
              ${post.excerpt}
            </p>
            <div class="mt-3 text-[11px] sm:text-xs font-semibold text-brand-gold">
              Xem chi tiết →
            </div>
          </div>
        </article>
      `).join('');
    }

    /* =========================================================================
       SLIDER 2 BANNER TỰ TRƯỢT CHUYÊN NGHIỆP
       ========================================================================= */
    let currentSlide = 0;
    const totalSlides = 2;
    let sliderTimer = null;

    function updateSlider() {
      const track = document.getElementById('hero-track');
      if (!track) return;
      track.style.transform = `translateX(-${currentSlide * 50}%)`;

      for (let i = 0; i < totalSlides; i++) {
        const dot = document.getElementById('dot-' + i);
        if (!dot) continue;
        if (i === currentSlide) {
          dot.classList.remove('w-2.5', 'bg-white/60');
          dot.classList.add('w-7', 'bg-brand-gold');
        } else {
          dot.classList.remove('w-7', 'bg-brand-gold');
          dot.classList.add('w-2.5', 'bg-white/60');
        }
      }
    }

    function nextSlide() {
      currentSlide = (currentSlide + 1) % totalSlides;
      updateSlider();
      resetSliderTimer();
    }

    function prevSlide() {
      currentSlide = (currentSlide - 1 + totalSlides) % totalSlides;
      updateSlider();
      resetSliderTimer();
    }

    function goToSlide(index) {
      currentSlide = index;
      updateSlider();
      resetSliderTimer();
    }

    function resetSliderTimer() {
      if (sliderTimer) clearInterval(sliderTimer);
      sliderTimer = setInterval(() => {
        currentSlide = (currentSlide + 1) % totalSlides;
        updateSlider();
      }, 5000);
    }

    /* Hỗ trợ vuốt cảm ứng trái/phải cho Banner trên điện thoại */
    let touchStartX = 0;
    const heroWrapper = document.querySelector('.hero-slider-wrapper');
    if (heroWrapper) {
      heroWrapper.addEventListener('touchstart', (e) => {
        touchStartX = e.changedTouches[0].screenX;
      }, { passive: true });
      heroWrapper.addEventListener('touchend', (e) => {
        const diff = e.changedTouches[0].screenX - touchStartX;
        if (Math.abs(diff) > 45) {
          if (diff < 0) nextSlide();
          else prevSlide();
        }
      }, { passive: true });
    }

    /* =========================================================================
       MENU MOBILE & MODAL CHI TIẾT
       ========================================================================= */
    const mobileMenuBtn = document.getElementById('mobile-menu-btn');
    const mobileMenuPanel = document.getElementById('mobile-menu-panel');
    const menuIconOpen = document.getElementById('menu-icon-open');
    const menuIconClose = document.getElementById('menu-icon-close');

    if (mobileMenuBtn) {
      mobileMenuBtn.addEventListener('click', () => {
        const isHidden = mobileMenuPanel.classList.contains('hidden');
        mobileMenuPanel.classList.toggle('hidden');
        menuIconOpen.classList.toggle('hidden', isHidden);
        menuIconClose.classList.toggle('hidden', !isHidden);
      });
    }

    function closeMobileMenu() {
      if (mobileMenuPanel) mobileMenuPanel.classList.add('hidden');
      if (menuIconOpen) menuIconOpen.classList.remove('hidden');
      if (menuIconClose) menuIconClose.classList.add('hidden');
    }

    function openDetailModal(driveId, title, meta, desc) {
      const modal = document.getElementById('detail-modal');
      const img = document.getElementById('modal-img');
      img.setAttribute('data-attempt', '0');
      img.onerror = function() { handleDriveImgError(this, driveId); };
      img.src = driveThumb(driveId);
      img.alt = title;

      document.getElementById('modal-title').textContent = title;
      document.getElementById('modal-meta').textContent = meta;
      document.getElementById('modal-desc').textContent = desc;
      modal.classList.remove('hidden');
      document.body.style.overflow = 'hidden';
    }

    function closeDetailModal() {
      const modal = document.getElementById('detail-modal');
      modal.classList.add('hidden');
      document.body.style.overflow = '';
    }

    /* =========================================================================
       XỬ LÝ FORM YÊU CẦU TƯ VẤN & BÁO GIÁ (KHÔNG DÙNG ALERT)
       ========================================================================= */
    function handleQuoteSubmit(event) {
      event.preventDefault();
      const form = event.target;
      const name = form.name.value.trim();
      const phone = form.phone.value.trim();
      const type = form.type.value;
      const feedback = document.getElementById('quote-feedback');

      if (!name || !phone) {
        feedback.textContent = 'Vui lòng nhập đầy đủ họ tên và số điện thoại để kỹ sư liên hệ tư vấn.';
        feedback.classList.remove('hidden', 'bg-emerald-50', 'border-emerald-200', 'text-emerald-800');
        feedback.classList.add('bg-amber-50', 'border-amber-200', 'text-amber-800');
        return;
      }

      feedback.textContent = `Cảm ơn ${name}! Yêu cầu báo giá hạng mục "${type}" của bạn đã được ghi nhận. Kỹ sư Xây Dựng 36 sẽ liên hệ qua số ${phone} trong thời gian sớm nhất.`;
      feedback.classList.remove('hidden', 'bg-amber-50', 'border-amber-200', 'text-amber-800');
      feedback.classList.add('bg-emerald-50', 'border-emerald-200', 'text-emerald-800');
      form.reset();
    }

    /* Khởi tạo toàn bộ nội dung khi tải trang */
    window.addEventListener('DOMContentLoaded', () => {
      renderConstructionGrid('all');
      renderDaNangProjects();
      renderArticles();
      updateSlider();
      resetSliderTimer();
    });
  </script>
</body>
</html>
