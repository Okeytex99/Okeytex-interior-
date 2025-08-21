
<!DOCTYPE html><html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Okeytex Company – Interior & Home Solutions</title>
  <meta name="description" content="Okeytex Company: Interior design, furniture supply, home renovation, and space planning. Call 08139472185." />
  <meta name="author" content="Okeytex Company" />
  <meta property="og:title" content="Okeytex Company" />
  <meta property="og:description" content="Designing Spaces, Defining Comfort." />
  <meta property="og:type" content="website" />
  <meta property="og:image" content="logo.png" />
  <link rel="icon" href="logo.png" />
  <style>
    :root {
      --bg: #0e1116;
      --card: #131823;
      --muted: #9aa4b2;
      --brand: #e4c06a; /* soft gold to match the logo */
      --text: #e8ecf1;
      --accent: #2b82f6;
      --maxw: 1200px;
      --radius: 18px;
      --shadow: 0 10px 30px rgba(0,0,0,.25);
    }
    * { box-sizing: border-box; }
    html, body { height: 100%; scroll-behavior: smooth; }
    body {
      margin: 0; font-family: ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, "Helvetica Neue", Arial, "Noto Sans", "Apple Color Emoji", "Segoe UI Emoji";
      background: radial-gradient(1200px 800px at 80% -10%, #1a2130 0%, var(--bg) 45%), var(--bg);
      color: var(--text);
      line-height: 1.6;
    }
    a { color: inherit; text-decoration: none; }
    img { max-width: 100%; display: block; }/* NAV */
.nav {
  position: sticky; top: 0; z-index: 50; backdrop-filter: blur(10px);
  background: rgba(15,18,24,.7); border-bottom: 1px solid rgba(255,255,255,.06);
}
.nav-wrap { max-width: var(--maxw); margin: 0 auto; display: flex; align-items: center; justify-content: space-between; padding: 12px 20px; }
.brand { display: flex; align-items: center; gap: 12px; font-weight: 700; letter-spacing: .4px; }
.brand img { width: 40px; height: 40px; border-radius: 10px; box-shadow: var(--shadow); object-fit: cover; }
.brand .name { font-size: 18px; }

.menu { display: flex; gap: 18px; align-items: center; }
.menu a { padding: 8px 10px; border-radius: 10px; color: var(--muted); }
.menu a:hover { background: rgba(255,255,255,.06); color: var(--text); }
.cta { background: linear-gradient(135deg, var(--brand), #f6e39a); color: #1b1f2a; padding: 10px 14px; border-radius: 12px; font-weight: 700; }

/* HERO */
.hero { position: relative; overflow: hidden; }
.hero-inner { max-width: var(--maxw); margin: 0 auto; padding: 64px 20px 40px; display: grid; grid-template-columns: 1.2fr 1fr; gap: 40px; align-items: center; }
.eyebrow { color: var(--brand); font-weight: 700; letter-spacing: .2em; font-size: 12px; text-transform: uppercase; }
h1 { font-size: clamp(32px, 4vw, 54px); margin: 10px 0 14px; line-height: 1.1; }
.sub { color: var(--muted); font-size: 18px; max-width: 56ch; }
.hero-cta { margin-top: 22px; display: flex; gap: 12px; flex-wrap: wrap; }
.btn { display: inline-flex; align-items: center; gap: 10px; padding: 12px 16px; border-radius: 12px; font-weight: 700; border: 1px solid rgba(255,255,255,.1); }
.btn.primary { background: linear-gradient(135deg, var(--brand), #f6e39a); color: #1a1d26; border: none; }
.btn.secondary { background: rgba(255,255,255,.06); color: var(--text); }

.hero-card { background: url('https://images.unsplash.com/photo-1505693416388-ac5ce068fe85?q=80&w=1600&auto=format&fit=crop') center/cover no-repeat; border-radius: var(--radius); height: 420px; position: relative; box-shadow: var(--shadow); }
.hero-card::after { content:""; position: absolute; inset: 0; background: radial-gradient(400px 300px at 70% 20%, rgba(0,0,0,.0), rgba(0,0,0,.65)); border-radius: inherit; }

/* SECTIONS */
section { padding: 72px 20px; }
.container { max-width: var(--maxw); margin: 0 auto; }
.section-title { font-size: clamp(24px, 3vw, 34px); margin: 0 0 12px; }
.section-sub { color: var(--muted); margin-bottom: 28px; }

/* SERVICES */
.grid { display: grid; gap: 20px; }
.grid-3 { grid-template-columns: repeat(3, 1fr); }
@media (max-width: 900px){ .hero-inner { grid-template-columns: 1fr; } .grid-3 { grid-template-columns: 1fr; } }

.card { background: linear-gradient(180deg, rgba(255,255,255,.03), rgba(255,255,255,.01)); border: 1px solid rgba(255,255,255,.08); border-radius: var(--radius); padding: 22px; box-shadow: var(--shadow); transition: transform .25s ease, border-color .25s ease; }
.card:hover { transform: translateY(-4px); border-color: rgba(255,255,255,.2); }
.card h3 { margin: 0 0 6px; }
.card p { margin: 0; color: var(--muted); }

/* PORTFOLIO */
.masonry { columns: 3 260px; column-gap: 16px; }
.shot { break-inside: avoid; margin: 0 0 16px; border-radius: 14px; overflow: hidden; border: 1px solid rgba(255,255,255,.08); box-shadow: var(--shadow); }

/* ABOUT */
.about { display: grid; gap: 24px; grid-template-columns: 1.1fr .9fr; }
.about img { border-radius: 16px; border: 1px solid rgba(255,255,255,.08); box-shadow: var(--shadow); }
@media (max-width: 900px){ .about { grid-template-columns: 1fr; } }

/* CONTACT */
.contact-wrap { display: grid; gap: 24px; grid-template-columns: 1.1fr .9fr; }
@media (max-width: 900px){ .contact-wrap { grid-template-columns: 1fr; } }
form { background: linear-gradient(180deg, rgba(255,255,255,.03), rgba(255,255,255,.01)); border: 1px solid rgba(255,255,255,.08); border-radius: var(--radius); padding: 22px; box-shadow: var(--shadow); }
label { display: block; font-weight: 700; margin: 10px 0 6px; }
input, textarea { width: 100%; padding: 12px 14px; border-radius: 12px; border: 1px solid rgba(255,255,255,.15); background: rgba(255,255,255,.04); color: var(--text); }
textarea { min-height: 140px; resize: vertical; }
.help { color: var(--muted); font-size: 14px; }

/* FOOTER */
footer { padding: 30px 20px 60px; border-top: 1px solid rgba(255,255,255,.08); color: var(--muted); }
.foot { max-width: var(--maxw); margin: 0 auto; display: grid; grid-template-columns: 1fr auto; align-items: center; gap: 20px; }
.social { display: flex; gap: 10px; }
.pill { border: 1px solid rgba(255,255,255,.2); padding: 8px 12px; border-radius: 999px; }

/* UTIL */
.muted { color: var(--muted); }
.hidden { display: none; }

  </style>
</head>
<body>
  <!-- NAVBAR -->
  <nav class="nav">
    <div class="nav-wrap">
      <a class="brand" href="#home">
        <!-- Replace logo.png with your uploaded logo file name (same folder) -->
        <img src="logo.png" alt="Okeytex Company Logo" />
        <span class="name">Okeytex Company</span>
      </a>
      <div class="menu" id="menu">
        <a href="#services">Services</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#about">About</a>
        <a href="#contact" class="cta">Contact</a>
      </div>
    </div>
  </nav>  <!-- HERO -->  <header id="home" class="hero">
    <div class="hero-inner">
      <div>
        <div class="eyebrow">Designing Spaces, Defining Comfort</div>
        <h1>Welcome to <span style="color: var(--brand)">Okeytex Company</span></h1>
        <p class="sub">We craft beautiful, functional interiors—from concept and space planning to bespoke furniture and full home renovation. Your vision, elevated with precision and style.</p>
        <div class="hero-cta">
          <a class="btn primary" href="#contact">Get in Touch</a>
          <a class="btn secondary" href="tel:+2348139472185">Call 08139472185</a>
        </div>
      </div>
      <div class="hero-card" aria-hidden="true"></div>
    </div>
  </header>  <!-- SERVICES -->  <section id="services">
    <div class="container">
      <h2 class="section-title">Our Services</h2>
      <p class="section-sub">End‑to‑end solutions for homes, offices, and hospitality spaces.</p>
      <div class="grid grid-3">
        <div class="card">
          <h3>Interior Design</h3>
          <p>Concept development, mood boards, and 3D visualization tailored to your lifestyle and budget.</p>
        </div>
        <div class="card">
          <h3>Furniture Supply</h3>
          <p>Premium ready-made and custom furniture pieces that balance comfort, durability, and aesthetics.</p>
        </div>
        <div class="card">
          <h3>Home Renovation</h3>
          <p>From flooring and lighting to cabinetry and finishes—planned, managed, and delivered on time.</p>
        </div>
        <div class="card">
          <h3>Space Planning</h3>
          <p>Smart layouts that optimize flow, storage, and natural light for residential and commercial spaces.</p>
        </div>
        <div class="card">
          <h3>Window Treatments</h3>
          <p>Curtains, blinds, and drapery installations—crafted to complement your interiors.</p>
        </div>
        <div class="card">
          <h3>Maintenance & Aftercare</h3>
          <p>Post‑project support to keep your space looking and functioning beautifully.</p>
        </div>
      </div>
    </div>
  </section>  <!-- PORTFOLIO -->  <section id="portfolio">
    <div class="container">
      <h2 class="section-title">Selected Work</h2>
      <p class="section-sub">A glimpse into our recent projects. (Replace with your own photos later.)</p>
      <div class="masonry">
        <img class="shot" src="https://images.unsplash.com/photo-1505691938895-1758d7feb511?q=80&w=1600&auto=format&fit=crop" alt="Modern living room" />
        <img class="shot" src="https://images.unsplash.com/photo-1505691723518-36a5ac3b2d95?q=80&w=1600&auto=format&fit=crop" alt="Minimal kitchen" />
        <img class="shot" src="https://images.unsplash.com/photo-1493666438817-866a91353ca9?q=80&w=1600&auto=format&fit=crop" alt="Elegant bedroom" />
        <img class="shot" src="https://images.unsplash.com/photo-1524758631624-e2822e304c36?q=80&w=1600&auto=format&fit=crop" alt="Office workspace" />
        <img class="shot" src="https://images.unsplash.com/photo-1484101403633-562f891dc89a?q=80&w=1600&auto=format&fit=crop" alt="Lobby design" />
        <img class="shot" src="https://images.unsplash.com/photo-1519710164239-da123dc03ef4?q=80&w=1600&auto=format&fit=crop" alt="Custom furniture" />
      </div>
    </div>
  </section>  <!-- ABOUT -->  <section id="about">
    <div class="container about">
      <div>
        <h2 class="section-title">About Okeytex Company</h2>
        <p class="section-sub">We are a Lagos/Nigeria‑based studio delivering tasteful interiors and reliable execution.</p>
        <p>Founded on craftsmanship and attention to detail, Okeytex Company blends design intelligence with practical project management. From apartments and private homes to commercial spaces, we create environments that feel refined, warm, and timeless.</p>
        <ul class="muted">
          <li>✓ Trusted by homeowners and businesses</li>
          <li>✓ Transparent pricing and clear timelines</li>
          <li>✓ Dedicated after‑service support</li>
        </ul>
      </div>
      <img src="https://images.unsplash.com/photo-1524758631624-e2822e304c36?q=80&w=1600&auto=format&fit=crop" alt="Team at work" />
    </div>
  </section>  <!-- CONTACT -->  <section id="contact">
    <div class="container contact-wrap">
      <form id="contactForm" novalidate>
        <h2 class="section-title">Get in Touch</h2>
        <p class="section-sub">We usually respond within 24 hours.</p>
        <label for="name">Name</label>
        <input id="name" name="name" type="text" placeholder="Your full name" required /><label for="email">Email</label>
    <input id="email" name="email" type="email" placeholder="you@example.com" required />

    <label for="phone">Phone (optional)</label>
    <input id="phone" name="phone" type="tel" placeholder="+234…" />

    <label for="message">Message</label>
    <textarea id="message" name="message" placeholder="Tell us about your project" required></textarea>

    <p class="help">By submitting, you agree to be contacted by Okeytex Company.</p>
    <button class="btn primary" type="submit">Send Message</button>
    <p id="formMsg" class="help" role="status" aria-live="polite"></p>
  </form>

  <div class="card" style="height: fit-content;">
    <h3>Contact Info</h3>
    <p class="muted">We’d love to hear about your project.</p>
    <p><strong>Phone:</strong> <a href="tel:+2348139472185">08139472185</a></p>
    <p><strong>WhatsApp:</strong> <a href="https://wa.me/2348139472185" target="_blank" rel="noopener">Chat on WhatsApp</a></p>
    <p><strong>Email:</strong> <a href="mailto:okechukwun99@gmail.com">okechukwun99@gmail.com</a></p>
    <p><strong>Hours:</strong> Mon–Sat, 9:00–18:00</p>
    <div class="pill" style="margin-top:10px">Okeytex Company • RC pending</div>
  </div>
</div>

  </section>  <footer>
    <div class="foot">
      <div>© <span id="year"></span> Okeytex Company. All rights reserved.</div>
      <div class="social">
        <a class="pill" href="#">Facebook</a>
        <a class="pill" href="#">Instagram</a>
        <a class="pill" href="#">X</a>
      </div>
    </div>
  </footer>  <script>
    // Replace placeholders on load
    document.getElementById('year').textContent = new Date().getFullYear();

    // Basic client-side validation + fake submit
    const form = document.getElementById('contactForm');
    const msg = document.getElementById('formMsg');

    form.addEventListener('submit', async (e) => {
      e.preventDefault();
      msg.textContent = '';

      const data = Object.fromEntries(new FormData(form).entries());
      if (!data.name || !data.email || !data.message) {
        msg.textContent = 'Please fill in Name, Email, and Message.';
        return;
      }

      // Example: send with a form service endpoint. Replace URL with your backend or Formspree endpoint.
      // await fetch('YOUR_ENDPOINT_URL', { method: 'POST', headers: { 'Content-Type': 'application/json' }, body: JSON.stringify(data) });

      form.reset();
      msg.textContent = 'Thanks! Your message has been sent.';
    });

    // Smooth scroll enhancement for older browsers
    document.querySelectorAll('a[href^="#"]').forEach(a => {
      a.addEventListener('click', (e) => {
        const id = a.getAttribute('href').slice(1);
        const el = document.getElementById(id);
        if (el) { e.preventDefault(); el.scrollIntoView({ behavior: 'smooth', block: 'start' }); }
      });
    });
  </script></body>
</html>
