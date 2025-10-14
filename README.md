# Ex.07 Restaurant Website
## Date:14.10.2025

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Delizia — Modern Restaurant</title>
  <meta name="description" content="Delizia — Fresh seasonal dishes, great coffee, cozy dining." />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#fff8f5;
      --muted:#6b6b6b;
      --accent:#e76f51;
      --accent-2:#2a9d8f;
      --card:#ffffff;
      --radius:14px;
      color-scheme: light;
      font-family: 'Inter', system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
    }
    *{box-sizing:border-box}
    body{margin:0;background:linear-gradient(180deg,var(--bg),#fff);color:#222;line-height:1.5}
    .container{max-width:1100px;margin:0 auto;padding:24px}

    /* Header */
    header{display:flex;align-items:center;justify-content:space-between;padding:12px 0}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{width:48px;height:48px;border-radius:10px;background:linear-gradient(135deg,var(--accent),var(--accent-2));display:grid;place-items:center;color:white;font-weight:700}
    nav{display:flex;gap:18px;align-items:center}
    nav a{color:var(--muted);text-decoration:none;font-weight:600}
    .cta{background:var(--accent);color:white;padding:10px 14px;border-radius:10px;text-decoration:none;font-weight:700}
    .menu-toggle{display:none;border:0;background:none;font-size:20px}

    /* Hero */
    .hero{display:grid;grid-template-columns:1fr 420px;gap:28px;align-items:center;margin:28px 0}
    .hero-card{background:var(--card);padding:28px;border-radius:var(--radius);box-shadow:0 8px 30px rgba(20,20,20,0.06)}
    .kicker{color:var(--accent);font-weight:700;letter-spacing:0.6px}
    h1{margin:8px 0;font-size:34px}
    p.lead{color:var(--muted);margin:12px 0}
    .hero-meta{display:flex;gap:12px;margin-top:18px}
    .meta{background:#fff5f2;padding:10px 12px;border-radius:10px;font-weight:600}

    /* Menu section */
    .section{margin:34px 0}
    .section-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:18px}
    .dish{background:linear-gradient(180deg,#fff,#fff);padding:16px;border-radius:12px;border:1px solid rgba(0,0,0,0.04)}
    .dish h3{margin:0 0 8px 0}
    .price{color:var(--accent);font-weight:700}

    /* Gallery */
    .gallery{display:grid;grid-template-columns:repeat(4,1fr);gap:8px}
    .gallery img{width:100%;height:150px;object-fit:cover;border-radius:10px}

    /* Contact */
    .contact-grid{display:grid;grid-template-columns:1fr 1fr;gap:18px}
    form{background:var(--card);padding:18px;border-radius:12px;border:1px solid rgba(0,0,0,0.04)}
    label{display:block;margin-bottom:8px;font-weight:600}
    input,textarea,select{width:100%;padding:10px;border-radius:8px;border:1px solid #e6e6e6;margin-bottom:12px;font-size:14px}
    button{background:var(--accent-2);color:white;padding:10px 14px;border-radius:10px;border:0;font-weight:700}

    footer{margin-top:40px;padding:18px 0;color:var(--muted);text-align:center}

    /* Responsive */
    @media (max-width:1000px){
      .hero{grid-template-columns:1fr}
      .hero-card{order:2}
      .hero-visual{order:1}
      .section-grid{grid-template-columns:repeat(2,1fr)}
      .gallery{grid-template-columns:repeat(2,1fr)}
    }
    @media (max-width:700px){
      nav{display:none}
      .menu-toggle{display:block}
      .section-grid{grid-template-columns:1fr}
      .contact-grid{grid-template-columns:1fr}
      .gallery img{height:120px}
    }

    /* small helpers */
    .muted{color:var(--muted)}
    .center{display:flex;align-items:center;justify-content:center}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="brand">
        <div class="logo">D</div>
        <div>
          <div style="font-weight:800">Delizia</div>
          <div style="font-size:12px;color:var(--muted)">Seasonal • Local • Handcrafted</div>
        </div>
      </div>

      <nav>
        <a href="#menu">Menu</a>
        <a href="#about">About</a>
        <a href="#gallery">Gallery</a>
        <a href="#contact">Contact</a>
        <a class="cta" href="#reserve">Reserve</a>
      </nav>

      <button class="menu-toggle" aria-label="open menu" onclick="toggleMobileMenu()">☰</button>
    </header>

    <main>
      <section class="hero">
        <div>
          <div class="hero-card">
            <div class="kicker">NOW OPEN</div>
            <h1>Local ingredients, global flavors — welcome to Delizia</h1>
            <p class="lead">A seasonal menu inspired by regional growers. Cozy dining, full bar, and a pastry program you'll dream about.</p>
            <div class="hero-meta">
              <div class="meta">Open Mon–Sun • 9am–11pm</div>
              <div class="meta">Brunch Sat–Sun • 9am–3pm</div>
            </div>
            <div style="margin-top:18px;display:flex;gap:10px">
              <a class="cta" href="#reserve">Book a Table</a>
              <a style="background:transparent;border:1px solid rgba(0,0,0,0.06);padding:10px 14px;border-radius:10px;text-decoration:none;font-weight:700;color:var(--muted)" href="#menu">See Menu</a>
            </div>
          </div>
        </div>

        <div class="hero-visual center">
          <img src="https://images.unsplash.com/photo-1528605248644-14dd04022da1?q=80&w=800&auto=format&fit=crop&ixlib=rb-4.0.3&s=placeholder" alt="Delicious dish" style="width:100%;height:360px;object-fit:cover;border-radius:14px;box-shadow:0 12px 40px rgba(0,0,0,0.08)">
        </div>
      </section>

      <section id="menu" class="section">
        <h2>Chef's Picks</h2>
        <p class="muted">A rotating selection — here's a snapshot of what we love right now.</p>
        <div class="section-grid" style="margin-top:18px">
          <article class="dish">
            <h3>Charred Octopus <span class="price">₹620</span></h3>
            <p class="muted">Smoky octopus, lemon aioli, crispy potatoes.</p>
          </article>

          <article class="dish">
            <h3>Wild Mushroom Risotto <span class="price">₹480</span></h3>
            <p class="muted">Creamy arborio, parmesan, herb oil.</p>
          </article>

          <article class="dish">
            <h3>Grilled Paneer Steak <span class="price">₹390</span></h3>
            <p class="muted">Tandoori-spiced paneer, charred veg, pepper chutney.</p>
          </article>

          <article class="dish">
            <h3>Seared Salmon <span class="price">₹560</span></h3>
            <p class="muted">Citrus glaze, seasonal greens.</p>
          </article>

          <article class="dish">
            <h3>Truffle Fries <span class="price">₹220</span></h3>
            <p class="muted">Crispy, tossed with truffle oil & parmesan.</p>
          </article>

          <article class="dish">
            <h3>Chocolate Hazelnut Tart <span class="price">₹260</span></h3>
            <p class="muted">Buttery crust, house-made ganache.</p>
          </article>
        </div>
      </section>

      <section id="about" class="section">
        <h2>About Delizia</h2>
        <p class="muted">Born from a tiny farmers' market stall, Delizia focuses on local producers and seasonal cooking. We source ethically and craft every plate to share.</p>
      </section>

      <section id="gallery" class="section">
        <h2>Gallery</h2>
        <div class="gallery" style="margin-top:12px">
          <img alt="table setting" src="https://images.unsplash.com/photo-1523475496153-3d6cc9a3d5b3?q=80&w=800&auto=format&fit=crop&s=placeholder">
          <img alt="coffee" src="https://images.unsplash.com/photo-1517248135467-4c7edcad34c4?q=80&w=800&auto=format&fit=crop&s=placeholder">
          <img alt="dessert" src="https://images.unsplash.com/photo-1540189549336-e6e99c3679fe?q=80&w=800&auto=format&fit=crop&s=placeholder">
          <img alt="interior" src="https://images.unsplash.com/photo-1504754524776-8f4f37790ca0?q=80&w=800&auto=format&fit=crop&s=placeholder">
        </div>
      </section>

      <section id="contact" class="section">
        <h2 id="reserve">Contact & Reservations</h2>
        <div class="contact-grid" style="margin-top:12px">
          <form id="reservationForm" onsubmit="return handleReserve(event)">
            <label for="name">Full name</label>
            <input id="name" required placeholder="Your name">

            <label for="phone">Phone</label>
            <input id="phone" required placeholder="+91 98765 43210">

            <label for="date">Date & time</label>
            <input id="date" type="datetime-local" required>

            <label for="party">Party size</label>
            <select id="party">
              <option>1</option>
              <option>2</option>
              <option>3</option>
              <option>4</option>
              <option>5+</option>
            </select>

            <button type="submit">Request Reservation</button>
          </form>

          <div style="padding:12px;background:var(--card);border-radius:12px;border:1px solid rgba(0,0,0,0.04)">
            <h3>Visit Us</h3>
            <p class="muted">123 Spice Lane, Foodie District, Your City</p>
            <p class="muted">Phone: +91 22 5555 5555</p>
            <p style="margin-top:12px">Hours: Mon–Sun • 9:00 — 23:00</p>
            <div style="margin-top:12px">
              <a href="#" style="text-decoration:none;font-weight:700;color:var(--accent)">Get directions →</a>
            </div>
          </div>
        </div>
      </section>

    </main>

    <footer>
      © <span id="year"></span> Delizia — Crafted with care • <span class="muted">Made for demo</span>
    </footer>
  </div>

  <script>
    // small helper JS
    document.getElementById('year').textContent = new Date().getFullYear();

    function toggleMobileMenu(){
      const nav = document.querySelector('nav');
      if(nav.style.display === 'flex') nav.style.display = '';
      else nav.style.display = 'flex';
      nav.style.flexDirection = 'column';
      nav.style.gap = '12px';
      nav.style.position = 'absolute';
      nav.style.right = '24px';
      nav.style.top = '68px';
      nav.style.background = 'white';
      nav.style.padding = '12px';
      nav.style.borderRadius = '10px';
      nav.style.boxShadow = '0 12px 30px rgba(0,0,0,0.08)';
    }

    function handleReserve(e){
      e.preventDefault();
      const name = document.getElementById('name').value.trim();
      const phone = document.getElementById('phone').value.trim();
      const date = document.getElementById('date').value;
      if(!name || !phone || !date){
        alert('Please fill in required fields');
        return false;
      }
      // In a real site you'd POST this to your server. For demo, show a friendly message.
      alert(`Thanks ${name}! We received your reservation request for ${new Date(date).toLocaleString()}. We will contact you at ${phone}.`);
      e.target.reset();
      return false;
    }
  </script>
</body>
</html>


```

## OUTPUT:
![alt text](<Screenshot 2025-10-11 142043.png>)

![alt text](<Screenshot 2025-10-11 142059.png>)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
