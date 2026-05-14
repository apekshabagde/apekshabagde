 <!DOCTYPE html>

<html lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Apeksha Bagde - GitHub Profile</title>
<!-- Tailwind CSS v3 CDN -->
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            'github-dark': '#0d1117',
            'github-card': '#161b22',
            'neon-blue': '#00d2ff',
            'neon-green': '#39ff14',
            'neon-purple': '#bc13fe',
            'neon-gold': '#ffd700',
            'neon-cyan': '#00ffff'
          },
          boxShadow: {
            'neon-blue': '0 0 10px rgba(0, 210, 255, 0.4)',
            'neon-green': '0 0 10px rgba(57, 255, 20, 0.4)',
            'neon-purple': '0 0 10px rgba(188, 19, 254, 0.4)',
            'neon-cyan': '0 0 10px rgba(0, 255, 255, 0.4)',
          }
        }
      }
    }
  </script>
<style data-purpose="custom-animations">
    @keyframes glow {
      0%, 100% { opacity: 0.8; }
      50% { opacity: 1; filter: brightness(1.2); }
    }
    .animate-glow {
      animation: glow 3s infinite ease-in-out;
    }
    /* Simple doughnut chart using CSS */
    .doughnut {
      width: 100px;
      height: 100px;
      border-radius: 50%;
      background: conic-gradient(
        #3b82f6 0% 45%, 
        #10b981 45% 75%, 
        #f59e0b 75% 91%, 
        #ef4444 91% 100%
      );
      display: flex;
      align-items: center;
      justify-content: center;
      position: relative;
    }
    .doughnut::after {
      content: "";
      width: 60px;
      height: 60px;
      background: #161b22;
      border-radius: 50%;
      position: absolute;
    }
  </style>
</head>
<body class="bg-github-dark text-gray-200 font-sans min-h-screen p-4 md:p-8">
<main class="max-w-7xl mx-auto grid grid-cols-1 lg:grid-cols-12 gap-8">
<!-- BEGIN: Sidebar Section -->
<aside class="lg:col-span-3 flex flex-col space-y-6">
<!-- Profile Picture Container -->
<div class="relative group mx-auto lg:mx-0">
<div class="w-64 h-64 rounded-full overflow-hidden border-4 border-gray-700 shadow-2xl relative z-10">
<img alt="Profile Picture" class="w-full h-full object-cover" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDv8W5-wXx-3CtlT7rzfAbO2XmCyMaHz7MG-OMXqG-uyka-ySO60tzw0KMS6Jp-Ub0TMYy6epqkX1JEBnadl2SlPWFtFhfpHKYbdCp7Eb9YExGn1ZY1IwiV9UeSS6BfXXfs5GhBeQAMg-Z8deNsRPWVR_b4cJcsNjUN-aactId9_2bB6ft8jCfEwFJyhDTwCWiQRGKWUsjpB4RCMZSbjrPjiwasSwKL2UrCHlzsIkUSlTH011yAOzltN2a_U0LQ2fCsLtAInu69AuI"/>
</div>
<!-- Decorative glowing ring behind profile -->
<div class="absolute inset-0 bg-neon-blue rounded-full blur-2xl opacity-20 -z-0"></div>
</div>
<!-- Identity -->
<div class="space-y-1">
<h1 class="text-3xl font-bold text-white">Apeksha Bagde</h1>
<p class="text-gray-400 font-mono text-sm">apekshabagde • she/her</p>
</div>
<!-- Status Card -->
<div class="bg-github-card p-4 rounded-xl border border-neon-blue shadow-neon-blue" data-purpose="status-card">
<h3 class="text-neon-blue font-bold text-sm mb-2 uppercase tracking-wider">Currently Working On</h3>
<p class="text-xs leading-relaxed">
          Developing a cutting-edge RAG system for financial document analysis using Llama 3 and LangChain.
        </p>
