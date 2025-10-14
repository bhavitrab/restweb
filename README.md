# Ex.07 Restaurant Website
## Date:14-10-25

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
HTML CODE
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>FoodWeb Restaurant</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <!-- ===== HEADER ===== -->
  <header>
    <nav class="navbar">
      <div class="logo">Food<span>Web</span></div>
      <ul class="nav-links">
        <li><a href="#home">Home</a></li>
        <li><a href="#menu">Menu</a></li>
        <li><a href="#service">Service</a></li>
        <li><a href="#about">About Us</a></li>
        <li><a href="#contact">Contact Us</a></li>
      </ul>
    </nav>
  </header>

  <!-- ===== HOME ===== -->
  <section id="home" class="home">
    <div class="home-content">
      <h1>Delicious Food, Delivered Fast</h1>
      <p>Experience mouthwatering dishes made with love and served fresh at your table.</p>
      <button class="order-btn">Order Now</button>
    </div>
    <div class="home-image">
      <img src="assets/main_img.png" alt="Delicious Dish">
    </div>
  </section>

  <!-- ===== MENU ===== -->
  <section id="menu" class="menu">
    <h2>Our Menu</h2>
    <p class="section-subtitle">Taste the best dishes curated by our top chefs.</p>

    <div class="menu-items">
      <div class="menu-card">
        <img src="assets/buger.jpg" alt="Burger">
        <h3>Classic Burger</h3>
        <p>Juicy grilled beef patty with fresh veggies & cheese.</p>
        
        <button class="order-btn">₹199</button>
      </div>
      <div class="menu-card">
        <img src="assets/pasta.jpg" alt="Pasta">
        <h3>Italian Pasta</h3>
        <p>Authentic creamy Alfredo sauce with parmesan.</p>
      
        <button class="order-btn">₹299</button>
      </div>
      <div class="menu-card">
        <img src="assets/pizza.jpg" alt="Pizza">
        <h3>Margherita Pizza</h3>
        <p>Fresh mozzarella, basil, and tomato perfection.</p>
          <button class="order-btn">₹349</button>
      </div>
    </div>
  </section>

  <!-- ===== SERVICE ===== -->
  <section id="service" class="service">
    <h2>Our Services</h2>
    <p class="section-subtitle">We make dining convenient, enjoyable, and memorable.</p>

    <div class="service-boxes">
      <div class="service-card">
        <h3>Online Delivery</h3>
        <p>Get your favorite meals delivered hot and fresh right to your doorstep.</p>
      </div>
      <div class="service-card">
        <h3>Event Catering</h3>
        <p>From birthdays to weddings, we cater events with exceptional taste.</p>
      </div>
      <div class="service-card">
        <h3>In-Restaurant Dining</h3>
        <p>Enjoy a cozy ambiance and excellent service at our restaurant.</p>
      </div>
    </div>
  </section>

  <!-- ===== ABOUT ===== -->
  <section id="about" class="about">
    <div class="about-content">
      <h2>About Us</h2>
      <p>At FoodWeb, we believe in serving happiness through flavors.  
      Our chefs use the finest ingredients and traditional recipes with a modern twist to ensure every bite delights you.
      Founded in 2020, we’ve become one of the city’s favorite dining spots, known for our quality, service, and taste.
    </div>
    <div class="about-image">
      <img src="https://images.unsplash.com/photo-1551782450-a2132b4ba21d?w=800" alt="Restaurant Interior">
    </div>
  </section>

  <!-- ===== CONTACT ===== -->
  <section id="contact" class="contact">
    <h2 >Contact Us</h2>
    <p >We’d love to hear from you! Book a table or ask anything.</p>

    <form class="contact-form">
      <input type="text" placeholder="Your Name" required>
      <input type="email" placeholder="Your Email" required>
      <textarea rows="4" placeholder="Your Message" required></textarea>
      <button type="submit" class="order-btn">Send Message</button>
    </form>
  </section>

  <!-- ===== FOOTER ===== -->
  <footer>
    <p>© 2025 FoodWeb Restaurant. All rights reserved.</p>
  </footer>
