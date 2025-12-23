# khtravel
<!DOCTYPE html>
<html lang="zh-Hant">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>高雄旅行手帳 - 12/25-12/27 版</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+TC:wght@300;400;500;700&display=swap" rel="stylesheet">
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        muji: {
                            bg: '#F5F5F0',     
                            paper: '#FFFFFF',
                            text: '#333333',   
                            accent: '#7F8C8D', 
                            warm: '#BC9F8B',   
                            alert: '#D35400'   
                        }
                    },
                    fontFamily: {
                        sans: ['Noto Sans TC', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <style>
        body { background-color: #F5F5F0; -webkit-tap-highlight-color: transparent; }
        .tab-content { display: none; }
        .tab-content.active { display: block; }
        .muji-card { border: 1px solid #E5E5E0; }
        .nav-active { color: #BC9F8B !important; border-top: 2px solid #BC9F8B; }
    </style>
</head>
<body class="font-sans text-muji-text pb-24">

    <header class="sticky top-0 bg-muji-paper/80 backdrop-blur-md z-40 border-b border-gray-200 px-6 py-4">
        <h1 class="text-xl font-bold tracking-widest text-center">高雄旅行手帳</h1>
        <p class="text-[10px] text-center text-gray-400 mt-1 uppercase">12/25 - 12/27 Travel Guide</p>
    </header>

    <main id="main-content" class="px-5 pt-6">
        
        <section id="plan" class="tab-content active">
            <h2 class="text-sm font-bold border-l-4 border-muji-warm pl-3 mb-6 tracking-widest uppercase">行程表 PLAN</h2>
            
            <div class="bg-muji-alert/10 border-l-4 border-muji-alert p-4 rounded-r-lg mb-8 shadow-sm">
                <div class="flex items-center gap-3 text-muji-alert mb-2 font-bold text-sm">
                    <i class="fa-solid fa-train"></i>
                    <span>高鐵班次</span>
                </div>
                <div class="text-xs space-y-1 text-gray-700 font-medium">
                    <p>去程：12/25 板橋 10:29 → 左營 12:20</p>
                    <p>回程：12/27 左營 16:55 → 板橋 18:20</p>
                </div>
            </div>

            <div class="space-y-8">
                <div class="relative pl-6 border-l-2 border-muji-warm/30">
                    <div class="absolute -left-[9px] top-0 w-4 h-4 rounded-full bg-muji-warm"></div>
                    <h3 class="font-bold text-lg mb-4">DAY 01 <span class="text-xs font-normal text-gray-400 ml-2">12/25 市區巡禮</span></h3>
                    <div class="space-y-3">
                        <div class="bg-white p-4 rounded-xl muji-card">
                            <span class="text-[10px] text-muji-warm font-bold">LUNCH</span>
                            <p class="font-bold">侯記鴨肉飯</p>
                        </div>
                        <div class="bg-white p-4 rounded-xl muji-card">
                            <span class="text-[10px] text-gray-400 font-bold uppercase">Stay</span>
                            <p class="font-bold">帕鉑舍旅 (Check-in)</p>
                        </div>
                        <div class="bg-white p-4 rounded-xl muji-card">
                            <span class="text-[10px] text-muji-warm font-bold">DINNER</span>
                            <p class="font-bold">正宗鴨肉飯 + 瑞豐夜市</p>
                        </div>
                    </div>
                </div>

                <div class="relative pl-6 border-l-2 border-muji-warm/30">
                    <div class="absolute -left-[9px] top-0 w-4 h-4 rounded-full bg-muji-warm"></div>
                    <h3 class="font-bold text-lg mb-4">DAY 02 <span class="text-xs font-normal text-gray-400 ml-2">12/26 港灣風情</span></h3>
                    <div class="space-y-3 font-medium">
                        <div class="bg-white p-4 rounded-xl muji-card">
                            <p>駁二、西子灣、真愛碼頭、旗津</p>
                        </div>
                        <div class="bg-white p-4 rounded-xl muji-card">
                            <span class="text-[10px] text-muji-warm font-bold uppercase">Dinner</span>
                            <p class="font-bold">自強夜市：南豐滷肉飯</p>
                        </div>
                    </div>
                </div>

                <div class="relative pl-6 border-l-2 border-muji-warm/30">
                    <div class="absolute -left-[9px] top-0 w-4 h-4 rounded-full bg-muji-warm"></div>
                    <h3 class="font-bold text-lg mb-4">DAY 03 <span class="text-xs font-normal text-gray-400 ml-2">12/27 湖光山色</span></h3>
                    <div class="space-y-3 text-sm">
                        <div class="bg-white p-4 rounded-xl muji-card">
                            <p class="font-bold">澄清湖 & 蓮池潭風景區</p>
                        </div>
                        <div class="bg-white p-4 rounded-xl muji-card">
                            <span class="text-[10px] text-muji-warm font-bold uppercase">Lunch</span>
                            <p class="font-bold">西安麵食館</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section id="food" class="tab-content">
            <h2 class="text-sm font-bold border-l-4 border-muji-warm pl-3 mb-6 tracking-widest uppercase">美食懶人包 FOOD</h2>
            
            <div class="space-y-4">
                <div class="bg-white p-6 rounded-2xl muji-card shadow-sm border-muji-warm/30">
                    <h3 class="font-bold text-lg mb-4 flex items-center gap-2">
                        <span class="text-xl">🌙</span> 夜市必吃清單
                    </h3>
                    <div class="space-y-6">
                        <div>
                            <p class="text-xs font-bold text-muji-warm mb-2 flex justify-between">
                                <span>● 瑞豐夜市 (D1 推薦)</span>
                                <a href="https://www.google.com/maps/search/瑞豐夜市" target="_blank" class="text-blue-500 underline text-[10px]">導航</a>
                            </p>
                            <ul class="text-sm space-y-1 text-gray-600 pl-4 border-l border-gray-100">
                                <li>天使雞排、萬國牛排、QQ蛋</li>
                            </ul>
                        </div>
                        <div>
                            <p class="text-xs font-bold text-muji-warm mb-2 flex justify-between">
                                <span>● 自強夜市 (D2 推薦)</span>
                                <a href="https://www.google.com/maps/search/自強夜市" target="_blank" class="text-blue-500 underline text-[10px]">導航</a>
                            </p>
                            <ul class="text-sm space-y-1 text-gray-600 pl-4 border-l border-gray-100">
                                <li>南豐滷肉飯、老牌白糖粿 (外酥內軟)</li>
                            </ul>
                        </div>
                        <div>
                            <p class="text-xs font-bold text-muji-warm mb-2 flex justify-between">
                                <span>● 旗津老街</span>
                                <a href="https://www.google.com/maps/search/旗津老街" target="_blank" class="text-blue-500 underline text-[10px]">導航</a>
                            </p>
                            <ul class="text-sm space-y-1 text-gray-600 pl-4 border-l border-gray-100">
                                <li>烤魷魚、赤肉羹、番茄沾薑汁</li>
                            </ul>
                        </div>
                    </div>
                </div>

                <div class="bg-white p-5 rounded-2xl muji-card">
                    <div class="flex justify-between items-start mb-2">
                        <span class="text-[11px] bg-muji-warm/20 text-muji-warm px-2 py-0.5 rounded font-bold">必喝推薦</span>
                        <a href="https://www.google.com/maps/search/蓁香茗茶" target="_blank" class="text-blue-500 bg-blue-50 w-8 h-8 rounded-full flex items-center justify-center">
                            <i class="fa-solid fa-location-arrow"></i>
                        </a>
                    </div>
                    <h3 class="font-bold text-lg">蓁香茗茶</h3>
                    <p class="text-xs text-gray-500 mt-2 leading-relaxed italic">「茶香濃郁，不愛喝甜的推薦鮮奶茶系列。」</p>
                </div>

                <div class="bg-white p-5 rounded-2xl muji-card">
                    <div class="flex justify-between items-start mb-2">
                        <span class="text-[11px] bg-muji-warm/20 text-muji-warm px-2 py-0.5 rounded font-bold">蓮池潭旁</span>
                        <a href="https://www.google.com/maps/search/西安麵食館" target="_blank" class="text-blue-500 bg-blue-50 w-8 h-8 rounded-full flex items-center justify-center">
                            <i class="fa-solid fa-location-arrow"></i>
                        </a>
                    </div>
                    <h3 class="font-bold text-lg">西安麵食館</h3>
                    <p class="text-xs text-gray-500 mt-2 leading-relaxed italic">「最有特色的皮帶麵，口感Q彈寬大，孜然味濃。」</p>
                </div>
            </div>
        </section>

        <section id="guide" class="tab-content">
            <h2 class="text-sm font-bold border-l-4 border-muji-warm pl-3 mb-6 tracking-widest uppercase">深度導覽 GUIDE</h2>
            
            <article class="bg-white p-5 rounded-2xl muji-card mb-6 shadow-sm">
                <div class="flex justify-between items-start mb-3">
                    <h3 class="font-bold text-lg">蓮池潭 & 龍虎塔</h3>
                    <a href="https://www.google.com/maps/search/蓮池潭龍虎塔" target="_blank" class="text-blue-500 bg-blue-50 w-10 h-10 rounded-full flex items-center justify-center">
                        <i class="fa-solid fa-map-location-dot text-lg"></i>
                    </a>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mb-4">
                    入龍口、出虎口，象徵大吉大利。這是來高雄絕不能錯過的中式美學地標。
                </p>
                <div class="h-44 rounded-xl overflow-hidden border border-gray-100">
                    <iframe width="100%" height="100%" frameborder="0" src="https://www.openstreetmap.org/export/embed.html?bbox=120.291,22.678,120.299,22.685&layer=mapnik"></iframe>
                </div>
            </article>

            <div class="bg-white p-6 rounded-2xl muji-card shadow-sm">
                <h3 class="text-xs font-bold text-gray-400 mb-4 uppercase tracking-widest">交通與氣象</h3>
                <div class="grid grid-cols-1 gap-3">
                    <a href="https://www.krtc.com.tw/" target="_blank" class="flex items-center justify-between bg-gray-50 p-4 rounded-xl text-sm font-medium">
                        <span class="flex items-center gap-3"><i class="fa-solid fa-m text-blue-600"></i> 高雄捷運時刻表</span>
                        <i class="fa-solid fa-chevron-right text-gray-300"></i>
                    </a>
                    <a href="https://tip.railway.gov.tw/" target="_blank" class="flex items-center justify-between bg-gray-50 p-4 rounded-xl text-sm font-medium">
                        <span class="flex items-center gap-3"><i class="fa-solid fa-train text-orange-600"></i> 火車時刻表查詢</span>
                        <i class="fa-solid fa-chevron-right text-gray-300"></i>
                    </a>
                    <a href="https://www.cwa.gov.tw/V8/C/W/County/County.html?CID=64" target="_blank" class="flex items-center justify-between bg-gray-50 p-4 rounded-xl text-sm font-medium">
                        <span class="flex items-center gap-3"><i class="fa-solid fa-sun text-yellow-500"></i> 高雄即時天氣</span>
                        <i class="fa-solid fa-chevron-right text-gray-300"></i>
                    </a>
                </div>
            </div>
        </section>
    </main>

    <nav class="fixed bottom-0 left-0 right-0 bg-white/95 backdrop-blur-sm border-t border-gray-100 px-2 z-50">
        <div class="max-w-md mx-auto flex justify-between items-center h-20">
            <button onclick="showTab('plan')" class="nav-btn flex-1 flex flex-col items-center gap-1 text-gray-300 py-2 nav-active" data-tab="plan">
                <i class="fa-solid fa-calendar-day text-lg"></i>
                <span class="text-[9px] font-bold">PLAN</span>
            </button>
            <button onclick="showTab('food')" class="nav-btn flex-1 flex flex-col items-center gap-1 text-gray-300 py-2" data-tab="food">
                <i class="fa-solid fa-utensils text-lg"></i>
                <span class="text-[9px] font-bold">FOOD</span>
            </button>
            <button onclick="showTab('guide')" class="nav-btn flex-1 flex flex-col items-center gap-1 text-gray-300 py-2" data-tab="guide">
                <i class="fa-solid fa-compass text-lg"></i>
                <span class="text-[9px] font-bold">GUIDE</span>
            </button>
        </div>
    </nav>

    <script>
        function showTab(tabId) {
            document.querySelectorAll('.tab-content').forEach(el => el.classList.remove('active'));
            document.getElementById(tabId).classList.add('active');
            document.querySelectorAll('.nav-btn').forEach(btn => btn.classList.remove('nav-active'));
            document.querySelector(`[data-tab="${tabId}"]`).classList.add('nav-active');
            window.scrollTo(0,0);
        }
    </script>
</body>

</html>
