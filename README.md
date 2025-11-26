<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mailseal — Agentic AI Email Infrastructure</title>
    <meta name="description" content="50+ qualified B2B meetings every month. Fully autonomous AI agents that research, write, and book — no SDRs, no agency.">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@500;700;900&display=swap" rel="stylesheet">
    <style>
        :root {
            --pink: #FF00C7;
            --yellow: #FFD600;
            --black: #000000;
            --dark: #0F001A;
        }
        * { margin:0; padding:0; box-sizing:border-box; }
        body { font-family:'Inter',sans-serif; background:var(--black); color:#fff; overflow-x:hidden; }
        .container { max-width:1400px; margin:0 auto; padding:0 2rem; }

        /* Header */
        header {
            position:fixed; top:0; left:0; right:0; z-index:1000;
            background:rgba(0,0,0,0.95); backdrop-filter:blur(20px);
            padding:1.5rem 0; border-bottom:2px solid var(--pink);
        }
        .header-inner { display:flex; justify-content:space-between; align-items:center; }
        .logo { font-size:2rem; font-weight:900; background:linear-gradient(90deg,var(--pink),var(--yellow)); -webkit-background-clip:text; -webkit-text-fill-color:transparent; }
        .btn-trial { background:var(--yellow); color:#000; padding:0.9rem 2rem; border-radius:50px; font-weight:900; font-size:1.1rem; }

        /* Hero */
        .hero {
            min-height:100vh; display:grid; place-items:center; text-align:center;
            background:radial-gradient(circle at top right, #FF00C780, transparent 50%),
                       radial-gradient(circle at bottom left, #FFD60050, transparent 60%), var(--black);
        }
        .hero h1 {
            font-size:5.5rem; font-weight:900; line-height:1;
            background:linear-gradient(90deg,#fff,#FFD600,#FF00C7); -webkit-background-clip:text; -webkit-text-fill-color:transparent;
        }
        .hero h2 { font-size:2.8rem; margin:1.5rem 0; color:var(--yellow); font-weight:700; }
        .hero p { font-size:1.4rem; max-width:800px; margin:2rem auto; opacity:0.9; }
        .hero .ctas { margin-top:3rem; display:flex; gap:2rem; justify-content:center; flex-wrap:wrap; }
        .btn-demo { border:2px solid var(--pink); padding:1rem 2.5rem; border-radius:50px; color:#fff; font-weight:700; }

        /* Agents */
        .agents { padding:10rem 0; background:var(--dark); }
        .section-title { font-size:3.5rem; text-align:center; margin-bottom:5rem; color:var(--pink); font-weight:900; }
        .agent-grid { display:grid; grid-template-columns:repeat(auto-fit,minmax(360px,1fr)); gap:3rem; }
        .agent-card {
            background:rgba(255,0,199,0.08); border:2px solid var(--pink); border-radius:32px;
            padding:3rem; text-align:center; transition:all .4s;
        }
        .agent-card:hover { transform:translateY(-20px); box-shadow:0 30px 80px rgba(255,0,199,0.3); }
        .agent-card img { width:220px; filter:drop-shadow(0 0 40px var(--pink)); margin-bottom:2rem; }
        .agent-card h3 { font-size:2.2rem; margin:1.5rem 0; color:var(--yellow); }

        /* Industries */
        .industries { padding:8rem 0; }
        .industry-grid { display:grid; grid-template-columns:repeat(auto-fit,minmax(220px,1fr)); gap:2rem; }
        .industry-card {
            background:linear-gradient(135deg,rgba(255,215,0,0.1),rgba(255,0,199,0.1));
            border:1px solid var(--pink); border-radius:20px; padding:2rem; text-align:center; font-weight:700;
        }

        /* Funnel */
        .funnel-section { padding:10rem 0; text-align:center; background:var(--black); }
        .funnel-img { max-width:100%; border-radius:30px; box-shadow:0 0 100px rgba(255,215,0,0.4); }

        /* Final CTA */
        .final-cta {
            padding:10rem 0; text-align:center;
            background:linear-gradient(135deg,var(--pink),var(--yellow));
            color:#000; clip-path:polygon(0 10%,100% 0%,100% 90%,0% 100%);
        }
        .final-cta h1 { font-size:5rem; font-weight:900; }

        footer { padding:4rem 0; text-align:center; background:var(--dark); color:#888; font-size:0.9rem; }

        @media (max-width:768px) {
            .hero h1 { font-size:3.5rem; }
            .hero h2 { font-size:2rem; }
            .hero .ctas { flex-direction:column; align-items:center; }
        }
    </style>
</head>
<body>

    <header>
        <div class="container header-inner">
            <div class="logo">Mailseal</div>
            <a href="#" class="btn-trial">Start Free Trial →</a>
        </div>
    </header>

    <section class="hero">
        <div class="container">
            <h1>50+ qualified B2B<br>meetings every month</h1>
            <h2>Fully autonomous AI agents<br>that never sleep</h2>
            <p>We built the first Agentic AI Email Infrastructure that researches, writes, and books meetings at scale — no SDRs, no agency, no off-the-shelf tools.</p>
            <div class="ctas">
                <a href="#" class="btn-trial" style="font-size:1.4rem;padding:1.2rem 3rem;">Start Free Trial — 14 days, no card</a>
                <a href="#" class="btn-demo">Watch 90-sec Demo →</a>
            </div>
            <p style="margin-top:3rem;color:var(--yellow);font-weight:700;">Private beta • 80+ Series A–C startups • Limited seats</p>
        </div>
    </section>

    <section class="agents">
        <div class="container">
            <h2 class="section-title">Meet Your Three AI Agents</h2>
            <div class="agent-grid">
                <div class="agent-card">
                    <img src="seal.png" alt="Seal the Sender">
                    <h3>Seal the Sender</h3>
                    <p>Writes hyper-personalized emails that land in the primary inbox — every single time.</p>
                </div>
                <div class="agent-card">
                    <img src="octopus.png" alt="Octopus the Data Miner">
                    <h3>Octopus the Data Miner</h3>
                    <p>Builds verified, intent-rich lead lists in seconds — like an octopus exploring the ocean of online data.</p>
                </div>
                <div class="agent-card">
                    <img src="jellyfish.png" alt="Jellyfish the Lead Scorer">
                    <h3>Jellyfish the Lead Scorer</h3>
                    <p>Scores replies in real-time and books qualified meetings straight to your calendar.</p>
                </div>
            </div>
        </div>
    </section>

    <section class="industries">
        <div class="container">
            <h2 class="section-title">Built for the Hardest Verticals</h2>
            <div class="industry-grid">
                <div class="industry-card">AI & ML Startups</div>
                <div class="industry-card">Climate Tech</div>
                <div class="industry-card">Fintech Infrastructure</div>
                <div class="industry-card">Cybersecurity</div>
                <div class="industry-card">Biotech & Pharma</div>
                <div class="industry-card">MedTech</div>
                <div class="industry-card">Industrial SaaS</div>
                <div class="industry-card">Renewable Energy</div>
            </div>
        </div>
    </section>

    <section class="funnel-section">
        <div class="container">
            <h2 class="section-title">Own Your Sales Funnel Again</h2>
            <img src="funnel.png" class="funnel-img" alt="Agentic AI Pipeline">
            <p style="margin-top:2rem;opacity:0.8;">Typical results from private beta users (2025)</p>
        </div>
    </section>

    <section class="final-cta">
        <div class="container">
            <h1>Let AI Agents Run Your Outbound<br>While You Close Deals</h1>
            <br><br>
            <a href="#" class="btn-trial" style="font-size:2rem;padding:1.5rem 4rem;background:#000;color:var(--yellow);border-radius:60px;">
                Start Free Trial — No credit card
            </a>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>© 2025 Mailseal • Agentic AI Email Infrastructure</p>
            <p>Pricing • Docs • hello@mailseal.co • Private Beta</p>
        </div>
    </footer>

</body>
</html>
