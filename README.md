# Portfolio
<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shravan Mahadik | Full-Stack Web Developer & IT Professional</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brandRed: '#e63946',
                        darkBg: '#0b0b0b',
                        cardBg: '#141414',
                        cardBorder: '#222222'
                    }
                }
            }
        }
    </script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;600;700;800&family=Syne:wght@700;800&display=swap');
        body { font-family: 'Plus Jakarta Sans', sans-serif; }
        .font-syne { font-family: 'Syne', sans-serif; }
        .hide-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .hide-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }

        /* Custom Animations */
        @keyframes fadeInDown {
            from { opacity: 0; transform: translateY(-20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        @keyframes fadeInUp {
            from { opacity: 0; transform: translateY(30px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .animate-fade-down {
            animation: fadeInDown 0.8s ease-out forwards;
        }

        .animate-fade-up {
            animation: fadeInUp 0.8s ease-out forwards;
        }

        /* Smooth Card Hover Glow Animation */
        .hover-card-effect {
            transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
        }
        .hover-card-effect:hover {
            transform: translateY(-6px);
            border-color: rgba(230, 57, 70, 0.6);
            box-shadow: 0 15px 30px -10px rgba(230, 57, 70, 0.2);
        }
    </style>
</head>
<body class="bg-darkBg text-slate-200 selection:bg-brandRed selection:text-white overflow-x-hidden">

    <!-- Top Navigation -->
    <nav class="sticky top-0 z-50 bg-darkBg/95 backdrop-blur-md border-b border-slate-900 animate-fade-down">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-4 flex flex-col md:flex-row justify-between items-center gap-4 text-xs tracking-widest uppercase text-slate-400">
            <div class="text-white font-bold font-syne text-sm tracking-wider hover:text-brandRed transition">SHRAVAN MAHADIK</div>
            <div class="flex items-center gap-4 sm:gap-6 font-medium flex-wrap justify-center">
                <a href="#about" class="hover:text-brandRed transition">About</a>
                <a href="#projects" class="hover:text-brandRed transition">Projects</a>
                <a href="#skills" class="hover:text-brandRed transition">Skills</a>
                <a href="#education" class="hover:text-brandRed transition">Education</a>
                <a href="#certifications" class="hover:text-brandRed transition">Certifications</a>
                <a href="#contact" class="hover:text-brandRed transition">Contact</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section / About -->
    <header id="about" class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-16 sm:py-24 relative overflow-hidden animate-fade-up">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-10 lg:gap-12 items-center">
            <div class="lg:col-span-8 space-y-6">
                <div class="inline-block bg-brandRed/10 border border-brandRed/30 px-3.5 py-1.5 rounded-full text-brandRed text-xs font-bold uppercase tracking-wider animate-pulse">
                    Welcome To My Portfolio
                </div>
                <h1 class="font-syne text-4xl sm:text-6xl lg:text-7xl font-extrabold text-white tracking-tight leading-none uppercase">
                    SHRAVAN<br/>MAHADIK
                </h1>
                <p class="text-brandRed font-bold tracking-wider text-sm sm:text-base uppercase">
                    Full-Stack Web Developer & IT Professional
                </p>
                <p class="text-slate-400 max-w-2xl text-sm sm:text-base leading-relaxed">
                    Motivated Web Developer skilled in HTML, CSS, JavaScript, Python, MySQL, and MongoDB. Passionate about building scalable applications and clean web interfaces.
                </p>
                <div class="flex flex-wrap gap-4 pt-2">
                    <a href="#projects" class="bg-brandRed text-white px-6 py-3.5 rounded-xl font-bold text-xs uppercase tracking-wider hover:bg-red-700 transition shadow-lg shadow-brandRed/20 transform hover:-translate-y-0.5">View Projects</a>
                    <a href="#contact" class="bg-cardBg border border-cardBorder text-slate-300 px-6 py-3.5 rounded-xl font-bold text-xs uppercase tracking-wider hover:border-brandRed transition transform hover:-translate-y-0.5">Get In Touch</a>
                </div>
            </div>

            <div class="lg:col-span-4 flex flex-col justify-center space-y-5 bg-cardBg border border-cardBorder p-6 sm:p-8 rounded-2xl shadow-xl hover-card-effect">
                <div>
                    <h3 class="text-3xl font-extrabold text-brandRed font-syne">100%</h3>
                    <p class="text-xs text-slate-400 uppercase tracking-wider mt-1">Project Commitment</p>
                </div>
                <div class="border-t border-slate-800 pt-4">
                    <h3 class="text-3xl font-extrabold text-white font-syne">4+</h3>
                    <p class="text-xs text-slate-400 uppercase tracking-wider mt-1">Key Tech Projects</p>
                </div>
                <div class="border-t border-slate-800 pt-4">
                    <h3 class="text-3xl font-extrabold text-white font-syne">MMS & B.Sc</h3>
                    <p class="text-xs text-slate-400 uppercase tracking-wider mt-1">IT Background</p>
                </div>
            </div>
        </div>
    </header>

    <!-- Selected Projects Section with Slider -->
    <section id="projects" class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-16 sm:py-24 border-t border-slate-900">
        <div class="flex justify-between items-end mb-10">
            <div>
                <span class="text-brandRed font-bold text-xs uppercase tracking-widest">Featured Work</span>
                <h2 class="font-syne text-3xl sm:text-4xl font-extrabold text-white uppercase mt-1">SELECTED PROJECTS</h2>
            </div>
            <div class="hidden sm:flex gap-3">
                <button onclick="document.getElementById('project-slider').scrollBy({left: -380, behavior: 'smooth'})" class="w-11 h-11 rounded-xl bg-cardBg border border-cardBorder text-white hover:border-brandRed flex items-center justify-center transition shadow-md hover:scale-105">
                    <i class="fa-solid fa-arrow-left"></i>
                </button>
                <button onclick="document.getElementById('project-slider').scrollBy({left: 380, behavior: 'smooth'})" class="w-11 h-11 rounded-xl bg-cardBg border border-cardBorder text-white hover:border-brandRed flex items-center justify-center transition shadow-md hover:scale-105">
                    <i class="fa-solid fa-arrow-right"></i>
                </button>
            </div>
        </div>

        <!-- Slider Container -->
        <div id="project-slider" class="flex overflow-x-auto gap-6 pb-6 pt-2 hide-scrollbar snap-x snap-mandatory">
            
            <!-- Project 01 -->
            <div class="min-w-[300px] sm:min-w-[380px] max-w-[380px] bg-cardBg border border-cardBorder rounded-2xl p-6 sm:p-8 hover-card-effect flex flex-col justify-between snap-start shadow-xl">
                <div>
                    <div class="aspect-video bg-slate-900 rounded-xl mb-6 border border-slate-800 flex items-center justify-center text-slate-600 group-hover:text-brandRed transition">
                        <i class="fa-solid fa-building-columns text-4xl group-hover:scale-110 transition duration-300"></i>
                    </div>
                    <div class="flex items-center gap-3">
                        <span class="text-brandRed font-syne text-2xl font-bold">01</span>
                        <h3 class="text-white font-bold text-lg group-hover:text-brandRed transition">ATM Management System</h3>
                    </div>
                    <p class="text-slate-400 text-xs sm:text-sm mt-3 leading-relaxed">
                        Console-based banking application built with Python. Features account management, deposit, withdrawal, and balance inquiry features.
                    </p>
                </div>
                <div class="mt-6 pt-4 border-t border-slate-800/80 flex justify-between items-center text-xs text-slate-500">
                    <span class="text-slate-300 font-medium">Python </span>
                    <i class="fa-solid fa-arrow-right group-hover:translate-x-1 group-hover:text-brandRed transition"></i>
                </div>
            </div>

            <!-- Project 02 -->
            <div class="min-w-[300px] sm:min-w-[380px] max-w-[380px] bg-cardBg border border-cardBorder rounded-2xl p-6 sm:p-8 hover-card-effect flex flex-col justify-between snap-start shadow-xl">
                <div>
                    <div class="aspect-video bg-slate-900 rounded-xl mb-6 border border-slate-800 flex items-center justify-center text-slate-600 group-hover:text-brandRed transition">
                        <i class="fa-solid fa-key text-4xl group-hover:scale-110 transition duration-300"></i>
                    </div>
                    <div class="flex items-center gap-3">
                        <span class="text-brandRed font-syne text-2xl font-bold">02</span>
                        <h3 class="text-white font-bold text-lg group-hover:text-brandRed transition">Password Generator</h3>
                    </div>
                    <p class="text-slate-400 text-xs sm:text-sm mt-3 leading-relaxed">
                        Created a secure password generation tool using randomization techniques with user-defined password length and complexity options.
                    </p>
                </div>
                <div class="mt-6 pt-4 border-t border-slate-800/80 flex justify-between items-center text-xs text-slate-500">
                    <span class="text-slate-300 font-medium">Python </span>
                    <i class="fa-solid fa-arrow-right group-hover:translate-x-1 group-hover:text-brandRed transition"></i>
                </div>
            </div>

            <!-- Project 03 -->
            <div class="min-w-[300px] sm:min-w-[380px] max-w-[380px] bg-cardBg border border-cardBorder rounded-2xl p-6 sm:p-8 hover-card-effect flex flex-col justify-between snap-start shadow-xl">
                <div>
                    <div class="aspect-video bg-slate-900 rounded-xl mb-6 border border-slate-800 flex items-center justify-center text-slate-600 group-hover:text-brandRed transition">
                        <i class="fa-solid fa-gamepad text-4xl group-hover:scale-110 transition duration-300"></i>
                    </div>
                    <div class="flex items-center gap-3">
                        <span class="text-brandRed font-syne text-2xl font-bold">03</span>
                        <h3 class="text-white font-bold text-lg group-hover:text-brandRed transition">Rock, Paper, Scissors Game</h3>
                    </div>
                    <p class="text-slate-400 text-xs sm:text-sm mt-3 leading-relaxed">
                        Built an interactive command-line game using Python logic for smooth user experience and automated opponent moves.
                    </p>
                </div>
                <div class="mt-6 pt-4 border-t border-slate-800/80 flex justify-between items-center text-xs text-slate-500">
                    <span class="text-slate-300 font-medium">Python </span>
                    <i class="fa-solid fa-arrow-right group-hover:translate-x-1 group-hover:text-brandRed transition"></i>
                </div>
            </div>

            <!-- Project 04 -->
            <div class="min-w-[300px] sm:min-w-[380px] max-w-[380px] bg-cardBg border border-cardBorder rounded-2xl p-6 sm:p-8 hover-card-effect flex flex-col justify-between snap-start shadow-xl">
                <div>
                    <div class="aspect-video bg-slate-900 rounded-xl mb-6 border border-slate-800 flex items-center justify-center text-slate-600 group-hover:text-brandRed transition">
                        <i class="fa-solid fa-database text-4xl group-hover:scale-110 transition duration-300"></i>
                    </div>
                    <div class="flex items-center gap-3">
                        <span class="text-brandRed font-syne text-2xl font-bold">04</span>
                        <h3 class="text-white font-bold text-lg group-hover:text-brandRed transition">Database Management Projects</h3>
                    </div>
                    <p class="text-slate-400 text-xs sm:text-sm mt-3 leading-relaxed">
                        Designed and managed Student, IPL, HR, and Vendor databases executing complex queries and optimized CRUD operations in SQL.
                    </p>
                </div>
                <div class="mt-6 pt-4 border-t border-slate-800/80 flex justify-between items-center text-xs text-slate-500">
                    <span class="text-slate-300 font-medium">MySQL </span>
                    <i class="fa-solid fa-arrow-right group-hover:translate-x-1 group-hover:text-brandRed transition"></i>
                </div>
            </div>

        </div>
    </section>

    <!-- Technical Skills Section -->
    <section id="skills" class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-16 sm:py-24 border-t border-slate-900">
        <div class="mb-12">
            <span class="text-brandRed font-bold text-xs uppercase tracking-widest">Expertise</span>
            <h2 class="font-syne text-3xl sm:text-4xl font-extrabold text-white uppercase mt-1">TECHNICAL SKILLS</h2>
        </div>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">
            <div class="bg-cardBg border border-cardBorder p-6 sm:p-8 rounded-2xl hover-card-effect shadow-lg">
                <div class="w-12 h-12 rounded-xl bg-slate-900 border border-slate-800 flex items-center justify-center text-brandRed mb-5">
                    <i class="fa-solid fa-code text-xl"></i>
                </div>
                <h3 class="text-white font-bold text-base mb-2">Programming</h3>
                <p class="text-slate-400 text-xs sm:text-sm leading-relaxed">Python, JavaScript, C</p>
            </div>

            <div class="bg-cardBg border border-cardBorder p-6 sm:p-8 rounded-2xl hover-card-effect shadow-lg">
                <div class="w-12 h-12 rounded-xl bg-slate-900 border border-slate-800 flex items-center justify-center text-brandRed mb-5">
                    <i class="fa-solid fa-globe text-xl"></i>
                </div>
                <h3 class="text-white font-bold text-base mb-2">Web Technologies</h3>
                <p class="text-slate-400 text-xs sm:text-sm leading-relaxed">HTML5, CSS3, JavaScript, Bootstrap</p>
            </div>

            <div class="bg-cardBg border border-cardBorder p-6 sm:p-8 rounded-2xl hover-card-effect shadow-lg">
                <div class="w-12 h-12 rounded-xl bg-slate-900 border border-slate-800 flex items-center justify-center text-brandRed mb-5">
                    <i class="fa-solid fa-database text-xl"></i>
                </div>
                <h3 class="text-white font-bold text-base mb-2">Databases</h3>
                <p class="text-slate-400 text-xs sm:text-sm leading-relaxed">MySQL, MongoDB</p>
            </div>

            <div class="bg-cardBg border border-cardBorder p-6 sm:p-8 rounded-2xl hover-card-effect shadow-lg">
                <div class="w-12 h-12 rounded-xl bg-slate-900 border border-slate-800 flex items-center justify-center text-brandRed mb-5">
                    <i class="fa-solid fa-toolbox text-xl"></i>
                </div>
                <h3 class="text-white font-bold text-base mb-2">Tools & Software</h3>
                <p class="text-slate-400 text-xs sm:text-sm leading-relaxed">MS Office, Photoshop, CorelDRAW, Illustrator, Tally Prime, GST</p>
            </div>
        </div>
    </section>

    <!-- Education Section -->
    <section id="education" class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-16 sm:py-24 border-t border-slate-900">
        <div class="mb-12">
            <span class="text-brandRed font-bold text-xs uppercase tracking-widest">Academic History</span>
            <h2 class="font-syne text-3xl sm:text-4xl font-extrabold text-white uppercase mt-1">EDUCATION</h2>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
            <div class="bg-cardBg border border-cardBorder p-6 sm:p-8 rounded-2xl hover-card-effect shadow-lg">
                <div class="flex justify-between items-center text-xs text-brandRed font-semibold mb-3">
                    <span>Kala Institute of Management Studies & Research</span>
                    <span class="bg-brandRed/10 px-2.5 py-1 rounded-md">2025</span>
                </div>
                <h3 class="text-white font-bold text-base sm:text-lg">Masters in Management Studies (MMS) in Information Technology</h3>
            </div>

            <div class="bg-cardBg border border-cardBorder p-6 sm:p-8 rounded-2xl hover-card-effect shadow-lg">
                <div class="flex justify-between items-center text-xs text-brandRed font-semibold mb-3">
                    <span>Maha Kaushal University</span>
                    <span class="bg-brandRed/10 px-2.5 py-1 rounded-md">2022 - 2025</span>
                </div>
                <h3 class="text-white font-bold text-base sm:text-lg">B.Sc. in Information Technology</h3>
            </div>

            <div class="bg-cardBg border border-cardBorder p-6 sm:p-8 rounded-2xl hover-card-effect shadow-lg">
                <div class="flex justify-between items-center text-xs text-brandRed font-semibold mb-3">
                    <span>Navodaya Junior College of Science & Commerce</span>
                    <span class="bg-brandRed/10 px-2.5 py-1 rounded-md">2020 - 2022</span>
                </div>
                <h3 class="text-white font-bold text-base sm:text-lg">Higher Secondary Education</h3>
            </div>

            <div class="bg-cardBg border border-cardBorder p-6 sm:p-8 rounded-2xl hover-card-effect shadow-lg">
                <div class="flex justify-between items-center text-xs text-brandRed font-semibold mb-3">
                    <span>Bal Vidya Mandir</span>
                    <span class="bg-brandRed/10 px-2.5 py-1 rounded-md">2009 - 2020</span>
                </div>
                <h3 class="text-white font-bold text-base sm:text-lg">Secondary Education</h3>
            </div>
        </div>
    </section>

    <!-- Certifications Section -->
    <section id="certifications" class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-16 sm:py-24 border-t border-slate-900">
        <div class="mb-12">
            <span class="text-brandRed font-bold text-xs uppercase tracking-widest">Credentials</span>
            <h2 class="font-syne text-3xl sm:text-4xl font-extrabold text-white uppercase mt-1">CERTIFICATIONS</h2>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
            <div class="bg-cardBg border border-cardBorder p-6 sm:p-8 rounded-2xl hover-card-effect flex items-start gap-5 shadow-lg">
                <div class="w-12 h-12 rounded-xl bg-slate-900 border border-slate-800 flex items-center justify-center text-brandRed shrink-0">
                    <i class="fa-solid fa-certificate text-xl"></i>
                </div>
                <div>
                    <span class="inline-block text-xs text-brandRed font-semibold bg-brandRed/10 px-2.5 py-1 rounded-md mb-2">2026</span>
                    <h3 class="text-white font-bold text-base sm:text-lg">Web Development using Python</h3>
                    <p class="text-slate-400 text-xs sm:text-sm mt-2 leading-relaxed">Comprehensive training covering front-end JavaScript, python back-end integration, and database management.</p>
                </div>
            </div>

            <div class="bg-cardBg border border-cardBorder p-6 sm:p-8 rounded-2xl hover-card-effect flex items-start gap-5 shadow-lg">
                <div class="w-12 h-12 rounded-xl bg-slate-900 border border-slate-800 flex items-center justify-center text-brandRed shrink-0">
                    <i class="fa-solid fa-award text-xl"></i>
                </div>
                <div>
                    <span class="inline-block text-xs text-brandRed font-semibold bg-brandRed/10 px-2.5 py-1 rounded-md mb-2">2025</span>
                    <h3 class="text-white font-bold text-base sm:text-lg">Diploma in Graphics and Automation</h3>
                    <p class="text-slate-400 text-xs sm:text-sm mt-2 leading-relaxed">Specialized training in modern graphic design tools including Photoshop, Illustrator, and CorelDRAW.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Let's Work Together Footer -->
    <footer id="contact" class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-16 sm:py-24 border-t border-slate-900">
        <div class="grid grid-cols-1 lg:grid-cols-2 gap-10 lg:gap-16 items-center">
            <div>
                <span class="text-brandRed font-bold text-xs uppercase tracking-widest">Get In Touch</span>
                <h2 class="font-syne text-4xl sm:text-5xl font-extrabold text-white uppercase mt-1">LET'S WORK<br/>TOGETHER</h2>
                <p class="text-slate-400 text-sm sm:text-base mt-4 max-w-md leading-relaxed">Currently open for full-time web developer roles and exciting technical projects.</p>
            </div>

            <div class="bg-cardBg border border-cardBorder p-6 sm:p-8 rounded-2xl space-y-5 shadow-xl hover-card-effect">
                <div class="flex items-center gap-4 text-sm">
                    <div class="w-12 h-12 rounded-xl bg-slate-900 border border-slate-800 flex items-center justify-center text-brandRed shrink-0">
                        <i class="fa-solid fa-envelope"></i>
                    </div>
                    <div>
                        <p class="text-xs text-slate-500 uppercase">Email</p>
                        <a href="mailto:mahadikshravan1976@gmail.com" class="text-white hover:text-brandRed font-medium text-xs sm:text-sm break-all">mahadikshravan1976@gmail.com</a>
                    </div>
                </div>

                <div class="flex items-center gap-4 text-sm border-t border-slate-800/80 pt-4">
                    <div class="w-12 h-12 rounded-xl bg-slate-900 border border-slate-800 flex items-center justify-center text-brandRed shrink-0">
                        <i class="fa-solid fa-phone"></i>
                    </div>
                    <div>
                        <p class="text-xs text-slate-500 uppercase">Phone</p>
                        <a href="tel:+917304778273" class="text-white hover:text-brandRed font-medium text-xs sm:text-sm">+91 7304778273</a>
                    </div>
                </div>

                <div class="flex items-center gap-4 text-sm border-t border-slate-800/80 pt-4">
                    <div class="w-12 h-12 rounded-xl bg-slate-900 border border-slate-800 flex items-center justify-center text-brandRed shrink-0">
                        <i class="fa-solid fa-location-dot"></i>
                    </div>
                    <div>
                        <p class="text-xs text-slate-500 uppercase">Location</p>
                        <p class="text-white font-medium text-xs sm:text-sm">Ghansoli, Navi Mumbai - 400701</p>
                    </div>
                </div>
            </div>
        </div>

        <div class="mt-16 text-center text-xs text-slate-600 border-t border-slate-900 pt-8">
            © 2026 Shravan Dinesh Mahadik. Designed & Built for Web Developers.
        </div>
    </footer>

    <!-- JavaScript for subtle interactive effects -->
    <script>
        console.log("Shravan Mahadik Portfolio Initialized with Animations!");
    </script>
</body>
</html>
