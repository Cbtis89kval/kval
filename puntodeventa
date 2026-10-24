<!DOCTYPE html>
<html lang="en" class="dark scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KVAL // OVERSIZE ARCHIVE - Y2K ALT STREETWEAR POS & STORE</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    colors: {
                        brand: {
                            black: '#070709',
                            card: '#0f0e13',
                            border: '#272530',
                            gold: '#d4af37',
                            darkgold: '#aa8c2c',
                            acid: '#d4ff00',
                            magenta: '#9d4edd',
                            silver: '#cbd5e1',
                            charcoal: '#1a1921'
                        }
                    },
                    fontFamily: {
                        mono: ['Courier New', 'Courier', 'monospace'],
                        sans: ['Inter', 'system-ui', 'sans-serif'],
                        y2k: ['Impact', 'Trebuchet MS', 'sans-serif']
                    }
                }
            }
        }
    </script>
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@400;600;700&family=Syne:wght@700;800&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Space Grotesk', sans-serif;
            background-color: #070709;
            color: #cbd5e1;
            overflow-x: hidden;
        }

        h1, h2, h3, .brand-font {
            font-family: 'Syne', sans-serif;
            letter-spacing: -0.03em;
        }

        /* Custom Alt Scrollbar */
        ::-webkit-scrollbar {
            width: 6px;
            height: 6px;
        }
        ::-webkit-scrollbar-track {
            background: #070709;
        }
        ::-webkit-scrollbar-thumb {
            background: #d4af37;
        }

        /* Grunge & Gold Visual Effects */
        .gold-glow {
            box-shadow: 0 0 25px rgba(212, 175, 55, 0.3);
        }
        .gold-border {
            border: 1px solid #d4af37;
        }
        .grunge-noise {
            background-image: radial-gradient(rgba(212, 175, 55, 0.05) 1px, transparent 0);
            background-size: 24px 24px;
        }
        
        .scanline {
            background: linear-gradient(
                to bottom,
                rgba(255,255,255,0),
                rgba(255,255,255,0) 50%,
                rgba(0, 0, 0, 0.4) 50%,
                rgba(0, 0, 0, 0.4)
            );
            background-size: 100% 4px;
        }

        .gold-chrome-text {
            background: linear-gradient(180deg, #ffffff 0%, #d4af37 50%, #705b1c 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        /* Clickable Squishy Buttons (Aplastasbles) */
        .squishy-btn {
            transition: all 0.1s ease-in-out;
            cursor: pointer;
        }
        .squishy-btn:active {
            transform: scale(0.94) translateY(2px);
        }

        /* Scratch Card Canvas */
        #scratch-canvas {
            cursor: pointer;
            touch-action: none;
        }
    </style>
</head>
<body class="min-h-screen flex flex-col justify-between selection:bg-brand-gold selection:text-black grunge-noise">

    <!-- Top Ticker Banner -->
    <div class="bg-brand-gold text-black font-mono text-xs font-black py-1 px-4 overflow-hidden whitespace-nowrap flex justify-between items-center z-50 border-b border-black">
        <div class="animate-marquee flex gap-8">
            <span>⚡ KVAL OVERSIZE ARCHIVE // 2026 DROP LIVE</span>
            <span>✦ FOUNDER: KVAL // GRUNGE LUXURY</span>
            <span>⚡ FREE WORLDWIDE SHIPPING ON ORDERS OVER $150</span>
            <span>✦ HEAVYWEIGHT 500GSM COTTON & EXTREME BAGGY CUTS</span>
        </div>
        <div class="hidden md:flex items-center gap-3">
            <span class="bg-black text-brand-gold px-2 py-0.5 rounded text-[10px] tracking-wider uppercase">SYSTEM ACTIVE // SLAY</span>
        </div>
    </div>

    <!-- Header & Navigation -->
    <header class="sticky top-0 z-40 backdrop-blur-md bg-brand-black/90 border-b border-brand-border">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-20">
                
                <!-- Brand Logo -->
                <a href="#hero" class="flex items-center gap-3 group squishy-btn" onclick="playBeep()">
                    <div class="w-10 h-10 bg-gradient-to-br from-brand-gold to-brand-darkgold text-black flex items-center justify-center font-black text-2xl tracking-tighter group-hover:rotate-12 transition-transform shadow-lg">
                        K
                    </div>
                    <div class="flex flex-col">
                        <span class="text-2xl font-extrabold tracking-widest gold-chrome-text uppercase leading-none">KVAL</span>
                        <span class="text-[9px] font-mono tracking-widest text-brand-gold uppercase">Grunge Archive // Slay Edition</span>
                    </div>
                </a>

                <!-- Nav Links -->
                <nav class="hidden lg:flex items-center space-x-6 text-xs font-mono uppercase tracking-wider text-gray-300">
                    <a href="#shop" class="hover:text-brand-gold transition-colors squishy-btn" onclick="playBeep()">Catalog</a>
                    <a href="#outfit-lab" class="hover:text-brand-gold transition-colors squishy-btn" onclick="playBeep()">Outfit Lab</a>
                    <a href="#size-calculator" class="hover:text-brand-gold transition-colors squishy-btn" onclick="playBeep()">Fit Engine</a>
                    <a href="#scratch-section" class="hover:text-brand-gold transition-colors text-brand-gold font-bold squishy-btn" onclick="playBeep()">🎁 Scratch Game</a>
                    <a href="#about" class="hover:text-brand-gold transition-colors squishy-btn" onclick="playBeep()">About Kval</a>
                </nav>

                <!-- Action Controls & Mode Toggles -->
                <div class="flex items-center gap-3">
                    
                    <!-- POS Mode Switcher -->
                    <button id="pos-mode-btn" onclick="togglePosMode()" class="squishy-btn px-3 py-1.5 rounded bg-brand-card border border-brand-border hover:border-brand-gold text-xs font-mono flex items-center gap-2 transition-all">
                        <span class="w-2 h-2 rounded-full bg-red-500 animate-pulse" id="pos-status-dot"></span>
                        <span id="pos-btn-text">POS TERMINAL</span>
                    </button>

                    <!-- Search Trigger -->
                    <div class="relative hidden sm:block">
                        <input type="text" id="search-input" onkeyup="handleSearch()" placeholder="SEARCH ARCHIVE..." class="bg-brand-card border border-brand-border text-xs text-white rounded px-3 py-1.5 w-36 focus:w-48 focus:border-brand-gold outline-none transition-all font-mono">
                        <i class="fas fa-search absolute right-3 top-2 text-xs text-gray-500"></i>
                    </div>

                    <!-- Cart Drawer Trigger -->
                    <button onclick="toggleCartDrawer()" class="squishy-btn relative p-2 bg-brand-gold text-black font-bold rounded hover:bg-white transition-colors flex items-center justify-center shadow-md">
                        <i class="fas fa-shopping-bag"></i>
                        <span id="cart-badge" class="absolute -top-2 -right-2 bg-brand-magenta text-white text-[10px] w-5 h-5 rounded-full flex items-center justify-center font-mono">0</span>
                    </button>

                    <!-- Mobile Menu Trigger -->
                    <button onclick="toggleMobileMenu()" class="squishy-btn lg:hidden text-white p-2 text-xl">
                        <i class="fas fa-bars"></i>
                    </button>
                </div>
            </div>
        </div>

        <!-- Mobile Drawer Menu -->
        <div id="mobile-menu" class="hidden lg:hidden bg-brand-card border-b border-brand-border px-4 py-4 space-y-3 font-mono text-sm">
            <input type="text" id="mobile-search-input" onkeyup="handleSearchMobile()" placeholder="SEARCH ARCHIVE..." class="w-full bg-brand-black border border-brand-border text-xs text-white rounded p-2 mb-2 font-mono">
            <a href="#shop" onclick="toggleMobileMenu()" class="block text-gray-300 hover:text-brand-gold">CATALOG</a>
            <a href="#outfit-lab" onclick="toggleMobileMenu()" class="block text-gray-300 hover:text-brand-gold">OUTFIT MIXER LAB</a>
            <a href="#size-calculator" onclick="toggleMobileMenu()" class="block text-gray-300 hover:text-brand-gold">FIT VISUALIZER</a>
            <a href="#scratch-section" onclick="toggleMobileMenu()" class="block text-brand-gold">SCRATCH COUPON GAME</a>
            <a href="#about" onclick="toggleMobileMenu()" class="block text-gray-300 hover:text-brand-gold">ABOUT KVAL</a>
        </div>
    </header>

    <main class="flex-grow">
        
        <!-- HERO BANNER SECTION -->
        <section id="hero" class="relative py-16 md:py-24 border-b border-brand-border overflow-hidden">
            <div class="absolute inset-0 scanline opacity-20 pointer-events-none"></div>
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
                    
                    <div class="lg:col-span-7 space-y-6">
                        <div class="inline-flex items-center gap-2 px-3 py-1 bg-brand-card border border-brand-gold/40 text-brand-gold text-xs font-mono uppercase tracking-widest rounded-full shadow">
                            <span class="w-2 h-2 rounded-full bg-brand-gold animate-ping"></span>
                            ICONIC DROP // 2026 GRUNGE ARCHIVE
                        </div>
                        
                        <h1 class="text-4xl sm:text-6xl xl:text-7xl font-black uppercase tracking-tighter leading-none text-white">
                            KVAL <span class="gold-chrome-text">OVERSIZE</span> <br>
                            <span class="text-brand-gold">ARCHIVE</span>
                        </h1>

                        <p class="text-gray-400 max-w-xl text-sm sm:text-base font-mono">
                            AUTHENTIC BAGGY & OVERSIZED STREETWEAR CURATED BY <span class="text-white font-bold underline decoration-brand-gold">KVAL</span>. HEAVY COTTON WASHES, WIDE PARACHUTE LEGS, CYBER-Y2K GRUNGE VIBES.
                        </p>

                        <div class="flex flex-wrap gap-4 pt-2">
                            <a href="#shop" onclick="playBeep()" class="squishy-btn px-8 py-4 bg-brand-gold text-black font-bold text-sm tracking-wider uppercase hover:bg-white transition-all shadow-lg gold-glow flex items-center gap-3">
                                <span>EXPLORE CATALOGUE</span>
                                <i class="fas fa-arrow-right"></i>
                            </a>
                            <button onclick="togglePosMode()" class="squishy-btn px-6 py-4 bg-brand-card border border-brand-border text-white hover:border-brand-gold font-mono text-sm tracking-wider uppercase transition-all flex items-center gap-2">
                                <i class="fas fa-calculator text-brand-gold"></i>
                                <span>POS CASHIER TERMINAL</span>
                            </button>
                        </div>

                        <div class="grid grid-cols-3 gap-4 pt-6 border-t border-brand-border/60 max-w-md font-mono text-xs">
                            <div>
                                <span class="block text-lg font-bold text-white">500 GSM</span>
                                <span class="text-gray-500">Acid Hoodies</span>
                            </div>
                            <div>
                                <span class="block text-lg font-bold text-brand-gold">45 CM</span>
                                <span class="text-gray-500">Leg Opening</span>
                            </div>
                            <div>
                                <span class="block text-lg font-bold text-brand-magenta">Y2K / GRUNGE</span>
                                <span class="text-gray-500">Original Kval Cuts</span>
                            </div>
                        </div>
                    </div>

                    <!-- Right Hero Visual Collage -->
                    <div class="lg:col-span-5 relative flex justify-center">
                        <div class="relative w-full max-w-md aspect-[4/5] bg-brand-card border border-brand-border rounded-xl p-3 shadow-2xl overflow-hidden group">
                            <img id="hero-img" src="https://i.pinterest.com/originals/d6/6a/eb/d66aeb379b83f7c56e7d42fce4e43403.jpg" alt="KVAL Oversize Lookbook" class="w-full h-full object-cover rounded grayscale hover:grayscale-0 transition-all duration-700 scale-105 group-hover:scale-100" onerror="this.src='https://images.unsplash.com/photo-1556905055-8f358a7a47b2?auto=format&fit=crop&q=80&w=800'">
                            
                            <div class="absolute top-6 left-6 bg-brand-gold text-black font-mono text-xs font-black px-3 py-1 uppercase tracking-widest shadow-md">
                                KVAL CERTIFIED // ICONIC
                            </div>
                            <div class="absolute bottom-6 right-6 bg-black/90 backdrop-blur-md border border-brand-border text-white p-3 rounded text-xs font-mono">
                                <span class="text-brand-gold font-bold block">SILHOUETTE 01</span>
                                <span>GOLD GRUNGE HOODIE + ULTRA BAGGY DENIM</span>
                            </div>
                        </div>
                    </div>

                </div>
            </div>
        </section>

        <!-- POS TERMINAL MODE CONTAINER -->
        <section id="pos-terminal-section" class="hidden py-8 bg-brand-black border-b border-brand-gold">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="bg-brand-card border-2 border-brand-gold p-6 rounded-xl shadow-2xl">
                    
                    <div class="flex flex-col md:flex-row justify-between items-start md:items-center border-b border-brand-border pb-4 mb-6 gap-4">
                        <div>
                            <span class="bg-brand-gold text-black font-mono font-bold text-xs px-2 py-0.5 rounded">CASH REGISTER TERMINAL</span>
                            <h2 class="text-2xl font-bold text-white mt-1">KVAL STOREFRONT POS v2.6 // SLAY MODE</h2>
                            <p class="text-xs font-mono text-gray-400">Cashier Desk: Kval Main Studio | Store #001</p>
                        </div>
                        <div class="flex items-center gap-3">
                            <button onclick="clearPosCart()" class="squishy-btn px-3 py-1.5 bg-red-900/40 text-red-400 border border-red-800 text-xs font-mono rounded hover:bg-red-800 hover:text-white transition-colors">CLEAR TERMINAL</button>
                            <button onclick="togglePosMode()" class="squishy-btn px-3 py-1.5 bg-brand-black text-gray-300 border border-brand-border text-xs font-mono rounded hover:text-white">EXIT POS</button>
                        </div>
                    </div>

                    <div class="grid grid-cols-1 lg:grid-cols-12 gap-6">
                        <!-- Quick Catalog Item Selector -->
                        <div class="lg:col-span-7 space-y-4">
                            <h3 class="text-xs font-mono text-brand-gold uppercase tracking-wider">Quick Select Catalog Items (Click to Add)</h3>
                            <div id="pos-items-grid" class="grid grid-cols-2 sm:grid-cols-3 gap-3 max-h-96 overflow-y-auto pr-2">
                                <!-- Dynamic Item Cards inserted via JS -->
                            </div>
                        </div>

                        <!-- Current POS Order Register -->
                        <div class="lg:col-span-5 bg-brand-black border border-brand-border rounded-xl p-4 flex flex-col justify-between">
                            <div>
                                <h3 class="text-xs font-mono text-white uppercase tracking-wider border-b border-brand-border pb-2 mb-3 flex justify-between">
                                    <span>Current Sale Register</span>
                                    <span id="pos-item-count" class="text-brand-gold">0 ITEMS</span>
                                </h3>
                                <div id="pos-register-list" class="space-y-2 max-h-48 overflow-y-auto pr-1 text-xs font-mono mb-4">
                                    <p class="text-gray-500 italic text-center py-8">No items added to current register.</p>
                                </div>
                            </div>

                            <div class="border-t border-brand-border pt-4 space-y-3 font-mono">
                                <!-- Cash Change Calculator -->
                                <div class="grid grid-cols-2 gap-2 text-xs">
                                    <div>
                                        <label class="block text-gray-400 mb-1">CASH TENDERED ($)</label>
                                        <input type="number" id="pos-cash-input" oninput="calculateChange()" placeholder="0.00" class="w-full bg-brand-card border border-brand-border text-white px-2 py-1 rounded">
                                    </div>
                                    <div>
                                        <label class="block text-gray-400 mb-1">CHANGE DUE</label>
                                        <div id="pos-change-due" class="text-brand-gold font-bold py-1">$0.00</div>
                                    </div>
                                </div>

                                <!-- Discount code for POS -->
                                <div class="flex gap-2">
                                    <input type="text" id="pos-discount-input" placeholder="COUPON (KVAL20, GRUNGE15)" class="bg-brand-card border border-brand-border text-xs text-white rounded px-2 py-1 flex-grow font-mono uppercase">
                                    <button onclick="applyPosDiscount()" class="squishy-btn px-3 py-1 bg-brand-card border border-brand-gold text-brand-gold text-xs hover:bg-brand-gold hover:text-black font-bold">APPLY</button>
                                </div>

                                <div class="space-y-1 text-xs">
                                    <div class="flex justify-between text-gray-400">
                                        <span>Subtotal:</span>
                                        <span id="pos-subtotal">$0.00</span>
                                    </div>
                                    <div class="flex justify-between text-gray-400">
                                        <span>Discount:</span>
                                        <span id="pos-discount" class="text-brand-gold">-$0.00</span>
                                    </div>
                                    <div class="flex justify-between text-gray-400">
                                        <span>Sales Tax (8%):</span>
                                        <span id="pos-tax">$0.00</span>
                                    </div>
                                    <div class="flex justify-between text-sm font-bold text-white border-t border-brand-border pt-2">
                                        <span>TOTAL DUE:</span>
                                        <span id="pos-total" class="text-brand-gold">$0.00</span>
                                    </div>
                                </div>

                                <!-- Payment Selector Buttons -->
                                <div class="pt-2 grid grid-cols-3 gap-2">
                                    <button onclick="processPosPayment('Cash Sale')" class="squishy-btn py-2 bg-brand-gold text-black font-bold text-[10px] uppercase hover:bg-white shadow">CASH</button>
                                    <button onclick="processPosPayment('Credit Card')" class="squishy-btn py-2 bg-brand-magenta text-white font-bold text-[10px] uppercase hover:bg-purple-600 shadow">CARD</button>
                                    <button onclick="processPosPayment('Bank Transfer')" class="squishy-btn py-2 bg-brand-card border border-brand-border text-white font-bold text-[10px] uppercase hover:border-brand-gold">TRANSFER</button>
                                </div>
                            </div>
                        </div>
                    </div>

                </div>
            </div>
        </section>

        <!-- STORE FRONT & PRODUCT GRID SECTION -->
        <section id="shop" class="py-16 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            
            <div class="flex flex-col md:flex-row justify-between items-start md:items-end mb-10 pb-4 border-b border-brand-border gap-4">
                <div>
                    <span class="text-xs font-mono text-brand-gold uppercase tracking-widest">// ARCHIVE DROP</span>
                    <h2 class="text-3xl sm:text-4xl font-extrabold text-white uppercase tracking-tight">GARMENT CATALOGUE</h2>
                </div>

                <!-- Category Filters Buttons -->
                <div class="flex flex-wrap gap-2 font-mono text-xs" id="category-filters">
                    <button onclick="filterCategory('all')" class="squishy-btn cat-btn active border border-brand-gold bg-brand-gold text-black font-bold px-3 py-1.5 rounded transition-all shadow">ALL GARMENTS</button>
                    <button onclick="filterCategory('hoodies')" class="squishy-btn cat-btn border border-brand-border text-gray-400 hover:border-brand-gold px-3 py-1.5 rounded transition-all">HOODIES</button>
                    <button onclick="filterCategory('denim')" class="squishy-btn cat-btn border border-brand-border text-gray-400 hover:border-brand-gold px-3 py-1.5 rounded transition-all">BAGGY DENIM</button>
                    <button onclick="filterCategory('tees')" class="squishy-btn cat-btn border border-brand-border text-gray-400 hover:border-brand-gold px-3 py-1.5 rounded transition-all">GRAPHIC TEES</button>
                    <button onclick="filterCategory('cargos')" class="squishy-btn cat-btn border border-brand-border text-gray-400 hover:border-brand-gold px-3 py-1.5 rounded transition-all">CARGOS</button>
                </div>
            </div>

            <!-- Products Grid -->
            <div id="products-grid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Dynamic Items inserted by JS -->
            </div>

        </section>

        <!-- KVAL OUTFIT LAB (INTERACTIVE OUTFIT MIXER) -->
        <section id="outfit-lab" class="py-16 bg-brand-card/30 border-y border-brand-border">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="text-center mb-10">
                    <span class="text-xs font-mono text-brand-gold uppercase tracking-widest">// INTERACTIVE MIXER</span>
                    <h2 class="text-3xl font-extrabold text-white uppercase">KVAL OUTFIT LAB</h2>
                    <p class="text-xs font-mono text-gray-400 mt-2">Combine tops, baggy bottoms, and accessories in real-time to preview full silhouettes.</p>
                </div>

                <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
                    
                    <!-- Left Selectors -->
                    <div class="lg:col-span-5 space-y-4 font-mono text-xs">
                        <div class="bg-brand-card border border-brand-border p-4 rounded-xl">
                            <label class="block text-brand-gold font-bold mb-2">1. SELECT OVERSIZED TOP:</label>
                            <select id="lab-top-select" onchange="updateOutfitLab()" class="w-full bg-brand-black border border-brand-border text-white p-2.5 rounded">
                                <option value="kval-01" data-price="110" data-img="https://i.pinterest.com/originals/d6/6a/eb/d66aeb379b83f7c56e7d42fce4e43403.jpg">KVAL OVERSIZE GOLD GRUNGE HOODIE ($110)</option>
                                <option value="kval-03" data-price="65" data-img="https://www.tiktok.com/api/img/?itemId=7610182710480375061&location=0&aid=1988">CYBER Y2K GRAPHIC OVERSIZED TEE ($65)</option>
                                <option value="kval-05" data-price="125" data-img="https://images.unsplash.com/photo-1578587018452-892bacefd3f2?auto=format&fit=crop&q=80&w=600">DISTRESSED OVERSIZED ZIP-UP ($125)</option>
                            </select>
                        </div>

                        <div class="bg-brand-card border border-brand-border p-4 rounded-xl">
                            <label class="block text-brand-gold font-bold mb-2">2. SELECT BAGGY BOTTOM:</label>
                            <select id="lab-bottom-select" onchange="updateOutfitLab()" class="w-full bg-brand-black border border-brand-border text-white p-2.5 rounded">
                                <option value="kval-02" data-price="130" data-img="https://m.media-amazon.com/images/I/81R9q7A1mPL._AC_SY1000_.jpg">EXTREME BAGGY DENIM JEANS ($130)</option>
                                <option value="kval-04" data-price="120" data-img="https://images.unsplash.com/photo-1517445312882-bc9910d016b7?auto=format&fit=crop&q=80&w=600">KVAL HEAVYWEIGHT CARGO BAGGY PANTS ($120)</option>
                            </select>
                        </div>

                        <div class="p-4 bg-brand-black border border-brand-border rounded-xl space-y-2">
                            <div class="flex justify-between text-sm font-bold">
                                <span>FULL OUTFIT TOTAL:</span>
                                <span id="lab-total-price" class="text-brand-gold text-lg">$240.00</span>
                            </div>
                            <button onclick="addOutfitToCart()" class="squishy-btn w-full py-3 bg-brand-gold text-black font-bold uppercase hover:bg-white transition-colors shadow-lg">ADD ENTIRE OUTFIT TO BAG</button>
                        </div>
                    </div>

                    <!-- Right Outfit Canvas Preview -->
                    <div class="lg:col-span-7 bg-brand-black border-2 border-brand-gold/40 rounded-xl p-6 relative overflow-hidden flex flex-col sm:flex-row items-center justify-center gap-6 min-h-[380px]">
                        <div class="absolute top-4 left-4 font-mono text-[10px] text-brand-gold bg-brand-card px-2 py-1 rounded border border-brand-border">LIVE CANVAS PREVIEW</div>
                        
                        <div class="w-48 h-64 bg-brand-card border border-brand-border rounded p-2 overflow-hidden flex flex-col justify-center items-center">
                            <span class="text-[10px] font-mono text-gray-400 mb-1">TOP GARMENT</span>
                            <img id="lab-top-img" src="https://i.pinterest.com/originals/d6/6a/eb/d66aeb379b83f7c56e7d42fce4e43403.jpg" class="w-full h-48 object-cover rounded" onerror="this.src='https://images.unsplash.com/photo-1556905055-8f358a7a47b2?auto=format&fit=crop&q=80&w=600'">
                        </div>

                        <div class="text-2xl text-brand-gold font-bold">+</div>

                        <div class="w-48 h-64 bg-brand-card border border-brand-border rounded p-2 overflow-hidden flex flex-col justify-center items-center">
                            <span class="text-[10px] font-mono text-gray-400 mb-1">BOTTOM GARMENT</span>
                            <img id="lab-bottom-img" src="https://m.media-amazon.com/images/I/81R9q7A1mPL._AC_SY1000_.jpg" class="w-full h-48 object-cover rounded" onerror="this.src='https://images.unsplash.com/photo-1541099649105-f69ad21f3246?auto=format&fit=crop&q=80&w=600'">
                        </div>
                    </div>

                </div>
            </div>
        </section>

        <!-- FIT VISUALIZER ENGINE -->
        <section id="size-calculator" class="py-16 border-b border-brand-border">
            <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="text-center mb-8">
                    <span class="text-xs font-mono text-brand-gold uppercase tracking-widest">// SILHOUETTE CALCULATOR</span>
                    <h2 class="text-3xl font-extrabold text-white uppercase">INTERACTIVE FIT VISUALIZER</h2>
                    <p class="text-xs font-mono text-gray-400 mt-2">Morph the SVG avatar to compute your custom draping measurements.</p>
                </div>

                <div class="bg-brand-card border border-brand-border p-6 sm:p-8 rounded-xl grid grid-cols-1 md:grid-cols-12 gap-8 items-center">
                    
                    <div class="md:col-span-7 space-y-6 font-mono text-xs">
                        <div>
                            <div class="flex justify-between mb-2">
                                <label class="text-gray-300">YOUR HEIGHT (CM)</label>
                                <span id="fit-height-val" class="text-brand-gold font-bold">178 cm</span>
                            </div>
                            <input type="range" id="fit-height" min="150" max="205" value="178" class="w-full accent-brand-gold" oninput="updateFitCalc()">
                        </div>

                        <div>
                            <div class="flex justify-between mb-2">
                                <label class="text-gray-300">BODY BUILD / WEIGHT (KG)</label>
                                <span id="fit-weight-val" class="text-brand-gold font-bold">75 kg</span>
                            </div>
                            <input type="range" id="fit-weight" min="50" max="120" value="75" class="w-full accent-brand-gold" oninput="updateFitCalc()">
                        </div>

                        <div id="fit-recommendation-box" class="p-4 bg-brand-black border border-brand-gold rounded text-center">
                            <span class="text-xs text-gray-400 block">RECOMMENDED GARMENT SIZE:</span>
                            <span id="fit-recommended-size" class="text-2xl font-black text-brand-gold my-1 block">L (KVAL BAGGY FIT)</span>
                            <p id="fit-recommendation-text" class="text-[11px] text-gray-300">Provides deep boxy shoulder drops and 42cm wide leg openings.</p>
                        </div>
                    </div>

                    <div class="md:col-span-5 flex flex-col items-center justify-center bg-brand-black p-4 rounded-xl border border-brand-border">
                        <span class="text-[10px] font-mono text-gray-500 mb-2">LIVE AVATAR DRAPE MODEL</span>
                        <svg id="avatar-svg" class="w-36 h-56 text-brand-gold" viewBox="0 0 100 160" fill="currentColor">
                            <rect id="svg-torso" x="30" y="30" width="40" height="60" rx="5" class="transition-all duration-300" />
                            <circle cx="50" cy="18" r="12" />
                            <rect id="svg-leg-left" x="30" y="90" width="18" height="65" rx="3" class="transition-all duration-300" />
                            <rect id="svg-leg-right" x="52" y="90" width="18" height="65" rx="3" class="transition-all duration-300" />
                        </svg>
                    </div>

                </div>
            </div>
        </section>

        <!-- INTERACTIVE SCRATCH DISCOUNT MINIGAME -->
        <section id="scratch-section" class="py-16 max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <span class="text-xs font-mono text-brand-gold uppercase tracking-widest">// EXCLUSIVE PERK</span>
            <h2 class="text-3xl font-extrabold text-white uppercase mt-1">SCRATCH & WIN DISCOUNT</h2>
            <p class="text-xs font-mono text-gray-400 mt-2 mb-8">Scratch the card below with your cursor or finger to reveal your secret KVAL promo code!</p>

            <div class="relative w-full max-w-md mx-auto aspect-[2/1] bg-brand-card border-2 border-brand-gold rounded-xl overflow-hidden shadow-2xl flex items-center justify-center">
                <div id="scratch-reward" class="absolute inset-0 flex flex-col items-center justify-center p-4 bg-brand-black font-mono">
                    <span class="text-xs text-gray-400">YOUR SECRET COUPON CODE:</span>
                    <span class="text-3xl font-black text-brand-gold my-2 tracking-wider">GRUNGE25</span>
                    <span class="text-[11px] text-white">25% OFF YOUR ENTIRE ARCHIVE ORDER</span>
                </div>
                <canvas id="scratch-canvas" class="absolute inset-0 w-full h-full"></canvas>
            </div>
            <button onclick="resetScratchCard()" class="squishy-btn mt-6 px-4 py-2 bg-brand-card border border-brand-border text-xs font-mono text-gray-300 hover:text-brand-gold rounded">RESET SCRATCH CARD</button>
        </section>

        <!-- ABOUT SECTION -->
        <section id="about" class="py-16 bg-brand-card/20 border-t border-brand-border">
            <div class="max-w-5xl mx-auto px-4 sm:px-6 lg:px-8 text-center space-y-4">
                <span class="text-xs font-mono text-brand-gold uppercase">// BRAND MANIFESTO</span>
                <h2 class="text-3xl font-extrabold text-white uppercase">ABOUT KVAL ARCHIVE</h2>
                <p class="text-gray-400 font-mono text-sm max-w-2xl mx-auto">
                    Born from underground cyber aesthetics and heavyweight streetwear culture. Every garment is engineered with hyper-baggy drape, distressed washes, and luxury-grade 500GSM cotton. Designed for icons who slay without compromise.
                </p>
            </div>
        </section>

    </main>

    <!-- Shopping Cart Slide-Over Drawer -->
    <div id="cart-drawer" class="fixed inset-0 z-50 overflow-hidden hidden">
        <div class="absolute inset-0 bg-black/70 backdrop-blur-sm transition-opacity" onclick="toggleCartDrawer()"></div>
        <div class="absolute inset-y-0 right-0 max-w-full flex pl-10">
            <div class="w-screen max-w-md bg-brand-card border-l border-brand-border flex flex-col shadow-2xl">
                
                <div class="p-6 border-b border-brand-border flex items-center justify-between">
                    <div class="flex items-center gap-2">
                        <i class="fas fa-shopping-bag text-brand-gold"></i>
                        <h3 class="font-extrabold text-white uppercase tracking-wider text-sm">YOUR KVAL SHOPPING BAG</h3>
                    </div>
                    <button onclick="toggleCartDrawer()" class="squishy-btn text-gray-400 hover:text-white p-2">
                        <i class="fas fa-times"></i>
                    </button>
                </div>

                <div id="cart-items-container" class="flex-grow overflow-y-auto p-6 space-y-4 font-mono text-xs">
                    <p class="text-gray-500 text-center py-12">Your shopping bag is currently empty.</p>
                </div>

                <div class="p-6 border-t border-brand-border space-y-4 font-mono">
                    <div class="flex justify-between text-sm font-bold text-white">
                        <span>BAG TOTAL:</span>
                        <span id="cart-drawer-total" class="text-brand-gold">$0.00</span>
                    </div>
                    <button onclick="checkoutCart()" class="squishy-btn w-full py-4 bg-brand-gold text-black font-bold uppercase tracking-wider hover:bg-white transition-colors shadow-lg">PROCEED TO SECURE CHECKOUT</button>
                </div>

            </div>
        </div>
    </div>

    <!-- Footer -->
    <footer class="bg-brand-black border-t border-brand-border py-12 text-center font-mono text-xs text-gray-500">
        <div class="max-w-7xl mx-auto px-4 space-y-4">
            <div class="flex justify-center gap-6 text-base text-gray-400">
                <a href="#" class="hover:text-brand-gold"><i class="fab fa-instagram"></i></a>
                <a href="#" class="hover:text-brand-gold"><i class="fab fa-tiktok"></i></a>
                <a href="#" class="hover:text-brand-gold"><i class="fab fa-pinterest"></i></a>
            </div>
            <p>© 2026 KVAL OVERSIZE ARCHIVE. ALL RIGHTS RESERVED. ICONIC STREETWEAR.</p>
        </div>
    </footer>

    <!-- JavaScript Application Logic -->
    <script>
        // Audio simulation for click feedback
        function playBeep() {
            try {
                const ctx = new (window.AudioContext || window.webkitAudioContext)();
                const osc = ctx.createOscillator();
                const gain = ctx.createGain();
                osc.type = 'sine';
                osc.frequency.value = 580;
                gain.gain.setValueAtTime(0.03, ctx.currentTime);
                gain.gain.exponentialRampToValueAtTime(0.0001, ctx.currentTime + 0.08);
                osc.connect(gain);
                gain.connect(ctx.destination);
                osc.start();
                osc.stop(ctx.currentTime + 0.08);
            } catch(e) {}
        }

        // Database of KVAL Garments
        const products = [
            { id: 'kval-01', name: 'KVAL OVERSIZE GOLD GRUNGE HOODIE', category: 'hoodies', price: 110, image: 'https://i.pinterest.com/originals/d6/6a/eb/d66aeb379b83f7c56e7d42fce4e43403.jpg', badge: '500 GSM' },
            { id: 'kval-02', name: 'EXTREME BAGGY DENIM JEANS', category: 'denim', price: 130, image: 'https://m.media-amazon.com/images/I/81R9q7A1mPL._AC_SY1000_.jpg', badge: '45CM LEG' },
            { id: 'kval-03', name: 'CYBER Y2K GRAPHIC OVERSIZED TEE', category: 'tees', price: 65, image: 'https://www.tiktok.com/api/img/?itemId=7610182710480375061&location=0&aid=1988', badge: 'HEAVY COTTON' },
            { id: 'kval-04', name: 'KVAL HEAVYWEIGHT CARGO BAGGY PANTS', category: 'cargos', price: 120, image: 'https://images.unsplash.com/photo-1517445312882-bc9910d016b7?auto=format&fit=crop&q=80&w=600', badge: 'MULTI-POCKET' },
            { id: 'kval-05', name: 'DISTRESSED OVERSIZED ZIP-UP', category: 'hoodies', price: 125, image: 'https://images.unsplash.com/photo-1578587018452-892bacefd3f2?auto=format&fit=crop&q=80&w=600', badge: 'WASHED BLACK' },
            { id: 'kval-06', name: 'ACID WASH PARACHUTE PANTS', category: 'cargos', price: 115, image: 'https://images.unsplash.com/photo-1541099649105-f69ad21f3246?auto=format&fit=crop&q=80&w=600', badge: 'PARACHUTE' }
        ];

        let cart = [];
        let posItems = [];
        let posDiscountRate = 0;

        // Render Product Catalog
        function renderProducts(filter = 'all', searchQuery = '') {
            const grid = document.getElementById('products-grid');
            grid.innerHTML = '';

            const filtered = products.filter(p => {
                const matchesCat = filter === 'all' || p.category === filter;
                const matchesSearch = p.name.toLowerCase().includes(searchQuery.toLowerCase());
                return matchesCat && matchesSearch;
            });

            if (filtered.length === 0) {
                grid.innerHTML = `<p class="col-span-full text-center py-12 font-mono text-gray-500">No garments found matching your query.</p>`;
                return;
            }

            filtered.forEach(p => {
                grid.innerHTML += `
                    <div class="bg-brand-card border border-brand-border rounded-xl overflow-hidden group hover:border-brand-gold transition-all duration-300 shadow-xl flex flex-col justify-between">
                        <div class="relative aspect-[4/5] overflow-hidden bg-brand-black">
                            <img src="${p.image}" class="w-full h-full object-cover grayscale group-hover:grayscale-0 group-hover:scale-105 transition-all duration-500" onerror="this.src='https://images.unsplash.com/photo-1556905055-8f358a7a47b2?auto=format&fit=crop&q=80&w=600'">
                            <span class="absolute top-3 left-3 bg-brand-gold text-black text-[10px] font-mono font-black px-2.5 py-1 uppercase">${p.badge}</span>
                        </div>
                        <div class="p-5 space-y-3 font-mono">
                            <div class="flex justify-between items-start">
                                <h3 class="font-bold text-white text-sm uppercase tracking-tight">${p.name}</h3>
                                <span class="text-brand-gold font-black text-base">$${p.price}</span>
                            </div>
                            <button onclick="addToCart('${p.id}')" class="squishy-btn w-full py-3 bg-brand-card border border-brand-border hover:border-brand-gold hover:bg-brand-gold hover:text-black text-xs font-bold uppercase transition-all flex items-center justify-center gap-2">
                                <i class="fas fa-shopping-bag"></i>
                                <span>ADD TO BAG</span>
                            </button>
                        </div>
                    </div>
                `;
            });
        }

        function filterCategory(cat) {
            playBeep();
            document.querySelectorAll('.cat-btn').forEach(btn => {
                btn.classList.remove('border-brand-gold', 'bg-brand-gold', 'text-black', 'font-bold');
                btn.classList.add('border-brand-border', 'text-gray-400');
            });
            event.target.classList.remove('border-brand-border', 'text-gray-400');
            event.target.classList.add('border-brand-gold', 'bg-brand-gold', 'text-black', 'font-bold');
            renderProducts(cat, document.getElementById('search-input').value);
        }

        function handleSearch() {
            const query = document.getElementById('search-input').value;
            renderProducts('all', query);
        }

        function handleSearchMobile() {
            const query = document.getElementById('mobile-search-input').value;
            renderProducts('all', query);
        }

        // Cart Drawer Management
        function toggleCartDrawer() {
            playBeep();
            const drawer = document.getElementById('cart-drawer');
            drawer.classList.toggle('hidden');
        }

        function addToCart(id) {
            playBeep();
            const product = products.find(p => p.id === id);
            const existing = cart.find(item => item.id === id);
            if (existing) {
                existing.qty += 1;
            } else {
                cart.push({ ...product, qty: 1 });
            }
            updateCartUI();
            toggleCartDrawer();
        }

        function updateCartUI() {
            const container = document.getElementById('cart-items-container');
            const badge = document.getElementById('cart-badge');
            const totalEl = document.getElementById('cart-drawer-total');

            const totalCount = cart.reduce((sum, item) => sum + item.qty, 0);
            badge.innerText = totalCount;

            if (cart.length === 0) {
                container.innerHTML = `<p class="text-gray-500 text-center py-12">Your shopping bag is currently empty.</p>`;
                totalEl.innerText = '$0.00';
                return;
            }

            container.innerHTML = '';
            let totalPrice = 0;

            cart.forEach(item => {
                totalPrice += item.price * item.qty;
                container.innerHTML += `
                    <div class="flex items-center justify-between bg-brand-black p-3 rounded border border-brand-border">
                        <div class="flex items-center gap-3">
                            <img src="${item.image}" class="w-12 h-12 object-cover rounded">
                            <div>
                                <h4 class="font-bold text-white text-[11px]">${item.name}</h4>
                                <span class="text-brand-gold">$${item.price} x ${item.qty}</span>
                            </div>
                        </div>
                        <button onclick="removeFromCart('${item.id}')" class="squishy-btn text-red-400 hover:text-red-200 p-1"><i class="fas fa-trash text-xs"></i></button>
                    </div>
                `;
            });

            totalEl.innerText = `$${totalPrice.toFixed(2)}`;
        }

        function removeFromCart(id) {
            playBeep();
            cart = cart.filter(item => item.id !== id);
            updateCartUI();
        }

        function checkoutCart() {
            playBeep();
            if (cart.length === 0) {
                alert('Your bag is empty!');
                return;
            }
            alert('🎉 Order successfully placed! Thank you for supporting KVAL Archive. Slay!');
            cart = [];
            updateCartUI();
            toggleCartDrawer();
        }

        // POS Mode Terminal Logic
        function togglePosMode() {
            playBeep();
            const section = document.getElementById('pos-terminal-section');
            const dot = document.getElementById('pos-status-dot');
            const btnText = document.getElementById('pos-btn-text');

            section.classList.toggle('hidden');
            if (!section.classList.contains('hidden')) {
                dot.classList.remove('bg-red-500');
                dot.classList.add('bg-brand-gold');
                btnText.innerText = 'EXIT POS';
                initPosGrid();
            } else {
                dot.classList.remove('bg-brand-gold');
                dot.classList.add('bg-red-500');
                btnText.innerText = 'POS TERMINAL';
            }
        }

        function initPosGrid() {
            const grid = document.getElementById('pos-items-grid');
            grid.innerHTML = '';
            products.forEach(p => {
                grid.innerHTML += `
                    <div onclick="addPosItem('${p.id}')" class="squishy-btn bg-brand-black border border-brand-border p-3 rounded hover:border-brand-gold cursor-pointer flex flex-col justify-between">
                        <span class="text-[11px] font-mono text-white font-bold uppercase">${p.name}</span>
                        <span class="text-brand-gold font-mono text-xs mt-2">$${p.price}</span>
                    </div>
                `;
            });
        }

        function addPosItem(id) {
            playBeep();
            const product = products.find(p => p.id === id);
            const existing = posItems.find(item => item.id === id);
            if (existing) {
                existing.qty += 1;
            } else {
                posItems.push({ ...product, qty: 1 });
            }
            updatePosRegister();
        }

        function updatePosRegister() {
            const list = document.getElementById('pos-register-list');
            const countEl = document.getElementById('pos-item-count');
            const subtotalEl = document.getElementById('pos-subtotal');
            const discountEl = document.getElementById('pos-discount');
            const taxEl = document.getElementById('pos-tax');
            const totalEl = document.getElementById('pos-total');

            const totalItems = posItems.reduce((s, i) => s + i.qty, 0);
            countEl.innerText = `${totalItems} ITEMS`;

            if (posItems.length === 0) {
                list.innerHTML = `<p class="text-gray-500 italic text-center py-8">No items added to current register.</p>`;
                subtotalEl.innerText = '$0.00';
                discountEl.innerText = '-$0.00';
                taxEl.innerText = '$0.00';
                totalEl.innerText = '$0.00';
                return;
            }

            list.innerHTML = '';
            let subtotal = 0;

            posItems.forEach(item => {
                subtotal += item.price * item.qty;
                list.innerHTML += `
                    <div class="flex justify-between items-center bg-brand-card p-2 rounded">
                        <span class="text-white">${item.name} (x${item.qty})</span>
                        <span class="text-brand-gold">$${item.price * item.qty}</span>
                    </div>
                `;
            });

            const discount = subtotal * posDiscountRate;
            const taxable = subtotal - discount;
            const tax = taxable * 0.08;
            const total = taxable + tax;

            subtotalEl.innerText = `$${subtotal.toFixed(2)}`;
            discountEl.innerText = `-$${discount.toFixed(2)}`;
            taxEl.innerText = `$${tax.toFixed(2)}`;
            totalEl.innerText = `$${total.toFixed(2)}`;
            calculateChange();
        }

        function applyPosDiscount() {
            playBeep();
            const code = document.getElementById('pos-discount-input').value.toUpperCase().trim();
            if (code === 'KVAL20' || code === 'GRUNGE25') {
                posDiscountRate = 0.20;
                alert('✨ Coupon applied successfully! 20% OFF.');
            } else {
                alert('❌ Invalid or expired coupon code.');
                posDiscountRate = 0;
            }
            updatePosRegister();
        }

        function calculateChange() {
            const cash = parseFloat(document.getElementById('pos-cash-input').value) || 0;
            const totalStr = document.getElementById('pos-total').innerText.replace('$', '');
            const total = parseFloat(totalStr) || 0;
            const changeDue = cash - total;
            document.getElementById('pos-change-due').innerText = changeDue >= 0 ? `$${changeDue.toFixed(2)}` : '$0.00';
        }

        function clearPosCart() {
            playBeep();
            posItems = [];
            posDiscountRate = 0;
            document.getElementById('pos-cash-input').value = '';
            document.getElementById('pos-discount-input').value = '';
            updatePosRegister();
        }

        function processPosPayment(method) {
            playBeep();
            if (posItems.length === 0) {
                alert('Terminal is empty. Add items to register.');
                return;
            }
            alert(`✅ Payment processed via ${method}! Receipt printed. Slay!`);
            clearPosCart();
            togglePosMode();
        }

        // Outfit Lab Logic
        function updateOutfitLab() {
            const topSelect = document.getElementById('lab-top-select');
            const bottomSelect = document.getElementById('lab-bottom-select');

            const topOpt = topSelect.options[topSelect.selectedIndex];
            const bottomOpt = bottomSelect.options[bottomSelect.selectedIndex];

            document.getElementById('lab-top-img').src = topOpt.getAttribute('data-img');
            document.getElementById('lab-bottom-img').src = bottomOpt.getAttribute('data-img');

            const total = parseFloat(topOpt.getAttribute('data-price')) + parseFloat(bottomOpt.getAttribute('data-price'));
            document.getElementById('lab-total-price').innerText = `$${total.toFixed(2)}.00`;
        }

        function addOutfitToCart() {
            playBeep();
            const topSelect = document.getElementById('lab-top-select');
            const bottomSelect = document.getElementById('lab-bottom-select');

            cart.push({ id: topSelect.value, name: topSelect.options[topSelect.selectedIndex].text.split(' ($')[0], price: parseFloat(topSelect.options[topSelect.selectedIndex].getAttribute('data-price')), qty: 1, image: topSelect.options[topSelect.selectedIndex].getAttribute('data-img') });
            cart.push({ id: bottomSelect.value, name: bottomSelect.options[bottomSelect.selectedIndex].text.split(' ($')[0], price: parseFloat(bottomSelect.options[bottomSelect.selectedIndex].getAttribute('data-price')), qty: 1, image: bottomSelect.options[bottomSelect.selectedIndex].getAttribute('data-img') });

            updateCartUI();
            toggleCartDrawer();
        }

        // Fit Visualizer Engine Logic
        function updateFitCalc() {
            const height = document.getElementById('fit-height').value;
            const weight = document.getElementById('fit-weight').value;

            document.getElementById('fit-height-val').innerText = `${height} cm`;
            document.getElementById('fit-weight-val').innerText = `${weight} kg`;

            const torso = document.getElementById('svg-torso');
            const legLeft = document.getElementById('svg-leg-left');
            const legRight = document.getElementById('svg-leg-right');

            let size = 'L (KVAL BAGGY FIT)';
            let desc = 'Provides deep boxy shoulder drops and 42cm wide leg openings.';

            if (weight > 90 || height > 190) {
                size = 'XL (EXTREME OVERSIZE)';
                desc = 'Maximum drop shoulder length with exaggerated floor-pooling hems.';
            } else if (weight < 60 && height < 170) {
                size = 'M (STANDARD ARCHIVE)';
                desc = 'Balanced baggy proportions tailored for compact frames.';
            }

            document.getElementById('fit-recommended-size').innerText = size;
            document.getElementById('fit-recommendation-text').innerText = desc;

            torso.setAttribute('width', 35 + (weight * 0.15));
            legLeft.setAttribute('width', 15 + (weight * 0.05));
            legRight.setAttribute('width', 15 + (weight * 0.05));
        }

        // Scratch Card Minigame Logic
        function initScratchCard() {
            const canvas = document.getElementById('scratch-canvas');
            const ctx = canvas.getContext('2d');
            canvas.width = canvas.offsetWidth;
            canvas.height = canvas.offsetHeight;

            ctx.fillStyle = '#272530';
            ctx.fillRect(0, 0, canvas.width, canvas.height);
            ctx.fillStyle = '#d4af37';
            ctx.font = 'bold 14px Courier New';
            ctx.textAlign = 'center';
            ctx.fillText('⚡ SCRATCH HERE FOR 25% OFF ⚡', canvas.width / 2, canvas.height / 2 + 5);

            let isDrawing = false;

            function scratch(e) {
                if (!isDrawing) return;
                const rect = canvas.getBoundingClientRect();
                const x = (e.clientX || e.touches[0].clientX) - rect.left;
                const y = (e.clientY || e.touches[0].clientY) - rect.top;

                ctx.globalCompositeOperation = 'destination-out';
                ctx.beginPath();
                ctx.arc(x, y, 22, 0, Math.PI * 2, false);
                ctx.fill();
            }

            canvas.addEventListener('mousedown', () => isDrawing = true);
            canvas.addEventListener('mousemove', scratch);
            window.addEventListener('mouseup', () => isDrawing = false);

            canvas.addEventListener('touchstart', () => isDrawing = true);
            canvas.addEventListener('touchmove', scratch);
            window.addEventListener('touchend', () => isDrawing = false);
        }

        function resetScratchCard() {
            playBeep();
            initScratchCard();
        }

        // Initialize App on Load
        window.onload = () => {
            renderProducts();
            initScratchCard();
        };
    </script>
</body>
</html>
