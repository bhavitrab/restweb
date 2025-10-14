-# Ex.07 Restaurant Website
# Date: 05/10/2025
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
inde.html:
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
         
                        <!--font for body-->
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Merienda:wght@300..900&display=swap" rel="stylesheet">
    
                             <!--font awesome icons w3 schools-->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
        <link rel="stylesheet" href="style.css">
        <title>Bibimbap Bliss</title>
    </head>
    <body>
        <!--session begins-->
        <div id="resto">
            <div id="restocontent">
                <h1>Bibimbap Bliss</h1>
                <h2>"Bringing Seoul to Your Plate"</h2>
                <b><a href="" id="menu">See Our Blissful K-Plate</a></b>
            </div>
        </div>
        <!--session ends-->
    
        <!-- header begins-->
         <div id="header">
            <nav id="navbar">
                <h1>Korean-Indo restaurant</h1>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="menu.html">Menu</a></li>
                    <li><a href="about.html">About</a></li>
                    <li><a href="contact.html">Contact Us</a></li>
                    <div id="email">
                        <a href="mailto:bibimbapbliss@gmail.com">bibimbapbliss@gmail.com</a>
                    </div>
                </ul>
            </nav>
         </div>
        <!-- header ends-->
    
        <!--menu section begins-->
        <div id="menu">
            <h1 id="section">Menu</h1>
            <div id="menu_row">
                <div id="menu_col">
                    <h2>Main course</h2>
                    <div class="box">
                        <div id="image">
                            <img src="Kimchi and Dumpling Noodle Soup.jpg">
                        </div>
                        <div id="rate">
                            <h3>Kimchi and Dumpling Ramen</h3>
                            <h4>Rs.350</h4>
                        </div>
                    </div>
                    <div class="box">
                        <div id="image">
                            <img src="Spicy Korean Silken Tofu Ramen - Sundubu Ramen (20 Minutes) - Tiffy Cooks.jpg">
                        </div>
                        <div id="rate">
                            <h3>Spicy Tofu Ramen</h3>
                            <h4>Rs.400</h4>
                        </div>
                    </div>
                    <div class="box">
                        <div id="image">
                            <img src="Korean Bibimbap Recipe_ A Delicious and Colorful Dish.jpg">
                        </div>
                        <div id="rate">
                            <h3>Bibimbap</h3>
                            <h4>Rs.450</h4>
                    <div class="box">
                        <div id="image">
                            <img src="Gimbap (Korean Seaweed Rolls) -.jpg">
                        </div>
                        <div id="rate">
                            <h3>Gimbap</h3>
                            <h4>Rs.350</h4>
                        </div>
                        </div>
                        </div>
                    </div>
                </div>
                <div id="menu_col">
                    <h2>Snacks</h2>
                    <div class="box">
                        <div id="image">
                            <img src="Korean corn dogs.jpg">
                        </div>
                        <div id="rate">
                            <h3>Corn Dogs</h3>
                            <h4>Rs.150</h4>
                        </div>
                    </div>
                    <div class="box">
                        <div id="image">
                            <img src="Korean rolled omelette (Gyeran-mari_ 계란말이).jpg">
                        </div>
                        <div id="rate">
                            <h3>Rolled omelette</h3>
                            <h4>Rs.100</h4>
                        </div>
                    </div>
                    <div class="box">
                        <div id="image">
                            <img src="Korean Spicy Chicken - Khin's Kitchen _ Korean Fried Chicken.jpg">
                        </div>
                        <div id="rate">
                            <h3>Spicy Chicken</h3>
                            <h4>Rs.200</h4>
                        <div class="box">
                            <div id="image">
                                <img src="Korean Tteokbokki with Boiled Eggs.jpg">
                            </div>
                        <div id="rate">
                            <h3>Tteokbeokki Spicy</h3>
                            <h4>Rs.250</h4>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div id="menu_col">
                    <h2>Drinks</h2>
                    <div class="box">
                        <div id="image">
                            <img src="Dalgona Coffee (Whipped Coffee) - Host The Toast.jpg">
                        </div>
                        <div id="rate">
                            <h3>Dalgona Coffee</h3>
                            <h4>Rs.380</h4>
                        </div>
                    </div>
                    <div class="box">
                        <div id="image">
                            <img src="Soju Yakult Cocktail.jpg">
                        </div>
                        <div id="rate">
                            <h3>Soju</h3>
                            <h4>Rs.200</h4>
                        </div>
                    </div>
                    <div class="box">
                        <div id="image">
                            <img src="Korean Mango Milk - Bake with Shivesh.jpg">
                        </div>
                    <div id="rate">
                        <h3>Mango Milk</h3>
                            <h4>Rs.450</h4>
                    <div class="box">
                                <div id="image">
                                    <img src="Korean Strawberry Milk Recipe (3 Ingredients) + Video.jpg">
                                </div>
                                <div id="rate">
                                    <h3>Mango Milk</h3>
                                    <h4>Rs.450</h4>
                                </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <!--menu section ends-->
    
        <!--About section begins-->
        <div id="about">
            <h1 id="section">About</h1>
            <div id="about_row">
                <h1>About Us</h1>
                <p>
                    <center>Welcome to Bibimbap Bliss, where the vibrant flavors of Korea and India unite in a delicious fusion experience! Our menu features a delightful array of dishes, from customizable bibimbap bowls to unique twists like kimchi samosas and tandoori chicken tacos. Committed to using fresh, locally sourced ingredients, we cater to all dietary preferences, ensuring everyone can savor our culinary creations. Join us for a meal that celebrates the joy of food and the warmth of community!</center>
                </p>
                </div>
            <div class="about_col">
                <div id="about_img">
                <img src="Girl_Eating_With_Chopsticks-removebg-preview.png">
                </div>
            </div>
        </div>
        <!--About section ends-->
    
        <!--Contact section begins-->
    <div id="contact">
        <h1 id="section">Contact</h1>
    <div id="contact_row">
        <div class="contact_col">
            </div>
            <div class="contact_col">
                <center>
                <p>
                    <i class="fa fa-map-marker"></i>
                    Anna Nagar, Chennai, Tamil-Nadu
                </p>
                <p>
                    <a href="mailto: bibimbapbliss@gmail.com">
                        <i class="fa fa-envelope-o"></i>
                        bibimbapbliss@gmail.com
                    </a>
                
                </p>
                <p>
                    <a href="tel: +918928364456">
                        <i class="	fa fa-phone"></i>
                        +918928364456
                    </a>
                </p>
                        <h3>
                            Follow Us on
                        </h3>
                    <p id="social">
                    <a href="">
                        <i class="	fa fa-instagram">
                        </i>
                    </a>
                    
                    <a href="">
                        <i class="fa fa-youtube-play">
                        </i>
                    </a>
    
                    <a href="">
                        <i class="fa fa-twitter">
                        </i>
                    </a>
                    <a href="">
                        <i class="fa fa-facebook-official">
                        </i>
                    </a>
                    </p>
                </p>
                </p>
            </center>    
            </div>
            <div class="contact-form-container">
                <h2>Get in Touch with Us</h2>
                <p>We'd love to hear from you! Please fill out the form below and we'll get back to you shortly.</p>
                <form method="POST" action="submit_form.php">
                    <!-- Name Input -->
                    <div class="form-group">
                        <label for="name">Name:</label>
                        <input type="text" id="name" name="name" placeholder="Enter your full name" required>
                    </div>
            
                    <!-- Email Input -->
                    <div class="form-group">
                        <label for="email">Email:</label>
                        <input type="email" id="email" name="email" placeholder="Enter your email address" required>
                    </div>
            
                    <!-- Subject Input -->
                    <div class="form-group">
                        <label for="subject">Subject:</label>
                        <input type="text" id="subject" name="subject" placeholder="Subject of your message" required>
                    </div>
            
                    <!-- Message Input -->
                    <div class="form-group">
                        <label for="message">Message:</label>
                        <textarea id="message" name="message" rows="6" placeholder="Type your message here..." required></textarea>
                    </div>
            
                    <!-- Submit Button -->
                    <div class="form-group">
                        <button type="submit" class="btn-submit">Send Message</button>
                    </div>
                    </form>                                                                          
        </div>
    </div>
    </div>
        <!--Contact section ends-->
    
    </body>
    </html>

