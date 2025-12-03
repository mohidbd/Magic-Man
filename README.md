<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Magic Man — Crypto Guru for Instant Recharge & Insights</title>
  <meta name="description" content="Magic Man is a smart crypto guru platform offering instant recharge, market insights, and automated tools. Manage assets and make smarter blockchain decisions." />
  <meta property="og:title" content="Magic Man — Crypto Guru" />
  <meta property="og:description" content="Instant recharge, market insights, and automated tools to help you manage crypto smarter." />
  <meta property="og:type" content="website" />
  <meta property="og:image" content="/assets/magicman-og.png" />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#0f1724; /* deep navy */
      --card:#0b1220;
      --accent:#f59e0b; /* amber */
      --muted:#9aa6b2;
      --glass: rgba(255,255,255,0.04);
    }
    *{box-sizing:border-box}
    html,body{height:100%;margin:0;font-family:Inter,system-ui,-apple-system,'Segoe UI',Roboto,"Helvetica Neue",Arial;color:#e6eef8;background:linear-gradient(180deg,var(--bg),#071023)}
    .container{max-width:1100px;margin:0 auto;padding:28px}
    header{display:flex;align-items:center;justify-content:space-between;padding:14px 0}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{width:56px;height:56px;border-radius:12px;background:linear-gradient(135deg,var(--accent),#ff6b6b);display:flex;align-items:center;justify-content:center;font-weight:800;color:#071023;font-size:22px;box-shadow:0 6px 18px rgba(0,0,0,0.5)}
    nav{display:flex;gap:18px;align-items:center}
    nav a{color:var(--muted);text-decoration:none;font-weight:600}
    nav a.cta{background:var(--accent);color:#071023;padding:8px 14px;border-radius:8px}

    .hero{display:grid;grid-template-columns:1fr 460px;gap:32px;align-items:center;padding:40px 0}
    .eyebrow{color:var(--accent);font-weight:700;text-transform:uppercase;letter-spacing:1px}
    h1{font-size:36px;margin:12px 0 6px;line-height:1.05}
    p.lead{color:var(--muted);font-size:16px;margin:0 0 18px}
    .cta-group{display:flex;gap:12px}
    .btn{padding:12px 18px;border-radius:10px;border:0;cursor:pointer;font-weight:700}
    .btn.primary{background:var(--accent);color:#071023}
    .btn.ghost{background:transparent;border:1px solid rgba(255,255,255,0.06);color:var(--muted)}

    .panel{background:linear-gradient(180deg,rgba(255,255,255,0.02),transparent);padding:18px;border-radius:14px;box-shadow:inset 0 1px 0 rgba(255,255,255,0.02)}
    .product-card{background:var(--card);border-radius:14px;padding:20px;color:#cfe8ff}
    .stat-grid{display:flex;gap:10px}
    .stat{flex:1;padding:12px;border-radius:10px;background:var(--glass);text-align:center}
    .stat b{display:block;font-size:20px;color:#fff}
    .features{display:grid;grid-template-columns:repeat(3,1fr);gap:14px;margin-top:18px}
    .feature{background:rgba(255,255,255,0.02);padding:14px;border-radius:10px}
    .feature h4{margin:6px 0 0}

    footer{margin-top:48px;padding:28px 0;border-top:1px solid rgba(255,255,255,0.03);display:flex;justify-content:space-between;align-items:center;color:var(--muted)}

    /* responsive */
    @media (max-width:900px){
      .hero{grid-template-columns:1fr;}
      .features{grid-template-columns:1fr 1fr}
      nav{display:none}
    }
    @media (max-width:520px){
      h1{font-size:28px}
      .features{grid-template-columns:1fr}
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="brand">
        <div class="logo">MM</div>
        <div>
          <div style="font-weight:800">Magic Man</div>
          <div style="font-size:12px;color:var(--muted);margin-top:2px">Crypto Guru · Instant Recharge</div>
        </div>
      </div>
      <nav>
        <a href="#features">Features</a>
        <a href="#about">About</a>
        <a class="cta" href="#signup">Get Started</a>
      </nav>
    </header>

    <main class="hero">
      <section>
        <div class="panel">
          <div class="eyebrow">Instant Recharge · Smart Insights</div>
          <h1>Magic Man — Your Crypto Guru for Instant Recharge</h1>
          <p class="lead">Magic Man is a smart crypto guru platform offering instant recharge, market insights, and automated tools. Manage assets and make smarter blockchain decisions.</p>

          <div class="cta-group">
            <button class="btn primary">Get Instant Recharge</button>
            <button class="btn ghost">See Demo</button>
          </div>

          <div style="margin-top:18px;display:flex;gap:12px;align-items:center">
            <div style="width:72px;height:72px;border-radius:12px;background:linear-gradient(135deg,#0ea5e9,#7c3aed);display:flex;align-items:center;justify-content:center;color:#fff;font-weight:800;box-shadow:0 8px 24px rgba(0,0,0,0.5)">AI</div>
            <div>
              <div style="color:var(--muted);font-size:13px">AI-powered analytics</div>
              <div style="font-weight:700">Automated signals & portfolio insights</div>
            </div>
          </div>

          <div class="stat-grid" style="margin-top:20px">
            <div class="stat"><b>24/7</b><span style="color:var(--muted)">Live Monitoring</span></div>
            <div class="stat"><b>Instant</b><span style="color:var(--muted)">Recharge</span></div>
            <div class="stat"><b>Secure</b><span style="color:var(--muted)">On-Chain Tools</span></div>
          </div>

        </div>
      </section>

      <aside class="product-card panel" aria-hidden="true">
        <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:14px">
          <div style="font-weight:800;font-size:18px">Magic Dashboard</div>
          <div style="color:var(--muted);font-size:13px">Live snapshot</div>
        </div>
        <div style="height:250px;border-radius:10px;background:linear-gradient(180deg,rgba(255,255,255,0.02),transparent);display:flex;flex-direction:column;justify-content:center;align-items:center;color:var(--muted)">
          <div style="font-size:14px">Portfolio Value</div>
          <div style="font-weight:800;font-size:24px;margin-top:8px">$12,482.70</div>
          <div style="margin-top:6px;color:var(--muted);font-size:13px">24h +3.8%</div>
        </div>

        <div class="features">
          <div class="feature">
            <h4>Instant Recharge</h4>
            <p style="margin:6px 0;color:var(--muted);font-size:13px">Top-up wallets and services instantly with on-chain automation.</p>
          </div>
          <div class="feature">
            <h4>Smart Signals</h4>
            <p style="margin:6px 0;color:var(--muted);font-size:13px">AI-driven alerts for trends, opportunities, and risk management.</p>
          </div>
          <div class="feature">
            <h4>Portfolio Tools</h4>
            <p style="margin:6px 0;color:var(--muted);font-size:13px">Track, rebalance, and optimize across chains with ease.</p>
          </div>
        </div>
      </aside>
    </main>

    <section id="features" style="margin-top:28px">
      <div class="panel product-card">
        <h3 style="margin:0 0 10px">Platform Highlights</h3>
        <ul style="margin:0;padding-left:18px;color:var(--muted)">
          <li>Secure smart-contract orchestrations for instant operations.</li>
          <li>Cross-chain compatibility and easy wallet integrations.</li>
          <li>Automated recharge flows with on-chain verifications.</li>
          <li>Data privacy-first architecture and institutional-grade tooling.</li>
        </ul>
      </div>
    </section>

    <section id="about" style="margin-top:22px">
      <div class="panel" style="padding:18px">
        <h3>About Magic Man</h3>
        <p style="color:var(--muted);margin:8px 0 0">Magic Man is built for people who want fast, secure, and intelligent crypto utilities. From instant recharge to portfolio insights, the platform brings AI-powered automation to everyday blockchain users. Designed for safety, speed, and simplicity.</p>
      </div>
    </section>

    <footer>
      <div>
        <div style="font-weight:700">Magic Man</div>
        <div style="font-size:13px;color:var(--muted)">© <span id="year"></span> Magic Man Labs</div>
      </div>
      <div style="color:var(--muted);font-size:13px">Built with ❤️ for crypto enthusiasts</div>
    </footer>
  </div>

  <script>
    document.getElementById('year').innerText = new Date().getFullYear();
  </script>
</body>
</html>
