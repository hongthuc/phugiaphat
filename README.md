<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
  <title>Công Ty TNHH Tư Vấn Và Thiết Kế Xây Dựng Phú Gia Phát - phunggiaphat.com</title>
  <meta name="description" content="Công ty TNHH Tư vấn và Thiết kế Xây dựng Phú Gia Phát chuyên Thiết kế Kiến trúc - Thi công Xây dựng nhà trọn gói - Thi công Nội thất uy tín tại Sơn Trà, Đà Nẵng. Hotline: 0905 615 563.">
  <meta name="keywords" content="Phú Gia Phát, phunggiaphat.com, xây dựng Phú Gia Phát Đà Nẵng, thiết kế nhà đẹp Đà Nẵng, xây nhà trọn gói Đà Nẵng, 21 Mân Quang 8 Sơn Trà Đà Nẵng">
  <link rel="canonical" href="https://phunggiaphat.com/">

  <!-- Open Graph / Thumbnail là ảnh Logo công ty khi gửi link trang web qua Zalo, Facebook -->
  <meta property="og:type" content="website">
  <meta property="og:site_name" content="Xây Dựng Phú Gia Phát - phunggiaphat.com">
  <meta property="og:url" content="https://phunggiaphat.com/">
  <meta property="og:title" content="Công Ty TNHH Tư Vấn Và Thiết Kế Xây Dựng Phú Gia Phát | phunggiaphat.com">
  <meta property="og:description" content="Chuyên Tư vấn - Thiết kế Kiến trúc - Thi công Xây dựng trọn gói Nhà phố, Biệt thự, Căn hộ, Khách sạn tại Đà Nẵng. Địa chỉ: 21 Mân Quang 8, Sơn Trà, Đà Nẵng. ĐT: 0905 615 563.">
  <meta property="og:image" content="https://placehold.co/1200x630/0c2d57/f59e0b.png?text=PHU+GIA+PHAT+%7C+TU+VAN+THIET+KE+VA+XAY+DUNG+%7C+phunggiaphat.com">
  <meta property="og:image:width" content="1200">
  <meta property="og:image:height" content="630">
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:title" content="Công Ty TNHH Tư Vấn Và Thiết Kế Xây Dựng Phú Gia Phát">
  <meta name="twitter:description" content="Thiết kế & Thi công Xây dựng trọn gói tại Đà Nẵng - Hotline: 0905 615 563">
  <meta name="twitter:image" content="https://placehold.co/1200x630/0c2d57/f59e0b.png?text=PHU+GIA+PHAT+%7C+TU+VAN+THIET+KE+VA+XAY+DUNG">

  <!-- Google Fonts: Montserrat & Inter chuẩn Flatsome xây dựng -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Montserrat:wght@600;700;800&display=swap" rel="stylesheet">
  <!-- Font Awesome Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
  <!-- Tailwind CSS hỗ trợ tiện ích bổ sung -->
  <script src="https://cdn.tailwindcss.com"></script>

  <style>
    /* ==========================================================================
       CSS CHUẨN CẤU TRÚC FLATSOME THEME (DỄ DÀNG CHỈNH SỬA TRÊN UX BUILDER)
       Màu chủ đạo theo Logo Phú Gia Phát: Xanh Navy (#0c2d57) & Vàng Đồng (#d97706)
       ========================================================================== */
    :root {
      --primary-color: #0c2d57;
      --primary-light: #16437e;
      --secondary-color: #d97706;
      --secondary-light: #f59e0b;
      --text-color: #1e293b;
      --muted-color: #64748b;
      --bg-light: #f8fafc;
      --border-color: #e2e8f0;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    html, body {
      width: 100%;
      max-width: 100%;
      overflow-x: hidden;
      font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
      color: var(--text-color);
      background-color: #ffffff;
      scroll-behavior: smooth;
      -webkit-font-smoothing: antialiased;
    }

    h1, h2, h3, h4, .heading-font {
      font-family: 'Montserrat', sans-serif;
    }

    a {
      text-decoration: none;
      color: inherit;
      transition: all 0.25s ease;
    }

    img {
      max-width: 100%;
      height: auto;
      display: block;
    }

    /* Chiều ngang giao diện trên máy tính bằng 95% kích thước màn hình máy tính, không tràn viền */
    .container,
    .row {
      width: 100%;
      max-width: 95%;
      margin-left: auto;
      margin-right: auto;
      padding-left: 12px;
      padding-right: 12px;
    }

    @media (max-width: 767px) {
      .container,
      .row {
        max-width: 100%;
        padding-left: 12px;
        padding-right: 12px;
      }
    }

    .section {
      padding: 48px 0;
      position: relative;
      width: 100%;
      overflow: hidden;
    }

    @media (max-width: 767px) {
      .section {
        padding: 32px 0;
      }
    }

    /* ==========================================================================
       TOP BAR & HEADER FLATSOME (KHÔNG ĐỂ NÚT GỌI NGAY ĐỂ TRÁNH TRÀN VIỀN)
       ========================================================================== */
    .top-bar {
      background-color: var(--primary-color);
      color: #f1f5f9;
      font-size: 12.5px;
      padding: 7px 0;
      border-bottom: 1px solid rgba(255, 255, 255, 0.1);
    }

    .header-wrapper {
      background: #ffffff;
      position: sticky;
      top: 0;
      z-index: 999;
      box-shadow: 0 2px 15px rgba(12, 45, 87, 0.08);
      border-bottom: 2px solid var(--secondary-color);
      width: 100%;
    }

    .header-inner {
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 14px;
      padding: 8px 0;
      width: 100%;
    }

    /* Logo chỉnh gọn nhỏ lại, sắc nét */
    .logo-box {
      display: flex;
      align-items: center;
      gap: 8px;
      flex-shrink: 0;
    }

    .logo-svg-wrap {
      width: 40px;
      height: 40px;
      flex-shrink: 0;
    }

    .logo-text-wrap {
      display: flex;
      flex-direction: column;
      line-height: 1.15;
    }

    .logo-brand-name {
      font-family: 'Montserrat', sans-serif;
      font-weight: 800;
      font-size: 15px;
      color: var(--primary-color);
      letter-spacing: 0.3px;
      white-space: nowrap;
    }

    .logo-brand-sub {
      font-size: 9.5px;
      font-weight: 600;
      color: var(--secondary-color);
      text-transform: uppercase;
      letter-spacing: 0.4px;
      white-space: nowrap;
    }

    /* Danh mục trên máy tính: chữ nhỏ gọn, viết liền trên 1 hàng (white-space: nowrap),
       nằm trên cùng 1 hàng hoặc xuống hàng 2 nguyên cụm, tuyệt đối không gãy chữ */
    .desktop-nav {
      display: flex;
      align-items: center;
      justify-content: flex-end;
      flex-wrap: wrap;
      gap: 2px 4px;
      flex: 1;
      min-width: 0;
    }

    .nav-item {
      position: relative;
      list-style: none;
    }

    .nav-link {
      display: inline-flex;
      align-items: center;
      gap: 4px;
      padding: 7px 9px;
      font-family: 'Montserrat', sans-serif;
      font-size: 12px;
      font-weight: 700;
      color: var(--primary-color);
      text-transform: uppercase;
      white-space: nowrap;
      border-radius: 5px;
      transition: all 0.2s ease;
    }

    .nav-link:hover,
    .nav-link.active {
      color: #ffffff;
      background-color: var(--primary-color);
    }

    .nav-link i {
      font-size: 10px;
      color: var(--secondary-color);
    }

    .nav-link:hover i,
    .nav-link.active i {
      color: var(--secondary-light);
    }

    /* Dropdown menu chuẩn Flatsome */
    .nav-dropdown {
      position: absolute;
      top: 100%;
      left: 0;
      min-width: 230px;
      background: #ffffff;
      border-top: 3px solid var(--secondary-color);
      box-shadow: 0 10px 25px rgba(12, 45, 87, 0.15);
      border-radius: 0 0 8px 8px;
      padding: 6px 0;
      opacity: 0;
      visibility: hidden;
      transform: translateY(8px);
      transition: all 0.2s ease;
      z-index: 1000;
    }

    .nav-item:hover .nav-dropdown {
      opacity: 1;
      visibility: visible;
      transform: translateY(0);
    }

    .nav-dropdown a {
      display: block;
      padding: 8px 14px;
      font-size: 12.5px;
      font-weight: 600;
      color: var(--text-color);
      white-space: nowrap;
      border-bottom: 1px solid #f1f5f9;
    }

    .nav-dropdown a:last-child {
      border-bottom: none;
    }

    .nav-dropdown a:hover {
      background-color: #f8fafc;
      color: var(--secondary-color);
      padding-left: 18px;
    }

    /* Thanh danh mục nhanh trên điện thoại */
    .mobile-category-strip {
      display: none;
      background: #f8fafc;
      border-top: 1px solid #e2e8f0;
      padding: 6px 8px;
      overflow-x: auto;
      -webkit-overflow-scrolling: touch;
      scrollbar-width: none;
    }

    .mobile-category-strip::-webkit-scrollbar {
      display: none;
    }

    @media (max-width: 1023px) {
      .desktop-nav {
        display: none;
      }
      .mobile-category-strip {
        display: flex;
        gap: 6px;
      }
    }

    .mobile-cat-pill {
      display: inline-block;
      padding: 5px 10px;
      font-size: 11.5px;
      font-weight: 700;
      color: var(--primary-color);
      background: #ffffff;
      border: 1px solid #cbd5e1;
      border-radius: 999px;
      white-space: nowrap;
      flex-shrink: 0;
    }

    .mobile-cat-pill.active,
    .mobile-cat-pill:hover {
      background: var(--primary-color);
      color: #ffffff;
      border-color: var(--primary-color);
    }

    /* ==========================================================================
       2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU
       Chữ và hình nằm gọn trong banner, cách xa viền, không bị thiếu chữ
       ========================================================================== */
    .hero-slider-wrapper {
      position: relative;
      width: 100%;
      overflow: hidden;
      background-color: var(--primary-color);
    }

    .hero-slide {
      display: none;
      width: 100%;
      height: 460px; /* Kích thước cố định bằng nhau hoàn toàn trên máy tính */
      position: relative;
      overflow: hidden;
    }

    .hero-slide.active {
      display: flex;
      align-items: center;
      justify-content: center;
    }

    @media (max-width: 1023px) {
      .hero-slide {
        height: 360px;
      }
    }

    @media (max-width: 639px) {
      .hero-slide {
        height: 290px; /* Kích thước cố định bằng nhau hoàn toàn trên điện thoại */
      }
    }

    .hero-bg-img {
      position: absolute;
      inset: 0;
      width: 100%;
      height: 100%;
      object-fit: cover;
      object-position: center;
      filter: brightness(0.42);
      transform: scale(1.02);
      transition: transform 6s ease;
    }

    .hero-slide.active .hero-bg-img {
      transform: scale(1);
    }

    .hero-overlay {
      position: absolute;
      inset: 0;
      background: linear-gradient(90deg, rgba(12, 45, 87, 0.90) 0%, rgba(12, 45, 87, 0.72) 55%, rgba(12, 45, 87, 0.55) 100%);
    }

    /* Khung nội dung cách xa viền ảnh banner (safe zone rộng rãi) */
    .hero-safe-box {
      position: relative;
      z-index: 10;
      width: 100%;
      max-width: 88%;
      margin: 0 auto;
      padding: 28px 44px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 28px;
    }

    @media (max-width: 767px) {
      .hero-safe-box {
        max-width: 90%;
        padding: 18px 20px;
        flex-direction: column;
        text-align: center;
        justify-content: center;
        gap: 10px;
      }
    }

    .hero-text-col {
      flex: 1;
      color: #ffffff;
      max-width: 680px;
    }

    .hero-subtitle {
      display: inline-block;
      background: rgba(217, 119, 6, 0.95);
      color: #ffffff;
      font-size: 11.5px;
      font-weight: 700;
      text-transform: uppercase;
      padding: 4px 12px;
      border-radius: 4px;
      margin-bottom: 10px;
      letter-spacing: 0.5px;
    }

    .hero-title {
      font-size: 28px;
      font-weight: 800;
      line-height: 1.28;
      margin-bottom: 10px;
      color: #ffffff;
      text-shadow: 0 2px 8px rgba(0, 0, 0, 0.35);
    }

    .hero-desc {
      font-size: 14.5px;
      line-height: 1.55;
      color: #e2e8f0;
      margin-bottom: 16px;
    }

    @media (max-width: 1023px) {
      .hero-title {
        font-size: 22px;
      }
      .hero-desc {
        font-size: 13px;
      }
    }

    @media (max-width: 639px) {
      .hero-subtitle {
        font-size: 10px;
        padding: 3px 9px;
        margin-bottom: 6px;
      }
      .hero-title {
        font-size: 15.5px;
        line-height: 1.32;
        margin-bottom: 6px;
      }
      .hero-desc {
        font-size: 11.5px;
        line-height: 1.42;
        margin-bottom: 10px;
      }
    }

    /* Hình minh họa phụ nằm gọn trong banner trên máy tính */
    .hero-SideCard {
      width: 290px;
      height: 210px;
      border-radius: 10px;
      overflow: hidden;
      border: 3px solid var(--secondary-light);
      box-shadow: 0 12px 30px rgba(0, 0, 0, 0.4);
      flex-shrink: 0;
      background: #0c2d57;
    }

    .hero-SideCard img {
      width: 100%;
      height: 100%;
      object-fit: cover;
    }

    @media (max-width: 900px) {
      .hero-SideCard {
        display: none;
      }
    }

    .slider-btn {
      position: absolute;
      top: 50%;
      transform: translateY(-50%);
      z-index: 20;
      width: 36px;
      height: 36px;
      border-radius: 50%;
      background: rgba(255, 255, 255, 0.2);
      color: #ffffff;
      border: 1px solid rgba(255, 255, 255, 0.4);
      display: flex;
      align-items: center;
      justify-content: center;
      cursor: pointer;
      transition: all 0.2s ease;
    }

    .slider-btn:hover {
      background: var(--secondary-color);
      border-color: var(--secondary-color);
    }

    .slider-btn.prev { left: 10px; }
    .slider-btn.next { right: 10px; }

    @media (max-width: 639px) {
      .slider-btn {
        width: 28px;
        height: 28px;
        font-size: 11px;
      }
      .slider-btn.prev { left: 4px; }
      .slider-btn.next { right: 4px; }
    }

    /* ==========================================================================
       TIÊU ĐỀ SECTION & DANH MỤC TRANG CHỦ NHỎ GỌN (CHUẨN FLATSOME)
       ========================================================================== */
    .section-title-container {
      text-align: center;
      margin-bottom: 24px;
    }

    .section-title-main {
      display: inline-block;
      font-size: 21px;
      font-weight: 800;
      color: var(--primary-color);
      text-transform: uppercase;
      position: relative;
      padding-bottom: 10px;
      margin-bottom: 6px;
    }

    .section-title-main::after {
      content: "";
      position: absolute;
      bottom: 0;
      left: 50%;
      transform: translateX(-50%);
      width: 64px;
      height: 3px;
      background-color: var(--secondary-color);
      border-radius: 2px;
    }

    @media (max-width: 639px) {
      .section-title-main {
        font-size: 17px;
      }
    }

    /* Nút lọc danh mục ở trang chủ nhỏ gọn, viết liền trên 1 hàng */
    .category-filter-bar {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      justify-content: center;
      gap: 6px;
      margin-bottom: 24px;
    }

    .cat-filter-btn {
      padding: 6px 12px;
      font-size: 12px;
      font-weight: 700;
      color: var(--primary-color);
      background-color: #f1f5f9;
      border: 1px solid #cbd5e1;
      border-radius: 6px;
      cursor: pointer;
      white-space: nowrap;
      transition: all 0.2s ease;
    }

    .cat-filter-btn:hover,
    .cat-filter-btn.active {
      background-color: var(--primary-color);
      color: #ffffff;
      border-color: var(--primary-color);
    }

    /* ==========================================================================
       LƯỚI SẢN PHẨM / CÔNG TRÌNH:
       - Chia 2 cột trên điện thoại, 3-4 cột trên máy tính
       - Không để các nhãn dán ở trang chủ
       - Tên sản phẩm hiển thị đầy đủ, không tràn ra ngoài, không thiếu chữ
       ========================================================================== */
    .flatsome-product-grid {
      display: grid;
      grid-template-columns: repeat(3, minmax(0, 1fr));
      gap: 20px;
      width: 100%;
    }

    .flatsome-project-grid-5 {
      display: grid;
      grid-template-columns: repeat(5, minmax(0, 1fr));
      gap: 16px;
      width: 100%;
    }

    @media (max-width: 1199px) {
      .flatsome-project-grid-5 {
        grid-template-columns: repeat(3, minmax(0, 1fr));
      }
    }

    /* Bắt buộc chia thành 2 cột trên giao diện điện thoại */
    @media (max-width: 767px) {
      .flatsome-product-grid,
      .flatsome-project-grid-5 {
        grid-template-columns: repeat(2, minmax(0, 1fr));
        gap: 10px;
      }
    }

    .ux-card {
      background: #ffffff;
      border: 1px solid var(--border-color);
      border-radius: 8px;
      overflow: hidden;
      display: flex;
      flex-direction: column;
      transition: transform 0.25s ease, box-shadow 0.25s ease;
      height: 100%;
    }

    .ux-card:hover {
      transform: translateY(-4px);
      box-shadow: 0 12px 24px rgba(12, 45, 87, 0.12);
      border-color: var(--secondary-color);
    }

    .ux-card-image {
      position: relative;
      width: 100%;
      aspect-ratio: 4 / 3;
      overflow: hidden;
      background-color: #e2e8f0;
    }

    .ux-card-image img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      transition: transform 0.45s ease;
    }

    .ux-card:hover .ux-card-image img {
      transform: scale(1.06);
    }

    .ux-card-body {
      padding: 12px;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      flex: 1;
      text-align: center;
    }

    @media (max-width: 639px) {
      .ux-card-body {
        padding: 8px 7px;
      }
    }

    /* Tên sản phẩm không bị tràn ra ngoài hoặc thiếu chữ (không dùng ellipsis cắt chữ) */
    .ux-card-title {
      font-family: 'Montserrat', sans-serif;
      font-size: 14px;
      font-weight: 700;
      color: var(--primary-color);
      line-height: 1.4;
      margin-bottom: 6px;
      white-space: normal;
      word-wrap: break-word;
      overflow-wrap: break-word;
    }

    @media (max-width: 639px) {
      .ux-card-title {
        font-size: 12px;
        line-height: 1.35;
      }
    }

    .ux-card-meta {
      font-size: 11.5px;
      color: var(--muted-color);
      font-weight: 500;
      white-space: normal;
      word-wrap: break-word;
    }

    @media (max-width: 639px) {
      .ux-card-meta {
        font-size: 10.5px;
      }
    }

    /* ==========================================================================
       NÚT LIÊN HỆ NỔI BẬT ZALO, FACEBOOK, HOTLINE (TƯƠNG THÍCH PC & MOBILE)
       ========================================================================== */
    .floating-contact-group {
      position: fixed;
      left: 14px;
      bottom: 18px;
      z-index: 9999;
      display: flex;
      flex-direction: column;
      gap: 10px;
    }

    .float-btn {
      display: flex;
      align-items: center;
      gap: 8px;
      padding: 8px 14px 8px 8px;
      border-radius: 999px;
      color: #ffffff;
      font-size: 12.5px;
      font-weight: 700;
      box-shadow: 0 6px 18px rgba(0, 0, 0, 0.22);
      transition: transform 0.2s ease;
    }

    .float-btn:hover {
      transform: translateY(-2px) scale(1.03);
    }

    .float-btn-icon {
      width: 34px;
      height: 34px;
      border-radius: 50%;
      background: rgba(255, 255, 255, 0.2);
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 16px;
      flex-shrink: 0;
    }

    .float-hotline {
      background: linear-gradient(135deg, #dc2626, #b91c1c);
    }

    .float-zalo {
      background: linear-gradient(135deg, #0068ff, #0052cc);
    }

    .float-fb {
      background: linear-gradient(135deg, #1877f2, #0c5dc7);
    }

    @media (max-width: 639px) {
      .floating-contact-group {
        left: 10px;
        bottom: 12px;
        gap: 8px;
      }
      .float-btn {
        padding: 6px 11px 6px 6px;
        font-size: 11px;
      }
      .float-btn-icon {
        width: 28px;
        height: 28px;
        font-size: 13px;
      }
    }
  </style>
</head>
<body>

  <!-- ================= TOP BAR CHUẨN TÍN TRƯỜNG THỊNH / FLATSOME ================= -->
  <div class="top-bar">
    <div class="container flex flex-wrap items-center justify-between gap-2">
      <div class="flex flex-wrap items-center gap-4">
        <span><i class="fa-solid fa-location-dot text-amber-400 mr-1"></i> 21 Mân Quang 8, Sơn Trà, Đà Nẵng</span>
        <span class="hidden sm:inline"><i class="fa-solid fa-globe text-amber-400 mr-1"></i> phunggiaphat.com</span>
      </div>
      <div class="flex items-center gap-4">
        <a href="tel:0905615563" class="hover:text-amber-400 font-semibold"><i class="fa-solid fa-phone-volume text-amber-400 mr-1"></i> 0905 615 563</a>
        <a href="https://www.facebook.com/profile.php?id=100094536896316" target="_blank" rel="noopener noreferrer" class="hover:text-amber-400 font-semibold">
          <i class="fa-brands fa-facebook text-amber-400 mr-1"></i> Fanpage Phú Gia Phát
        </a>
      </div>
    </div>
  </div>

  <!-- ================= HEADER MAIN (KHÔNG ĐỂ NÚT GỌI NGAY ĐỂ TRÁNH TRÀN VIỀN) ================= -->
  <header id="header" class="header-wrapper">
    <div class="container">
      <div class="header-inner">
        <!-- Logo Công ty Phú Gia Phát thiết kế chuyên nghiệp, nhỏ gọn -->
        <a href="#trang-chu" class="logo-box" title="Công ty TNHH Tư vấn và Thiết kế Xây dựng Phú Gia Phát">
          <div class="logo-svg-wrap">
            <svg viewBox="0 0 100 100" width="100%" height="100%" xmlns="http://www.w3.org/2000/svg">
              <defs>
                <linearGradient id="pgpNavy" x1="0%" y1="0%" x2="100%" y2="100%">
                  <stop offset="0%" stop-color="#0c2d57"/>
                  <stop offset="100%" stop-color="#1e4b85"/>
                </linearGradient>
                <linearGradient id="pgpGold" x1="0%" y1="0%" x2="100%" y2="0%">
                  <stop offset="0%" stop-color="#d97706"/>
                  <stop offset="100%" stop-color="#fbbf24"/>
                </linearGradient>
              </defs>
              <!-- Khung lục giác kiến trúc vững chãi -->
              <polygon points="50,4 93,27 93,73 50,96 7,73 7,27" fill="url(#pgpNavy)" stroke="url(#pgpGold)" stroke-width="4"/>
              <!-- Biểu tượng Mái nhà & Tòa nhà cao tầng -->
              <path d="M22,52 L50,26 L78,52 L71,52 L50,33 L29,52 Z" fill="url(#pgpGold)"/>
              <rect x="33" y="48" width="10" height="28" fill="#ffffff" rx="1"/>
              <rect x="46" y="40" width="10" height="36" fill="url(#pgpGold)" rx="1"/>
              <rect x="59" y="52" width="10" height="24" fill="#ffffff" rx="1"/>
              <!-- Đường nền móng vững chắc -->
              <rect x="25" y="76" width="50" height="4" fill="url(#pgpGold)" rx="2"/>
            </svg>
          </div>
          <div class="logo-text-wrap">
            <span class="logo-brand-name">PHÚ GIA PHÁT</span>
            <span class="logo-brand-sub">Tư Vấn &amp; Thiết Kế Xây Dựng</span>
          </div>
        </a>

        <!-- Menu Danh mục trên máy tính: chữ nhỏ gọn, viết liền trên 1 hàng, không xuống dòng từng từ -->
        <nav aria-label="Menu chính">
          <ul class="desktop-nav">
            <li class="nav-item"><a href="#trang-chu" class="nav-link active">Trang chủ</a></li>
            <li class="nav-item"><a href="#gioi-thieu" class="nav-link">Giới thiệu</a></li>
            <li class="nav-item">
              <a href="#cong-trinh-thuc-te" class="nav-link">Công trình thực tế <i class="fa-solid fa-chevron-down"></i></a>
              <div class="nav-dropdown">
                <a href="#cong-trinh-thuc-te" onclick="filterProducts('khach-san')">Khách sạn – Căn hộ – Phòng trọ</a>
                <a href="#cong-trinh-thuc-te" onclick="filterProducts('biet-thu')">Biệt thự</a>
                <a href="#cong-trinh-thuc-te" onclick="filterProducts('nha-pho')">Nhà phố</a>
                <a href="#cong-trinh-thuc-te" onclick="filterProducts('van-phong')">Văn phòng</a>
              </div>
            </li>
            <li class="nav-item">
              <a href="#du-an-da-nang" class="nav-link">Dự án Đà Nẵng <i class="fa-solid fa-chevron-down"></i></a>
              <div class="nav-dropdown">
                <a href="#du-an-da-nang" onclick="filterDaNang('all')">Tất cả dự án Đà Nẵng</a>
                <a href="#du-an-da-nang" onclick="filterDaNang('son-tra')">Dự án Quận Sơn Trà</a>
                <a href="#du-an-da-nang" onclick="filterDaNang('hoa-xuan')">Dự án Hòa Xuân – Cẩm Lệ</a>
                <a href="#du-an-da-nang" onclick="filterDaNang('hai-chau')">Dự án Hải Châu – Ngũ Hành Sơn</a>
              </div>
            </li>
            <li class="nav-item">
              <a href="#linh-vuc-hoat-dong" class="nav-link">Lĩnh vực hoạt động <i class="fa-solid fa-chevron-down"></i></a>
              <div class="nav-dropdown">
                <a href="#linh-vuc-hoat-dong">Thiết kế Kiến trúc – Nội thất</a>
                <a href="#linh-vuc-hoat-dong">Thi công phần thô</a>
                <a href="#linh-vuc-hoat-dong">Thi công hoàn thiện</a>
                <a href="#linh-vuc-hoat-dong">Thi công nội thất</a>
              </div>
            </li>
            <li class="nav-item">
              <a href="#cong-trinh-thuc-te" class="nav-link">Mẫu thiết kế <i class="fa-solid fa-chevron-down"></i></a>
              <div class="nav-dropdown">
                <a href="#cong-trinh-thuc-te" onclick="filterProducts('nha-pho')">Mẫu thiết kế nhà phố</a>
                <a href="#cong-trinh-thuc-te" onclick="filterProducts('biet-thu')">Mẫu thiết kế biệt thự</a>
                <a href="#cong-trinh-thuc-te" onclick="filterProducts('khach-san')">Mẫu thiết kế nội thất &amp; căn hộ</a>
              </div>
            </li>
            <li class="nav-item">
              <a href="#bao-gia" class="nav-link">Báo giá <i class="fa-solid fa-chevron-down"></i></a>
              <div class="nav-dropdown">
                <a href="#bao-gia">Báo giá thiết kế kiến trúc</a>
                <a href="#bao-gia">Báo giá thi công phần thô</a>
                <a href="#bao-gia">Báo giá thi công hoàn thiện</a>
                <a href="#bao-gia">Báo giá thi công trọn gói</a>
              </div>
            </li>
            <li class="nav-item"><a href="#doi-tac" class="nav-link">Đối tác</a></li>
            <li class="nav-item"><a href="#tin-tuc" class="nav-link">Tin tức</a></li>
            <li class="nav-item"><a href="#lien-he" class="nav-link">Liên hệ</a></li>
          </ul>
        </nav>

        <!-- Nút mở menu trên điện thoại -->
        <button type="button" onclick="toggleMobileMenu()" class="lg:hidden inline-flex items-center justify-center w-9 h-9 rounded border border-slate-300 text-slate-800 hover:bg-slate-100" aria-label="Mở danh mục">
          <i class="fa-solid fa-bars text-base"></i>
        </button>
      </div>
    </div>

    <!-- Thanh danh mục rút gọn hiển thị đẹp trên điện thoại -->
    <div class="mobile-category-strip">
      <a href="#trang-chu" class="mobile-cat-pill active">Trang chủ</a>
      <a href="#gioi-thieu" class="mobile-cat-pill">Giới thiệu</a>
      <a href="#cong-trinh-thuc-te" class="mobile-cat-pill">Công trình thực tế</a>
      <a href="#du-an-da-nang" class="mobile-cat-pill">Dự án Đà Nẵng</a>
      <a href="#linh-vuc-hoat-dong" class="mobile-cat-pill">Lĩnh vực hoạt động</a>
      <a href="#bao-gia" class="mobile-cat-pill">Báo giá</a>
      <a href="#doi-tac" class="mobile-cat-pill">Đối tác</a>
      <a href="#tin-tuc" class="mobile-cat-pill">Tin tức</a>
      <a href="#lien-he" class="mobile-cat-pill">Liên hệ</a>
    </div>

    <!-- Menu Drawer trên điện thoại -->
    <div id="mobileDrawer" class="hidden lg:hidden bg-white border-t border-slate-200 shadow-xl">
      <div class="container py-3 flex flex-col gap-1 text-sm font-semibold text-slate-800">
        <a href="#trang-chu" onclick="toggleMobileMenu()" class="py-2 px-3 rounded hover:bg-slate-100">Trang chủ</a>
        <a href="#gioi-thieu" onclick="toggleMobileMenu()" class="py-2 px-3 rounded hover:bg-slate-100">Giới thiệu công ty</a>
        <a href="#cong-trinh-thuc-te" onclick="toggleMobileMenu()" class="py-2 px-3 rounded hover:bg-slate-100">Công trình thực tế (Nhà phố, Biệt thự, Căn hộ, Văn phòng)</a>
        <a href="#du-an-da-nang" onclick="toggleMobileMenu()" class="py-2 px-3 rounded hover:bg-slate-100">Dự án tiêu biểu tại Đà Nẵng</a>
        <a href="#linh-vuc-hoat-dong" onclick="toggleMobileMenu()" class="py-2 px-3 rounded hover:bg-slate-100">Lĩnh vực hoạt động</a>
        <a href="#bao-gia" onclick="toggleMobileMenu()" class="py-2 px-3 rounded hover:bg-slate-100">Bảng báo giá thiết kế &amp; thi công</a>
        <a href="#doi-tac" onclick="toggleMobileMenu()" class="py-2 px-3 rounded hover:bg-slate-100">Đối tác chiến lược</a>
        <a href="#tin-tuc" onclick="toggleMobileMenu()" class="py-2 px-3 rounded hover:bg-slate-100">Tin tức &amp; Cẩm nang xây dựng</a>
        <a href="#lien-he" onclick="toggleMobileMenu()" class="py-2 px-3 rounded hover:bg-slate-100">Liên hệ &amp; Bản đồ</a>
      </div>
    </div>
  </header>

  <!-- ================= 2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU ================= -->
  <section id="trang-chu" class="hero-slider-wrapper" aria-label="Banner chính Phú Gia Phát">
    <!-- Banner 1 -->
    <div class="hero-slide active" data-slide="0">
      <img src="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w1600"
           onerror="this.onerror=null;this.src='https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=1600&q=80';"
           alt="Công ty TNHH Tư vấn và Thiết kế Xây dựng Phú Gia Phát" class="hero-bg-img">
      <div class="hero-overlay"></div>

      <div class="hero-safe-box">
        <div class="hero-text-col">
          <span class="hero-subtitle">PHUNGGIAPHAT.COM • UY TÍN TẠI ĐÀ NẴNG</span>
          <h1 class="hero-title">CÔNG TY TNHH TƯ VẤN VÀ THIẾT KẾ XÂY DỰNG PHÚ GIA PHÁT</h1>
          <p class="hero-desc">
            Chuyên Tư vấn – Thiết kế Kiến trúc – Thi công Xây dựng trọn gói Nhà phố, Biệt thự, Khách sạn, Căn hộ &amp; Văn phòng tại Đà Nẵng. Cam kết An toàn – Chất lượng – Đúng tiến độ.
          </p>
          <div class="flex flex-wrap items-center justify-center md:justify-start gap-2.5">
            <a href="#form-bao-gia" class="bg-amber-600 hover:bg-amber-500 text-white font-bold text-xs sm:text-sm px-4 py-2.5 rounded shadow transition">
              <i class="fa-solid fa-calculator mr-1.5"></i> Nhận Báo Giá Miễn Phí
            </a>
            <a href="#cong-trinh-thuc-te" class="bg-white/15 hover:bg-white/25 text-white border border-white/40 font-semibold text-xs sm:text-sm px-4 py-2.5 rounded transition">
              Xem Công Trình Thực Tế
            </a>
          </div>
        </div>
        <div class="hero-SideCard">
          <img src="https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w800"
               onerror="this.onerror=null;this.src='https://images.unsplash.com/photo-1600596542815-ffad4c1539a9?auto=format&fit=crop&w=800&q=80';"
               alt="Dự án thực tế Phú Gia Phát Đà Nẵng">
        </div>
      </div>
    </div>

    <!-- Banner 2 (Kích thước bằng hệt Banner 1, chữ nằm gọn bên trong cách xa viền) -->
    <div class="hero-slide" data-slide="1">
      <img src="https://drive.google.com/thumbnail?id=1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff&sz=w1600"
           onerror="this.onerror=null;this.src='https://images.unsplash.com/photo-1541888946425-d09bb18086f6?auto=format&fit=crop&w=1600&q=80';"
           alt="Thi công xây dựng trọn gói Phú Gia Phát Đà Nẵng" class="hero-bg-img">
      <div class="hero-overlay"></div>

      <div class="hero-safe-box">
        <div class="hero-text-col">
          <span class="hero-subtitle">GIẢI PHÁP XÂY NHÀ TRỌN GÓI CHÌA KHÓA TRAO TAY</span>
          <h2 class="hero-title">THIẾT KẾ ĐỘT PHÁ – THI CÔNG CHUẨN KỸ THUẬT – BẢO HÀNH DÀI HẠN</h2>
          <p class="hero-desc">
            Trụ sở: 21 Mân Quang 8, Sơn Trà, Đà Nẵng • Hotline: 0905 615 563. Đội ngũ Kiến trúc sư, Kỹ sư giàu kinh nghiệm trực tiếp giám sát từng hạng mục thi công thực tế.
          </p>
          <div class="flex flex-wrap items-center justify-center md:justify-start gap-2.5">
            <a href="#du-an-da-nang" class="bg-amber-600 hover:bg-amber-500 text-white font-bold text-xs sm:text-sm px-4 py-2.5 rounded shadow transition">
              <i class="fa-solid fa-building-circle-check mr-1.5"></i> Dự Án Tại Đà Nẵng
            </a>
            <a href="#bao-gia" class="bg-white/15 hover:bg-white/25 text-white border border-white/40 font-semibold text-xs sm:text-sm px-4 py-2.5 rounded transition">
              Bảng Giá Xây Dựng 2026
            </a>
          </div>
        </div>
        <div class="hero-SideCard">
          <img src="https://drive.google.com/thumbnail?id=1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR&sz=w800"
               onerror="this.onerror=null;this.src='https://images.unsplash.com/photo-1600607687939-ce8a6c25118c?auto=format&fit=crop&w=800&q=80';"
               alt="Thi công hoàn thiện Phú Gia Phát">
        </div>
      </div>
    </div>

    <!-- Nút điều hướng 2 Banner -->
    <button type="button" class="slider-btn prev" onclick="changeSlide(-1)" aria-label="Banner trước">
      <i class="fa-solid fa-chevron-left"></i>
    </button>
    <button type="button" class="slider-btn next" onclick="changeSlide(1)" aria-label="Banner tiếp">
      <i class="fa-solid fa-chevron-right"></i>
    </button>

    <!-- Chấm chỉ báo slide -->
    <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
      <button type="button" onclick="goToSlide(0)" class="slide-dot w-2.5 h-2.5 rounded-full bg-amber-500 transition-all" aria-label="Slide 1"></button>
      <button type="button" onclick="goToSlide(1)" class="slide-dot w-2.5 h-2.5 rounded-full bg-white/50 transition-all" aria-label="Slide 2"></button>
    </div>
  </section>

  <!-- ================= LĨNH VỰC HOẠT ĐỘNG / DỊCH VỤ TIÊU BIỂU (GIỐNG WEB MẪU) ================= -->
  <section id="linh-vuc-hoat-dong" class="section bg-slate-50">
    <div class="container">
      <div class="section-title-container">
        <h2 class="section-title-main">Lĩnh Vực Hoạt Động</h2>
        <p class="text-xs sm:text-sm text-slate-600">Giải pháp toàn diện từ Tư vấn Thiết kế Kiến trúc đến Thi công Xây dựng &amp; Nội thất trọn gói</p>
      </div>

      <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
        <div class="bg-white p-4 sm:p-6 rounded-lg border border-slate-200 text-center hover:border-amber-500 transition shadow-sm">
          <div class="w-12 h-12 mx-auto mb-3 rounded-full bg-blue-950 text-amber-400 flex items-center justify-center text-xl">
            <i class="fa-solid fa-compass-drafting"></i>
          </div>
          <h3 class="text-sm sm:text-base font-bold text-blue-950 mb-1.5">Thiết Kế Kiến Trúc – Nội Thất</h3>
          <p class="text-xs text-slate-600 leading-relaxed">Thiết kế hồ sơ kỹ thuật thi công, phối cảnh 3D Nhà phố, Biệt thự, Căn hộ, Khách sạn chuẩn phong thủy và tối ưu công năng.</p>
        </div>

        <div class="bg-white p-4 sm:p-6 rounded-lg border border-slate-200 text-center hover:border-amber-500 transition shadow-sm">
          <div class="w-12 h-12 mx-auto mb-3 rounded-full bg-blue-950 text-amber-400 flex items-center justify-center text-xl">
            <i class="fa-solid fa-trowel-bricks"></i>
          </div>
          <h3 class="text-sm sm:text-base font-bold text-blue-950 mb-1.5">Thi Công Phần Thô</h3>
          <p class="text-xs text-slate-600 leading-relaxed">Thi công móng, kết cấu bê tông cốt thép, xây tô tường đúng tiêu chuẩn kỹ thuật với vật tư chính hãng chất lượng cao.</p>
        </div>

        <div class="bg-white p-4 sm:p-6 rounded-lg border border-slate-200 text-center hover:border-amber-500 transition shadow-sm">
          <div class="w-12 h-12 mx-auto mb-3 rounded-full bg-blue-950 text-amber-400 flex items-center justify-center text-xl">
            <i class="fa-solid fa-paint-roller"></i>
          </div>
          <h3 class="text-sm sm:text-base font-bold text-blue-950 mb-1.5">Thi Công Hoàn Thiện</h3>
          <p class="text-xs text-slate-600 leading-relaxed">Ốp lát gạch đá, sơn bả, trần thạch cao, lắp đặt nhôm kính, điện nước M&amp;E sắc nét, thẩm mỹ và đồng bộ với bản vẽ 3D.</p>
        </div>

        <div class="bg-white p-4 sm:p-6 rounded-lg border border-slate-200 text-center hover:border-amber-500 transition shadow-sm">
          <div class="w-12 h-12 mx-auto mb-3 rounded-full bg-blue-950 text-amber-400 flex items-center justify-center text-xl">
            <i class="fa-solid fa-couch"></i>
          </div>
          <h3 class="text-sm sm:text-base font-bold text-blue-950 mb-1.5">Xây Nhà Trọn Gói &amp; Nội Thất</h3>
          <p class="text-xs text-slate-600 leading-relaxed">Dịch vụ chìa khóa trao tay từ xin phép xây dựng, thi công thô, hoàn thiện đến sản xuất lắp đặt nội thất gỗ cao cấp.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- ================= GIỚI THIỆU CÔNG TY & 6 THẾ MẠNH (THEO MẪU TÍN TRƯỜNG THỊNH) ================= -->
  <section id="gioi-thieu" class="section bg-white">
    <div class="container">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
        <div class="lg:col-span-6">
          <p class="text-xs font-bold uppercase tracking-wider text-amber-600 mb-1">Về Chúng Tôi • phunggiaphat.com</p>
          <h2 class="text-xl sm:text-2xl font-extrabold text-blue-950 mb-3 leading-snug">
            CÔNG TY TNHH TƯ VẤN VÀ THIẾT KẾ XÂY DỰNG PHÚ GIA PHÁT
          </h2>
          <p class="text-xs sm:text-sm text-slate-700 leading-relaxed mb-3">
            <strong>PHÚ GIA PHÁT</strong> chuyên Tư vấn – Thiết kế – Thi công Xây dựng và Nội thất các công trình <strong>Khách sạn, Biệt thự, Căn hộ, Văn phòng, Nhà phố</strong> tại Thành phố Đà Nẵng và khu vực miền Trung.
          </p>
          <p class="text-xs sm:text-sm text-slate-700 leading-relaxed mb-4">
            Đặt chữ <strong>“TÂM”</strong> và chữ <strong>“TÍN”</strong> lên hàng đầu, mỗi công trình do Phú Gia Phát thực hiện luôn tuân thủ nghiêm ngặt tiêu chí: <strong>“AN TOÀN – CHẤT LƯỢNG – ĐÚNG TIẾN ĐỘ – TỐI ƯU CHI PHÍ”</strong>.
          </p>

          <div class="grid grid-cols-2 sm:grid-cols-3 gap-3 mb-4">
            <div class="p-3 rounded bg-slate-50 border border-slate-200">
              <div class="text-amber-600 font-extrabold text-lg">10+ Năm</div>
              <div class="text-xs text-slate-600">Kinh nghiệm thực chiến</div>
            </div>
            <div class="p-3 rounded bg-slate-50 border border-slate-200">
              <div class="text-amber-600 font-extrabold text-lg">150+</div>
              <div class="text-xs text-slate-600">Công trình tại Đà Nẵng</div>
            </div>
            <div class="p-3 rounded bg-slate-50 border border-slate-200 col-span-2 sm:col-span-1">
              <div class="text-amber-600 font-extrabold text-lg">Bảo Hành 5 Năm</div>
              <div class="text-xs text-slate-600">Kết cấu công trình</div>
            </div>
          </div>

          <div class="text-xs sm:text-sm space-y-1 text-slate-700 bg-amber-50/70 p-3.5 rounded-lg border border-amber-200">
            <div><i class="fa-solid fa-building text-amber-600 mr-2"></i><strong>Trụ sở:</strong> 21 Mân Quang 8, Phường Thọ Quang, Quận Sơn Trà, TP. Đà Nẵng</div>
            <div><i class="fa-solid fa-phone text-amber-600 mr-2"></i><strong>Hotline/Zalo:</strong> <a href="tel:0905615563" class="font-bold text-blue-950">0905 615 563</a></div>
            <div><i class="fa-solid fa-globe text-amber-600 mr-2"></i><strong>Website:</strong> phunggiaphat.com</div>
          </div>
        </div>

        <!-- 6 Thế mạnh của Phú Gia Phát -->
        <div class="lg:col-span-6 grid grid-cols-1 sm:grid-cols-2 gap-3.5">
          <div class="p-4 rounded-lg border border-slate-200 bg-slate-50 flex gap-3 items-start">
            <i class="fa-solid fa-user-check text-amber-600 text-lg mt-0.5"></i>
            <div>
              <h3 class="text-xs sm:text-sm font-bold text-blue-950 mb-1">Kiến trúc sư &amp; Kỹ sư chuyên nghiệp</h3>
              <p class="text-xs text-slate-600">Đội ngũ KTS sáng tạo, kỹ sư giám sát giàu kinh nghiệm và thợ lành nghề trực tiếp thi công.</p>
            </div>
          </div>
          <div class="p-4 rounded-lg border border-slate-200 bg-slate-50 flex gap-3 items-start">
            <i class="fa-solid fa-layer-group text-amber-600 text-lg mt-0.5"></i>
            <div>
              <h3 class="text-xs sm:text-sm font-bold text-blue-950 mb-1">Cập nhật xu hướng hiện đại</h3>
              <p class="text-xs text-slate-600">Ứng dụng giải pháp không gian xanh, thông tầng thoáng sáng và vật liệu bền vững cho khí hậu biển Đà Nẵng.</p>
            </div>
          </div>
          <div class="p-4 rounded-lg border border-slate-200 bg-slate-50 flex gap-3 items-start">
            <i class="fa-solid fa-clipboard-check text-amber-600 text-lg mt-0.5"></i>
            <div>
              <h3 class="text-xs sm:text-sm font-bold text-blue-950 mb-1">Giám sát tiến độ chuẩn xác</h3>
              <p class="text-xs text-slate-600">Báo cáo hình ảnh/video nghiệm thu từng giai đoạn thi công hàng ngày để Chủ đầu tư yên tâm theo dõi.</p>
            </div>
          </div>
          <div class="p-4 rounded-lg border border-slate-200 bg-slate-50 flex gap-3 items-start">
            <i class="fa-solid fa-shield-halved text-amber-600 text-lg mt-0.5"></i>
            <div>
              <h3 class="text-xs sm:text-sm font-bold text-blue-950 mb-1">Bảo hành công trình lâu dài</h3>
              <p class="text-xs text-slate-600">Cam kết đồng hành hậu mãi tận tâm, hỗ trợ kiểm tra bảo trì định kỳ nhanh chóng tại Đà Nẵng.</p>
            </div>
          </div>
          <div class="p-4 rounded-lg border border-slate-200 bg-slate-50 flex gap-3 items-start">
            <i class="fa-solid fa-hand-holding-dollar text-amber-600 text-lg mt-0.5"></i>
            <div>
              <h3 class="text-xs sm:text-sm font-bold text-blue-950 mb-1">Chi phí minh bạch, không phát sinh</h3>
              <p class="text-xs text-slate-600">Dự toán bóc tách chi tiết từng hạng mục vật tư ngay từ đầu, cam kết đúng chủng loại đã ký kết.</p>
            </div>
          </div>
          <div class="p-4 rounded-lg border border-slate-200 bg-slate-50 flex gap-3 items-start">
            <i class="fa-solid fa-headset text-amber-600 text-lg mt-0.5"></i>
            <div>
              <h3 class="text-xs sm:text-sm font-bold text-blue-950 mb-1">Hỗ trợ tư vấn &amp; Pháp lý 24/7</h3>
              <p class="text-xs text-slate-600">Hỗ trợ trọn gói thủ tục xin cấp phép xây dựng, bản vẽ hoàn công và tư vấn phong thủy miễn phí.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ================= BỘ 1: 9 ẢNH THỰC TẾ THI CÔNG XÂY DỰNG (ĐƯA VÀO ĐÚNG DANH MỤC & TÊN SẢN PHẨM) ================= -->
  <!-- Không để các nhãn dán trên ảnh, chia 2 cột trên điện thoại, tên hiển thị đầy đủ không thiếu chữ -->
  <section id="cong-trinh-thuc-te" class="section bg-slate-50">
    <div class="container">
      <div class="section-title-container">
        <h2 class="section-title-main">Công Trình Thực Tế &amp; Hạng Mục Thi Công</h2>
        <p class="text-xs sm:text-sm text-slate-600">Hình ảnh thực tế thi công xây dựng của Công ty TNHH Tư vấn và Thiết kế Xây dựng Phú Gia Phát</p>
      </div>

      <!-- Chữ danh mục ở trang chủ nhỏ gọn, viết liền trên 1 hàng -->
      <div class="category-filter-bar">
        <button type="button" class="cat-filter-btn active" onclick="filterProducts('all', this)">Tất cả</button>
        <button type="button" class="cat-filter-btn" onclick="filterProducts('khach-san', this)">Khách sạn – Căn hộ – Phòng trọ</button>
        <button type="button" class="cat-filter-btn" onclick="filterProducts('biet-thu', this)">Biệt thự</button>
        <button type="button" class="cat-filter-btn" onclick="filterProducts('nha-pho', this)">Nhà phố</button>
        <button type="button" class="cat-filter-btn" onclick="filterProducts('van-phong', this)">Văn phòng</button>
      </div>

      <!-- Lưới 9 sản phẩm/công trình thực tế từ 9 file Google Drive bộ 1 -->
      <div id="productGrid" class="flatsome-product-grid">
        <!-- Ảnh 1: 13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz -->
        <article class="ux-card product-item" data-category="nha-pho">
          <div class="ux-card-image">
            <img src="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w1000"
                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz=w1000';"
                 alt="Thi Công Phần Thô Và Kết Cấu Nhà Phố 3 Tầng Sơn Trà" loading="lazy">
          </div>
          <div class="ux-card-body">
            <h3 class="ux-card-title">Thi Công Phần Thô Và Kết Cấu Nhà Phố 3 Tầng Sơn Trà</h3>
            <p class="ux-card-meta">Danh mục: Nhà phố • Thi công phần thô</p>
          </div>
        </article>

        <!-- Ảnh 2: 1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR -->
        <article class="ux-card product-item" data-category="biet-thu">
          <div class="ux-card-image">
            <img src="https://drive.google.com/thumbnail?id=1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR&sz=w1000"
                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR=w1000';"
                 alt="Thi Công Hoàn Thiện Biệt Thự Hiện Đại Khu Đô Thị Hòa Xuân" loading="lazy">
          </div>
          <div class="ux-card-body">
            <h3 class="ux-card-title">Thi Công Hoàn Thiện Biệt Thự Hiện Đại Khu Đô Thị Hòa Xuân</h3>
            <p class="ux-card-meta">Danh mục: Biệt thự • Xây dựng trọn gói</p>
          </div>
        </article>

        <!-- Ảnh 3: 1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv -->
        <article class="ux-card product-item" data-category="khach-san">
          <div class="ux-card-image">
            <img src="https://drive.google.com/thumbnail?id=1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv&sz=w1000"
                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv=w1000';"
                 alt="Thiết Kế Và Thi Công Căn Hộ Cho Thuê Cao Cấp Sơn Trà" loading="lazy">
          </div>
          <div class="ux-card-body">
            <h3 class="ux-card-title">Thiết Kế Và Thi Công Căn Hộ Cho Thuê Cao Cấp Sơn Trà</h3>
            <p class="ux-card-meta">Danh mục: Khách sạn – Căn hộ – Phòng trọ</p>
          </div>
        </article>

        <!-- Ảnh 4: 1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_ -->
        <article class="ux-card product-item" data-category="nha-pho">
          <div class="ux-card-image">
            <img src="https://drive.google.com/thumbnail?id=1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_&sz=w1000"
                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_=w1000';"
                 alt="Thi Công Nhà Phố Hiện Đại 2 Mặt Tiền Mân Quang – Sơn Trà" loading="lazy">
          </div>
          <div class="ux-card-body">
            <h3 class="ux-card-title">Thi Công Nhà Phố Hiện Đại 2 Mặt Tiền Mân Quang – Sơn Trà</h3>
            <p class="ux-card-meta">Danh mục: Nhà phố • Thiết kế &amp; Thi công</p>
          </div>
        </article>

        <!-- Ảnh 5: 1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO -->
        <article class="ux-card product-item" data-category="biet-thu">
          <div class="ux-card-image">
            <img src="https://drive.google.com/thumbnail?id=1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO&sz=w1000"
                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO=w1000';"
                 alt="Thi Công Xây Dựng Trọn Gói Biệt Thự Phố Ngũ Hành Sơn" loading="lazy">
          </div>
          <div class="ux-card-body">
            <h3 class="ux-card-title">Thi Công Xây Dựng Trọn Gói Biệt Thự Phố Ngũ Hành Sơn</h3>
            <p class="ux-card-meta">Danh mục: Biệt thự • Thi công hoàn thiện</p>
          </div>
        </article>

        <!-- Ảnh 6: 1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t -->
        <article class="ux-card product-item" data-category="van-phong">
          <div class="ux-card-image">
            <img src="https://drive.google.com/thumbnail?id=1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t&sz=w1000"
                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t=w1000';"
                 alt="Thi Công Tòa Nhà Văn Phòng Kết Hợp Căn Hộ Quận Hải Châu" loading="lazy">
          </div>
          <div class="ux-card-body">
            <h3 class="ux-card-title">Thi Công Tòa Nhà Văn Phòng Kết Hợp Căn Hộ Quận Hải Châu</h3>
            <p class="ux-card-meta">Danh mục: Văn phòng • Thi công trọn gói</p>
          </div>
        </article>

        <!-- Ảnh 7: 1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_ -->
        <article class="ux-card product-item" data-category="nha-pho">
          <div class="ux-card-image">
            <img src="https://drive.google.com/thumbnail?id=1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_&sz=w1000"
                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_=w1000';"
                 alt="Thi Công Nội Thất Và Hoàn Thiện Nhà Phố 3 Tầng Tại Đà Nẵng" loading="lazy">
          </div>
          <div class="ux-card-body">
            <h3 class="ux-card-title">Thi Công Nội Thất Và Hoàn Thiện Nhà Phố 3 Tầng Tại Đà Nẵng</h3>
            <p class="ux-card-meta">Danh mục: Nhà phố • Thi công nội thất</p>
          </div>
        </article>

        <!-- Ảnh 8: 1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT -->
        <article class="ux-card product-item" data-category="khach-san">
          <div class="ux-card-image">
            <img src="https://drive.google.com/thumbnail?id=1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT&sz=w1000"
                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT=w1000';"
                 alt="Thi Công Khách Sạn Và Căn Hộ Dịch Vụ Ven Biển Sơn Trà" loading="lazy">
          </div>
          <div class="ux-card-body">
            <h3 class="ux-card-title">Thi Công Khách Sạn Và Căn Hộ Dịch Vụ Ven Biển Sơn Trà</h3>
            <p class="ux-card-meta">Danh mục: Khách sạn – Căn hộ – Phòng trọ</p>
          </div>
        </article>

        <!-- Ảnh 9: 1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn -->
        <article class="ux-card product-item" data-category="van-phong">
          <div class="ux-card-image">
            <img src="https://drive.google.com/thumbnail?id=1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn&sz=w1000"
                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn=w1000';"
                 alt="Thiết Kế Thi Công Trọn Gói Văn Phòng Công Ty Tại Đà Nẵng" loading="lazy">
          </div>
          <div class="ux-card-body">
            <h3 class="ux-card-title">Thiết Kế Thi Công Trọn Gói Văn Phòng Công Ty Tại Đà Nẵng</h3>
            <p class="ux-card-meta">Danh mục: Văn phòng • Hoàn thiện &amp; Nội thất</p>
          </div>
        </article>
      </div>
    </div>
  </section>

  <!-- ================= BỘ 2: 10 ẢNH DANH MỤC CÁC DỰ ÁN Ở ĐÀ NẴNG VÀO TRANG CHỦ ================= -->
  <section id="du-an-da-nang" class="section bg-white">
    <div class="container">
      <div class="section-title-container">
        <h2 class="section-title-main">Danh Mục Các Dự Án Tại Đà Nẵng</h2>
        <p class="text-xs sm:text-sm text-slate-600">Các dự án thiết kế và thi công xây dựng tiêu biểu của Phú Gia Phát trên địa bàn TP. Đà Nẵng</p>
      </div>

      <!-- Bộ lọc danh mục dự án Đà Nẵng nhỏ gọn -->
      <div class="category-filter-bar">
        <button type="button" class="cat-filter-btn active" onclick="filterDaNang('all', this)">Tất cả dự án Đà Nẵng</button>
        <button type="button" class="cat-filter-btn" onclick="filterDaNang('son-tra', this)">Quận Sơn Trà</button>
        <button type="button" class="cat-filter-btn" onclick="filterDaNang('hoa-xuan', this)">Khu Đô Thị Hòa Xuân – Cẩm Lệ</button>
        <button type="button" class="cat-filter-btn" onclick="filterDaNang('hai-chau', this)">Hải Châu – Ngũ Hành Sơn</button>
      </div>

      <!-- Lưới 10 dự án ở Đà Nẵng (2 cột trên điện thoại, không nhãn dán đè lên ảnh) -->
      <div id="daNangGrid" class="flatsome-project-grid-5">
        <!-- Dự án Đà Nẵng 1: 157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT -->
        <article class="ux-card danang-item" data-area="son-tra">
          <div class="ux-card-image">
            <img src="https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w1000"
                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT=w1000';"
                 alt="Dự Án Nhà Phố 3 Tầng Hiện Đại Mân Quang – Sơn Trà – Đà Nẵng" loading="lazy">
          </div>
          <div class="ux-card-body">
            <h3 class="ux-card-title">Dự Án Nhà Phố 3 Tầng Hiện Đại Mân Quang – Sơn Trà – Đà Nẵng</h3>
            <p class="ux-card-meta">Khu vực: Quận Sơn Trà, Đà Nẵng</p>
          </div>
        </article>

        <!-- Dự án Đà Nẵng 2: 1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff -->
        <article class="ux-card danang-item" data-area="son-tra">
          <div class="ux-card-image">
            <img src="https://drive.google.com/thumbnail?id=1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff&sz=w1000"
                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff=w1000';"
                 alt="Dự Án Căn Hộ Dịch Vụ Cao Cấp Phạm Văn Đồng – Sơn Trà – Đà Nẵng" loading="lazy">
          </div>
          <div class="ux-card-body">
            <h3 class="ux-card-title">Dự Án Căn Hộ Dịch Vụ Cao Cấp Phạm Văn Đồng – Sơn Trà – Đà Nẵng</h3>
            <p class="ux-card-meta">Khu vực: Quận Sơn Trà, Đà Nẵng</p>
          </div>
        </article>

        <!-- Dự án Đà Nẵng 3: 1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz -->
        <article class="ux-card danang-item" data-area="hoa-xuan">
          <div class="ux-card-image">
            <img src="https://drive.google.com/thumbnail?id=1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz&sz=w1000"
                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz=w1000';"
                 alt="Dự Án Biệt Thự Sân Vườn Khu Đô Thị Nam Hòa Xuân – Đà Nẵng" loading="lazy">
          </div>
          <div class="ux-card-body">
            <h3 class="ux-card-title">Dự Án Biệt Thự Sân Vườn Khu Đô Thị Nam Hòa Xuân – Đà Nẵng</h3>
            <p class="ux-card-meta">Khu vực: Hòa Xuân, Cẩm Lệ, Đà Nẵng</p>
          </div>
        </article>

        <!-- Dự án Đà Nẵng 4: 1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k -->
        <article class="ux-card danang-item" data-area="hai-chau">
          <div class="ux-card-image">
            <img src="https://drive.google.com/thumbnail?id=1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k&sz=w1000"
                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k=w1000';"
                 alt="Dự Án Nhà Phố Lệch Tầng Khu Đô Thị Nam Việt Á – Đà Nẵng" loading="lazy">
          </div>
          <div class="ux-card-body">
            <h3 class="ux-card-title">Dự Án Nhà Phố Lệch Tầng Khu Đô Thị Nam Việt Á – Đà Nẵng</h3>
            <p class="ux-card-meta">Khu vực: Ngũ Hành Sơn, Đà Nẵng</p>
          </div>
        </article>

        <!-- Dự án Đà Nẵng 5: 1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N -->
        <article class="ux-card danang-item" data-area="hai-chau">
          <div class="ux-card-image">
            <img src="https://drive.google.com/thumbnail?id=1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N&sz=w1000"
                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N=w1000';"
                 alt="Dự Án Tòa Nhà Văn Phòng Và Showroom Quận Hải Châu – Đà Nẵng" loading="lazy">
          </div>
          <div class="ux-card-body">
            <h3 class="ux-card-title">Dự Án Tòa Nhà Văn Phòng Và Showroom Quận Hải Châu – Đà Nẵng</h3>
            <p class="ux-card-meta">Khu vực: Quận Hải Châu, Đà Nẵng</p>
          </div>
        </article>

        <!-- Dự án Đà Nẵng 6: 1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML -->
        <article class="ux-card danang-item" data-area="son-tra">
          <div class="ux-card-image">
            <img src="https://drive.google.com/thumbnail?id=1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML&sz=w1000"
                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML=w1000';"
                 alt="Dự Án Nhà Phố Kết Hợp Kinh Doanh Vương Thừa Vũ – Sơn Trà" loading="lazy">
          </div>
          <div class="ux-card-body">
            <h3 class="ux-card-title">Dự Án Nhà Phố Kết Hợp Kinh Doanh Vương Thừa Vũ – Sơn Trà</h3>
            <p class="ux-card-meta">Khu vực: Quận Sơn Trà, Đà Nẵng</p>
          </div>
        </article>

        <!-- Dự án Đà Nẵng 7: 1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF -->
        <article class="ux-card danang-item" data-area="hai-chau">
          <div class="ux-card-image">
            <img src="https://drive.google.com/thumbnail?id=1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF&sz=w1000"
                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF=w1000';"
                 alt="Dự Án Biệt Thự Hiện Đại 3 Tầng Khu Đô Thị FPT City – Đà Nẵng" loading="lazy">
          </div>
          <div class="ux-card-body">
            <h3 class="ux-card-title">Dự Án Biệt Thự Hiện Đại 3 Tầng Khu Đô Thị FPT City – Đà Nẵng</h3>
            <p class="ux-card-meta">Khu vực: Ngũ Hành Sơn, Đà Nẵng</p>
          </div>
        </article>

        <!-- Dự án Đà Nẵng 8: 1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A -->
        <article class="ux-card danang-item" data-area="hai-chau">
          <div class="ux-card-image">
            <img src="https://drive.google.com/thumbnail?id=1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A&sz=w1000"
                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A=w1000';"
                 alt="Dự Án Căn Hộ Cho Thuê Khu Phố Du Lịch An Thượng – Đà Nẵng" loading="lazy">
          </div>
          <div class="ux-card-body">
            <h3 class="ux-card-title">Dự Án Căn Hộ Cho Thuê Khu Phố Du Lịch An Thượng – Đà Nẵng</h3>
            <p class="ux-card-meta">Khu vực: Ngũ Hành Sơn, Đà Nẵng</p>
          </div>
        </article>

        <!-- Dự án Đà Nẵng 9: 1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80 -->
        <article class="ux-card danang-item" data-area="son-tra">
          <div class="ux-card-image">
            <img src="https://drive.google.com/thumbnail?id=1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80&sz=w1000"
                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80=w1000';"
                 alt="Dự Án Nhà Phố 4 Tầng Mặt Tiền Nguyễn Văn Thoại – Sơn Trà" loading="lazy">
          </div>
          <div class="ux-card-body">
            <h3 class="ux-card-title">Dự Án Nhà Phố 4 Tầng Mặt Tiền Nguyễn Văn Thoại – Sơn Trà</h3>
            <p class="ux-card-meta">Khu vực: Quận Sơn Trà, Đà Nẵng</p>
          </div>
        </article>

        <!-- Dự án Đà Nẵng 10: 1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4 -->
        <article class="ux-card danang-item" data-area="hoa-xuan">
          <div class="ux-card-image">
            <img src="https://drive.google.com/thumbnail?id=1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4&sz=w1000"
                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4=w1000';"
                 alt="Dự Án Biệt Thự Phố 2 Mặt Tiền Khu Đô Thị Hòa Xuân – Đà Nẵng" loading="lazy">
          </div>
          <div class="ux-card-body">
            <h3 class="ux-card-title">Dự Án Biệt Thự Phố 2 Mặt Tiền Khu Đô Thị Hòa Xuân – Đà Nẵng</h3>
            <p class="ux-card-meta">Khu vực: Hòa Xuân, Cẩm Lệ, Đà Nẵng</p>
          </div>
        </article>
      </div>
    </div>
  </section>

  <!-- ================= BẢNG BÁO GIÁ THIẾT KẾ & THI CÔNG TRỌN GÓI ================= -->
  <section id="bao-gia" class="section bg-slate-50">
    <div class="container">
      <div class="section-title-container">
        <h2 class="section-title-main">Bảng Báo Giá Thiết Kế &amp; Thi Công</h2>
        <p class="text-xs sm:text-sm text-slate-600">Đơn giá tham khảo chuẩn chất lượng tại Đà Nẵng của Công ty Xây dựng Phú Gia Phát</p>
      </div>

      <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
        <div class="bg-white rounded-lg border border-slate-200 p-4 sm:p-5 flex flex-col justify-between shadow-sm">
          <div>
            <h3 class="text-xs sm:text-base font-extrabold text-blue-950 uppercase mb-1">Báo Giá Thiết Kế Kiến Trúc</h3>
            <div class="text-amber-600 font-extrabold text-base sm:text-xl mb-3">120.000đ – 180.000đ/m²</div>
            <ul class="text-xs text-slate-600 space-y-1.5 mb-4">
              <li><i class="fa-solid fa-check text-amber-600 mr-1.5"></i>Bản vẽ phối cảnh 3D mặt tiền</li>
              <li><i class="fa-solid fa-check text-amber-600 mr-1.5"></i>Hồ sơ kết cấu, điện nước M&amp;E</li>
              <li><i class="fa-solid fa-check text-amber-600 mr-1.5"></i>Giảm 100% khi ký HĐ thi công</li>
            </ul>
          </div>
          <a href="#form-bao-gia" class="block text-center bg-blue-950 hover:bg-amber-600 text-white text-xs font-bold py-2.5 rounded transition">Đăng Ký Tư Vấn</a>
        </div>

        <div class="bg-white rounded-lg border border-slate-200 p-4 sm:p-5 flex flex-col justify-between shadow-sm">
          <div>
            <h3 class="text-xs sm:text-base font-extrabold text-blue-950 uppercase mb-1">Báo Giá Thi Công Phần Thô</h3>
            <div class="text-amber-600 font-extrabold text-base sm:text-xl mb-3">3.500.000đ – 3.850.000đ/m²</div>
            <ul class="text-xs text-slate-600 space-y-1.5 mb-4">
              <li><i class="fa-solid fa-check text-amber-600 mr-1.5"></i>Vật tư chuẩn Thép Hòa Phát / Việt Nhật</li>
              <li><i class="fa-solid fa-check text-amber-600 mr-1.5"></i>Nhân công phần thô &amp; hoàn thiện</li>
              <li><i class="fa-solid fa-check text-amber-600 mr-1.5"></i>Bảo hành kết cấu 5 năm</li>
            </ul>
          </div>
          <a href="#form-bao-gia" class="block text-center bg-blue-950 hover:bg-amber-600 text-white text-xs font-bold py-2.5 rounded transition">Đăng Ký Tư Vấn</a>
        </div>

        <div class="bg-white rounded-lg border border-slate-200 p-4 sm:p-5 flex flex-col justify-between shadow-sm">
          <div>
            <h3 class="text-xs sm:text-base font-extrabold text-blue-950 uppercase mb-1">Báo Giá Thi Công Hoàn Thiện</h3>
            <div class="text-amber-600 font-extrabold text-base sm:text-xl mb-3">2.200.000đ – 3.200.000đ/m²</div>
            <ul class="text-xs text-slate-600 space-y-1.5 mb-4">
              <li><i class="fa-solid fa-check text-amber-600 mr-1.5"></i>Gạch ốp lát, đá Granite, sơn Jotun/Dulux</li>
              <li><i class="fa-solid fa-check text-amber-600 mr-1.5"></i>Cửa nhôm Xingfa, thiết bị Inax/Toto</li>
              <li><i class="fa-solid fa-check text-amber-600 mr-1.5"></i>Cam kết không phát sinh chi phí</li>
            </ul>
          </div>
          <a href="#form-bao-gia" class="block text-center bg-blue-950 hover:bg-amber-600 text-white text-xs font-bold py-2.5 rounded transition">Đăng Ký Tư Vấn</a>
        </div>

        <div class="bg-white rounded-lg border-2 border-amber-500 p-4 sm:p-5 flex flex-col justify-between shadow-md">
          <div>
            <h3 class="text-xs sm:text-base font-extrabold text-blue-950 uppercase mb-1">Báo Giá Thi Công Trọn Gói</h3>
            <div class="text-amber-600 font-extrabold text-base sm:text-xl mb-3">5.600.000đ – 6.900.000đ/m²</div>
            <ul class="text-xs text-slate-600 space-y-1.5 mb-4">
              <li><i class="fa-solid fa-check text-amber-600 mr-1.5"></i>Miễn phí 100% thiết kế &amp; Xin phép XD</li>
              <li><i class="fa-solid fa-check text-amber-600 mr-1.5"></i>Chìa khóa trao tay từ A - Z</li>
              <li><i class="fa-solid fa-check text-amber-600 mr-1.5"></i>Kỹ sư giám sát trực tiếp tại công trình</li>
            </ul>
          </div>
          <a href="#form-bao-gia" class="block text-center bg-amber-600 hover:bg-amber-500 text-white text-xs font-bold py-2.5 rounded transition">Nhận Báo Giá Chi Tiết</a>
        </div>
      </div>
    </div>
  </section>

  <!-- ================= FORM YÊU CẦU TƯ VẤN & BÁO GIÁ TRANG CHỦ (CHUẨN WEB MẪU) ================= -->
  <section id="form-bao-gia" class="section bg-blue-950 text-white">
    <div class="container">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
        <div class="lg:col-span-5">
          <span class="inline-block bg-amber-600 text-white text-xs font-bold px-3 py-1 rounded mb-2 uppercase">Hỗ Trợ Tư Vấn 24/7</span>
          <h2 class="text-xl sm:text-2xl font-extrabold mb-3">ĐĂNG KÝ NHẬN TƯ VẤN &amp; BÁO GIÁ MIỄN PHÍ</h2>
          <p class="text-xs sm:text-sm text-slate-200 leading-relaxed mb-4">
            Quý khách hàng đang có dự định xây dựng Nhà phố, Biệt thự, Căn hộ cho thuê hay Văn phòng tại Đà Nẵng? Hãy để lại thông tin, Kỹ sư trưởng của <strong>Phú Gia Phát</strong> sẽ liên hệ tư vấn phương án kiến trúc và bảng dự toán chi tiết trong vòng 15 phút.
          </p>
          <div class="space-y-2 text-xs sm:text-sm text-amber-300 font-semibold">
            <div><i class="fa-solid fa-circle-check mr-2"></i>Khảo sát hiện trạng đất &amp; tư vấn quy hoạch miễn phí tại Đà Nẵng</div>
            <div><i class="fa-solid fa-circle-check mr-2"></i>Bóc tách dự toán chi tiết từng hạng mục vật tư</div>
            <div><i class="fa-solid fa-circle-check mr-2"></i>Hotline trực tiếp: <a href="tel:0905615563" class="underline text-white">0905 615 563</a></div>
          </div>
        </div>

        <div class="lg:col-span-7">
          <form id="quoteRequestForm" onsubmit="submitQuoteForm(event)" class="bg-white text-slate-800 p-5 sm:p-7 rounded-xl shadow-xl">
            <h3 class="text-base sm:text-lg font-extrabold text-blue-950 mb-4 uppercase text-center border-b pb-2">
              Form Yêu Cầu Tư Vấn &amp; Báo Giá Xây Dựng
            </h3>
            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
              <div>
                <label class="block text-xs font-bold text-slate-700 mb-1">Họ và tên Quý khách *</label>
                <input type="text" id="custName" required placeholder="Nhập họ và tên..." class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded focus:outline-none focus:border-amber-600">
              </div>
              <div>
                <label class="block text-xs font-bold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                <input type="tel" id="custPhone" required placeholder="Nhập số điện thoại..." class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded focus:outline-none focus:border-amber-600">
              </div>
              <div>
                <label class="block text-xs font-bold text-slate-700 mb-1">Loại công trình</label>
                <select id="projectType" class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded focus:outline-none focus:border-amber-600">
                  <option value="Nhà phố">Nhà phố hiện đại</option>
                  <option value="Khách sạn - Căn hộ - Phòng trọ">Khách sạn – Căn hộ cho thuê – Phòng trọ</option>
                  <option value="Biệt thự">Biệt thự phố / Biệt thự sân vườn</option>
                  <option value="Văn phòng">Tòa nhà Văn phòng / Showroom</option>
                  <option value="Cải tạo sửa chữa">Cải tạo – Sửa chữa – Hoàn thiện nội thất</option>
                </select>
              </div>
              <div>
                <label class="block text-xs font-bold text-slate-700 mb-1">Mức đầu tư dự kiến</label>
                <select id="budgetLevel" class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded focus:outline-none focus:border-amber-600">
                  <option value="Chưa xác định">Chưa xác định (Cần tư vấn dự toán)</option>
                  <option value="Dưới 1 tỷ">Dưới 1 tỷ</option>
                  <option value="1 - 2 tỷ">Từ 1 – 2 tỷ</option>
                  <option value="2 - 3 tỷ">Từ 2 – 3 tỷ</option>
                  <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                </select>
              </div>
              <div>
                <label class="block text-xs font-bold text-slate-700 mb-1">Email (nếu có)</label>
                <input type="email" id="custEmail" placeholder="example@gmail.com" class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded focus:outline-none focus:border-amber-600">
              </div>
              <div>
                <label class="block text-xs font-bold text-slate-700 mb-1">Khu vực xây dựng &amp; Diện tích đất</label>
                <input type="text" id="custArea" placeholder="VD: Sơn Trà, Đà Nẵng - 5x20m, 3 tầng" class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded focus:outline-none focus:border-amber-600">
              </div>
            </div>
            <div class="mt-3.5">
              <label class="block text-xs font-bold text-slate-700 mb-1">Yêu cầu chi tiết</label>
              <textarea id="custNote" rows="2" placeholder="Ghi chú thêm về nhu cầu công năng, số tầng, thời gian dự kiến khởi công..." class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded focus:outline-none focus:border-amber-600"></textarea>
            </div>
            <button type="submit" class="mt-4 w-full bg-amber-600 hover:bg-amber-500 text-white font-extrabold text-xs sm:text-sm uppercase py-3 rounded shadow transition">
              <i class="fa-solid fa-paper-plane mr-1.5"></i> Gửi Yêu Cầu Báo Giá Ngay
            </button>
            <div id="quoteSuccessMsg" class="hidden mt-3 p-3 rounded bg-emerald-50 border border-emerald-300 text-emerald-800 text-xs font-semibold text-center"></div>
          </form>
        </div>
      </div>
    </div>
  </section>

  <!-- ================= DANH MỤC CÁC BÀI VIẾT TIN TỨC TRANG CHỦ ================= -->
  <section id="tin-tuc" class="section bg-white">
    <div class="container">
      <div class="section-title-container">
        <h2 class="section-title-main">Tin Tức &amp; Cẩm Nang Xây Dựng</h2>
        <p class="text-xs sm:text-sm text-slate-600">Kiến thức thiết kế kiến trúc, kinh nghiệm thi công xây dựng nhà đẹp tại Đà Nẵng</p>
      </div>

      <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
      <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
        <article class="ux-card">
          <div class="ux-card-image">
            <img src="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w800"
                 onerror="this.onerror=null;this.src='https://images.unsplash.com/photo-1503387762-592deb58ef4e?auto=format&fit=crop&w=800&q=80';"
                 alt="Hướng dẫn bảo dưỡng bê tông móng và sàn đúng kỹ thuật" loading="lazy">
          </div>
          <div class="ux-card-body text-left">
            <h3 class="ux-card-title">Hướng dẫn bảo dưỡng bê tông móng và sàn đúng kỹ thuật</h3>
            <p class="ux-card-meta">Quy trình tưới nước giữ ẩm và kiểm định cường độ bê tông cốt thép giúp kết cấu nhà phố bền vững hàng chục năm.</p>
          </div>
        </article>

        <article class="ux-card">
          <div class="ux-card-image">
            <img src="https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w800"
                 onerror="this.onerror=null;this.src='https://images.unsplash.com/photo-1600585154526-990dced4db0d?auto=format&fit=crop&w=800&q=80';"
                 alt="Kinh nghiệm xây nhà trọn gói tại Sơn Trà Đà Nẵng tiết kiệm chi phí" loading="lazy">
          </div>
          <div class="ux-card-body text-left">
            <h3 class="ux-card-title">Kinh nghiệm xây nhà trọn gói tại Sơn Trà Đà Nẵng tiết kiệm chi phí</h3>
            <p class="ux-card-meta">Những lưu ý quan trọng khi lựa chọn vật tư chống thấm, chống ăn mòn muối biển cho công trình ven biển Đà Nẵng.</p>
          </div>
        </article>

        <article class="ux-card">
          <div class="ux-card-image">
            <img src="https://drive.google.com/thumbnail?id=1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_&sz=w800"
                 onerror="this.onerror=null;this.src='https://images.unsplash.com/photo-1618221195710-dd6b41faaea6?auto=format&fit=crop&w=800&q=80';"
                 alt="Tâm lý học không gian: Thiết kế nội thất tác động đến tổ ấm thế nào" loading="lazy">
          </div>
          <div class="ux-card-body text-left">
            <h3 class="ux-card-title">Tâm lý học không gian: Thiết kế nội thất tác động đến tổ ấm thế nào</h3>
            <p class="ux-card-meta">Cách bố trí ánh sáng tự nhiên, giếng trời và thông gió giúp nhà ống Đà Nẵng luôn thoáng mát và tràn đầy năng lượng.</p>
          </div>
        </article>

        <article class="ux-card">
          <div class="ux-card-image">
            <img src="https://drive.google.com/thumbnail?id=1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz&sz=w800"
                 onerror="this.onerror=null;this.src='https://images.unsplash.com/photo-1600607687920-4e2a09cf159d?auto=format&fit=crop&w=800&q=80';"
                 alt="03 Nỗi lo lớn nhất khi xây nhà mà Chủ đầu tư nào cũng cần biết" loading="lazy">
          </div>
          <div class="ux-card-body text-left">
            <h3 class="ux-card-title">03 Nỗi lo lớn nhất khi xây nhà mà Chủ đầu tư nào cũng cần biết</h3>
            <p class="ux-card-meta">Giải pháp kiểm soát chi phí không phát sinh, đảm bảo đúng tiến độ và cam kết chất lượng vật tư tại Phú Gia Phát.</p>
          </div>
        </article>
      </div>
    </div>
  </section>

  <!-- ================= DANH MỤC CÁC ĐỐI TÁC UY TÍN ================= -->
  <section id="doi-tac" class="section bg-slate-50">
    <div class="container">
      <div class="section-title-container">
        <h2 class="section-title-main">Đối Tác &amp; Thương Hiệu Vật Tư</h2>
        <p class="text-xs sm:text-sm text-slate-600">Phú Gia Phát hợp tác cùng các thương hiệu vật liệu xây dựng &amp; nội thất hàng đầu Việt Nam</p>
      </div>

      <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-3">
        <div class="bg-white border border-slate-200 rounded-lg p-3 text-center flex flex-col items-center justify-center h-20 shadow-sm">
          <span class="font-extrabold text-xs sm:text-sm text-blue-950">THÉP HÒA PHÁT</span>
          <span class="text-[10px] text-slate-500">Kết cấu thép chuẩn</span>
        </div>
        <div class="bg-white border border-slate-200 rounded-lg p-3 text-center flex flex-col items-center justify-center h-20 shadow-sm">
          <span class="font-extrabold text-xs sm:text-sm text-blue-950">VIỆT NHẬT VJS</span>
          <span class="text-[10px] text-slate-500">Thép xây dựng</span>
        </div>
        <div class="bg-white border border-slate-200 rounded-lg p-3 text-center flex flex-col items-center justify-center h-20 shadow-sm">
          <span class="font-extrabold text-xs sm:text-sm text-blue-950">JOTUN PAINT</span>
          <span class="text-[10px] text-slate-500">Sơn ngoại thất cao cấp</span>
        </div>
        <div class="bg-white border border-slate-200 rounded-lg p-3 text-center flex flex-col items-center justify-center h-20 shadow-sm">
          <span class="font-extrabold text-xs sm:text-sm text-blue-950">DULUX AKZONOBEL</span>
          <span class="text-[10px] text-slate-500">Sơn nội ngoại thất</span>
        </div>
        <div class="bg-white border border-slate-200 rounded-lg p-3 text-center flex flex-col items-center justify-center h-20 shadow-sm">
          <span class="font-extrabold text-xs sm:text-sm text-blue-950">INAX / TOTO</span>
          <span class="text-[10px] text-slate-500">Thiết bị vệ sinh</span>
        </div>
        <div class="bg-white border border-slate-200 rounded-lg p-3 text-center flex flex-col items-center justify-center h-20 shadow-sm">
          <span class="font-extrabold text-xs sm:text-sm text-blue-950">PANASONIC</span>
          <span class="text-[10px] text-slate-500">Thiết bị điện M&amp;E</span>
        </div>
        <div class="bg-white border border-slate-200 rounded-lg p-3 text-center flex flex-col items-center justify-center h-20 shadow-sm">
          <span class="font-extrabold text-xs sm:text-sm text-blue-950">NHÔM XINGFA</span>
          <span class="text-[10px] text-slate-500">Hệ cửa nhôm kính</span>
        </div>
        <div class="bg-white border border-slate-200 rounded-lg p-3 text-center flex flex-col items-center justify-center h-20 shadow-sm">
          <span class="font-extrabold text-xs sm:text-sm text-blue-950">AN CƯỜNG WOOD</span>
          <span class="text-[10px] text-slate-500">Vật liệu gỗ nội thất</span>
        </div>
      </div>
    </div>
  </section>

  <!-- ================= ĐƯA FANPAGE & GOOGLE MAP RA NGOÀI TRANG CHỦ ================= -->
  <section id="lien-he" class="section bg-white">
    <div class="container">
      <div class="section-title-container">
        <h2 class="section-title-main">Kết Nối Fanpage &amp; Bản Đồ Trụ Sở</h2>
        <p class="text-xs sm:text-sm text-slate-600">Địa chỉ: 21 Mân Quang 8, Sơn Trà, Đà Nẵng • Hotline: 0905 615 563 • Website: phunggiaphat.com</p>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">
        <!-- Cột Fanpage Facebook đưa ra ngoài trang chủ -->
        <div class="lg:col-span-5 bg-slate-50 border border-slate-200 rounded-xl p-4 sm:p-5 flex flex-col justify-between">
          <div>
            <div class="flex items-center gap-3 pb-3 mb-3 border-b border-slate-200">
              <div class="w-12 h-12 rounded-full bg-blue-950 text-amber-400 flex items-center justify-center font-extrabold text-base flex-shrink-0">
                PGP
              </div>
              <div>
                <h3 class="text-sm sm:text-base font-extrabold text-blue-950">
                  Công Ty TNHH Tư Vấn Và Thiết Kế Xây Dựng Phú Gia Phát
                </h3>
                <p class="text-xs text-slate-600"><i class="fa-brands fa-facebook text-blue-600 mr-1"></i>Fanpage Chính Thức • Đà Nẵng</p>
              </div>
            </div>

            <!-- Khung Plugin Fanpage + Thẻ trực quan của Fanpage -->
            <div class="rounded-lg overflow-hidden border border-slate-200 bg-white mb-3">
              <div class="relative h-36 bg-blue-950 overflow-hidden">
                <img src="https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w1000"
                     onerror="this.onerror=null;this.src='https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=900&q=80';"
                     alt="Ảnh bìa Fanpage Phú Gia Phát" class="w-full h-full object-cover opacity-60">
                <div class="absolute inset-0 bg-gradient-to-t from-blue-950 via-blue-950/40 to-transparent"></div>
                <div class="absolute bottom-3 left-3 right-3 text-white">
                  <div class="text-xs font-bold text-amber-400">FANPAGE FACEBOOK CHÍNH THỨC</div>
                  <div class="text-sm font-extrabold">Xây Dựng Phú Gia Phát - Đà Nẵng</div>
                </div>
              </div>
              <div class="p-3.5 text-xs text-slate-700 space-y-1.5">
                <div><i class="fa-solid fa-location-dot text-amber-600 mr-1.5"></i>21 Mân Quang 8, Sơn Trà, Đà Nẵng</div>
                <div><i class="fa-solid fa-phone text-amber-600 mr-1.5"></i>0905 615 563</div>
                <div><i class="fa-solid fa-link text-amber-600 mr-1.5"></i>facebook.com/profile.php?id=100094536896316</div>
              </div>
            </div>
          </div>

          <div class="flex flex-wrap gap-2.5">
            <a href="https://www.facebook.com/profile.php?id=100094536896316" target="_blank" rel="noopener noreferrer"
               class="flex-1 text-center bg-blue-600 hover:bg-blue-700 text-white text-xs font-bold py-2.5 px-3 rounded transition">
              <i class="fa-brands fa-facebook-f mr-1.5"></i> Truy Cập Fanpage
            </a>
            <a href="https://zalo.me/0905615563" target="_blank" rel="noopener noreferrer"
               class="flex-1 text-center bg-amber-600 hover:bg-amber-500 text-white text-xs font-bold py-2.5 px-3 rounded transition">
              <i class="fa-solid fa-comment-dots mr-1.5"></i> Nhắn Zalo Ngay
            </a>
          </div>
        </div>

        <!-- Cột Bản đồ Google Map đưa trực tiếp ra ngoài trang chủ -->
        <div class="lg:col-span-7 bg-slate-50 border border-slate-200 rounded-xl p-3 sm:p-4 flex flex-col">
          <div class="flex flex-wrap items-center justify-between gap-2 mb-2.5 px-1">
            <div>
              <h3 class="text-sm sm:text-base font-extrabold text-blue-950">
                <i class="fa-solid fa-map-location-dot text-amber-600 mr-1.5"></i>Bản Đồ Google Maps: 21 Mân Quang 8, Sơn Trà, Đà Nẵng
              </h3>
            </div>
            <a href="https://www.google.com/maps/search/?api=1&query=21+M%C3%A2n+Quang+8,+S%C6%A1n+Tr%C3%A0,+%C4%90%C3%A0+N%E1%BA%B5ng"
               target="_blank" rel="noopener noreferrer"
               class="text-xs font-bold text-amber-700 hover:underline">
              Mở chỉ đường lớn <i class="fa-solid fa-up-right-from-square ml-1"></i>
            </a>
          </div>
          <div class="w-full flex-1 min-h-[280px] rounded-lg overflow-hidden border border-slate-300">
            <iframe
              title="Bản đồ Công ty TNHH Tư vấn và Thiết kế Xây dựng Phú Gia Phát - 21 Mân Quang 8, Sơn Trà, Đà Nẵng"
              src="https://maps.google.com/maps?q=21%20M%C3%A2n%20Quang%208,%20S%C6%A1n%20Tr%C3%A0,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
              width="100%"
              height="100%"
              style="border:0; min-height: 280px;"
              allowfullscreen=""
              loading="lazy"
              referrerpolicy="no-referrer-when-downgrade">
            </iframe>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ================= FOOTER CHUẨN FLATSOME ================= -->
  <footer class="bg-blue-950 text-slate-200 pt-10 pb-6 border-t-4 border-amber-500">
    <div class="container">
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-8 pb-8 border-b border-white/10">
        <div class="lg:col-span-5">
          <div class="flex items-center gap-2.5 mb-3">
            <div class="w-9 h-9 rounded bg-amber-500 text-blue-950 font-extrabold flex items-center justify-center text-sm">PGP</div>
            <span class="font-extrabold text-base text-white">CÔNG TY TNHH TƯ VẤN &amp; THIẾT KẾ XÂY DỰNG PHÚ GIA PHÁT</span>
          </div>
          <p class="text-xs text-slate-300 leading-relaxed mb-3">
            Đơn vị uy tín hàng đầu tại Đà Nẵng chuyên Thiết kế Kiến trúc – Thi công Xây dựng trọn gói – Thi công Nội thất các công trình Nhà phố, Biệt thự, Khách sạn, Căn hộ và Văn phòng.
          </p>
          <ul class="text-xs space-y-1.5 text-slate-200">
            <li><i class="fa-solid fa-location-dot text-amber-400 mr-2"></i><strong>Địa chỉ:</strong> 21 Mân Quang 8, Sơn Trà, Đà Nẵng</li>
            <li><i class="fa-solid fa-phone text-amber-400 mr-2"></i><strong>Điện thoại:</strong> <a href="tel:0905615563" class="text-amber-400 font-bold">0905 615 563</a></li>
            <li><i class="fa-solid fa-globe text-amber-400 mr-2"></i><strong>Website:</strong> <a href="https://phunggiaphat.com" class="hover:text-amber-400">phunggiaphat.com</a></li>
            <li><i class="fa-brands fa-facebook text-amber-400 mr-2"></i><strong>Fanpage:</strong> <a href="https://www.facebook.com/profile.php?id=100094536896316" target="_blank" rel="noopener noreferrer" class="hover:text-amber-400">facebook.com/profile.php?id=100094536896316</a></li>
          </ul>
        </div>

        <div class="lg:col-span-3">
          <h4 class="text-sm font-extrabold text-white uppercase mb-3 border-l-4 border-amber-500 pl-2.5">Lĩnh Vực Hoạt Động</h4>
          <ul class="text-xs space-y-2 text-slate-300">
            <li><a href="#linh-vuc-hoat-dong" class="hover:text-amber-400"><i class="fa-solid fa-angle-right text-amber-400 mr-1.5"></i>Thiết kế Kiến trúc – Nội thất</a></li>
            <li><a href="#linh-vuc-hoat-dong" class="hover:text-amber-400"><i class="fa-solid fa-angle-right text-amber-400 mr-1.5"></i>Thi công xây dựng phần thô</a></li>
            <li><a href="#linh-vuc-hoat-dong" class="hover:text-amber-400"><i class="fa-solid fa-angle-right text-amber-400 mr-1.5"></i>Thi công xây dựng hoàn thiện</a></li>
            <li><a href="#linh-vuc-hoat-dong" class="hover:text-amber-400"><i class="fa-solid fa-angle-right text-amber-400 mr-1.5"></i>Xây nhà trọn gói chìa khóa trao tay</a></li>
            <li><a href="#linh-vuc-hoat-dong" class="hover:text-amber-400"><i class="fa-solid fa-angle-right text-amber-400 mr-1.5"></i>Sản xuất &amp; Thi công nội thất</a></li>
          </ul>
        </div>

        <div class="lg:col-span-4">
          <h4 class="text-sm font-extrabold text-white uppercase mb-3 border-l-4 border-amber-500 pl-2.5">Danh Mục Công Trình</h4>
          <ul class="text-xs space-y-2 text-slate-300">
            <li><a href="#cong-trinh-thuc-te" onclick="filterProducts('khach-san')" class="hover:text-amber-400"><i class="fa-solid fa-angle-right text-amber-400 mr-1.5"></i>Khách sạn – Căn hộ – Phòng trọ</a></li>
            <li><a href="#cong-trinh-thuc-te" onclick="filterProducts('biet-thu')" class="hover:text-amber-400"><i class="fa-solid fa-angle-right text-amber-400 mr-1.5"></i>Thiết kế &amp; Thi công Biệt thự</a></li>
            <li><a href="#cong-trinh-thuc-te" onclick="filterProducts('nha-pho')" class="hover:text-amber-400"><i class="fa-solid fa-angle-right text-amber-400 mr-1.5"></i>Thiết kế &amp; Thi công Nhà phố</a></li>
            <li><a href="#cong-trinh-thuc-te" onclick="filterProducts('van-phong')" class="hover:text-amber-400"><i class="fa-solid fa-angle-right text-amber-400 mr-1.5"></i>Thiết kế &amp; Thi công Văn phòng</a></li>
            <li><a href="#du-an-da-nang" class="hover:text-amber-400"><i class="fa-solid fa-angle-right text-amber-400 mr-1.5"></i>Các dự án tiêu biểu tại Đà Nẵng</a></li>
          </ul>
        </div>
      </div>

      <div class="pt-5 text-center text-xs text-slate-400">
        Copyright 2026 © <strong>CÔNG TY TNHH TƯ VẤN VÀ THIẾT KẾ XÂY DỰNG PHÚ GIA PHÁT</strong> (phunggiaphat.com) • 21 Mân Quang 8, Sơn Trà, Đà Nẵng.
      </div>
    </div>
  </footer>

  <!-- ================= CÁC NÚT LIÊN HỆ NỔI BẬT ZALO, FACEBOOK, HOTLINE ================= -->
  <div class="floating-contact-group" aria-label="Nút liên hệ nhanh">
    <a href="tel:0905615563" class="float-btn float-hotline" title="Gọi ngay Hotline 0905 615 563">
      <span class="float-btn-icon"><i class="fa-solid fa-phone-volume"></i></span>
      <span>0905 615 563</span>
    </a>
    <a href="https://zalo.me/0905615563" target="_blank" rel="noopener noreferrer" class="float-btn float-zalo" title="Chat Zalo 0905 615 563">
      <span class="float-btn-icon"><i class="fa-solid fa-comment-dots"></i></span>
      <span>Chat Zalo</span>
    </a>
    <a href="https://www.facebook.com/profile.php?id=100094536896316" target="_blank" rel="noopener noreferrer" class="float-btn float-fb" title="Fanpage Xây Dựng Phú Gia Phát">
      <span class="float-btn-icon"><i class="fa-brands fa-facebook-f"></i></span>
      <span>Fanpage</span>
    </a>
  </div>

  <!-- ================= JAVASCRIPT XỬ LÝ BANNER TỰ TRƯỢT, LỌC DANH MỤC & FORM ================= -->
  <script>
    // 1. Quản lý 2 Banner tự trượt chuyên nghiệp
    let currentSlideIndex = 0;
    const slides = document.querySelectorAll('.hero-slide');
    const dots = document.querySelectorAll('.slide-dot');
    let slideTimer = null;

    function showSlide(index) {
      if (index >= slides.length) currentSlideIndex = 0;
      else if (index < 0) currentSlideIndex = slides.length - 1;
      else currentSlideIndex = index;

      slides.forEach((slide, i) => {
        slide.classList.toggle('active', i === currentSlideIndex);
      });

      dots.forEach((dot, i) => {
        if (i === currentSlideIndex) {
          dot.classList.remove('bg-white/50');
          dot.classList.add('bg-amber-500');
        } else {
          dot.classList.remove('bg-amber-500');
          dot.classList.add('bg-white/50');
        }
      });
    }

    function changeSlide(step) {
      showSlide(currentSlideIndex + step);
      resetSlideTimer();
    }

    function goToSlide(index) {
      showSlide(index);
      resetSlideTimer();
    }

    function resetSlideTimer() {
      if (slideTimer) clearInterval(slideTimer);
      slideTimer = setInterval(() => {
        showSlide(currentSlideIndex + 1);
      }, 5000);
    }

    // 2. Đóng/mở menu trên điện thoại
    function toggleMobileMenu() {
      const drawer = document.getElementById('mobileDrawer');
      drawer.classList.toggle('hidden');
    }

    // 3. Lọc danh mục Công trình thực tế (Bộ 9 ảnh Google Drive)
    function filterProducts(category, btnElement) {
      const items = document.querySelectorAll('#productGrid .product-item');
      items.forEach(item => {
        if (category === 'all' || item.getAttribute('data-category') === category) {
          item.style.display = 'flex';
        } else {
          item.style.display = 'none';
        }
      });

      if (btnElement) {
        const container = btnElement.parentElement;
        container.querySelectorAll('.cat-filter-btn').forEach(btn => btn.classList.remove('active'));
        btnElement.classList.add('active');
      }
    }

    // 4. Lọc danh mục Dự án tại Đà Nẵng (Bộ 10 ảnh Google Drive)
    function filterDaNang(area, btnElement) {
      const items = document.querySelectorAll('#daNangGrid .danang-item');
      items.forEach(item => {
        if (area === 'all' || item.getAttribute('data-area') === area) {
          item.style.display = 'flex';
        } else {
          item.style.display = 'none';
        }
      });

      if (btnElement) {
        const container = btnElement.parentElement;
        container.querySelectorAll('.cat-filter-btn').forEach(btn => btn.classList.remove('active'));
        btnElement.classList.add('active');
      }
    }

    // 5. Xử lý gửi Form Yêu cầu tư vấn & báo giá
    function submitQuoteForm(event) {
      event.preventDefault();
      const name = document.getElementById('custName').value.trim();
      const phone = document.getElementById('custPhone').value.trim();
      const projectType = document.getElementById('projectType').value;
      const budget = document.getElementById('budgetLevel').value;
      const msgBox = document.getElementById('quoteSuccessMsg');

      msgBox.classList.remove('hidden');
      msgBox.innerHTML = 'Cảm ơn Quý khách <strong>' + name + '</strong> (' + phone + ')! Yêu cầu báo giá <strong>' + projectType + '</strong> (Mức đầu tư: ' + budget + ') đã được gửi đến <strong>Công ty Xây dựng Phú Gia Phát</strong>. Kỹ sư sẽ liên hệ tư vấn ngay qua SĐT/Zalo 0905 615 563.';
      document.getElementById('quoteRequestForm').reset();
    }

    window.onload = function () {
      resetSlideTimer();
    };
  </script>
</body>
</html>