menu.html:

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="style.css">
        <title>Menu - Bibimbap Bliss</title>
    </head>
    <body>
        <!-- Navbar -->
        <nav id="navbar">
            <h1>Bibimbap Bliss</h1>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    
        <!-- Menu Section -->
        <div id="menu">
            <h1 id="section">Menu</h1>
            <div id="menu_row">
                <div id="menu_col">
                    <h2>Main course</h2>
                    <div class="box">
                        <div id="image">
                            <img src="Kimchi and Dumpling Noodle Soup.jpg">
                        </div>
                        <div id="rate">
                            <h3>Kimchi and Dumpling Ramen</h3>
                            <h4>Rs.350</h4>
                        </div>
                    </div>
                    <div class="box">
                        <div id="image">
                            <img src="Spicy Korean Silken Tofu Ramen - Sundubu Ramen (20 Minutes) - Tiffy Cooks.jpg">
                        </div>
                        <div id="rate">
                            <h3>Spicy Tofu Ramen</h3>
                            <h4>Rs.400</h4>
                        </div>
                    </div>
                    <div class="box">
                        <div id="image">
                            <img src="Korean Bibimbap Recipe_ A Delicious and Colorful Dish.jpg">
                        </div>
                        <div id="rate">
                            <h3>Bibimbap</h3>
                            <h4>Rs.450</h4>
                    <div class="box">
                        <div id="image">
                            <img src="Gimbap (Korean Seaweed Rolls) -.jpg">
                        </div>
                        <div id="rate">
                            <h3>Gimbap</h3>
                            <h4>Rs.350</h4>
                        </div>
                        </div>
                        </div>
                    </div>
                </div>
                <div id="menu_col">
                    <h2>Snacks</h2>
                    <div class="box">
                        <div id="image">
                            <img src="Korean corn dogs.jpg">
                        </div>
                        <div id="rate">
                            <h3>Corn Dogs</h3>
                            <h4>Rs.150</h4>
                        </div>
                    </div>
                    <div class="box">
                        <div id="image">
                            <img src="Korean rolled omelette (Gyeran-mari_ 계란말이).jpg">
                        </div>
                        <div id="rate">
                            <h3>Rolled omelette</h3>
                            <h4>Rs.100</h4>
                        </div>
                    </div>
                    <div class="box">
                        <div id="image">
                            <img src="Korean Spicy Chicken - Khin's Kitchen _ Korean Fried Chicken.jpg">
                        </div>
                        <div id="rate">
                            <h3>Spicy Chicken</h3>
                            <h4>Rs.200</h4>
                        <div class="box">
                            <div id="image">
                                <img src="Korean Tteokbokki with Boiled Eggs.jpg">
                            </div>
                        <div id="rate">
                            <h3>Tteokbeokki Spicy</h3>
                            <h4>Rs.250</h4>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div id="menu_col">
                    <h2>Drinks</h2>
                    <div class="box">
                        <div id="image">
                            <img src="Dalgona Coffee (Whipped Coffee) - Host The Toast.jpg">
                        </div>
                        <div id="rate">
                            <h3>Dalgona Coffee</h3>
                            <h4>Rs.380</h4>
                        </div>
                    </div>
                    <div class="box">
                        <div id="image">
                            <img src="Soju Yakult Cocktail.jpg">
                        </div>
                        <div id="rate">
                            <h3>Soju</h3>
                            <h4>Rs.200</h4>
                        </div>
                    </div>
                    <div class="box">
                        <div id="image">
                            <img src="Korean Mango Milk - Bake with Shivesh.jpg">
                        </div>
                    <div id="rate">
                        <h3>Mango Milk</h3>
                            <h4>Rs.450</h4>
                    <div class="box">
                                <div id="image">
                                    <img src="Korean Strawberry Milk Recipe (3 Ingredients) + Video.jpg">
                                </div>
                                <div id="rate">
                                    <h3>Mango Milk</h3>
                                    <h4>Rs.450</h4>
                                </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </body>
    </html>

