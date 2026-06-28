This is the first version of html files for TGRF

<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tele-Geriatric Research Fellowship | TGRF</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            50: '#f0fdfa',
                            100: '#ccfbf1',
                            600: '#0d9488',
                            700: '#0f766e',
                            900: '#115e59',
                        }
                    }
                }
            }
        }
    </script>
</head>
<body class="bg-slate-50 text-slate-800 antialiased font-sans">

    <!-- Header / Navigation -->
    <header class="sticky top-0 z-50 bg-white/90 backdrop-blur-md border-b border-slate-200">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-20">
                <div class="flex items-center space-x-3">
                    <div class="bg-brand-600 text-white p-2.5 rounded-xl shadow-md">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 11H5m14 0a2 2 0 012 2v6a2 2 0 01-2 2H5a2 2 0 01-2-2v-6a2 2 0 012-2m14 0V9a2 2 0 00-2-2M5 11V9a2 2 0 012-2m0 0V5a2 2 0 012-2h6a2 2 0 012 2v2M7 7h10"></path>
                        </svg>
                    </div>
                    <div>
                        <span class="text-xl font-bold tracking-tight text-slate-900 block leading-none">TGRF</span>
                        <span class="text-xs text-slate-500 font-medium tracking-wide uppercase">Tele-Geriatric Research</span>
                    </div>
                </div>
                <nav class="hidden md:flex space-x-8 items-center font-medium text-slate-600">
                    <a href="#about" class="hover:text-brand-600 transition">About</a>
                    <a href="#timeline" class="hover:text-brand-600 transition">Timeline</a>
                    <a href="#curriculum" class="hover:text-brand-600 transition">Curriculum</a>
                    <a href="#impact" class="hover:text-brand-600 transition">Impact</a>
                    <a href="#apply" class="bg-brand-600 text-white px-5 py-2.5 rounded-lg hover:bg-brand-700 shadow-sm transition">Apply Now</a>
                </nav>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="relative bg-white overflow-hidden py-20 lg:py-32 border-b border-slate-100">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="max-w-3xl">
                <span class="inline-flex items-center px-3 py-1 rounded-full text-sm font-medium bg-brand-50 text-brand-700 mb-6">
                    Combined Research Foundation Framework
                </span>
                <h1 class="text-4xl sm:text-5xl lg:text-6xl font-extrabold text-slate-900 tracking-tight mb-6">
                    Shaping the Future of <span class="text-brand-600">Tele-Geriatric Care</span>
                </h1>
                <p class="text-xl text-slate-600 mb-10 leading-relaxed">
                    Empowering international and unmatched medical graduates through high-impact virtual research excellence, structured clinical decision frameworks, and dedicated mentorship.
                </p>
                <div class="flex flex-col sm:flex-row gap-4">
                    <a href="#apply" class="inline-flex justify-center items-center px-6 py-3.5 border border-transparent text-base font-medium rounded-xl text-white bg-brand-600 hover:bg-brand-700 shadow-md transition">
                        Apply for Fellowship
                    </a>
                    <a href="#about" class="inline-flex justify-center items-center px-6 py-3.5 border border-slate-200 text-base font-medium rounded-xl text-slate-700 bg-slate-50 hover:bg-slate-100 transition">
                        Explore Our Program
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="bg-gradient-to-br from-brand-900 to-slate-900 rounded-3xl p-8 sm:p-12 text-white shadow-xl">
            <div class="max-w-3xl">
                <h2 class="text-3xl font-bold tracking-tight mb-4">Our Mission</h2>
                <p class="text-brand-100 text-lg leading-relaxed mb-6">
                    Originally supported via the Pearl J. Aldrich Endowment, the Tele-Geriatric Research Fellowship translates raw clinical capability into peer-reviewed publication success and career match-readiness. We mitigate provider bottlenecks by arming virtual cohorts with statistical, analytical, and digital health competencies.
                </p>
                <blockquote class="border-l-4 border-brand-100 pl-4 italic text-slate-300">
                    "Bridging the structural gap between outstanding unmatched medical talent and critical developments in global aging health frameworks."
                </blockquote>
            </div>
        </div>
    </section>

    <!-- Curriculum Timeline -->
    <section id="timeline" class="py-20 bg-white border-y border-slate-100">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <h2 class="text-3xl font-bold text-slate-900">Fellowship Development Timeline</h2>
                <p class="text-slate-500 mt-2">A methodical, year-long virtual framework driving concepts from raw clinical inquiry to national dissemination.</p>
            </div>
            
            <div class="space-y-8 max-w-4xl mx-auto">
                <div class="flex flex-col md:flex-row gap-4 md:gap-8 bg-slate-50 p-6 rounded-2xl border border-slate-100">
                    <div class="md:w-1/4 font-bold text-brand-700 text-lg">Weeks 1 - 4</div>
                    <div class="md:w-3/4">
                        <h3 class="text-xl font-bold text-slate-900 mb-1">Phase 1: Foundations & Ethics</h3>
                        <p class="text-slate-600">Establish foundational research competencies based on the entering research syllabus, literature validation methods, and baseline research ethics standards.</p>
                    </div>
                </div>
                <div class="flex flex-col md:flex-row gap-4 md:gap-8 bg-slate-50 p-6 rounded-2xl border border-slate-100">
                    <div class="md:w-1/4 font-bold text-brand-700 text-lg">Weeks 5 - 12</div>
                    <div class="md:w-3/4">
                        <h3 class="text-xl font-bold text-slate-900 mb-1">Phase 2: Project Formulation</h3>
                        <p class="text-slate-600">Cohorts connect directly with faculty mentors, formulate definitive clinical trial or meta-analysis proposals, and solidify research team frameworks.</p>
                    </div>
                </div>
                <div class="flex flex-col md:flex-row gap-4 md:gap-8 bg-slate-50 p-6 rounded-2xl border border-slate-100">
                    <div class="md:w-1/4 font-bold text-brand-700 text-lg">Weeks 13 - 24</div>
                    <div class="md:w-3/4">
                        <h3 class="text-xl font-bold text-slate-900 mb-1">Phase 3: Data Management & Tools</h3>
                        <p class="text-slate-600">Practical application of medical informatics systems, statistical packages (SPSS, RStudio), and bibliographic managers (EndNote).</p>
                    </div>
                </div>
                <div class="flex flex-col md:flex-row gap-4 md:gap-8 bg-slate-50 p-6 rounded-2xl border border-slate-100">
                    <div class="md:w-1/4 font-bold text-brand-700 text-lg">Weeks 25 - 52</div>
                    <div class="md:w-3/4">
                        <h3 class="text-xl font-bold text-slate-900 mb-1">Phase 4: Dissemination & Match Preparation</h3>
                        <p class="text-slate-600">Writing scientific manuscripts and building visual presentations for national medical symposia (AGS, AMDA) alongside intentional residency Match strategy design.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Impact & Metrics -->
    <section id="impact" class="py-20 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="text-center max-w-3xl mx-auto mb-16">
            <h2 class="text-3xl font-bold text-slate-900">Our Strategic Impact</h2>
            <p class="text-slate-500 mt-2">Demonstrated milestones delivered by our active virtual research labs.</p>
        </div>
        
        <div class="overflow-hidden bg-white shadow-sm border border-slate-200 rounded-2xl">
            <table class="min-w-full divide-y divide-slate-200 text-left">
                <thead class="bg-slate-50">
                    <tr>
                        <th class="px-6 py-4 font-semibold text-slate-900">Performance Metric</th>
                        <th class="px-6 py-4 font-semibold text-slate-900">Observed Output</th>
                        <th class="px-6 py-4 font-semibold text-slate-900">Core Significance</th>
                    </tr>
                </thead>
                <tbody class="divide-y divide-slate-200 text-slate-600">
                    <tr>
                        <td class="px-6 py-4 font-medium text-slate-950">Residency Match Success</td>
                        <td class="px-6 py-4">Consistent placement across cohorts</td>
                        <td class="px-6 py-4">Directly fills the growing U.S. geriatrician provider deficit.</td>
                    </tr>
                    <tr>
                        <td class="px-6 py-4 font-medium text-slate-950">Abstract Dissemination</td>
                        <td class="px-6 py-4">24+ National Accepted Posters</td>
                        <td class="px-6 py-4">Showcased at frontline medical hubs including AMDA and AGS.</td>
                    </tr>
                    <tr>
                        <td class="px-6 py-4 font-medium text-slate-950">Framework Governance</td>
                        <td class="px-6 py-4">Independent 501(c)(3) Entity</td>
                        <td class="px-6 py-4">Sustained administration via the Combined Research Foundation.</td>
                    </tr>
                </tbody>
            </table>
        </div>
    </section>

    <!-- Application / Checklist Section -->
    <section id="apply" class="py-20 bg-slate-900 text-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid lg:grid-cols-2 gap-12 items-center">
                <div>
                    <h2 class="text-3xl font-bold tracking-tight mb-4">Join Our Research Cohort</h2>
                    <p class="text-slate-400 mb-8 max-w-lg leading-relaxed">
                        Ready to elevate your clinical research portfolio? Ensure you review the following standard application requirements carefully before starting your digital submission.
                    </p>
                    <div class="bg-slate-800 p-6 rounded-xl border border-slate-700">
                        <p class="font-semibold mb-2 text-brand-100">Contact Administrative Hub</p>
                        <p class="text-sm text-slate-300">Combined Research Foundation Inc.</p>
                        <p class="text-sm text-slate-300">4129 Okemos Rd, Okemos, MI 48864</p>
                        <p class="text-sm text-brand-100 mt-4 font-mono">nadir@telegeriatricresearchfellowship.us</p>
                    </div>
                </div>

                <div class="space-y-6">
                    <div class="bg-slate-800 p-5 rounded-xl border border-slate-700 flex gap-4">
                        <div class="w-8 h-8 rounded-full bg-brand-600 text-white flex items-center justify-center font-bold flex-shrink-0">1</div>
                        <div>
                            <h4 class="font-bold text-lg">Verify Core Eligibility</h4>
                            <p class="text-slate-400 text-sm mt-1">Open to medical graduates targeted at expanding U.S. clinical space exposure and geriatric trial frameworks.</p>
                        </div>
                    </div>
                    <div class="bg-slate-800 p-5 rounded-xl border border-slate-700 flex gap-4">
                        <div class="w-8 h-8 rounded-full bg-brand-600 text-white flex items-center justify-center font-bold flex-shrink-0">2</div>
                        <div>
                            <h4 class="font-bold text-lg">Compile Academic Documents</h4>
                            <p class="text-slate-400 text-sm mt-1">Prepare your medical CV, a precise Statement of Purpose, and any prior abstract files or analytical drafts.</p>
                        </div>
                    </div>
                    <div class="bg-slate-800 p-5 rounded-xl border border-slate-700 flex gap-4">
                        <div class="w-8 h-8 rounded-full bg-brand-600 text-white flex items-center justify-center font-bold flex-shrink-0">3</div>
                        <div>
                            <h4 class="font-bold text-lg">Submit Digital Portal Request</h4>
                            <p class="text-slate-400 text-sm mt-1">Route finalized items via the secure onboarding desk at telegeriatricresearchfellowship.us.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-slate-950 text-slate-500 text-sm py-12 border-t border-slate-900">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex flex-col md:flex-row justify-between items-center gap-4">
            <div>
                <p>&copy; 2020-2026 The Tele-Geriatric Research Fellowship. All rights reserved.</p>
                <p class="text-xs text-slate-600 mt-1">The Combined Research Foundation is governed independently as a 501(c)(3) infrastructure.</p>
            </div>
            <div class="flex space-x-6 text-slate-400">
                <a href="#about" class="hover:text-white transition">About</a>
                <a href="#timeline" class="hover:text-white transition">Timeline</a>
                <a href="#impact" class="hover:text-white transition">Impact</a>
            </div>
        </div>
    </footer>

</body>
</html>
