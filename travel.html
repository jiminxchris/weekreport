<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>일본 도시별 대표 환경 Explorer</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@300;400;500;700;900&display=swap" rel="stylesheet">
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Noto Sans KR', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            red: '#E60012',
                            dark: '#1E293B',
                            accent: '#38BDF8',
                            gold: '#F59E0B'
                        }
                    }
                }
            }
        }
    </script>
    <style>
        /* Custom scrollbar & glassmorphism styling */
        ::-webkit-scrollbar {
            width: 8px;
            height: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #f1f5f9;
        }
        ::-webkit-scrollbar-thumb {
            background: #cbd5e1;
            border-radius: 4px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #94a3b8;
        }
        .glass-panel {
            background: rgba(255, 255, 255, 0.85);
            backdrop-filter: blur(12px);
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 font-sans min-h-screen flex flex-col">

    <!-- Header Navbar -->
    <header class="sticky top-0 z-30 bg-white/90 backdrop-blur-md border-b border-slate-200 shadow-sm">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-16 flex items-center justify-between">
            <div class="flex items-center gap-3">
                <span class="text-2xl">🇯🇵</span>
                <div>
                    <h1 class="text-xl font-bold text-slate-900 tracking-tight flex items-center gap-2">
                        Japan Travel Explorer
                        <span class="text-xs font-semibold px-2 py-0.5 bg-red-100 text-brand-red rounded-full">Interactive</span>
                    </h1>
                    <p class="text-xs text-slate-500 hidden sm:block">클릭하여 각 도시의 매력과 주요 환경을 탐색해보세요</p>
                </div>
            </div>
            
            <div class="flex items-center gap-2">
                <div class="relative">
                    <i class="fa-solid fa-magnifying-glass absolute left-3 top-1/2 -translate-y-1/2 text-slate-400 text-sm"></i>
                    <input type="text" id="searchInput" placeholder="도시 또는 키워드 검색..." 
                           class="pl-9 pr-4 py-1.5 text-sm bg-slate-100 border border-slate-200 rounded-full focus:outline-none focus:ring-2 focus:ring-red-500/50 w-36 sm:w-60 transition-all">
                </div>
            </div>
        </div>
    </header>

    <main class="flex-grow max-w-7xl w-full mx-auto px-4 sm:px-6 lg:px-8 py-6 flex flex-col gap-6">
        
        <!-- Hero Tagline & Stats Banner -->
        <section class="bg-gradient-to-r from-slate-900 via-indigo-950 to-slate-900 rounded-3xl p-6 sm:p-8 text-white shadow-xl relative overflow-hidden">
            <div class="absolute -right-10 -bottom-10 opacity-10 text-9xl font-black pointer-events-none">JAPAN</div>
            <div class="relative z-10 max-w-2xl">
                <span class="inline-block px-3 py-1 bg-red-600/80 text-white text-xs font-bold rounded-full mb-3 tracking-wider">나에게 딱 맞는 여행지 찾기</span>
                <h2 class="text-2xl sm:text-4xl font-extrabold leading-tight mb-3">
                    일본 도시별 주요 환경과<br><span class="text-sky-400">명소·테마</span>를 한눈에 둘러보세요!
                </h2>
                <p class="text-slate-300 text-sm sm:text-base mb-4">
                    도심의 화려한 야경부터 전통 가옥 거리, 온천 마을, 대자연, 휴양지까지 도시 카드를 클릭하면 상세 분위기와 환경을 미리 확인할 수 있습니다.
                </p>
            </div>

            <!-- Quick Filter Chips -->
            <div class="mt-4 pt-4 border-t border-slate-800/80 flex flex-wrap gap-2 items-center">
                <span class="text-xs text-slate-400 font-medium mr-1"><i class="fa-solid fa-filter mr-1"></i>테마 필터:</span>
                <button onclick="filterCities('all')" class="filter-btn active-filter text-xs px-3 py-1.5 rounded-full font-medium transition-all bg-white text-slate-900 shadow">전체 보기</button>
                <button onclick="filterCities('urban')" class="filter-btn text-xs px-3 py-1.5 rounded-full font-medium transition-all bg-slate-800 hover:bg-slate-700 text-slate-300">🏙️ 현대 도시 & 쇼핑</button>
                <button onclick="filterCities('culture')" class="filter-btn text-xs px-3 py-1.5 rounded-full font-medium transition-all bg-slate-800 hover:bg-slate-700 text-slate-300">⛩️ 역사 & 전통</button>
                <button onclick="filterCities('onsen')" class="filter-btn text-xs px-3 py-1.5 rounded-full font-medium transition-all bg-slate-800 hover:bg-slate-700 text-slate-300">♨️ 힐링 & 온천</button>
                <button onclick="filterCities('nature')" class="filter-btn text-xs px-3 py-1.5 rounded-full font-medium transition-all bg-slate-800 hover:bg-slate-700 text-slate-300">❄️ 대자연 & 설경</button>
                <button onclick="filterCities('resort')" class="filter-btn text-xs px-3 py-1.5 rounded-full font-medium transition-all bg-slate-800 hover:bg-slate-700 text-slate-300">🏖️ 휴양 & 에메랄드 바다</button>
            </div>
        </section>

        <!-- City Cards Grid Section -->
        <section>
            <div class="flex items-center justify-between mb-4">
                <h3 class="text-lg font-bold text-slate-900 flex items-center gap-2">
                    <i class="fa-solid fa-location-dot text-brand-red"></i>
                    주요 추천 도시 목록
                    <span id="cityCountBadge" class="text-xs bg-slate-200 text-slate-700 font-semibold px-2 py-0.5 rounded-full">8개 도시</span>
                </h3>
                <span class="text-xs text-slate-500"><i class="fa-solid fa-hand-pointer text-slate-400 mr-1"></i>카드를 클릭하면 상세 환경이 열립니다</span>
            </div>

            <!-- Cards Container -->
            <div id="cityGrid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-5">
                <!-- Dynamically Populated via JavaScript -->
            </div>
        </section>
    </main>

    <!-- City Detail Modal -->
    <div id="cityModal" class="fixed inset-0 z-50 flex items-center justify-center p-4 bg-slate-900/60 backdrop-blur-sm opacity-0 pointer-events-none transition-all duration-300">
        <div class="bg-white w-full max-w-4xl rounded-3xl shadow-2xl overflow-hidden flex flex-col max-h-[90vh] transform scale-95 transition-all duration-300" id="modalContainer">
            
            <!-- Modal Header / Hero Banner -->
            <div id="modalHero" class="relative h-64 sm:h-80 bg-slate-800 text-white p-6 flex flex-col justify-end bg-cover bg-center">
                <div class="absolute inset-0 bg-gradient-to-t from-slate-950 via-slate-950/40 to-transparent"></div>
                
                <!-- Close Button -->
                <button onclick="closeModal()" class="absolute top-4 right-4 w-10 h-10 rounded-full bg-slate-900/60 hover:bg-slate-900/90 backdrop-blur-md text-white flex items-center justify-center transition-all shadow-lg z-10">
                    <i class="fa-solid fa-xmark text-lg"></i>
                </button>

                <!-- Top Badge & Region -->
                <div class="relative z-10 flex items-center gap-2 mb-2">
                    <span id="modalRegion" class="text-xs font-bold px-3 py-1 bg-red-600 text-white rounded-full uppercase tracking-wider">관동</span>
                    <span id="modalVibeBadge" class="text-xs font-semibold px-3 py-1 bg-white/20 backdrop-blur-md text-white rounded-full">화려한 초고층 빌딩 & 문화 중심지</span>
                </div>

                <h2 id="modalTitle" class="relative z-10 text-3xl sm:text-5xl font-black tracking-tight drop-shadow-md">도쿄 (Tokyo)</h2>
                <p id="modalTagline" class="relative z-10 text-slate-200 text-sm sm:text-base mt-1 font-medium">전통과 초현대가 절묘하게 교차하는 매혹적인 거대 대도시</p>
            </div>

            <!-- Modal Content Body -->
            <div class="p-6 sm:p-8 overflow-y-auto space-y-6 flex-grow bg-slate-50">
                
                <!-- Environment & Atmosphere Cards -->
                <div>
                    <h3 class="text-base font-bold text-slate-900 mb-3 flex items-center gap-2">
                        <i class="fa-solid fa-mountain-city text-red-500"></i> 도시의 주요 환경 & 분위기 (Environment Vibe)
                    </h3>
                    <div id="modalEnvGrid" class="grid grid-cols-1 sm:grid-cols-3 gap-3">
                        <!-- Populated by JS -->
                    </div>
                </div>

                <!-- Key Highlights & Attractions -->
                <div>
                    <h3 class="text-base font-bold text-slate-900 mb-3 flex items-center gap-2">
                        <i class="fa-solid fa-camera text-sky-500"></i> 핵심 방문 스팟 & 환경적 특징
                    </h3>
                    <div id="modalAttractions" class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                        <!-- Populated by JS -->
                    </div>
                </div>

                <!-- Culinary & Local Delicacies -->
                <div class="bg-amber-50/70 border border-amber-200/60 rounded-2xl p-4">
                    <h3 class="text-sm font-bold text-amber-900 mb-2 flex items-center gap-2">
                        <i class="fa-solid fa-utensils text-amber-600"></i> 대표 미식 & 먹거리 환경
                    </h3>
                    <p id="modalFood" class="text-xs sm:text-sm text-amber-800 leading-relaxed"></p>
                </div>

                <!-- Best Season & Travel Tip -->
                <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                    <div class="bg-white border border-slate-200 rounded-2xl p-4">
                        <div class="text-xs font-bold text-slate-400 uppercase tracking-wider mb-1"><i class="fa-solid fa-calendar-days text-indigo-500 mr-1"></i> 추천 방문 계절</div>
                        <div id="modalSeason" class="text-sm font-semibold text-slate-800"></div>
                    </div>
                    <div class="bg-white border border-slate-200 rounded-2xl p-4">
                        <div class="text-xs font-bold text-slate-400 uppercase tracking-wider mb-1"><i class="fa-solid fa-lightbulb text-amber-500 mr-1"></i> 현지 여행 꿀팁</div>
                        <div id="modalTip" class="text-sm text-slate-700"></div>
                    </div>
                </div>

            </div>

            <!-- Modal Footer -->
            <div class="p-4 bg-white border-t border-slate-200 flex justify-end">
                <button onclick="closeModal()" class="px-5 py-2 text-sm font-bold bg-slate-900 hover:bg-slate-800 text-white rounded-xl transition-all">
                    닫기
                </button>
            </div>
        </div>
    </div>

    <script>
        // Data for Cities in Japan
        const citiesData = [
            {
                id: 'tokyo',
                name: '도쿄',
                englishName: 'Tokyo',
                region: '관동 (Kanto)',
                category: 'urban',
                categoryLabel: '🏙️ 현대 도시 & 쇼핑',
                image: 'https://images.unsplash.com/photo-1540959733332-eab4deabeeaf?auto=format&fit=crop&w=800&q=80',
                shortDesc: '네온사인 번화가와 첨단 문화, 고즈넉한 정원이 절묘하게 조화된 매가시티',
                tagline: '세계 최대 규모의 대도시와 다채로운 서브컬처, 명품 쇼핑의 천국',
                envCards: [
                    { title: '도심 스카이라인', desc: '초고층 마천루와 시부야 스크램블, 신주쿠의 화려한 네온 상가가 가득합니다.', icon: 'fa-building-ngo' },
                    { title: '대중교통 네트워크', desc: '세계에서 가장 촘촘한 지하철/철도망으로 근교까지 원스톱 이동 가능.', icon: 'fa-train-subway' },
                    { title: '공원 & 사찰', desc: '아사쿠사 센소지, 메이지신궁, 신주쿠 교엔 등 조용하고 넓은 녹지가 공존.', icon: 'fa-torii-gate' }
                ],
                attractions: [
                    { name: '시부야 & 하라주쿠', desc: '트렌디한 패션, 젊음의 거리, 세계적인 시부야 스크램블 교차로.' },
                    { name: '아사쿠사 센소지', desc: '도쿄에서 가장 오래된 사찰로 고풍스러운 가미나리몬과 전통 상점가 연출.' },
                    { name: '긴자 & 롯폰기', desc: '럭셔리 브랜드 쇼핑몰과 미슐랭 레스토랑, 도쿄타워 야경 조망.' },
                    { name: '도쿄 디즈니 리조트', desc: '세계적인 수준의 디즈니랜드와 세계 유일의 디즈니씨 테마파크.' }
                ],
                food: '스시(초밥), 몬자야키, 아키하바라 이자카야, 도쿄식 라멘, 디저트 카페',
                season: '봄 (3~4월 벚꽃 시즌) / 가을 (10~11월 선선한 날씨)',
                tip: 'Suica나 Pasmo 실물/애플페이 교통카드를 미리 등록해두면 지하철 이동과 편의점 결제가 매우 편리합니다.'
            },
            {
                id: 'kyoto',
                name: '교토',
                englishName: 'Kyoto',
                region: '간사이 (Kansai)',
                category: 'culture',
                categoryLabel: '⛩️ 역사 & 전통',
                image: 'https://images.unsplash.com/photo-1493976040374-85c8e12f0c0e?auto=format&fit=crop&w=800&q=80',
                shortDesc: '천년 고도(古都)의 숨결, 유네스코 세계유산과 목조 가옥이 보존된 전통 도심',
                tagline: '붉은 도리이와 대나무 숲, 고즈넉한 젠(Zen) 정원이 펼쳐진 문화의 중심',
                envCards: [
                    { title: '전통 목조 건축물', desc: '기온 거리의 마치야(전통 가옥)와 수많은 사찰, 신사가 보존되어 있습니다.', icon: 'fa-house-chimney-window' },
                    { title: '자연과의 조화', desc: '아라시야마 대나무 숲과 카모강 수변 산책로가 시내 중심과 인접.', icon: 'fa-tree' },
                    { title: '고요함과 정운', desc: '다도 문화와 정갈한 가이세키 요리를 즐길 수 있는 고요한 분위기.', icon: 'fa-spa' }
                ],
                attractions: [
                    { name: '후시미 이나리 신사', desc: '산기슭을 따라 끊임없이 이어지는 수천 개의 주황색 도리이 길.' },
                    { name: '기요미즈데라 (청수사)', desc: '절벽 위에 세워진 웅장한 목조 툇마루에서 교토 시내를 한눈에 조망.' },
                    { name: '아라시야마 치쿠린', desc: '바람 소리가 낭만적인 울창한 대나무 숲길과 도게츠교 다리.' },
                    { name: '금각사 (킨카쿠지)', desc: '연못 위에 반짝이는 화려한 금박의 사찰과 연못 정원.' }
                ],
                food: '가이세키 정식, 말차(Matcha) 디저트, 교토식 유두부(두부요리), 소바',
                season: '가을 (11월 단풍 절정) / 봄 (4월 벚꽃)',
                tip: '인기 명소(청수사, 후시미 이나리)는 오전 8시 이전에 방문해야 한적하게 사진을 찍을 수 있습니다.'
            },
            {
                id: 'osaka',
                name: '오사카',
                englishName: 'Osaka',
                region: '간사이 (Kansai)',
                category: 'urban',
                categoryLabel: '🛍️ 미식 & 쇼핑',
                image: 'https://images.unsplash.com/photo-1590559899731-a382839e5549?auto=format&fit=crop&w=800&q=80',
                shortDesc: '활기찬 에너지, 글리코상 야경과 천하의 부엌이라 불리는 스트리트 푸드천국',
                tagline: '입이 즐거운 식도락 여행과 유니버설 스튜디오의 즐거움이 가득한 도시',
                envCards: [
                    { title: '화려한 네온 간판', desc: '도톤보리 운하 주변의 입체적인 상점 간판과 활기찬 밤거리.', icon: 'fa-lightbulb' },
                    { title: '운하와 친수 공간', desc: '도톤보리 강 크루즈 및 우메다 도심의 현대적 스카이라인.', icon: 'fa-water' },
                    { title: '개방적인 상인 문화', desc: '친근하고 활발한 현지인들과 활력 넘치는 시장 분위기.', icon: 'fa-comments' }
                ],
                attractions: [
                    { name: '도톤보리 & 난바', desc: '글리코상 전광판, 타코야키/쿠시카츠 가게가 밀집한 오사카의 심장.' },
                    { name: '유니버설 스튜디오 재팬(USJ)', desc: '해리포터, 슈퍼 닌텐도 월드 등 세계적 테마파크.' },
                    { name: '오사카성', desc: '웅장한 해자와 성벽, 계절마다 아름다운 성곽 공원.' },
                    { name: '우메다 스카이빌딩', desc: '360도 탁 트인 도심 전망을 감상하는 공중정원 전망대.' }
                ],
                food: '타코야키, 오코노미야키, 쿠시카츠(꼬치튀김), 하이볼, 호르몬 구이',
                season: '사계절 내내 방문하기 좋음 (봄 벚꽃, 가을 산책 추천)',
                tip: '주요 관광지와 지하철을 무료 이용할 수 있는 주유패스(Osaka Amazing Pass) 활용을 추천합니다.'
            },
            {
                id: 'sapporo',
                name: '삿포로 & 비에이',
                englishName: 'Sapporo & Biei',
                region: '홋카이도 (Hokkaido)',
                category: 'nature',
                categoryLabel: '❄️ 대자연 & 설경',
                image: 'https://images.unsplash.com/photo-1542051841857-5f90071e7989?auto=format&fit=crop&w=800&q=80',
                shortDesc: '웅장한 설원과 여름의 라벤더 밭, 신선한 해산물과 맥주의 고향',
                tagline: '겨울에는 하얀 눈꽃 세상, 여름에는 서늘하고 드넓은 꽃밭이 펼쳐지는 대자연',
                envCards: [
                    { title: '탁 트인 대자연', desc: '비에이의 언덕, 청의 호수, 드넓은 라벤더 밭 등 압도적 자연미.', icon: 'fa-snowflake' },
                    { title: '격자형 도심 구조', desc: '오도리 공원을 중심축으로 깨끗하고 정돈된 유럽풍 도시 구획.', icon: 'fa-border-all' },
                    { title: '풍부한 청정 식재료', desc: '낙농업과 신선한 북방 해산물이 풍부한 미식 환경.', icon: 'fa-cow' }
                ],
                attractions: [
                    { name: '비에이 & 후라노', desc: '청의 호수, 패치워크 언덕, 여름철 보랏빛 라벤더 밭 투어.' },
                    { name: '오타루 운하', desc: '고풍스러운 석조 창고와 가스등, 오르골당이 주는 로맨틱 분위기.' },
                    { name: '오도리 공원 & 눈축제', desc: '도심 한가운데 길게 늘어선 공원과 겨울 세계적 눈축제.' },
                    { name: '삿포로 맥주 박물관', desc: '일본 유일의 맥주 박물관과 시원한 생맥주 시음 경험.' }
                ],
                food: '징기스칸(양고기 구이), 삿포로 미소라메, 스프카레, 대게 요리, 유제품 디저트',
                season: '겨울 (12~2월 설경/스키) / 여름 (7~8월 꽃밭 & 서늘한 기후)',
                tip: '비에이와 후라노는 대중교통 이용이 어려울 수 있으므로 버스 일일투어나 렌터카 예약을 권장합니다.'
            },
            {
                id: 'fukuoka',
                name: '후쿠오카 & 유후인',
                englishName: 'Fukuoka & Yufuin',
                region: '규슈 (Kyushu)',
                category: 'onsen',
                categoryLabel: '♨️ 힐링 & 온천',
                image: 'https://images.unsplash.com/photo-1528164344705-47542687990d?auto=format&fit=crop&w=800&q=80',
                shortDesc: '비행시간 1시간 20분! 포장마차 거리와 고즈넉한 료칸 온천 힐링',
                tagline: '가까운 비행거리, 하카타 라멘의 본고장이자 아기자기한 온천 마을',
                envCards: [
                    { title: '온천 온구 & 료칸', desc: '유후인, 벳푸 등 자연 속 온천 가와 고즈넉한 전통 료칸 숙박.', icon: 'fa-hot-tub-person' },
                    { title: '콤팩트한 도시 동선', desc: '공항에서 시내(하카타)까지 지하철 10분 거리의 뛰어난 접근성.', icon: 'fa-plane-arrival' },
                    { title: '나카스 야타이(포장마차)', desc: '강변을 따라 형성된 감성 넘치는 야간 포장마차 문화.', icon: 'fa-utensils' }
                ],
                attractions: [
                    { name: '유후인 온천마을', desc: '유후다케 산 아래 물안개 피는 긴린코 호수와 아기자기한 상점가.' },
                    { name: '나카스 야타이 거리', desc: '강변 야경을 바라보며 라멘과 꼬치구이를 즐기는 야간 명소.' },
                    { name: '텐진 지하상가 & 쇼핑몰', desc: '캐널시티 하카타 분수쇼와 원스톱 도심 쇼핑가.' },
                    { name: '벳푸 지옥온천 순례', desc: '신기한 색깔의 온천수가 솟아오르는 지옥온천 체험.' }
                ],
                food: '돈코츠 라멘(하카타 라멘), 모츠나베(곱창전골), 미즈타키(닭한마리), 명란젓',
                season: '가을~겨울 (11월~3월 온천욕 최적기)',
                tip: '유후인 버스(유후인호)나 특급열차(유후인노모리)는 인기가 높아 출발 최소 1달 전 예약을 추천합니다.'
            },
            {
                id: 'okinawa',
                name: '오키나와',
                englishName: 'Okinawa',
                region: '오키나와 (Okinawa)',
                category: 'resort',
                categoryLabel: '🏖️ 휴양 & 에메랄드 바다',
                image: 'https://images.unsplash.com/photo-1507525428034-b723cf961d3e?auto=format&fit=crop&w=800&q=80',
                shortDesc: '동양의 하와이! 에메랄드빛 해변과 류큐 왕국의 독자적 휴양 문화',
                tagline: '스노클링, 드라이브 코스, 미국풍 거리가 어우러진 남국 아열대 리조트',
                envCards: [
                    { title: '에메랄드 해변 & 코랄', desc: '투명한 바다, 화이트 샌드, 다양한 해양 액티비티 환경.', icon: 'fa-umbrella-beach' },
                    { title: '해안 드라이브 코스', desc: '코우리 대교, 만좌모 등 탁 트인 바다 절경을 달리는 도로.', icon: 'fa-car-side' },
                    { title: '이국적 미·류큐 문화', desc: '아메리칸 빌리지와 류큐 왕국 유적의 독특한 이국적 분위기.', icon: 'fa-compact-disc' }
                ],
                attractions: [
                    { name: '츄라우미 수족관', desc: '거대한 고래상어가 헤엄치는 세계 최대급 기네스 수족관.' },
                    { name: '만좌모', desc: '코끼리 코 모양의 기암절벽과 시원한 아열대 잔디 언덕.' },
                    { name: '아메리칸 빌리지', desc: '미국 서해안 느낌의 쇼핑가, 관람차, 일몰 포인트.' },
                    { name: '코우리 대교', desc: '바다 위를 지르는 2km의 수려한 드라이브 다리.' }
                ],
                food: '오키나와 소바, 오키나와 흑돼지(아구), 타코라이스, 블루씰 아이스크림, 오리온 생맥주',
                season: '봄~가을 (5월~10월 수영 및 해양 스포츠 최적기)',
                tip: '대중교통이 제한적이므로 렌터카 여행이 필수적입니다 (국제운전면허증 사전 준비 필요).'
            },
            {
                id: 'hakone',
                name: '하코네',
                englishName: 'Hakone',
                region: '관동 (Kanto)',
                category: 'onsen',
                categoryLabel: '♨️ 온천 & 후지산 조망',
                image: 'https://images.unsplash.com/photo-1503899036084-c55cdd92da26?auto=format&fit=crop&w=800&q=80',
                shortDesc: '도쿄 근교의 국립공원! 후지산 전경과 아시노코 호수, 유황 온천',
                tagline: '로프웨이, 등산열차, 해적선을 타며 후지산을 감상하는 최고의 온천 리조트',
                envCards: [
                    { title: '화산 지형 & 유황천', desc: '오와쿠다니 화산 계곡의 자욱한 연기와 검은 달걀.', icon: 'fa-volcano' },
                    { title: '호수 & 후지산 뷰', desc: '아시노코 호수 위 해적선에서 감상하는 웅장한 후지산 전경.', icon: 'fa-mountain' },
                    { title: '자연 속 미술관', desc: '하코네 조각의 숲 미술관 등 자연과 조화된 문화 공간.', icon: 'fa-palette' }
                ],
                attractions: [
                    { name: '오와쿠다니 (대涌谷)', desc: '화산 활동의 증기를 눈앞에서 보고 수명을 늘려준다는 온천 달걀 시식.' },
                    { name: '아시노코 호수 해적선', desc: '호수 위를 유람하며 붉은 도리이와 후지산을 담는 대표 스팟.' },
                    { name: '하코네 조각의 숲', desc: '푸른 정원 속 야외에 전시된 세계적 작가들의 현대 조각품.' }
                ],
                food: '오와쿠다니 검은 달걀(쿠로타마고), 하코네 메밀국수(소바), 온천 만두',
                season: '가을 (10~11월 단풍과 후지산 선명함) / 겨울 (온천욕)',
                tip: '신주쿠에서 출발할 경우 교통수단을 무제한 이용할 수 있는 하코네 프리패스를 이용하세요.'
            },
            {
                id: 'nara',
                name: '나라',
                englishName: 'Nara',
                region: '간사이 (Kansai)',
                category: 'culture',
                categoryLabel: '🦌 역사 & 사슴 자연',
                image: 'https://images.unsplash.com/photo-1570077188670-e3a8d69ac5ff?auto=format&fit=crop&w=800&q=80',
                shortDesc: '자유롭게 거니는 사슴들과 거대한 대불상이 반겨주는 평화로운 고도',
                tagline: '사람과 사슴이 함께 어우러지는 고즈넉하고 평화로운 원시림 공원 환경',
                envCards: [
                    { title: '사슴들의 안식처', desc: '1,000마리가 넘는 야생 사슴들이 공원과 길가를 자유롭게 다니는 풍경.', icon: 'fa-paw' },
                    { title: '웅장한 불교 유적', desc: '세계 최대 목조건물 도다이지와 초대형 불상.', icon: 'fa-om' },
                    { title: '울창한 원시림', desc: '가스가타이샤 신사 주변 수백 년 된 등불과 삼림욕 코스.', icon: 'fa-leaf' }
                ],
                attractions: [
                    { name: '나라 사슴 공원', desc: '센베 과자를 사서 사슴들에게 나누어 주는 이색적인 경험.' },
                    { name: '도다이지 (동대사)', desc: '압도적인 크기의 목조 대웅전과 거대한 청동 대불상.' },
                    { name: '가스가타이샤', desc: '수많은 수석 석등과 붉은 기둥이 운치를 더하는 신사.' }
                ],
                food: '감잎 초밥(카키노하스시), 나라즈케(장아찌), 가키고리(빙수)',
                season: '봄 (사슴과 벚꽃) / 가을 (단풍 오솔길)',
                tip: '오사카나 교토에서 킨테츠 전철로 30~40분이면 올 수 있어 당일치기 여행으로 최적입니다.'
            }
        ];

        // Render City Cards
        function renderCities(data) {
            const grid = document.getElementById('cityGrid');
            const countBadge = document.getElementById('cityCountBadge');
            grid.innerHTML = '';

            countBadge.textContent = `${data.length}개 도시`;

            if(data.length === 0) {
                grid.innerHTML = `
                    <div class="col-span-full py-12 text-center text-slate-400">
                        <i class="fa-solid fa-compass text-4xl mb-3"></i>
                        <p class="text-sm">검색 결과가 없습니다. 다른 키워드로 검색해보세요.</p>
                    </div>
                `;
                return;
            }

            data.forEach(city => {
                const card = document.createElement('div');
                card.className = 'bg-white rounded-2xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-xl hover:-translate-y-1 transition-all duration-300 cursor-pointer flex flex-col group';
                card.onclick = () => openModal(city.id);

                card.innerHTML = `
                    <div class="relative h-48 overflow-hidden bg-slate-100">
                        <img src="${city.image}" alt="${city.name}" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500">
                        <div class="absolute inset-0 bg-gradient-to-t from-slate-950/80 via-transparent to-transparent"></div>
                        
                        <span class="absolute top-3 left-3 bg-slate-900/70 backdrop-blur-md text-white text-[10px] font-bold px-2.5 py-1 rounded-full border border-white/20">
                            ${city.region}
                        </span>

                        <div class="absolute bottom-3 left-3 right-3 text-white">
                            <h4 class="text-xl font-extrabold flex items-center justify-between">
                                ${city.name}
                                <span class="text-xs font-normal opacity-80">${city.englishName}</span>
                            </h4>
                        </div>
                    </div>

                    <div class="p-4 flex-grow flex flex-col justify-between space-y-3">
                        <p class="text-xs text-slate-600 line-clamp-2 leading-relaxed">
                            ${city.shortDesc}
                        </p>

                        <div class="pt-2 border-t border-slate-100 flex items-center justify-between text-xs">
                            <span class="text-slate-500 font-medium">${city.categoryLabel.split(' ')[0]} ${city.categoryLabel.split(' ')[1]}</span>
                            <span class="text-brand-red font-bold group-hover:translate-x-1 transition-transform flex items-center gap-1">
                                상세보기 <i class="fa-solid fa-chevron-right text-[10px]"></i>
                            </span>
                        </div>
                    </div>
                `;
                grid.appendChild(card);
            });
        }

        // Filter by Category
        let currentFilter = 'all';
        function filterCities(category) {
            currentFilter = category;
            
            // Update Active Filter UI
            document.querySelectorAll('.filter-btn').forEach(btn => {
                btn.classList.remove('bg-white', 'text-slate-900', 'shadow', 'active-filter');
                btn.classList.add('bg-slate-800', 'text-slate-300');
            });

            event.target.classList.remove('bg-slate-800', 'text-slate-300');
            event.target.classList.add('bg-white', 'text-slate-900', 'shadow', 'active-filter');

            applyFilters();
        }

        // Apply Search & Category Filters Combined
        function applyFilters() {
            const searchTerm = document.getElementById('searchInput').value.toLowerCase().trim();

            const filtered = citiesData.filter(city => {
                const matchesCategory = (currentFilter === 'all') || (city.category === currentFilter);
                const matchesSearch = city.name.toLowerCase().includes(searchTerm) ||
                                      city.englishName.toLowerCase().includes(searchTerm) ||
                                      city.region.toLowerCase().includes(searchTerm) ||
                                      city.shortDesc.toLowerCase().includes(searchTerm) ||
                                      city.food.toLowerCase().includes(searchTerm);

                return matchesCategory && matchesSearch;
            });

            renderCities(filtered);
        }

        // Search Input Listener
        document.getElementById('searchInput').addEventListener('input', applyFilters);

        // Open Modal Function
        function openModal(cityId) {
            const city = citiesData.find(c => c.id === cityId);
            if (!city) return;

            // Fill Hero
            document.getElementById('modalHero').style.backgroundImage = `url('${city.image}')`;
            document.getElementById('modalRegion').textContent = city.region;
            document.getElementById('modalVibeBadge').textContent = city.categoryLabel;
            document.getElementById('modalTitle').textContent = `${city.name} (${city.englishName})`;
            document.getElementById('modalTagline').textContent = city.tagline;

            // Fill Environment Grid
            const envGrid = document.getElementById('modalEnvGrid');
            envGrid.innerHTML = city.envCards.map(env => `
                <div class="bg-white p-3.5 rounded-2xl border border-slate-200 shadow-sm flex flex-col justify-between">
                    <div class="flex items-center gap-2 mb-1.5 text-brand-red font-bold text-xs sm:text-sm">
                        <i class="fa-solid ${env.icon} text-base"></i>
                        <span>${env.title}</span>
                    </div>
                    <p class="text-xs text-slate-600 leading-relaxed">${env.desc}</p>
                </div>
            `).join('');

            // Fill Attractions
            const attractionsContainer = document.getElementById('modalAttractions');
            attractionsContainer.innerHTML = city.attractions.map(attr => `
                <div class="bg-white p-3.5 rounded-2xl border border-slate-200 shadow-sm">
                    <div class="font-bold text-slate-800 text-xs sm:text-sm mb-1 flex items-center gap-1.5">
                        <span class="w-1.5 h-1.5 rounded-full bg-red-500"></span>
                        ${attr.name}
                    </div>
                    <p class="text-xs text-slate-500 leading-relaxed">${attr.desc}</p>
                </div>
            `).join('');

            // Fill Food, Season, Tip
            document.getElementById('modalFood').textContent = city.food;
            document.getElementById('modalSeason').textContent = city.season;
            document.getElementById('modalTip').textContent = city.tip;

            // Show Modal
            const modal = document.getElementById('cityModal');
            const modalContainer = document.getElementById('modalContainer');

            modal.classList.remove('opacity-0', 'pointer-events-none');
            modalContainer.classList.remove('scale-95');
            modalContainer.classList.add('scale-100');
            document.body.style.overflow = 'hidden';
        }

        // Close Modal
        function closeModal() {
            const modal = document.getElementById('cityModal');
            const modalContainer = document.getElementById('modalContainer');

            modal.classList.add('opacity-0', 'pointer-events-none');
            modalContainer.classList.remove('scale-100');
            modalContainer.classList.add('scale-95');
            document.body.style.overflow = '';
        }

        // Close on Esc key or Backdrop click
        window.addEventListener('keydown', (e) => {
            if (e.key === 'Escape') closeModal();
        });
        document.getElementById('cityModal').addEventListener('click', (e) => {
            if (e.target.id === 'cityModal') closeModal();
        });

        // Initialize on Load
        window.onload = function () {
            renderCities(citiesData);
        };
    </script>
</body>
</html>
