y<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="google-site-verification" content="3Ye8EB8q06-GVWsDOecPR1pqfbkIE7IvJvS-MMJNa9o" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SABRY ELHADIDY | Ultimate Bodybuilding & Analytics Platform</title>
    <meta name="description" content="منصة الحديدي المتكاملة لكمال الأجسام والتحليلات الرياضية - حسابات التغذية، دليل تشريح العضلات، ومتابعة البدلاء مع صبري الحديدي.">
    <meta name="keywords" content="صبري الحديدي, الحديدي, كمال أجسام, جيم, تشريح العضلات, حساب السعرات, elhadidy-iron, bodybuilding, fitness Egypt">
    <meta name="author" content="Sabry Elhadidy">

    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700;900&family=Cairo:wght@300;400;600;700;900&family=Oswald:wght@400;600;700&family=Montserrat:wght@300;400;600;700&display=swap" rel="stylesheet">

    <style>
        :root {
            --gold: #C9A84C;
            --gold-light: #E8C96A;
            --gold-dark: #9A7A30;
            --black: #050505;
            --dark: #0D0D0D;
            --card: #141414;
            --card2: #1A1A1A;
            --white: #F5F0E8;
            --grey: #888;
            --secondary-red: #ff0000;
            --accent-orange: #ff6b00;
            --accent-gold: #ffa726;
            --dragon-glow: rgba(255, 0, 0, 0.25);
            --success: #00ff66;
        }

        * { margin: 0; padding: 0; box-sizing: border-box; scroll-behavior: smooth; }

        body {
            background: var(--black);
            color: var(--white);
            font-family: 'Cairo', sans-serif;
            direction: rtl;
            overflow-x: hidden;
            line-height: 1.6;
            padding-bottom: 60px;
        }

        h1, h2, h3, h4, .logo, .nav-btn {
            font-family: 'Oswald', 'Cairo', sans-serif;
            text-transform: uppercase;
        }

        .container { width: 90%; max-width: 1200px; margin: 0 auto; }

        /* ===== TOP BAR & HEADER ===== */
        .top-bar {
            background-color: #000;
            border-bottom: 1px solid #111;
            padding: 10px 0;
            font-size: 0.85rem;
        }
        .bar-flex { display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap; gap: 8px; }
        .brand-owner { font-weight: bold; color: var(--accent-gold); letter-spacing: 1px; }
        .brand-phone { color: #fff; text-decoration: none; font-weight: bold; transition: 0.3s; }
        .brand-phone:hover { color: var(--success); }

        .main-header {
            background-color: rgba(5, 5, 5, 0.95);
            border-bottom: 2px solid var(--secondary-red);
            position: sticky; top: 0; z-index: 1000; padding: 15px 0;
            box-shadow: 0 4px 20px var(--dragon-glow);
        }
        .header-flex { display: flex; justify-content: space-between; align-items: center; }
        .logo { font-size: 1.8rem; color: #fff; text-decoration: none; font-weight: 700; }
        .logo span { color: var(--secondary-red); }
        .logo i { color: var(--accent-orange); margin-right: 5px; }

        /* ===== COVER / HERO ===== */
        .cover {
            min-height: 80vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            text-align: center;
            padding: 60px 40px;
            position: relative;
            background: radial-gradient(ellipse at 50% 30%, #2a0808 0%, #050505 70%);
            overflow: hidden;
        }
        .cover-badge {
            font-family: 'Oswald', sans-serif;
            font-size: 13px;
            letter-spacing: 6px;
            color: var(--accent-gold);
            text-transform: uppercase;
            border: 1px solid var(--secondary-red);
            padding: 8px 24px;
            margin-bottom: 35px;
        }
        .cover-title-ar { font-size: clamp(36px, 7vw, 75px); font-weight: 900; color: #fff; line-height: 1.1; }
        .text-gradient {
            background: linear-gradient(45deg, var(--secondary-red), var(--accent-orange));
            -webkit-background-clip: text; -webkit-text-fill-color: transparent;
            background-clip: text;
        }
        .cover-divider {
            width: 200px; height: 2px;
            background: linear-gradient(90deg, transparent, var(--secondary-red), transparent);
            margin: 25px auto;
        }
        .cover-subtitle { font-size: 18px; opacity: 0.8; font-style: italic; margin-bottom: 40px; }

        /* ===== BUTTONS ===== */
        .btn {
            display: inline-flex; align-items: center; gap: 10px; padding: 14px 32px;
            font-family: 'Oswald', sans-serif; font-weight: 600; text-transform: uppercase;
            text-decoration: none; transition: all 0.3s; cursor: pointer; border: none;
        }
        .btn-primary { background: linear-gradient(135deg, var(--secondary-red), var(--accent-orange)); color: #fff; }
        .btn-primary:hover { transform: translateY(-3px); box-shadow: 0 8px 25px rgba(255,0,0,0.5); }
        .btn-outline { background: transparent; color: #fff; border: 2px solid #fff; margin-right: 10px; }
        .btn-outline:hover { background: #fff; color: #000; }
        .btn-full { width: 100%; justify-content: center; }
        .btn-danger { background: var(--secondary-red); color: #fff; padding: 6px 12px; font-size: 12px; border-radius: 4px; border: none; cursor: pointer; }
        .btn-danger:hover { background: #b30000; }

        /* ===== GENERAL SECTIONS ===== */
        .section-padding { padding: 80px 0; }
        .section-header { text-align: center; margin-bottom: 50px; }
        .section-tag { font-family: 'Oswald', sans-serif; font-size: 12px; letter-spacing: 5px; color: var(--accent-gold); margin-bottom: 12px; display: block; }
        .section-title { font-size: 2.8rem; font-weight: 900; margin-bottom: 10px; }
        .line-accent { width: 100px; height: 4px; background: linear-gradient(90deg, var(--secondary-red), var(--accent-gold)); margin: 15px auto; }
        h2.h2-style { font-size: 24px; font-weight: 700; color: var(--accent-gold); margin: 40px 0 20px; padding-right: 16px; border-right: 4px solid var(--secondary-red); }
        p.body-text { font-size: 16px; line-height: 1.9; color: rgba(255,255,255,0.8); margin-bottom: 16px; text-align: justify; }

        /* ===== TRACKER FORM ===== */
        .tracker-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(180px, 1fr)); gap: 15px; margin-bottom: 20px; }

        /* ===== TIMER GRAPHICS ===== */
        .timer-display { font-size: 4.5rem; font-family: 'Oswald', sans-serif; font-weight: bold; color: var(--success); text-align: center; margin: 20px 0; letter-spacing: 2px; text-shadow: 0 0 15px rgba(0, 255, 102, 0.4); }
        .timer-preset-btns { display: flex; gap: 10px; justify-content: center; margin-bottom: 20px; flex-wrap: wrap; }
        .btn-preset { background: #222; color: #fff; border: 1px solid #333; padding: 10px 18px; cursor: pointer; font-size: 14px; transition: 0.3s; }
        .btn-preset:hover, .btn-preset.active { background: var(--success); color: #000; border-color: var(--success); font-weight: bold; box-shadow: 0 0 10px rgba(0, 255, 102, 0.3); }

        /* ===== RESCUE ENGINE ===== */
        .rescue-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 15px; margin-bottom: 30px; }
        .rescue-node {
            background: var(--card); border: 1px solid #222; padding: 20px; text-align: center;
            border-radius: 6px; cursor: pointer; transition: all 0.3s ease;
        }
        .rescue-node:hover { border-color: var(--accent-orange); background: #1a1a1a; transform: translateY(-3px); }
        .rescue-node i { font-size: 2rem; color: var(--accent-gold); margin-bottom: 10px; display: block; }
        .rescue-node h3 { font-size: 16px; color: #fff; }

        .rescue-panel {
            background: #090909; border: 2px dashed var(--accent-orange); border-radius: 6px; padding: 25px;
            margin-top: 25px; display: none; animation: fadeIn 0.4s ease-in-out;
        }
        @keyframes fadeIn { from { opacity: 0; } to { opacity: 1; } }

        /* ===== INFO BOX & TABLES ===== */
        .info-box {
            background: var(--card); border: 1px solid #222; border-right: 4px solid var(--secondary-red);
            padding: 24px; margin: 32px 0; border-radius: 4px;
        }
        .info-box .box-title { font-size: 18px; font-weight: 700; color: var(--accent-gold); margin-bottom: 8px; }
        .tbl-wrap { overflow-x: auto; margin: 24px 0; border-radius: 6px; border: 1px solid #222; }
        table.tbl { width: 100%; border-collapse: collapse; font-size: 15px; min-width: 600px; }
        table.tbl thead tr { background: #000; }
        table.tbl thead th { padding: 14px; color: var(--accent-gold); border-bottom: 2px solid var(--secondary-red); }
        table.tbl tbody tr:nth-child(odd) { background: var(--card); }
        table.tbl tbody tr:nth-child(even) { background: var(--card2); }
        table.tbl tbody td { padding: 13px; text-align: center; border-bottom: 1px solid #222; }

        /* ===== BULLETS ===== */
        .bullet-list { list-style: none; margin: 16px 0; }
        .bullet-list li { padding: 10px 28px 10px 0; position: relative; font-size: 15px; border-bottom: 1px solid #111; }
        .bullet-list li::before { content: '⚡'; position: absolute; right: 0; top: 12px; font-size: 12px; color: var(--accent-gold); }

        /* ===== GRID SYSTEMS ===== */
        .system-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 25px; margin: 32px 0; }
        .interactive-card {
            background: var(--card); border: 1px solid #1a1a1a; padding: 30px;
            border-top: 3px solid var(--secondary-red); transition: 0.3s;
        }
        .interactive-card:hover { border-color: var(--accent-orange); transform: translateY(-5px); box-shadow: 0 5px 15px var(--dragon-glow); }
        .interactive-card i { font-size: 2.5rem; color: var(--accent-orange); margin-bottom: 15px; display: block; }

        /* ===== CALCULATORS ===== */
        /* FIX: changed minmax from 450px to 320px to prevent overflow on mobile */
        .calculators-container { display: grid; grid-template-columns: repeat(auto-fit, minmax(320px, 1fr)); gap: 40px; }
        .macro-box { background-color: var(--card); border: 1px solid #222; padding: 35px; border-top: 4px solid var(--accent-orange); position: relative; }
        .form-group { margin-bottom: 20px; }
        .form-group label { display: block; margin-bottom: 8px; font-size: 0.85rem; font-weight: bold; text-transform: uppercase; color: var(--grey); }
        .form-group input, .form-group select { width: 100%; padding: 14px; background: #000; border: 1px solid #222; color: #fff; font-family: 'Cairo', sans-serif; }
        .form-group input:focus, .form-group select:focus { border-color: var(--secondary-red); outline: none; box-shadow: 0 0 10px rgba(255,0,0,0.3); }

        /* FIX: removed duplicate display declarations — only display:none here, JS sets display:grid */
        .results { display: none; grid-template-columns: repeat(3, 1fr); gap: 15px; margin-top: 25px; }
        .burn-results { display: none; grid-template-columns: 1fr; margin-top: 25px; }

        .res-item { background: #000; padding: 15px; text-align: center; border-bottom: 3px solid var(--secondary-red); }
        .res-val { display: block; font-size: 2rem; font-family: 'Oswald', sans-serif; font-weight: bold; color: var(--accent-gold); }

        /* ===== FLOATING WHATSAPP ===== */
        .floating-whatsapp {
            position: fixed; bottom: 30px; left: 30px;
            background: #25d366; color: #fff; width: 60px; height: 60px;
            border-radius: 50%; display: flex; align-items: center; justify-content: center;
            font-size: 32px; box-shadow: 0 4px 15px rgba(0,0,0,0.4);
            z-index: 2000; text-decoration: none; transition: 0.3s;
        }
        .floating-whatsapp:hover { transform: scale(1.1); background: #20ba5a; box-shadow: 0 0 20px #25d366; }

        /* ===== SCROLL NAV ===== */
        .scroll-nav { position: fixed; top: 50%; left: 20px; transform: translateY(-50%); display: flex; flex-direction: column; gap: 10px; z-index: 100; }
        .scroll-dot { width: 10px; height: 10px; border-radius: 50%; background: rgba(255,255,255,0.2); cursor: pointer; transition: all 0.3s; }
        .scroll-dot:hover, .scroll-dot.active { background: var(--secondary-red); transform: scale(1.4); box-shadow: 0 0 8px var(--secondary-red); }
        @media (max-width: 992px) { .scroll-nav { display: none; } }

        /* ===== RESPONSIVE FIXES ===== */
        @media (max-width: 600px) {
            .cover { padding: 40px 20px; }
            .section-title { font-size: 1.8rem; }
            .calculators-container { grid-template-columns: 1fr; }
            .results { grid-template-columns: 1fr; }
            .cover .btn { font-size: 13px; padding: 12px 18px; }
        }

        /* ===== FOOTER ===== */
        footer { background: #000; padding: 50px 0; border-top: 2px solid var(--secondary-red); text-align: center; }
        footer p { color: var(--grey); font-size: 0.95rem; margin-bottom: 12px; }
    </style>
</head>
<body>

    <a href="https://wa.me/201013689867?text=أهلاً كابتن صبري، أريد الاستفسار عن الأنظمة والتدريب" class="floating-whatsapp" target="_blank" rel="noopener noreferrer" title="تواصل واتساب مباشر">
        <i class="fa-brands fa-whatsapp"></i>
    </a>

    <nav class="scroll-nav" aria-label="التنقل السريع">
        <div class="scroll-dot active" onclick="window.scrollTo({top:0,behavior:'smooth'})" title="الغلاف"></div>
        <div class="scroll-dot" onclick="document.getElementById('tracker-section').scrollIntoView({behavior:'smooth'})" title="مسجل الأوزان والعدات"></div>
        <div class="scroll-dot" onclick="document.getElementById('timer-section').scrollIntoView({behavior:'smooth'})" title="مؤقت الراحة التكتيكي"></div>
        <div class="scroll-dot" onclick="document.getElementById('supplements-section').scrollIntoView({behavior:'smooth'})" title="المكملات وبدائل الصيدلية"></div>
        <div class="scroll-dot" onclick="document.getElementById('errors-section').scrollIntoView({behavior:'smooth'})" title="الأخطاء والتحذيرات"></div>
        <div class="scroll-dot" onclick="document.getElementById('protocols').scrollIntoView({behavior:'smooth'})" title="البروتوكولات التدريبية"></div>
        <div class="scroll-dot" onclick="document.getElementById('rescue').scrollIntoView({behavior:'smooth'})" title="بدائل الأجهزة"></div>
        <div class="scroll-dot" onclick="document.getElementById('tips').scrollIntoView({behavior:'smooth'})" title="نصائح الـ Iron"></div>
        <div class="scroll-dot" onclick="document.getElementById('phases').scrollIntoView({behavior:'smooth'})" title="التضخيم والتنشيف"></div>
        <div class="scroll-dot" onclick="document.getElementById('kitchen').scrollIntoView({behavior:'smooth'})" title="المطبخ الصحي"></div>
        <div class="scroll-dot" onclick="document.getElementById('calculators').scrollIntoView({behavior:'smooth'})" title="حاسبة التحليلات"></div>
    </nav>

    <div class="top-bar">
        <div class="container bar-flex">
            <span class="brand-owner"><i class="fa-solid fa-dragon"></i> FOUNDER: SABRY ELHADIDY</span>
            <a href="tel:01013689867" class="brand-phone"><i class="fa-solid fa-phone-volume" style="color:var(--success);"></i> للاستفسارات والاشتراكات الفورية: 01013689867</a>
        </div>
    </div>

    <header class="main-header">
        <div class="container header-flex">
            <!-- FIX: replaced href="#" with javascript:void(0) to prevent unwanted page jump -->
            <a href="javascript:void(0)" class="logo"><i class="fa-solid fa-dragon"></i>ELHADIDY<span>IRON</span></a>
        </div>
    </header>

    <section class="cover">
        <div class="cover-badge" id="dynamicBadge">The Ultimate Tactical Platform</div>
        <h1 class="cover-title-ar" id="dynamicTitle">الدليل الرياضي الشامل<br><span class="text-gradient">والمحرك التحليلي المطور</span></h1>
        <div class="cover-divider"></div>
        <p class="cover-subtitle">البروتوكولات التدريبية العالمية، مصفوفات التكتيك، والمطبخ الأنابوليكي</p>
        <div>
            <a href="#supplements-section" class="btn btn-primary">دليل المكملات والبدائل الطبية <i class="fa-solid fa-capsules"></i></a>
            <a href="tel:01013689867" class="btn btn-outline">اتصال مباشر <i class="fa-solid fa-headset"></i></a>
        </div>
    </section>

    <!-- ===== TRACKER ===== -->
    <section id="tracker-section" class="container section-padding">
        <div class="section-header">
            <span class="section-tag">LIVE PROGRESS ENGINE</span>
            <h2 class="section-title">دفتر تسجيل التمارين والأوزان والعدّات الحية</h2>
            <div class="line-accent"></div>
        </div>

        <div class="macro-box" style="border-top-color: var(--accent-gold);">
            <div class="tracker-grid">
                <div class="form-group">
                    <label for="trackName">اسم التمرين (Exercise)</label>
                    <input type="text" id="trackName" placeholder="مثال: Bench Press">
                </div>
                <div class="form-group">
                    <label for="trackWeight">الوزن المرفوع (Weight - KG)</label>
                    <input type="number" id="trackWeight" placeholder="مثال: 80" min="0">
                </div>
                <div class="form-group">
                    <label for="trackSets">المجموعات (Sets)</label>
                    <input type="number" id="trackSets" placeholder="مثال: 4" min="1">
                </div>
                <div class="form-group">
                    <label for="trackReps">العدّات (Reps)</label>
                    <input type="text" id="trackReps" placeholder="مثال: 12-10-8">
                </div>
            </div>
            <button class="btn btn-primary" onclick="addGymLog()"><i class="fa-solid fa-plus"></i> حفظ التمرين في مصفوفة التطور</button>

            <div class="tbl-wrap" style="margin-top: 20px;">
                <table class="tbl">
                    <thead>
                        <tr>
                            <th>التمرين</th>
                            <th>الوزن المستهدف</th>
                            <th>المجموعات</th>
                            <th>العدّات تفصيلياً</th>
                            <th>الإجراء</th>
                        </tr>
                    </thead>
                    <tbody id="gymLogTableBody"></tbody>
                </table>
            </div>
        </div>
    </section>

    <!-- ===== TIMER ===== -->
    <section id="timer-section" class="section-padding" style="background: var(--dark);">
        <div class="container" style="max-width:600px;">
            <div class="section-header">
                <span class="section-tag">ANABOLIC RECOVERY</span>
                <h2 class="section-title">مؤقت الراحة التكتيكي بين المجموعات</h2>
                <div class="line-accent"></div>
            </div>

            <div class="macro-box" style="border-top-color: var(--success); text-align:center;">
                <div class="timer-preset-btns">
                    <!-- FIX: store preset seconds in data-seconds attribute for reliable reset logic -->
                    <button class="btn-preset" data-seconds="30" onclick="setTimerPreset(30, this)">⏱️ 30 ثانية (كارديو/بطن)</button>
                    <button class="btn-preset active" data-seconds="90" onclick="setTimerPreset(90, this)">⚡ 90 ثانية (هايبرتروفي)</button>
                    <button class="btn-preset" data-seconds="180" onclick="setTimerPreset(180, this)">🔥 3 دقائق (قوة عضلية)</button>
                </div>

                <div class="timer-display" id="timerOutput">01:30</div>

                <div style="display:flex; gap:10px; justify-content:center;">
                    <button class="btn btn-primary" onclick="startRestTimer()" style="background:linear-gradient(135deg, var(--success), #00b344); color:#000;"><i class="fa-solid fa-play"></i> ابدأ الراحة</button>
                    <button class="btn btn-outline" onclick="resetRestTimer()"><i class="fa-solid fa-rotate-left"></i> إعادة تعيين</button>
                </div>
            </div>
        </div>
    </section>

    <!-- ===== SUPPLEMENTS ===== -->
    <section id="supplements-section" class="container section-padding">
        <div class="section-header">
            <span class="section-tag">SUPPLEMENT MATRIX</span>
            <h2 class="section-title">دليل المكملات الغذائية وبدائلها الاقتصادية من الصيدلية</h2>
            <div class="line-accent"></div>
        </div>

        <p class="body-text" style="text-align: center; margin-bottom: 30px;">مش شرط تشتري مكملات بآلاف الجنيهات! دي مصفوفة التحليل العلمي لفوائد أشهر المكملات وبدائلها الطبية المباشرة المتاحة في الصيدليات بأسعار ممتازة.</p>

        <div class="tbl-wrap">
            <table class="tbl">
                <thead>
                    <tr>
                        <th>المكمل الرياضي العالمي</th>
                        <th>الفائدة الحركية والبيولوجية</th>
                        <th>البديل الطبي من الصيدلية المصرية</th>
                        <th>الجرعة والتكتيك اليومي</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td><strong>الواي بروتين (Whey Protein)</strong></td>
                        <td>توفير الأحماض الأمينية سريعة الامتصاص لبناء وإصلاح الألياف بعد تدريب الحديد.</td>
                        <td><span style="color:var(--success);">مكمل أمينو ميكس (Amino Mix)</span> أو بياض البيض والجبن القريش</td>
                        <td>4 أقراص صيدلية أو 4 بياض بيض يوفر حوالي 24 جرام بروتين صافي.</td>
                    </tr>
                    <tr>
                        <td><strong>الكرياتين مونوهيدرات (Creatine)</strong></td>
                        <td>زيادة إنتاج طاقة الـ ATP داخل الخلايا، تضخيم العضلات بالماء، وزيادة القوة الانفجارية.</td>
                        <td>لا يوجد بديل دوائي كيميائي كافي (يفضل شراؤه كمكمل نقي)، أو الاعتماد على اللحوم الحمراء.</td>
                        <td>5 جرام يومياً ثابتة في نفس الميعاد مع شرب 4 لتر ماء على مدار اليوم.</td>
                    </tr>
                    <tr>
                        <td><strong>الـ Pre-Workout (باور الطاقة)</strong></td>
                        <td>زيادة ضخ الدم وعزل المفاصل، وتوسيع الأوعية الدموية (Pump) وزيادة التركيز العصبي.</td>
                        <td><span style="color:var(--success);">كوب قهوة سادة مزدوج + قرص ترينتال 400 (Trental)</span></td>
                        <td>قرص ترينتال لزيادة تدفق الدم مع القهوة قبل التمرين بـ 45 دقيقة (تحت إشراف طبي).</td>
                    </tr>
                    <tr>
                        <td><strong>الأوميجا 3 (Omega 3)</strong></td>
                        <td>تقليل التهابات المفاصل والأوتار، حماية القلب، ورفع كفاءة الاستشفاء العضلي.</td>
                        <td><span style="color:var(--success);">كبسولات بلس أوميجا 3 (Omega 3 Plus)</span></td>
                        <td>كارتونة الصيدلية، كبسولة واحدة إلى كبسولتين بعد وجبة الإفطار أو الغداء مباشرة.</td>
                    </tr>
                </tbody>
            </table>
        </div>
    </section>

    <!-- ===== ERRORS ===== -->
    <section id="errors-section" class="section-padding" style="background: var(--dark);">
        <div class="container">
            <div class="section-header">
                <span class="section-tag">WARNING MATRIX</span>
                <h2 class="section-title">مصفوفة الأخطاء القاتلة والتكتيكات الواجب تجنبها</h2>
                <div class="line-accent"></div>
            </div>

            <div class="system-grid">
                <div class="interactive-card" style="border-top-color: var(--secondary-red);">
                    <h3 style="color: var(--secondary-red);"><i class="fa-solid fa-triangle-exclamation"></i> 1. إهمال المدى الحركي الكامل (Partial Reps)</h3>
                    <p class="body-text" style="font-size: 14px; margin-top:10px;">
                        <strong>الخطأ:</strong> تحريك الوزن في نصف زاوية فقط من أجل التباهي برفع وزن ثقيل.<br>
                        <span style="color:var(--accent-gold);"><strong>الضرر:</strong></span> عدم تفعيل 40% من الألياف العضلية، وتركيز حمل جبار وضار على الأوتار والمفاصل.<br>
                        <span style="color:var(--success);"><strong>التصحيح:</strong></span> قلل الوزن، وانزل بالوزن حتى أقصى تمدد (Stretch) واصعد حتى أقصى انقباض (Contraction).
                    </p>
                </div>

                <div class="interactive-card" style="border-top-color: var(--secondary-red);">
                    <h3 style="color: var(--secondary-red);"><i class="fa-solid fa-circle-xmark"></i> 2. قطع الكربوهيدرات نهائياً أثناء التنشيف</h3>
                    <p class="body-text" style="font-size: 14px; margin-top:10px;">
                        <strong>الخطأ:</strong> منع الكربوهيدرات والعيش على البروتين فقط ظناً أن هذا يسرع حرق الدهون.<br>
                        <span style="color:var(--accent-gold);"><strong>الضرر:</strong></span> تفريغ مخازن الجليكوجين، هبوط الأداء البدني الزيرو، وهدم الكتلة العضلية يقيناً.<br>
                        <span style="color:var(--success);"><strong>التصحيح:</strong></span> اعتمد على الكربوهيدرات المعقدة (الشوفان، الأرز، البطاطس) بكميات محسوبة ضمن عجز سعرات الحرارة.
                    </p>
                </div>

                <div class="interactive-card" style="border-top-color: var(--secondary-red);">
                    <h3 style="color: var(--secondary-red);"><i class="fa-solid fa-skull-crossbones"></i> 3. تكرار نفس التمارين والأوزان لشهور</h3>
                    <p class="body-text" style="font-size: 14px; margin-top:10px;">
                        <strong>الخطأ:</strong> دخول الجيم ولعب نفس الـ 4 مجاميع بنفس الـ 10 عدّات وبنفس الوزن كل أسبوع.<br>
                        <span style="color:var(--accent-gold);"><strong>الضرر:</strong></span> تكيف الجسم تماماً وتوقف النمو العضلي والدخول في مرحلة الثبات البنائي.<br>
                        <span style="color:var(--success);"><strong>التصحيح:</strong></span> طبق تكتيك التحميل التدريجي (Progressive Overload) بزيادة وزن أو عدّة أو تحسين الأداء في كل حصة.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- ===== PROTOCOLS ===== -->
    <section id="protocols" class="container section-padding">
        <div class="section-header">
            <span class="section-tag">PRO SYSTEMS</span>
            <h2 class="section-title">الأنظمة التدريبية الاحترافية</h2>
            <div class="line-accent"></div>
        </div>

        <div class="info-box">
            <div class="box-title">🔄 فلسفة التدريب والتحميل التدريجي</div>
            <p style="font-size:14px; color:var(--grey)">اختر نظامك التدريبي بناءً على نمط حياتك ومعدل الاستشفاء الخاص بك. القاعدة الذهبية دائماً هي (Progressive Overload).</p>
        </div>

        <h2 class="h2-style">1. نظام البرو سبليت (Pro Split)</h2>
        <p class="body-text">نظام متقدم يعتمد على تفجير مجموعة عضلية واحدة في الحصة التدريبية بحجم تدريبي (Volume) عالٍ جداً، وهو المفضل لأبطال الوزن الثقيل مستر أولمبيا مثل روني كولمان وجاي كاتلر.</p>
        <div class="tbl-wrap">
            <table class="tbl">
                <thead>
                    <tr><th>اليوم</th><th>المجموعة العضلية</th><th>تمرين القوة الرئيسي</th><th>الحجم الإجمالي</th></tr>
                </thead>
                <tbody>
                    <tr><td>الإثنين</td><td>الصدر (Chest Day)</td><td>بنش برس بالبار مائل</td><td>5 تمارين / 20 جولة</td></tr>
                    <tr><td>الثلاثاء</td><td>الظهر (Back Day)</td><td>ديدليفت + سحب بار مائل</td><td>6 تمارين / 24 جولة</td></tr>
                    <tr><td>الأربعاء</td><td>الكتفين (Shoulders)</td><td>ميلتري بريس بالبار</td><td>5 تمارين / 20 جولة</td></tr>
                    <tr><td>الخميس</td><td>الذراعين (Arms)</td><td>تبادل دمبل + بنش ضيق</td><td>6 تمارين / 22 جولة</td></tr>
                    <tr><td>الجمعة</td><td>الأرجل (Legs)</td><td>سكوات حر بالبار</td><td>6 تمارين / 25 جولة</td></tr>
                </tbody>
            </table>
        </div>

        <h2 class="h2-style">2. نظام بوش بول ليجز (Push Pull Legs)</h2>
        <p class="body-text">النظام الأكثر توازناً، يقوم بتقسيم الجسم حسب الوظيفة الحركية (دفع، سحب، أرجل). يسمح بتدريب العضلة مرتين أسبوعياً وهو ممتاز للمتوسطين والمتقدمين.</p>
        <div class="tbl-wrap">
            <table class="tbl">
                <thead>
                    <tr><th>النوع</th><th>العضلات المستهدفة</th><th>أهم التمارين المركبة</th></tr>
                </thead>
                <tbody>
                    <tr><td>PUSH (الدفع)</td><td>الصدر، الكتف الأمامي والجانبي، الترايسبس</td><td>بنش برس، أوفر هيد بريس، غطس</td></tr>
                    <tr><td>PULL (السحب)</td><td>الظهر كاملاً، الكتف الخلفي، البايسبس، الساعد</td><td>عُقلة بالوزن، بار رو، هامر كيرل</td></tr>
                    <tr><td>LEGS (الأرجل)</td><td>الفخذ الأمامي، الخلفيات، السمانة، الأرداف</td><td>سكوات، ليج بريس، رومانيان ديدليفت</td></tr>
                </tbody>
            </table>
        </div>
    </section>

    <!-- ===== RESCUE ===== -->
    <section id="rescue" class="section-padding" style="background: var(--dark);">
        <div class="container">
            <div class="section-header">
                <span class="section-tag">INSTANT BACKUP SYSTEMS</span>
                <h2 class="section-title">مُولد خطة الإنقاذ وبدائل أجهزة الجيم المزدحمة</h2>
                <div class="line-accent"></div>
            </div>
            <p class="body-text" style="text-align: center; margin-bottom: 40px;">لو لقيت الجهاز اللي عليه الدور في جدولك محجوز أو زحمة، اضغط عليه فوراً وهيطلعلك البديل الحر الأقوى لتفعيل نفس الزوايا بدون ما تعطل تمرينك.</p>

            <div class="rescue-grid">
                <div class="rescue-node" onclick="getGymBackup('latPulldown')">
                    <i class="fa-solid fa-person-falling-burst"></i>
                    <h3>جهاز السحب العالي</h3>
                </div>
                <div class="rescue-node" onclick="getGymBackup('legPress')">
                    <i class="fa-solid fa-angles-up"></i>
                    <h3>جهاز الـ Leg Press</h3>
                </div>
                <div class="rescue-node" onclick="getGymBackup('chestFlyMachine')">
                    <i class="fa-solid fa-arrows-left-right"></i>
                    <h3>جهاز الفراشة للصدر</h3>
                </div>
                <div class="rescue-node" onclick="getGymBackup('cableTricep')">
                    <i class="fa-solid fa-link"></i>
                    <h3>كابل الترايسبس</h3>
                </div>
                <div class="rescue-node" onclick="getGymBackup('smithSquat')">
                    <i class="fa-solid fa-bars-staggered"></i>
                    <h3>جهاز سميث سكوات</h3>
                </div>
            </div>

            <div class="rescue-panel" id="rescuePanel">
                <h3 id="rescueTitle" style="color:var(--accent-gold); margin-bottom:10px;"></h3>
                <p id="rescueText" style="color:#fff; font-size:15px;"></p>
            </div>
        </div>
    </section>

    <!-- ===== TIPS ===== -->
    <section id="tips" class="container section-padding">
        <div class="section-header">
            <span class="section-tag">ELHADIDY GYM WISDOM</span>
            <h2 class="section-title">نصائح الـ Iron الذهبية والتكتيكات النفسية</h2>
            <div class="line-accent"></div>
        </div>

        <div class="system-grid">
            <div class="interactive-card">
                <i class="fa-solid fa-brain"></i>
                <h3>الاتصال العضلي العصبي (Mind-Muscle Connection)</h3>
                <p class="body-text" style="font-size: 14px; margin-top:10px;">ما ترفعش الوزن لمجرد الرفع! ركز بعقلك في العضلة المستهدفة وهي بتنقبض وتنبسط. الحركة دي بتزود تفعيل الألياف العضلية بنسبة تصل لـ 30% وتضمنلك نمو حقيقي بدلاً من رمي الوزن بالقصور الذاتي.</p>
            </div>

            <div class="interactive-card">
                <i class="fa-solid fa-bed"></i>
                <h3>استشفاء الـ Alpha المطور</h3>
                <p class="body-text" style="font-size: 14px; margin-top:10px;">العضلات بتكبر برة الجيم مش جواه. النوم من 7 لـ 8 ساعات يومياً في غرفة مظلمة هو الوقت السحري لإفراز هرمون النمو الطبيعي (GH). تدميرك للحديد بدون نوم كافي يعني هدم عضلي صريح.</p>
            </div>

            <div class="interactive-card">
                <i class="fa-solid fa-kit-medical"></i>
                <h3>مصفوفة الأمان وتجنب الـ Ego Lifting</h3>
                <p class="body-text" style="font-size: 14px; margin-top:10px;">الإصابة بتعطلك شهور لورا. العب بمدى حركي كامل (Full Range of Motion) وبوزن تقدر تتحكم فيه في النزول (المدى السلبي) لمدة ثانيتين على الأقل. سيب وزن كبريائك برة باب الجيم!</p>
            </div>
        </div>
    </section>

    <!-- ===== PHASES ===== -->
    <section id="phases" class="container section-padding">
        <div class="section-header">
            <span class="section-tag">TACTICAL METRICS</span>
            <h2 class="section-title">طرق التضخيم والتنشيف العلمي</h2>
            <div class="line-accent"></div>
        </div>

        <div class="system-grid">
            <div class="interactive-card" style="border-top-color: var(--accent-gold);">
                <h3><i class="fa-solid fa-cubes-stacked" style="color:var(--accent-gold)"></i> بروتوكول التضخيم الذكي (Clean Bulking)</h3>
                <p class="body-text" style="font-size: 14px; margin-top:15px;">الهدف هو بناء أكبر كتلة عضلية ممكنة مع تقليل اكتساب الدهون. الخطوات:</p>
                <ul class="bullet-list" style="font-size: 13px;">
                    <li>فائض سعرات حرارية بسيط: إضافة 300 إلى 500 سعرة فوق كمية المحافظة.</li>
                    <li>زيادة حجم التدريب وكثافته لضمان توجيه السعرات للبناء العضلي.</li>
                    <li>تناول كربوهيدرات معقدة بكثرة لتعبئة مخازن الجليكوجين في العضلات.</li>
                </ul>
            </div>

            <div class="interactive-card" style="border-top-color: var(--secondary-red);">
                <h3><i class="fa-solid fa-fire-flame-curved" style="color:var(--secondary-red)"></i> بروتوكول التنشيف الحاد (Aggressive Shredding)</h3>
                <p class="body-text" style="font-size: 14px; margin-top:15px;">الهدف هو حرق دهون الجسم المستعصية مع الحفاظ المطلق على النسيج العضلي. الخطوات:</p>
                <ul class="bullet-list" style="font-size: 13px;">
                    <li>عجز سعرات حرارية مدروس: تقليل 500 سعرة حرارية من سعرات المحافظة.</li>
                    <li>رفع كمية البروتين إلى (2.5g لكل كيلوجرام) لمنع الهدم العضلي (Catabolism).</li>
                    <li>إدخال الكارديو عالي الكثافة (HIIT) أو الكارديو منخفض الكثافة الثابت (LISS) بحسب الاستجابة.</li>
                </ul>
            </div>
        </div>
    </section>

    <!-- ===== KITCHEN ===== -->
    <section id="kitchen" class="section-padding" style="background: var(--dark);">
        <div class="container">
            <div class="section-header">
                <span class="section-tag">ANABOLIC FUEL</span>
                <h2 class="section-title">مطبخ الأكل الصحي والوصفات</h2>
                <div class="line-accent"></div>
            </div>

            <h2 class="h2-style">وجبات محسوبة الماكروز للرياضيين</h2>

            <div class="system-grid">
                <div class="interactive-card">
                    <span style="color: var(--accent-gold); font-weight: bold; font-size: 12px;">وجبة الغداء / تضخيم وتنشيف</span>
                    <h3 style="margin: 10px 0;">الأرز البسمتي بالدجاج المتبل</h3>
                    <p style="font-size: 14px; color: var(--grey);">200 جرام صدور دجاج مشوية + 150 جرام أرز بسمتي مسلوق + خضار سوتيه + ملعقة زيت زيتون.</p>
                    <div style="margin-top:15px; border-top: 1px dashed #333; padding-top:10px; font-size:13px; color:var(--accent-gold)">
                        <strong>القيم الغذائية:</strong> السعرات: ~650 | بروتين: 55g | كارب: 68g | دهون: 12g
                    </div>
                </div>

                <div class="interactive-card">
                    <span style="color: var(--accent-gold); font-weight: bold; font-size: 12px;">وجبة الإفطار / بناء عضلي</span>
                    <h3 style="margin: 10px 0;">بان كيك الشوفان الخارق</h3>
                    <p style="font-size: 14px; color: var(--grey);">60 جرام شوفان مطحون + 4 بياض بيض + بيضة كاملة + سكوب واي بروتين + نصف موزة + قرفة.</p>
                    <div style="margin-top:15px; border-top: 1px dashed #333; padding-top:10px; font-size:13px; color:var(--accent-gold)">
                        <strong>القيم الغذائية:</strong> السعرات: ~520 | بروتين: 48g | كارب: 50g | دهون: 9g
                    </div>
                </div>

                <div class="interactive-card">
                    <span style="color: var(--accent-gold); font-weight: bold; font-size: 12px;">وجبة قبل النوم / استشفاء</span>
                    <h3 style="margin: 10px 0;">مزيج الكازين والقريش المطور</h3>
                    <p style="font-size: 14px; color: var(--grey);">200 جرام جبنة قريش كريمية + 30 جرام مكسرات مشكلة (لوز/جوز) + ملعقة عسل صغيرة للتحلية.</p>
                    <div style="margin-top:15px; border-top: 1px dashed #333; padding-top:10px; font-size:13px; color:var(--accent-gold)">
                        <strong>القيم الغذائية:</strong> السعرات: ~390 | بروتين: 32g | كارب: 15g | دهون: 18g
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ===== CALCULATORS ===== -->
    <section id="calculators" class="container section-padding">
        <div class="section-header">
            <span class="section-tag">COMPUTATIONAL ENGINE</span>
            <h2 class="section-title">مركز التحليلات الرياضية وحساب الطاقة</h2>
            <div class="line-accent"></div>
        </div>

        <div class="calculators-container">
            <!-- Calculator 1: Macros -->
            <div class="macro-box">
                <h3><i class="fa-solid fa-calculator" style="color:var(--secondary-red)"></i> 1. حاسبة السعرات والماكروز المستهدفة</h3>
                <div class="form-group" style="margin-top:20px;">
                    <label for="weight">الوزن الحالي بالكيلوجرام (KG)</label>
                    <input type="number" id="weight" value="95" min="30" max="300">
                </div>
                <div class="form-group">
                    <label for="goal">الهدف البدني الرئيسي</label>
                    <select id="goal" onchange="updateDynamicTheme()">
                        <option value="build">Massive Muscle Gain (تضخيم عنيف)</option>
                        <option value="shred">Aggressive Shredding (تنشيف حاد)</option>
                        <option value="maintain">Weight Maintenance (حفاظ وثبات الوزن)</option>
                    </select>
                </div>
                <div class="form-group">
                    <label for="trainingDays">معدل أيام التدريب أسبوعياً</label>
                    <select id="trainingDays">
                        <option value="3">3 أيام / أسبوع (مجهود خفيف)</option>
                        <option value="4">4 أيام / أسبوع (مجهود متوسط)</option>
                        <option value="5" selected>5 أيام / أسبوع (أداء مكثف)</option>
                        <option value="6">6 أيام / أسبوع (مستوى المحترفين)</option>
                    </select>
                </div>
                <button class="btn btn-primary btn-full" onclick="calculateMacros()">تشغيل خوارزمية الماكروز</button>

                <!-- FIX: single display property; JS will set display:grid when showing -->
                <div class="results" id="resultsBox">
                    <div class="res-item">
                        <span class="res-val" id="calOut">0</span>
                        <span style="font-size:0.8rem; color:var(--grey)">Calories</span>
                    </div>
                    <div class="res-item">
                        <span class="res-val" id="proOut">0g</span>
                        <span style="font-size:0.8rem; color:var(--grey)">Protein</span>
                    </div>
                    <div class="res-item">
                        <span class="res-val" id="carbOut">0g</span>
                        <span style="font-size:0.8rem; color:var(--grey)">Carbs</span>
                    </div>
                </div>
            </div>

            <!-- Calculator 2: Burn -->
            <div class="macro-box" style="border-top-color: var(--secondary-red);">
                <h3><i class="fa-solid fa-fire" style="color:var(--accent-orange)"></i> 2. متتبع معدل حرق السعرات في الجلسة</h3>
                <div class="form-group" style="margin-top:20px;">
                    <label for="burnType">بروتوكول التدريب المتبع</label>
                    <select id="burnType">
                        <option value="heavy-lifting">Intense Bodybuilding / Heavy Lifting (حديد عنيف)</option>
                        <option value="mid-lifting">Moderate Bodybuilding / Hypertrophy (حديد متوسط الجهد)</option>
                        <option value="hiit">HIIT / High-Intensity Cardio (كارديو سريع السعرات)</option>
                        <option value="steady-cardio">Steady-State Cardio / Treadmill (مشاية / كارديو خفيف)</option>
                    </select>
                </div>
                <div class="form-group">
                    <label for="burnDuration">مدة الحصة التدريبية (بالدقائق)</label>
                    <input type="number" id="burnDuration" value="60" min="10" max="300">
                </div>
                <div class="form-group">
                    <label for="burnWeight">وزنك الحالي بالكيلوجرام (KG)</label>
                    <input type="number" id="burnWeight" value="85" min="30" max="300">
                </div>
                <button class="btn btn-primary btn-full" onclick="calculateBurn()">حساب الطاقة المستهلكة الإجمالية</button>

                <div class="burn-results" id="burnResultsBox">
                    <div class="res-item" style="border-bottom-color: var(--accent-orange);">
                        <span class="res-val" id="burnOut">0</span>
                        <span style="font-size:0.9rem; color:var(--grey)">إجمالي السعرات الحرارية النشطة المحروقة</span>
                    </div>
                    <div class="res-item" style="border-bottom-color: var(--success); margin-top: 12px;">
                        <span class="res-val" id="burnRateOut">0</span>
                        <span style="font-size:0.9rem; color:var(--grey)">معدل الحرق بالدقيقة (Cal/min)</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2026 ELHADIDYIRON Global Systems. Engineered and Supervised by Sabry Elhadidy Platform Operations.</p>
            <p style="color: var(--accent-gold); font-weight: bold; font-size:1.2rem; letter-spacing:1px;">
                <a href="tel:01013689867" style="color:inherit; text-decoration:none;"><i class="fa-solid fa-headset"></i> الخط الساخن للاستفسارات: 01013689867</a>
            </p>
        </div>
    </footer>

    <script>
        // ===================================================
        // RESCUE ENGINE — بدائل الأجهزة
        // ===================================================
        const backupExercises = {
            latPulldown: {
                title: "بديل جهاز السحب العالي لتعريض الظهر:",
                text: "العب <strong>عقلة واسعة بوزن جسمك أو بمساعدة (Pull-ups)</strong>، وإذا كانت صعبة، البديل الأقوى هو <strong>السحب بالدمبل مائل فردي (Single-Arm Dumbbell Row)</strong> مع التركيز على سحب الكوع لورا عند الوسط تماماً لتفعيل عضلات اللاتس."
            },
            legPress: {
                title: "بديل جهاز الـ Leg Press لتفجير الأماميات:",
                text: "اتجه فوراً للعب <strong>السكوات الحر بالبار (Barbell Back Squat)</strong> بمدى حركي كامل، أو العب <strong>اللانجز بالدمبلز متحرك (Walking Lunges)</strong> بتركيز عالي، هيحط حمل جبار ومباشر على الكوادز والأرداف."
            },
            chestFlyMachine: {
                title: "بديل جهاز الفراشة لعزل وتشريح الصدر:",
                text: "البديل المثالي هو <strong>التجميع على كابل الصدر من المنتصف (Cable Flyes)</strong>، وإذا كان الكابل مشغولاً، العب <strong>تفتيح بالدمبل على بنش فلات (Flat Dumbbell Flyes)</strong> مع الحفاظ على انحناء بسيط جداً في الكوع لحماية المفاصل."
            },
            cableTricep: {
                title: "بديل كابل الترايسبس بالحبل:",
                text: "العب تمرين <strong>كسارة الجمجمة بالبار الزيجزاج (Skull Crushers)</strong> وأنت مستلقي على البنش، أو تمرين <strong>دفع الدمبل خلف الرأس بيد واحدة أو باليدين (Overhead Dumbbell Extension)</strong> لتفجير الرأس الطويل للترايسبس."
            },
            smithSquat: {
                title: "بديل جهاز سميث سكوات للأرجل:",
                text: "العب <strong>جوبلت سكوات بالدمبل (Goblet Squat)</strong> بوزن ثقيل، أو تمرين <strong>السكوات البلغاري فردي (Bulgarian Split Squat)</strong> بالدمبلز؛ تمرين جبار بيعزل كل رجل لوحدها ويدمر أي اختلال عضلي."
            }
        };

        function getGymBackup(key) {
            const item = backupExercises[key];
            if (!item) return;
            document.getElementById('rescueTitle').innerText = item.title;
            document.getElementById('rescueText').innerHTML = item.text;
            const panel = document.getElementById('rescuePanel');
            panel.style.display = 'block';
            panel.scrollIntoView({ behavior: 'smooth', block: 'nearest' });
        }

        // ===================================================
        // GYM LOG TRACKER — مسجل التمارين
        // FIX: called loadGymLogs() on DOMContentLoaded so logs persist after page refresh
        // ===================================================
        function loadGymLogs() {
            const logs = JSON.parse(localStorage.getItem('sabryGymLogs') || '[]');
            const tbody = document.getElementById('gymLogTableBody');
            tbody.innerHTML = '';
            if (logs.length === 0) {
                tbody.innerHTML = '<tr><td colspan="5" style="color:var(--grey); padding:20px;">لم يتم تسجيل أي تمارين بعد. ابدأ الآن! 💪</td></tr>';
                return;
            }
            logs.forEach((log, index) => {
                tbody.innerHTML += `<tr>
                    <td><strong>${escapeHtml(log.name)}</strong></td>
                    <td><span style="color:var(--accent-gold); font-weight:bold;">${escapeHtml(log.weight)} KG</span></td>
                    <td>${escapeHtml(log.sets)} مجاميع</td>
                    <td>${escapeHtml(log.reps)} عدّة</td>
                    <td><button class="btn btn-danger" onclick="deleteGymLog(${index})"><i class="fa-solid fa-trash"></i> حذف</button></td>
                </tr>`;
            });
        }

        // FIX: added escapeHtml to prevent XSS from user input
        function escapeHtml(str) {
            return String(str)
                .replace(/&/g, '&amp;')
                .replace(/</g, '&lt;')
                .replace(/>/g, '&gt;')
                .replace(/"/g, '&quot;');
        }

        function addGymLog() {
            const name     = document.getElementById('trackName').value.trim();
            const weight   = document.getElementById('trackWeight').value.trim();
            const sets     = document.getElementById('trackSets').value.trim();
            const reps     = document.getElementById('trackReps').value.trim();

            if (!name || !weight || !sets || !reps) {
                alert('يا كابتن، املا الخانات كلها عشان نحفظ البيانات صح! 💪');
                return;
            }

            const logs = JSON.parse(localStorage.getItem('sabryGymLogs') || '[]');
            logs.push({ name, weight, sets, reps, date: new Date().toLocaleDateString('ar-EG') });
            localStorage.setItem('sabryGymLogs', JSON.stringify(logs));

            document.getElementById('trackName').value  = '';
            document.getElementById('trackWeight').value = '';
            document.getElementById('trackSets').value  = '';
            document.getElementById('trackReps').value  = '';

            loadGymLogs();
        }

        function deleteGymLog(index) {
            const logs = JSON.parse(localStorage.getItem('sabryGymLogs') || '[]');
            if (index < 0 || index >= logs.length) return; // FIX: bounds check
            logs.splice(index, 1);
            localStorage.setItem('sabryGymLogs', JSON.stringify(logs));
            loadGymLogs();
        }

        // ===================================================
        // REST TIMER — مؤقت الراحة
        // FIX: timer preset seconds now read from data-seconds attribute (reliable)
        // ===================================================
        let timerInterval  = null;
        let timeRemaining  = 90;
        let currentPreset  = 90;

        function setTimerPreset(seconds, btnElement) {
            clearInterval(timerInterval);
            timerInterval   = null;
            timeRemaining   = seconds;
            currentPreset   = seconds;
            updateTimerDisplay();
            document.querySelectorAll('.btn-preset').forEach(b => b.classList.remove('active'));
            btnElement.classList.add('active');
        }

        function updateTimerDisplay() {
            const mins = Math.floor(timeRemaining / 60);
            const secs = timeRemaining % 60;
       