about.html:

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="style.css">
        <title>About - Bibimbap Bliss</title>
    </head>
    <body>
        <!-- Navbar -->
        <nav id="navbar">
            <h1>Bibimbap Bliss</h1>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    
        <!-- About Section -->
        <div id="about">
            <h1 id="section">About</h1>
            <div id="about_row">
                <h1>About Us</h1>
                <p>
                    Welcome to Bibimbap Bliss, where the vibrant flavors of Korea and India unite in a delicious fusion experience! 
                    Our menu features a delightful array of dishes, from customizable bibimbap bowls to unique twists like kimchi samosas and tandoori chicken tacos. 
                    Committed to using fresh, locally sourced ingredients, we cater to all dietary preferences, ensuring everyone can savor our culinary creations.
                    Join us for a meal that celebrates the joy of food and the warmth of community!
                </p>
                <div class="about_col">
                    <img src="Girl_Eating_With_Chopsticks-removebg-preview.png" alt="Girl Eating with Chopsticks">
                </div>
            </div>
        </div>
    </body>
    </html>

contact.html:

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="style.css">
        <title>Menu - Bibimbap Bliss</title>
    </head>
    <body>
        <!-- Navbar -->
        <nav id="navbar">
            <h1>Bibimbap Bliss</h1>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    
        <div id="contact">
            <h1 id="section">Contact</h1>
        <div id="contact_row">
            <div class="contact_col">
                </div>
                <div class="contact_col">
                    <center>
                    <p>
                        <i class="fa fa-map-marker"></i>
                        Anna Nagar, Chennai, Tamil-Nadu
                    </p>
                    <p>
                        <a href="mailto: bibimbapbliss@gmail.com">
                            <i class="fa fa-envelope-o"></i>
                            bibimbapbliss@gmail.com
                        </a>
                    
                    </p>
                    <p>
                        <a href="tel: +918928364456">
                            <i class="	fa fa-phone"></i>
                            +918928364456
                        </a>
                    </p>
                            <h3>
                                Follow Us on
                            </h3>
                        <p id="social">
                        <a href="">
                            <i class="	fa fa-instagram">
                            </i>
                        </a>
                        
                        <a href="">
                            <i class="fa fa-youtube-play">
                            </i>
                        </a>
        
                        <a href="">
                            <i class="fa fa-twitter">
                            </i>
                        </a>
                        <a href="">
                            <i class="fa fa-facebook-official">
                            </i>
                        </a>
                        </p>
                    </p>
                    </p>
                </center>    
                </div>
                <div class="contact-form-container">
                    <h2>Get in Touch with Us</h2>
                    <p>We'd love to hear from you! Please fill out the form below and we'll get back to you shortly.</p>
                    <form method="POST" action="submit_form.php">
                        <!-- Name Input -->
                        <div class="form-group">
                            <label for="name">Name:</label>
                            <input type="text" id="name" name="name" placeholder="Enter your full name" required>
                        </div>
                
                        <!-- Email Input -->
                        <div class="form-group">
                            <label for="email">Email:</label>
                            <input type="email" id="email" name="email" placeholder="Enter your email address" required>
                        </div>
                
                        <!-- Subject Input -->
                        <div class="form-group">
                            <label for="subject">Subject:</label>
                            <input type="text" id="subject" name="subject" placeholder="Subject of your message" required>
                        </div>
                
                        <!-- Message Input -->
                        <div class="form-group">
                            <label for="message">Message:</label>
                            <textarea id="message" name="message" rows="6" placeholder="Type your message here..." required></textarea>
                        </div>
                
                        <!-- Submit Button -->
                        <div class="form-group">
                            <button type="submit" class="btn-submit">Send Message</button>
                        </div>
                        </form>                                                                          
            </div>
        </div>
        </div>
    </body>
    </html>

