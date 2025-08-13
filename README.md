# data-portfolio

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Taiwo Adegbola – Data Analyst Portfolio</title>
  <meta name="description" content="Portfolio of Taiwo Adegbola – Data Analyst & Insurance Advisor" />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#0b1220;          /* deep navy */
      --panel:#121a2b;       /* card background */
      --muted:#9aa4b2;       /* muted text */
      --text:#f5f7fa;        /* primary text */
      --accent:#22c55e;      /* green accent */
      --accent-2:#4b5563;    /* dark gray */
      --accent-3:#06b6d4;    /* teal for links */
      --ring: rgba(34,197,94,.35);
      --shadow: 0 10px 25px rgba(0,0,0,.35);
      --radius: 18px;
    }
    *{box-sizing:border-box}
    html,body{margin:0;padding:0;font-family:Inter,system-ui,Segoe UI,Roboto,Helvetica,Arial,sans-serif;background:linear-gradient(180deg,#0b1220 0%, #0a1020 60%, #0b1220 100%);color:var(--text)}
    a{color:var(--accent-3);text-decoration:none}
    a:hover{opacity:.9;text-decoration:underline}
    .container{max-width:1100px;margin:auto;padding:28px}
    header{
      display:grid;grid-template-columns:1fr auto;gap:20px;align-items:center;margin:10px 0 26px
    }
    .brand{display:flex;align-items:center;gap:14px}
    .logo{width:48px;height:48px;border-radius:12px;background:radial-gradient(65% 65% at 30% 30%, #1f2937 0%, #0b1220 100%);border:1px solid #1f2937;box-shadow:inset 0 0 0 2px #0f1626}
    .title{font-weight:800;font-size:1.25rem;letter-spacing:.3px}
    .nav{display:flex;gap:14px;flex-wrap:wrap}
    .btn{background:var(--panel);border:1px solid #1d2a42;color:var(--text);padding:10px 14px;border-radius:12px;box-shadow:var(--shadow);display:inline-flex;gap:10px;align-items:center}
    .btn:focus,.btn:hover{outline:none;box-shadow:0 0 0 6px var(--ring)}

    .hero{margin:28px 0 18px;padding:26px;border-radius:var(--radius);background:linear-gradient(160deg,rgba(34,197,94,.08),rgba(6,182,212,.05) 35%,rgba(255,255,255,.02) 100%), var(--panel);border:1px solid #1d2a42;box-shadow:var(--shadow)}
    .hero h1{margin:0 0 10px;font-size:2.1rem;line-height:1.15}
    .tagline{color:var(--muted);font-size:1rem}

    .grid{display:grid;grid-template-columns:1fr;gap:18px}
    @media(min-width:760px){.grid{grid-template-columns:2fr 1.2fr}}

    .card{background:var(--panel);border:1px solid #1d2a42;border-radius:var(--radius);padding:18px;box-shadow:var(--shadow)}
    h2{margin:4px 0 14px;font-size:1.2rem}
    .chips{display:flex;gap:8px;flex-wrap:wrap}
    .chip{padding:6px 10px;border-radius:999px;background:#0f172a;border:1px solid #1d2a42;color:#cbd5e1;font-size:.85rem}

    .portfolio{display:grid;grid-template-columns:1fr;gap:18px}
    @media(min-width:900px){.portfolio{grid-template-columns:repeat(2,1fr)}}
    .project{border-radius:var(--radius);overflow:hidden;border:1px solid #1d2a42;background:linear-gradient(180deg,#111a2a 0%, #0f1626 100%);display:flex;flex-direction:column;min-height:320px}
    .project-img{width:100%;aspect-ratio:16/9;object-fit:cover;background:#0b1220;border-bottom:1px solid #1d2a42}
    .project-body{padding:16px 16px 18px;display:flex;flex-direction:column;gap:10px}
    .project h3{margin:0 0 4px;font-size:1.05rem}
    .meta{color:var(--muted);font-size:.95rem}
    .actions{margin-top:auto;display:flex;gap:10px;flex-wrap:wrap}
    .primary{background:linear-gradient(180deg,#1ad06b,#16a34a);border:0;color:#04140b}
    .ghost{background:transparent;border:1px solid #263b57}

    .section-gap{margin-top:28px}

    footer{margin:26px 0 40px;color:var(--muted);text-align:center}

    /* small accent bars */
    .bar{height:6px;background:linear-gradient(90deg,var(--accent), #22d3ee, #16a34a);border-radius:999px;margin:10px 0 16px;opacity:.9}

    /* badge */
    .badge{display:inline-flex;gap:8px;align-items:center;background:#0e1526;border:1px solid #1d2a42;padding:6px 10px;border-radius:999px;color:#c7d2fe}

    /* contact table */
    table{width:100%;border-collapse:separate;border-spacing:0 10px}
    td{padding:10px 12px;background:#0e1526;border:1px solid #1d2a42}
    td:first-child{width:54px;text-align:center;border-right:none;border-radius:12px 0 0 12px}
    td:last-child{border-left:none;border-radius:0 12px 12px 0}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="brand">
        <div class="logo" aria-hidden="true"></div>
        <div>
          <div class="title">Taiwo Adegbola</div>
          <div class="tagline">Data Analyst • Insurance Advisor • Public Health Enthusiast</div>
        </div>
      </div>
      <nav class="nav">
        <a class="btn" href="#portfolio">Portfolio</a>
        <a class="btn" href="#about">About</a>
        <a class="btn" href="#contact">Contact</a>
        <a class="btn primary" href="#cv">Download CV</a>
      </nav>
    </header>

    <section class="hero" id="about">
      <div class="badge">📊 Open to data projects & collaborations</div>
      <h1>Turning data into decisions that drive growth and impact.</h1>
      <p class="tagline">I work with SQL, Python, and visualization tools to deliver clear, actionable insights. My goal is to contribute these skills to international public health organizations like the WHO or CDC.</p>
      <div class="bar" aria-hidden="true"></div>
      <div class="chips">
        <span class="chip">SQL</span>
        <span class="chip">Python</span>
        <span class="chip">Tableau / Power BI</span>
        <span class="chip">Excel</span>
        <span class="chip">Data Cleaning</span>
        <span class="chip">Dashboards</span>
      </div>
    </section>

    <section class="section-gap" id="portfolio">
      <h2>📂 Portfolio</h2>
      <p class="tagline">Selected projects showcasing analytics, dashboards, and machine learning.</p>
      <div class="portfolio">
        <!-- Project 1: Customer Segmentation -->
        <article class="project">
          <img class="project-img" src="customer-segmentation.jpg" alt="Customer Segmentation dashboard mockup" />
          <div class="project-body">
            <h3>Customer Segmentation — Bike Sales Dataset</h3>
            <p class="meta">Segmented customers into ranked tiers based on purchase history to enable targeted marketing strategies.</p>
            <p class="meta"><strong>Tools:</strong> SQL, Tableau</p>
            <div class="actions">
              <a class="btn primary" href="#" target="_blank" rel="noopener">View Write‑up</a>
              <a class="btn ghost" href="#" target="_blank" rel="noopener">Dataset</a>
            </div>
          </div>
        </article>

        <!-- Project 2: Titanic ML -->
        <article class="project">
          <img class="project-img" src="titanic-ml.jpg" alt="Titanic predictive modeling visual" />
          <div class="project-body">
            <h3>Predictive Modeling — Titanic Dataset</h3>
            <p class="meta">Built and evaluated models to understand survival probabilities using passenger demographics and travel details.</p>
            <p class="meta"><strong>Tools:</strong> Python (Pandas, scikit‑learn), Jupyter</p>
            <div class="actions">
              <a class="btn primary" href="https://www.linkedin.com/pulse/predictive-modeling-hypothesis-testing-using-titanic-dataset-anietie/" target="_blank" rel="noopener">Read More</a>
              <a class="btn ghost" href="#" target="_blank" rel="noopener">Notebook</a>
            </div>
          </div>
        </article>

        <!-- Project 3: Cancer Prediction -->
        <article class="project">
          <img class="project-img" src="cancer-prediction.jpg" alt="Cancer prediction ML project" />
          <div class="project-body">
            <h3>Cancer Prediction — Machine Learning</h3>
            <p class="meta">Developed a classifier to predict malignant vs. benign cases. Included EDA, feature selection, and model comparison (Logistic Regression, Random Forest).</p>
            <p class="meta"><strong>Tools:</strong> Python (Pandas, scikit‑learn, Matplotlib)</p>
            <div class="actions">
              <a class="btn primary" href="#" target="_blank" rel="noopener">Project Page</a>
              <a class="btn ghost" href="#" target="_blank" rel="noopener">Code</a>
            </div>
          </div>
        </article>

        <!-- Project 4: Sales Performance Dashboard -->
        <article class="project">
          <img class="project-img" src="sales-performance-dashboard.png" alt="Sales Performance Analysis Dashboard" />
          <div class="project-body">
            <h3>Sales Performance Analysis Dashboard</h3>
            <p class="meta">Designed an interactive dashboard to track leads, clients, prospects, conversion rates, inspections, product mix, and weekly performance by branches and gender.</p>
            <p class="meta"><strong>Tools:</strong> Excel, Tableau/Power BI</p>
            <div class="actions">
              <a class="btn primary" href="#" target="_blank" rel="noopener">Open Dashboard</a>
              <a class="btn ghost" href="#" target="_blank" rel="noopener">Case Study</a>
            </div>
          </div>
        </article>
      </div>
    </section>

    <section class="section-gap" id="contact">
      <h2>📬 Contact</h2>
      <p class="tagline">Let’s connect and see how we can make a difference together.</p>
      <table role="presentation">
        <tbody>
          <tr>
            <td>📧</td>
            <td><a href="mailto:taiwoanalytics@gmail.com">taiwoanalytics@gmail.com</a></td>
          </tr>
          <tr>
            <td>🌐</td>
            <td><a href="https://linkedin.com/in/taiwo-analytics" target="_blank" rel="noopener">LinkedIn — Taiwo Adegbola</a></td>
          </tr>
          <tr>
            <td>💻</td>
            <td><a href="https://github.com/taiwo-analytics" target="_blank" rel="noopener">GitHub — taiwo-analytics</a></td>
          </tr>
          <tr id="cv">
            <td>⬇️</td>
            <td><a href="#" target="_blank" rel="noopener">Download my CV (PDF)</a></td>
          </tr>
          <tr>
            <td>📍</td>
            <td>Lagos, Nigeria</td>
          </tr>
        </tbody>
      </table>
    </section>

    <footer>© <span id="year"></span> Taiwo Adegbola. Built with HTML & CSS. Dark‑blue theme with green and dark‑gray accents.</footer>
  </div>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
