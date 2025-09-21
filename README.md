<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>ShapedCo Medical Spa</title>
  <meta name="description" content="ShapedCo Medical Spa — personalized treatments to help you look and feel your best." />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    :root { --brand:#2a8a6e; --text:#1a1a1a; --muted:#666; --bg:#ffffff; --light:#f4f7f6; }
    * { box-sizing:border-box; }
    body { margin:0; font-family:Inter, system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif; color:var(--text); background:var(--bg); line-height:1.5; }
    a { color:inherit; text-decoration:none; }
    .container { max-width:1100px; margin:0 auto; padding:0 20px; }
    /* Header */
    header { position:sticky; top:0; z-index:10; background:#fff; border-bottom:1px solid #eee; }
    .nav { display:flex; align-items:center; justify-content:space-between; padding:14px 0; }
    .brand { font-weight:700; font-size:20px; color:var(--brand); }
    .menu { display:flex; gap:18px; }
    .menu a { padding:8px 10px; border-radius:8px; }
    .menu a.cta { background:var(--brand); color:#fff; font-weight:600; }
    /* Hero */
    .hero { background:var(--light); }
    .hero .wrap { display:grid; gap:24px; grid-template-columns:1fr; padding:48px 0; }
    .hero h1 { font-size:34px; line-height:1.15; margin:0 0 12px; }
    .hero p { color:var(--muted); margin:0 0 20px; }
    .btn { display:inline-block; padding:12px 18px; border-radius:10px; background:var(--brand); color:#fff; font-weight:600; }
    .btn.outline { background:transparent; color:var(--brand); border:2px solid var(--brand); }
    .hero img { width:100%; border-radius:14px; }
    /* Sections */
    section { padding:52px 0; }
    .cards { display:grid; grid-template-columns:1fr; gap:18px; }
    .card { padding:18px; border:1px solid #eee; border-radius:14px; background:#fff; }
    .card h3 { margin:0 0 6px; }
    .muted { color:var(--muted); }
    /* Footer */
    footer { border-top:1px solid #eee; padding:28px 0; color:var(--muted); font-size:14px; }
    /* Larger screens */
    @media (min-width: 820px){
      .hero .wrap { grid-template-columns:1.2fr 1fr; align-items:center; }
      .cards { grid-template-columns:repeat(3, 1fr); }
      .hero h1 { font-size:44px; }
    }
  </style>
</head>
<body>
  <header>
    <div class="container nav">
      <a class="brand" href="/">ShapedCo Medical Spa</a>
      <nav class="menu">
        <a href="/treatments.html">Treatments</a>
        <a href="/training.html">Training</a>
        <a href="/testing.html">Testing</a>
        <a class="cta" href="/book.html">Book Now</a>
      </nav>
    </div>
  </header>

  <main>
    <!-- HERO -->
    <section class="hero">
      <div class="container wrap">
        <div>
          <h1>Look refreshed. Feel confident.</h1>
          <p>Safe, professional medical-spa treatments tailored to you. Book a consultation to create your personalized plan.</p>
          <div style="display:flex; gap:10px; flex-wrap:wrap;">
            <a class="btn" href="/book.html">Book a Consultation</a>
            <a class="btn outline" href="/treatments.html">View Treatments</a>
          </div>
          <p class="muted" style="margin-top:14px;">Open Mon–Sat · Insurance not required</p>
        </div>
        <div>
          <!-- Replace the src with your own image path (e.g. /images/hero.jpg) -->
          <img src="https://images.unsplash.com/photo-1582095133179-bfd08e2fc6b3?q=80&w=1200&auto=format&fit=crop" alt="Medical spa treatment room">
        </div>
      </div>
    </section>

    <!-- SERVICES -->
    <section>
      <div class="container">
        <h2 style="margin:0 0 14px;">Popular treatments</h2>
        <p class="muted" style="margin:0 0 18px;">Ask us about packages and memberships.</p>
        <div class="cards">
          <article class="card">
            <h3>Injectables</h3>
            <p class="muted">Wrinkle relaxers and dermal fillers for natural-looking results.</p>
          </article>
          <article class="card">
            <h3>Skin Rejuvenation</h3>
            <p class="muted">Microneedling, chemical peels, and customized facials.</p>
          </article>
          <article class="card">
            <h3>Body Contouring</h3>
            <p class="muted">Non-invasive treatments to tone and tighten.</p>
          </article>
        </div>
      </div>
    </section>

    <!-- CONTACT STRIP -->
    <section style="background:var(--light);">
      <div class="container" style="display:flex; flex-wrap:wrap; gap:12px; align-items:center; justify-content:space-between;">
        <div>
          <h2 style="margin:0;">Ready to get started?</h2>
          <p class="muted" style="margin:6px 0 0;">Book online or call us: <a href="tel:+1-000-000-0000">(000) 000-0000</a></p>
        </div>
        <a class="btn" href="/book.html">Book Now</a>
      </div>
    </section>
  </main>

  <footer>
    <div class="container">
      © <span id="y"></span> ShapedCo Medical Spa · <a href="/privacy.html">Privacy</a>
    </div>
  </footer>
  <script>document.getElementById('y').textContent = new Date().getFullYear();</script>
</body>
</html>