style.css:

        *{
            margin: 0%;
            padding: 0%;
        }
        
        html{
          font-size: 100;
          scroll-behavior: smooth;
        }
        body{
            font-family: "Merienda", cursive;
            font-optical-sizing: auto;
            font-style: normal;
            overflow-x: hidden;
        }
        
        #resto{
          position: relative;
          height: 100vh;
          width: 100vw;
          display: flex;
          justify-content: center;
          text-align: center;
          align-items: center;
        }
        
        #resto::before{
          content: "";
          top: 0%;
          left: 0%;
          width: 100%;
          height: 100%;
          background-image: url("eecfa46e-ecd7-41de-a4ca-b504aa6cd5d3.jpg");
          position:absolute;
          background-repeat: no-repeat;
          background-size: cover;
          background-attachment: fixed;
          filter: brightness(50%);
        }
        
        #restocontent{
          position: absolute;
        }
        
        h1,h2{
          font-size: 3rem;
          color:lavender;
          font-style: italic;
          margin-bottom: 5rem;
        }
        #menu{
          font-family: monospace;
          font-size: 1.5rem;
          color: antiquewhite;
          border: 1px white solid;
          border-radius: 25px;
          padding: 4px;
        }
        
        #restocontent a:hover{
          background-color:cadetblue;
        }
        
        /*------------------------------------------------------------------------------------------*/
        /* header section*/
        
        #header{
          font-family: Georgia, 'Times New Roman', Times, serif;
          position: fixed;
          top: 0;
          width: 100vw;
          height: 70px;
          line-height: 70px;
        }
        
        #navbar{
        display: flex;
        justify-content: space-around;
        color:azure;
        background: rgba(134, 162, 162, 0.5);
        }
        
        #navbar h1{
        font-size: 2rem;
        font-family: sans-serif;
        color:khaki;
        text-shadow: none;
        display: flex;
        justify-content: space-around;
        }
        
        #navbar ul{
          display: flex;
        }
        
        #navbar ul li{ 
        list-style: none;
        padding: 3px 15px 3px 15px;
        }
        
        #navbar ul li a{
        text-decoration: underline;
        color:azure;
        }
        
        #email a{
          text-decoration: solid;
          padding: 3px 15px 3px 15px;
          color: lavender;
          border: 1px solid blanchedalmond;
          border-radius: 25px;
        }
        
        /*-----------------------------------------------------------------------------------------*/
        /*menu section*/
        #menu{
          padding: 0 25px 0 25px;
        }
        
        #section{
          padding: 0 25px 0 25px;
          font-family: Verdana, Geneva, Tahoma, sans-serif;
          color:black;
          text-align: center;
          font-size: 2rem;
        }
        
        #menu_row{
          padding: 0 100px 0 100px;
          display: flex;
        }
        
        #menu_col{
          border: 1px solid #bbb;
          margin: 5px;
          box-shadow: 2px 2px 2px #bbb;
          background-color: #fff;
          padding: 10px;
          flex: 1;
        }
        
        #menu_col h2{
          padding: 5px;
          color: #fff;
          text-align: center;
          background-color:dimgrey;
        }
        
        #image{
          width: 150px;
          height: 150px;
          border-radius: 50%;
          padding: 1px;
          border:2px solid black;
        }
        
        #image img{
           width: 100%;
           height: 100%;
           border-radius: 50%;
           object-fit:cover;
           border-color: black;
           top:0%;
           align-items: center;
           
        }
        
        .box{
          display: flex;
          flex-direction: column;
          align-items: center;
          text-align: center;
          margin: 5px;
        }
        
        #rate{
          color: black;
          text-align: center;
        }
        
        /*---------------------------------------------------------------------------------------*/
        /*about section*/
        
        #about{
          padding: 25px 0 25px 0;
        }
        
        #about_row{
          display:flex;
          justify-content: center;
          align-items: center;
          flex-wrap: wrap;
          padding: 0 100px 0 100px;
          color: coral;
        }
        
        .about_col{
          flex:1;
        }
        
        #about_img{
          width: 300px;
          height: 300px;
          border-radius: 50%;
          margin: auto;
        }
        
        #about_img img{
          width: 100%;
          height: 100%;
          border-radius: 50%;
          object-fit: fill;
        }
        
        /****************************************************************/
        /*Contact us*/
        
        .contact_col p,h3{
          font-weight: bold;
          color:lightpink;
          margin: 10px;
        }
        
        .contact_col p a{
          text-decoration: none;
          color:lightpink;
        }
        
        #social{
          color:black;
          margin: 3px;
        }
        
        .contact_col form{
          display: flex;
          flex-direction: column;
          background-color:wheat;
          width: 20%;
        }
        
        #get{
          font-size: 1rem;
          text-align: center;
          justify-content: center;
          color: black;
        }
        
        /* General Styling */
        body {
          font-family: 'Merienda', cursive;
          margin: 0;
          padding: 0;
          background-color: #f5f5f5;
          color: #333;
        }
        
        /* Contact Form Container */
        .contact-form-container {
          max-width: 600px;
          margin: 50px auto;
          padding: 30px;
          background-color: #ffffff;
          border-radius: 8px;
          box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        
        /* Form Header */
        .contact-form-container h2 {
          text-align: center;
          color: #333333;
          margin-bottom: 10px;
          font-size: 24px;
        }
        
        .contact-form-container p {
          text-align: center;
          color: #666666;
          margin-bottom: 20px;
          font-size: 16px;
        }
        
        /* Form Groups */
        .form-group {
          margin-bottom: 20px;
        }
        
        .form-group label {
          display: block;
          font-weight: bold;
          margin-bottom: 5px;
          color: #333333;
        }
        
        .form-group input,
        .form-group textarea {
          width: 100%;
          padding: 10px;
          border: 1px solid #dddddd;
          border-radius: 4px;
          font-size: 14px;
          font-family: inherit;
          box-sizing: border-box;
          background-color: #fdfdfd;
        }
        
        /* Textarea Specific Styling */
        .form-group textarea {
          resize: none;
        }
        
        /* Input and Textarea Focus States */
        .form-group input:focus,
        .form-group textarea:focus {
          border-color: #4CAF50;
          outline: none;
          box-shadow: 0 0 5px rgba(76, 175, 80, 0.4);
        }
        
        /* Submit Button */
        .btn-submit {
          display: block;
          width: 100%;
          padding: 10px;
          background-color: #4CAF50;
          color: #ffffff;
          border: none;
          border-radius: 4px;
          font-size: 16px;
          cursor: pointer;
          transition: background-color 0.3s ease;
          text-transform: uppercase;
          font-weight: bold;
        }
        
        .btn-submit:hover {
          background-color: #45a049;
        }
        
        /* Responsive Design */
        @media (max-width: 768px) {
          .contact-form-container {
              padding: 20px;
          }
        
          .contact-form-container h2 {
              font-size: 22px;
          }
        
          .contact-form-container p {
              font-size: 14px;
          }
        }

# OUTPUT:

![image](https://github.com/user-attachments/assets/5211a5fd-0198-468f-9fcc-22c701ece70d)
![image](https://github.com/user-attachments/assets/c822fcd7-7209-47cb-bab8-4c4b0b5ba4a9)
![image](https://github.com/user-attachments/assets/cab20d20-5d42-4a45-8c07-39817edea4b8)
![image](https://github.com/user-attachments/assets/c6eedcce-e3bb-4f4a-b36a-5d02b862ed47)
![image](https://github.com/user-attachments/assets/23501534-b43d-492d-a373-ec4c7a13b6c6)

# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