</div>
<!-- Certifications -->
<div class="space-y-4 pt-4">
<h3 class="text-white font-semibold border-b border-gray-800 pb-2">Certifications</h3>
<div class="grid grid-cols-2 gap-2">
<!-- Cert 1 -->
<div class="flex flex-col items-center p-2 bg-github-card border border-gray-800 rounded-lg">
<img alt="TATA logo" class="mb-2" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDC3xK_epOdVOHEs1OopXLqtwb34hVJWhoMMJg5m3e4lXOhwji8ThmQCH8HJL8O9fxpVa-9HVdSwuNymqUtw2TSD9RuWiiX8VOdGeIH4nnrQImDXjZy9WpzdNT8HdUF6xI-4cU51unUT0URP635RohZnnD8gsSPUGaRTflkq33oHsuw45vzO_QHNCvXQrkFffzVJmftJX3gMTadBbDPFzQSBcbVz5kx2DW0LYHTeGuyJfCKJa4eym6cjL-4hm6_ktrw1NHFU3bVjg8"/>
<p class="text-[10px] text-center">TATA GenAI Powered Data Analytics</p>
</div>
<!-- Cert 2 -->
<div class="flex flex-col items-center p-2 bg-github-card border border-gray-800 rounded-lg">
<img alt="DataViz logo" class="mb-2" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBYH3pjlntjQvGGM84uQ6V8nunmMKSjWTpc0WLC_-PUjj252uYJ4Hks6G9QDo-8iF5AfJ-pWCPRPN0A7FhrkHwDiE0ql4lc6R_72SqOfti-wcX-WLMjZpyHdjnes71kBjY5QbCOUjnKleGzGtBfIWbL4kOXspzX8AmUVzbfWb8H1HadJsrCLLuras_DAnGfe700jgNzLppvRts_sp6ll5LN8xUl83GBd_t_9ti0VHAAQYpv4QC5tHaQ1xulxGbqSFeGBtL5qIhZQS0"/>
<p class="text-[10px] text-center">Data Visualization</p>
</div>
</div>
</div>
</aside>
<!-- END: Sidebar Section -->
<!-- BEGIN: Main Dashboard Content -->
<div class="lg:col-span-9 space-y-6">
<!-- BEGIN: Header Banner -->
<header class="relative bg-github-card rounded-2xl p-8 overflow-hidden border border-gray-800">
<!-- Abstract wave background -->
<div class="absolute top-0 right-0 h-full w-1/2 opacity-40">
<img alt="Wave Decoration" class="w-full h-full object-cover mix-blend-screen" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAcC7d0Vo_xDVS-mBHoXPeiZesdhE0tKzrOcLV8vLx5B4ni6oI5lx7XyK-Sdw7mXXKleW5r2T0JcWAevIsG47jC22D9OQMaglCMtXbBenugWDo8pz94ADs9eZlY6V_8Zi0VU0_q2kOMt1btODBJb8nWlv52ZvxfYr-HGYOXTHWPGlmbRILidMTk0eSd15wFr_8QSqsOkkT-M-gPVhwMoH4Z55yzTMMgk5w09rchRTIPsKPw91bcdzeteiSYPBbAXFimx1ogOlk_NHE"/>
</div>
<div class="relative z-10">
<h2 class="text-3xl font-extrabold text-white">Data Analyst | Software Engineer</h2>
<p class="text-neon-blue mt-1">Data-Driven Solutions.</p>
<div class="mt-12">
<h3 class="text-4xl font-bold tracking-tight">GenAI &amp; Machine Learning</h3>
</div>
</div>
</header>
<!-- END: Header Banner -->
<!-- BEGIN: Stats Row -->
<div class="grid grid-cols-1 md:grid-cols-2 gap-6">
<!-- GitHub Stats Card -->
<div class="bg-github-card p-6 rounded-2xl border border-gray-800 shadow-xl">
<h4 class="text-white font-bold mb-4 flex items-center">
            GitHub Stats
          </h4>
