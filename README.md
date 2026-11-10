<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
  <title>Đồ Cổ Đà Nẵng - docodanang.com | Kỷ Vật Thời Gian & Cổ Vật Xưa Uy Tín</title>
  <meta name="description" content="Đồ Cổ Đà Nẵng (docodanang.com) chuyên sưu tầm, giao lưu đèn cổ, đồng hồ xưa, quạt cổ, gốm sứ, tivi, điện thoại cổ, kỷ vật chiến tranh tại 02 Lê Đại Hải Châu, Phường Hòa Cường, Tp.Đà Nẵng. Hotline: 0905.124.408" />

  <!-- Open Graph / Thumbnail là ảnh Logo trang web khi gửi link chia sẻ -->
  <meta property="og:type" content="website" />
  <meta property="og:url" content="https://docodanang.com/" />
  <meta property="og:title" content="Đồ Cổ Đà Nẵng - docodanang.com | Tinh Hoa Cổ Vật & Kỷ Vật Xưa" />
  <meta property="og:description" content="Chuyên giao lưu, sưu tầm đồ cổ, đồ xưa, kỷ vật thời gian tại 02 Lê Đại Hải Châu, Phường Hòa Cường, Tp.Đà Nẵng. ĐT: 0905.124.408" />
  <meta property="og:image" content="https://placehold.co/1200x630/5c1d0c/e6c365?text=DO+CO+DA+NANG+-+DOCODANANG.COM" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:image" content="https://placehold.co/1200x630/5c1d0c/e6c365?text=DO+CO+DA+NANG+-+DOCODANANG.COM" />

  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- Font Awesome Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" />
  <!-- Google Fonts: Inter & Playfair Display -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.googleapis.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Playfair+Display:wght@600;700;800&display=swap" rel="stylesheet" />

  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            brand: {
              dark: '#4a1708',      /* Nâu trầm cổ điển theo màu logo */
              DEFAULT: '#6b230f',   /* Nâu đỏ gụ chủ đạo giống nhadoco.com */
              light: '#8a3319',     /* Nâu đồng nhạt */
              gold: '#c89b3c',      /* Vàng đồng cổ */
              goldLight: '#ebd08e', /* Vàng kem sáng */
              cream: '#fbf8f3',     /* Nền kem cổ điển */
              border: '#e6dccb'     /* Viền ấm */
            }
          },
          fontFamily: {
            sans: ['Inter', 'sans-serif'],
            serif: ['Playfair Display', 'serif']
          },
          maxWidth: {
            'flatsome': '1500px'
          }
        }
      }
    }
  </script>

  <style>
    /* Đảm bảo tuyệt đối không tràn viền, không lệch sang phải trên mọi thiết bị */
    *, *::before, *::after {
      box-sizing: border-box;
    }
    html, body {
      margin: 0;
      padding: 0;
      width: 100%;
      max-width: 100vw;
      overflow-x: hidden;
      font-family: 'Inter', sans-serif;
      background-color: #fbf8f3;
      color: #29201b;
      scroll-behavior: smooth;
    }

    /* Khung chuẩn Flatsome 1500px trên máy tính */
    .container-1500 {
      width: 100%;
      max-width: 1500px;
      margin-left: auto;
      margin-right: auto;
      padding-left: 12px;
      padding-right: 12px;
    }
    @media (min-width: 1024px) {
      .container-1500 {
        padding-left: 20px;
        padding-right: 20px;
      }
    }

    /* Tiêu đề Section chuẩn Flatsome (Section Title Normal / Center) */
    .flatsome-section-title {
      display: flex;
      align-items: center;
      justify-content: space-between;
      border-bottom: 2px solid #e6dccb;
      margin-bottom: 18px;
      padding-bottom: 8px;
      flex-wrap: wrap;
      gap: 8px;
    }
    .flatsome-section-title h2 {
      position: relative;
      font-weight: 700;
      text-transform: uppercase;
      color: #6b230f;
      margin: 0;
      letter-spacing: 0.02em;
    }
    .flatsome-section-title h2::after {
      content: "";
      position: absolute;
      bottom: -10px;
      left: 0;
      width: 100%;
      height: 3px;
      background-color: #c89b3c;
    }

    /* Danh mục trên máy tính: chữ nhỏ gọn, viết liền trên 1 hàng, không tự xuống dòng trong tên danh mục */
    .nav-cat-item {
      white-space: nowrap !important;
      display: inline-flex;
      align-items: center;
      transition: all 0.2s ease;
    }

    /* Badge % giảm giá chuẩn Flatsome góc trên bên trái */
    .flatsome-sale-badge {
      position: absolute;
      top: 8px;
      left: 8px;
      z-index: 10;
      background: #b91c1c;
      color: #ffffff;
      font-weight: 700;
      font-size: 11px;
      line-height: 1;
      padding: 6px 8px;
      border-radius: 9999px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.2);
    }

    /* Tên sản phẩm hiển thị đầy đủ, không bị cắt chữ hay tràn ra ngoài */
    .product-title-full {
      word-wrap: break-word;
      overflow-wrap: break-word;
      white-space: normal;
      line-height: 1.38;
    }

    /* Thanh cuộn mảnh cho danh mục mobile */
    .no-scrollbar::-webkit-scrollbar {
      display: none;
    }
    .no-scrollbar {
      -ms-overflow-style: none;
      scrollbar-width: none;
    }
  </style>