</body>
</html>
```
CSS CODE
```
/* ===== RESET ===== */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
  }
  
  /* ===== BODY ===== */
  body {
    background-color: #fff;
    color: #333;
  }
  
  /* ===== NAVBAR ===== */
  .navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #ff6600;
    padding: 15px 60px;
    box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
    border-radius: 0  0 12px  12px ; 
    width: 100%;
    
  }
  
  .logo {
    font-size: 1.8rem;
    font-weight: 700;
    color: #fff;
  }
  
  .logo span {
    color: #fff;
    opacity: 0.9;
  }
  
  .nav-links {
    list-style: none;
    display: flex;
    gap: 30px;
  }
  
  .nav-links a {
    text-decoration: none;
    color: #fff;
    font-weight: 500;
    transition: 0.3s ease;
  }
  
  .nav-links a:hover {
    color: #000;
  }
  
  /* ===== HOME ===== */
  .home {
    display: flex;
    justify-content: space-between;
    align-items: center;
    text-align: left;
    padding: 80px 60px;
    background-color: #fff;
    
  }
  
  .home-content {
    flex: 1;
    max-width: 50%;
  }
  
  .home-content h1 {
    font-size: 60px;
    color: #ff6600;
    margin-bottom: 20px;
    justify-content: left;
    text-align: left;
  }
  
  .home-content p {
    font-size: 24px;
    line-height: 2pc;
    color: #555;
    margin-bottom: 30px;
    text-align: left;
  }
  
  .order-btn {
    background-color: #ff6600;
    color: #fff;
    padding: 12px 28px;
    border: none;
    border-radius: 5px;
    font-size: 1rem;
    cursor: pointer;
    transition: 0.3s;
    
  }
  
  .order-btn:hover {
    background-color: #e55a00;
  }
  
  .home-image {
    flex: 1;
    text-align: right;
  }
  
  .home-image img {
    width: 85%;
    border-radius: 20px;
    
  }
  
  /* ===== SECTION STYLES ===== */
  section {
    padding: 80px 60px;
    text-align: center;
  }
  
  section h2 {
    color: #ff6600;
    font-size: 2.4rem;
    margin-bottom: 10px;
  }
  
  .section-subtitle {
    color: #777;
    margin-bottom: 40px;
  }
  
  /* ===== MENU ===== */
  .menu-items {
    display: flex;
    justify-content: center;
    gap: 30px;
    flex-wrap: wrap;
  }
  
  .menu-card {
    background: #fff;
    border-radius: 15px;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
    padding: 20px;
    width: 280px;
    transition: 0.3s ease;
  }
  
  .menu-card img {
    width: 100%;
    border-radius: 10px;
    margin-bottom: 15px;
    height: 400px;
  }
  
  .menu-card h3 {
    color: #ff6600;
    margin-bottom: 10px;
  }
  
  .menu-card p {
    color: #555;
    margin-bottom: 10px;
  }
  
  .menu-card span {
    font-weight: 600;
    color: #000;
  }
  
  .menu-card:hover {
    transform: translateY(-5px);
  }
  
  /* ===== SERVICE ===== */
  .service-boxes {
    display: flex;
    justify-content: center;
    gap: 30px;
    flex-wrap: wrap;
  }
  
  .service-card {
    background-color: #fff;
    border: 2px solid #ff6600;
    border-radius: 15px;
    padding: 25px;
    width: 280px;
    transition: 0.3s;
    
  }
  
  .service-card h3 {
    color: #ff6600;
    margin-bottom: 10px;
  }
 
  
  .service-card p {
    color: #555;
  }
  
  .service-card:hover {
    background-color: #ff6600 ;
    color: #fff;
    transform: translateY(-5px);
    
  }
  
  /* ===== ABOUT ===== */
  .about {
    display: flex;
    justify-content: space-between;
    align-items: center;
    text-align: left;
    flex-wrap: wrap;
    gap: 40px;
  }
  
  .about-content {
    flex: 1;
    min-width: 300px;
    justify-content: space-between;
    gap: 24px;
  }

  .about-content h2{
    font-size: 46px;
  }
  .about-content h2:hover{
    text-decoration: underline;
    transition: 0.5s;
  }

  .about-content p{
    font-family: sans-serif;
    font-weight: 400;
    font-size: 18px;
    line-height: 2pc;
  }
  
  .about-image {
    flex: 1;
    text-align: right;
  }
  
  .about-image img {
    width: 90%;
    border-radius: 20px;
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.15);
  }
  
  /* ===== CONTACT ===== */
  .contact-form {
    max-width: 600px;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    gap: 15px;
  }
  
  .contact-form input,
  .contact-form textarea {
    padding: 12px;
    border: 1px solid #ccc;
    border-radius: 10px;
    font-size: 1rem;
  }
  
  .contact-form button {
    align-self: center;
    width: 200px;
  }
  .contact p{
    font-size: 16px;
    font-family: sans-serif;
    font-weight: 300;
    margin-bottom: 24px;
  }
  .contact h2{
    font-size: 40px;
  }
  
  /* ===== FOOTER ===== */
  footer {
    background-color: #ff6600;
    color: #fff;
    text-align: center;
    padding: 15px 0;
    margin-top: 50px;
  }
  
  /* ===== RESPONSIVE ===== */
  @media (max-width: 900px) {
    .home, .about {
      flex-direction: column;
      text-align: center;
    }
  
    .home-content, .about-content {
      max-width: 100%;
    }
  
    .home-image, .about-image {
      text-align: center;
    }
  
    .home-image img, .about-image img {
      width: 80%;
    }
  
    .nav-links {
      gap: 15px;
    }
  }
  ```


## OUTPUT:
<img width="1366" height="3100" alt="screencapture-127-0-0-1-5500-index-html-2025-10-05-13_31_07" src="https://github.com/user-attachments/assets/296c93bd-cc17-4ec4-b7f5-e424e3c70d7c" />


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