<div class="grid grid-cols-2 gap-4 text-sm">
<div class="flex items-center space-x-2">
<span class="text-neon-blue">👁️</span>
<span class="text-gray-400">Total Commits:</span>
<span class="text-white font-mono">1.2k</span>
</div>
<div class="flex items-center space-x-2">
<span class="text-neon-green">🔥</span>
<span class="text-gray-400">Contribution Streak:</span>
<span class="text-white font-mono">45 Days</span>
</div>
<div class="flex items-center space-x-2">
<span class="text-neon-purple">❗</span>
<span class="text-gray-400">Issues Closed:</span>
<span class="text-white font-mono">150</span>
</div>
<div class="flex items-center space-x-2">
<span class="text-neon-gold">🌿</span>
<span class="text-gray-400">PRs Merged:</span>
<span class="text-white font-mono">80</span>
</div>
</div>
<div class="mt-4 flex space-x-4">
<img alt="GitHub icon" class="opacity-50" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDVHxmnkILY6VeqGlZrncpgeHqL3saliTaKMEZPywGKV7iMgo0zuNPYSODYTOdWi-aoKVSmizX5p5SAbLhVjBWPFpKSWPh65xG4YYu7xPi0D3YAz5dCwBui9aoaSdCjYdwiZnb7h4MdWQe9azcitC_HCuhKsUo6LKle0Ppx7ib2JaVd_VfWGixUE8sFFrIvMgxRAcPxP9Tp-uZqnXSc5_w_7k9G04PcknFxGNKO5VnXUAjRbCj4b9Nru37R-vYdV4qazvusiwBeAXs"/>
<img alt="Linkedin icon" class="opacity-50" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBfq1Pomrdn4mfAvVSrcRB94HkMu_qCNElbnGYk1nbMksBpl5I_yRbNUCod1o7e0xpolrDswqtfweswbc2XBJVHZ9RsdMUZQvcoz8B5r-Nf2eczG9HJWGOdNQAzBGUhpK6aUBqBCfMWdSvz7OmmE6DbaoTgYJrS9y-WXTHKYYuqkQ-jGR2dBn1CXx_-YK2xsYTngzBqZnmREmqYU_3h8Wv3BYpYgLHMNuLJR-PEZX7mi9OGg2TdRYNf0bl_oYWp2dZcjEb2mOqppwE"/>
</div>
</div>
<!-- Top Languages Card -->
<div class="bg-github-card p-6 rounded-2xl border border-gray-800 shadow-xl flex items-center justify-between">
<div>
<h4 class="text-white font-bold mb-4">Top Languages</h4>
<ul class="space-y-2 text-xs">
<li class="flex items-center"><span class="w-2 h-2 rounded-full bg-blue-500 mr-2"></span> Python (45%)</li>
<li class="flex items-center"><span class="w-2 h-2 rounded-full bg-emerald-500 mr-2"></span> SQL (30%)</li>
<li class="flex items-center"><span class="w-2 h-2 rounded-full bg-amber-500 mr-2"></span> JavaScript (15%)</li>
<li class="flex items-center"><span class="w-2 h-2 rounded-full bg-red-500 mr-2"></span> HTML/CSS (10%)</li>
</ul>
</div>
<div class="doughnut"></div>
</div>
</div>
<!-- END: Stats Row -->
<!-- BEGIN: Tech Stack Section -->
<section>
<h4 class="text-white font-bold mb-4 text-xl">Tech Stack</h4>
<div class="grid grid-cols-1 md:grid-cols-3 gap-6">
<!-- Expert -->
<div class="space-y-3">
<h5 class="text-neon-blue text-sm font-semibold uppercase">Expert</h5>
<div class="flex flex-wrap gap-2">
<div class="px-3 py-1 rounded-lg border border-neon-blue bg-blue-900/20 text-xs flex items-center shadow-neon-blue">
<span class="mr-2">🐍</span> Python
              </div>
<div class="px-3 py-1 rounded-lg border border-neon-blue bg-blue-900/20 text-xs flex items-center shadow-neon-blue">
<span class="mr-2">☕</span> Java
              </div>
<div class="px-3 py-1 rounded-lg border border-neon-blue bg-blue-900/20 text-xs flex items-center shadow-neon-blue">
<span class="mr-2">💾</span> Advanced SQL
              </div>
<div class="px-3 py-1 rounded-lg border border-neon-blue bg-blue-900/20 text-xs flex items-center shadow-neon-blue">
<span class="mr-2">⚛️</span> React.js
              </div>
<div class="px-3 py-1 rounded-lg border border-neon-blue bg-blue-900/20 text-xs flex items-center shadow-neon-blue">
<span class="mr-2">🍃</span> Spring Boot
              </div>
</div>
</div>
<!-- Intermediate -->
<div class="space-y-3">
<h5 class="text-neon-green text-sm font-semibold uppercase">Intermediate</h5>
<div class="flex flex-wrap gap-2">
<div class="px-3 py-1 rounded-lg border border-neon-green bg-green-900/20 text-xs flex items-center shadow-neon-green">
<span class="mr-2">N</span> Next.js
              </div>
<div class="px-3 py-1 rounded-lg border border-neon-green bg-green-900/20 text-xs flex items-center shadow-neon-green">
<span class="mr-2">⬢</span> Node.js
              </div>
<div class="px-3 py-1 rounded-lg border border-neon-green bg-green-900/20 text-xs flex items-center shadow-neon-green">
<span class="mr-2">☁️</span> AWS
              </div>
