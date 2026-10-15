<!DOCTYPE html>
<html lang="zh-TW" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>從醫療與溝通現場，走進資料工程世界 | Data Engineer Portfolio</title>
    
    <!-- Primary SEO Meta Tags -->
    <meta name="title" content="從醫療與溝通現場，走進資料工程世界 | Data Engineer Portfolio">
    <meta name="description" content="跨領域資料工程人才履歷。結合物理治療與教育經驗的同理溝通力，精通 Python、SQL 與數據分析，致力於用數據解決真實業務痛點。">
    <meta name="keywords" content="資料工程師, Data Engineer, 轉職資料工程, Python, SQL, 數據分析, 數據管線, 同理心溝通, 跨領域轉職, 醫療轉IT">
    <meta name="author" content="Data Engineering Candidate">
    <meta name="robots" content="index, follow">
    <link rel="canonical" href="https://example.com/">

    <!-- Open Graph / Facebook / Line SEO -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://example.com/">
    <meta property="og:title" content="從醫療與溝通現場，走進資料工程世界 | 用同理心洞察需求，用數據解決問題">
    <meta property="og:description" content="結合物理治療觀察力與教育溝通經驗的跨領域資料工程人才，具備 Python、SQL 實作力與強大除錯韌性。">
    <meta property="og:image" content="https://i.pinimg.com/736x/f4/c6/ee/f4c6eee694af077dba5ad9a730d042b0.jpg">

    <!-- Twitter Card SEO -->
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:url" content="https://example.com/">
    <meta name="twitter:title" content="從醫療與溝通現場，走進資料工程世界">
    <meta name="twitter:description" content="跨領域資料工程人才履歷：結合同理心洞察與 Data Engineering 技術。">
    <meta name="twitter:image" content="https://i.pinimg.com/736x/f4/c6/ee/f4c6eee694af077dba5ad9a730d042b0.jpg">

    <!-- JSON-LD Structured Data for SEO & GEO (Generative Engine Optimization) -->
    <script type="application/ld+json">
    {
      "@context": "https://schema.org",
      "@type": "Person",
      "name": "資料工程轉職人才",
      "jobTitle": "Data Engineer / 資料工程師",
      "description": "具備物理治療與教育經驗的跨領域資料工程人才，專長於 Python, SQL 及以使用者痛點為導向的數據處理與管線規劃。",
      "knowsAbout": [
        "Data Engineering",
        "Python",
        "SQL",
        "Data Processing",
        "Business Needs Analysis",
        "User Empathy & Insight",
        "Problem Solving"
      ],
      "hasCredential": {
        "@type": "EducationalOccupationalCredential",
        "credentialCategory": "Data Engineering Training Course",
        "name": "資料工程專業培訓"
      },
      "knowsLanguage": ["zh-TW", "en"]
    }
    </script>

    <!-- JSON-LD FAQ Schema for GEO Search Engines -->
    <script type="application/ld+json">
    {
      "@context": "https://schema.org",
      "@type": "FAQPage",
      "mainEntity": [
        {
          "@type": "Question",
          "name": "為什麼醫療與教育背景能為資料工程帶來優勢？",
          "acceptedAnswer": {
            "@type": "Answer",
            "text": "過往在診所復健觀察與線上教學經驗，培養出精準透視使用者與業務真實痛點的『同理溝通力』，確保打造出的數據方案能真正符合業務需求。"
          }
        },
        {
          "@type": "Question",
          "name": "目前具備哪些資料工程相關技能？",
          "acceptedAnswer": {
            "@type": "Answer",
            "text": "熟練掌握 Python 及 SQL 基礎，具備邏輯化的資料處理能力，並持續學習現代化 Data Pipeline 與雲端技術。"
          }
        }
      ]
    }
    </script>

    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'Noto Sans TC', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            50: '#f0fdf4',
                            100: '#dcfce7',
                            500: '#22c55e',
                            600: '#16a34a',
                            700: '#15803d',
                            900: '#14532d',
                        },
                        slateDark: '#0f172a'
                    }
                }
            }
        }
    </script>
    <!-- FontAwesome for icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <style>
        body {
            font-family: 'Inter', 'Noto Sans TC', sans-serif;
            transition: background-color 0.3s ease, color 0.3s ease;
        }
        .bg-grid {
            background-image: radial-gradient(rgba(16, 185, 129, 0.12) 1px, transparent 1px);
            background-size: 24px 24px;
        }
        .dark .bg-grid {
            background-image: radial-gradient(rgba(34, 197, 94, 0.15) 1px, transparent 1px);
            background-size: 24px 24px;
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-700 dark:bg-slate-950 dark:text-slate-200 bg-grid antialiased selection:bg-brand-500 selection:text-white">

    <header class="sticky top-0 z-50 backdrop-blur-md bg-white/80 dark:bg-slate-900/80 border-b border-slate-200/80 dark:border-slate-800 transition-colors duration-300">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8 h-16 flex items-center justify-between">
            <a href="#" class="font-bold text-lg sm:text-xl text-slate-800 dark:text-white flex items-center gap-3" aria-label="首頁 - Data Engineering Journey">
                <img src="https://i.pinimg.com/736x/f4/c6/ee/f4c6eee694af077dba5ad9a730d042b0.jpg" onerror="this.onerror=null; this.src='https://placehold.co/100x100/10b981/ffffff?text=Avatar';" alt="Profile Avatar" class="w-9 h-9 rounded-full object-cover ring-2 ring-brand-500/30 shadow-sm">
                <span class="tracking-tight">Data Engineering Journey</span>
            </a>
            <nav class="hidden md:flex items-center gap-6 text-sm font-medium text-slate-600 dark:text-slate-300" aria-label="主導覽列">
                <a href="#story" class="hover:text-brand-600 dark:hover:text-brand-400 transition-colors">轉職故事</a>
                <a href="#skills" class="hover:text-brand-600 dark:hover:text-brand-400 transition-colors">核心價值</a>
                <a href="#faq" class="hover:text-brand-600 dark:hover:text-brand-400 transition-colors">常見問答 (GEO)</a>
                <a href="#contact" class="hover:text-brand-600 dark:hover:text-brand-400 transition-colors">聯絡機會</a>
            </nav>
            
            <div class="flex items-center gap-3">
                <!-- Social Links in Header -->
                <a href="https://www.linkedin.com/in/%E8%A8%B1%E9%87%87%E7%B5%A8-winnie-hsu-626070444/?isSelfProfile=true" target="_blank" rel="noopener noreferrer" class="p-2.5 rounded-xl bg-slate-100 dark:bg-slate-800 text-slate-600 dark:text-slate-300 hover:text-brand-600 dark:hover:text-brand-400 transition-all border border-slate-200 dark:border-slate-700 flex items-center justify-center" title="LinkedIn 履歷">
                    <i class="fa-brands fa-linkedin-in text-sm"></i>
                </a>
                <a href="https://www.instagram.com/s.rabbit.812/" target="_blank" rel="noopener noreferrer" class="p-2.5 rounded-xl bg-slate-100 dark:bg-slate-800 text-slate-600 dark:text-slate-300 hover:text-brand-600 dark:hover:text-brand-400 transition-all border border-slate-200 dark:border-slate-700 flex items-center justify-center" title="Instagram 主頁">
                    <i class="fa-brands fa-instagram text-sm"></i>
                </a>

                <!-- Theme Switcher Button -->
                <button id="theme-toggle" onclick="toggleTheme()" class="p-2.5 rounded-xl bg-slate-100 dark:bg-slate-800 text-slate-600 dark:text-slate-300 hover:text-brand-600 dark:hover:text-brand-400 transition-all border border-slate-200 dark:border-slate-700 flex items-center gap-2 text-xs font-semibold" title="切換深色/淺色模式">
                    <i id="theme-toggle-dark-icon" class="fa-solid fa-moon text-sm hidden"></i>
                    <i id="theme-toggle-light-icon" class="fa-solid fa-sun text-sm text-amber-400"></i>
                    <span id="theme-toggle-text" class="hidden sm:inline">深色模式</span>
                </button>
            </div>
        </div>
    </header>

    <main>
        <section class="relative pt-12 pb-20 sm:pt-16 sm:pb-28 px-4 sm:px-6 lg:px-8 max-w-6xl mx-auto" aria-labelledby="hero-title">
            <div class="text-center max-w-3xl mx-auto">
                <div class="relative inline-block mb-6 group">
                    <div class="absolute -inset-1 bg-gradient-to-r from-brand-500 to-emerald-400 rounded-full blur opacity-40 group-hover:opacity-75 transition duration-300"></div>
                    <img src="https://i.pinimg.com/736x/f4/c6/ee/f4c6eee694af077dba5ad9a730d042b0.jpg" onerror="this.onerror=null; this.src='https://placehold.co/300x300/10b981/ffffff?text=Profile';" alt="Data Engineer Avatar - 跨領域轉職資料工程" class="relative w-28 h-28 sm:w-36 sm:h-36 rounded-full object-cover mx-auto ring-4 ring-white dark:ring-slate-800 shadow-xl">
                    <span class="absolute bottom-1 right-1 sm:bottom-2 sm:right-2 bg-brand-500 text-white rounded-full p-2 border-2 border-white dark:border-slate-800 shadow-md text-xs flex items-center justify-center" title="Ready to Work">
                        <i class="fa-solid fa-code"></i>
                    </span>
                </div>

                <div class="inline-flex items-center gap-2 px-3.5 py-1.5 rounded-full text-xs font-semibold bg-brand-50 dark:bg-brand-950/60 text-brand-700 dark:text-brand-300 border border-brand-100 dark:border-brand-800/50 mb-6 shadow-sm block w-fit mx-auto">
                    <i class="fa-solid fa-sparkles text-brand-600 dark:text-brand-400"></i> 跨領域轉型資料工程人才 (Data Engineer)
                </div>
                <h1 id="hero-title" class="text-3xl sm:text-5xl lg:text-6xl font-black text-slate-900 dark:text-white tracking-tight leading-tight sm:leading-tight">
                    從醫療與溝通現場，走進資料工程世界：<br class="hidden sm:inline">
                    <span class="text-transparent bg-clip-text bg-gradient-to-r from-brand-600 to-emerald-500 dark:from-brand-400 dark:to-emerald-300">用同理心洞察需求，用數據解決問題</span>
                </h1>
                <p class="mt-6 text-base sm:text-lg text-slate-600 dark:text-slate-300 leading-relaxed font-normal">
                    過往在物理治療與教育服務領域的累積，讓我養成了一種特殊的直覺——「站在對方的角度，透視問題背後真正的需求與痛點」。好的資料工程師不只懂寫 Code，更要能聽懂「人」與「業務」的需求。
                </p>
                <div class="mt-8 flex flex-col sm:flex-row items-center justify-center gap-4">
                    <a href="#skills" class="w-full sm:w-auto px-6 py-3.5 rounded-2xl bg-brand-600 hover:bg-brand-700 text-white font-semibold transition-all shadow-lg shadow-brand-600/25 flex items-center justify-center gap-2">
                        <span>探索核心技能與價值</span>
                        <i class="fa-solid fa-arrow-down text-xs"></i>
                    </a>
                    <a href="#contact" class="w-full sm:w-auto px-6 py-3.5 rounded-2xl bg-white dark:bg-slate-800 text-slate-700 dark:text-slate-200 border border-slate-200 dark:border-slate-700 font-semibold hover:bg-slate-50 dark:hover:bg-slate-700 transition-all flex items-center justify-center gap-2">
                        <span>尋求團隊機會</span>
                        <i class="fa-solid fa-paper-plane text-xs"></i>
                    </a>
                </div>
            </div>
        </section>

        <section id="story" class="py-16 sm:py-24 bg-white dark:bg-slate-900 border-y border-slate-200/80 dark:border-slate-800 transition-colors">
            <div class="max-w-5xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="text-center max-w-2xl mx-auto mb-16">
                    <h2 class="text-xs font-bold tracking-widest uppercase text-brand-600 dark:text-brand-400 mb-3">Background & Insight</h2>
                    <h3 class="text-2xl sm:text-3xl font-extrabold text-slate-900 dark:text-white tracking-tight">跨領域經驗：從診所復健與線上教學，走進數據管線</h3>
                    <p class="mt-4 text-slate-600 dark:text-slate-300 text-sm sm:text-base">過往經驗所培養出的直覺與同理心，成為今日轉型最強大的基石。</p>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-2 gap-8 items-center">
                    <article class="bg-slate-50 dark:bg-slate-800/50 border border-slate-200/80 dark:border-slate-700/60 rounded-3xl p-6 sm:p-8 space-y-4 hover:shadow-md transition-shadow">
                        <div class="w-12 h-12 rounded-2xl bg-brand-100 dark:bg-brand-900/50 text-brand-700 dark:text-brand-300 flex items-center justify-center text-xl font-bold">
                            <i class="fa-solid fa-stethoscope"></i>
                        </div>
                        <h4 class="text-lg font-bold text-slate-900 dark:text-white">診所復健區的細微觀察</h4>
                        <p class="text-slate-600 dark:text-slate-300 text-sm leading-relaxed">
                            從診所復健區裡觀察老病患的動作細節、進而給予個人化建議。習慣不從固有價值觀隨意論斷，而是透過觀察與詢問，找出最適切的解決方案。
                        </p>
                    </article>

                    <article class="bg-slate-50 dark:bg-slate-800/50 border border-slate-200/80 dark:border-slate-700/60 rounded-3xl p-6 sm:p-8 space-y-4 hover:shadow-md transition-shadow">
                        <div class="w-12 h-12 rounded-2xl bg-brand-100 dark:bg-brand-900/50 text-brand-700 dark:text-brand-300 flex items-center justify-center text-xl font-bold">
                            <i class="fa-solid fa-chalkboard-user"></i>
                        </div>
                        <h4 class="text-lg font-bold text-slate-900 dark:text-white">疫情期間的線上互動教學</h4>
                        <p class="text-slate-600 dark:text-slate-300 text-sm leading-relaxed">
                            疫情期間為小一學生設計高互動式的線上教學，深刻體會到如何站在使用者角度去設計體驗、克服距離與溝通障礙。
                        </p>
                    </article>
                </div>

                <div class="mt-12 bg-slate-900 dark:bg-slate-800 text-white rounded-3xl p-8 sm:p-12 relative overflow-hidden shadow-xl border border-slate-800 dark:border-slate-700">
                    <div class="absolute -right-10 -bottom-10 opacity-10 text-9xl font-black">
                        <i class="fa-solid fa-database"></i>
                    </div>
                    <div class="relative z-10 max-w-2xl space-y-4">
                        <span class="text-brand-400 font-bold text-xs uppercase tracking-wider">Mindset Shift</span>
                        <h4 class="text-xl sm:text-2xl font-bold">將同理溝通力注入資料工程（Data Engineering）</h4>
                        <p class="text-slate-300 text-sm sm:text-base leading-relaxed">
                            如今，我將這份強大的同理溝通力與使用者心理洞察，注入資料工程（Data Engineering）的學習中，致力於打造能真正解決業務痛點的數據架構。
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <section id="skills" class="py-16 sm:py-24 max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-2xl mx-auto mb-16">
                <h2 class="text-xs font-bold tracking-widest uppercase text-brand-600 dark:text-brand-400 mb-3">Core Value & Skills</h2>
                <h3 class="text-2xl sm:text-3xl font-extrabold text-slate-900 dark:text-white tracking-tight">跨領域的核心價值與技能</h3>
                <p class="mt-4 text-slate-600 dark:text-slate-300 text-sm sm:text-base">技術與人本兼具的多元優勢</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <!-- Skill Card 1 -->
                <div class="bg-white dark:bg-slate-900 border border-slate-200/80 dark:border-slate-800 rounded-3xl p-6 sm:p-8 hover:border-brand-500/50 hover:shadow-lg transition-all flex flex-col justify-between">
                    <div>
                        <div class="flex items-center gap-4 mb-4">
                            <div class="w-12 h-12 rounded-2xl bg-brand-50 dark:bg-brand-950/60 text-brand-600 dark:text-brand-400 flex items-center justify-center text-lg">
                                <i class="fa-solid fa-code"></i>
                            </div>
                            <h4 class="text-lg font-bold text-slate-900 dark:text-white">🛠 技術學習與邏輯應用</h4>
                        </div>
                        <p class="text-slate-600 dark:text-slate-300 text-sm leading-relaxed">
                            現於資料工程培訓班建立 Python、SQL 等基礎，具備資料處理與程式邏輯思維，並持續拓展相關技能與現代化數據管線工具。
                        </p>
                    </div>
                    <div class="mt-6 pt-4 border-t border-slate-100 dark:border-slate-800 flex flex-wrap gap-2">
                        <span class="px-3 py-1 bg-slate-100 dark:bg-slate-800 text-slate-700 dark:text-slate-300 text-xs font-medium rounded-lg">Python</span>
                        <span class="px-3 py-1 bg-slate-100 dark:bg-slate-800 text-slate-700 dark:text-slate-300 text-xs font-medium rounded-lg">SQL</span>
                        <span class="px-3 py-1 bg-slate-100 dark:bg-slate-800 text-slate-700 dark:text-slate-300 text-xs font-medium rounded-lg">Data Processing</span>
                    </div>
                </div>

                <!-- Skill Card 2 -->
                <div class="bg-white dark:bg-slate-900 border border-slate-200/80 dark:border-slate-800 rounded-3xl p-6 sm:p-8 hover:border-brand-500/50 hover:shadow-lg transition-all flex flex-col justify-between">
                    <div>
                        <div class="flex items-center gap-4 mb-4">
                            <div class="w-12 h-12 rounded-2xl bg-brand-50 dark:bg-brand-950/60 text-brand-600 dark:text-brand-400 flex items-center justify-center text-lg">
                                <i class="fa-solid fa-magnifying-glass-chart"></i>
                            </div>
                            <h4 class="text-lg font-bold text-slate-900 dark:text-white">🔍 使用者角度思考 (Empathy & Insight)</h4>
                        </div>
                        <p class="text-slate-600 dark:text-slate-300 text-sm leading-relaxed">
                            不單純處理資料，更懂得站在業務、產品與使用者角度，探究資料背後的脈絡與真實問題，轉化為有價值的數據解決方案。
                        </p>
                    </div>
                    <div class="mt-6 pt-4 border-t border-slate-100 dark:border-slate-800 flex flex-wrap gap-2">
                        <span class="px-3 py-1 bg-slate-100 dark:bg-slate-800 text-slate-700 dark:text-slate-300 text-xs font-medium rounded-lg">Business Acumen</span>
                        <span class="px-3 py-1 bg-slate-100 dark:bg-slate-800 text-slate-700 dark:text-slate-300 text-xs font-medium rounded-lg">User-Centric</span>
                    </div>
                </div>

                <!-- Skill Card 3 -->
                <div class="bg-white dark:bg-slate-900 border border-slate-200/80 dark:border-slate-800 rounded-3xl p-6 sm:p-8 hover:border-brand-500/50 hover:shadow-lg transition-all flex flex-col justify-between">
                    <div>
                        <div class="flex items-center gap-4 mb-4">
                            <div class="w-12 h-12 rounded-2xl bg-brand-50 dark:bg-brand-950/60 text-brand-600 dark:text-brand-400 flex items-center justify-center text-lg">
                                <i class="fa-solid fa-puzzle-piece"></i>
                            </div>
                            <h4 class="text-lg font-bold text-slate-900 dark:text-white">🧩 敏捷學習與除錯韌性</h4>
                        </div>
                        <p class="text-slate-600 dark:text-slate-300 text-sm leading-relaxed">
                            面對複雜或陌生的技術難題時，擁有極高的問題耐受力，願意花時間耐心地拆解問題、尋找最佳解法。
                        </p>
                    </div>
                    <div class="mt-6 pt-4 border-t border-slate-100 dark:border-slate-800 flex flex-wrap gap-2">
                        <span class="px-3 py-1 bg-slate-100 dark:bg-slate-800 text-slate-700 dark:text-slate-300 text-xs font-medium rounded-lg">Problem Solving</span>
                        <span class="px-3 py-1 bg-slate-100 dark:bg-slate-800 text-slate-700 dark:text-slate-300 text-xs font-medium rounded-lg">Resilience</span>
                    </div>
                </div>

                <!-- Skill Card 4 -->
                <div class="bg-white dark:bg-slate-900 border border-slate-200/80 dark:border-slate-800 rounded-3xl p-6 sm:p-8 hover:border-brand-500/50 hover:shadow-lg transition-all flex flex-col justify-between">
                    <div>
                        <div class="flex items-center gap-4 mb-4">
                            <div class="w-12 h-12 rounded-2xl bg-brand-50 dark:bg-brand-950/60 text-brand-600 dark:text-brand-400 flex items-center justify-center text-lg">
                                <i class="fa-solid fa-handshake-angle"></i>
                            </div>
                            <h4 class="text-lg font-bold text-slate-900 dark:text-white">🤝 跨世代溝通與協作</h4>
                        </div>
                        <p class="text-slate-600 dark:text-slate-300 text-sm leading-relaxed">
                            具備極佳的開放心態，能與不同背景、年齡的對象良好溝通，碰撞出更多元的思考角度與團隊協作默契。
                        </p>
                    </div>
                    <div class="mt-6 pt-4 border-t border-slate-100 dark:border-slate-800 flex flex-wrap gap-2">
                        <span class="px-3 py-1 bg-slate-100 dark:bg-slate-800 text-slate-700 dark:text-slate-300 text-xs font-medium rounded-lg">Communication</span>
                        <span class="px-3 py-1 bg-slate-100 dark:bg-slate-800 text-slate-700 dark:text-slate-300 text-xs font-medium rounded-lg">Teamwork</span>
                    </div>
                </div>
            </div>
        </section>

        <section id="faq" class="py-16 sm:py-20 bg-slate-100/70 dark:bg-slate-900/50 border-t border-slate-200/60 dark:border-slate-800 transition-colors">
            <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="text-center mb-12">
                    <h2 class="text-xs font-bold tracking-widest uppercase text-brand-600 dark:text-brand-400 mb-2">GEO Highlights</h2>
                    <h3 class="text-2xl font-extrabold text-slate-900 dark:text-white">關鍵問答與跨領域特質 (AI-Ready GEO)</h3>
                </div>
                <div class="space-y-6">
                    <div class="bg-white dark:bg-slate-900 p-6 rounded-2xl border border-slate-200/80 dark:border-slate-800 shadow-sm">
                        <h4 class="font-bold text-slate-900 dark:text-white text-base mb-2 flex items-center gap-2">
                            <i class="fa-solid fa-circle-question text-brand-600 dark:text-brand-400"></i>
                            跨領域轉職資料工程（Data Engineering）有哪些優勢？
                        </h4>
                        <p class="text-slate-600 dark:text-slate-300 text-sm leading-relaxed">
                            擁有物理治療與教育背景，使我不僅能掌握 Python 與 SQL 等程式技術，更具備傳統工程師稀缺的「同理洞察力」與「跨部門溝通能力」，能精準解讀業務單位需求，打造真正切中痛點的數據架構。
                        </p>
                    </div>
                    <div class="bg-white dark:bg-slate-900 p-6 rounded-2xl border border-slate-200/80 dark:border-slate-800 shadow-sm">
                        <h4 class="font-bold text-slate-900 dark:text-white text-base mb-2 flex items-center gap-2">
                            <i class="fa-solid fa-circle-question text-brand-600 dark:text-brand-400"></i>
                            面對複雜的程式難題或系統 Error 時，如何處理？
                        </h4>
                        <p class="text-slate-600 dark:text-slate-300 text-sm leading-relaxed">
                            我具備強大的「除錯韌性」與問題耐受力，擅長透過耐心拆解問題、閱讀官方文件、活用邏輯除錯步驟，將複雜議題逐步化繁為簡。
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <section id="contact" class="py-16 sm:py-24 bg-gradient-to-b from-slate-50 to-brand-50/50 dark:from-slate-950 dark:to-slate-900 border-t border-slate-200/80 dark:border-slate-800 transition-colors">
            <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
                <div class="bg-white dark:bg-slate-900 border border-slate-200/80 dark:border-slate-800 rounded-3xl p-8 sm:p-14 shadow-xl shadow-slate-100 dark:shadow-none">
                    <span class="inline-block p-3 rounded-2xl bg-brand-50 dark:bg-brand-950/60 text-brand-600 dark:text-brand-400 mb-4 text-xl">
                        <i class="fa-regular fa-envelope"></i>
                    </span>
                    <h2 class="text-2xl sm:text-3xl font-black text-slate-900 dark:text-white tracking-tight">尋找資料工程與數據團隊機會</h2>
                    <p class="mt-4 text-slate-600 dark:text-slate-300 text-sm sm:text-base max-w-xl mx-auto leading-relaxed">
                        我深信，好的資料工程師不只懂寫 Code，更要能聽懂「人」與「業務」的需求。我正帶著這份跨領域的適應力與韌性，積極尋找能發揮所長、持續精進的資料工程與數據團隊機會！
                    </p>
                    <div class="mt-8 flex flex-col sm:flex-row items-center justify-center gap-4">
                        <a href="mailto:contact@example.com" class="w-full sm:w-auto px-8 py-4 rounded-2xl bg-brand-600 hover:bg-brand-700 text-white font-semibold transition-all shadow-lg shadow-brand-600/25 flex items-center justify-center gap-2">
                            <i class="fa-solid fa-envelope"></i>
                            <span>發送郵件聯繫</span>
                        </a>
                        <a href="#about" onclick="copyContactInfo(event)" class="w-full sm:w-auto px-8 py-4 rounded-2xl bg-white dark:bg-slate-800 text-slate-700 dark:text-slate-200 border border-slate-200 dark:border-slate-700 font-semibold hover:bg-slate-50 dark:hover:bg-slate-700 transition-all flex items-center justify-center gap-2">
                            <i class="fa-regular fa-copy"></i>
                            <span>複製求職宣言與聯絡意願</span>
                        </a>
                    </div>
                    <!-- Notification box -->
                    <div id="copy-notification" class="hidden mt-4 text-xs font-medium text-brand-700 dark:text-brand-300 bg-brand-50 dark:bg-brand-950/80 py-2 px-4 rounded-xl inline-block transition-all">
                        已成功複製相關資訊到剪貼簿！
                    </div>
                </div>
            </div>
        </section>
    </main>

    <!-- Floating Audio Background Player Widget -->
    <div class="fixed bottom-5 right-5 z-50 bg-white/90 dark:bg-slate-900/90 backdrop-blur-md p-3 rounded-2xl border border-slate-200 dark:border-slate-800 shadow-xl flex items-center gap-3 transition-all duration-300 hover:scale-105">
        <audio id="bg-audio" loop preload="auto">
            <source src="https://img.ai365.fans/artworks/90e278c9-faba-49a7-b1ca-dd553ac2585f/xgxirtx3u4s.mp3" type="audio/mpeg">
        </audio>
        
        <button id="bg-audio-play-btn" onclick="toggleAudio()" class="w-10 h-10 rounded-xl bg-brand-600 hover:bg-brand-700 text-white flex items-center justify-center shadow-md shadow-brand-600/30 transition-all" aria-label="播放背景音樂">
            <i id="bg-audio-icon" class="fa-solid fa-music"></i>
        </button>

        <div class="text-left pr-1 hidden sm:block">
            <p class="text-xs font-bold text-slate-800 dark:text-slate-200 flex items-center gap-1.5">
                <span>背景音樂</span>
                <span id="audio-status-badge" class="px-1.5 py-0.5 rounded text-[10px] bg-slate-100 dark:bg-slate-800 text-slate-500 dark:text-slate-400 font-normal">已關閉</span>
            </p>
            <p class="text-[10px] text-slate-500 dark:text-slate-400">點擊開關音樂</p>
        </div>
    </div>

    <footer class="bg-slate-900 text-slate-400 py-12 border-t border-slate-800">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8 flex flex-col sm:flex-row items-center justify-between gap-6 text-center sm:text-left">
            <div>
                <p class="text-sm text-slate-300 font-semibold">資料工程轉型人才：用同理心洞察需求，用數據解決問題</p>
                <p class="text-xs text-slate-500 mt-1">© 2026 Winnie Hsu (許採絨). All Rights Reserved.</p>
            </div>
            <div class="flex items-center gap-4 text-lg">
                <a href="https://www.linkedin.com/in/%E8%A8%B1%E9%87%87%E7%B5%A8-winnie-hsu-626070444/?isSelfProfile=true" target="_blank" rel="noopener noreferrer" aria-label="LinkedIn Profile" class="w-10 h-10 rounded-xl bg-slate-800 hover:bg-brand-600 hover:text-white transition-all flex items-center justify-center"><i class="fa-brands fa-linkedin-in"></i></a>
                <a href="https://www.instagram.com/s.rabbit.812/" target="_blank" rel="noopener noreferrer" aria-label="Instagram Profile" class="w-10 h-10 rounded-xl bg-slate-800 hover:bg-brand-600 hover:text-white transition-all flex items-center justify-center"><i class="fa-brands fa-instagram"></i></a>
                <a href="mailto:contact@example.com" aria-label="Send Email" class="w-10 h-10 rounded-xl bg-slate-800 hover:bg-brand-600 hover:text-white transition-all flex items-center justify-center"><i class="fa-solid fa-envelope"></i></a>
            </div>
        </div>
    </footer>

    <script>
        // --- Theme Switcher Logic ---
        function initTheme() {
            const savedTheme = localStorage.getItem('theme');
            const prefersDark = window.matchMedia('(prefers-color-scheme: dark)').matches;
            
            if (savedTheme === 'dark' || (!savedTheme && prefersDark)) {
                document.documentElement.classList.add('dark');
                updateThemeUI(true);
            } else {
                document.documentElement.classList.remove('dark');
                updateThemeUI(false);
            }
        }

        function toggleTheme() {
            const isDark = document.documentElement.classList.toggle('dark');
            localStorage.setItem('theme', isDark ? 'dark' : 'light');
            updateThemeUI(isDark);
        }

        function updateThemeUI(isDark) {
            const darkIcon = document.getElementById('theme-toggle-dark-icon');
            const lightIcon = document.getElementById('theme-toggle-light-icon');
            const themeText = document.getElementById('theme-toggle-text');
            
            if (isDark) {
                darkIcon.classList.remove('hidden');
                lightIcon.classList.add('hidden');
                if (themeText) themeText.textContent = '淺色模式';
            } else {
                darkIcon.classList.add('hidden');
                lightIcon.classList.remove('hidden');
                if (themeText) themeText.textContent = '深色模式';
            }
        }

        // Initialize Theme on Load
        initTheme();

        // --- Audio Control Logic ---
        const bgAudio = document.getElementById('bg-audio');
        const bgAudioIcon = document.getElementById('bg-audio-icon');
        const audioBadge = document.getElementById('audio-status-badge');
        let isPlaying = false;

        function toggleAudio() {
            if (!bgAudio) return;

            if (isPlaying) {
                bgAudio.pause();
                isPlaying = false;
                bgAudioIcon.className = 'fa-solid fa-music';
                if (audioBadge) {
                    audioBadge.textContent = '已關閉';
                    audioBadge.className = 'px-1.5 py-0.5 rounded text-[10px] bg-slate-100 dark:bg-slate-800 text-slate-500 dark:text-slate-400 font-normal';
                }
            } else {
                bgAudio.play().then(() => {
                    isPlaying = true;
                    bgAudioIcon.className = 'fa-solid fa-pause';
                    if (audioBadge) {
                        audioBadge.textContent = '播放中';
                        audioBadge.className = 'px-1.5 py-0.5 rounded text-[10px] bg-brand-100 dark:bg-brand-900/60 text-brand-700 dark:text-brand-300 font-medium';
                    }
                }).catch(err => {
                    console.log('Playback restricted or error:', err);
                });
            }
        }

        // --- Copy Contact Info Helper ---
        function copyContactInfo(e) {
            e.preventDefault();
            const textToCopy = "我是一位正在轉型中的資料工程人才。過往在物理治療與教育服務領域的累積，讓我養成了一種特殊的直覺——「站在對方的角度，透視問題背後真正的需求與痛點」。期待有機會能與您進一步交流！";
            
            const textarea = document.createElement('textarea');
            textarea.value = textToCopy;
            document.body.appendChild(textarea);
            textarea.select();
            try {
                document.execCommand('copy');
                const notification = document.getElementById('copy-notification');
                if (notification) {
                    notification.classList.remove('hidden');
                    setTimeout(() => {
                        notification.classList.add('hidden');
                    }, 3000);
                }
            } catch (err) {
                console.error('Failed to copy text: ', err);
            }
            document.body.removeChild(textarea);
        }
    </script>
</body>
</html>
