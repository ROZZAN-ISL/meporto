# meporto
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rozzan Zhofrul Islam - Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Inter', sans-serif; }
        html { scroll-behavior: smooth; }
    </style>
</head>
<body class="bg-slate-50 text-slate-800">

    <nav class="bg-white shadow-sm sticky top-0 z-50">
        <div class="max-w-5xl mx-auto px-4 py-4 flex justify-between items-center">
            <a href="#" class="font-bold text-xl text-blue-900 tracking-wider">RZI.</a>
            <div class="space-x-4 text-sm font-semibold text-slate-600">
                <a href="#about" class="hover:text-blue-600 transition">About</a>
                <a href="#projects" class="hover:text-blue-600 transition">Projects</a>
                <a href="#contact" class="hover:text-blue-600 transition">Contact</a>
            </div>
        </div>
    </nav>

    <header class="py-24 text-center px-4 bg-gradient-to-b from-white to-slate-50 border-b border-slate-200">
        <h1 class="text-4xl md:text-5xl font-bold text-blue-900 mb-4">Rozzan Zhofrul Islam</h1>
        <h2 class="text-xl md:text-2xl font-semibold text-slate-600 mb-6">Digital Business Student | Business Analyst Enthusiast</h2>
        <p class="max-w-2xl mx-auto text-slate-500 mb-10 leading-relaxed">
            Passionate about Business Analytics, Data Reporting, and Digital Transformation. I focus on turning raw data into actionable business strategies and impactful insights.
        </p>
        <a href="#projects" class="bg-blue-600 text-white px-8 py-3 rounded-lg font-semibold hover:bg-blue-700 shadow-md transition">View My Projects</a>
    </header>

    <section id="about" class="py-20 px-4">
        <div class="max-w-5xl mx-auto grid md:grid-cols-2 gap-12 items-start">
            <div>
                <h3 class="text-2xl font-bold text-slate-800 mb-4">About Me</h3>
                <p class="text-slate-600 leading-relaxed">
                    I am a Digital Business student at Telkom University Purwokerto with a strong interest in Business Analytics, Data Reporting, and digital business development. Through academic projects and business development activities, I have developed skills in business analysis, data visualization, reporting, market research, and public relations. I am eager to continue growing in the fields of business intelligence and digital transformation.
                </p>
            </div>
            <div>
                <h3 class="text-2xl font-bold text-slate-800 mb-4">Core Competencies</h3>
                <div class="flex flex-wrap gap-2">
                    <span class="bg-blue-100 text-blue-800 px-3 py-1 rounded-md text-sm font-medium border border-blue-200">Business Strategy & Analysis</span>
                    <span class="bg-blue-100 text-blue-800 px-3 py-1 rounded-md text-sm font-medium border border-blue-200">Business Intelligence & Reporting</span>
                    <span class="bg-blue-100 text-blue-800 px-3 py-1 rounded-md text-sm font-medium border border-blue-200">Data Visualization (Power BI)</span>
                    <span class="bg-blue-100 text-blue-800 px-3 py-1 rounded-md text-sm font-medium border border-blue-200">Data Cleaning (ETL)</span>
                    <span class="bg-blue-100 text-blue-800 px-3 py-1 rounded-md text-sm font-medium border border-blue-200">Market Research & R&D</span>
                    <span class="bg-blue-100 text-blue-800 px-3 py-1 rounded-md text-sm font-medium border border-blue-200">Project Leadership</span>
                </div>
            </div>
        </div>
    </section>

    <section id="projects" class="py-20 bg-white border-y border-slate-200 px-4">
        <div class="max-w-5xl mx-auto">
            <h3 class="text-3xl font-bold text-center text-slate-800 mb-12">Key Projects & Achievements</h3>
            
            <div class="grid md:grid-cols-2 gap-6">
                
                <div class="bg-slate-50 p-6 rounded-xl border border-slate-200 hover:shadow-lg transition hover:border-blue-300 group">
                    <h4 class="text-lg font-bold text-blue-900 mb-2 group-hover:text-blue-700">Capstone Project: Rucky's Fashion</h4>
                    <p class="text-slate-600 mb-4 text-sm leading-relaxed">Served as a Digital Transformation Consultant and Project Leader. Implemented digital tools such as an Odoo-based business website, a POS system, and simple AI to optimize daily operations for a local tailoring MSME.</p>
                    <div class="flex flex-wrap gap-2">
                        <span class="bg-white text-slate-600 px-2 py-1 rounded border border-slate-300 text-xs font-semibold">Project Management</span>
                        <span class="bg-white text-slate-600 px-2 py-1 rounded border border-slate-300 text-xs font-semibold">Digital Transformation</span>
                    </div>
                </div>

                <div class="bg-slate-50 p-6 rounded-xl border border-slate-200 hover:shadow-lg transition hover:border-blue-300 group">
                    <h4 class="text-lg font-bold text-blue-900 mb-2 group-hover:text-blue-700">Adidas Retail Dashboard</h4>
                    <p class="text-slate-600 mb-4 text-sm leading-relaxed">Developed an interactive sales dashboard using Power BI based on an Adidas retail dataset. Transformed raw data to visualize key metrics, including total sales, profit margins, and overall sales trends from 2020-2021.</p>
                    <div class="flex flex-wrap gap-2">
                        <span class="bg-white text-slate-600 px-2 py-1 rounded border border-slate-300 text-xs font-semibold">Power BI</span>
                        <span class="bg-white text-slate-600 px-2 py-1 rounded border border-slate-300 text-xs font-semibold">Data Visualization</span>
                    </div>
                </div>

                <div class="bg-slate-50 p-6 rounded-xl border border-slate-200 hover:shadow-lg transition hover:border-blue-300 group">
                    <h4 class="text-lg font-bold text-blue-900 mb-2 group-hover:text-blue-700">Sales Prediction Using ANN</h4>
                    <p class="text-slate-600 mb-4 text-sm leading-relaxed">Developed a sales prediction model using the Big Mart Sales dataset on Kaggle to support data-driven retail decision-making. Executed end-to-end analytics using ANN-MLP as the primary model.</p>
                    <div class="flex flex-wrap gap-2">
                        <span class="bg-white text-slate-600 px-2 py-1 rounded border border-slate-300 text-xs font-semibold">Machine Learning</span>
                        <span class="bg-white text-slate-600 px-2 py-1 rounded border border-slate-300 text-xs font-semibold">Python</span>
                    </div>
                </div>

                <div class="bg-slate-50 p-6 rounded-xl border border-slate-200 hover:shadow-lg transition hover:border-blue-300 group">
                    <h4 class="text-lg font-bold text-blue-900 mb-2 group-hover:text-blue-700">End-to-End Sales Dashboard & ETL</h4>
                    <p class="text-slate-600 mb-4 text-sm leading-relaxed">Executed a complete ETL process to extract, clean, and load sales data into a relational model using Power BI. Built an interactive dashboard presenting insights like profit trends and product clustering.</p>
                    <div class="flex flex-wrap gap-2">
                        <span class="bg-white text-slate-600 px-2 py-1 rounded border border-slate-300 text-xs font-semibold">ETL</span>
                        <span class="bg-white text-slate-600 px-2 py-1 rounded border border-slate-300 text-xs font-semibold">Data Modeling</span>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <section class="py-20 px-4 bg-slate-50">
        <div class="max-w-5xl mx-auto grid md:grid-cols-2 gap-12">
            <div>
                <h3 class="text-2xl font-bold text-slate-800 mb-6 flex items-center gap-2">
                    🎓 Education
                </h3>
                <div class="bg-white p-6 rounded-xl border border-slate-200 shadow-sm relative overflow-hidden">
                    <div class="absolute top-0 left-0 w-1 h-full bg-blue-600"></div>
                    <h4 class="font-bold text-lg text-blue-900">Telkom University Purwokerto</h4>
                    <p class="text-slate-700 font-medium">Undergraduate Bachelor of Digital Business</p>
                    <p class="text-sm text-slate-500 mt-2">GPA: 3.84</p>
                </div>
            </div>

            <div>
                <h3 class="text-2xl font-bold text-slate-800 mb-6 flex items-center gap-2">
                    📜 Key Certifications
                </h3>
                <ul class="space-y-3">
                    <li class="bg-white px-4 py-3 border border-slate-200 rounded-lg shadow-sm flex items-center gap-3">
                        <span class="text-blue-600">✔</span>
                        <div>
                            <p class="text-slate-800 font-semibold text-sm">Intro to Machine Learning</p>
                            <p class="text-xs text-slate-500">Kaggle</p>
                        </div>
                    </li>
                    <li class="bg-white px-4 py-3 border border-slate-200 rounded-lg shadow-sm flex items-center gap-3">
                        <span class="text-blue-600">✔</span>
                        <div>
                            <p class="text-slate-800 font-semibold text-sm">Data Cleaning</p>
                            <p class="text-xs text-slate-500">Kaggle</p>
                        </div>
                    </li>
                    <li class="bg-white px-4 py-3 border border-slate-200 rounded-lg shadow-sm flex items-center gap-3">
                        <span class="text-blue-600">✔</span>
                        <div>
                            <p class="text-slate-800 font-semibold text-sm">Business Intelligence Fundamentals</p>
                            <p class="text-xs text-slate-500">Simplilearn</p>
                        </div>
                    </li>
                    <li class="bg-white px-4 py-3 border border-slate-200 rounded-lg shadow-sm flex items-center gap-3">
                        <span class="text-blue-600">✔</span>
                        <div>
                            <p class="text-slate-800 font-semibold text-sm">Power BI for Beginners</p>
                            <p class="text-xs text-slate-500">Simplilearn</p>
                        </div>
                    </li>
                </ul>
            </div>
        </div>
    </section>

    <footer id="contact" class="bg-slate-900 text-white py-16 text-center px-4 border-t-4 border-blue-600">
        <h3 class="text-3xl font-bold mb-4">Let's Connect</h3>
        <p class="mb-8 text-slate-400 max-w-lg mx-auto">I am actively looking for opportunities in Data Reporting, Business Analytics, and Digital Transformation roles.</p>
        
        <div class="flex flex-col md:flex-row justify-center items-center gap-6 mb-10 text-slate-200 font-medium">
            <a href="mailto:rozzanzhofrulislam@gmail.com" class="flex items-center gap-2 hover:text-blue-400 transition">
                <span>📧</span> rozzanzhofrulislam@gmail.com
            </a>
            <span class="hidden md:block text-slate-600">|</span>
            <div class="flex items-center gap-2">
                <span>📞</span> +62-895-3769-40266
            </div>
            <span class="hidden md:block text-slate-600">|</span>
            <div class="flex items-center gap-2">
                <span>📍</span> Tegal / Purwokerto
            </div>
        </div>
        
        <p class="text-slate-600 text-sm">&copy; 2026 Rozzan Zhofrul Islam. All rights reserved.</p>
    </footer>

</body>
</html>
