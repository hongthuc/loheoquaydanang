<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Lò Heo Quay Đà Nẵng - Da Giòn Rụm, Giao Nóng Tận Nơi | loheoquaydanang.com</title>
    <meta name="description" content="Lò Heo Quay Đà Nẵng (loheoquaydanang.com) chuyên heo sữa quay, heo quay nguyên con, mâm cúng trọn gói tại Đà Nẵng. Địa chỉ: H97/40/27k138 Hoàng Văn Thái, Phường Hòa Khánh, TP. Đà Nẵng. Hotline: 0978.922.722">

    <!-- Open Graph / Thumbnail là ảnh Logo khi gửi link trang web -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://loheoquaydanang.com/">
    <meta property="og:title" content="Lò Heo Quay Đà Nẵng - Da Giòn Rụm, Chu Toàn Lễ Nghi | 0978.922.722">
    <meta property="og:description" content="Chuyên cung cấp Heo sữa quay, Heo quay nguyên con cúng Khai trương, Đầy tháng, Thôi nôi, Thần Tài, Cưới hỏi tại Đà Nẵng. Giao nóng tận nơi đúng giờ Hoàng Đạo.">
    <meta property="og:image" content="https://lh3.googleusercontent.com/d/1pi7Dt3XNoMJy10ObYE21VlhcXKEyhOTq">
    <meta property="og:image:alt" content="Logo Lò Heo Quay Đà Nẵng">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1pi7Dt3XNoMJy10ObYE21VlhcXKEyhOTq">
    <link rel="icon" href="https://lh3.googleusercontent.com/d/1pi7Dt3XNoMJy10ObYE21VlhcXKEyhOTq">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>

    <!-- Google Fonts: Inter & Roboto chuẩn Flatsome -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <style>
        /* Thiết lập chống tràn viền và không lệch phải tuyệt đối */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            margin: 0;
            padding: 0;
            width: 100%;
            max-width: 100%;
            overflow-x: hidden;
            font-family: 'Inter', sans-serif;
            background-color: #fdfaf6;
            color: #222222;
            scroll-behavior: smooth;
        }

        /* Khung chuẩn 1500px trên máy tính theo yêu cầu */
        .flatsome-container {
            width: 100%;
            max-width: 1500px;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }
        @media (min-width: 1024px) {
            .flatsome-container {
                padding-left: 20px;
                padding-right: 20px;
            }
        }

        /* Màu chủ đạo theo màu Logo Lò Heo Quay (Đỏ Đô Truyền Thống & Vàng Hoàng Kim) */
        :root {
            --brand-red: #a81817;
            --brand-red-dark: #7f1010;
            --brand-gold: #f59e0b;
            --brand-gold-light: #fef3c7;
        }

        /* Tối ưu tên danh mục trên máy tính: viết liền trên 1 hàng chữ nhỏ gọn, tuyệt đối không xuống dòng trong từng tên danh mục */
        .nav-cat-link {
            white-space: nowrap !important;
            display: inline-flex;
            align-items: center;
            font-size: 13px;
            font-weight: 700;
            letter-spacing: 0.01em;
            transition: all 0.2s ease;
        }

        /* Chữ danh mục ở trang chủ nhỏ gọn, không gãy dòng */
        .home-cat-pill {
            white-space: nowrap !important;
            font-size: 12.5px;
            line-height: 1.3;
        }

        /* Tiêu đề Section kiểu Flatsome Title */
        .flatsome-section-title {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 100%;
            margin-bottom: 1.25rem;
        }
        .flatsome-section-title::before,
        .flatsome-section-title::after {
            content: "";
            flex: 1;
            height: 2px;
            background-color: #e5dcd3;
        }
        .flatsome-section-title span {
            padding: 0 16px;
            font-weight: 800;
            text-transform: uppercase;
            color: var(--brand-red);
            text-align: center;
        }

        /* Nhãn giảm giá % góc trên bên trái chuẩn Flatsome WooCommerce */
        .flatsome-Discount-badge {
            position: absolute;
            top: 8px;
            left: 8px;
            z-index: 10;
            background-color: #c81e1e;
            color: #ffffff;
            font-weight: 800;
            font-size: 11.5px;
            line-height: 1;
            padding: 6px 8px;
            border-radius: 9999px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
            pointer-events: none;
        }

        /* Hiệu ứng rung nhẹ cho nút Hotline nổi */
        @keyframes pulse-ring {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(185, 28, 28, 0.7); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(185, 28, 28, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(185, 28, 28, 0); }
        }
        .floating-pulse {
            animation: pulse-ring 2s infinite;
        }

        /* Thanh cuộn ngang mượt cho danh mục trên điện thoại nếu cần */
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }
    </style>