<div class="px-3 py-1 rounded-lg border border-neon-green bg-green-900/20 text-xs flex items-center shadow-neon-green">
<span class="mr-2">🍃</span> MongoDB
              </div>
<div class="px-3 py-1 rounded-lg border border-neon-green bg-green-900/20 text-xs flex items-center shadow-neon-green">
<span class="mr-2">📊</span> Power BI
              </div>
</div>
</div>
<!-- Familiar -->
<div class="space-y-3">
<h5 class="text-neon-purple text-sm font-semibold uppercase">Familiar</h5>
<div class="flex flex-wrap gap-2">
<div class="px-3 py-1 rounded-lg border border-neon-purple bg-purple-900/20 text-xs flex items-center shadow-neon-purple">
<span class="mr-2">🐳</span> Docker
              </div>
<div class="px-3 py-1 rounded-lg border border-neon-purple bg-purple-900/20 text-xs flex items-center shadow-neon-purple">
<span class="mr-2">🏗️</span> Jenkins
              </div>
<div class="px-3 py-1 rounded-lg border border-neon-purple bg-purple-900/20 text-xs flex items-center shadow-neon-purple">
<span class="mr-2">🔴</span> Redis
              </div>
<div class="px-3 py-1 rounded-lg border border-neon-purple bg-purple-900/20 text-xs flex items-center shadow-neon-purple">
<span class="mr-2">⚡</span> XGBoost
              </div>