</head>
<body class="bg-brand-cream text-stone-800 antialiased">

  <!-- =====================================================================
       TOP BAR (Đơn giản, chuẩn Flatsome Top Bar, không chứa công cụ UXBuilder)
  ====================================================================== -->
  <div class="bg-brand-dark text-brand-goldLight text-xs py-1.5 border-b border-brand-light/40">
    <div class="container-1500 flex flex-wrap items-center justify-between gap-2">
      <div class="flex items-center gap-2 truncate">
        <i class="fa-solid fa-location-dot text-brand-gold shrink-0"></i>
        <span class="truncate">Địa chỉ: 02 Lê Đại Hải Châu, Phường Hòa Cường, Tp.Đà Nẵng</span>
      </div>
      <div class="hidden md:flex items-center gap-5 shrink-0">
        <span><i class="fa-solid fa-globe text-brand-gold mr-1"></i>Website: <strong>docodanang.com</strong></span>
        <span><i class="fa-solid fa-clock text-brand-gold mr-1"></i>Mở cửa: 08:00 - 21:00 (Hàng ngày)</span>
      </div>
    </div>
  </div>

  <!-- =====================================================================
       HEADER CHÍNH (Logo gọn nhỏ chuyên nghiệp, không để nút gọi ngay tránh tràn viền)
  ====================================================================== -->
  <header class="bg-white border-b border-brand-border sticky top-0 z-40 shadow-sm">
    <div class="container-1500 py-2.5">
      <div class="flex items-center justify-between gap-3">
        
        <!-- Nút mở menu danh mục trên điện thoại -->
        <button id="btnMobileMenu" type="button" onclick="toggleMobileDrawer()" aria-label="Mở danh mục" class="lg:hidden p-2 rounded-lg border border-brand-border text-brand hover:bg-brand-cream shrink-0">
          <i class="fa-solid fa-bars text-lg"></i>
        </button>

        <!-- LOGO MỚI CHUYÊN NGHIỆP - ĐÃ CHỈNH GỌN NHỎ LẠI -->
        <a href="#top" class="flex items-center gap-2.5 shrink-0 group">
          <div class="w-10 h-10 md:w-11 md:h-11 shrink-0">
            <!-- SVG Logo Đồ Cổ Đà Nẵng thiết kế mới gọn nhỏ, sắc nét -->
            <svg viewBox="0 0 100 100" class="w-full h-full drop-shadow-sm" xmlns="http://www.w3.org/2000/svg">
              <defs>
                <linearGradient id="logoBg" x1="0%" y1="0%" x2="100%" y2="100%">
                  <stop offset="0%" stop-color="#6b230f" />
                  <stop offset="100%" stop-color="#3f1205" />
                </linearGradient>
                <linearGradient id="logoGold" x1="0%" y1="0%" x2="100%" y2="100%">
                  <stop offset="0%" stop-color="#f3d999" />
                  <stop offset="50%" stop-color="#c89b3c" />
                  <stop offset="100%" stop-color="#9b701c" />
                </linearGradient>
              </defs>
              <!-- Khung ấn triện tròn cổ điển -->
              <circle cx="50" cy="50" r="47" fill="url(#logoBg)" stroke="url(#logoGold)" stroke-width="4"/>
              <circle cx="50" cy="50" r="41" fill="none" stroke="url(#logoGold)" stroke-width="1" stroke-dasharray="3 2"/>
              <!-- Biểu tượng bình gốm cổ & hoa văn đồng Đông Sơn cách điệu -->
              <path d="M40 24 H60 L56 32 C65 39 67 52 62 64 C59 71 55 74 50 74 C45 74 41 71 38 64 C33 52 35 39 44 32 Z" fill="none" stroke="url(#logoGold)" stroke-width="3.2" stroke-linejoin="round"/>
              <path d="M36 24 H64" stroke="url(#logoGold)" stroke-width="3.2" stroke-linecap="round"/>
              <circle cx="50" cy="50" r="7" fill="url(#logoGold)"/>
              <path d="M34 78 H66" stroke="url(#logoGold)" stroke-width="2.5" stroke-linecap="round"/>
            </svg>
          </div>
          <div class="leading-tight">
            <span class="block font-serif font-bold text-base md:text-lg text-brand tracking-wide">ĐỒ CỔ ĐÀ NẴNG</span>
            <span class="block text-[10px] md:text-[11px] font-medium text-brand-gold tracking-wider uppercase">docodanang.com</span>
          </div>
        </a>

        <!-- Ô TÌM KIẾM SẢN PHẨM (Giống bố cục Flatsome nhadoco.com) -->
        <div class="hidden md:flex flex-1 max-w-xl mx-4">
          <div class="relative w-full flex items-center">
            <input 
              id="desktopSearchInput"
              type="text" 
              oninput="handleSearchProduct(this.value)"
              placeholder="Tìm đồ cổ: đèn măng xông, quạt hòm, đồng hồ, bàn ủi con gà, gốm sứ..." 
              class="w-full pl-3.5 pr-10 py-2 text-xs md:text-sm rounded-l-lg border border-brand-border bg-brand-cream/60 focus:bg-white focus:outline-none focus:border-brand"
            />
            <button type="button" onclick="handleSearchProduct(document.getElementById('desktopSearchInput').value)" class="bg-brand hover:bg-brand-dark text-white px-4 py-2 rounded-r-lg text-xs md:text-sm font-medium transition shrink-0">
              <i class="fa-solid fa-magnifying-glass"></i>
            </button>
          </div>
        </div>

        <!-- MENU TRANG CHÍNH GỌN NHẸ (Không để nút Gọi ngay trên Header để tránh tràn viền) -->
        <nav class="hidden xl:flex items-center gap-4 text-xs font-semibold text-stone-700 shrink-0">
          <a href="#top" class="text-brand hover:text-brand-gold whitespace-nowrap">TRANG CHỦ</a>
          <a href="#san-pham-noi-bat" class="hover:text-brand whitespace-nowrap">SẢN PHẨM</a>
          <a href="#cam-nang-do-co" class="hover:text-brand whitespace-nowrap">CẨM NANG ĐỒ CỔ</a>
          <a href="#doi-tac" class="hover:text-brand whitespace-nowrap">ĐỐI TÁC</a>
          <a href="#bao-gia-lien-he" class="hover:text-brand whitespace-nowrap">BÁO GIÁ & LIÊN HỆ</a>
        </nav>

        <!-- Giỏ hàng / Yêu cầu báo giá gọn nhẹ -->
        <div class="flex items-center gap-2 shrink-0">
          <a href="#bao-gia-lien-he" class="inline-flex items-center gap-1.5 px-2.5 py-1.5 rounded-lg border border-brand/25 bg-brand-cream text-brand text-xs font-semibold hover:bg-brand hover:text-white transition whitespace-nowrap">
            <i class="fa-solid fa-file-signature text-brand-gold"></i>
            <span class="hidden sm:inline">Báo giá</span>
            <span id="quoteCartCount" class="bg-brand text-white text-[10px] px-1.5 py-0.5 rounded-full">0</span>
          </a>
        </div>

      </div>

      <!-- Thanh tìm kiếm trên điện thoại -->
      <div class="mt-2 md:hidden">
        <div class="relative w-full flex items-center">
          <input 
            id="mobileSearchInput"
            type="text" 
            oninput="handleSearchProduct(this.value)"
            placeholder="Tìm kiếm cổ vật, đèn cổ, đồng hồ, gốm sứ..." 
            class="w-full pl-3 pr-9 py-1.5 text-xs rounded-l-lg border border-brand-border bg-brand-cream/60 focus:bg-white focus:outline-none focus:border-brand"
          />
          <button type="button" onclick="handleSearchProduct(document.getElementById('mobileSearchInput').value)" class="bg-brand text-white px-3 py-1.5 rounded-r-lg text-xs">
            <i class="fa-solid fa-magnifying-glass"></i>
          </button>
        </div>
      </div>
    </div>

    <!-- =====================================================================
         THANH DANH MỤC SẢN PHẨM TRÊN MÁY TÍNH (Lấy từ web mẫu nhadoco.com)
         Chữ nhỏ gọn, viết liền trên 1 hàng hoặc xuống hàng 2 nguyên cụm,
         tuyệt đối KHÔNG tự xuống dòng bên trong tên danh mục.
    ====================================================================== -->
    <div class="hidden lg:block bg-brand text-white border-t border-brand-light/40">
      <div class="container-1500 py-1.5">
        <ul class="flex flex-wrap items-center justify-center gap-x-1.5 gap-y-1 text-[11.5px] font-semibold tracking-tight">
          <li>
            <button type="button" onclick="filterByCategory('ALL')" data-cat-btn="ALL" class="nav-cat-item px-2.5 py-1 rounded bg-brand-gold text-brand-dark font-bold">
              <i class="fa-solid fa-border-all mr-1 text-[10px]"></i>TẤT CẢ DANH MỤC
            </button>
          </li>
          <li>
            <button type="button" onclick="filterByCategory('TIVI')" data-cat-btn="TIVI" class="nav-cat-item px-2.5 py-1 rounded hover:bg-brand-dark/70 text-white">
              TIVI XƯA
            </button>
          </li>
          <li>
            <button type="button" onclick="filterByCategory('XE CỔ')" data-cat-btn="XE CỔ" class="nav-cat-item px-2.5 py-1 rounded hover:bg-brand-dark/70 text-white">
              XE CỔ
            </button>
          </li>
          <li>
            <button type="button" onclick="filterByCategory('ĐIỆN THOẠI')" data-cat-btn="ĐIỆN THOẠI" class="nav-cat-item px-2.5 py-1 rounded hover:bg-brand-dark/70 text-white">
              ĐIỆN THOẠI
            </button>
          </li>
          <li>
            <button type="button" onclick="filterByCategory('ĐÈN')" data-cat-btn="ĐÈN" class="nav-cat-item px-2.5 py-1 rounded hover:bg-brand-dark/70 text-white">
              ĐÈN CỔ
            </button>
          </li>
          <li>
            <button type="button" onclick="filterByCategory('BÀN ỦI CON GÀ')" data-cat-btn="BÀN ỦI CON GÀ" class="nav-cat-item px-2.5 py-1 rounded hover:bg-brand-dark/70 text-white">
              BÀN ỦI CON GÀ
            </button>
          </li>
          <li>
            <button type="button" onclick="filterByCategory('TRANH ẢNH')" data-cat-btn="TRANH ẢNH" class="nav-cat-item px-2.5 py-1 rounded hover:bg-brand-dark/70 text-white">
              TRANH ẢNH
            </button>
          </li>
          <li>
            <button type="button" onclick="filterByCategory('GỐM SỨ')" data-cat-btn="GỐM SỨ" class="nav-cat-item px-2.5 py-1 rounded hover:bg-brand-dark/70 text-white">
              GỐM SỨ
            </button>
          </li>
          <li>
            <button type="button" onclick="filterByCategory('ĐỒNG HỒ')" data-cat-btn="ĐỒNG HỒ" class="nav-cat-item px-2.5 py-1 rounded hover:bg-brand-dark/70 text-white">
              ĐỒNG HỒ
            </button>
          </li>
          <li>
            <button type="button" onclick="filterByCategory('ÂM THANH')" data-cat-btn="ÂM THANH" class="nav-cat-item px-2.5 py-1 rounded hover:bg-brand-dark/70 text-white">
              ÂM THANH
            </button>
          </li>
          <li>
            <button type="button" onclick="filterByCategory('QUẠT')" data-cat-btn="QUẠT" class="nav-cat-item px-2.5 py-1 rounded hover:bg-brand-dark/70 text-white">
              QUẠT XƯA
            </button>
          </li>
          <li>
            <button type="button" onclick="filterByCategory('KỶ VẬT CHIẾN TRANH')" data-cat-btn="KỶ VẬT CHIẾN TRANH" class="nav-cat-item px-2.5 py-1 rounded hover:bg-brand-dark/70 text-white">
              KỶ VẬT CHIẾN TRANH
            </button>
          </li>
          <li>
            <button type="button" onclick="filterByCategory('HÀNG SƯU TẦM LIÊN XÔ XƯA')" data-cat-btn="HÀNG SƯU TẦM LIÊN XÔ XƯA" class="nav-cat-item px-2.5 py-1 rounded hover:bg-brand-dark/70 text-white">
              HÀNG SƯU TẦM LIÊN XÔ XƯA
            </button>
          </li>
          <li>
            <button type="button" onclick="filterByCategory('HÀNG SƯU TẦM KHÁC')" data-cat-btn="HÀNG SƯU TẦM KHÁC" class="nav-cat-item px-2.5 py-1 rounded hover:bg-brand-dark/70 text-white">
              HÀNG SƯU TẦM KHÁC
            </button>
          </li>
        </ul>
      </div>
    </div>
  </header>

  <!-- =====================================================================
       DRAWER MENU DANH MỤC TRÊN ĐIỆN THOẠI (Chuẩn Flatsome Mobile Off-Canvas)
  ====================================================================== -->
  <div id="mobileMenuOverlay" class="fixed inset-0 bg-black/50 z-50 hidden" onclick="toggleMobileDrawer()"></div>
  <aside id="mobileMenuDrawer" class="fixed top-0 left-0 bottom-0 w-72 max-w-[82vw] bg-white z-50 transform -translate-x-full transition-transform duration-300 flex flex-col shadow-2xl">
    <div class="p-3.5 bg-brand text-white flex items-center justify-between">
      <div class="flex items-center gap-2">
        <span class="font-serif font-bold text-sm text-brand-goldLight">DANH MỤC ĐỒ CỔ ĐÀ NẴNG</span>
      </div>
      <button type="button" onclick="toggleMobileDrawer()" class="text-white hover:text-brand-gold p-1">
        <i class="fa-solid fa-xmark text-lg"></i>
      </button>
    </div>
    <div class="p-3 overflow-y-auto flex-1 divide-y divide-brand-border/60 text-xs font-medium">
      <button type="button" onclick="filterByCategory('ALL'); toggleMobileDrawer();" class="w-full text-left py-2.5 px-2 font-bold text-brand flex items-center justify-between">
        <span>TẤT CẢ SẢN PHẨM</span>
        <i class="fa-solid fa-chevron-right text-[10px]"></i>
      </button>
      <button type="button" onclick="filterByCategory('TIVI'); toggleMobileDrawer();" class="w-full text-left py-2.5 px-2 hover:bg-brand-cream flex items-center justify-between">
        <span>TIVI (Việt Nam, Liên Xô, Cửa Lùa)</span>
        <i class="fa-solid fa-chevron-right text-[10px] text-stone-400"></i>
      </button>
      <button type="button" onclick="filterByCategory('XE CỔ'); toggleMobileDrawer();" class="w-full text-left py-2.5 px-2 hover:bg-brand-cream flex items-center justify-between">
        <span>XE CỔ (Mobylette, Solex, Xe Pháp)</span>
        <i class="fa-solid fa-chevron-right text-[10px] text-stone-400"></i>
      </button>
      <button type="button" onclick="filterByCategory('ĐIỆN THOẠI'); toggleMobileDrawer();" class="w-full text-left py-2.5 px-2 hover:bg-brand-cream flex items-center justify-between">
        <span>ĐIỆN THOẠI (Quay số, Để bàn, Sừng nai)</span>
        <i class="fa-solid fa-chevron-right text-[10px] text-stone-400"></i>
      </button>
      <button type="button" onclick="filterByCategory('ĐÈN'); toggleMobileDrawer();" class="w-full text-left py-2.5 px-2 hover:bg-brand-cream flex items-center justify-between">
        <span>ĐÈN CỔ (Măng xông, Đèn bão, Châu Âu)</span>
        <i class="fa-solid fa-chevron-right text-[10px] text-stone-400"></i>
      </button>
      <button type="button" onclick="filterByCategory('BÀN ỦI CON GÀ'); toggleMobileDrawer();" class="w-full text-left py-2.5 px-2 hover:bg-brand-cream flex items-center justify-between">
        <span>BÀN ỦI CON GÀ (Việt Nam, 1914)</span>
        <i class="fa-solid fa-chevron-right text-[10px] text-stone-400"></i>
      </button>
      <button type="button" onclick="filterByCategory('TRANH ẢNH'); toggleMobileDrawer();" class="w-full text-left py-2.5 px-2 hover:bg-brand-cream flex items-center justify-between">
        <span>TRANH ẢNH XƯA</span>
        <i class="fa-solid fa-chevron-right text-[10px] text-stone-400"></i>
      </button>
      <button type="button" onclick="filterByCategory('GỐM SỨ'); toggleMobileDrawer();" class="w-full text-left py-2.5 px-2 hover:bg-brand-cream flex items-center justify-between">
        <span>GỐM SỨ (Chén dĩa, Lọ hoa, Ấm trà)</span>
        <i class="fa-solid fa-chevron-right text-[10px] text-stone-400"></i>
      </button>
      <button type="button" onclick="filterByCategory('ĐỒNG HỒ'); toggleMobileDrawer();" class="w-full text-left py-2.5 px-2 hover:bg-brand-cream flex items-center justify-between">
        <span>ĐỒNG HỒ (Để bàn, Treo tường, Đeo dây)</span>
        <i class="fa-solid fa-chevron-right text-[10px] text-stone-400"></i>
      </button>
      <button type="button" onclick="filterByCategory('ÂM THANH'); toggleMobileDrawer();" class="w-full text-left py-2.5 px-2 hover:bg-brand-cream flex items-center justify-between">
        <span>ÂM THANH (Radio, Cassette, Loa kèn)</span>
        <i class="fa-solid fa-chevron-right text-[10px] text-stone-400"></i>
      </button>
      <button type="button" onclick="filterByCategory('QUẠT'); toggleMobileDrawer();" class="w-full text-left py-2.5 px-2 hover:bg-brand-cream flex items-center justify-between">
        <span>QUẠT XƯA (Quạt hòm, Việt Nam, Châu Âu)</span>
        <i class="fa-solid fa-chevron-right text-[10px] text-stone-400"></i>
      </button>
      <button type="button" onclick="filterByCategory('KỶ VẬT CHIẾN TRANH'); toggleMobileDrawer();" class="w-full text-left py-2.5 px-2 hover:bg-brand-cream flex items-center justify-between">
        <span>KỶ VẬT CHIẾN TRANH (Bình tông, Cà mèn)</span>
        <i class="fa-solid fa-chevron-right text-[10px] text-stone-400"></i>
      </button>
      <button type="button" onclick="filterByCategory('HÀNG SƯU TẦM LIÊN XÔ XƯA'); toggleMobileDrawer();" class="w-full text-left py-2.5 px-2 hover:bg-brand-cream flex items-center justify-between">
        <span>HÀNG SƯU TẦM LIÊN XÔ XƯA</span>
        <i class="fa-solid fa-chevron-right text-[10px] text-stone-400"></i>
      </button>
      <button type="button" onclick="filterByCategory('HÀNG SƯU TẦM KHÁC'); toggleMobileDrawer();" class="w-full text-left py-2.5 px-2 hover:bg-brand-cream flex items-center justify-between">
        <span>HÀNG SƯU TẦM KHÁC (Lư đồng, Máy chữ...)</span>
        <i class="fa-solid fa-chevron-right text-[10px] text-stone-400"></i>
      </button>
    </div>
    <div class="p-3 bg-brand-cream border-t border-brand-border text-xs space-y-1">
      <div class="font-bold text-brand">ĐỒ CỔ ĐÀ NẴNG - DOCODANANG.COM</div>
      <div class="text-stone-600">02 Lê Đại Hải Châu, P. Hòa Cường, Đà Nẵng</div>
      <div class="font-bold text-brand">SĐT/Zalo: 0905.124.408</div>
    </div>
  </aside>

  <!-- =====================================================================
       SECTION 1: SLIDER 2 ẢNH BANNER TỰ TRƯỢT KÍCH THƯỚC BẰNG NHAU
       - Có bản thiết kế Banner Máy Tính riêng & Banner Điện Thoại riêng
       - Chữ bên trong ảnh được chỉnh nhỏ gọn, nằm trọn trong khung an toàn,
         tuyệt đối không tràn viền.
  ====================================================================== -->
  <section id="top" class="py-3 md:py-4">
    <div class="container-1500">
      <div class="relative rounded-xl overflow-hidden border border-brand-border shadow-sm bg-brand-dark">

        <!-- ================= SLIDE 1 ================= -->
        <div class="banner-slide block transition-opacity duration-500" data-slide="0">
          
          <!-- ẢNH BANNER 1 TRÊN MÁY TÍNH (Kích thước chuẩn bằng nhau: cao 360px) -->
          <div class="hidden md:flex relative w-full h-[360px] items-center overflow-hidden bg-gradient-to-r from-[#3b1105] via-[#5e1e0c] to-[#3b1105]">
            <!-- Hoa văn SVG nền máy tính -->
            <svg class="absolute inset-0 w-full h-full opacity-15 pointer-events-none" viewBox="0 0 1500 360" preserveAspectRatio="none">
              <circle cx="1220" cy="180" r="220" fill="none" stroke="#ebd08e" stroke-width="2" stroke-dasharray="6 6"/>
              <circle cx="1220" cy="180" r="165" fill="none" stroke="#ebd08e" stroke-width="1.5"/>
              <rect x="24" y="20" width="1452" height="320" rx="12" fill="none" stroke="#ebd08e" stroke-width="1.5"/>
            </svg>

            <div class="relative z-10 w-full grid grid-cols-12 items-center px-12 gap-6">
              <!-- Khối chữ gọn nhỏ nằm trọn trong khung ảnh máy tính -->
              <div class="col-span-7 text-white space-y-2.5 pr-4">
                <div class="inline-block px-3 py-1 rounded-full bg-brand-gold/20 border border-brand-gold text-brand-goldLight text-xs font-semibold tracking-wider uppercase">
                  ĐỒ CỔ ĐÀ NẴNG • DOCODANANG.COM
                </div>
                <h1 class="font-serif text-2xl lg:text-3xl font-bold text-brand-goldLight leading-snug">
                  Gìn Giữ Ký Ức Thời Gian &amp; Tinh Hoa Cổ Vật Xưa Tại Đà Nẵng
                </h1>
                <p class="text-xs lg:text-sm text-stone-200 max-w-xl leading-relaxed">
                  Chuyên sưu tầm, giao lưu và thẩm định: Đèn măng xông cổ, Quạt hòm xưa, Đồng hồ cổ, Gốm sứ, Điện thoại quay số, Tivi cửa lùa &amp; Kỷ vật xưa nguyên bản.
                </p>
                <div class="pt-1 flex flex-wrap items-center gap-4 text-xs text-brand-goldLight font-medium">
                  <span><i class="fa-solid fa-location-dot text-brand-gold mr-1.5"></i>02 Lê Đại Hải Châu, P. Hòa Cường, Tp.Đà Nẵng</span>
                  <span><i class="fa-solid fa-phone-volume text-brand-gold mr-1.5"></i>Hotline/Zalo: <strong>0905.124.408</strong></span>
                </div>
                <div class="pt-1 flex items-center gap-3">
                  <a href="#san-pham-noi-bat" class="px-4 py-2 rounded-lg bg-brand-gold hover:bg-brand-goldLight text-brand-dark font-bold text-xs transition shadow">
                    KHÁM PHÁ CỔ VẬT
                  </a>
                  <a href="#bao-gia-lien-he" class="px-4 py-2 rounded-lg border border-brand-goldLight/60 hover:bg-white/10 text-white font-semibold text-xs transition">
                    YÊU CẦU BÁO GIÁ
                  </a>
                </div>
              </div>

              <!-- Khối hình thực tế trong banner máy tính -->
              <div class="col-span-5 flex items-center justify-center gap-3">
                <div class="w-40 h-56 rounded-lg overflow-hidden border-2 border-brand-gold shadow-lg bg-stone-900 shrink-0">
                  <img src="https://drive.google.com/thumbnail?id=1H0mGjMkomcuk1ngaBw3r8PZeyU9pjBBw&sz=w800" data-drive-id="1H0mGjMkomcuk1ngaBw3r8PZeyU9pjBBw" alt="Cổ vật Đà Nẵng 1" class="w-full h-full object-cover" onerror="handleDriveImgError(this)" />
                </div>
                <div class="w-40 h-56 rounded-lg overflow-hidden border-2 border-brand-gold shadow-lg bg-stone-900 shrink-0 hidden lg:block">
                  <img src="https://drive.google.com/thumbnail?id=1re65R4tQ6Ah34BWF2ZACbO4Cla_8LnU9&sz=w800" data-drive-id="1re65R4tQ6Ah34BWF2ZACbO4Cla_8LnU9" alt="Cổ vật Đà Nẵng 2" class="w-full h-full object-cover" onerror="handleDriveImgError(this)" />
                </div>
              </div>
            </div>
          </div>

          <!-- ẢNH BANNER 1 THIẾT KẾ MỚI RIÊNG CHO ĐIỆN THOẠI (Cao đúng 220px, chữ nhỏ gọn không tràn viền) -->
          <div class="flex md:hidden relative w-full h-[220px] items-center overflow-hidden bg-gradient-to-br from-[#471406] via-[#6b230f] to-[#380f04] px-4 py-3">
            <div class="absolute inset-1.5 border border-brand-gold/40 rounded-lg pointer-events-none"></div>
            <div class="relative z-10 w-full grid grid-cols-12 items-center gap-2.5">
              <div class="col-span-8 space-y-1 text-white pr-1">
                <span class="inline-block px-2 py-0.5 rounded bg-brand-gold/25 text-brand-goldLight text-[10px] font-bold uppercase">
                  docodanang.com
                </span>
                <h2 class="font-serif text-sm font-bold text-brand-goldLight leading-tight">
                  ĐỒ CỔ ĐÀ NẴNG - KỶ VẬT THỜI GIAN
                </h2>
                <p class="text-[11px] text-stone-200 leading-snug">
                  Chuyên đèn cổ, đồng hồ, quạt xưa, gốm sứ, điện thoại &amp; đồ sưu tầm.
                </p>
                <div class="text-[10px] text-brand-goldLight leading-tight pt-0.5">
                  <div><i class="fa-solid fa-location-dot mr-1"></i>02 Lê Đại Hải Châu, P.Hòa Cường, ĐN</div>
                  <div class="mt-0.5"><i class="fa-solid fa-phone mr-1"></i>SĐT: <strong>0905.124.408</strong></div>
                </div>
              </div>
              <div class="col-span-4 flex justify-end">
                <div class="w-24 h-32 rounded-lg overflow-hidden border border-brand-gold shadow bg-stone-900 shrink-0">
                  <img src="https://drive.google.com/thumbnail?id=1H0mGjMkomcuk1ngaBw3r8PZeyU9pjBBw&sz=w600" data-drive-id="1H0mGjMkomcuk1ngaBw3r8PZeyU9pjBBw" alt="Đồ Cổ Đà Nẵng Mobile 1" class="w-full h-full object-cover" onerror="handleDriveImgError(this)" />
                </div>
              </div>
            </div>
          </div>

        </div>

        <!-- ================= SLIDE 2 ================= -->
        <div class="banner-slide hidden transition-opacity duration-500" data-slide="1">
          
          <!-- ẢNH BANNER 2 TRÊN MÁY TÍNH (Kích thước chuẩn bằng nhau: cao 360px) -->
          <div class="hidden md:flex relative w-full h-[360px] items-center overflow-hidden bg-gradient-to-r from-[#2c1810] via-[#5c2210] to-[#2c1810]">
            <svg class="absolute inset-0 w-full h-full opacity-15 pointer-events-none" viewBox="0 0 1500 360" preserveAspectRatio="none">
              <circle cx="280" cy="180" r="210" fill="none" stroke="#ebd08e" stroke-width="2" stroke-dasharray="8 6"/>
              <rect x="24" y="20" width="1452" height="320" rx="12" fill="none" stroke="#ebd08e" stroke-width="1.5"/>
            </svg>

            <div class="relative z-10 w-full grid grid-cols-12 items-center px-12 gap-6">
              <div class="col-span-7 text-white space-y-2.5 pr-4">
                <div class="inline-block px-3 py-1 rounded-full bg-brand-gold/20 border border-brand-gold text-brand-goldLight text-xs font-semibold tracking-wider uppercase">
                  SƯU TẦM &amp; GIAO LƯU CỔ VẬT TOÀN QUỐC
                </div>
                <h2 class="font-serif text-2xl lg:text-3xl font-bold text-brand-goldLight leading-snug">
                  Không Gian Hoài Niệm Xưa - Chuẩn Giá Trị Thật &amp; Nguyên Bản
                </h2>
                <p class="text-xs lg:text-sm text-stone-200 max-w-xl leading-relaxed">
                  Tư vấn bài trí không gian xưa, quán cà phê cổ điển, nhà gỗ truyền thống. Nhận ký gửi, thu mua và định giá cổ vật uy tín tại Đà Nẵng.
                </p>
                <div class="pt-1 flex flex-wrap items-center gap-4 text-xs text-brand-goldLight font-medium">
                  <span><i class="fa-solid fa-map-location-dot text-brand-gold mr-1.5"></i>02 Lê Đại Hải Châu, P. Hòa Cường, Tp.Đà Nẵng</span>
                  <span><i class="fa-solid fa-headset text-brand-gold mr-1.5"></i>Tư vấn 24/7: <strong>0905.124.408</strong></span>
                </div>
                <div class="pt-1 flex items-center gap-3">
                  <a href="#bao-gia-lien-he" class="px-4 py-2 rounded-lg bg-brand-gold hover:bg-brand-goldLight text-brand-dark font-bold text-xs transition shadow">
                    NHẬN BÁO GIÁ NGAY
                  </a>
                  <a href="#ban-do-trang-chu" class="px-4 py-2 rounded-lg border border-brand-goldLight/60 hover:bg-white/10 text-white font-semibold text-xs transition">
                    XEM BẢN ĐỒ CỬA HÀNG
                  </a>
                </div>
              </div>

              <div class="col-span-5 flex items-center justify-center gap-3">
                <div class="w-40 h-56 rounded-lg overflow-hidden border-2 border-brand-gold shadow-lg bg-stone-900 shrink-0">
                  <img src="https://drive.google.com/thumbnail?id=19MJehNTgG1y8yj-3QX1HriLZqvv5wVnh&sz=w800" data-drive-id="19MJehNTgG1y8yj-3QX1HriLZqvv5wVnh" alt="Cổ vật Đà Nẵng 3" class="w-full h-full object-cover" onerror="handleDriveImgError(this)" />
                </div>
                <div class="w-40 h-56 rounded-lg overflow-hidden border-2 border-brand-gold shadow-lg bg-stone-900 shrink-0 hidden lg:block">
                  <img src="https://drive.google.com/thumbnail?id=1PK6y5m52N7Eh5fuLZHRUmfHkwbljGR3C&sz=w800" data-drive-id="1PK6y5m52N7Eh5fuLZHRUmfHkwbljGR3C" alt="Cổ vật Đà Nẵng 4" class="w-full h-full object-cover" onerror="handleDriveImgError(this)" />
                </div>
              </div>
            </div>
          </div>

          <!-- ẢNH BANNER 2 THIẾT KẾ MỚI RIÊNG CHO ĐIỆN THOẠI (Cao đúng 220px, chữ nhỏ gọn không tràn viền) -->
          <div class="flex md:hidden relative w-full h-[220px] items-center overflow-hidden bg-gradient-to-br from-[#2c1810] via-[#5c2210] to-[#3a1207] px-4 py-3">
            <div class="absolute inset-1.5 border border-brand-gold/40 rounded-lg pointer-events-none"></div>
            <div class="relative z-10 w-full grid grid-cols-12 items-center gap-2.5">
              <div class="col-span-8 space-y-1 text-white pr-1">
                <span class="inline-block px-2 py-0.5 rounded bg-brand-gold/25 text-brand-goldLight text-[10px] font-bold uppercase">
                  UY TÍN - CHẤT LƯỢNG
                </span>
                <h2 class="font-serif text-sm font-bold text-brand-goldLight leading-tight">
                  GIAO LƯU &amp; THẨM ĐỊNH ĐỒ XƯA ĐÀ NẴNG
                </h2>
                <p class="text-[11px] text-stone-200 leading-snug">
                  Kiểm định kỹ lưỡng độ tuổi &amp; chất lượng. Giao hàng toàn quốc an toàn.
                </p>
                <div class="text-[10px] text-brand-goldLight leading-tight pt-0.5">
                  <div><i class="fa-solid fa-location-dot mr-1"></i>02 Lê Đại Hải Châu, P.Hòa Cường, ĐN</div>
                  <div class="mt-0.5"><i class="fa-solid fa-phone mr-1"></i>Hotline: <strong>0905.124.408</strong></div>
                </div>
              </div>
              <div class="col-span-4 flex justify-end">
                <div class="w-24 h-32 rounded-lg overflow-hidden border border-brand-gold shadow bg-stone-900 shrink-0">
                  <img src="https://drive.google.com/thumbnail?id=19MJehNTgG1y8yj-3QX1HriLZqvv5wVnh&sz=w600" data-drive-id="19MJehNTgG1y8yj-3QX1HriLZqvv5wVnh" alt="Đồ Cổ Đà Nẵng Mobile 2" class="w-full h-full object-cover" onerror="handleDriveImgError(this)" />
                </div>
              </div>
            </div>
          </div>

        </div>

        <!-- Nút điều hướng & chấm tròn chuyển Slide -->
        <button type="button" onclick="changeSlide(-1)" aria-label="Slide trước" class="absolute left-2 top-1/2 -translate-y-1/2 w-7 h-7 md:w-8 md:h-8 rounded-full bg-black/40 hover:bg-brand-gold text-white hover:text-brand-dark flex items-center justify-center transition z-20">
          <i class="fa-solid fa-chevron-left text-xs"></i>
        </button>
        <button type="button" onclick="changeSlide(1)" aria-label="Slide tiếp" class="absolute right-2 top-1/2 -translate-y-1/2 w-7 h-7 md:w-8 md:h-8 rounded-full bg-black/40 hover:bg-brand-gold text-white hover:text-brand-dark flex items-center justify-center transition z-20">
          <i class="fa-solid fa-chevron-right text-xs"></i>
        </button>
        <div class="absolute bottom-2 left-1/2 -translate-x-1/2 flex items-center gap-2 z-20">
          <button type="button" onclick="goToSlide(0)" class="slide-dot w-2.5 h-2.5 rounded-full bg-brand-gold transition" aria-label="Banner 1"></button>
          <button type="button" onclick="goToSlide(1)" class="slide-dot w-2.5 h-2.5 rounded-full bg-white/50 transition" aria-label="Banner 2"></button>
        </div>

      </div>
    </div>
  </section>

  <!-- =====================================================================
       SECTION 2: DANH MỤC SẢN PHẨM TRANG CHỦ (Lấy đúng danh mục web mẫu nhadoco.com)
       - Chữ danh mục ở trang chủ nhỏ gọn, viết liền trên 1 hàng, không rớt chữ
       - Thiết kế đẹp mắt trên cả máy tính và điện thoại
  ====================================================================== -->
  <section class="py-3">
    <div class="container-1500">
      <div class="bg-white rounded-xl border border-brand-border p-3 md:p-4 shadow-sm">
        <div class="flatsome-section-title">
          <h2 class="text-sm md:text-base">DANH MỤC SẢN PHẨM ĐỒ CỔ</h2>
          <span class="text-[11px] text-stone-500">Chọn danh mục để lọc cổ vật nhanh</span>
        </div>

        <!-- Lưới danh mục: chữ nhỏ gọn, whitespace-nowrap để không bao giờ bị xuống dòng tên danh mục -->
        <div id="homepageCategoryGrid" class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-7 gap-2">
          <!-- Render động từ danh sách chuẩn nhadoco.com -->
        </div>
      </div>
    </div>
  </section>

  <!-- =====================================================================
       SECTION 3: SẢN PHẨM NỔI BẬT (14 ẢNH THỰC TẾ TRONG FILE GOOGLE DRIVE)
       - Chia 2 cột trên điện thoại (grid-cols-2), 4-5 cột trên máy tính
       - Góc trên bên trái có % giảm giá chuẩn Flatsome (-16%, -20%...)
       - Không để các nhãn dán rườm rà ở trang chủ
       - Tên sản phẩm hiển thị đầy đủ, không bị tràn hoặc thiếu chữ
  ====================================================================== -->
  <section id="san-pham-noi-bat" class="py-4">
    <div class="container-1500">
      <div class="bg-white rounded-xl border border-brand-border p-3 md:p-5 shadow-sm">
        
        <div class="flatsome-section-title">
          <div>
            <h2 id="currentCategoryTitle" class="text-sm md:text-lg">SẢN PHẨM NỔI BẬT</h2>
          </div>
          <div class="flex items-center gap-2 text-xs">
            <span id="productCountBadge" class="text-stone-600 font-medium">Hiển thị 14 sản phẩm</span>
            <button type="button" onclick="filterByCategory('ALL')" class="px-2.5 py-1 rounded border border-brand text-brand hover:bg-brand hover:text-white font-semibold transition text-[11px] whitespace-nowrap">
              Xem tất cả
            </button>
          </div>
        </div>

        <!-- Lưới sản phẩm: 2 cột trên điện thoại (grid-cols-2), 4 cột tablet, 5 cột desktop 1500px -->
        <div id="featuredProductsGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 xl:grid-cols-5 gap-2.5 md:gap-4">
          <!-- Được render bằng JS từ 14 file ảnh Google Drive thực tế -->
        </div>

      </div>
    </div>
  </section>

  <!-- =====================================================================
       SECTION 4: HÀNG SƯU TẦM LIÊN XÔ XƯA & ĐÈN CỔ - ĐỒNG HỒ XƯA (Giống nhadoco.com)
  ====================================================================== -->
  <section class="py-3">
    <div class="container-1500">
      <div class="bg-white rounded-xl border border-brand-border p-3 md:p-5 shadow-sm">
        <div class="flatsome-section-title">
          <h2 class="text-sm md:text-lg">HÀNG SƯU TẦM LIÊN XÔ XƯA &amp; ĐỒ ĐỒNG CỔ</h2>
          <a href="#bao-gia-lien-he" class="text-xs font-semibold text-brand hover:underline whitespace-nowrap">Nhận báo giá sỉ &amp; lẻ &raquo;</a>
        </div>
        <!-- Chia 2 cột trên điện thoại, 5 cột trên máy tính -->
        <div id="sovietProductsGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-2.5 md:gap-4">
          <!-- Render tự động từ dữ liệu sản phẩm -->
        </div>
      </div>
    </div>
  </section>

  <!-- =====================================================================
       SECTION 5: FORM YÊU CẦU TƯ VẤN & BÁO GIÁ + FANPAGE FACEBOOK TRANG CHỦ
       - Đưa Fanpage Đồ Cổ Đà Nẵng ra ngoài trang chủ
       - Thêm Form yêu cầu và báo giá ngay tại trang chủ
  ====================================================================== -->
  <section id="bao-gia-lien-he" class="py-4">
    <div class="container-1500">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-4">
        
        <!-- CỘT TRÁI (7 CỘT): FORM YÊU CẦU TƯ VẤN & BÁO GIÁ ĐỒ CỔ -->
        <div class="lg:col-span-7 bg-white rounded-xl border border-brand-border p-4 md:p-6 shadow-sm">
          <div class="flatsome-section-title">
            <h2 class="text-sm md:text-lg">YÊU CẦU TƯ VẤN &amp; BÁO GIÁ ĐỒ CỔ</h2>
            <span class="text-xs text-brand font-semibold">Hotline/Zalo: 0905.124.408</span>
          </div>

          <p class="text-xs md:text-sm text-stone-600 mb-4">
            Quý khách cần báo giá chi tiết sản phẩm, đặt mua kỷ vật xưa hoặc ký gửi thẩm định đồ cổ tại <strong>Đồ Cổ Đà Nẵng (docodanang.com)</strong>, vui lòng để lại thông tin bên dưới:
          </p>

          <form id="quoteForm" onsubmit="submitQuoteForm(event)" class="space-y-3">
            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
              <div>
                <label class="block text-xs font-semibold text-stone-700 mb-1">Họ và tên quý khách *</label>
                <input id="qName" type="text" required placeholder="Nhập họ và tên..." class="w-full px-3 py-2 text-xs md:text-sm rounded-lg border border-brand-border bg-brand-cream/40 focus:bg-white focus:outline-none focus:border-brand" />
              </div>
              <div>
                <label class="block text-xs font-semibold text-stone-700 mb-1">Số điện thoại / Zalo *</label>
                <input id="qPhone" type="tel" required placeholder="Ví dụ: 0905124408" class="w-full px-3 py-2 text-xs md:text-sm rounded-lg border border-brand-border bg-brand-cream/40 focus:bg-white focus:outline-none focus:border-brand" />
              </div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
              <div>
                <label class="block text-xs font-semibold text-stone-700 mb-1">Danh mục quan tâm</label>
                <select id="qCategory" class="w-full px-3 py-2 text-xs md:text-sm rounded-lg border border-brand-border bg-brand-cream/40 focus:bg-white focus:outline-none focus:border-brand">
                  <option value="Tư vấn báo giá mua đồ cổ">Báo giá mua sản phẩm đồ cổ</option>
                  <option value="Đèn cổ - Đèn măng xông">Đèn cổ (Petromax, Aida, Đèn bão)</option>
                  <option value="Quạt cổ - Đồng hồ xưa">Quạt hòm xưa &amp; Đồng hồ cổ</option>
                  <option value="Tivi - Điện thoại - Âm thanh xưa">Tivi, Điện thoại quay số, Máy hát</option>
                  <option value="Gốm sứ - Lư đồng - Bàn ủi con gà">Gốm sứ, Lư đồng, Bàn ủi con gà</option>
                  <option value="Ký gửi - Định giá cổ vật">Ký gửi / Thẩm định cổ vật xưa</option>
                </select>
              </div>
              <div>
                <label class="block text-xs font-semibold text-stone-700 mb-1">Sản phẩm đã chọn báo giá</label>
                <input id="qProductSelected" type="text" placeholder="Chọn từ danh sách hoặc nhập tên SP..." class="w-full px-3 py-2 text-xs md:text-sm rounded-lg border border-brand-border bg-brand-cream/40 focus:bg-white focus:outline-none focus:border-brand" />
              </div>
            </div>

            <div>
              <label class="block text-xs font-semibold text-stone-700 mb-1">Nội dung yêu cầu chi tiết</label>
              <textarea id="qNote" rows="3" placeholder="Nhập yêu cầu xem thêm ảnh/video thực tế, báo giá vận chuyển hoặc địa chỉ nhận hàng..." class="w-full px-3 py-2 text-xs md:text-sm rounded-lg border border-brand-border bg-brand-cream/40 focus:bg-white focus:outline-none focus:border-brand"></textarea>
            </div>

            <div class="flex flex-wrap items-center justify-between gap-3 pt-1">
              <div class="text-[11px] text-stone-500">
                <i class="fa-solid fa-shield-halved text-brand-gold mr-1"></i>Cam kết cổ vật chuẩn xưa - Giao hàng đảm bảo toàn quốc
              </div>
              <button type="submit" class="px-5 py-2.5 rounded-lg bg-brand hover:bg-brand-dark text-white font-bold text-xs md:text-sm transition shadow flex items-center gap-2">
                <i class="fa-solid fa-paper-plane"></i>
                <span>GỬI YÊU CẦU BÁO GIÁ</span>
              </button>
            </div>
          </form>

          <!-- Hộp thông báo gửi thành công -->
          <div id="quoteSuccessBox" class="hidden mt-3 p-3 rounded-lg bg-emerald-50 border border-emerald-300 text-emerald-900 text-xs">
            <div class="font-bold flex items-center gap-1.5">
              <i class="fa-solid fa-circle-check text-emerald-600 text-sm"></i>
              <span>Đã ghi nhận yêu cầu báo giá của quý khách!</span>
            </div>
            <p id="quoteSuccessDetail" class="mt-1 text-emerald-800"></p>
          </div>
        </div>

        <!-- CỘT PHẢI (5 CỘT): ĐƯA FANPAGE ĐỒ CỔ ĐÀ NẴNG RA NGOÀI TRANG CHỦ -->
        <div class="lg:col-span-5 bg-white rounded-xl border border-brand-border p-4 md:p-6 shadow-sm flex flex-col justify-between">
          <div>
            <div class="flatsome-section-title">
              <h2 class="text-sm md:text-lg">FANPAGE ĐỒ CỔ ĐÀ NẴNG</h2>
              <a href="https://www.facebook.com/docodanang?locale=vi_VN" target="_blank" rel="noopener noreferrer" class="text-xs font-semibold text-blue-700 hover:underline whitespace-nowrap">
                <i class="fa-brands fa-facebook mr-1"></i>Mở Fanpage
              </a>
            </div>

            <!-- Thẻ Fanpage trực quan + Iframe Facebook Plugin chuẩn -->
            <div class="rounded-xl border border-brand-border overflow-hidden bg-brand-cream/50">
              <div class="bg-gradient-to-r from-brand-dark to-brand p-3.5 text-white flex items-center justify-between gap-2">
                <div class="flex items-center gap-2.5 min-w-0">
                  <div class="w-11 h-11 rounded-full bg-white p-1 shrink-0 border-2 border-brand-gold flex items-center justify-center">
                    <span class="font-serif font-bold text-brand text-xs">ĐCĐN</span>
                  </div>
                  <div class="min-w-0">
                    <a href="https://www.facebook.com/docodanang?locale=vi_VN" target="_blank" rel="noopener noreferrer" class="font-bold text-sm text-brand-goldLight hover:underline block truncate">
                      Đồ Cổ Đà Nẵng - Cổ Xưa Đà Thành
                    </a>
                    <span class="text-[11px] text-stone-200 block truncate">@docodanang • Cửa hàng đồ cổ &amp; kỷ vật xưa</span>
                  </div>
                </div>
                <a href="https://www.facebook.com/docodanang?locale=vi_VN" target="_blank" rel="noopener noreferrer" class="px-3 py-1.5 rounded-lg bg-blue-600 hover:bg-blue-700 text-white text-xs font-semibold shrink-0 flex items-center gap-1 shadow">
                  <i class="fa-brands fa-facebook-f"></i>
                  <span>Theo dõi</span>
                </a>
              </div>

              <!-- Khung nhúng Facebook Page Plugin thực tế -->
              <div class="w-full overflow-hidden bg-white flex justify-center py-2 border-b border-brand-border">
                <iframe 
                  title="Fanpage Đồ Cổ Đà Nẵng"
                  src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fdocodanang&tabs=timeline&width=340&height=220&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true" 
                  width="340" 
                  height="220" 
                  style="border:none;overflow:hidden;max-width:100%;" 
                  scrolling="no" 
                  frameborder="0" 
                  allowfullscreen="true" 
                  allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share">
                </iframe>
              </div>

              <div class="p-3 text-xs space-y-1.5 text-stone-700">
                <div class="flex items-start gap-2">
                  <i class="fa-solid fa-location-dot text-brand mt-0.5 shrink-0"></i>
                  <span><strong>Địa chỉ:</strong> 02 Lê Đại Hải Châu, Phường Hòa Cường, Tp.Đà Nẵng</span>
                </div>
                <div class="flex items-center gap-2">
                  <i class="fa-solid fa-phone text-brand shrink-0"></i>
                  <span><strong>Điện thoại / Zalo:</strong> <a href="tel:0905124408" class="font-bold text-brand hover:underline">0905.124.408</a></span>
                </div>
                <div class="flex items-center gap-2">
                  <i class="fa-brands fa-facebook text-blue-600 shrink-0"></i>
                  <a href="https://www.facebook.com/docodanang?locale=vi_VN" target="_blank" rel="noopener noreferrer" class="text-blue-700 hover:underline truncate">
                    https://www.facebook.com/docodanang
                  </a>
                </div>
              </div>
            </div>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- =====================================================================
       SECTION 6: ĐƯA ẢNH GOOGLE MAP RA NGOÀI TRANG CHỦ
       Địa chỉ: 02 Lê Đại Hải Châu, Phường Hòa Cường, Tp.Đà Nẵng | SĐT: 0905.124.408
  ====================================================================== -->
  <section id="ban-do-trang-chu" class="py-3">
    <div class="container-1500">
      <div class="bg-white rounded-xl border border-brand-border p-3 md:p-5 shadow-sm">
        <div class="flatsome-section-title">
          <h2 class="text-sm md:text-lg">BẢN ĐỒ ĐƯỜNG ĐI ĐẾN ĐỒ CỔ ĐÀ NẴNG</h2>
          <a href="https://www.google.com/maps/search/?api=1&query=02+L%C3%AA+%C4%90%E1%BA%A1i+H%E1%BA%A3i+Ch%C3%A2u+Ph%C6%B0%E1%BB%9Dng+H%C3%B2a+C%C6%B0%E1%BB%9Dng+%C4%90%C3%A0+N%E1%BA%B5ng" target="_blank" rel="noopener noreferrer" class="text-xs font-semibold text-brand hover:underline whitespace-nowrap">
            <i class="fa-solid fa-diamond-turn-right mr-1"></i>Chỉ đường trên Google Maps
          </a>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-12 gap-4 items-center">
          <div class="lg:col-span-4 space-y-2.5 text-xs md:text-sm bg-brand-cream p-4 rounded-xl border border-brand-border">
            <div class="font-serif font-bold text-base text-brand">CỬA HÀNG ĐỒ CỔ ĐÀ NẴNG</div>
            <p class="text-stone-600 leading-relaxed">
              Không gian trưng bày và giao lưu hàng trăm hiện vật cổ xưa: đèn dầu, đèn măng xông, đồng hồ cổ, gốm sứ, quạt xưa, xe cổ và kỷ vật thời gian ngay trung tâm Đà Nẵng.
            </p>
            <div class="space-y-1.5 pt-1 text-stone-800">
              <div><i class="fa-solid fa-location-dot text-brand mr-2"></i><strong>Địa chỉ:</strong> 02 Lê Đại Hải Châu, Phường Hòa Cường, Tp.Đà Nẵng</div>
              <div><i class="fa-solid fa-phone-volume text-brand mr-2"></i><strong>SĐT / Zalo:</strong> <a href="tel:0905124408" class="text-brand font-bold">0905.124.408</a></div>
              <div><i class="fa-solid fa-globe text-brand mr-2"></i><strong>Website:</strong> docodanang.com</div>
            </div>
            <div class="pt-2">
              <a href="https://www.google.com/maps/search/?api=1&query=02+L%C3%AA+%C4%90%E1%BA%A1i+H%E1%BA%A3i+Ch%C3%A2u+Ph%C6%B0%E1%BB%9Dng+H%C3%B2a+C%C6%B0%E1%BB%9Dng+%C4%90%C3%A0+N%E1%BA%B5ng" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-2 px-4 py-2 rounded-lg bg-brand text-white text-xs font-semibold hover:bg-brand-dark transition">
                <i class="fa-solid fa-map-location-dot"></i>
                <span>Mở Bản Đồ Lớn</span>
              </a>
            </div>
          </div>

          <div class="lg:col-span-8 w-full h-[260px] md:h-[320px] rounded-xl overflow-hidden border border-brand-border shadow-inner bg-stone-100">
            <iframe 
              title="Bản đồ Google Map Đồ Cổ Đà Nẵng 02 Lê Đại"
              src="https://maps.google.com/maps?q=02%20L%C3%AA%20%C4%90%E1%BA%A1i,%20H%C3%B2a%20C%C6%B0%E1%BB%9Dng,%20H%E1%BA%A3i%20Ch%C3%A2u,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed" 
              class="w-full h-full border-0" 
              loading="lazy" 
              referrerpolicy="no-referrer-when-downgrade">
            </iframe>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- =====================================================================
       SECTION 7: CẨM NANG ĐỒ CỔ - DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (Giống nhadoco.com)
  ====================================================================== -->
  <section id="cam-nang-do-co" class="py-4">
    <div class="container-1500">
      <div class="bg-white rounded-xl border border-brand-border p-3 md:p-5 shadow-sm">
        <div class="flatsome-section-title">
          <h2 class="text-sm md:text-lg">CẨM NANG ĐỒ CỔ &amp; BÀI VIẾT MỚI</h2>
          <span class="text-xs text-stone-500">Kiến thức sưu tầm &amp; bảo quản cổ vật xưa</span>
        </div>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-3.5">
          <!-- Bài viết 1 -->
          <article class="rounded-xl border border-brand-border overflow-hidden bg-brand-cream/30 hover:shadow-md transition flex flex-col">
            <div class="h-40 overflow-hidden bg-stone-200">
              <img src="https://drive.google.com/thumbnail?id=1re65R4tQ6Ah34BWF2ZACbO4Cla_8LnU9&sz=w600" data-drive-id="1re65R4tQ6Ah34BWF2ZACbO4Cla_8LnU9" alt="Thú chơi đèn măng xông cổ" class="w-full h-full object-cover hover:scale-105 transition duration-300" onerror="handleDriveImgError(this)" />
            </div>
            <div class="p-3 flex-1 flex flex-col justify-between">
              <div>
                <div class="text-[11px] text-stone-500 mb-1"><i class="fa-regular fa-calendar mr-1"></i>Cẩm nang đồ cổ • 2.950 lượt xem</div>
                <h3 class="font-bold text-xs md:text-sm text-brand leading-snug mb-1.5">
                  Cách nhận biết đèn măng xông Petromax &amp; Aida Express nguyên bản Đức
                </h3>
                <p class="text-xs text-stone-600 line-clamp-3">
                  Đèn măng xông cổ không chỉ là vật dụng chiếu sáng một thời mà còn là tuyệt tác cơ khí được giới sưu tầm tại Đà Nẵng săn đón...
                </p>
              </div>
              <a href="#bao-gia-lien-he" class="mt-2.5 inline-block text-xs font-semibold text-brand hover:text-brand-gold">Xem chi tiết &raquo;</a>
            </div>
          </article>

          <!-- Bài viết 2 -->
          <article class="rounded-xl border border-brand-border overflow-hidden bg-brand-cream/30 hover:shadow-md transition flex flex-col">
            <div class="h-40 overflow-hidden bg-stone-200">
              <img src="https://drive.google.com/thumbnail?id=1qsK7L0tyzMV6rOgDxH2NsO0Q6rVnYqlB&sz=w600" data-drive-id="1qsK7L0tyzMV6rOgDxH2NsO0Q6rVnYqlB" alt="Chén chấm xưa Lái Thiêu" class="w-full h-full object-cover hover:scale-105 transition duration-300" onerror="handleDriveImgError(this)" />
            </div>
            <div class="p-3 flex-1 flex flex-col justify-between">
              <div>
                <div class="text-[11px] text-stone-500 mb-1"><i class="fa-regular fa-calendar mr-1"></i>Gốm sứ cổ • 1.820 lượt xem</div>
                <h3 class="font-bold text-xs md:text-sm text-brand leading-snug mb-1.5">
                  Chén bát Lái Thiêu &amp; Gốm sứ xưa: Vẻ đẹp mộc mạc cho không gian Việt
                </h3>
                <p class="text-xs text-stone-600 line-clamp-3">
                  Trong phong tục người Việt xưa, những chiếc chén виền xanh, dĩa con gà Lái Thiêu luôn gợi nhớ ký ức ấm cúng của gia đình...
                </p>
              </div>
              <a href="#bao-gia-lien-he" class="mt-2.5 inline-block text-xs font-semibold text-brand hover:text-brand-gold">Xem chi tiết &raquo;</a>
            </div>
          </article>

          <!-- Bài viết 3 -->
          <article class="rounded-xl border border-brand-border overflow-hidden bg-brand-cream/30 hover:shadow-md transition flex flex-col">
            <div class="h-40 overflow-hidden bg-stone-200">
              <img src="https://drive.google.com/thumbnail?id=10Muf3SHoMY8cElbboG9-7Jxt0Sdjn4oK&sz=w600" data-drive-id="10Muf3SHoMY8cElbboG9-7Jxt0Sdjn4oK" alt="Đồng hồ cổ và quạt xưa" class="w-full h-full object-cover hover:scale-105 transition duration-300" onerror="handleDriveImgError(this)" />
            </div>
            <div class="p-3 flex-1 flex flex-col justify-between">
              <div>
                <div class="text-[11px] text-stone-500 mb-1"><i class="fa-regular fa-calendar mr-1"></i>Hàng Liên Xô xưa • 3.410 lượt xem</div>
                <h3 class="font-bold text-xs md:text-sm text-brand leading-snug mb-1.5">
                  Sức hút của kỷ vật thời bao cấp: Đồng hồ con gà, quạt tai voi, bàn ủi đồng
                </h3>
                <p class="text-xs text-stone-600 line-clamp-3">
                  Những món đồ Liên Xô xưa và kỷ vật bao cấp mang giá trị hoài niệm sâu sắc, bền bỉ vượt thời gian qua nhiều thế hệ...
                </p>
              </div>
              <a href="#bao-gia-lien-he" class="mt-2.5 inline-block text-xs font-semibold text-brand hover:text-brand-gold">Xem chi tiết &raquo;</a>
            </div>
          </article>

          <!-- Bài viết 4 -->
          <article class="rounded-xl border border-brand-border overflow-hidden bg-brand-cream/30 hover:shadow-md transition flex flex-col">
            <div class="h-40 overflow-hidden bg-stone-200">
              <img src="https://drive.google.com/thumbnail?id=1wuJPWSoaavMUc4MquWgcLdfZmecEk6Dn&sz=w600" data-drive-id="1wuJPWSoaavMUc4MquWgcLdfZmecEk6Dn" alt="Kinh nghiệm chọn mua đồ đồng xưa" class="w-full h-full object-cover hover:scale-105 transition duration-300" onerror="handleDriveImgError(this)" />
            </div>
            <div class="p-3 flex-1 flex flex-col justify-between">
              <div>
                <div class="text-[11px] text-stone-500 mb-1"><i class="fa-regular fa-calendar mr-1"></i>Kinh nghiệm sưu tầm • 2.190 lượt xem</div>
                <h3 class="font-bold text-xs md:text-sm text-brand leading-snug mb-1.5">
                  Kinh nghiệm chọn mua lư đồng xưa và bài trí đồ cổ tại Đà Nẵng
                </h3>
                <p class="text-xs text-stone-600 line-clamp-3">
                  Lư đồng xưa với lớp ten đồng tự nhiên theo năm tháng mang lại vẻ trang nghiêm, cổ kính cho không gian thờ tự và phòng khách...
                </p>
              </div>
              <a href="#bao-gia-lien-he" class="mt-2.5 inline-block text-xs font-semibold text-brand hover:text-brand-gold">Xem chi tiết &raquo;</a>
            </div>
          </article>
        </div>
      </div>
    </div>
  </section>

  <!-- =====================================================================
       SECTION 8: DANH MỤC CÁC ĐỐI TÁC (ĐỐI TÁC & ĐƠN VỊ ĐỒNG HÀNH)
  ====================================================================== -->
  <section id="doi-tac" class="py-3 pb-6">
    <div class="container-1500">
      <div class="bg-white rounded-xl border border-brand-border p-3 md:p-5 shadow-sm">
        <div class="flatsome-section-title">
          <h2 class="text-sm md:text-lg">ĐỐI TÁC &amp; CỘNG ĐỒNG SƯU TẦM ĐỒ CỔ</h2>
          <span class="text-xs text-stone-500">Kết nối giao lưu cổ vật uy tín toàn quốc</span>
        </div>

        <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-2.5">
          <div class="p-3 rounded-lg border border-brand-border bg-brand-cream/40 flex flex-col items-center text-center justify-center">
            <i class="fa-solid fa-landmark text-brand-gold text-xl mb-1.5"></i>
            <span class="font-bold text-xs text-brand">CLB Cổ Vật Đà Thành</span>
            <span class="text-[10px] text-stone-500">Đối tác thẩm định</span>
          </div>
          <div class="p-3 rounded-lg border border-brand-border bg-brand-cream/40 flex flex-col items-center text-center justify-center">
            <i class="fa-solid fa-compass-drafting text-brand-gold text-xl mb-1.5"></i>
            <span class="font-bold text-xs text-brand">Nhà Đồ Cổ Sài Gòn</span>
            <span class="text-[10px] text-stone-500">Giao lưu toàn quốc</span>
          </div>
          <div class="p-3 rounded-lg border border-brand-border bg-brand-cream/40 flex flex-col items-center text-center justify-center">
            <i class="fa-solid fa-mug-hot text-brand-gold text-xl mb-1.5"></i>
            <span class="font-bold text-xs text-brand">Cà Phê Cổ Phố Hội</span>
            <span class="text-[10px] text-stone-500">Đối tác trưng bày</span>
          </div>
          <div class="p-3 rounded-lg border border-brand-border bg-brand-cream/40 flex flex-col items-center text-center justify-center">
            <i class="fa-solid fa-bicycle text-brand-gold text-xl mb-1.5"></i>
            <span class="font-bold text-xs text-brand">Hội Xe Cổ Miền Trung</span>
            <span class="text-[10px] text-stone-500">CLB Mobylette &amp; Solex</span>
          </div>
          <div class="p-3 rounded-lg border border-brand-border bg-brand-cream/40 flex flex-col items-center text-center justify-center">
            <i class="fa-solid fa-record-vinyl text-brand-gold text-xl mb-1.5"></i>
            <span class="font-bold text-xs text-brand">Hội Âm Thanh Xưa</span>
            <span class="text-[10px] text-stone-500">Radio &amp; Máy hát đĩa</span>
          </div>
          <div class="p-3 rounded-lg border border-brand-border bg-brand-cream/40 flex flex-col items-center text-center justify-center">
            <i class="fa-solid fa-award text-brand-gold text-xl mb-1.5"></i>
            <span class="font-bold text-xs text-brand">Không Gian Xưa Việt</span>
            <span class="text-[10px] text-stone-500">Thiết kế &amp; Decor xưa</span>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- =====================================================================
       FOOTER CHUẨN FLATSOME (Màu theo màu Logo, thông tin đầy đủ)
  ====================================================================== -->
  <footer class="bg-brand-dark text-stone-200 border-t-4 border-brand-gold">
    <div class="container-1500 py-8">
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6 text-xs">
        
        <!-- Cột 1: Thông tin cửa hàng -->
        <div class="space-y-2.5">
          <div class="font-serif font-bold text-base text-brand-goldLight uppercase">
            ĐỒ CỔ ĐÀ NẴNG - DOCODANANG.COM
          </div>
          <p class="text-stone-300 leading-relaxed">
            Góp nhặt yêu thương qua những kỷ vật thời gian. Mang đến không gian ĐỘC - LẠ - CHẤT cho người yêu đồ cổ tại Đà Nẵng và toàn quốc.
          </p>
          <div class="space-y-1.5 text-stone-200 pt-1">
            <div><i class="fa-solid fa-location-dot text-brand-gold mr-2"></i><strong>Địa chỉ:</strong> 02 Lê Đại Hải Châu, Phường Hòa Cường, Tp.Đà Nẵng</div>
            <div><i class="fa-solid fa-phone text-brand-gold mr-2"></i><strong>Hotline/Zalo:</strong> <a href="tel:0905124408" class="text-brand-goldLight font-bold">0905.124.408</a></div>
            <div><i class="fa-solid fa-globe text-brand-gold mr-2"></i><strong>Website:</strong> docodanang.com</div>
            <div><i class="fa-brands fa-facebook text-brand-gold mr-2"></i><strong>Fanpage:</strong> fb.com/docodanang</div>
          </div>
        </div>

        <!-- Cột 2: Danh mục chính -->
        <div class="space-y-2">
          <div class="font-bold text-sm text-brand-goldLight uppercase border-b border-brand-light pb-1.5">
            DANH MỤC SẢN PHẨM
          </div>
          <ul class="grid grid-cols-2 gap-1.5 text-stone-300">
            <li><a href="#san-pham-noi-bat" onclick="filterByCategory('TIVI')" class="hover:text-brand-goldLight">» Tivi xưa</a></li>
            <li><a href="#san-pham-noi-bat" onclick="filterByCategory('XE CỔ')" class="hover:text-brand-goldLight">» Xe cổ</a></li>
            <li><a href="#san-pham-noi-bat" onclick="filterByCategory('ĐIỆN THOẠI')" class="hover:text-brand-goldLight">» Điện thoại cổ</a></li>
            <li><a href="#san-pham-noi-bat" onclick="filterByCategory('ĐÈN')" class="hover:text-brand-goldLight">» Đèn măng xông</a></li>
            <li><a href="#san-pham-noi-bat" onclick="filterByCategory('BÀN ỦI CON GÀ')" class="hover:text-brand-goldLight">» Bàn ủi con gà</a></li>
            <li><a href="#san-pham-noi-bat" onclick="filterByCategory('GỐM SỨ')" class="hover:text-brand-goldLight">» Gốm sứ cổ</a></li>
            <li><a href="#san-pham-noi-bat" onclick="filterByCategory('ĐỒNG HỒ')" class="hover:text-brand-goldLight">» Đồng hồ xưa</a></li>
            <li><a href="#san-pham-noi-bat" onclick="filterByCategory('ÂM THANH')" class="hover:text-brand-goldLight">» Âm thanh cổ</a></li>
            <li><a href="#san-pham-noi-bat" onclick="filterByCategory('QUẠT')" class="hover:text-brand-goldLight">» Quạt hòm xưa</a></li>
            <li><a href="#san-pham-noi-bat" onclick="filterByCategory('KỶ VẬT CHIẾN TRANH')" class="hover:text-brand-goldLight">» Kỷ vật chiến tranh</a></li>
          </ul>
        </div>

        <!-- Cột 3: Chính sách & Hướng dẫn (Giống nhadoco.com) -->
        <div class="space-y-2">
          <div class="font-bold text-sm text-brand-goldLight uppercase border-b border-brand-light pb-1.5">
            HƯỚNG DẪN &amp; CHÍNH SÁCH
          </div>
          <ul class="space-y-1.5 text-stone-300">
            <li><a href="#bao-gia-lien-he" class="hover:text-brand-goldLight">» Hướng dẫn mua hàng &amp; đặt cọc</a></li>
            <li><a href="#bao-gia-lien-he" class="hover:text-brand-goldLight">» Hướng dẫn thanh toán COD &amp; Chuyển khoản</a></li>
            <li><a href="#bao-gia-lien-he" class="hover:text-brand-goldLight">» Chính sách đóng gói &amp; vận chuyển cổ vật</a></li>
            <li><a href="#bao-gia-lien-he" class="hover:text-brand-goldLight">» Chính sách thẩm định &amp; bảo hành</a></li>
            <li><a href="#bao-gia-lien-he" class="hover:text-brand-goldLight">» Dịch vụ thu mua &amp; ký gửi đồ cổ Đà Nẵng</a></li>
          </ul>
        </div>

        <!-- Cột 4: Đăng ký nhận tin khuyến mãi -->
        <div class="space-y-2.5">
          <div class="font-bold text-sm text-brand-goldLight uppercase border-b border-brand-light pb-1.5">
            NHẬN THÔNG BÁO CỔ VẬT MỚI
          </div>
          <p class="text-stone-300">
            Đăng ký số điện thoại hoặc email để nhận thông báo sớm nhất khi có món đồ cổ độc bản mới về tại cửa hàng:
          </p>
          <form onsubmit="event.preventDefault(); document.getElementById('subMsg').classList.remove('hidden');" class="flex">
            <input type="text" required placeholder="Nhập SĐT hoặc Email..." class="w-full px-3 py-2 text-xs text-stone-900 rounded-l-lg focus:outline-none" />
            <button type="submit" class="bg-brand-gold hover:bg-brand-goldLight text-brand-dark font-bold px-3.5 py-2 rounded-r-lg text-xs shrink-0">
              GỬI
            </button>
          </form>
          <div id="subMsg" class="hidden text-emerald-300 text-[11px]">Cảm ơn quý khách đã đăng ký theo dõi Đồ Cổ Đà Nẵng!</div>
        </div>

      </div>
    </div>

    <div class="bg-[#2c0d04] py-3 text-center text-[11px] text-stone-400 border-t border-white/10">
      <div class="container-1500">
        © Bản quyền thuộc về <strong>https://docodanang.com</strong> - Đồ Cổ Đà Nẵng | Địa chỉ: 02 Lê Đại Hải Châu, Phường Hòa Cường, Tp.Đà Nẵng - ĐT: 0905.124.408
      </div>
    </div>
  </footer>

  <!-- =====================================================================
       MODAL XEM CHI TIẾT SẢN PHẨM & CHỌN BÁO GIÁ NHANH
  ====================================================================== -->
  <div id="productModal" class="fixed inset-0 bg-black/60 z-50 hidden items-center justify-center p-3" onclick="closeProductModal(event)">
    <div class="bg-white rounded-xl max-w-2xl w-full overflow-hidden shadow-2xl border border-brand-border" onclick="event.stopPropagation()">
      <div class="bg-brand text-white px-4 py-3 flex items-center justify-between">
        <h3 id="modalTitle" class="font-bold text-sm md:text-base truncate">Chi tiết cổ vật</h3>
        <button type="button" onclick="closeProductModal()" class="text-white hover:text-brand-gold">
          <i class="fa-solid fa-xmark text-lg"></i>
        </button>
      </div>
      <div class="p-4 grid grid-cols-1 md:grid-cols-2 gap-4 items-center">
        <div class="relative rounded-lg overflow-hidden border border-brand-border bg-stone-100 aspect-square">
          <span id="modalBadge" class="flatsome-sale-badge">-15%</span>
          <img id="modalImg" src="" alt="" class="w-full h-full object-cover" />
        </div>
        <div class="space-y-2.5 text-xs md:text-sm">
          <div id="modalCat" class="inline-block px-2.5 py-0.5 rounded bg-brand-cream border border-brand-border text-brand font-semibold text-[11px]"></div>
          <div id="modalName" class="font-bold text-base md:text-lg text-stone-900"></div>
          <div class="flex items-baseline gap-2">
            <span id="modalPrice" class="text-lg font-extrabold text-red-700"></span>
            <del id="modalOldPrice" class="text-xs text-stone-400"></del>
          </div>
          <p id="modalDesc" class="text-xs text-stone-600 leading-relaxed"></p>
          <div class="p-2.5 rounded-lg bg-brand-cream border border-brand-border text-xs space-y-1">
            <div><i class="fa-solid fa-check text-emerald-700 mr-1.5"></i>Hiện vật thực tế tại: <strong>02 Lê Đại Hải Châu, P. Hòa Cường, Đà Nẵng</strong></div>
            <div><i class="fa-solid fa-phone text-brand mr-1.5"></i>Tư vấn trực tiếp: <strong>0905.124.408</strong></div>
          </div>
          <div class="pt-2 flex flex-wrap gap-2">
            <button type="button" id="modalQuoteBtn" class="flex-1 py-2 px-3 rounded-lg bg-brand hover:bg-brand-dark text-white font-bold text-xs transition">
              CHỌN BÁO GIÁ SẢN PHẨM NÀY
            </button>
            <a id="modalDriveLink" href="#" target="_blank" rel="noopener noreferrer" class="py-2 px-3 rounded-lg border border-brand-border hover:bg-brand-cream text-stone-700 font-semibold text-xs">
              Ảnh gốc Drive
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- =====================================================================
       CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
       Tương thích hoàn hảo trên máy tính & điện thoại, không gây tràn viền
  ====================================================================== -->
  <div class="fixed bottom-3 right-3 z-40 flex flex-col gap-2">
    <!-- Nút Zalo -->
    <a href="https://zalo.me/0905124408" target="_blank" rel="noopener noreferrer" aria-label="Chat Zalo 0905.124.408" class="flex items-center gap-2 bg-blue-600 hover:bg-blue-700 text-white px-3 py-2 rounded-full shadow-lg transition transform hover:-translate-y-0.5">
      <span class="w-6 h-6 rounded-full bg-white text-blue-600 font-extrabold text-[11px] flex items-center justify-center shrink-0">Zalo</span>
      <span class="text-xs font-bold hidden sm:inline pr-1">Zalo: 0905.124.408</span>
    </a>

    <!-- Nút Facebook Fanpage -->
    <a href="https://www.facebook.com/docodanang?locale=vi_VN" target="_blank" rel="noopener noreferrer" aria-label="Facebook Đồ Cổ Đà Nẵng" class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-800 text-white px-3 py-2 rounded-full shadow-lg transition transform hover:-translate-y-0.5">
      <span class="w-6 h-6 rounded-full bg-white text-[#1877F2] flex items-center justify-center shrink-0">
        <i class="fa-brands fa-facebook-f text-xs"></i>
      </span>
      <span class="text-xs font-bold hidden sm:inline pr-1">Fanpage Đồ Cổ</span>
    </a>

    <!-- Nút Hotline -->
    <a href="tel:0905124408" aria-label="Gọi Hotline 0905.124.408" class="flex items-center gap-2 bg-red-700 hover:bg-red-800 text-white px-3 py-2 rounded-full shadow-lg transition transform hover:-translate-y-0.5">
      <span class="w-6 h-6 rounded-full bg-white text-red-700 flex items-center justify-center shrink-0">
        <i class="fa-solid fa-phone-volume text-xs"></i>
      </span>
      <span class="text-xs font-bold pr-1">0905.124.408</span>
    </a>
  </div>

  <!-- =====================================================================
       JAVASCRIPT XỬ LÝ DỮ LIỆU 14 ẢNH GOOGLE DRIVE, SLIDER & BỘ LỌC FLATSOME
  ====================================================================== -->
  <script>
    // Danh sách 13 danh mục chuẩn từ web mẫu nhadoco.com
    const CATEGORIES = [
      { id: 'TIVI', name: 'TIVI XƯA', sub: 'Việt Nam, Liên Xô, Cửa lùa', icon: 'fa-tv' },
      { id: 'XE CỔ', name: 'XE CỔ', sub: 'Mobylette, Solex, Xe Pháp', icon: 'fa-bicycle' },
      { id: 'ĐIỆN THOẠI', name: 'ĐIỆN THOẠI', sub: 'Quay số, Để bàn, Sừng nai', icon: 'fa-phone-rotary' },
      { id: 'ĐÈN', name: 'ĐÈN CỔ', sub: 'Măng xông, Đèn bão, Châu Âu', icon: 'fa-fire-flame-simple' },
      { id: 'BÀN ỦI CON GÀ', name: 'BÀN ỦI CON GÀ', sub: 'Việt Nam, 1914 nguyên bản', icon: 'fa-weight-hanging' },
      { id: 'TRANH ẢNH', name: 'TRANH ẢNH', sub: 'Tranh cổ, Khung xưa', icon: 'fa-image' },
      { id: 'GỐM SỨ', name: 'GỐM SỨ', sub: 'Chén dĩa, Lọ hoa, Ấm trà', icon: 'fa-wine-bottle' },
      { id: 'ĐỒNG HỒ', name: 'ĐỒNG HỒ', sub: 'Để bàn, Treo tường, Đeo dây', icon: 'fa-clock' },
      { id: 'ÂM THANH', name: 'ÂM THANH', sub: 'Radio, Cassette, Loa kèn', icon: 'fa-record-vinyl' },
      { id: 'QUẠT', name: 'QUẠT XƯA', sub: 'Quạt hòm, Việt Nam, Châu Âu', icon: 'fa-fan' },
      { id: 'KỶ VẬT CHIẾN TRANH', name: 'KỶ VẬT CHIẾN TRANH', sub: 'Bình tông, Cà mèn, Nón xưa', icon: 'fa-helmet-safety' },
      { id: 'HÀNG SƯU TẦM LIÊN XÔ XƯA', name: 'HÀNG LIÊN XÔ XƯA', sub: 'Đồ bao cấp & Liên Xô', icon: 'fa-star' },
      { id: 'HÀNG SƯU TẦM KHÁC', name: 'SƯU TẦM KHÁC', sub: 'Lư đồng, Máy chữ, Bàn tính', icon: 'fa-box-archive' },
      { id: 'ALL', name: 'TẤT CẢ CỔ VẬT', sub: 'Xem toàn bộ 14+ hiện vật', icon: 'fa-border-all' }
    ];

    // 14 sản phẩm thực tế gắn đúng 14 file ảnh Google Drive người dùng cung cấp
    // Đầy đủ giá giảm, giá gốc và % giảm giá góc trên bên trái giống Flatsome nhadoco.com
    const PRODUCTS = [
      {
        id: 1,
        driveId: '1H0mGjMkomcuk1ngaBw3r8PZeyU9pjBBw',
        name: 'Quạt hòm xưa Châu Âu nguyên bản sưu tầm',
        category: 'QUẠT',
        price: '6.700.000đ',
        oldPrice: '8.000.000đ',
        discountPercent: '-16%',
        isSovietSection: false,
        desc: 'Quạt hòm xưa kiểu dáng cổ điển sang trọng, động cơ êm, cánh đồng nguyên bản, thích hợp trưng bày phòng khách và không gian xưa.'
      },
      {
        id: 2,
        driveId: '1re65R4tQ6Ah34BWF2ZACbO4Cla_8LnU9',
        name: 'Đèn măng xông Petromax cổ Đức',
        category: 'ĐÈN',
        price: '5.500.000đ',
        oldPrice: '6.000.000đ',
        discountPercent: '-8%',
        isSovietSection: false,
        desc: 'Đèn măng xông Petromax cổ chính hãng, bầu đồng sáng đẹp, đầy đủ phụ kiện zin nguyên bản cho người đam mê đèn cổ.'
      },
      {
        id: 3,
        driveId: '19MJehNTgG1y8yj-3QX1HriLZqvv5wVnh',
        name: 'Đèn măng xông Aida Express – Đèn dầu cổ xưa độc đáo',
        category: 'ĐÈN',
        price: '5.500.000đ',
        oldPrice: '6.000.000đ',
        discountPercent: '-8%',
        isSovietSection: true,
        desc: 'Mẫu đèn măng xông Aida Express quý hiếm, giữ nguyên nét cổ kính thời gian, hoạt động tốt và giá trị sưu tầm cao.'
      },
      {
        id: 4,
        driveId: '1PK6y5m52N7Eh5fuLZHRUmfHkwbljGR3C',
        name: 'Điện thoại quay số của Mỹ thời xưa',
        category: 'ĐIỆN THOẠI',
        price: '950.000đ',
        oldPrice: '1.200.000đ',
        discountPercent: '-21%',
        isSovietSection: true,
        desc: 'Điện thoại bàn quay số cổ điển của Mỹ, chuông cơ vang thanh, vòng quay mượt mà, decor bàn làm việc hoặc quán cà phê xưa.'
      },
      {
        id: 5,
        driveId: '1JyibbUp5Zk1AFveDxfsHMOxxkhTaTlq9',
        name: 'Tivi trắng đen cửa lùa xưa sưu tầm',
        category: 'TIVI',
        price: '1.500.000đ',
        oldPrice: '2.000.000đ',
        discountPercent: '-25%',
        isSovietSection: false,
        desc: 'Tivi trắng đen vỏ gỗ cửa lùa hoài niệm thập niên 70-80, kiểu dáng đẹp, thích hợp trưng bày không gian truyền thống.'
      },
      {
        id: 6,
        driveId: '1wuJPWSoaavMUc4MquWgcLdfZmecEk6Dn',
        name: 'Bộ lư đồng xưa chạm rồng cổ kính',
        category: 'HÀNG SƯU TẦM KHÁC',
        price: '3.800.000đ',
        oldPrice: '4.500.000đ',
        discountPercent: '-16%',
        isSovietSection: true,
        desc: 'Lư đồng xưa đúc thủ công tinh xảo, nước đồng lên màu thời gian tự nhiên, mang đậm nét văn hóa gia đình Việt xưa.'
      },
      {
        id: 7,
        driveId: '1WJnvXdMBNEeBYUztTe0Breke2Q-NnuN5',
        name: 'Bàn ủi con gà Việt Nam 1914 bằng đồng',
        category: 'BÀN ỦI CON GÀ',
        price: '1.250.000đ',
        oldPrice: '1.500.000đ',
        discountPercent: '-17%',
        isSovietSection: false,
        desc: 'Bàn ủi than con gà cổ bằng đồng nguyên chiếc, chốt khóa hình gà sắc nét, hiện vật tiêu biểu của đời sống Việt Nam xưa.'
      },
      {
        id: 8,
        driveId: '10Muf3SHoMY8cElbboG9-7Jxt0Sdjn4oK',
        name: 'Đồng hồ để bàn con gà Liên Xô xưa',
        category: 'ĐỒNG HỒ',
        price: '1.100.000đ',
        oldPrice: '1.400.000đ',
        discountPercent: '-21%',
        isSovietSection: true,
        desc: 'Đồng hồ cơ lên dây cót thời Liên Xô xưa, họa tiết con gà mổ thóc quen thuộc, máy chạy chuẩn giờ, chuông báo thức vang.'
      },
      {
        id: 9,
        driveId: '1-jiLNmrBeFy1BEucUoPEXuydvdeEKLzB',
        name: 'Máy hát đĩa loa kèn cổ điển Châu Âu',
        category: 'ÂM THANH',
        price: '6.800.000đ',
        oldPrice: '8.000.000đ',
        discountPercent: '-15%',
        isSovietSection: false,
        desc: 'Máy hát đĩa than có loa kèn đồng cổ điển, âm thanh mộc mạc hoài cổ, tạo điểm nhấn sang trọng cho phòng khách.'
      },
      {
        id: 10,
        driveId: '1qsK7L0tyzMV6rOgDxH2NsO0Q6rVnYqlB',
        name: 'Bộ chén xưa viền xanh & Tôm sứ treo tường cổ',
        category: 'GỐM SỨ',
        price: '850.000đ',
        oldPrice: '1.000.000đ',
        discountPercent: '-15%',
        isSovietSection: false,
        desc: 'Gốm sứ cổ men rạn tự nhiên, nét vẽ thủ công tinh tế của nghệ nhân xưa, rất được giới sưu tầm gốm Nam Bộ và miền Trung ưa chuộng.'
      },
      {
        id: 11,
        driveId: '1wWYKaetcHh1vFsis6qJNxWXDlt8IXyuK',
        name: 'Cà mèn xưa & Bình tông kỷ vật chiến tranh',
        category: 'KỶ VẬT CHIẾN TRANH',
        price: '350.000đ',
        oldPrice: '500.000đ',
        discountPercent: '-30%',
        isSovietSection: true,
        desc: 'Kỷ vật thời chiến nguyên vẹn, mang đậm dấu ấn lịch sử, thích hợp trưng bày góc kỷ niệm hoặc sưu tầm chuyên đề.'
      },
      {
        id: 12,
        driveId: '1AVMDQDsRr3v1s0E6Ht_XV9_VVaiZ13Tl',
        name: 'Đèn dầu ABC & Đèn bão xưa cổ điển',
        category: 'ĐÈN',
        price: '600.000đ',
        oldPrice: '750.000đ',
        discountPercent: '-20%',
        isSovietSection: false,
        desc: 'Đèn dầu cổ và đèn bão xưa giữ nguyên bóng thủy tinh chịu nhiệt, tim đèn nhạy lửa, vẻ đẹp mộc mạc vượt thời gian.'
      },
      {
        id: 13,
        driveId: '1B_lXknHAKn_cTf631LwToPh39nuh0SYE',
        name: 'Tranh cẩn ốc xà cừ & Máy đánh chữ Pháp xưa',
        category: 'TRANH ẢNH',
        price: '2.400.000đ',
        oldPrice: '2.900.000đ',
        discountPercent: '-17%',
        isSovietSection: false,
        desc: 'Tác phẩm nghệ thuật xưa kết hợp hiện vật thời Pháp thuộc, đường nét chạm khắc tỉ mỉ, sang trọng và giàu giá trị văn hóa.'
      },
      {
        id: 14,
        driveId: '12z0LAuOwH7ccdh-7dyOllrg43x5-3EPE',
        name: 'Xe cổ Mobylette / Xe đạp Pháp xưa nguyên bản',
        category: 'XE CỔ',
        price: '14.500.000đ',
        oldPrice: '16.500.000đ',
        discountPercent: '-12%',
        isSovietSection: false,
        desc: 'Dòng xe cổ Pháp danh tiếng được bảo tồn kỹ lưỡng tại Đồ Cổ Đà Nẵng, khung sườn chắc chắn, phụ tùng zin quý hiếm.'
      }
    ];

    // Hàm tạo URL ảnh từ Google Drive ID + cơ chế tự động chuyển link dự phòng nếu trình duyệt chặn cookie
    function getDriveImgUrl(driveId) {
      return `https://drive.google.com/thumbnail?id=${driveId}&sz=w1000`;
    }

    function handleDriveImgError(imgEl) {
      const driveId = imgEl.getAttribute('data-drive-id');
      const step = parseInt(imgEl.getAttribute('data-fallback-step') || '0', 10);
      if (step === 0 && driveId) {
        imgEl.setAttribute('data-fallback-step', '1');
        imgEl.src = `https://lh3.googleusercontent.com/d/${driveId}=w1000`;
      } else if (step === 1 && driveId) {
        imgEl.setAttribute('data-fallback-step', '2');
        imgEl.src = `https://drive.google.com/uc?export=view&id=${driveId}`;
      } else {
        imgEl.onerror = null;
        imgEl.src = `https://placehold.co/600x600/5c1d0c/ebd08e?text=Co+Vat+Da+Nang`;
      }
    }

    // Render Danh mục ở trang chủ: chữ nhỏ gọn, whitespace-nowrap không bao giờ bị rớt dòng
    function renderHomepageCategories(activeCat = 'ALL') {
      const grid = document.getElementById('homepageCategoryGrid');
      if (!grid) return;
      grid.innerHTML = CATEGORIES.map(cat => {
        const isActive = cat.id === activeCat;
        return `
          <button
            type="button"
            onclick="filterByCategory('${cat.id}')"
            class="flex items-center gap-2 p-2 rounded-lg border text-left transition ${
              isActive
                ? 'bg-brand text-white border-brand shadow-sm'
                : 'bg-brand-cream/50 hover:bg-brand-cream text-stone-800 border-brand-border'
            }"
          >
            <span class="w-7 h-7 rounded-md flex items-center justify-center shrink-0 ${
              isActive ? 'bg-brand-gold text-brand-dark' : 'bg-brand/10 text-brand'
            }">
              <i class="fa-solid ${cat.icon} text-xs"></i>
            </span>
            <div class="min-w-0 flex-1">
              <div class="text-[11px] font-bold whitespace-nowrap overflow-hidden text-ellipsis">${cat.name}</div>
              <div class="text-[10px] ${isActive ? 'text-brand-goldLight' : 'text-stone-500'} whitespace-nowrap overflow-hidden text-ellipsis">${cat.sub}</div>
            </div>
          </button>
        `;
      }).join('');
    }

    // Render Card sản phẩm chuẩn Flatsome (2 cột trên điện thoại, badge % góc trên bên trái, tên SP đầy đủ không cắt chữ)
    function createProductCardHTML(p) {
      const imgUrl = getDriveImgUrl(p.driveId);
      return `
        <div class="product-small box bg-white rounded-xl border border-brand-border overflow-hidden hover:shadow-md transition flex flex-col justify-between group">
          <div>
            <!-- Ảnh sản phẩm + Badge % giảm giá chuẩn Flatsome góc trên bên trái -->
            <div class="relative aspect-square w-full bg-stone-100 overflow-hidden cursor-pointer" onclick="openProductModal(${p.id})">
              <span class="flatsome-sale-badge">${p.discountPercent}</span>
              <img
                src="${imgUrl}"
                data-drive-id="${p.driveId}"
                alt="${p.name}"
                loading="lazy"
                onerror="handleDriveImgError(this)"
                class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
              />
            </div>

            <!-- Nội dung sản phẩm: Tên hiển thị đầy đủ, không bị thiếu chữ hay tràn ra ngoài -->
            <div class="p-2.5 md:p-3">
              <div class="text-[10px] font-semibold text-stone-400 uppercase mb-0.5">${p.category}</div>
              <h3
                onclick="openProductModal(${p.id})"
                class="product-title-full font-bold text-xs md:text-sm text-stone-800 hover:text-brand cursor-pointer mb-1.5"
              >
                ${p.name}
              </h3>
            </div>
          </div>

          <!-- Khối giá giảm giá & nút chọn báo giá nằm gọn dưới đáy card -->
          <div class="px-2.5 pb-2.5 md:px-3 md:pb-3 pt-1 border-t border-brand-border/50">
            <div class="flex flex-wrap items-baseline gap-x-1.5 gap-y-0.5 mb-2">
              <span class="text-xs md:text-sm font-extrabold text-red-700">${p.price}</span>
              <del class="text-[10px] md:text-xs text-stone-400">${p.oldPrice}</del>
            </div>
            <div class="flex items-center gap-1.5">
              <button
                type="button"
                onclick="selectProductForQuote(${p.id})"
                class="w-full py-1.5 px-2 rounded-lg bg-brand hover:bg-brand-dark text-white font-semibold text-[11px] transition flex items-center justify-center gap-1"
              >
                <i class="fa-solid fa-cart-plus text-[10px] text-brand-goldLight"></i>
                <span>Báo giá / Đặt mua</span>
              </button>
            </div>
          </div>
        </div>
      `;
    }

    // Lọc sản phẩm theo danh mục
    let currentCategory = 'ALL';
    function filterByCategory(catId) {
      currentCategory = catId;
      renderHomepageCategories(catId);

      // Cập nhật trạng thái nút trên thanh menu máy tính
      document.querySelectorAll('[data-cat-btn]').forEach(btn => {
        if (btn.getAttribute('data-cat-btn') === catId) {
          btn.className = 'nav-cat-item px-2.5 py-1 rounded bg-brand-gold text-brand-dark font-bold';
        } else {
          btn.className = 'nav-cat-item px-2.5 py-1 rounded hover:bg-brand-dark/70 text-white';
        }
      });

      const filtered = catId === 'ALL'
        ? PRODUCTS
        : PRODUCTS.filter(p => p.category === catId || (catId === 'HÀNG SƯU TẦM LIÊN XÔ XƯA' && p.isSovietSection));

      const titleEl = document.getElementById('currentCategoryTitle');
      const countEl = document.getElementById('productCountBadge');
      if (titleEl) {
        titleEl.textContent = catId === 'ALL' ? 'SẢN PHẨM NỔI BẬT' : `DANH MỤC: ${catId}`;
      }
      if (countEl) {
        countEl.textContent = `Hiển thị ${filtered.length} sản phẩm`;
      }

      const grid = document.getElementById('featuredProductsGrid');
      if (grid) {
        grid.innerHTML = filtered.map(createProductCardHTML).join('');
      }
    }

    // Tìm kiếm sản phẩm theo từ khóa
    function handleSearchProduct(keyword) {
      const q = (keyword || '').trim().toLowerCase();
      const filtered = !q
        ? PRODUCTS
        : PRODUCTS.filter(p =>
            p.name.toLowerCase().includes(q) ||
            p.category.toLowerCase().includes(q) ||
            p.desc.toLowerCase().includes(q)
          );

      const titleEl = document.getElementById('currentCategoryTitle');
      const countEl = document.getElementById('productCountBadge');
      if (titleEl) {
        titleEl.textContent = q ? `KẾT QUẢ TÌM KIẾM: "${keyword}"` : 'SẢN PHẨM NỔI BẬT';
      }
      if (countEl) {
        countEl.textContent = `Hiển thị ${filtered.length} sản phẩm`;
      }

      const grid = document.getElementById('featuredProductsGrid');
      if (grid) {
        grid.innerHTML = filtered.length
          ? filtered.map(createProductCardHTML).join('')
          : `<div class="col-span-full py-8 text-center text-xs md:text-sm text-stone-500">Không tìm thấy sản phẩm phù hợp. Quý khách vui lòng gọi/Zalo <strong>0905.124.408</strong> để được gửi ảnh trực tiếp!</div>`;
      }
    }

    // Render mục Hàng Sưu Tầm Liên Xô Xưa
    function renderSovietSection() {
      const sovietGrid = document.getElementById('sovietProductsGrid');
      if (!sovietGrid) return;
      const list = PRODUCTS.filter(p => p.isSovietSection);
      sovietGrid.innerHTML = list.map(createProductCardHTML).join('');
    }

    // Chọn sản phẩm đưa xuống Form Báo Giá
    let quoteCount = 0;
    function selectProductForQuote(productId) {
      const product = PRODUCTS.find(p => p.id === productId);
      if (!product) return;
      quoteCount += 1;
      const badge = document.getElementById('quoteCartCount');
      if (badge) badge.textContent = String(quoteCount);

      const input = document.getElementById('qProductSelected');
      if (input) {
        input.value = `${product.name} (${product.price})`;
      }
      const formSection = document.getElementById('bao-gia-lien-he');
      if (formSection) {
        formSection.scrollIntoView({ behavior: 'smooth' });
      }
    }

    // Modal xem chi tiết sản phẩm
    function openProductModal(productId) {
      const product = PRODUCTS.find(p => p.id === productId);
      if (!product) return;
      const modal = document.getElementById('productModal');
      document.getElementById('modalTitle').textContent = product.name;
      document.getElementById('modalName').textContent = product.name;
      document.getElementById('modalCat').textContent = product.category;
      document.getElementById('modalPrice').textContent = product.price;
      document.getElementById('modalOldPrice').textContent = product.oldPrice;
      document.getElementById('modalBadge').textContent = product.discountPercent;
      document.getElementById('modalDesc').textContent = product.desc;

      const img = document.getElementById('modalImg');
      img.setAttribute('data-drive-id', product.driveId);
      img.setAttribute('data-fallback-step', '0');
      img.onerror = function() { handleDriveImgError(this); };
      img.src = getDriveImgUrl(product.driveId);

      const driveLink = document.getElementById('modalDriveLink');
      driveLink.href = `https://drive.google.com/file/d/${product.driveId}/view?usp=sharing`;

      const quoteBtn = document.getElementById('modalQuoteBtn');
      quoteBtn.onclick = function() {
        closeProductModal();
        selectProductForQuote(product.id);
      };

      modal.classList.remove('hidden');
      modal.classList.add('flex');
    }

    function closeProductModal() {
      const modal = document.getElementById('productModal');
      modal.classList.add('hidden');
      modal.classList.remove('flex');
    }

    // Xử lý gửi Form Yêu cầu và Báo giá trang chủ
    function submitQuoteForm(e) {
      e.preventDefault();
      const name = document.getElementById('qName').value.trim();
      const phone = document.getElementById('qPhone').value.trim();
      const cat = document.getElementById('qCategory').value;
      const prod = document.getElementById('qProductSelected').value.trim() || 'Tư vấn chung';

      const box = document.getElementById('quoteSuccessBox');
      const detail = document.getElementById('quoteSuccessDetail');
      detail.textContent = `Cảm ơn ${name} (${phone}). Yêu cầu "${cat} - ${prod}" đã được gửi tới Đồ Cổ Đà Nẵng (0905.124.408). Chúng tôi sẽ liên hệ lại ngay!`;
      box.classList.remove('hidden');
      document.getElementById('quoteForm').reset();
    }

    // Đóng/mở menu mobile
    function toggleMobileDrawer() {
      const drawer = document.getElementById('mobileMenuDrawer');
      const overlay = document.getElementById('mobileMenuOverlay');
      const isClosed = drawer.classList.contains('-translate-x-full');
      if (isClosed) {
        drawer.classList.remove('-translate-x-full');
        overlay.classList.remove('hidden');
      } else {
        drawer.classList.add('-translate-x-full');
        overlay.classList.add('hidden');
      }
    }

    // Slider 2 ảnh banner tự trượt chuyên nghiệp
    let activeSlide = 0;
    let slideInterval = null;

    function showSlide(index) {
      const slides = document.querySelectorAll('.banner-slide');
      const dots = document.querySelectorAll('.slide-dot');
      if (!slides.length) return;
      activeSlide = (index + slides.length) % slides.length;
      slides.forEach((s, i) => {
        if (i === activeSlide) {
          s.classList.remove('hidden');
          s.classList.add('block');
        } else {
          s.classList.remove('block');
          s.classList.add('hidden');
        }
      });
      dots.forEach((d, i) => {
        d.className = i === activeSlide
          ? 'slide-dot w-2.5 h-2.5 rounded-full bg-brand-gold transition'
          : 'slide-dot w-2.5 h-2.5 rounded-full bg-white/50 transition';
      });
    }

    function changeSlide(step) {
      showSlide(activeSlide + step);
      resetSlideTimer();
    }

    function goToSlide(index) {
      showSlide(index);
      resetSlideTimer();
    }

    function resetSlideTimer() {
      if (slideInterval) clearInterval(slideInterval);
      slideInterval = setInterval(() => {
        showSlide(activeSlide + 1);
      }, 4500);
    }

    // Khởi chạy khi tải trang
    window.addEventListener('DOMContentLoaded', () => {
      renderHomepageCategories('ALL');
      filterByCategory('ALL');
      renderSovietSection();
      resetSlideTimer();
    });
  </script>
</body>
</html>
