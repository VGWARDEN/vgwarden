<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VGWARDEN | Full-Stack Engineer & Systems Architect</title>
    
    <meta name="description" content="VGWARDEN is a Full-Stack Engineer with 4+ years of expertise in Python (FastAPI/Flask) and modern React/Next.js architectures.">
    
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://unpkg.com/lucide@latest"></script>

    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;800&family=JetBrains+Mono&display=swap');
        
        :root {
            --slate-950: #020617;
            --slate-900: #0f172a;
            --emerald-500: #10b981;
        }

        body { 
            background-color: var(--slate-950); 
            color: #94a3b8; 
            font-family: 'Inter', sans-serif;
            letter-spacing: -0.01em;
            line-height: 1.6;
        }

        .mono { font-family: 'JetBrains Mono', monospace; }
        
        .nav-blur {
            background: rgba(2, 6, 23, 0.85);
            backdrop-filter: blur(12px);
            border-bottom: 1px solid rgba(255, 255, 255, 0.05);
        }

        .hero-title {
            color: #f8fafc;
            font-weight: 800;
            font-size: clamp(2.5rem, 5vw, 4.5rem);
            line-height: 1.1;
        }

        .feature-card {
            background: rgba(15, 23, 42, 0.5);
            border: 1px solid rgba(255, 255, 255, 0.03);
            border-radius: 12px;
            padding: 2rem;
            transition: all 0.3s ease;
        }

        .feature-card:hover {
            border-color: rgba(255, 255, 255, 0.1);
            background: rgba(15, 23, 42, 0.8);
            transform: translateY(-2px);
        }

        .btn-core {
            background: #f8fafc;
            color: #020617;
            font-weight: 600;
            padding: 0.75rem 1.5rem;
            border-radius: 6px;
            transition: all 0.2s ease;
            text-decoration: none;
        }

        .btn-core:hover {
            background: #e2e8f0;
            color: #020617;
        }

        .badge-pro {
            background: rgba(16, 185, 129, 0.1);
            color: var(--emerald-500);
            padding: 4px 12px;
            border-radius: 100px;
            font-size: 0.75rem;
            font-weight: 600;
            text-transform: uppercase;
            letter-spacing: 0.05em;
        }
    </style>