</div>
</div>
</div>
</section>
<!-- END: Tech Stack Section -->
<!-- BEGIN: Top Repositories -->
<section>
<h4 class="text-white font-bold mb-4 text-xl">Top Repositories</h4>
<div class="grid grid-cols-1 md:grid-cols-2 gap-6">
<!-- Repo 1 -->
<div class="bg-github-card p-5 rounded-2xl border border-neon-blue/50 flex items-start space-x-4 shadow-neon-blue/20">
<div class="text-4xl">🐍</div>
<div class="flex-1">
<h5 class="text-white font-bold">Repo 1: AI FinTech</h5>
<p class="text-xs text-gray-400 mt-1">Predictive modeling for stock market</p>
<p class="text-xs text-blue-400 font-mono mt-2">Python 80%, SQL 20%</p>
</div>
</div>
<!-- Repo 2 -->
<div class="bg-github-card p-5 rounded-2xl border border-neon-cyan/50 flex items-start space-x-4 shadow-neon-cyan/20">
<div class="text-4xl text-neon-cyan">🏠</div>
<div class="flex-1">
<h5 class="text-white font-bold">Repo 2: SmartHome IoT</h5>
<p class="text-xs text-gray-400 mt-1">IoT device management dashboard</p>
<p class="text-xs text-cyan-400 font-mono mt-2">JavaScript 60%, C++ 40%</p>
</div>
</div>
</div>
</section>
<!-- END: Top Repositories -->
<!-- BEGIN: Soft Skills Section -->
<section>
<h4 class="text-white font-bold mb-4 text-xl">Soft Skills</h4>
<div class="grid grid-cols-2 md:grid-cols-4 gap-4">
<!-- Skill: Communication -->
<div class="p-4 bg-github-card border border-neon-blue rounded-2xl flex flex-col items-center justify-center space-y-2 shadow-neon-blue/20 hover:scale-105 transition-transform cursor-default">
<img alt="Icon" class="w-10 h-10" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAuK-FTjxELWi6U1knOq_r4Vhdrsr1fLIe3wx4pl42SJ34kX2dcInNucBGePg3XqsMYumgeoRCrbfZ4aXIWFuaRy6b9Hf_NueHQL5xubYDiCP-sy7tStlHFWfbV9i71rNWKhnAN0qGnKKHArjAxNQ5tKpPndzsivsyMVR7CCynSp_clnNNDgKeCyDpxtCGw-30rfOVENFq9PQQSDqnOEIWFWICsDDS0hK-NlJtaqMXQbg-dT0ZIxRcOgUePlmDUNJwb2l_0sUrbZpE"/>
<span class="text-[10px] uppercase font-bold text-gray-300">Communication</span>
</div>
<!-- Skill: Leadership -->
<div class="p-4 bg-github-card border border-neon-green rounded-2xl flex flex-col items-center justify-center space-y-2 shadow-neon-green/20 hover:scale-105 transition-transform cursor-default">
<img alt="Icon" class="w-10 h-10" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAv0aaN8o-iM3rXAx3Hm7rlQ_3NyL7lGZ9NxzEq69d7beVeU4whe8nXOpQu29jSoLIOblThwLKgw5_XJMAuHWJBSXtzHgIHNh9gMAi1DtzGc7-IphByjDj2RXgVlJ2N9-vZRz7nQUHxVzcDtOvIBXQB7A0NeI9sbJmKSncs2wHKK6WvXnOcUJJ5ynPVPYEF62WDS3D4rFiJUonv5McgkNt2UWf4hQn8-O_9OJ4LRdhDblHG8l_hFWDLTXqQ0GMLYzHQBcSEtxe9ObQ"/>
<span class="text-[10px] uppercase font-bold text-gray-300">Leadership</span>
</div>
<!-- Skill: Problem Solving -->
<div class="p-4 bg-github-card border border-neon-gold rounded-2xl flex flex-col items-center justify-center space-y-2 shadow-neon-gold/20 hover:scale-105 transition-transform cursor-default">
<img alt="Icon" class="w-10 h-10" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAHgNx9L82UsWcU9uQKft9ORErtQlFXrUg6WQ5ycX8EyP3br0UKjO4x31T8bnHVfBnhwIembMmwNMcv8blFvTGg0I9EnMNUcBolgn-sl-goJYHPegyLukRq86Jao8sI3BO7ITAxqRUmtl85FtkV519L9hi2NPF9xgnAOHaqUAbpBetlmQuyB1cz8dj3Feqk349DWu1OINEdNyJSVXJJTrV-7VUMjsgUChZ7JP70vl_jjoSM6nUTwgYZZI1rO6ygyqL1TbZrEKCax6I"/>
<span class="text-[10px] uppercase font-bold text-gray-300">Problem Solving</span>
</div>
<!-- Skill: Stakeholder Management -->
<div class="p-4 bg-github-card border border-neon-cyan rounded-2xl flex flex-col items-center justify-center space-y-2 shadow-neon-cyan/20 hover:scale-105 transition-transform cursor-default text-center">
<img alt="Icon" class="w-10 h-10" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAtz_2Bgjjw13QnWxlpVk-jlOMoSALD2eX86ZphtT7apyCgZxR7acjQjvzyamTF0mLi7M6X8cVFvZJpV0Z4h7YS6a5s8koiGBQgrLtuK3WglUFNuEcDjY2VIgplAJnilC-VQ_xa1irQVtXPN_6iEhAWarGW4C6frr9eWTNfFnNpjgxieHUJap1FW01yC69unWXBVMxifkSU1INIfz7zRDszgHLeyDbtvnI_EE7ZjPlzFe_lxJ6yueUleLfcORdQMX10zhSjHuHHJP0"/>
<span class="text-[10px] uppercase font-bold text-gray-300 leading-tight">Stakeholder Management</span>
</div>
</div>
</section>
<!-- END: Soft Skills Section -->
<!-- BEGIN: Footer Row -->
<section class="grid grid-cols-1 md:grid-cols-2 gap-6 pb-12">
<!-- Visitor Counter -->
<div class="bg-github-card p-5 rounded-2xl border border-gray-800 flex items-center space-x-6">
<div class="text-neon-blue font-bold">
<p class="text-xs uppercase text-gray-500">Visitor Counter</p>
<p class="text-2xl font-mono">Visitors: 15,432</p>
</div>
</div>
<!-- Trophy Showcase -->
<div class="bg-github-card p-5 rounded-2xl border border-neon-green/30 flex items-center space-x-4">
<img alt="Trophy" class="animate-glow" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCcEGvhMxRmVdUE14rdABlKQ--C6iGRavgL6gDknhq3D9FLqqPvIBQT31Wg8_plvW678TfpWAswdCYZFZrfO0WV0HdojVTqK-h3vN-OFNlNH9eFEmW7eiKeF4-nZFAn5Lv6qblfhVvNZqgreOhz4vio6E0p5SBumUdW9zux0ylfYKBQQI2d1kpmiS-ub7YNtYwKata8jo29SwtoIcPsLp3fHBldd4y_tvHO78VMBoRyET1GPrUoLcGyilbWSZ0RArzE8Ql6HUMuR14"/>
<div>
<h5 class="text-sm font-bold text-white">GitHub Trophy</h5>
<p class="text-[10px] text-gray-400">Achieved for consistent contributions in Open Source projects.</p>
</div>
</div>
</section>
<!-- END: Footer Row -->
</div>
<!-- END: Main Dashboard Content -->
</main>
</body></html>