</head>
<body class="bg-[#fdfaf6] text-stone-800">

    <!-- =====================================================================
         FLATSOME TOP BAR (Đơn giản, không hiển thị thanh UX Builder)
    ====================================================================== -->
    <div class="bg-[#7f1010] text-amber-100 text-xs py-1.5 border-b border-amber-500/30">
        <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-2 truncate">
                <i class="fa-solid fa-fire-flame-curved text-amber-400"></i>
                <span class="font-medium">Lò Heo Quay Đà Nẵng - Da Giòn Rụm, Chu Toàn Lễ Nghi - Giao Nóng Tận Nơi</span>
            </div>
            <div class="hidden md:flex items-center gap-4 text-[11.5px] whitespace-nowrap">
                <span><i class="fa-solid fa-location-dot text-amber-400 mr-1"></i>H97/40/27k138 Hoàng Văn Thái, P. Hòa Khánh, TP. Đà Nẵng</span>
                <span>|</span>
                <span><i class="fa-regular fa-clock text-amber-400 mr-1"></i>Phục vụ: 05:00 - 21:00 (Tất cả các ngày)</span>
            </div>
        </div>
    </div>

    <!-- =====================================================================
         FLATSOME HEADER (Logo gọn nhỏ, KHÔNG để nút gọi ngay để tránh tràn viền,
         Menu danh mục viết liền trên 1 hàng chữ nhỏ gọn)
    ====================================================================== -->
    <header class="bg-white sticky top-0 z-40 shadow-sm border-b border-stone-200">
        <div class="flatsome-container py-2">
            <div class="flex items-center justify-between gap-3">
                <!-- Logo chỉnh gọn nhỏ lại theo yêu cầu -->
                <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 group">
                    <img 
                        src="https://lh3.googleusercontent.com/d/1pi7Dt3XNoMJy10ObYE21VlhcXKEyhOTq" 
                        onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1pi7Dt3XNoMJy10ObYE21VlhcXKEyhOTq&sz=w400';"
                        alt="Logo Lò Heo Quay Đà Nẵng" 
                        class="h-10 w-10 md:h-11 md:w-11 object-contain rounded-full border border-amber-500/60 p-0.5 bg-white shrink-0"
                    >
                    <div class="leading-tight">
                        <span class="block text-sm md:text-base font-extrabold text-[#a81817] tracking-tight uppercase">LÒ HEO QUAY ĐÀ NẴNG</span>
                        <span class="block text-[10.5px] text-stone-500 font-medium">loheoquaydanang.com</span>
                    </div>
                </a>

                <!-- Menu Danh Mục trên Máy Tính: chữ nhỏ gọn, viết liền trên 1 hàng (hoặc tự xuống hàng 2), tuyệt đối không gãy dòng tên danh mục -->
                <nav class="hidden lg:flex flex-wrap items-center justify-end gap-x-3.5 gap-y-1 flex-1">
                    <a href="#trang-chu" class="nav-cat-link text-[#a81817] hover:text-amber-600 py-1">TRANG CHỦ</a>
                    <a href="#gioi-thieu" class="nav-cat-link text-stone-700 hover:text-[#a81817] py-1">GIỚI THIỆU</a>
                    <a href="#heo-sua-quay" class="nav-cat-link text-stone-700 hover:text-[#a81817] py-1">HEO SỮA QUAY</a>
                    <a href="#heo-quay-nguyen-con" class="nav-cat-link text-stone-700 hover:text-[#a81817] py-1">HEO QUAY NGUYÊN CON</a>
                    <a href="#mam-cung-tron-goi" class="nav-cat-link text-stone-700 hover:text-[#a81817] py-1">MÂM CÚNG TRỌN GÓI</a>
                    <a href="#bang-gia" class="nav-cat-link text-stone-700 hover:text-[#a81817] py-1">BẢNG GIÁ</a>
                    <a href="#cam-nang-tin-tuc" class="nav-cat-link text-stone-700 hover:text-[#a81817] py-1">CẨM NANG & VĂN KHẤN</a>
                    <a href="#bao-gia-nhanh" class="nav-cat-link text-stone-700 hover:text-[#a81817] py-1">BÁO GIÁ</a>
                    <a href="#lien-he-ban-do" class="nav-cat-link text-stone-700 hover:text-[#a81817] py-1">LIÊN HỆ</a>
                </nav>

                <!-- Nút mở Menu trên Điện Thoại (Không để nút gọi ngay trên Header để tránh tràn viền) -->
                <button id="mobile-menu-btn" type="button" aria-label="Mở danh mục" class="lg:hidden inline-flex items-center justify-center px-3 py-1.5 rounded border border-stone-300 text-stone-700 hover:bg-stone-100 text-xs font-bold gap-1.5 shrink-0">
                    <i class="fa-solid fa-bars text-sm text-[#a81817]"></i>
                    <span>DANH MỤC</span>
                </button>
            </div>

            <!-- Thanh Danh Mục Nhanh trên Điện Thoại (Thiết kế gọn đẹp, cuộn ngang mượt, không tràn viền) -->
            <div class="lg:hidden mt-2 pt-1.5 border-t border-stone-100 flex items-center gap-1.5 overflow-x-auto no-scrollbar">
                <a href="#heo-sua-quay" class="home-cat-pill px-2.5 py-1 rounded bg-red-50 text-[#a81817] font-bold border border-red-200 shrink-0">Heo Sữa Quay</a>
                <a href="#heo-quay-nguyen-con" class="home-cat-pill px-2.5 py-1 rounded bg-stone-100 text-stone-700 font-semibold border border-stone-200 shrink-0">Heo Nguyên Con</a>
                <a href="#mam-cung-tron-goi" class="home-cat-pill px-2.5 py-1 rounded bg-stone-100 text-stone-700 font-semibold border border-stone-200 shrink-0">Mâm Cúng</a>
                <a href="#bang-gia" class="home-cat-pill px-2.5 py-1 rounded bg-stone-100 text-stone-700 font-semibold border border-stone-200 shrink-0">Bảng Giá</a>
                <a href="#bao-gia-nhanh" class="home-cat-pill px-2.5 py-1 rounded bg-stone-100 text-stone-700 font-semibold border border-stone-200 shrink-0">Báo Giá</a>
                <a href="#cam-nang-tin-tuc" class="home-cat-pill px-2.5 py-1 rounded bg-stone-100 text-stone-700 font-semibold border border-stone-200 shrink-0">Cẩm Nang</a>
                <a href="#lien-he-ban-do" class="home-cat-pill px-2.5 py-1 rounded bg-stone-100 text-stone-700 font-semibold border border-stone-200 shrink-0">Bản Đồ</a>
            </div>
        </div>

        <!-- Hộp Menu xổ xuống trên Điện Thoại -->
        <div id="mobile-menu-drawer" class="hidden lg:hidden bg-white border-t border-stone-200 shadow-lg">
            <div class="flatsome-container py-3 flex flex-col divide-y divide-stone-100 text-xs font-bold">
                <a href="#trang-chu" class="py-2.5 text-[#a81817] flex items-center justify-between"><span>TRANG CHỦ</span><i class="fa-solid fa-angle-right"></i></a>
                <a href="#gioi-thieu" class="py-2.5 text-stone-700 flex items-center justify-between"><span>GIỚI THIỆU LÒ QUAY</span><i class="fa-solid fa-angle-right"></i></a>
                <a href="#heo-sua-quay" class="py-2.5 text-stone-700 flex items-center justify-between"><span>HEO SỮA QUAY (1.5KG - 3.8KG)</span><i class="fa-solid fa-angle-right"></i></a>
                <a href="#heo-quay-nguyen-con" class="py-2.5 text-stone-700 flex items-center justify-between"><span>HEO QUAY NGUYÊN CON (4KG - 22KG)</span><i class="fa-solid fa-angle-right"></i></a>
                <a href="#mam-cung-tron-goi" class="py-2.5 text-stone-700 flex items-center justify-between"><span>DỊCH VỤ MÂM CÚNG TRỌN GÓI</span><i class="fa-solid fa-angle-right"></i></a>
                <a href="#bang-gia" class="py-2.5 text-stone-700 flex items-center justify-between"><span>BẢNG GIÁ HEO QUAY ĐÀ NẴNG</span><i class="fa-solid fa-angle-right"></i></a>
                <a href="#bao-gia-nhanh" class="py-2.5 text-stone-700 flex items-center justify-between"><span>FORM YÊU CẦU & BÁO GIÁ</span><i class="fa-solid fa-angle-right"></i></a>
                <a href="#cam-nang-tin-tuc" class="py-2.5 text-stone-700 flex items-center justify-between"><span>CẨM NANG & VĂN KHẤN</span><i class="fa-solid fa-angle-right"></i></a>
                <a href="#lien-he-ban-do" class="py-2.5 text-stone-700 flex items-center justify-between"><span>LIÊN HỆ & BẢN ĐỒ GOOGLE MAPS</span><i class="fa-solid fa-angle-right"></i></a>
            </div>
        </div>
    </header>

    <!-- =====================================================================
         FLATSOME SECTION 1: SLIDER 2 ẢNH BANNER TỰ TRƯỢT KÍCH THƯỚC BẰNG NHAU
         - Thiết kế riêng Banner Máy Tính (Desktop) khác với Banner Điện Thoại (Mobile)
         - Chữ nhỏ gọn nằm trọn bên trong ảnh banner, tuyệt đối không tràn viền
    ====================================================================== -->
    <section id="trang-chu" class="py-3 md:py-4">
        <div class="flatsome-container">
            <div class="relative w-full overflow-hidden rounded-xl shadow-md border border-amber-500/30 bg-[#6e0d0d]">

                <!-- SLIDE 1 -->
                <div class="banner-slide transition-opacity duration-700 ease-in-out opacity-100 block" data-slide="0">
                    <!-- BANNER MÁY TÍNH (Desktop Slide 1 - Chiều cao cố định 380px bằng nhau) -->
                    <div class="hidden md:grid md:grid-cols-12 items-center h-[380px] w-full bg-gradient-to-r from-[#6e0d0d] via-[#991515] to-[#7a1010] px-10 lg:px-14 relative overflow-hidden">
                        <div class="col-span-7 z-10 pr-6">
                            <p class="text-amber-300 text-xs font-bold uppercase tracking-widest mb-1.5">LÒ HEO QUAY ĐÀ NẴNG - LOHEOQUAYDANANG.COM</p>
                            <h1 class="text-white text-2xl lg:text-3xl font-extrabold leading-snug mb-2.5">
                                HEO SỮA QUAY & HEO QUAY NGUYÊN CON DA GIÒN BÌ CỐM
                            </h1>
                            <p class="text-amber-100 text-xs lg:text-sm leading-relaxed mb-4 max-w-xl">
                                Chuyên phục vụ lễ Cúng Khai Trương, Đầy Tháng, Thôi Nôi, Thần Tài, Động Thổ, Cưới Hỏi. Tẩm ướp thảo mộc gia truyền, heo sạch kiểm dịch 100%, giao nóng tận nơi đúng giờ Hoàng Đạo.
                            </p>
                            <div class="bg-black/25 border border-amber-400/40 rounded-lg px-3.5 py-2 inline-block mb-4">
                                <p class="text-amber-200 text-xs font-semibold">
                                    <i class="fa-solid fa-location-dot text-amber-400 mr-1.5"></i>Đ/C: H97/40/27k138 Hoàng Văn Thái, Phường Hòa Khánh, TP. Đà Nẵng
                                </p>
                                <p class="text-white text-xs font-bold mt-0.5">
                                    <i class="fa-solid fa-phone-volume text-amber-400 mr-1.5"></i>Hotline/Zalo đặt heo: <span class="text-amber-300">0978.922.722</span> (Tặng kèm nước chấm + rau dưa)
                                </p>
                            </div>
                            <div class="flex items-center gap-3">
                                <a href="#san-pham-chu-luc" class="px-4 py-2 rounded-lg bg-amber-400 hover:bg-amber-300 text-[#6e0d0d] font-extrabold text-xs uppercase transition">
                                    Xem Bảng Giá Sản Phẩm
                                </a>
                                <a href="#bao-gia-nhanh" class="px-4 py-2 rounded-lg bg-white/15 hover:bg-white/25 text-white border border-white/30 font-bold text-xs uppercase transition">
                                    Đặt Heo Quay Ngay
                                </a>
                            </div>
                        </div>
                        <div class="col-span-5 h-full flex items-center justify-center py-5 z-10">
                            <div class="w-full h-[310px] rounded-xl overflow-hidden border-2 border-amber-400/70 shadow-xl bg-stone-900">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/1CO6KyqnCsKVMSWDRrHThikfcCOaaQmpn" 
                                    onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1CO6KyqnCsKVMSWDRrHThikfcCOaaQmpn&sz=w1000';"
                                    alt="Heo quay nguyên con Đà Nẵng" 
                                    class="w-full h-full object-cover"
                                >
                            </div>
                        </div>
                    </div>

                    <!-- BANNER ĐIỆN THOẠI (Mobile Slide 1 - Thiết kế khác máy tính, chiều cao 300px bằng nhau, chữ nhỏ gọn nằm hết bên trong ảnh) -->
                    <div class="flex md:hidden flex-col justify-between h-[300px] w-full bg-gradient-to-b from-[#7a1010] via-[#991515] to-[#5e0b0b] p-3.5 relative overflow-hidden">
                        <div class="flex items-center gap-2.5 bg-black/20 p-2 rounded-lg border border-amber-400/30">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1CO6KyqnCsKVMSWDRrHThikfcCOaaQmpn" 
                                onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1CO6KyqnCsKVMSWDRrHThikfcCOaaQmpn&sz=w600';"
                                alt="Heo sữa quay Đà Nẵng" 
                                class="w-20 h-20 rounded-lg object-cover border border-amber-300 shrink-0"
                            >
                            <div class="min-w-0 flex-1">
                                <span class="block text-[10px] font-bold text-amber-300 uppercase">LOHEOQUAYDANANG.COM</span>
                                <h2 class="text-white text-[13px] font-extrabold leading-tight mt-0.5">
                                    LÒ HEO QUAY ĐÀ NẴNG DA GIÒN BÌ CỐM
                                </h2>
                                <p class="text-amber-100 text-[11px] leading-snug mt-1">
                                    Heo sữa quay & Heo nguyên con cúng Đầy tháng, Khai trương, Thần Tài.
                                </p>
                            </div>
                        </div>
                        <div class="bg-black/25 rounded-lg p-2.5 border border-white/15 text-center my-auto">
                            <p class="text-amber-200 text-[11px] leading-snug font-medium">
                                Cam kết 3 KHÔNG: Không phẩm màu - Không chất bảo quản - Không quay lại nhiều lần. Tặng nước chấm, dưa chua, rau sống.
                            </p>
                            <p class="text-white text-[11px] font-bold mt-1">
                                Đ/C: H97/40/27k138 Hoàng Văn Thái, P. Hòa Khánh, Đà Nẵng
                            </p>
                        </div>
                        <div class="flex items-center justify-between gap-2 pt-1">
                            <span class="text-amber-300 text-xs font-extrabold">SĐT: 0978.922.722</span>
                            <a href="#bao-gia-nhanh" class="px-3 py-1.5 rounded bg-amber-400 text-[#6e0d0d] font-extrabold text-[11px] uppercase">
                                Đặt Hàng Ngay
                            </a>
                        </div>
                    </div>
                </div>

                <!-- SLIDE 2 -->
                <div class="banner-slide transition-opacity duration-700 ease-in-out opacity-0 hidden" data-slide="1">
                    <!-- BANNER MÁY TÍNH (Desktop Slide 2 - Chiều cao cố định 380px bằng Slide 1) -->
                    <div class="hidden md:grid md:grid-cols-12 items-center h-[380px] w-full bg-gradient-to-r from-[#5c0b0b] via-[#8c1414] to-[#6e0d0d] px-10 lg:px-14 relative overflow-hidden">
                        <div class="col-span-7 z-10 pr-6">
                            <p class="text-amber-300 text-xs font-bold uppercase tracking-widest mb-1.5">DỊCH VỤ ĐỒ CÚNG & HEO QUAY TRỌN GÓI ĐÀ NẴNG</p>
                            <h2 class="text-white text-2xl lg:text-3xl font-extrabold leading-snug mb-2.5">
                                MÂM CÚNG ĐẦY ĐỦ LỄ VẬT - BÀY TRÍ ĐẸP MẮT - GIAO ĐÚNG GIỜ
                            </h2>
                            <p class="text-amber-100 text-xs lg:text-sm leading-relaxed mb-4 max-w-xl">
                                Nhận đặt heo quay từ 1.5kg đến 22kg và mâm cúng trọn gói: Khai Trương, Động Thổ, Nhập Trạch, Đầy Tháng, Thôi Nôi, Cúng Thần Tài, Tất Niên. Miễn phí giao hàng nội thành Đà Nẵng.
                            </p>
                            <div class="bg-black/25 border border-amber-400/40 rounded-lg px-3.5 py-2 inline-block mb-4">
                                <p class="text-amber-200 text-xs font-semibold">
                                    <i class="fa-solid fa-gift text-amber-400 mr-1.5"></i>Ưu đãi: Giảm ngay 12% - 16% khi đặt trước qua Website hoặc Zalo
                                </p>
                                <p class="text-white text-xs font-bold mt-0.5">
                                    <i class="fa-solid fa-phone-volume text-amber-400 mr-1.5"></i>Liên hệ tư vấn 24/7: <span class="text-amber-300">0978.922.722</span> - Hòa Khánh, Đà Nẵng
                                </p>
                            </div>
                            <div class="flex items-center gap-3">
                                <a href="#mam-cung-tron-goi" class="px-4 py-2 rounded-lg bg-amber-400 hover:bg-amber-300 text-[#6e0d0d] font-extrabold text-xs uppercase transition">
                                    Xem Các Mâm Cúng
                                </a>
                                <a href="#lien-he-ban-do" class="px-4 py-2 rounded-lg bg-white/15 hover:bg-white/25 text-white border border-white/30 font-bold text-xs uppercase transition">
                                    Xem Bản Đồ Lò Quay
                                </a>
                            </div>
                        </div>
                        <div class="col-span-5 h-full flex items-center justify-center py-5 z-10">
                            <div class="w-full h-[310px] rounded-xl overflow-hidden border-2 border-amber-400/70 shadow-xl bg-stone-900">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/1ae9Q8ZjB1SOcM6HRo9rIM3tZUnbN7gAt" 
                                    onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1ae9Q8ZjB1SOcM6HRo9rIM3tZUnbN7gAt&sz=w1000';"
                                    alt="Mâm cúng heo quay Đà Nẵng" 
                                    class="w-full h-full object-cover"
                                >
                            </div>
                        </div>
                    </div>

                    <!-- BANNER ĐIỆN THOẠI (Mobile Slide 2 - Thiết kế khác máy tính, chiều cao 300px bằng Slide 1, chữ nhỏ gọn không tràn viền) -->
                    <div class="flex md:hidden flex-col justify-between h-[300px] w-full bg-gradient-to-b from-[#6e0d0d] via-[#8c1414] to-[#4d0909] p-3.5 relative overflow-hidden">
                        <div class="flex items-center gap-2.5 bg-black/20 p-2 rounded-lg border border-amber-400/30">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1ae9Q8ZjB1SOcM6HRo9rIM3tZUnbN7gAt" 
                                onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1ae9Q8ZjB1SOcM6HRo9rIM3tZUnbN7gAt&sz=w600';"
                                alt="Đặt mâm cúng heo quay Đà Nẵng" 
                                class="w-20 h-20 rounded-lg object-cover border border-amber-300 shrink-0"
                            >
                            <div class="min-w-0 flex-1">
                                <span class="block text-[10px] font-bold text-amber-300 uppercase">ƯU ĐÃI ĐẶT TRƯỚC 15%</span>
                                <h2 class="text-white text-[13px] font-extrabold leading-tight mt-0.5">
                                    MÂM CÚNG TRỌN GÓI & HEO QUAY CÚNG LỄ
                                </h2>
                                <p class="text-amber-100 text-[11px] leading-snug mt-1">
                                    Đầy đủ lễ vật, trang trí nơ đỏ trang trọng, giao nóng tận nhà.
                                </p>
                            </div>
                        </div>
                        <div class="bg-black/25 rounded-lg p-2.5 border border-white/15 text-center my-auto">
                            <p class="text-amber-200 text-[11px] leading-snug font-medium">
                                Đầy Tháng - Thôi Nôi - Khai Trương - Động Thổ - Nhập Trạch - Thần Tài - Tất Niên. Giao miễn phí nội thành Đà Nẵng.
                            </p>
                            <p class="text-white text-[11px] font-bold mt-1">
                                Đ/C: H97/40/27k138 Hoàng Văn Thái, P. Hòa Khánh, Đà Nẵng
                            </p>
                        </div>
                        <div class="flex items-center justify-between gap-2 pt-1">
                            <span class="text-amber-300 text-xs font-extrabold">Hotline: 0978.922.722</span>
                            <a href="#mam-cung-tron-goi" class="px-3 py-1.5 rounded bg-amber-400 text-[#6e0d0d] font-extrabold text-[11px] uppercase">
                                Xem Mâm Cúng
                            </a>
                        </div>
                    </div>
                </div>

                <!-- Nút chuyển Slide Trái / Phải & Chấm tròn điều hướng -->
                <button type="button" onclick="changeBannerSlide(-1)" aria-label="Slide trước" class="absolute left-2 top-1/2 -translate-y-1/2 z-20 w-7 h-7 md:w-9 md:h-9 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-left text-xs"></i>
                </button>
                <button type="button" onclick="changeBannerSlide(1)" aria-label="Slide tiếp" class="absolute right-2 top-1/2 -translate-y-1/2 z-20 w-7 h-7 md:w-9 md:h-9 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-right text-xs"></i>
                </button>
                <div class="absolute bottom-2 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                    <button type="button" onclick="goToBannerSlide(0)" id="slider-dot-0" aria-label="Slide 1" class="w-2.5 h-2.5 rounded-full bg-amber-400 transition"></button>
                    <button type="button" onclick="goToBannerSlide(1)" id="slider-dot-1" aria-label="Slide 2" class="w-2.5 h-2.5 rounded-full bg-white/50 transition"></button>
                </div>

            </div>
        </div>
    </section>

    <!-- =====================================================================
         FLATSOME SECTION 2: DANH MỤC SẢN PHẨM TRANG CHỦ
         - Tối ưu danh mục trên máy tính và điện thoại đẹp, chữ nhỏ gọn,
           không xuống dòng tên danh mục
    ====================================================================== -->
    <section class="py-5 bg-white border-y border-stone-200">
        <div class="flatsome-container">
            <div class="flatsome-section-title">
                <span class="text-sm md:text-lg">DANH MỤC SẢN PHẨM & DỊCH VỤ</span>
            </div>

            <!-- Danh mục sản phẩm thiết kế gọn đẹp trên cả máy tính và điện thoại -->
            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-2.5 md:gap-4">
                <a href="#heo-sua-quay" class="group bg-[#fdfaf6] hover:bg-red-50 border border-stone-200 hover:border-[#a81817] rounded-xl p-2.5 flex flex-col items-center text-center transition">
                    <div class="w-14 h-14 md:w-16 md:h-16 rounded-full overflow-hidden border-2 border-amber-500 mb-2 shrink-0">
                        <img src="https://lh3.googleusercontent.com/d/1CO6KyqnCsKVMSWDRrHThikfcCOaaQmpn" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1CO6KyqnCsKVMSWDRrHThikfcCOaaQmpn&sz=w400';" alt="Heo Sữa Quay" class="w-full h-full object-cover group-hover:scale-105 transition">
                    </div>
                    <span class="home-cat-pill font-bold text-stone-800 group-hover:text-[#a81817]">Heo Sữa Quay</span>
                    <span class="text-[11px] text-stone-500 mt-0.5">Size 1.5kg - 3.8kg</span>
                </a>

                <a href="#heo-quay-nguyen-con" class="group bg-[#fdfaf6] hover:bg-red-50 border border-stone-200 hover:border-[#a81817] rounded-xl p-2.5 flex flex-col items-center text-center transition">
                    <div class="w-14 h-14 md:w-16 md:h-16 rounded-full overflow-hidden border-2 border-amber-500 mb-2 shrink-0">
                        <img src="https://lh3.googleusercontent.com/d/17wT6uMKy3-4cyZJWGff8jZG5MoT-Q8k-" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=17wT6uMKy3-4cyZJWGff8jZG5MoT-Q8k-&sz=w400';" alt="Heo Quay Nguyên Con" class="w-full h-full object-cover group-hover:scale-105 transition">
                    </div>
                    <span class="home-cat-pill font-bold text-stone-800 group-hover:text-[#a81817]">Heo Nguyên Con</span>
                    <span class="text-[11px] text-stone-500 mt-0.5">Size 4kg - 22kg</span>
                </a>

                <a href="#mam-cung-tron-goi" class="group bg-[#fdfaf6] hover:bg-red-50 border border-stone-200 hover:border-[#a81817] rounded-xl p-2.5 flex flex-col items-center text-center transition">
                    <div class="w-14 h-14 md:w-16 md:h-16 rounded-full overflow-hidden border-2 border-amber-500 mb-2 shrink-0">
                        <img src="https://lh3.googleusercontent.com/d/1ae9Q8ZjB1SOcM6HRo9rIM3tZUnbN7gAt" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1ae9Q8ZjB1SOcM6HRo9rIM3tZUnbN7gAt&sz=w400';" alt="Cúng Đầy Tháng Thôi Nôi" class="w-full h-full object-cover group-hover:scale-105 transition">
                    </div>
                    <span class="home-cat-pill font-bold text-stone-800 group-hover:text-[#a81817]">Cúng Đầy Tháng</span>
                    <span class="text-[11px] text-stone-500 mt-0.5">Mâm cúng trọn gói</span>
                </a>

                <a href="#mam-cung-tron-goi" class="group bg-[#fdfaf6] hover:bg-red-50 border border-stone-200 hover:border-[#a81817] rounded-xl p-2.5 flex flex-col items-center text-center transition">
                    <div class="w-14 h-14 md:w-16 md:h-16 rounded-full overflow-hidden border-2 border-amber-500 mb-2 shrink-0">
                        <img src="https://lh3.googleusercontent.com/d/1q8o_1zVAuxiQsxYHH5dALvDny2dPtWaU" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1q8o_1zVAuxiQsxYHH5dALvDny2dPtWaU&sz=w400';" alt="Cúng Khai Trương" class="w-full h-full object-cover group-hover:scale-105 transition">
                    </div>
                    <span class="home-cat-pill font-bold text-stone-800 group-hover:text-[#a81817]">Cúng Khai Trương</span>
                    <span class="text-[11px] text-stone-500 mt-0.5">Hồng phát tài lộc</span>
                </a>

                <a href="#mam-cung-tron-goi" class="group bg-[#fdfaf6] hover:bg-red-50 border border-stone-200 hover:border-[#a81817] rounded-xl p-2.5 flex flex-col items-center text-center transition">
                    <div class="w-14 h-14 md:w-16 md:h-16 rounded-full overflow-hidden border-2 border-amber-500 mb-2 shrink-0">
                        <img src="https://lh3.googleusercontent.com/d/1vxvqh8dgfD0fmhUPOfy2WanUoELHD59N" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1vxvqh8dgfD0fmhUPOfy2WanUoELHD59N&sz=w400';" alt="Cúng Thần Tài" class="w-full h-full object-cover group-hover:scale-105 transition">
                    </div>
                    <span class="home-cat-pill font-bold text-stone-800 group-hover:text-[#a81817]">Cúng Thần Tài</span>
                    <span class="text-[11px] text-stone-500 mt-0.5">Động thổ / Nhập trạch</span>
                </a>

                <a href="#heo-quay-nguyen-con" class="group bg-[#fdfaf6] hover:bg-red-50 border border-stone-200 hover:border-[#a81817] rounded-xl p-2.5 flex flex-col items-center text-center transition">
                    <div class="w-14 h-14 md:w-16 md:h-16 rounded-full overflow-hidden border-2 border-amber-500 mb-2 shrink-0">
                        <img src="https://lh3.googleusercontent.com/d/1pkFCiHM2YXCkM2aoZW9NtfvMK3UaIcqc" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1pkFCiHM2YXCkM2aoZW9NtfvMK3UaIcqc&sz=w400';" alt="Heo Quay Đãi Tiệc" class="w-full h-full object-cover group-hover:scale-105 transition">
                    </div>
                    <span class="home-cat-pill font-bold text-stone-800 group-hover:text-[#a81817]">Heo Quay Đãi Tiệc</span>
                    <span class="text-[11px] text-stone-500 mt-0.5">Cưới hỏi / Tất niên</span>
                </a>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         FLATSOME SECTION 3: DANH MỤC 1 - HEO SỮA QUAY ĐÀ NẴNG
         - Chia 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính
         - Tên sản phẩm hiển thị đầy đủ, không bị tràn hoặc thiếu chữ
         - Có giá giảm và % giảm giá góc trên bên trái giống Flatsome
    ====================================================================== -->
    <section id="heo-sua-quay" class="py-7">
        <div id="san-pham-chu-luc" class="flatsome-container">
            <div class="flatsome-section-title">
                <span class="text-sm md:text-lg">HEO SỮA QUAY ĐÀ NẴNG (DA GIÒN RỤM - THỊT MỀM NGỌT)</span>
            </div>
            <p class="text-center text-xs md:text-sm text-stone-600 mb-5 max-w-3xl mx-auto">
                Dòng sản phẩm được ưa chuộng nhất cho mâm cúng Đầy tháng, Thôi nôi, Cúng Thần Tài và tiệc gia đình. Tặng kèm bộ đồ ăn gồm: Nước chấm gia truyền, Dưa chua, Rau thơm tươi sạch và miễn phí giao nội thành Đà Nẵng.
            </p>

            <!-- Lưới sản phẩm: 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 md:gap-5">

                <!-- Sản phẩm 1 (Ảnh thực tế 1) -->
                <div class="bg-white rounded-xl border border-stone-200 shadow-sm hover:shadow-md transition flex flex-col overflow-hidden">
                    <div class="relative aspect-[4/3] w-full bg-stone-100 overflow-hidden">
                        <span class="flatsome-Discount-badge">-16%</span>
                        <img 
                            src="https://lh3.googleusercontent.com/d/1CO6KyqnCsKVMSWDRrHThikfcCOaaQmpn" 
                            onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1CO6KyqnCsKVMSWDRrHThikfcCOaaQmpn&sz=w800';"
                            alt="Heo Sữa Quay 1,5 - 1,8kg Đà Nẵng" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 md:p-4 flex flex-col flex-1 justify-between">
                        <div>
                            <p class="text-[10.5px] text-stone-500 uppercase font-semibold mb-1">Heo Sữa Quay</p>
                            <h3 class="text-xs sm:text-sm md:text-base font-bold text-stone-800 leading-snug break-words">
                                Heo Sữa Quay 1,5 - 1,8kg Nguyên Con Da Giòn
                            </h3>
                            <p class="text-[11px] text-stone-600 mt-1 leading-normal">
                                Phù hợp cúng Thần Tài, Đầy tháng, Thôi nôi (4 - 6 người ăn).
                            </p>
                        </div>
                        <div class="mt-3 pt-2.5 border-t border-stone-100">
                            <div class="flex flex-wrap items-baseline gap-1.5 mb-2.5">
                                <del class="text-[11px] md:text-xs text-stone-400">950.000đ</del>
                                <span class="text-sm md:text-base font-extrabold text-[#a81817]">799.000đ</span>
                            </div>
                            <button type="button" onclick="selectProductForQuote('Heo Sữa Quay 1,5 - 1,8kg (799.000đ)')" class="w-full py-2 px-2 rounded-lg bg-[#a81817] hover:bg-[#7f1010] text-white font-bold text-xs uppercase transition">
                                Đặt Mua Ngay
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 2 (Ảnh thực tế 2) -->
                <div class="bg-white rounded-xl border border-stone-200 shadow-sm hover:shadow-md transition flex flex-col overflow-hidden">
                    <div class="relative aspect-[4/3] w-full bg-stone-100 overflow-hidden">
                        <span class="flatsome-Discount-badge">-12%</span>
                        <img 
                            src="https://lh3.googleusercontent.com/d/1ae9Q8ZjB1SOcM6HRo9rIM3tZUnbN7gAt" 
                            onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1ae9Q8ZjB1SOcM6HRo9rIM3tZUnbN7gAt&sz=w800';"
                            alt="Heo Sữa Quay 1,9 - 2,5kg Đà Nẵng" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 md:p-4 flex flex-col flex-1 justify-between">
                        <div>
                            <p class="text-[10.5px] text-stone-500 uppercase font-semibold mb-1">Heo Sữa Quay</p>
                            <h3 class="text-xs sm:text-sm md:text-base font-bold text-stone-800 leading-snug break-words">
                                Heo Sữa Quay 1,9 - 2,5kg Size Nhỡ Thịt Dày
                            </h3>
                            <p class="text-[11px] text-stone-600 mt-1 leading-normal">
                                Phù hợp cúng Khai trương, Thần Tài, tiệc gia đình (6 - 8 người ăn).
                            </p>
                        </div>
                        <div class="mt-3 pt-2.5 border-t border-stone-100">
                            <div class="flex flex-wrap items-baseline gap-1.5 mb-2.5">
                                <del class="text-[11px] md:text-xs text-stone-400">1.250.000đ</del>
                                <span class="text-sm md:text-base font-extrabold text-[#a81817]">1.099.000đ</span>
                            </div>
                            <button type="button" onclick="selectProductForQuote('Heo Sữa Quay 1,9 - 2,5kg (1.099.000đ)')" class="w-full py-2 px-2 rounded-lg bg-[#a81817] hover:bg-[#7f1010] text-white font-bold text-xs uppercase transition">
                                Đặt Mua Ngay
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 3 (Ảnh thực tế 3) -->
                <div class="bg-white rounded-xl border border-stone-200 shadow-sm hover:shadow-md transition flex flex-col overflow-hidden">
                    <div class="relative aspect-[4/3] w-full bg-stone-100 overflow-hidden">
                        <span class="flatsome-Discount-badge">-13%</span>
                        <img 
                            src="https://lh3.googleusercontent.com/d/1Hv4O_TGrZ_8mARxibtRyr6PqMGZl5Ebp" 
                            onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1Hv4O_TGrZ_8mARxibtRyr6PqMGZl5Ebp&sz=w800';"
                            alt="Heo Sữa Quay 2,6 - 2,9kg Đà Nẵng" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 md:p-4 flex flex-col flex-1 justify-between">
                        <div>
                            <p class="text-[10.5px] text-stone-500 uppercase font-semibold mb-1">Heo Sữa Quay</p>
                            <h3 class="text-xs sm:text-sm md:text-base font-bold text-stone-800 leading-snug break-words">
                                Heo Sữa Quay 2,6 - 2,9kg Da Nổ Giòn Tan
                            </h3>
                            <p class="text-[11px] text-stone-600 mt-1 leading-normal">
                                Dáng heo căng tròn, trang trí nơ đỏ đẹp mắt (8 - 10 người ăn).
                            </p>
                        </div>
                        <div class="mt-3 pt-2.5 border-t border-stone-100">
                            <div class="flex flex-wrap items-baseline gap-1.5 mb-2.5">
                                <del class="text-[11px] md:text-xs text-stone-400">1.490.000đ</del>
                                <span class="text-sm md:text-base font-extrabold text-[#a81817]">1.299.000đ</span>
                            </div>
                            <button type="button" onclick="selectProductForQuote('Heo Sữa Quay 2,6 - 2,9kg (1.299.000đ)')" class="w-full py-2 px-2 rounded-lg bg-[#a81817] hover:bg-[#7f1010] text-white font-bold text-xs uppercase transition">
                                Đặt Mua Ngay
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 4 (Ảnh thực tế 4) -->
                <div class="bg-white rounded-xl border border-stone-200 shadow-sm hover:shadow-md transition flex flex-col overflow-hidden">
                    <div class="relative aspect-[4/3] w-full bg-stone-100 overflow-hidden">
                        <span class="flatsome-Discount-badge">-15%</span>
                        <img 
                            src="https://lh3.googleusercontent.com/d/1SvqKDslODY2Nqu58jEYkHlplnXkLk71l" 
                            onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1SvqKDslODY2Nqu58jEYkHlplnXkLk71l&sz=w800';"
                            alt="Heo Sữa Quay 3 - 3,8kg Đà Nẵng" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 md:p-4 flex flex-col flex-1 justify-between">
                        <div>
                            <p class="text-[10.5px] text-stone-500 uppercase font-semibold mb-1">Heo Sữa Quay</p>
                            <h3 class="text-xs sm:text-sm md:text-base font-bold text-stone-800 leading-snug break-words">
                                Heo Sữa Quay 3 - 3,8kg Đặc Biệt Cúng Lễ
                            </h3>
                            <p class="text-[11px] text-stone-600 mt-1 leading-normal">
                                Thịt mềm mọng nước, thơm mùi thảo mộc (10 - 12 người ăn).
                            </p>
                        </div>
                        <div class="mt-3 pt-2.5 border-t border-stone-100">
                            <div class="flex flex-wrap items-baseline gap-1.5 mb-2.5">
                                <del class="text-[11px] md:text-xs text-stone-400">1.650.000đ</del>
                                <span class="text-sm md:text-base font-extrabold text-[#a81817]">1.399.000đ</span>
                            </div>
                            <button type="button" onclick="selectProductForQuote('Heo Sữa Quay 3 - 3,8kg (1.399.000đ)')" class="w-full py-2 px-2 rounded-lg bg-[#a81817] hover:bg-[#7f1010] text-white font-bold text-xs uppercase transition">
                                Đặt Mua Ngay
                            </button>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- =====================================================================
         FLATSOME SECTION 4: DANH MỤC 2 - HEO QUAY NGUYÊN CON LỚN (4KG - 22KG)
         - Sử dụng 5 ảnh thực tế tiếp theo từ Google Drive
         - Chia 2 cột trên điện thoại, tên sản phẩm đầy đủ không tràn viền
    ====================================================================== -->
    <section id="heo-quay-nguyen-con" class="py-7 bg-white border-t border-stone-200">
        <div class="flatsome-container">
            <div class="flatsome-section-title">
                <span class="text-sm md:text-lg">HEO QUAY NGUYÊN CON ĐÀ NẴNG (CÚNG ĐẠI LỄ - ĐÁM CƯỚI - KHAI TRƯƠNG)</span>
            </div>
            <p class="text-center text-xs md:text-sm text-stone-600 mb-5 max-w-3xl mx-auto">
                Heo quay nguyên con dáng bệ vệ, lớp da nổ cốm vàng óng tự nhiên, thịt dày săn chắc. Chuyên phục vụ lễ Khai trương công ty, Động thổ dự án, Cưới hỏi, Cúng Tổ nghề, Tất niên.
            </p>

            <!-- Lưới sản phẩm: 2 cột trên điện thoại, 3-5 cột trên máy tính -->
            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-3 md:gap-4">

                <!-- Sản phẩm 5 (Ảnh thực tế 5) -->
                <div class="bg-[#fdfaf6] rounded-xl border border-stone-200 shadow-sm hover:shadow-md transition flex flex-col overflow-hidden">
                    <div class="relative aspect-[4/3] w-full bg-stone-100 overflow-hidden">
                        <span class="flatsome-Discount-badge">-14%</span>
                        <img 
                            src="https://lh3.googleusercontent.com/d/17wT6uMKy3-4cyZJWGff8jZG5MoT-Q8k-" 
                            onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=17wT6uMKy3-4cyZJWGff8jZG5MoT-Q8k-&sz=w800';"
                            alt="Heo Quay Nguyên Con 4 - 4,8kg" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
                        <div>
                            <p class="text-[10px] text-stone-500 uppercase font-semibold mb-1">Heo Nguyên Con</p>
                            <h3 class="text-xs sm:text-sm font-bold text-stone-800 leading-snug break-words">
                                Heo Quay Nguyên Con 4 - 4,8kg Chuẩn Lễ
                            </h3>
                            <p class="text-[11px] text-stone-600 mt-1">
                                Cúng Khai trương, Nhập trạch, tiệc 12 - 15 người.
                            </p>
                        </div>
                        <div class="mt-3 pt-2 border-t border-stone-200">
                            <div class="flex flex-wrap items-baseline gap-1.5 mb-2">
                                <del class="text-[11px] text-stone-400">1.850.000đ</del>
                                <span class="text-sm font-extrabold text-[#a81817]">1.599.000đ</span>
                            </div>
                            <button type="button" onclick="selectProductForQuote('Heo Quay Nguyên Con 4 - 4,8kg (1.599.000đ)')" class="w-full py-2 px-2 rounded-lg bg-[#a81817] hover:bg-[#7f1010] text-white font-bold text-xs uppercase transition">
                                Đặt Mua Ngay
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 6 (Ảnh thực tế 6) -->
                <div class="bg-[#fdfaf6] rounded-xl border border-stone-200 shadow-sm hover:shadow-md transition flex flex-col overflow-hidden">
                    <div class="relative aspect-[4/3] w-full bg-stone-100 overflow-hidden">
                        <span class="flatsome-Discount-badge">-15%</span>
                        <img 
                            src="https://lh3.googleusercontent.com/d/1q8o_1zVAuxiQsxYHH5dALvDny2dPtWaU" 
                            onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1q8o_1zVAuxiQsxYHH5dALvDny2dPtWaU&sz=w800';"
                            alt="Heo Quay Nguyên Con 5 - 5,8kg" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
                        <div>
                            <p class="text-[10px] text-stone-500 uppercase font-semibold mb-1">Heo Nguyên Con</p>
                            <h3 class="text-xs sm:text-sm font-bold text-stone-800 leading-snug break-words">
                                Heo Quay Nguyên Con 5 - 5,8kg Da Giòn Cốm
                            </h3>
                            <p class="text-[11px] text-stone-600 mt-1">
                                Cúng Động thổ, Khai trương, tiệc 15 - 20 người.
                            </p>
                        </div>
                        <div class="mt-3 pt-2 border-t border-stone-200">
                            <div class="flex flex-wrap items-baseline gap-1.5 mb-2">
                                <del class="text-[11px] text-stone-400">1.990.000đ</del>
                                <span class="text-sm font-extrabold text-[#a81817]">1.699.000đ</span>
                            </div>
                            <button type="button" onclick="selectProductForQuote('Heo Quay Nguyên Con 5 - 5,8kg (1.699.000đ)')" class="w-full py-2 px-2 rounded-lg bg-[#a81817] hover:bg-[#7f1010] text-white font-bold text-xs uppercase transition">
                                Đặt Mua Ngay
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 7 (Ảnh thực tế 7) -->
                <div class="bg-[#fdfaf6] rounded-xl border border-stone-200 shadow-sm hover:shadow-md transition flex flex-col overflow-hidden">
                    <div class="relative aspect-[4/3] w-full bg-stone-100 overflow-hidden">
                        <span class="flatsome-Discount-badge">-14%</span>
                        <img 
                            src="https://lh3.googleusercontent.com/d/1vxvqh8dgfD0fmhUPOfy2WanUoELHD59N" 
                            onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1vxvqh8dgfD0fmhUPOfy2WanUoELHD59N&sz=w800';"
                            alt="Heo Quay Nguyên Con 6 - 6,8kg" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
                        <div>
                            <p class="text-[10px] text-stone-500 uppercase font-semibold mb-1">Heo Nguyên Con</p>
                            <h3 class="text-xs sm:text-sm font-bold text-stone-800 leading-snug break-words">
                                Heo Quay Nguyên Con 6 - 6,8kg Cúng Cưới Hỏi
                            </h3>
                            <p class="text-[11px] text-stone-600 mt-1">
                                Dáng đẹp uy nghi, phù hợp tiệc 25 - 35 người.
                            </p>
                        </div>
                        <div class="mt-3 pt-2 border-t border-stone-200">
                            <div class="flex flex-wrap items-baseline gap-1.5 mb-2">
                                <del class="text-[11px] text-stone-400">2.150.000đ</del>
                                <span class="text-sm font-extrabold text-[#a81817]">1.850.000đ</span>
                            </div>
                            <button type="button" onclick="selectProductForQuote('Heo Quay Nguyên Con 6 - 6,8kg (1.850.000đ)')" class="w-full py-2 px-2 rounded-lg bg-[#a81817] hover:bg-[#7f1010] text-white font-bold text-xs uppercase transition">
                                Đặt Mua Ngay
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 8 (Ảnh thực tế 8) -->
                <div class="bg-[#fdfaf6] rounded-xl border border-stone-200 shadow-sm hover:shadow-md transition flex flex-col overflow-hidden">
                    <div class="relative aspect-[4/3] w-full bg-stone-100 overflow-hidden">
                        <span class="flatsome-Discount-badge">-15%</span>
                        <img 
                            src="https://lh3.googleusercontent.com/d/1S87FEtO5wTLsM19spNcyOX-PFX8tYudL" 
                            onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1S87FEtO5wTLsM19spNcyOX-PFX8tYudL&sz=w800';"
                            alt="Heo Quay Nguyên Con 7 - 7,8kg" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
                        <div>
                            <p class="text-[10px] text-stone-500 uppercase font-semibold mb-1">Heo Nguyên Con</p>
                            <h3 class="text-xs sm:text-sm font-bold text-stone-800 leading-snug break-words">
                                Heo Quay Nguyên Con 7 - 7,8kg Cúng Đại Lễ
                            </h3>
                            <p class="text-[11px] text-stone-600 mt-1">
                                Cúng Khánh thành, Dự án lớn, tiệc 35 - 45 người.
                            </p>
                        </div>
                        <div class="mt-3 pt-2 border-t border-stone-200">
                            <div class="flex flex-wrap items-baseline gap-1.5 mb-2">
                                <del class="text-[11px] text-stone-400">2.350.000đ</del>
                                <span class="text-sm font-extrabold text-[#a81817]">1.999.000đ</span>
                            </div>
                            <button type="button" onclick="selectProductForQuote('Heo Quay Nguyên Con 7 - 7,8kg (1.999.000đ)')" class="w-full py-2 px-2 rounded-lg bg-[#a81817] hover:bg-[#7f1010] text-white font-bold text-xs uppercase transition">
                                Đặt Mua Ngay
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 9 (Ảnh thực tế 9) -->
                <div class="bg-[#fdfaf6] rounded-xl border border-stone-200 shadow-sm hover:shadow-md transition flex flex-col overflow-hidden col-span-2 md:col-span-1">
                    <div class="relative aspect-[4/3] w-full bg-stone-100 overflow-hidden">
                        <span class="flatsome-Discount-badge">-14%</span>
                        <img 
                            src="https://lh3.googleusercontent.com/d/1pkFCiHM2YXCkM2aoZW9NtfvMK3UaIcqc" 
                            onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1pkFCiHM2YXCkM2aoZW9NtfvMK3UaIcqc&sz=w800';"
                            alt="Heo Quay Nguyên Con 8 - 22kg" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
                        <div>
                            <p class="text-[10px] text-stone-500 uppercase font-semibold mb-1">Heo Size Lớn</p>
                            <h3 class="text-xs sm:text-sm font-bold text-stone-800 leading-snug break-words">
                                Heo Quay Nguyên Con 8kg - 22kg (Tính Theo Kg)
                            </h3>
                            <p class="text-[11px] text-stone-600 mt-1">
                                Đặt theo số kg yêu cầu cho Công trình, Tất niên, Đãi tiệc.
                            </p>
                        </div>
                        <div class="mt-3 pt-2 border-t border-stone-200">
                            <div class="flex flex-wrap items-baseline gap-1.5 mb-2">
                                <del class="text-[11px] text-stone-400">280.000đ/kg</del>
                                <span class="text-sm font-extrabold text-[#a81817]">230.000đ/kg</span>
                            </div>
                            <button type="button" onclick="selectProductForQuote('Heo Quay Nguyên Con Lớn 8kg - 22kg (230.000đ/kg)')" class="w-full py-2 px-2 rounded-lg bg-[#a81817] hover:bg-[#7f1010] text-white font-bold text-xs uppercase transition">
                                Đặt Mua Ngay
                            </button>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- =====================================================================
         FLATSOME SECTION 5: DỊCH VỤ MÂM CÚNG TRỌN GÓI (Theo Web Mẫu heoquaydanang.net)
         - Chia 2 cột trên điện thoại, 4 cột trên máy tính
         - Có % giảm giá góc trên bên trái chuẩn Flatsome
    ====================================================================== -->
    <section id="mam-cung-tron-goi" class="py-7">
        <div class="flatsome-container">
            <div class="flatsome-section-title">
                <span class="text-sm md:text-lg">DỊCH VỤ MÂM CÚNG TRỌN GÓI TẠI ĐÀ NẴNG</span>
            </div>
            <p class="text-center text-xs md:text-sm text-stone-600 mb-5 max-w-3xl mx-auto">
                "Lễ vật đầy đủ - Bày trí đẹp mắt - Giao đúng giờ Hoàng Đạo". Chuẩn bị trọn gói từ Heo quay, Xôi chè, Gà luộc, Trái cây, Hoa tươi, Nhang đèn đến Bài văn khấn chuẩn phong tục.
            </p>

            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 md:gap-5">
                <!-- Mâm cúng 1 -->
                <div class="bg-white rounded-xl border border-stone-200 shadow-sm hover:shadow-md transition flex flex-col overflow-hidden">
                    <div class="relative aspect-[4/3] w-full bg-stone-100 overflow-hidden">
                        <span class="flatsome-Discount-badge">-15%</span>
                        <img src="https://lh3.googleusercontent.com/d/1ae9Q8ZjB1SOcM6HRo9rIM3tZUnbN7gAt" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1ae9Q8ZjB1SOcM6HRo9rIM3tZUnbN7gAt&sz=w800';" alt="Mâm Cúng Đầy Tháng Thôi Nôi" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 md:p-4 flex flex-col flex-1 justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm md:text-base font-bold text-stone-800 leading-snug break-words">
                                Mâm Cúng Đầy Tháng / Thôi Nôi Kèm Heo Sữa Quay
                            </h3>
                            <p class="text-[11px] text-stone-600 mt-1">
                                Mẹ tròn con vuông, cầu bé hay ăn chóng lớn, bình an.
                            </p>
                        </div>
                        <div class="mt-3 pt-2.5 border-t border-stone-100">
                            <div class="flex flex-wrap items-baseline gap-1.5 mb-2.5">
                                <del class="text-[11px] text-stone-400">2.100.000đ</del>
                                <span class="text-sm md:text-base font-extrabold text-[#a81817]">1.790.000đ</span>
                            </div>
                            <button type="button" onclick="selectProductForQuote('Mâm Cúng Đầy Tháng / Thôi Nôi Trọn Gói (1.790.000đ)')" class="w-full py-2 px-2 rounded-lg bg-[#a81817] hover:bg-[#7f1010] text-white font-bold text-xs uppercase transition">
                                Tư Vấn & Đặt Mâm
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Mâm cúng 2 -->
                <div class="bg-white rounded-xl border border-stone-200 shadow-sm hover:shadow-md transition flex flex-col overflow-hidden">
                    <div class="relative aspect-[4/3] w-full bg-stone-100 overflow-hidden">
                        <span class="flatsome-Discount-badge">-14%</span>
                        <img src="https://lh3.googleusercontent.com/d/1q8o_1zVAuxiQsxYHH5dALvDny2dPtWaU" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1q8o_1zVAuxiQsxYHH5dALvDny2dPtWaU&sz=w800';" alt="Mâm Cúng Khai Trương Hồng Phát" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 md:p-4 flex flex-col flex-1 justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm md:text-base font-bold text-stone-800 leading-snug break-words">
                                Mâm Cúng Khai Trương Cửa Hàng / Công Ty Hồng Phát
                            </h3>
                            <p class="text-[11px] text-stone-600 mt-1">
                                Kích hoạt tài lộc, buôn may bán đắt, vạn sự hanh thông.
                            </p>
                        </div>
                        <div class="mt-3 pt-2.5 border-t border-stone-100">
                            <div class="flex flex-wrap items-baseline gap-1.5 mb-2.5">
                                <del class="text-[11px] text-stone-400">2.300.000đ</del>
                                <span class="text-sm md:text-base font-extrabold text-[#a81817]">1.980.000đ</span>
                            </div>
                            <button type="button" onclick="selectProductForQuote('Mâm Cúng Khai Trương Trọn Gói (1.980.000đ)')" class="w-full py-2 px-2 rounded-lg bg-[#a81817] hover:bg-[#7f1010] text-white font-bold text-xs uppercase transition">
                                Tư Vấn & Đặt Mâm
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Mâm cúng 3 -->
                <div class="bg-white rounded-xl border border-stone-200 shadow-sm hover:shadow-md transition flex flex-col overflow-hidden">
                    <div class="relative aspect-[4/3] w-full bg-stone-100 overflow-hidden">
                        <span class="flatsome-Discount-badge">-13%</span>
                        <img src="https://lh3.googleusercontent.com/d/1vxvqh8dgfD0fmhUPOfy2WanUoELHD59N" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1vxvqh8dgfD0fmhUPOfy2WanUoELHD59N&sz=w800';" alt="Mâm Cúng Động Thổ Nhập Trạch" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 md:p-4 flex flex-col flex-1 justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm md:text-base font-bold text-stone-800 leading-snug break-words">
                                Mâm Cúng Động Thổ / Khởi Công & Nhập Trạch Nhà Mới
                            </h3>
                            <p class="text-[11px] text-stone-600 mt-1">
                                Cầu công trình suôn sẻ, an cư lạc nghiệp, gia đạo hưng long.
                            </p>
                        </div>
                        <div class="mt-3 pt-2.5 border-t border-stone-100">
                            <div class="flex flex-wrap items-baseline gap-1.5 mb-2.5">
                                <del class="text-[11px] text-stone-400">2.250.000đ</del>
                                <span class="text-sm md:text-base font-extrabold text-[#a81817]">1.950.000đ</span>
                            </div>
                            <button type="button" onclick="selectProductForQuote('Mâm Cúng Động Thổ / Nhập Trạch (1.950.000đ)')" class="w-full py-2 px-2 rounded-lg bg-[#a81817] hover:bg-[#7f1010] text-white font-bold text-xs uppercase transition">
                                Tư Vấn & Đặt Mâm
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Mâm cúng 4 -->
                <div class="bg-white rounded-xl border border-stone-200 shadow-sm hover:shadow-md transition flex flex-col overflow-hidden">
                    <div class="relative aspect-[4/3] w-full bg-stone-100 overflow-hidden">
                        <span class="flatsome-Discount-badge">-15%</span>
                        <img src="https://lh3.googleusercontent.com/d/1S87FEtO5wTLsM19spNcyOX-PFX8tYudL" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1S87FEtO5wTLsM19spNcyOX-PFX8tYudL&sz=w800';" alt="Mâm Cúng Thần Tài Tất Niên" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 md:p-4 flex flex-col flex-1 justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm md:text-base font-bold text-stone-800 leading-snug break-words">
                                Mâm Cúng Thần Tài / Cúng Đất Đai / Tất Niên Cuối Năm
                            </h3>
                            <p class="text-[11px] text-stone-600 mt-1">
                                Rước lộc vào nhà, tạ ơn Thổ Thần, sum vầy ấm cúng.
                            </p>
                        </div>
                        <div class="mt-3 pt-2.5 border-t border-stone-100">
                            <div class="flex flex-wrap items-baseline gap-1.5 mb-2.5">
                                <del class="text-[11px] text-stone-400">1.950.000đ</del>
                                <span class="text-sm md:text-base font-extrabold text-[#a81817]">1.650.000đ</span>
                            </div>
                            <button type="button" onclick="selectProductForQuote('Mâm Cúng Thần Tài / Đất Đai / Tất Niên (1.650.000đ)')" class="w-full py-2 px-2 rounded-lg bg-[#a81817] hover:bg-[#7f1010] text-white font-bold text-xs uppercase transition">
                                Tư Vấn & Đặt Mâm
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         FLATSOME SECTION 6: BẢNG GIÁ TỔNG HỢP & GIỚI THIỆU LÒ QUAY
    ====================================================================== -->
    <section id="bang-gia" class="py-7 bg-white border-y border-stone-200">
        <div id="gioi-thieu" class="flatsome-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-start">
                <!-- Cột Bảng Giá -->
                <div class="lg:col-span-7">
                    <h2 class="text-base md:text-lg font-extrabold text-[#a81817] uppercase mb-3">
                        BẢNG GIÁ HEO QUAY ĐÀ NẴNG MỚI NHẤT
                    </h2>
                    <div class="overflow-x-auto rounded-xl border border-stone-200">
                        <table class="w-full text-left border-collapse text-xs md:text-sm">
                            <thead>
                                <tr class="bg-[#a81817] text-white">
                                    <th class="py-2.5 px-3 font-bold">Phân Loại Heo Quay</th>
                                    <th class="py-2.5 px-3 font-bold">Giá Gốc</th>
                                    <th class="py-2.5 px-3 font-bold">Giá Ưu Đãi</th>
                                    <th class="py-2.5 px-3 font-bold">Khẩu Phần</th>
                                </tr>
                            </thead>
                            <tbody class="divide-y divide-stone-200 bg-[#fdfaf6]">
                                <tr>
                                    <td class="py-2 px-3 font-semibold">Heo Sữa Quay 1,5 - 1,8kg</td>
                                    <td class="py-2 px-3 text-stone-400 line-through">950.000đ</td>
                                    <td class="py-2 px-3 font-extrabold text-[#a81817]">799.000đ</td>
                                    <td class="py-2 px-3">4 - 6 người</td>
                                </tr>
                                <tr>
                                    <td class="py-2 px-3 font-semibold">Heo Sữa Quay 1,9 - 2,5kg</td>
                                    <td class="py-2 px-3 text-stone-400 line-through">1.250.000đ</td>
                                    <td class="py-2 px-3 font-extrabold text-[#a81817]">1.099.000đ</td>
                                    <td class="py-2 px-3">6 - 8 người</td>
                                </tr>
                                <tr>
                                    <td class="py-2 px-3 font-semibold">Heo Sữa Quay 2,6 - 2,9kg</td>
                                    <td class="py-2 px-3 text-stone-400 line-through">1.490.000đ</td>
                                    <td class="py-2 px-3 font-extrabold text-[#a81817]">1.299.000đ</td>
                                    <td class="py-2 px-3">8 - 10 người</td>
                                </tr>
                                <tr>
                                    <td class="py-2 px-3 font-semibold">Heo Sữa Quay 3,0 - 3,8kg</td>
                                    <td class="py-2 px-3 text-stone-400 line-through">1.650.000đ</td>
                                    <td class="py-2 px-3 font-extrabold text-[#a81817]">1.399.000đ</td>
                                    <td class="py-2 px-3">10 - 12 người</td>
                                </tr>
                                <tr>
                                    <td class="py-2 px-3 font-semibold">Heo Quay Nguyên Con 4 - 4,8kg</td>
                                    <td class="py-2 px-3 text-stone-400 line-through">1.850.000đ</td>
                                    <td class="py-2 px-3 font-extrabold text-[#a81817]">1.599.000đ</td>
                                    <td class="py-2 px-3">12 - 15 người</td>
                                </tr>
                                <tr>
                                    <td class="py-2 px-3 font-semibold">Heo Quay Nguyên Con 5 - 5,8kg</td>
                                    <td class="py-2 px-3 text-stone-400 line-through">1.990.000đ</td>
                                    <td class="py-2 px-3 font-extrabold text-[#a81817]">1.699.000đ</td>
                                    <td class="py-2 px-3">15 - 20 người</td>
                                </tr>
                                <tr>
                                    <td class="py-2 px-3 font-semibold">Heo Quay Nguyên Con 6 - 6,8kg</td>
                                    <td class="py-2 px-3 text-stone-400 line-through">2.150.000đ</td>
                                    <td class="py-2 px-3 font-extrabold text-[#a81817]">1.850.000đ</td>
                                    <td class="py-2 px-3">25 - 35 người</td>
                                </tr>
                                <tr>
                                    <td class="py-2 px-3 font-semibold">Heo Quay Nguyên Con 7 - 7,8kg</td>
                                    <td class="py-2 px-3 text-stone-400 line-through">2.350.000đ</td>
                                    <td class="py-2 px-3 font-extrabold text-[#a81817]">1.999.000đ</td>
                                    <td class="py-2 px-3">35 - 45 người</td>
                                </tr>
                                <tr>
                                    <td class="py-2 px-3 font-semibold">Heo Quay Lớn 8kg - 22kg</td>
                                    <td class="py-2 px-3 text-stone-400 line-through">280.000đ/kg</td>
                                    <td class="py-2 px-3 font-extrabold text-[#a81817]">220.000đ - 240.000đ/kg</td>
                                    <td class="py-2 px-3">Đặt theo yêu cầu</td>
                                </tr>
                            </tbody>
                        </table>
                    </div>
                </div>

                <!-- Cột Cam Kết Chất Lượng -->
                <div class="lg:col-span-5 bg-[#fdfaf6] rounded-xl p-4 md:p-5 border border-stone-200">
                    <h2 class="text-base md:text-lg font-extrabold text-[#a81817] uppercase mb-3">
                        VÌ SAO KHÁCH HÀNG TIN CHỌN LÒ HEO QUAY ĐÀ NẴNG?
                    </h2>
                    <p class="text-xs md:text-sm text-stone-700 leading-relaxed mb-3">
                        <strong>Lò Heo Quay Đà Nẵng (loheoquaydanang.com)</strong> tại địa chỉ <strong>H97/40/27k138 Hoàng Văn Thái, Phường Hòa Khánh, TP. Đà Nẵng</strong> tự hào gìn giữ bí quyết quay heo gia truyền kết hợp lò quay hiện đại khép kín:
                    </p>
                    <ul class="space-y-2.5 text-xs md:text-sm text-stone-700">
                        <li class="flex items-start gap-2">
                            <i class="fa-solid fa-circle-check text-[#a81817] mt-1 shrink-0"></i>
                            <span><strong>Da Giòn Bì Cốm:</strong> Lớp da nổ đều giòn rụm, màu vàng mật tự nhiên, thịt bên trong mềm ngọt thấm vị thảo mộc.</span>
                        </li>
                        <li class="flex items-start gap-2">
                            <i class="fa-solid fa-circle-check text-[#a81817] mt-1 shrink-0"></i>
                            <span><strong>Cam Kết "3 KHÔNG":</strong> Không phẩm màu độc hại - Không chất bảo quản - Không quay lại hàng cũ. Heo tươi sạch có dấu kiểm dịch 100%.</span>
                        </li>
                        <li class="flex items-start gap-2">
                            <i class="fa-solid fa-circle-check text-[#a81817] mt-1 shrink-0"></i>
                            <span><strong>Quà Tặng Kèm Đầy Đủ:</strong> Tặng kèm Nước chấm gia truyền, Dưa chua, Rau sống, trang trí nơ đỏ và hộp giữ nhiệt sang trọng.</span>
                        </li>
                        <li class="flex items-start gap-2">
                            <i class="fa-solid fa-circle-check text-[#a81817] mt-1 shrink-0"></i>
                            <span><strong>Giao Nóng Đúng Giờ Hoàng Đạo:</strong> Miễn phí giao hàng tận nơi tại Hòa Khánh, Liên Chiểu, Hải Châu, Thanh Khê, Cẩm Lệ, Sơn Trà, Ngũ Hành Sơn.</span>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         FLATSOME SECTION 7: FORM YÊU CẦU TƯ VẤN VÀ BÁO GIÁ TRANG CHỦ
    ====================================================================== -->
    <section id="bao-gia-nhanh" class="py-7">
        <div class="flatsome-container">
            <div class="bg-gradient-to-r from-[#7f1010] via-[#991515] to-[#7f1010] rounded-2xl p-4 md:p-7 text-white shadow-md border border-amber-500/40">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
                    <div class="lg:col-span-5">
                        <span class="text-amber-300 text-xs font-bold uppercase tracking-wider">HỖ TRỢ TƯ VẤN & ĐẶT LỊCH 24/7</span>
                        <h2 class="text-xl md:text-2xl font-extrabold mt-1 mb-2">
                            FORM YÊU CẦU & NHẬN BÁO GIÁ NHANH
                        </h2>
                        <p class="text-amber-100 text-xs md:text-sm leading-relaxed mb-4">
                            Quý khách cần đặt heo quay cúng lễ, hỏi cưới hoặc báo giá sỉ cho nhà hàng, sự kiện tại Đà Nẵng? Hãy để lại thông tin, lò quay sẽ gọi lại tư vấn ngay trong 3 phút!
                        </p>
                        <div class="space-y-2 text-xs md:text-sm bg-black/20 p-3.5 rounded-xl border border-white/15">
                            <p><i class="fa-solid fa-phone text-amber-400 mr-2"></i><strong>Hotline / Zalo:</strong> 0978.922.722</p>
                            <p><i class="fa-solid fa-location-dot text-amber-400 mr-2"></i><strong>Địa chỉ lò quay:</strong> H97/40/27k138 Hoàng Văn Thái, Phường Hòa Khánh, TP. Đà Nẵng</p>
                            <p><i class="fa-solid fa-globe text-amber-400 mr-2"></i><strong>Website:</strong> loheoquaydanang.com</p>
                        </div>
                    </div>

                    <div class="lg:col-span-7 bg-white text-stone-800 rounded-xl p-4 md:p-6 shadow">
                        <form id="quote-request-form" onsubmit="handleQuoteSubmit(event)" class="space-y-3">
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                                <div>
                                    <label class="block text-xs font-bold text-stone-700 mb-1">Họ và tên quý khách (*)</label>
                                    <input type="text" id="quote-name" required placeholder="Nhập họ và tên..." class="w-full px-3 py-2 rounded-lg border border-stone-300 text-xs md:text-sm focus:outline-none focus:border-[#a81817]">
                                </div>
                                <div>
                                    <label class="block text-xs font-bold text-stone-700 mb-1">Số điện thoại / Zalo (*)</label>
                                    <input type="tel" id="quote-phone" required placeholder="Ví dụ: 0978922722" class="w-full px-3 py-2 rounded-lg border border-stone-300 text-xs md:text-sm focus:outline-none focus:border-[#a81817]">
                                </div>
                            </div>

                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                                <div>
                                    <label class="block text-xs font-bold text-stone-700 mb-1">Chọn sản phẩm / Mâm cúng (*)</label>
                                    <select id="quote-product" class="w-full px-3 py-2 rounded-lg border border-stone-300 text-xs md:text-sm focus:outline-none focus:border-[#a81817]">
                                        <option value="Heo Sữa Quay 1,5 - 1,8kg (799.000đ)">Heo Sữa Quay 1,5 - 1,8kg (799.000đ)</option>
                                        <option value="Heo Sữa Quay 1,9 - 2,5kg (1.099.000đ)">Heo Sữa Quay 1,9 - 2,5kg (1.099.000đ)</option>
                                        <option value="Heo Sữa Quay 2,6 - 2,9kg (1.299.000đ)">Heo Sữa Quay 2,6 - 2,9kg (1.299.000đ)</option>
                                        <option value="Heo Sữa Quay 3 - 3,8kg (1.399.000đ)">Heo Sữa Quay 3 - 3,8kg (1.399.000đ)</option>
                                        <option value="Heo Quay Nguyên Con 4 - 4,8kg (1.599.000đ)">Heo Quay Nguyên Con 4 - 4,8kg (1.599.000đ)</option>
                                        <option value="Heo Quay Nguyên Con 5 - 5,8kg (1.699.000đ)">Heo Quay Nguyên Con 5 - 5,8kg (1.699.000đ)</option>
                                        <option value="Heo Quay Nguyên Con 6 - 6,8kg (1.850.000đ)">Heo Quay Nguyên Con 6 - 6,8kg (1.850.000đ)</option>
                                        <option value="Heo Quay Nguyên Con 7 - 7,8kg (1.999.000đ)">Heo Quay Nguyên Con 7 - 7,8kg (1.999.000đ)</option>
                                        <option value="Heo Quay Nguyên Con Lớn 8kg - 22kg (230.000đ/kg)">Heo Quay Nguyên Con Lớn 8kg - 22kg (230.000đ/kg)</option>
                                        <option value="Mâm Cúng Đầy Tháng / Thôi Nôi Trọn Gói (1.790.000đ)">Mâm Cúng Đầy Tháng / Thôi Nôi Trọn Gói</option>
                                        <option value="Mâm Cúng Khai Trương Trọn Gói (1.980.000đ)">Mâm Cúng Khai Trương Trọn Gói</option>
                                        <option value="Mâm Cúng Động Thổ / Nhập Trạch (1.950.000đ)">Mâm Cúng Động Thổ / Nhập Trạch</option>
                                        <option value="Mâm Cúng Thần Tài / Đất Đai / Tất Niên (1.650.000đ)">Mâm Cúng Thần Tài / Đất Đai / Tất Niên</option>
                                    </select>
                                </div>
                                <div>
                                    <label class="block text-xs font-bold text-stone-700 mb-1">Ngày & Giờ nhận hàng</label>
                                    <input type="text" id="quote-time" placeholder="Ví dụ: 7h30 sáng mai..." class="w-full px-3 py-2 rounded-lg border border-stone-300 text-xs md:text-sm focus:outline-none focus:border-[#a81817]">
                                </div>
                            </div>

                            <div>
                                <label class="block text-xs font-bold text-stone-700 mb-1">Địa chỉ giao hàng tại Đà Nẵng & Ghi chú yêu cầu</label>
                                <textarea id="quote-note" rows="2" placeholder="Nhập địa chỉ nhận hàng hoặc yêu cầu riêng (ví dụ: chặt sẵn hay để nguyên con cúng lễ...)" class="w-full px-3 py-2 rounded-lg border border-stone-300 text-xs md:text-sm focus:outline-none focus:border-[#a81817]"></textarea>
                            </div>

                            <div class="flex flex-wrap items-center gap-3 pt-1">
                                <button type="submit" class="px-5 py-2.5 rounded-lg bg-[#a81817] hover:bg-[#7f1010] text-white font-extrabold text-xs md:text-sm uppercase transition">
                                    Gửi Yêu Cầu Báo Giá
                                </button>
                                <a href="https://zalo.me/0978922722" target="_blank" rel="noopener noreferrer" class="px-4 py-2.5 rounded-lg bg-blue-600 hover:bg-blue-700 text-white font-bold text-xs md:text-sm transition">
                                    Nhắn Zalo: 0978.922.722
                                </a>
                            </div>

                            <!-- Hộp thông báo kết quả gửi form (thay cho alert) -->
                            <div id="quote-success-box" class="hidden mt-3 p-3 rounded-lg bg-green-50 border border-green-300 text-green-800 text-xs font-medium"></div>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         FLATSOME SECTION 8: DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (CẨM NANG & VĂN KHẤN)
    ====================================================================== -->
    <section id="cam-nang-tin-tuc" class="py-7 bg-white border-t border-stone-200">
        <div class="flatsome-container">
            <div class="flatsome-section-title">
                <span class="text-sm md:text-lg">CẨM NANG HEO QUAY & VĂN KHẤN NGHI LỄ</span>
            </div>

            <!-- Bộ lọc danh mục bài viết trang chủ -->
            <div class="flex flex-wrap items-center justify-center gap-2 mb-5">
                <button type="button" onclick="filterPosts('all')" class="post-cat-btn active px-3 py-1.5 rounded-full text-xs font-bold bg-[#a81817] text-white transition" data-cat="all">
                    Tất cả bài viết
                </button>
                <button type="button" onclick="filterPosts('van-khan')" class="post-cat-btn px-3 py-1.5 rounded-full text-xs font-bold bg-stone-100 text-stone-700 hover:bg-stone-200 transition" data-cat="van-khan">
                    Văn Khấn & Nghi Lễ
                </button>
                <button type="button" onclick="filterPosts('kien-thuc')" class="post-cat-btn px-3 py-1.5 rounded-full text-xs font-bold bg-stone-100 text-stone-700 hover:bg-stone-200 transition" data-cat="kien-thuc">
                    Kiến Thức Heo Quay
                </button>
                <button type="button" onclick="filterPosts('kinh-nghiem')" class="post-cat-btn px-3 py-1.5 rounded-full text-xs font-bold bg-stone-100 text-stone-700 hover:bg-stone-200 transition" data-cat="kinh-nghiem">
                    Kinh Nghiệm Đặt Đồ Cúng
                </button>
            </div>

            <!-- Danh sách bài viết (2 cột trên điện thoại, 4 cột trên máy tính) -->
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 md:gap-5">
                <article class="post-card bg-[#fdfaf6] rounded-xl border border-stone-200 overflow-hidden flex flex-col justify-between" data-category="van-khan">
                    <div>
                        <div class="aspect-[16/10] w-full overflow-hidden bg-stone-200">
                            <img src="https://lh3.googleusercontent.com/d/1q8o_1zVAuxiQsxYHH5dALvDny2dPtWaU" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1q8o_1zVAuxiQsxYHH5dALvDny2dPtWaU&sz=w600';" alt="Bài Văn Khấn Cúng Khai Trương" class="w-full h-full object-cover">
                        </div>
                        <div class="p-3">
                            <span class="text-[10px] font-bold uppercase text-[#a81817]">Văn Khấn & Nghi Lễ</span>
                            <h3 class="text-xs sm:text-sm font-bold text-stone-800 mt-1 leading-snug break-words">
                                Bài Văn Khấn Cúng Khai Trương Cửa Hàng, Công Ty Chuẩn Phong Tục
                            </h3>
                            <p class="text-[11px] text-stone-600 mt-1.5 leading-normal">
                                Hướng dẫn sắm lễ vật heo quay, mâm cúng khai trương và bài văn khấn rước tài lộc, buôn may bán đắt.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3">
                        <a href="#bao-gia-nhanh" class="text-[11px] font-bold text-[#a81817] hover:underline">Tư vấn sắm lễ ››</a>
                    </div>
                </article>

                <article class="post-card bg-[#fdfaf6] rounded-xl border border-stone-200 overflow-hidden flex flex-col justify-between" data-category="kien-thuc">
                    <div>
                        <div class="aspect-[16/10] w-full overflow-hidden bg-stone-200">
                            <img src="https://lh3.googleusercontent.com/d/1CO6KyqnCsKVMSWDRrHThikfcCOaaQmpn" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1CO6KyqnCsKVMSWDRrHThikfcCOaaQmpn&sz=w600';" alt="Cách Chọn Heo Sữa Quay" class="w-full h-full object-cover">
                        </div>
                        <div class="p-3">
                            <span class="text-[10px] font-bold uppercase text-[#a81817]">Kiến Thức Heo Quay</span>
                            <h3 class="text-xs sm:text-sm font-bold text-stone-800 mt-1 leading-snug break-words">
                                Kinh Nghiệm Chọn Size Heo Sữa Quay Phù Hợp Cho Mâm Cúng Đầy Tháng, Thôi Nôi
                            </h3>
                            <p class="text-[11px] text-stone-600 mt-1.5 leading-normal">
                                Cách chọn trọng lượng heo sữa quay từ 1.5kg đến 3.8kg vừa đẹp mâm cúng vừa đủ khẩu phần đãi tiệc gia đình.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3">
                        <a href="#heo-sua-quay" class="text-[11px] font-bold text-[#a81817] hover:underline">Xem các size heo ››</a>
                    </div>
                </article>

                <article class="post-card bg-[#fdfaf6] rounded-xl border border-stone-200 overflow-hidden flex flex-col justify-between" data-category="van-khan">
                    <div>
                        <div class="aspect-[16/10] w-full overflow-hidden bg-stone-200">
                            <img src="https://lh3.googleusercontent.com/d/1vxvqh8dgfD0fmhUPOfy2WanUoELHD59N" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1vxvqh8dgfD0fmhUPOfy2WanUoELHD59N&sz=w600';" alt="Văn Khấn Cúng Đất Đai Thần Tài" class="w-full h-full object-cover">
                        </div>
                        <div class="p-3">
                            <span class="text-[10px] font-bold uppercase text-[#a81817]">Văn Khấn & Nghi Lễ</span>
                            <h3 class="text-xs sm:text-sm font-bold text-stone-800 mt-1 leading-snug break-words">
                                Văn Khấn Cúng Thần Tài Thổ Địa & Cúng Đất Đai Cầu Bình An Tài Lộc
                            </h3>
                            <p class="text-[11px] text-stone-600 mt-1.5 leading-normal">
                                Cách bày bộ Tam Sên, heo quay nguyên con và nghi thức cúng Thần Tài, Tạ Đất chuẩn truyền thống Việt Nam.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3">
                        <a href="#mam-cung-tron-goi" class="text-[11px] font-bold text-[#a81817] hover:underline">Xem mâm cúng ››</a>
                    </div>
                </article>

                <article class="post-card bg-[#fdfaf6] rounded-xl border border-stone-200 overflow-hidden flex flex-col justify-between" data-category="kinh-nghiem">
                    <div>
                        <div class="aspect-[16/10] w-full overflow-hidden bg-stone-200">
                            <img src="https://lh3.googleusercontent.com/d/17wT6uMKy3-4cyZJWGff8jZG5MoT-Q8k-" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=17wT6uMKy3-4cyZJWGff8jZG5MoT-Q8k-&sz=w600';" alt="Cách Giữ Da Heo Quay Giòn Lâu" class="w-full h-full object-cover">
                        </div>
                        <div class="p-3">
                            <span class="text-[10px] font-bold uppercase text-[#a81817]">Kinh Nghiệm Đặt Đồ Cúng</span>
                            <h3 class="text-xs sm:text-sm font-bold text-stone-800 mt-1 leading-snug break-words">
                                Bí Quyết Giữ Da Heo Quay Giòn Rụm Từ Lúc Cúng Lễ Đến Khi Hạ Mâm Thưởng Thức
                            </h3>
                            <p class="text-[11px] text-stone-600 mt-1.5 leading-normal">
                                Hướng dẫn cách bảo quản heo quay trên bàn lễ để lớp da cốm luôn nổ giòn tan và thịt giữ trọn vị ngọt.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3">
                        <a href="#heo-quay-nguyen-con" class="text-[11px] font-bold text-[#a81817] hover:underline">Xem heo nguyên con ››</a>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         FLATSOME SECTION 9: FANPAGE FACEBOOK & BẢN ĐỒ GOOGLE MAPS NGOÀI TRANG CHỦ
         - Đưa Fanpage https://www.facebook.com/trungthong.1207?locale=vi_VN ra ngoài trang chủ
         - Đưa ảnh & bản đồ Google Map địa chỉ H97/40/27k138 Hoàng Văn Thái, Phường Hòa Khánh, Tp. Đà Nẵng ra ngoài trang chủ
    ====================================================================== -->
    <section id="lien-he-ban-do" class="py-7">
        <div class="flatsome-container">
            <div class="flatsome-section-title">
                <span class="text-sm md:text-lg">KẾT NỐI FANPAGE & BẢN ĐỒ ĐƯỜNG ĐI ĐẾN LÒ QUAY</span>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">

                <!-- Cột 1: Đưa Fanpage ra ngoài trang chủ -->
                <div class="lg:col-span-5 bg-white rounded-xl border border-stone-200 p-4 shadow-sm flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between mb-3 pb-2 border-b border-stone-100">
                            <h3 class="text-sm md:text-base font-extrabold text-[#a81817] uppercase flex items-center gap-2">
                                <i class="fa-brands fa-facebook text-blue-600 text-lg"></i>
                                <span>FANPAGE LÒ HEO QUAY ĐÀ NẴNG</span>
                            </h3>
                            <a href="https://www.facebook.com/trungthong.1207?locale=vi_VN" target="_blank" rel="noopener noreferrer" class="text-xs font-bold text-blue-600 hover:underline">
                                Mở Facebook ›
                            </a>
                        </div>

                        <!-- Khung hiển thị trực quan Fanpage + Nhúng Plugin Facebook -->
                        <div class="rounded-xl overflow-hidden border border-stone-200 bg-stone-50 mb-3">
                            <div class="relative h-32 w-full bg-gradient-to-r from-[#7f1010] to-[#b91c1c] overflow-hidden">
                                <img src="https://lh3.googleusercontent.com/d/1S87FEtO5wTLsM19spNcyOX-PFX8tYudL" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1S87FEtO5wTLsM19spNcyOX-PFX8tYudL&sz=w800';" alt="Ảnh bìa Fanpage Lò Heo Quay Đà Nẵng" class="w-full h-full object-cover opacity-55">
                                <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/30 to-transparent flex items-end p-3">
                                    <div class="flex items-center gap-3">
                                        <img src="https://lh3.googleusercontent.com/d/1pi7Dt3XNoMJy10ObYE21VlhcXKEyhOTq" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1pi7Dt3XNoMJy10ObYE21VlhcXKEyhOTq&sz=w300';" alt="Logo Fanpage" class="w-12 h-12 rounded-full border-2 border-white bg-white object-contain shrink-0">
                                        <div class="text-white">
                                            <a href="https://www.facebook.com/trungthong.1207?locale=vi_VN" target="_blank" rel="noopener noreferrer" class="font-extrabold text-sm hover:underline block">
                                                Lò Heo Quay Đà Nẵng - Trung Thông
                                            </a>
                                            <span class="text-[11px] text-amber-300 block">facebook.com/trungthong.1207</span>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="p-3 text-xs text-stone-700 space-y-2">
                                <p>
                                    Cập nhật hình ảnh heo sữa quay, heo quay nguyên con ra lò nóng hổi mỗi ngày tại Fanpage chính thức.
                                </p>
                                <div class="grid grid-cols-3 gap-1.5 pt-1">
                                    <img src="https://lh3.googleusercontent.com/d/1CO6KyqnCsKVMSWDRrHThikfcCOaaQmpn" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1CO6KyqnCsKVMSWDRrHThikfcCOaaQmpn&sz=w300';" alt="Ảnh thực tế 1" class="h-16 w-full object-cover rounded">
                                    <img src="https://lh3.googleusercontent.com/d/1Hv4O_TGrZ_8mARxibtRyr6PqMGZl5Ebp" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1Hv4O_TGrZ_8mARxibtRyr6PqMGZl5Ebp&sz=w300';" alt="Ảnh thực tế 2" class="h-16 w-full object-cover rounded">
                                    <img src="https://lh3.googleusercontent.com/d/1SvqKDslODY2Nqu58jEYkHlplnXkLk71l" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1SvqKDslODY2Nqu58jEYkHlplnXkLk71l&sz=w300';" alt="Ảnh thực tế 3" class="h-16 w-full object-cover rounded">
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="flex flex-wrap items-center gap-2">
                        <a href="https://www.facebook.com/trungthong.1207?locale=vi_VN" target="_blank" rel="noopener noreferrer" class="flex-1 text-center py-2.5 px-3 rounded-lg bg-[#1877F2] hover:bg-blue-700 text-white font-bold text-xs transition">
                            <i class="fa-brands fa-facebook-f mr-1.5"></i>Theo Dõi & Nhắn Tin Fanpage
                        </a>
                        <a href="https://zalo.me/0978922722" target="_blank" rel="noopener noreferrer" class="py-2.5 px-3 rounded-lg bg-stone-100 hover:bg-stone-200 text-stone-800 font-bold text-xs transition">
                            Zalo: 0978.922.722
                        </a>
                    </div>
                </div>

                <!-- Cột 2: Đưa Bản Đồ Google Map ra ngoài trang chủ -->
                <div class="lg:col-span-7 bg-white rounded-xl border border-stone-200 p-4 shadow-sm flex flex-col justify-between">
                    <div>
                        <div class="flex flex-wrap items-center justify-between gap-2 mb-3 pb-2 border-b border-stone-100">
                            <div>
                                <h3 class="text-sm md:text-base font-extrabold text-[#a81817] uppercase flex items-center gap-2">
                                    <i class="fa-solid fa-map-location-dot text-[#a81817] text-lg"></i>
                                    <span>BẢN ĐỒ GOOGLE MAPS LÒ HEO QUAY ĐÀ NẴNG</span>
                                </h3>
                                <p class="text-xs text-stone-600 mt-0.5">
                                    Địa chỉ: <strong>H97/40/27k138 Hoàng Văn Thái, Phường Hòa Khánh, Tp. Đà Nẵng</strong>
                                </p>
                            </div>
                            <a href="https://www.google.com/maps/search/?api=1&query=138+Ho%C3%A0ng+V%C4%83n+Th%C3%A1i,+H%C3%B2a+Kh%C3%A1nh,+%C4%90%C3%A0+N%E1%BA%B5ng" target="_blank" rel="noopener noreferrer" class="px-3 py-1.5 rounded-lg bg-red-50 text-[#a81817] border border-red-200 font-bold text-xs hover:bg-red-100 transition">
                                <i class="fa-solid fa-diamond-turn-right mr-1"></i>Chỉ Đường Google Maps
                            </a>
                        </div>

                        <!-- Khung Bản Đồ Google Maps trực tiếp ngoài trang chủ -->
                        <div class="w-full h-[270px] md:h-[300px] rounded-xl overflow-hidden border border-stone-200 bg-stone-100">
                            <iframe 
                                title="Bản đồ Lò Heo Quay Đà Nẵng - H97/40/27k138 Hoàng Văn Thái, Phường Hòa Khánh, Tp. Đà Nẵng"
                                src="https://maps.google.com/maps?q=138%20Ho%C3%A0ng%20V%C4%83n%20Th%C3%A1i,%20H%C3%B2a%20Kh%C3%A1nh,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed" 
                                width="100%" 
                                height="100%" 
                                style="border:0;" 
                                allowfullscreen="" 
                                loading="lazy" 
                                referrerpolicy="no-referrer-when-downgrade">
                            </iframe>
                        </div>
                    </div>

                    <div class="mt-3 pt-2 border-t border-stone-100 flex flex-wrap items-center justify-between gap-2 text-xs text-stone-700">
                        <span><i class="fa-solid fa-location-crosshairs text-[#a81817] mr-1"></i>H97/40/27k138 Hoàng Văn Thái, Phường Hòa Khánh, Tp. Đà Nẵng</span>
                        <span class="font-bold text-[#a81817]"><i class="fa-solid fa-phone mr-1"></i>Hotline: 0978.922.722</span>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- =====================================================================
         FLATSOME FOOTER (Chân trang chuẩn mẫu heoquaydanang.net)
    ====================================================================== -->
    <footer class="bg-[#3b0707] text-stone-200 pt-8 pb-20 md:pb-8 border-t-4 border-amber-500">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6 pb-6 border-b border-white/10">
                <!-- Cột 1: Thông tin liên hệ -->
                <div>
                    <div class="flex items-center gap-2.5 mb-3">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1pi7Dt3XNoMJy10ObYE21VlhcXKEyhOTq" 
                            onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1pi7Dt3XNoMJy10ObYE21VlhcXKEyhOTq&sz=w300';"
                            alt="Logo Lò Heo Quay Đà Nẵng" 
                            class="w-10 h-10 rounded-full bg-white p-0.5 object-contain shrink-0"
                        >
                        <div>
                            <h3 class="text-sm font-extrabold text-amber-400 uppercase">LÒ HEO QUAY ĐÀ NẴNG</h3>
                            <p class="text-[11px] text-stone-300">loheoquaydanang.com</p>
                        </div>
                    </div>
                    <ul class="space-y-2 text-xs text-stone-300 leading-relaxed">
                        <li><strong class="text-white">Địa chỉ:</strong> H97/40/27k138 Hoàng Văn Thái, Phường Hòa Khánh, Tp. Đà Nẵng</li>
                        <li><strong class="text-white">Hotline / Zalo:</strong> <a href="tel:0978922722" class="text-amber-300 font-bold">0978.922.722</a></li>
                        <li><strong class="text-white">Fanpage:</strong> <a href="https://www.facebook.com/trungthong.1207?locale=vi_VN" target="_blank" rel="noopener noreferrer" class="text-amber-300 hover:underline">facebook.com/trungthong.1207</a></li>
                        <li><strong class="text-white">Giờ làm việc:</strong> 05:00 Sáng - 21:00 Tối (Thứ 2 - Chủ Nhật)</li>
                    </ul>
                </div>

                <!-- Cột 2: Danh mục sản phẩm -->
                <div>
                    <h4 class="text-sm font-extrabold text-amber-400 uppercase mb-3">DANH MỤC SẢN PHẨM</h4>
                    <ul class="space-y-2 text-xs text-stone-300">
                        <li><a href="#heo-sua-quay" class="hover:text-amber-300">› Heo Sữa Quay Đà Nẵng (1.5kg - 3.8kg)</a></li>
                        <li><a href="#heo-quay-nguyen-con" class="hover:text-amber-300">› Heo Quay Nguyên Con (4kg - 7.8kg)</a></li>
                        <li><a href="#heo-quay-nguyen-con" class="hover:text-amber-300">› Heo Quay Size Khủng (8kg - 22kg)</a></li>
                        <li><a href="#mam-cung-tron-goi" class="hover:text-amber-300">› Mâm Cúng Đầy Tháng / Thôi Nôi</a></li>
                        <li><a href="#mam-cung-tron-goi" class="hover:text-amber-300">› Mâm Cúng Khai Trương / Động Thổ</a></li>
                        <li><a href="#mam-cung-tron-goi" class="hover:text-amber-300">› Mâm Cúng Thần Tài / Nhập Trạch</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Chính sách bán hàng -->
                <div>
                    <h4 class="text-sm font-extrabold text-amber-400 uppercase mb-3">CHÍNH SÁCH & CAM KẾT</h4>
                    <ul class="space-y-2 text-xs text-stone-300">
                        <li>› Cam kết heo tươi sạch có kiểm dịch 100%</li>
                        <li>› Giao hàng miễn phí nội thành Đà Nẵng</li>
                        <li>› Giao nóng tận nơi đúng giờ Hoàng Đạo</li>
                        <li>› Kiểm tra hàng thoải mái trước khi thanh toán</li>
                        <li>› Tặng kèm nước chấm gia truyền, rau dưa đầy đủ</li>
                    </ul>
                </div>

                <!-- Cột 4: Đặt lịch nhanh -->
                <div>
                    <h4 class="text-sm font-extrabold text-amber-400 uppercase mb-3">ĐẶT HEO QUAY GIAO NGAY</h4>
                    <p class="text-xs text-stone-300 leading-relaxed mb-3">
                        Quý khách vui lòng liên hệ trước 2 - 3 tiếng để lò quay chuẩn bị heo mới ra lò nóng giòn nhất phục vụ lễ cúng.
                    </p>
                    <div class="flex flex-col gap-2">
                        <a href="tel:0978922722" class="py-2 px-3 rounded-lg bg-amber-400 text-[#4d0909] font-extrabold text-xs text-center uppercase">
                            <i class="fa-solid fa-phone-volume mr-1.5"></i>Gọi: 0978.922.722
                        </a>
                        <a href="https://www.facebook.com/trungthong.1207?locale=vi_VN" target="_blank" rel="noopener noreferrer" class="py-2 px-3 rounded-lg bg-[#1877F2] text-white font-bold text-xs text-center">
                            <i class="fa-brands fa-facebook mr-1.5"></i>Nhắn Tin Qua Fanpage
                        </a>
                    </div>
                </div>
            </div>

            <div class="pt-4 text-center text-xs text-stone-400">
                © Bản quyền thuộc về <strong class="text-amber-300">Lò Heo Quay Đà Nẵng - loheoquaydanang.com</strong> | Đ/C: H97/40/27k138 Hoàng Văn Thái, Phường Hòa Khánh, Tp. Đà Nẵng
            </div>
        </div>
    </footer>

    <!-- =====================================================================
         CỤM NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
         - Tương thích hoàn hảo trên máy tính và điện thoại, không tràn viền
    ====================================================================== -->
    <div class="fixed right-3 bottom-4 z-50 flex flex-col items-end gap-2.5">
        <!-- Nút Facebook Fanpage -->
        <a href="https://www.facebook.com/trungthong.1207?locale=vi_VN" target="_blank" rel="noopener noreferrer" aria-label="Chat Facebook Fanpage" class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white px-3 py-2 rounded-full shadow-lg transition">
            <i class="fa-brands fa-facebook-f text-sm w-4 text-center"></i>
            <span class="text-xs font-bold">Facebook</span>
        </a>

        <!-- Nút Chat Zalo -->
        <a href="https://zalo.me/0978922722" target="_blank" rel="noopener noreferrer" aria-label="Chat Zalo 0978.922.722" class="flex items-center gap-2 bg-[#0068FF] hover:bg-blue-600 text-white px-3 py-2 rounded-full shadow-lg transition">
            <span class="text-xs font-extrabold bg-white text-[#0068FF] px-1.5 py-0.5 rounded-full leading-none">Zalo</span>
            <span class="text-xs font-bold">0978.922.722</span>
        </a>

        <!-- Nút Gọi Hotline Nổi Bật -->
        <a href="tel:0978922722" aria-label="Gọi Hotline 0978.922.722" class="floating-pulse flex items-center gap-2 bg-[#b91c1c] hover:bg-[#7f1010] text-white px-3.5 py-2.5 rounded-full shadow-xl border border-amber-300 transition">
            <i class="fa-solid fa-phone-volume text-amber-300 text-sm"></i>
            <span class="text-xs md:text-sm font-extrabold">0978.922.722</span>
        </a>
    </div>

    <!-- =====================================================================
         JAVASCRIPT XỬ LÝ SLIDER BANNER, MENU ĐIỆN THOẠI, LỌC BÀI VIẾT & BÁO GIÁ
    ====================================================================== -->
    <script>
        // 1. Điều khiển Menu trên điện thoại
        const mobileMenuBtn = document.getElementById('mobile-menu-btn');
        const mobileMenuDrawer = document.getElementById('mobile-menu-drawer');
        if (mobileMenuBtn && mobileMenuDrawer) {
            mobileMenuBtn.addEventListener('click', function () {
                mobileMenuDrawer.classList.toggle('hidden');
            });
            // Tự đóng menu khi chọn mục
            mobileMenuDrawer.querySelectorAll('a').forEach(function (link) {
                link.addEventListener('click', function () {
                    mobileMenuDrawer.classList.add('hidden');
                });
            });
        }

        // 2. Điều khiển 2 Ảnh Banner Tự Trượt (Auto Slider)
        let currentBannerIndex = 0;
        const bannerSlides = document.querySelectorAll('.banner-slide');
        const dot0 = document.getElementById('slider-dot-0');
        const dot1 = document.getElementById('slider-dot-1');

        function renderBannerSlide(index) {
            bannerSlides.forEach(function (slide, i) {
                if (i === index) {
                    slide.classList.remove('hidden', 'opacity-0');
                    slide.classList.add('block', 'opacity-100');
                } else {
                    slide.classList.remove('block', 'opacity-100');
                    slide.classList.add('hidden', 'opacity-0');
                }
            });
            if (dot0 && dot1) {
                dot0.className = index === 0 ? 'w-2.5 h-2.5 rounded-full bg-amber-400 transition' : 'w-2.5 h-2.5 rounded-full bg-white/50 transition';
                dot1.className = index === 1 ? 'w-2.5 h-2.5 rounded-full bg-amber-400 transition' : 'w-2.5 h-2.5 rounded-full bg-white/50 transition';
            }
        }

        function changeBannerSlide(step) {
            currentBannerIndex = (currentBannerIndex + step + bannerSlides.length) % bannerSlides.length;
            renderBannerSlide(currentBannerIndex);
        }

        function goToBannerSlide(index) {
            currentBannerIndex = index;
            renderBannerSlide(currentBannerIndex);
        }

        // Tự động trượt mỗi 4.5 giây
        window.onload = function () {
            setInterval(function () {
                changeBannerSlide(1);
            }, 4500);
        };

        // 3. Chọn sản phẩm và cuộn xuống Form Báo Giá
        function selectProductForQuote(productName) {
            const productSelect = document.getElementById('quote-product');
            const quoteSection = document.getElementById('bao-gia-nhanh');
            if (productSelect) {
                for (let i = 0; i < productSelect.options.length; i++) {
                    if (productSelect.options[i].value === productName) {
                        productSelect.selectedIndex = i;
                        break;
                    }
                }
            }
            if (quoteSection) {
                quoteSection.scrollIntoView({ behavior: 'smooth' });
            }
        }

        // 4. Xử lý gửi Form Yêu Cầu & Báo Giá (Không dùng alert)
        function handleQuoteSubmit(event) {
            event.preventDefault();
            const name = document.getElementById('quote-name').value.trim();
            const phone = document.getElementById('quote-phone').value.trim();
            const product = document.getElementById('quote-product').value;
            const time = document.getElementById('quote-time').value.trim();
            const successBox = document.getElementById('quote-success-box');

            if (successBox) {
                successBox.classList.remove('hidden');
                successBox.innerHTML = '<strong>Đặt yêu cầu thành công!</strong> Cảm ơn <strong>' + name + '</strong> (' + phone + '). Lò Heo Quay Đà Nẵng đã ghi nhận yêu cầu <strong>' + product + '</strong>' + (time ? ' vào lúc <strong>' + time + '</strong>' : '') + ' và sẽ liên hệ lại ngay qua SĐT/Zalo 0978.922.722!';
            }
        }

        // 5. Bộ lọc danh mục bài viết ở trang chủ
        function filterPosts(category) {
            const cards = document.querySelectorAll('.post-card');
            const buttons = document.querySelectorAll('.post-cat-btn');

            buttons.forEach(function (btn) {
                if (btn.getAttribute('data-cat') === category) {
                    btn.className = 'post-cat-btn active px-3 py-1.5 rounded-full text-xs font-bold bg-[#a81817] text-white transition';
                } else {
                    btn.className = 'post-cat-btn px-3 py-1.5 rounded-full text-xs font-bold bg-stone-100 text-stone-700 hover:bg-stone-200 transition';
                }
            });

            cards.forEach(function (card) {
                if (category === 'all' || card.getAttribute('data-category') === category) {
                    card.classList.remove('hidden');
                    card.classList.add('flex');
                } else {
                    card.classList.remove('flex');
                    card.classList.add('hidden');
                }
            });
        }
    </script>
</body>
</html>