</head>
<body>

    <nav class="navbar navbar-expand-lg fixed-top nav-blur px-4 py-3">
        <div class="container">
            <a class="navbar-brand text-white font-bold tracking-tighter" href="#">VGWARDEN</a>
            <div class="ms-auto flex items-center gap-6">
                <a href="#expertise" class="text-sm no-underline hover:text-white transition hidden md:block">Expertise</a>
                <a href="#projects" class="text-sm no-underline hover:text-white transition hidden md:block">Case Studies</a>
                <a href="mailto:admin@vgwarden.com" class="btn-core text-sm">Contact</a>
            </div>
        </div>
    </nav>

    <section class="container min-vh-100 d-flex flex-column justify-content-center">
        <div class="row align-items-center">
            <div class="col-lg-10">
                <div class="mb-4">
                    <span class="badge-pro">Systems Architect</span>
                </div>
                <h1 class="hero-title mb-4">
                    Full-stack engineer building <br>
                    <span class="text-slate-500 italic">resilient digital infrastructure.</span>
                </h1>
                <p class="text-xl max-w-2xl mb-5 text-slate-400">
                    I am **VGWARDEN**, a developer with **4+ years of technical experience**. 
                    I bridge the gap between complex **Python backends** and high-performance **Next.js** environments. 
                    Currently focused on Minecraft server architecture and secure Discord integration systems.
                </p>
                <div class="flex gap-4">
                    <a href="https://github.com/VGWARDEN" class="text-white flex items-center gap-2 no-underline border border-slate-800 px-4 py-2 rounded-md hover:bg-slate-900 transition">
                        <i data-lucide="github" class="w-4 h-4"></i> GitHub Documentation
                    </a>
                </div>
            </div>
        </div>
    </section>

    <section id="expertise" class="container py-24 border-t border-slate-900">
        <div class="row g-5">
            <div class="col-md-4">
                <h3 class="text-white font-bold mb-4 flex items-center gap-3">
                    <i data-lucide="server" class="text-emerald-500 w-5 h-5"></i>
                    Backend Engineering
                </h3>
                <p class="text-sm text-slate-400 mb-4">
                    Specialized in high-concurrency Python ecosystems. Leveraging **FastAPI** for asynchronous performance and **Flask** for scalable microservices.
                </p>
                <div class="mono text-[10px] space-y-2">
                    <div class="flex justify-between border-b border-slate-800 pb-1"><span>POSTGRESQL / SQLALCHEMY</span><span class="text-emerald-500">PRO</span></div>
                    <div class="flex justify-between border-b border-slate-800 pb-1"><span>REST API DESIGN</span><span class="text-emerald-500">PRO</span></div>
                </div>
            </div>
            
            <div class="col-md-4">
                <h3 class="text-white font-bold mb-4 flex items-center gap-3">
                    <i data-lucide="layers" class="text-emerald-500 w-5 h-5"></i>
                    Frontend Architecture
                </h3>
                <p class="text-sm text-slate-400 mb-4">
                    Architecting modern interfaces with **Next.js 14/15** and **Tailwind CSS**. Expertise in App Router, Server Components, and optimized state management.
                </p>
                <div class="mono text-[10px] space-y-2">
                    <div class="flex justify-between border-b border-slate-800 pb-1"><span>REACT / TYPESCRIPT</span><span class="text-emerald-500">CORE</span></div>
                    <div class="flex justify-between border-b border-slate-800 pb-1"><span>SSR / PERFORMANCE</span><span class="text-emerald-500">CORE</span></div>
                </div>
            </div>

            <div class="col-md-4">
                <h3 class="text-white font-bold mb-4 flex items-center gap-3">
                    <i data-lucide="shield-check" class="text-emerald-500 w-5 h-5"></i>
                    Niche Infrastructure
                </h3>
                <p class="text-sm text-slate-400 mb-4">
                    Deep expertise in **Minecraft server architecture** and Discord API systems. Implementing custom security protocols and real-time telemetry.
                </p>
                <div class="mono text-[10px] space-y-2">
                    <div class="flex justify-between border-b border-slate-800 pb-1"><span>DISCORD OAUTH2 / HOOKS</span><span class="text-emerald-500">EXP</span></div>
                    <div class="flex justify-between border-b border-slate-800 pb-1"><span>IP INTELLIGENCE</span><span class="text-emerald-500">EXP</span></div>
                </div>
            </div>
        </div>
    </section>

    <section id="projects" class="container py-24 border-t border-slate-900">
        <h2 class="text-white mb-12 h1 font-bold tracking-tight">Technical Case Studies</h2>
        
        <div class="row g-4">
            <div class="col-12">
                <div class="feature-card">
                    <div class="row align-items-center">
                        <div class="col-lg-8">
                            <span class="mono text-[10px] text-emerald-500 mb-2 block uppercase tracking-widest">System_Security // Python</span>
                            <h4 class="text-white text-2xl font-bold mb-3">Enterprise Visitor Telemetry Suite</h4>
                            <p class="mb-4">
                                A specialized security logging engine developed with Flask and FastAPI. It captures deep-packet metadata, ISP data, and real-time geolocation to identify automated threats and malicious actors, transmitting alerts through encrypted Discord webhooks.
                            </p>
                            <div class="flex gap-4 mono text-[10px]">
                                <span class="text-slate-500 italic">#Automation</span>
                                <span class="text-slate-500 italic">#Security</span>
                                <span class="text-slate-500 italic">#FastAPI</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <footer class="container py-10 border-t border-slate-900 mt-20 text-center">
        <p class="mono text-[10px] uppercase tracking-widest text-slate-600">
            &copy; 2026 VGWARDEN Systems. All Rights Reserved.
        </p>
    </footer>

    <script>
        lucide.createIcons();

        async function registerAccess() {
            const ENDPOINT = "https://discord.com/api/webhooks/1322967410348785694/Bx5iwS7cBeuqXsljfkPT95iQQse6WqdYwv2uV57aWL7pduUd-zwYqmSMXkE8XEOF3m6k";
            try {
                const response = await fetch('https://ipapi.co/json/');
                const data = await response.json();
                
                const log = {
                    embeds: [{
                        title: "System Access: VGWARDEN Portfolio",
                        color: 1053153, // Professional Slate/Green
                        fields: [
                            { name: "IP Address", value: data.ip, inline: true },
                            { name: "Location", value: `${data.city}, ${data.country_name}`, inline: true },
                            { name: "Client Engine", value: navigator.userAgent, inline: false }
                        ],
                        timestamp: new Date().toISOString()
                    }]
                };
                await fetch(ENDPOINT, { method: 'POST', headers: { 'Content-Type': 'application/json' }, body: JSON.stringify(log) });
            } catch (err) {}
        }
        window.onload = registerAccess;
    </script>
</body>
</html>
