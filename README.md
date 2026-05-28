
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>مستشار القبول المركزي العراقي 2024-2025</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts (Cairo) -->
    <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@300;400;600;700;800&display=swap" rel="stylesheet">
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        cairo: ['Cairo', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            50: '#f0f7ff',
                            100: '#e0effe',
                            200: '#bae0fd',
                            600: '#0284c7',
                            700: '#0369a1',
                            800: '#075985',
                            900: '#0c4a6e',
                        }
                    }
                }
            }
        }
    </script>
    <style>
        body {
            font-family: 'Cairo', sans-serif;
            background-color: #f8fafc;
        }
        .custom-scrollbar::-webkit-scrollbar {
            width: 6px;
        }
        .custom-scrollbar::-webkit-scrollbar-track {
            background: #f1f5f9;
        }
        .custom-scrollbar::-webkit-scrollbar-thumb {
            background: #cbd5e1;
            border-radius: 4px;
        }
        .custom-scrollbar::-webkit-scrollbar-thumb:hover {
            background: #94a3b8;
        }
    </style>
</head>
<body class="text-slate-800 antialiased min-h-screen flex flex-col">

    <!-- Header / Nav -->
    <header class="bg-gradient-to-r from-brand-900 via-brand-800 to-slate-900 text-white shadow-lg sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-20">
                <div class="flex items-center gap-3">
                    <div class="bg-white/10 p-2.5 rounded-xl backdrop-blur-md border border-white/20">
                        <i class="fa-solid fa-graduation-cap text-3xl text-sky-400"></i>
                    </div>
                    <div>
                        <h1 class="text-xl sm:text-2xl font-bold tracking-tight">مُستشار القبول المركزي</h1>
                        <p class="text-xs text-sky-300 font-medium">الحدود الدنيا للجامعات الحكومية العراقية 2024-2025</p>
                    </div>
                </div>
                <div class="hidden md:flex items-center gap-2 bg-white/10 px-4 py-2 rounded-lg text-sm border border-white/10">
                    <span class="w-2 h-2 rounded-full bg-emerald-400 animate-pulse"></span>
                    <span>البيانات محدثة ومطابقة لوزارة التعليم العالي</span>
                </div>
            </div>
        </div>
    </header>

    <!-- Main Content Area -->
    <main class="flex-grow max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-8 w-full">
        
        <!-- Hero Section / Welcome -->
        <div class="bg-white rounded-2xl p-6 sm:p-8 shadow-sm border border-slate-100 mb-8 relative overflow-hidden">
            <div class="absolute top-0 left-0 w-32 h-32 bg-brand-500/5 rounded-full blur-2xl -translate-x-10 -translate-y-10"></div>
            <div class="absolute bottom-0 right-0 w-48 h-48 bg-emerald-500/5 rounded-full blur-3xl translate-x-10 translate-y-10"></div>
            
            <div class="relative z-10 flex flex-col md:flex-row md:items-center justify-between gap-6">
                <div class="max-w-3xl">
                    <span class="bg-brand-100 text-brand-800 text-xs font-bold px-3 py-1.5 rounded-full mb-4 inline-block">نسخة تفاعلية ذكية</span>
                    <h2 class="text-2xl sm:text-3xl font-bold text-slate-900 mb-3">ابحث عن مستقبلك الجامعي بسهولة!</h2>
                    <p class="text-slate-600 leading-relaxed text-sm sm:text-base">
                        بدلاً من تصفح ملفات القبول المعقدة، قمنا ببناء هذه الأداة الذكية لمساعدتك في استكشاف الحدود الدنيا لجميع التخصصات الطبية، الهندسية، الإنسانية والعلمية في العراق، ومعرفة أين يؤهلك معدلك مباشرة.
                    </p>
                </div>
                <div class="flex flex-wrap gap-3">
                    <button onclick="scrollToSection('calculator')" class="bg-brand-600 hover:bg-brand-700 text-white font-semibold px-6 py-3.5 rounded-xl shadow-md transition-all hover:scale-[1.02] flex items-center gap-2">
                        <i class="fa-solid fa-calculator"></i>
                        حاسبة المعدل الذكية
                    </button>
                    <button onclick="scrollToSection('explorer')" class="bg-slate-100 hover:bg-slate-200 text-slate-700 font-semibold px-6 py-3.5 rounded-xl transition-all flex items-center gap-2">
                        <i class="fa-solid fa-compass"></i>
                        استكشاف الأقسام
                    </button>
                </div>
            </div>
        </div>

        <!-- Metric Cards -->
        <div class="grid grid-cols-2 lg:grid-cols-4 gap-4 mb-8">
            <div class="bg-white p-4 sm:p-5 rounded-2xl shadow-sm border border-slate-100 flex items-center gap-4">
                <div class="w-12 h-12 bg-rose-50 rounded-xl flex items-center justify-center text-rose-500 text-xl shrink-0">
                    <i class="fa-solid fa-heart-pulse"></i>
                </div>
                <div>
                    <p class="text-xs text-slate-500 font-bold">أعلى معدل قبول</p>
                    <h4 class="text-lg sm:text-xl font-extrabold text-slate-900 mt-0.5">101.41</h4>
                    <span class="text-[10px] text-slate-400">طب بغداد</span>
                </div>
            </div>

            <div class="bg-white p-4 sm:p-5 rounded-2xl shadow-sm border border-slate-100 flex items-center gap-4">
                <div class="w-12 h-12 bg-brand-50 rounded-xl flex items-center justify-center text-brand-600 text-xl shrink-0">
                    <i class="fa-solid fa-microscope"></i>
                </div>
                <div>
                    <p class="text-xs text-slate-500 font-bold">أدنى قبول طبي (عام)</p>
                    <h4 class="text-lg sm:text-xl font-extrabold text-slate-900 mt-0.5">99.57</h4>
                    <span class="text-[10px] text-slate-400">طب ميسان/الموصل/تكريت</span>
                </div>
            </div>

            <div class="bg-white p-4 sm:p-5 rounded-2xl shadow-sm border border-slate-100 flex items-center gap-4">
                <div class="w-12 h-12 bg-amber-50 rounded-xl flex items-center justify-center text-amber-600 text-xl shrink-0">
                    <i class="fa-solid fa-gears"></i>
                </div>
                <div>
                    <p class="text-xs text-slate-500 font-bold">أدنى هندسة نفط</p>
                    <h4 class="text-lg sm:text-xl font-extrabold text-slate-900 mt-0.5">95.71</h4>
                    <span class="text-[10px] text-slate-400">نفط ميسان</span>
                </div>
            </div>

            <div class="bg-white p-4 sm:p-5 rounded-2xl shadow-sm border border-slate-100 flex items-center gap-4">
                <div class="w-12 h-12 bg-emerald-50 rounded-xl flex items-center justify-center text-emerald-600 text-xl shrink-0">
                    <i class="fa-solid fa-scale-balanced"></i>
                </div>
                <div>
                    <p class="text-xs text-slate-500 font-bold">أدنى قبول للقانون</p>
                    <h4 class="text-lg sm:text-xl font-extrabold text-slate-900 mt-0.5">70.00</h4>
                    <span class="text-[10px] text-slate-400">عدة محافظات</span>
                </div>
            </div>
        </div>

        <!-- Calculator Section -->
        <div id="calculator" class="bg-white rounded-2xl shadow-sm border border-slate-100 p-6 mb-8">
            <div class="flex items-center gap-3 border-b border-slate-100 pb-4 mb-6">
                <div class="w-10 h-10 bg-brand-100 rounded-xl flex items-center justify-center text-brand-700">
                    <i class="fa-solid fa-calculator text-lg"></i>
                </div>
                <div>
                    <h3 class="font-bold text-slate-900 text-lg">حاسبة القبول الذكية ومطابقة المعدل</h3>
                    <p class="text-xs text-slate-500">ادخل معدلك وشاهد التخصصات التي تقبلك فوراً</p>
                </div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-12 gap-6 items-end">
                <div class="md:col-span-4">
                    <label class="block text-sm font-semibold text-slate-700 mb-2">أدخل معدلك بدقة (مثلاً: 98.43):</label>
                    <div class="relative">
                        <input id="user-score" type="number" step="0.01" min="50" max="105" placeholder="مثال: 97.5" 
                               class="w-full bg-slate-50 border border-slate-200 rounded-xl px-4 py-3 text-lg font-bold text-slate-900 focus:outline-none focus:ring-2 focus:ring-brand-600 focus:bg-white transition-all text-left">
                        <span class="absolute right-3 top-1/2 -translate-y-1/2 text-slate-400 font-bold">%</span>
                    </div>
                </div>

                <div class="md:col-span-3">
                    <label class="block text-sm font-semibold text-slate-700 mb-2">الفرع الدراسي الحالي:</label>
                    <select id="user-branch" class="w-full bg-slate-50 border border-slate-200 rounded-xl px-4 py-3.5 text-sm font-semibold text-slate-700 focus:outline-none focus:ring-2 focus:ring-brand-600 focus:bg-white transition-all">
                        <option value="الكل">جميع الفروع</option>
                        <option value="علمي">علمي (أحيائي / تطبيقي)</option>
                        <option value="ادبي">أدبي</option>
                    </select>
                </div>

                <div class="md:col-span-3">
                    <label class="block text-sm font-semibold text-slate-700 mb-2">تفضيل المحافظة:</label>
                    <select id="user-governorate" class="w-full bg-slate-50 border border-slate-200 rounded-xl px-4 py-3.5 text-sm font-semibold text-slate-700 focus:outline-none focus:ring-2 focus:ring-brand-600 focus:bg-white transition-all">
                        <option value="الكل">كل المحافظات</option>
                        <option value="بغداد">بغداد</option>
                        <option value="البصرة">البصرة</option>
                        <option value="الموصل">نينوى / الموصل</option>
                        <option value="بابل">بابل</option>
                        <option value="كربلاء">كربلاء</option>
                        <option value="النجف">النجف / الكوفة</option>
                        <option value="ميسان">ميسان</option>
                        <option value="ذي قار">ذي قار</option>
                        <option value="كركوك">كركوك</option>
                        <option value="صلاح الدين">صلاح الدين / تكريت</option>
                        <option value="الانبار">الانبار</option>
                        <option value="ديالى">ديالى</option>
                        <option value="واسط">واسط</option>
                        <option value="القادسية">القادسية</option>
                        <option value="المثنى">المثنى</option>
                    </select>
                </div>

                <div class="md:col-span-2">
                    <button onclick="calculateAdmission()" class="w-full bg-brand-600 hover:bg-brand-700 text-white font-bold py-3.5 px-4 rounded-xl shadow-md transition-all flex items-center justify-center gap-2">
                        <i class="fa-solid fa-wand-magic-sparkles"></i>
                        مطابقة القبول
                    </button>
                </div>
            </div>

            <!-- Match Results Placeholder -->
            <div id="calculator-results" class="mt-8 hidden">
                <div class="flex items-center justify-between border-t border-slate-100 pt-6 mb-4">
                    <h4 class="font-bold text-slate-800 flex items-center gap-2">
                        <span class="w-2.5 h-2.5 rounded-full bg-emerald-500"></span>
                        الخيارات المتاحة لمعدلك:
                    </h4>
                    <span id="results-count" class="bg-emerald-50 text-emerald-700 text-xs font-bold px-3 py-1 rounded-full"></span>
                </div>
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4 max-h-[400px] overflow-y-auto custom-scrollbar pr-1" id="results-grid">
                    <!-- Dynamic cards will render here -->
                </div>
            </div>
        </div>

        <!-- Explorer & Search Section -->
        <div id="explorer" class="bg-white rounded-2xl shadow-sm border border-slate-100 p-6 mb-8">
            <div class="flex flex-col lg:flex-row lg:items-center justify-between gap-4 border-b border-slate-100 pb-6 mb-6">
                <div>
                    <h3 class="font-bold text-slate-900 text-lg">استكشاف وتصفية الحدود الدنيا الكاملة</h3>
                    <p class="text-xs text-slate-500">اختر التخصص والمحافظة لتظهر لك الكليات فوراً مع نبذة تعريفية كاملة عن القسم</p>
                </div>
                
                <!-- Quick Search -->
                <div class="relative w-full lg:w-80">
                    <input type="text" id="quick-search" oninput="filterAdmissionData()" placeholder="ابحث باسم الكلية أو الجامعة..." 
                           class="w-full bg-slate-50 border border-slate-200 rounded-xl pl-4 pr-10 py-2.5 text-sm focus:outline-none focus:ring-2 focus:ring-brand-600 focus:bg-white transition-all">
                    <i class="fa-solid fa-magnifying-glass absolute right-3.5 top-1/2 -translate-y-1/2 text-slate-400 text-sm"></i>
                </div>
            </div>

            <!-- Categories Tabs -->
            <div class="flex gap-2 overflow-x-auto pb-4 mb-6 custom-scrollbar scroll-smooth">
                <button onclick="setCategoryFilter('الكل', this)" class="category-btn active px-5 py-2.5 rounded-xl text-sm font-bold shrink-0 transition-all bg-brand-600 text-white shadow-sm">
                    🧪 الكل
                </button>
                <button onclick="setCategoryFilter('طب عام', this)" class="category-btn px-5 py-2.5 rounded-xl text-sm font-bold shrink-0 transition-all bg-slate-50 hover:bg-slate-100 text-slate-600">
                    🩺 الطب العام
                </button>
                <button onclick="setCategoryFilter('طب اسنان', this)" class="category-btn px-5 py-2.5 rounded-xl text-sm font-bold shrink-0 transition-all bg-slate-50 hover:bg-slate-100 text-slate-600">
                    🦷 طب الأسنان
                </button>
                <button onclick="setCategoryFilter('صيدلة', this)" class="category-btn px-5 py-2.5 rounded-xl text-sm font-bold shrink-0 transition-all bg-slate-50 hover:bg-slate-100 text-slate-600">
                    💊 الصيدلة
                </button>
                <button onclick="setCategoryFilter('هندسة نفط وغاز', this)" class="category-btn px-5 py-2.5 rounded-xl text-sm font-bold shrink-0 transition-all bg-slate-50 hover:bg-slate-100 text-slate-600">
                    🔥 النفط والغاز
                </button>
                <button onclick="setCategoryFilter('هندسة', this)" class="category-btn px-5 py-2.5 rounded-xl text-sm font-bold shrink-0 transition-all bg-slate-50 hover:bg-slate-100 text-slate-600">
                    ⚙️ الهندسة (عام)
                </button>
                <button onclick="setCategoryFilter('تمريض', this)" class="category-btn px-5 py-2.5 rounded-xl text-sm font-bold shrink-0 transition-all bg-slate-50 hover:bg-slate-100 text-slate-600">
                    🏥 التمريض
                </button>
                <button onclick="setCategoryFilter('علوم', this)" class="category-btn px-5 py-2.5 rounded-xl text-sm font-bold shrink-0 transition-all bg-slate-50 hover:bg-slate-100 text-slate-600">
                    🧬 العلوم والتطبيقية
                </button>
                <button onclick="setCategoryFilter('قانون', this)" class="category-btn px-5 py-2.5 rounded-xl text-sm font-bold shrink-0 transition-all bg-slate-50 hover:bg-slate-100 text-slate-600">
                    ⚖️ القانون والسياسة
                </button>
                <button onclick="setCategoryFilter('زراعة', this)" class="category-btn px-5 py-2.5 rounded-xl text-sm font-bold shrink-0 transition-all bg-slate-50 hover:bg-slate-100 text-slate-600">
                    🌱 الزراعة والبيطرة
                </button>
            </div>

            <!-- Filter Grid Options -->
            <div class="grid grid-cols-1 md:grid-cols-2 gap-4 mb-6">
                <div>
                    <label class="block text-xs font-bold text-slate-500 uppercase tracking-wider mb-2">تصفية حسب المحافظة:</label>
                    <select id="filter-governorate" onchange="filterAdmissionData()" class="w-full bg-slate-50 border border-slate-200 rounded-xl px-4 py-3 text-sm font-semibold text-slate-700 focus:outline-none focus:ring-2 focus:ring-brand-600 focus:bg-white transition-all">
                        <option value="الكل">كل المحافظات</option>
                        <option value="بغداد">بغداد</option>
                        <option value="البصرة">البصرة</option>
                        <option value="الموصل">نينوى / الموصل</option>
                        <option value="بابل">بابل</option>
                        <option value="كربلاء">كربلاء</option>
                        <option value="النجف">النجف / الكوفة</option>
                        <option value="ميسان">ميسان</option>
                        <option value="ذي قار">ذي قار</option>
                        <option value="كركوك">كركوك</option>
                        <option value="صلاح الدين">صلاح الدين / تكريت</option>
                        <option value="الانبار">الانبار</option>
                        <option value="ديالى">ديالى</option>
                        <option value="واسط">واسط</option>
                        <option value="القادسية">القادسية</option>
                        <option value="المثنى">المثنى</option>
                    </select>
                </div>
                <div>
                    <label class="block text-xs font-bold text-slate-500 uppercase tracking-wider mb-2">الفرع المطلوب:</label>
                    <select id="filter-branch" onchange="filterAdmissionData()" class="w-full bg-slate-50 border border-slate-200 rounded-xl px-4 py-3 text-sm font-semibold text-slate-700 focus:outline-none focus:ring-2 focus:ring-brand-600 focus:bg-white transition-all">
                        <option value="الكل">الكل (علمي + أدبي)</option>
                        <option value="علمي">علمي فقط</option>
                        <option value="ادبي">أدبي فقط</option>
                    </select>
                </div>
            </div>

            <!-- Results Table & Info Card Panel -->
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6">
                <!-- Data List (Table style for Desktop, Cards for Mobile) -->
                <div class="lg:col-span-8">
                    <div class="overflow-x-auto border border-slate-100 rounded-xl bg-white">
                        <table class="w-full text-right text-sm">
                            <thead class="bg-slate-50 text-slate-500 font-bold border-b border-slate-100">
                                <tr>
                                    <th class="px-4 py-3.5">الجامعة أو الكلية</th>
                                    <th class="px-4 py-3.5">المعدل</th>
                                    <th class="px-4 py-3.5">المجموع</th>
                                    <th class="px-4 py-3.5 text-center">الفرع</th>
                                    <th class="px-4 py-3.5 text-center">الخيار</th>
                                </tr>
                            </thead>
                            <tbody id="data-table-body" class="divide-y divide-slate-100">
                                <!-- Table Rows Render dynamically -->
                            </tbody>
                        </table>
                    </div>
                    <!-- Pagination info -->
                    <div class="flex items-center justify-between mt-4 text-xs text-slate-500 px-2">
                        <span id="data-count-info">عرض 10 من 120 سجل</span>
                        <div class="flex gap-2">
                            <button onclick="prevPage()" class="px-3 py-1.5 bg-slate-100 hover:bg-slate-200 rounded-lg font-bold transition-all disabled:opacity-50" id="btn-prev">السابق</button>
                            <button onclick="nextPage()" class="px-3 py-1.5 bg-slate-100 hover:bg-slate-200 rounded-lg font-bold transition-all disabled:opacity-50" id="btn-next">التالي</button>
                        </div>
                    </div>
                </div>

                <!-- Department Info Quick Card (Sticky) -->
                <div class="lg:col-span-4">
                    <div class="bg-gradient-to-br from-slate-900 to-brand-950 text-white rounded-2xl p-6 shadow-md sticky top-24" id="dept-info-card">
                        <div class="flex items-center gap-3 mb-4">
                            <div class="w-10 h-10 bg-white/10 rounded-xl flex items-center justify-center text-sky-400 text-lg border border-white/10">
                                <i class="fa-solid fa-circle-info" id="info-icon"></i>
                            </div>
                            <h4 class="font-bold text-base" id="info-title">اختر كلية لمعاينتها</h4>
                        </div>
                        <p class="text-xs text-slate-300 mb-6 leading-relaxed" id="info-desc">
                            انقر على أي صف من الكليات في الجدول أو ابحث لعرض ميزات القسم، سنوات الدراسة، والتعيين الوظيفي ومستقبل القسم في العراق فوراً.
                        </p>
                        
                        <div class="space-y-4 border-t border-white/10 pt-4 text-xs" id="info-stats">
                            <div class="flex justify-between">
                                <span class="text-slate-400">سنوات الدراسة:</span>
                                <span class="font-bold text-sky-300" id="info-years">-</span>
                            </div>
                            <div class="flex justify-between">
                                <span class="text-slate-400">حالة التعيين بالعراق:</span>
                                <span class="font-bold text-emerald-400" id="info-hiring">-</span>
                            </div>
                            <div class="flex justify-between">
                                <span class="text-slate-400">طبيعة العمل:</span>
                                <span class="font-bold text-slate-200" id="info-work">-</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- FAQ and Tips Section -->
        <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-8">
            <div class="bg-white rounded-2xl p-6 shadow-sm border border-slate-100">
                <h4 class="font-bold text-slate-900 mb-4 flex items-center gap-2">
                    <i class="fa-solid fa-lightbulb text-amber-500"></i>
                    نصائح التقديم الذكي على استمارة القبول
                </h4>
                <ul class="space-y-3 text-sm text-slate-600">
                    <li class="flex items-start gap-2.5">
                        <span class="w-1.5 h-1.5 rounded-full bg-brand-500 mt-2 shrink-0"></span>
                        <span>املأ الخيارات الأولى بالكليات التي ترغب بها بشدة حتى وإن كان معدلك أقل منها بقليل، فربما تهبط الحدود الدنيا هذا العام.</span>
                    </li>
                    <li class="flex items-start gap-2.5">
                        <span class="w-1.5 h-1.5 rounded-full bg-brand-500 mt-2 shrink-0"></span>
                        <span>انتبه جيداً لشروط بعض الكليات في المحافظات، فبعض القبولات تشترط السكن أو خاصة بأبناء المحافظة حصراً.</span>
                    </li>
                    <li class="flex items-start gap-2.5">
                        <span class="w-1.5 h-1.5 rounded-full bg-brand-500 mt-2 shrink-0"></span>
                        <span>احرص على تنويع خياراتك بين الكليات الطبية والتقنية الطبية والهندسية لضمان تأمين مقعد دراسي ممتاز.</span>
                    </li>
                </ul>
            </div>

            <div class="bg-white rounded-2xl p-6 shadow-sm border border-slate-100">
                <h4 class="font-bold text-slate-900 mb-4 flex items-center gap-2">
                    <i class="fa-solid fa-triangle-exclamation text-rose-500"></i>
                    توضيح حول حاسبة مطابقة المعدل
                </h4>
                <p class="text-sm text-slate-600 leading-relaxed mb-4">
                    الحاسبة تقوم بفلترة وعرض كافة الكليات التي قبلت معدلات مساوية لمعدلك أو أقل منه بناءً على الحدود الدنيا الرسمية المعلنة لعام 2024-2025. 
                </p>
                <div class="p-4 bg-slate-50 rounded-xl border border-slate-200/50 flex items-center gap-3">
                    <i class="fa-solid fa-info-circle text-brand-600 text-lg"></i>
                    <p class="text-xs text-slate-500">
                        ملاحظة: الحدود الدنيا قد تتغير قليلاً من عام لآخر صعوداً أو نزولاً بحسب مستويات درجات الطلاب والقدرة الاستيعابية للجامعات.
                    </p>
                </div>
            </div>
        </div>
    </main>

    <!-- Footer -->
    <footer class="bg-slate-900 text-slate-400 py-8 border-t border-slate-800 text-center text-sm">
        <div class="max-w-7xl mx-auto px-4">
            <p class="mb-2">جميع الحقوق محفوظة ومأخوذة من البيانات الرسمية لوزارة التعليم العالي والبحث العلمي العراقية © 2024-2025</p>
            <p class="text-xs text-slate-500">تم التطوير لتسهيل خيارات الطالب العراقي بأسلوب تصفح ذكي وعصري من قبل المُبرمج محمد ماجد الفريجي 2026</p>
        </div>
    </footer>

    <!-- App Logic JS -->
    <script>
        // Full structured dataset extracted from provided images of Iraq Admission Limits 2024-2025
        const admissionData = [
            // MEDICINE & HEALTH (Images 1 & 2)
            { university: "جامعة بغداد/كلية الطب", score: 101.41, sum: 709.84, fav: 295, branch: "علمي", gender: "مختلط", category: "طب عام", governorate: "بغداد" },
            { university: "جامعة بغداد/كلية طب الكندي", score: 100.77, sum: 705.36, fav: 292, branch: "علمي", gender: "مختلط", category: "طب عام", governorate: "بغداد" },
            { university: "جامعة النهرين/كلية الطب", score: 100.71, sum: 705.00, fav: 299, branch: "علمي", gender: "مختلط", category: "طب عام", governorate: "بغداد" },
            { university: "جامعة كربلاء/كلية الطب", score: 100.66, sum: 704.60, fav: 293, branch: "علمي", gender: "مختلط", category: "طب عام", governorate: "كربلاء" },
            { university: "جامعة بابل/كلية الطب", score: 100.57, sum: 704.00, fav: 299, branch: "علمي", gender: "مختلط", category: "طب عام", governorate: "بابل" },
            { university: "جامعة الكوفة/كلية الطب", score: 100.57, sum: 704.00, fav: 300, branch: "علمي", gender: "مختلط", category: "طب عام", governorate: "النجف" },
            { university: "جامعة الموصل/كلية طب الموصل", score: 100.57, sum: 703.96, fav: 291, branch: "علمي", gender: "مختلط", category: "طب عام", governorate: "الموصل" },
            { university: "جامعة كركوك/كلية الطب", score: 100.43, sum: 703.00, fav: 299, branch: "علمي", gender: "مختلط", category: "طب عام", governorate: "كركوك" },
            { university: "الجامعة المستنصرية/كلية الطب", score: 100.29, sum: 702.00, fav: 296, branch: "علمي", gender: "مختلط", category: "طب عام", governorate: "بغداد" },
            { university: "الجامعة العراقية/كلية الطب", score: 100.13, sum: 700.92, fav: 291, branch: "علمي", gender: "مختلط", category: "طب عام", governorate: "بغداد" },
            { university: "جامعة ابن سينا للعلوم الطبية والصيدلانية/كلية الطب", score: 100.10, sum: 700.72, fav: 296, branch: "علمي", gender: "مختلط", category: "طب عام", governorate: "بغداد" },
            { university: "جامعة ذي قار/كلية الطب", score: 100.04, sum: 700.28, fav: 292, branch: "علمي", gender: "مختلط", category: "طب عام", governorate: "ذي قار" },
            { university: "جامعة جابر بن حيان للعلوم الطبية والصيدلانية/كلية الطب", score: 100.00, sum: 700.00, fav: 295, branch: "علمي", gender: "مختلط", category: "طب عام", governorate: "النجف" },
            { university: "جامعة بابل/كلية طب حمورابي", score: 100.00, sum: 700.00, fav: 294, branch: "علمي", gender: "مختلط", category: "طب عام", governorate: "بابل" },
            { university: "جامعة البصرة/كلية الطب", score: 99.86, sum: 699.00, fav: 294, branch: "علمي", gender: "مختلط", category: "طب عام", governorate: "البصرة" },
            { university: "جامعة المثنى/كلية الطب/أبناء المحافظة", score: 99.86, sum: 699.00, fav: 298, branch: "علمي", gender: "مختلط", category: "طب عام", governorate: "المثنى" },
            { university: "جامعة الفلوجة/كلية الطب", score: 99.86, sum: 699.00, fav: 294, branch: "علمي", gender: "مختلط", category: "طب عام", governorate: "الانبار" },
            { university: "جامعة ديالى/كلية الطب", score: 99.86, sum: 699.00, fav: 297, branch: "علمي", gender: "مختلط", category: "طب عام", governorate: "ديالى" },
            { university: "جامعة واسط/كلية الطب", score: 99.86, sum: 699.00, fav: 300, branch: "علمي", gender: "مختلط", category: "طب عام", governorate: "واسط" },
            { university: "جامعة القادسية/كلية الطب", score: 99.86, sum: 699.00, fav: 300, branch: "علمي", gender: "مختلط", category: "طب عام", governorate: "القادسية" },
            { university: "جامعة المثنى/كلية الطب", score: 99.83, sum: 698.84, fav: 290, branch: "علمي", gender: "مختلط", category: "طب عام", governorate: "المثنى" },
            { university: "جامعة الانبار/كلية الطب", score: 99.71, sum: 698.00, fav: 293, branch: "علمي", gender: "مختلط", category: "طب عام", governorate: "الانبار" },
            { university: "جامعة نينوى/كلية الطب", score: 99.71, sum: 698.00, fav: 290, branch: "علمي", gender: "مختلط", category: "طب عام", governorate: "الموصل" },
            { university: "جامعة البصرة/كلية طب الزهراء", score: 99.71, sum: 698.00, fav: 296, branch: "علمي", gender: "مختلط", category: "طب عام", governorate: "البصرة" },
            { university: "جامعة ميسان/كلية الطب", score: 99.71, sum: 697.96, fav: 293, branch: "علمي", gender: "مختلط", category: "طب عام", governorate: "ميسان" },
            { university: "جامعة سومر/كلية الطب", score: 99.69, sum: 697.80, fav: 293, branch: "علمي", gender: "مختلط", category: "طب عام", governorate: "ذي قار" },
            { university: "جامعة الموصل/كلية طب البتول", score: 99.57, sum: 697.00, fav: 294, branch: "علمي", gender: "مختلط", category: "طب عام", governorate: "الموصل" },
            { university: "جامعة تكريت/كلية الطب", score: 99.57, sum: 697.00, fav: 298, branch: "علمي", gender: "مختلط", category: "طب عام", governorate: "صلاح الدين" },
            { university: "جامعة تكريت/كلية الطب/أبناء المحافظة", score: 99.29, sum: 695.00, fav: 300, branch: "علمي", gender: "مختلط", category: "طب عام", governorate: "صلاح الدين" },
            { university: "جامعة ميسان/كلية الطب/أبناء المحافظة", score: 98.43, sum: 689.00, fav: 294, branch: "علمي", gender: "مختلط", category: "طب عام", governorate: "ميسان" },
            
            // DENTISTRY (Image 1 continued)
            { university: "جامعة بغداد/كلية طب الاسنان", score: 99.43, sum: 696.00, fav: 297, branch: "علمي", gender: "مختلط", category: "طب اسنان", governorate: "بغداد" },
            { university: "جامعة ذي قار/كلية طب الاسنان", score: 99.29, sum: 695.00, fav: 294, branch: "علمي", gender: "مختلط", category: "طب اسنان", governorate: "ذي قار" },
            { university: "جامعة الكوفة/كلية طب الاسنان", score: 99.29, sum: 695.00, fav: 291, branch: "علمي", gender: "مختلط", category: "طب اسنان", governorate: "النجف" },
            { university: "الجامعة المستنصرية/كلية طب الاسنان", score: 99.28, sum: 694.96, fav: 293, branch: "علمي", gender: "مختلط", category: "طب اسنان", governorate: "بغداد" },
            { university: "جامعة البصرة/كلية طب الاسنان", score: 99.14, sum: 694.00, fav: 291, branch: "علمي", gender: "مختلط", category: "طب اسنان", governorate: "البصرة" },
            { university: "جامعة القادسية/كلية طب الاسنان", score: 99.00, sum: 693.00, fav: 297, branch: "علمي", gender: "مختلط", category: "طب اسنان", governorate: "القادسية" },
            { university: "جامعة ميسان/كلية طب الاسنان", score: 99.00, sum: 693.00, fav: 290, branch: "علمي", gender: "مختلط", category: "طب اسنان", governorate: "ميسان" },
            { university: "جامعة بابل/كلية طب الاسنان", score: 99.00, sum: 693.00, fav: 289, branch: "علمي", gender: "مختلط", category: "طب اسنان", governorate: "بابل" },
            { university: "جامعة كربلاء/كلية طب الاسنان", score: 99.00, sum: 693.00, fav: 293, branch: "علمي", gender: "مختلط", category: "طب اسنان", governorate: "كربلاء" },
            { university: "الجامعة العراقية/كلية طب الاسنان", score: 99.00, sum: 693.00, fav: 294, branch: "علمي", gender: "مختلط", category: "طب اسنان", governorate: "بغداد" },
            { university: "جامعة كركوك/كلية طب الاسنان", score: 98.98, sum: 692.88, fav: 292, branch: "علمي", gender: "مختلط", category: "طب اسنان", governorate: "كركوك" },
            { university: "جامعة واسط/كلية طب الاسنان", score: 98.96, sum: 692.72, fav: 289, branch: "علمي", gender: "مختلط", category: "طب اسنان", governorate: "واسط" },
            { university: "جامعة ابن سينا للعلوم الطبية والصيدلانية/كلية طب الاسنان", score: 98.86, sum: 692.00, fav: 300, branch: "علمي", gender: "مختلط", category: "طب اسنان", governorate: "بغداد" },
            { university: "جامعة المثنى/كلية طب الاسنان", score: 98.86, sum: 692.00, fav: 297, branch: "علمي", gender: "مختلط", category: "طب اسنان", governorate: "المثنى" },
            { university: "جامعة الانبار/كلية طب الاسنان", score: 98.71, sum: 691.00, fav: 292, branch: "علمي", gender: "مختلط", category: "طب اسنان", governorate: "الانبار" },
            { university: "جامعة ديالى/كلية طب الاسنان", score: 98.71, sum: 691.00, fav: 298, branch: "علمي", gender: "مختلط", category: "طب اسنان", governorate: "ديالى" },
            { university: "جامعة الموصل/كلية طب الاسنان", score: 98.71, sum: 691.00, fav: 300, branch: "علمي", gender: "مختلط", category: "طب اسنان", governorate: "الموصل" },
            { university: "جامعة تكريت/كلية طب الاسنان", score: 98.67, sum: 690.68, fav: 296, branch: "علمي", gender: "مختلط", category: "طب اسنان", governorate: "صلاح الدين" },
            
            // PHARMACY (Image 2)
            { university: "جامعة بغداد/كلية الصيدلة", score: 99.14, sum: 694.00, fav: 294, branch: "علمي", gender: "مختلط", category: "صيدلة", governorate: "بغداد" },
            { university: "جامعة الكوفة/كلية الصيدلة", score: 98.72, sum: 691.04, fav: 290, branch: "علمي", gender: "مختلط", category: "صيدلة", governorate: "النجف" },
            { university: "جامعة النهرين/كلية الصيدلة", score: 98.71, sum: 691.00, fav: 290, branch: "علمي", gender: "مختلط", category: "صيدلة", governorate: "بغداد" },
            { university: "الجامعة المستنصرية/كلية الصيدلة", score: 98.63, sum: 690.44, fav: 293, branch: "علمي", gender: "مختلط", category: "صيدلة", governorate: "بغداد" },
            { university: "جامعة البصرة/كلية الصيدلة", score: 98.57, sum: 690.00, fav: 291, branch: "علمي", gender: "مختلط", category: "صيدلة", governorate: "البصرة" },
            { university: "جامعة جابر بن حيان للعلوم الطبية والصيدلانية/كلية الصيدلة", score: 98.57, sum: 690.00, fav: 298, branch: "علمي", gender: "مختلط", category: "صيدلة", governorate: "النجف" },
            { university: "جامعة ذي قار/كلية الصيدلة", score: 98.53, sum: 689.72, fav: 291, branch: "علمي", gender: "مختلط", category: "صيدلة", governorate: "ذي قار" },
            { university: "جامعة بابل/كلية الصيدلة", score: 98.51, sum: 689.60, fav: 290, branch: "علمي", gender: "مختلط", category: "صيدلة", governorate: "بابل" },
            { university: "جامعة كربلاء/كلية الصيدلة", score: 98.51, sum: 689.56, fav: 293, branch: "علمي", gender: "مختلط", category: "صيدلة", governorate: "كربلاء" },
            { university: "جامعة القادسية/كلية الصيدلة", score: 98.48, sum: 689.36, fav: 291, branch: "علمي", gender: "مختلط", category: "صيدلة", governorate: "القادسية" },
            { university: "جامعة المثنى/كلية الصيدلة", score: 98.43, sum: 689.00, fav: 296, branch: "علمي", gender: "مختلط", category: "صيدلة", governorate: "المثنى" },
            { university: "جامعة الانبار/كلية الصيدلة", score: 98.43, sum: 689.00, fav: 291, branch: "علمي", gender: "مختلط", category: "صيدلة", governorate: "الانبار" },
            { university: "جامعة كركوك/كلية الصيدلة", score: 98.43, sum: 689.00, fav: 293, branch: "علمي", gender: "مختلط", category: "صيدلة", governorate: "كركوك" },
            { university: "جامعة ميسان/كلية الصيدلة", score: 98.43, sum: 689.00, fav: 292, branch: "علمي", gender: "مختلط", category: "صيدلة", governorate: "ميسان" },
            { university: "جامعة نينوى/كلية الصيدلة", score: 98.29, sum: 688.00, fav: 289, branch: "علمي", gender: "مختلط", category: "صيدلة", governorate: "الموصل" },
            { university: "جامعة الموصل/كلية الصيدلة", score: 98.29, sum: 688.00, fav: 295, branch: "علمي", gender: "مختلط", category: "صيدلة", governorate: "الموصل" },
            { university: "جامعة تكريت/كلية الصيدلة", score: 98.29, sum: 688.00, fav: 292, branch: "علمي", gender: "مختلط", category: "صيدلة", governorate: "صلاح الدين" },
            { university: "جامعة ميسان/كلية الصيدلة/أبناء المحافظة", score: 97.14, sum: 680.00, fav: 287, branch: "علمي", gender: "مختلط", category: "صيدلة", governorate: "ميسان" },

            // ENGINEERING (PETROLEUM & HIGH-END - Images 2 & 3)
            { university: "جامعة بغداد/كلية الهندسة-قسم العمارة", score: 98.43, sum: 689.00, fav: 292, branch: "علمي", gender: "مختلط", category: "هندسة", governorate: "بغداد" },
            { university: "جامعة البصرة للنفط والغاز/كلية هندسة النفط والغاز-قسم هندسة النفط والغاز", score: 98.14, sum: 687.00, fav: 290, branch: "علمي", gender: "مختلط", category: "هندسة نفط وغاز", governorate: "البصرة" },
            { university: "جامعة النهرين/كلية الهندسة-قسم العمارة", score: 98.03, sum: 686.20, fav: 288, branch: "علمي", gender: "مختلط", category: "هندسة", governorate: "بغداد" },
            { university: "جامعة البصرة/كلية الهندسة-قسم النفط والغاز", score: 97.91, sum: 685.40, fav: 284, branch: "علمي", gender: "مختلط", category: "هندسة نفط وغاز", governorate: "البصرة" },
            { university: "الجامعة المستنصرية/كلية الهندسة-قسم العمارة", score: 97.90, sum: 685.32, fav: 280, branch: "علمي", gender: "مختلط", category: "هندسة", governorate: "بغداد" },
            { university: "جامعة كربلاء/كلية الهندسة-قسم النفط", score: 97.71, sum: 684.00, fav: 291, branch: "علمي", gender: "مختلط", category: "هندسة نفط وغاز", governorate: "كربلاء" },
            { university: "الجامعة التكنولوجية/كلية هندسة العمارة-قسم التصميم المعماري", score: 97.71, sum: 684.00, fav: 292, branch: "علمي", gender: "مختلط", category: "هندسة", governorate: "بغداد" },
            { university: "جامعة كربلاء/كلية الهندسة-قسم العمارة", score: 97.61, sum: 683.28, fav: 287, branch: "علمي", gender: "مختلط", category: "هندسة", governorate: "كربلاء" },
            { university: "جامعة بغداد/كلية الهندسة الخوارزمي-قسم الطب الحياتي", score: 97.57, sum: 683.00, fav: 292, branch: "علمي", gender: "مختلط", category: "هندسة", governorate: "بغداد" },
            { university: "جامعة بغداد/كلية الهندسة-قسم النفط", score: 97.57, sum: 683.00, fav: 280, branch: "علمي", gender: "مختلط", category: "هندسة نفط وغاز", governorate: "بغداد" },
            { university: "جامعة الكوفة/كلية الهندسة-قسم العمارة", score: 97.47, sum: 682.28, fav: 279, branch: "علمي", gender: "مختلط", category: "هندسة", governorate: "النجف" },
            { university: "جامعة بابل/كلية الهندسة-قسم العمارة", score: 97.47, sum: 682.28, fav: 283, branch: "علمي", gender: "مختلط", category: "هندسة", governorate: "بابل" },
            { university: "جامعة البصرة/كلية الهندسة-قسم العمارة", score: 97.43, sum: 682.00, fav: 293, branch: "علمي", gender: "مختلط", category: "هندسة", governorate: "البصرة" },
            { university: "جامعة النهرين/كلية الهندسة-قسم الطب الحياتي", score: 97.43, sum: 682.00, fav: 288, branch: "علمي", gender: "مختلط", category: "هندسة", governorate: "بغداد" },
            { university: "جامعة كربلاء/كلية الهندسة-قسم الطب الحياتي", score: 97.42, sum: 681.96, fav: 284, branch: "علمي", gender: "مختلط", category: "هندسة", governorate: "كربلاء" },
            { university: "الجامعة التكنولوجية/كلية هندسة العمارة-قسم التصميم الحضري", score: 97.29, sum: 681.00, fav: 287, branch: "علمي", gender: "مختلط", category: "هندسة", governorate: "بغداد" },
            { university: "جامعة الموصل/كلية الهندسة-قسم العمارة", score: 97.29, sum: 681.00, fav: 285, branch: "علمي", gender: "مختلط", category: "هندسة", governorate: "الموصل" },
            { university: "جامعة البصرة للنفط والغاز/كلية هندسة النفط والغاز-قسم الهندسة الكيميائية وتكرير النفط", score: 97.14, sum: 680.00, fav: 286, branch: "علمي", gender: "مختلط", category: "هندسة نفط وغاز", governorate: "البصرة" },
            { university: "جامعة ميسان/كلية الهندسة-قسم النفط", score: 96.86, sum: 678.00, fav: 284, branch: "علمي", gender: "مختلط", category: "هندسة نفط وغاز", governorate: "ميسان" },
            { university: "جامعة بغداد/كلية الهندسة-قسم المدني", score: 96.71, sum: 677.00, fav: 291, branch: "علمي", gender: "مختلط", category: "هندسة", governorate: "بغداد" },
            { university: "جامعة بغداد/كلية الهندسة-قسم الطيران", score: 96.71, sum: 677.00, fav: 292, branch: "علمي", gender: "مختلط", category: "هندسة", governorate: "بغداد" },
            { university: "الجامعة التكنولوجية/كلية هندسة الطب الحياتي-قسم الاجهزة الطبية الحيوية", score: 96.57, sum: 676.00, fav: 291, branch: "علمي", gender: "مختلط", category: "هندسة", governorate: "بغداد" },
            { university: "الجامعة التكنولوجية/كلية هندسة النفط والغاز-قسم النفط", score: 96.57, sum: 676.00, fav: 289, branch: "علمي", gender: "مختلط", category: "هندسة نفط وغاز", governorate: "بغداد" },
            
            // COGNITIVE, AI, AND LAW (Images 4, 7, 8)
            { university: "جامعة تكنولوجيا المعلومات والاتصالات/كلية معلوماتية الاعمال", score: 70.14, sum: 491.00, fav: 199, branch: "علمي", gender: "مختلط", category: "علوم", governorate: "بغداد" },
            { university: "جامعة بغداد/كلية القانون", score: 92.86, sum: 650.00, fav: 187, branch: "علمي", gender: "مختلط", category: "قانون", governorate: "بغداد" },
            { university: "الجامعة المستنصرية/كلية القانون", score: 91.29, sum: 639.00, fav: 180, branch: "علمي", gender: "مختلط", category: "قانون", governorate: "بغداد" },
            { university: "جامعة البصرة/كلية القانون", score: 90.86, sum: 636.00, fav: 166, branch: "علمي", gender: "مختلط", category: "قانون", governorate: "البصرة" },
            { university: "جامعة بابل/كلية القانون", score: 83.14, sum: 582.00, fav: 187, branch: "علمي", gender: "مختلط", category: "قانون", governorate: "بابل" },
            { university: "جامعة كركوك/كلية القانون", score: 71.29, sum: 499.00, fav: 170, branch: "علمي", gender: "مختلط", category: "قانون", governorate: "كركوك" },
            { university: "جامعة واسط/كلية القانون", score: 70.00, sum: 490.00, fav: 117, branch: "ادبي", gender: "مختلط", category: "قانون", governorate: "واسط" },
            
            // NURSING & VET (Images 8 & 9)
            { university: "جامعة بغداد/كلية التمريض (إناث)", score: 96.57, sum: 676.00, fav: 284, branch: "علمي", gender: "أنثى", category: "تمريض", governorate: "بغداد" },
            { university: "جامعة بغداد/كلية التمريض (ذكور)", score: 96.43, sum: 675.00, fav: 286, branch: "علمي", gender: "ذكر", category: "تمريض", governorate: "بغداد" },
            { university: "الجامعة المستنصرية/كلية التمريض", score: 96.43, sum: 675.00, fav: 292, branch: "علمي", gender: "مختلط", category: "تمريض", governorate: "بغداد" },
            { university: "جامعة كربلاء/كلية التمريض", score: 96.00, sum: 672.00, fav: 284, branch: "علمي", gender: "مختلط", category: "تمريض", governorate: "كربلاء" },
            { university: "جامعة واسط/كلية التمريض", score: 95.71, sum: 670.00, fav: 286, branch: "علمي", gender: "مختلط", category: "تمريض", governorate: "واسط" },
            { university: "جامعة بغداد/كلية الطب البيطري", score: 83.57, sum: 585.00, fav: 253, branch: "علمي", gender: "مختلط", category: "زراعة", governorate: "بغداد" },
            { university: "جامعة بابل/كلية الطب البيطري", score: 75.71, sum: 530.00, fav: 227, branch: "علمي", gender: "مختلط", category: "زراعة", governorate: "بابل" }
        ];

        // Details database for each category
        const categoryDetails = {
            "طب عام": {
                title: "الطب العام البشري",
                icon: "fa-solid fa-user-doctor",
                years: "6 سنوات",
                hiring: "مركزي (100% مضمون في وزارة الصحة)",
                work: "طبيب مقيم دوري في المستشفيات والمراكز الطبية",
                desc: "يعد التخصص الأكثر طلباً ومكانة في العراق. يدرس فيه الطالب العلوم التشريحية، الفسيولوجية، والأمراض الباطنية والجراحية مع تدريب سريري مكثف بآخر سنتين."
            },
            "طب اسنان": {
                title: "طب وجراحة الفم والأسنان",
                icon: "fa-solid fa-teeth",
                years: "5 سنوات",
                hiring: "مركزي (حسب حاجة وزارة الصحة)",
                work: "طبيب أسنان في المراكز التخصصية والمستشفيات",
                desc: "يهتم بدراسة علاج وتقويم وتجميل الأسنان واللثة والفكين. يمتاز بالتدريب العملي في العيادات التعليمية ابتداءً من المرحلة الثالثة والعمل الحر بالعيادات الخاصة."
            },
            "صيدلة": {
                title: "علم الصيدلة والصيدلة السريرية",
                icon: "fa-solid fa-pills",
                years: "5 سنوات",
                hiring: "مركزي (وزارة الصحة)",
                work: "صيدلاني في المستشفيات الحكومية أو الصيدليات الخاصة ومصانع الأدوية",
                desc: "يركز هذا التخصص على كيمياء الأدوية، تراكيبها، تفاعلاتها بالجسم، والمهارات السريرية لصرف العلاجات وتوجيه المرضى."
            },
            "هندسة نفط وغاز": {
                title: "هندسة النفط والغاز والتكرير",
                icon: "fa-solid fa-oil-well",
                years: "4 سنوات",
                hiring: "شبه مركزي (وزارة النفط والشركات الأجنبية جولات التراخيص)",
                work: "مهندس موقعي بالحقول النفطية، مصافي النفط، أو دوائر وزارة النفط",
                desc: "من أهم التخصصات الهندسية الداعمة للاقتصاد العراقي. يركز على عمليات الحفر، استخراج وتكرير الذهب الأسود وإدارة المكامن النفطية الكبيرة."
            },
            "هندسة": {
                title: "التخصصات الهندسية (مدني، عمارة، طيران، إلخ)",
                icon: "fa-solid fa-compass-drafting",
                years: "4 إلى 5 سنوات (المعماري 5 سنوات)",
                hiring: "حسب الملاك والاحتياج (وزارة الإعمار، البلديات، القطاع الخاص)",
                work: "مهندس تصميم، إشراف موقعي، أو مستشار فني بالشركات",
                desc: "تشمل تخطيط وتصميم وبناء البنى التحتية، العمارات السكنية، وصناعة المحركات. تتطلب مهارات تفكير تحليلي ورياضيات متقدمة."
            },
            "تمريض": {
                title: "علوم التمريض",
                icon: "fa-solid fa-user-nurse",
                years: "4 سنوات",
                hiring: "مركزي (مضمون بوزارة الصحة)",
                work: "ممرض جامعي مؤهل بالرعاية الصحية الفائقة والطوارئ",
                desc: "تخصص إنساني أساسي في رعاية المرضى بالمستشفيات والعمليات الجراحية، يمنح خريجيه خلفية علمية طبية ممتازة وتعيين فوري مباشر."
            },
            "علوم": {
                title: "كليات العلوم وتقنية المعلومات",
                icon: "fa-solid fa-flask",
                years: "4 سنوات",
                hiring: "مفتوح (حسب الشواغر بوزارة الصحة، التربية، والنفط)",
                work: "محلل مختبرات، مبرمج، باحث علمي، أو تدريسي",
                desc: "تغطي كيمياء، فيزياء، علوم الحياة، وتقنية معلومات الاعمال والذكاء الاصطناعي. تمنح الخريج مهارات بحثية وتجريبية عالية جداً."
            },
            "قانون": {
                title: "القانون والعلوم السياسية",
                icon: "fa-solid fa-scale-balanced",
                years: "4 سنوات",
                hiring: "قطاع عام أو حر (مجلس القضاء الأعلى، المحاماة، الدوائر القانونية)",
                work: "محامي، مستشار قانوني، كاتب عدل، أو قاضي بعد التدرج",
                desc: "يدرس القانون الدستوري والمدني والجنائي وحقوق الإنسان. يفتح الباب للترافع بالمحاكم أو العمل كمستشار بالوزارات والقطاع الخاص."
            },
            "زراعة": {
                title: "الزراعة والطب البيطري",
                icon: "fa-solid fa-wheat-awn",
                years: "4 إلى 5 سنوات (البيطري 5 سنوات)",
                hiring: "حسب الاحتياج (وزارة الزراعة والمستشفيات البيطرية والشركات)",
                work: "طبيب بيطري، مهندس زراعي، أو مراقب جودة تغذية",
                desc: "تركز على حماية الثروة الحيوانية والزراعية والإنتاج الغذائي وتصميم المشاريع البيئية والزراعية الحديثة والمصانع التابعة لها."
            }
        };

        // State variables
        let currentCategory = "الكل";
        let currentPage = 1;
        const rowsPerPage = 10;
        let filteredList = [...admissionData];

        // Scroll helper
        function scrollToSection(id) {
            document.getElementById(id).scrollIntoView({ behavior: 'smooth' });
        }

        // Handle category tab click
        function setCategoryFilter(category, buttonEl) {
            currentCategory = category;
            
            // Toggle active styles on buttons
            document.querySelectorAll('.category-btn').forEach(btn => {
                btn.classList.remove('active', 'bg-brand-600', 'text-white', 'shadow-sm');
                btn.classList.add('bg-slate-50', 'text-slate-600');
            });
            buttonEl.classList.remove('bg-slate-50', 'text-slate-600');
            buttonEl.classList.add('active', 'bg-brand-600', 'text-white', 'shadow-sm');

            filterAdmissionData();
        }

        // Primary filter logic
        function filterAdmissionData() {
            const gov = document.getElementById('filter-governorate').value;
            const branch = document.getElementById('filter-branch').value;
            const searchVal = document.getElementById('quick-search').value.toLowerCase().trim();

            filteredList = admissionData.filter(item => {
                const matchesCategory = (currentCategory === "الكل") || (item.category === currentCategory);
                const matchesGov = (gov === "الكل") || (item.governorate === gov);
                const matchesBranch = (branch === "الكل") || (item.branch === branch);
                const matchesSearch = !searchVal || 
                                     item.university.toLowerCase().includes(searchVal) || 
                                     item.category.toLowerCase().includes(searchVal);

                return matchesCategory && matchesGov && matchesBranch && matchesSearch;
            });

            currentPage = 1;
            renderTable();
        }

        // Render data rows in table
        function renderTable() {
            const tbody = document.getElementById('data-table-body');
            tbody.innerHTML = '';

            const startIndex = (currentPage - 1) * rowsPerPage;
            const endIndex = Math.min(startIndex + rowsPerPage, filteredList.length);
            const paginatedItems = filteredList.slice(startIndex, endIndex);

            if (paginatedItems.length === 0) {
                tbody.innerHTML = `
                    <tr>
                        <td colspan="5" class="px-4 py-8 text-center text-slate-400">
                            <i class="fa-solid fa-folder-open text-3xl mb-2 block"></i>
                            لا توجد نتائج مطابقة لخيارات التصفية الحالية.
                        </td>
                    </tr>
                `;
                document.getElementById('data-count-info').textContent = 'لا توجد سجلات لعرضها';
                document.getElementById('btn-prev').disabled = true;
                document.getElementById('btn-next').disabled = true;
                return;
            }

            paginatedItems.forEach(item => {
                const tr = document.createElement('tr');
                tr.className = "hover:bg-slate-50 transition-all cursor-pointer";
                tr.onclick = () => showDepartmentInfo(item.category, item.university);

                tr.innerHTML = `
                    <td class="px-4 py-3.5 font-semibold text-slate-800">
                        ${item.university}
                    </td>
                    <td class="px-4 py-3.5 text-brand-700 font-extrabold text-base">
                        ${item.score.toFixed(2)}%
                    </td>
                    <td class="px-4 py-3.5 text-slate-600 font-medium">
                        ${item.sum.toFixed(2)}
                    </td>
                    <td class="px-4 py-3.5 text-center">
                        <span class="px-2.5 py-1 rounded-full text-xs font-bold ${item.branch === 'علمي' ? 'bg-indigo-50 text-indigo-700' : 'bg-amber-50 text-amber-700'}">
                            ${item.branch}
                        </span>
                    </td>
                    <td class="px-4 py-3.5 text-center">
                        <button class="text-brand-600 hover:text-brand-800 font-bold text-xs flex items-center gap-1 mx-auto bg-brand-50 hover:bg-brand-100 px-3 py-1.5 rounded-lg transition-all">
                            معاينة
                            <i class="fa-solid fa-chevron-left text-[10px]"></i>
                        </button>
                    </td>
                `;
                tbody.appendChild(tr);
            });

            // Update footer info & buttons
            document.getElementById('data-count-info').textContent = `عرض ${startIndex + 1} - ${endIndex} من أصل ${filteredList.length} كلية وقسم`;
            document.getElementById('btn-prev').disabled = currentPage === 1;
            document.getElementById('btn-next').disabled = endIndex >= filteredList.length;
        }

        function nextPage() {
            if ((currentPage * rowsPerPage) < filteredList.length) {
                currentPage++;
                renderTable();
            }
        }

        function prevPage() {
            if (currentPage > 1) {
                currentPage--;
                renderTable();
            }
        }

        // Show department/college description
        function showDepartmentInfo(categoryKey, exactUniversityName) {
            const card = document.getElementById('dept-info-card');
            const details = categoryDetails[categoryKey];

            if (!details) return;

            // Apply neat transition effects
            card.classList.add('scale-[0.98]', 'opacity-90');
            
            setTimeout(() => {
                document.getElementById('info-title').innerHTML = `
                    <span class="block text-sky-400 text-[10px] uppercase font-bold tracking-wider mb-0.5">${details.title}</span>
                    <span class="text-white text-sm font-semibold">${exactUniversityName}</span>
                `;
                document.getElementById('info-desc').textContent = details.desc;
                document.getElementById('info-years').textContent = details.years;
                document.getElementById('info-hiring').textContent = details.hiring;
                document.getElementById('info-work').textContent = details.work;
                
                // Update icon inside info box
                const iconContainer = document.getElementById('info-icon');
                iconContainer.className = `${details.icon} text-lg`;

                card.classList.remove('scale-[0.98]', 'opacity-90');
            }, 150);
        }

        // Smart Calculator Logic
        function calculateAdmission() {
            const rawScore = document.getElementById('user-score').value;
            const branch = document.getElementById('user-branch').value;
            const gov = document.getElementById('user-governorate').value;

            const resultsSection = document.getElementById('calculator-results');
            const resultsGrid = document.getElementById('results-grid');
            const resultsCount = document.getElementById('results-count');

            if (!rawScore || isNaN(rawScore) || rawScore < 50 || rawScore > 105) {
                alert("الرجاء إدخال معدل صحيح بين 50 و 105.");
                return;
            }

            const parsedScore = parseFloat(rawScore);

            // Filter data according to score
            const matchedData = admissionData.filter(item => {
                const matchesScore = item.score <= parsedScore;
                const matchesBranch = (branch === "الكل") || (item.branch === branch);
                const matchesGov = (gov === "الكل") || (item.governorate === gov);
                return matchesScore && matchesBranch && matchesGov;
            });

            // Sort matched data so the closest to student's score appears first (highest likelihood)
            matchedData.sort((a, b) => b.score - a.score);

            resultsGrid.innerHTML = '';
            resultsCount.textContent = `${matchedData.length} كلية متاحة`;

            if (matchedData.length === 0) {
                resultsGrid.innerHTML = `
                    <div class="col-span-full py-12 text-center bg-slate-50 rounded-2xl border border-slate-100">
                        <i class="fa-solid fa-face-frown text-4xl text-slate-300 mb-3"></i>
                        <p class="font-bold text-slate-500">للأسف، لم نجد كليات تطابق هذا المعدل في تصنيفاتنا الحالية.</p>
                        <p class="text-xs text-slate-400 mt-1">حاول توسيع نطاق البحث الجغرافي أو التحقق من القبولات الإنسانية الأخرى.</p>
                    </div>
                `;
            } else {
                matchedData.forEach(item => {
                    const diff = (parsedScore - item.score).toFixed(2);
                    const card = document.createElement('div');
                    card.className = "bg-white p-4 rounded-xl border border-slate-100 shadow-sm hover:shadow-md transition-all flex flex-col justify-between cursor-pointer";
                    card.onclick = () => {
                        scrollToSection('explorer');
                        // Pre-populate search and search for this university
                        document.getElementById('quick-search').value = item.university;
                        filterAdmissionData();
                        showDepartmentInfo(item.category, item.university);
                    };

                    card.innerHTML = `
                        <div>
                            <div class="flex justify-between items-start mb-2">
                                <span class="bg-brand-50 text-brand-700 text-[10px] font-bold px-2.5 py-1 rounded-md">
                                    ${item.category}
                                </span>
                                <span class="text-xs text-slate-400 font-semibold">${item.governorate}</span>
                            </div>
                            <h5 class="font-bold text-slate-800 text-sm mb-2 line-clamp-2">${item.university}</h5>
                        </div>
                        <div class="flex items-end justify-between border-t border-slate-50 pt-3 mt-3">
                            <div>
                                <span class="text-[10px] text-slate-400 block">الحد الأدنى</span>
                                <span class="font-extrabold text-slate-800 text-sm">%${item.score.toFixed(2)}</span>
                            </div>
                            <div class="text-left">
                                <span class="text-[10px] text-emerald-500 block font-bold">معدلك أعلى بـ:</span>
                                <span class="font-extrabold text-emerald-600 text-sm">+${diff}%</span>
                            </div>
                        </div>
                    `;
                    resultsGrid.appendChild(card);
                });
            }

            resultsSection.classList.remove('hidden');
            // Scroll down a bit to see the results
            resultsSection.scrollIntoView({ behavior: 'smooth' });
        }

        // Initialize App
        window.onload = function() {
            // Fill default explorer panel on start
            filterAdmissionData();
            // Show default info as the first medical university
            showDepartmentInfo("طب عام", "جامعة بغداد/كلية الطب");
        }
    </script>
</body>
</html>

```
