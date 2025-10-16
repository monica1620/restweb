# Ex.07 Restaurant Website
## Date:16/10/2025

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
team.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Modern Kitchen - Our Team</title>
    <link rel="stylesheet" href="style-admin.css">
</head>
<body>
    <header>
        <div class="header-content">
            <h1>Modern Kitchen</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="menu.html">Menu</a></li>
                    <li><a href="team.html">Our Team</a></li>
                    <li><a href="contact.html">Contact Us</a></li>
                </ul>
            </nav>
        </div>
    </header>
    <main class="team-container">
        <h2>Our Culinary Engineers</h2>
        <div class="team-grid">
            <div class="team-member">
                <div class="profile-image">
                    <img src="surya.png" alt="Chef">
                </div>
                <h4>SURYA</h4>
                <p>Executive Chef & Founder</p>
            </div>
            <div class="team-member">
                <div class="profile-image">
                    <img src="ajith.png" alt="Sous Chef Kim">
                </div>
                <h4>AJITH</h4>
                <p>Sous Chef / Molecular Specialist</p>
            </div>
            <div class="team-member">
                <div class="profile-image">
                    <img src="vijay.png" alt="Pastry Chef Lisa">
                </div>
                <h4>VIJAY</h4>
                <p>Pastry & Dessert Alchemist</p>
            </div>
            <div class="team-member">
                <div class="profile-image">
                    <img src="dhanush.png" alt="Manager Emily">
                </div>
                <h4>DHANUSH</h4>
                <p>Restaurant Manager</p>
            </div>
            <div class="team-member">
                <div class="profile-image">
                    <img src="simbu.png" alt="Service Manager">
                </div>
                <h4>SIMBU</h4>
                <p>Lead Sommelier & Service</p>
            </div>
        </div>
    </main>
    <footer>
        <p>© 2025 Modern Kitchen | Developed by Ajay Karthick R - 25018493</p>
    </footer>
</body>
</html>

menu.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Modern Kitchen - Menu</title>
    <link rel="stylesheet" href="style-menu.css">
</head>
<body>
    <header>
        <div class="header-content">
            <h1>Modern Kitchen</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="menu.html">Menu</a></li>
                    <li><a href="team.html">Our Team</a></li>
                    <li><a href="contact.html">Contact Us</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main class="menu-container">
        <div class="menu-grid">
            <div class="menu-item">
                <img src="Molecular Cooking_ Mango 'sunny side up'.jpeg" alt="Molecular Sphere">
                <h4>Molecular Mango Sphere</h4>
                <p class="description">Perfectly formed mango spheres that burst on the tongue with basil oil.</p>
                <p class="price">Price: RS.200/-</p>
            </div>
            <div class="menu-item">
                <img src="Ceasar salad.jpeg" alt="Deconstructed Salad">
                <h4>Deconstructed Caesar</h4>
                <p class="description">Romaine, Parmesan foam, and crispy croutons presented in separate states.</p>
                <p class="price">Price: RS.550/-</p>
            </div>
            <div class="menu-item">
                <img src="Beef Wellington – Bec's Table.jpeg" alt="Beef Wellington">
                <h4>Prime Beef Wellington</h4>
                <p class="description">Classic tenderloin encased in mushroom duxelles and flaky pastry.</p>
                <p class="price">Price: RS.700/-</p>
            </div>
            <div class="menu-item">
                <img src="Truffle Risotto.jpeg" alt="Truffle Risotto">
                <h4>White Truffle Risotto</h4>
                <p class="description">Creamy Italian Arborio rice with shaved white truffle and aged Pecorino.</p>
                <p class="price">Price: RS.280/-</p>
            </div>
            <div class="menu-item">
                <img src="Nitrogen.jpeg" alt="Dry Ice Cocktail">
                <h4>"Liquid Nitrogen" Old Fashioned</h4>
                <p class="description">A chilled, smoky bourbon cocktail prepared tableside for dramatic effect.</p>
                <p class="price">Price: RS.850/-</p>
            </div>
            <div class="menu-item">
                <img src="Ceasar salad.jpeg" alt="Dessert Cube">
                <h4>Compressed Chocolate Cube</h4>
                <p class="description">A dense cube of dark chocolate mousse, ganache, and cocoa nibs.</p>
                <p class="price">Price: RS.650/-</p>
            </div>
        </div>
    </main>

    <footer>
        <p>© 2025 Modern Kitchen | Developed by Ajay Karthick R - 25018493 </p>
    </footer>
</body>
</html>

index.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ajay Karthick - 25018493</title>
    <link rel="stylesheet" href="style-index.css">
</head>
<body>
    <header>
        <h1>Modern Kitchen</h1>
        <nav>
             <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="team.html">Our Team</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="hero-section">
            <div class="hero-content">
                <h2>Welcome to Modern Kitchen!</h2>
                <p>Experience molecular gastronomy and classic flavors in unexpected new states.</p>
                <p class="offer">New Series: "The Subatomic Sampler" tasting menu available this week!</p>
            </div>
        </section>

        <section class="info-cards">
            <div class="card">
                <h3>View The Menu</h3>
                <p>Explore our experimental and seasonal dishes designed by Chef Ajay Karthick R</p>
                <a href="menu.html">Explore our creations</a>
            </div>
            <div class="card">
                <h3>Reserve Your Table</h3>
                <p>Secure your spot for a truly unique and memorable dining event.</p>
                <a href="contact.html">Book your reservation</a>
            </div>
            <div class="card">
                <h3>Current Service Hours</h3>
                <p>Lunch: Tue - Fri, 11 AM - 2 PM</p>
                <p>Dinner: Tue - Sat, 5 PM - 10 PM</p>
                <p>Closed: Sunday & Monday</p>
            </div>
        </section>
    </main>

    <footer>
        <p>© 2025 Modern Kitchen | Developed by Ajay Karthick R - 25018493</p>
    </footer>
</body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Modern Kitchen - Contact Us</title>
    <link rel="stylesheet" href="style-contact.css">
</head>
<body>
    <header>
        <div class="header-content">
            <h1>Modern Kitchen</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="menu.html">Menu</a></li>
                    <li><a href="team.html">Our Team</a></li>
                    <li><a href="contact.html">Contact Us</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main class="contact-info">
        <h2>Contact & Reservations</h2>
        <p>Location:3/96 West Street Tuty </p>
        <p>Phone: +91 9585657387</p>
        <p>Email: rajaykarthick2007@gmail.com</p>
        
    </main>

    <footer>
        <p>© 2025 Modern Kitchen | Developed by Ajay Karthick R - 25018493</p>
    </footer>
</body>
</html>

style-admin.css

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    text-align: center;
    color: #333;
}

header {
    background-color: #666; 
    padding: 20px 0;
    color: #fff;
}

.header-content {
    max-width: 1200px;
    margin: 0 auto;
}

h1 {
    font-size: 2em;
    margin-bottom: 10px;
    color: #fff;
}

nav ul {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
    justify-content: center;
    gap: 20px;
}

nav a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
    padding: 5px 10px;
}

nav a:hover {
    color: #ffd700;
}


.team-container {
    padding: 40px 20px;
    max-width: 1200px;
    margin: 0 auto;
}

.team-container h2 {
    text-align: left;
    margin-bottom: 30px;
    font-size: 1.8em;
}

.team-grid {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    gap: 20px;
}

.team-member {
    background-color: #fff;
    border: 1px solid #ccc;
    border-radius: 8px;
    overflow: hidden;
    width: 200px;
    text-align: center;
    padding: 15px 0 20px 0;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.profile-image {
    width: 150px;
    height: 200px;
    margin: 0 auto 15px auto;
    overflow: hidden;
    border-radius: 10px; 
    position: relative;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
}

.profile-image img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    border-radius: 50%/70%; 
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}

.team-member h4 {
    margin: 5px 0 2px 0;
    color: #333;
}

.team-member p {
    font-size: 0.9em;
    color: #666;
    margin: 0;
}

footer {
    background-color: #666;
    color: #ccc;
    padding: 10px 0;
    font-size: 0.9em;
}

style-contact.css

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    text-align: center;
    color: #333;
    min-height: 100vh; 
    display: flex;
    flex-direction: column;
}

header {
    background-color: #666;
    padding: 20px 0;
    color: #fff;
}

.header-content {
    max-width: 1200px;
    margin: 0 auto;
}

h1 {
    font-size: 2em;
    margin-bottom: 10px;
    color: #fff;
}

nav ul {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
    justify-content: center;
    gap: 20px;
}

nav a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
    padding: 5px 10px;
}

nav a:hover {
    color: #ffd700;
}


main {
    flex-grow: 1;
    max-width: 600px;
    margin: 0 auto;
    background-color: #fff;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    margin-top: 40px;
    margin-bottom: 40px;
}

.contact-info h2 {
    color: #333;
    margin-bottom: 20px;
    font-size: 2em;
}

.contact-info p {
    font-size: 1.1em;
    line-height: 1.6;
    margin: 10px 0;
}

footer {
    background-color: #666;
    color: #ccc;
    padding: 10px 0;
    font-size: 0.9em;
    margin-top: auto; 
}

style-index.css

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    color: #fff; 
    background-color: #f4f4f4;
    text-align: center;
    overflow-x: hidden; 
}

header {
  
    height: 10vh; 
    background-color: #4a4a4a;
    padding: 1vh 0; 
    color: #fff;
    display: flex; 
    flex-direction: column;
    justify-content: center;
}

h1 {
    font-size: 1.5em; 
    margin: 0;
    color: #ffd700;
}

nav ul {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
    justify-content: center;
    gap: 20px;
}

nav a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
    font-size: 0.8em; 
    padding: 0;
}


.hero-section {
   
    height: 55vh; 
    
   
    background: url(indexpage.jpeg)no-repeat center center/cover;
    
    display: flex;
    align-items: center; 
    justify-content: center; 
    
    text-shadow: 1px 1px 5px rgba(0, 0, 0, 0.8);
}

.hero-content {
  
    background-color: rgba(0, 0, 0, 0.7); 
    padding: 3vh 5vw; 
    border-radius: 10px;
    max-width: 80%;
    margin: 0; 
}

.hero-content h2 {
    color: #ffd700;
    font-size: 2.5em; 
    margin-bottom: 10px;
}

.hero-content p {
    font-size: 1em;
    margin-bottom: 10px;
    color: #fff;
}

.hero-content p.offer {
    color: #ff4500; 
    font-weight: bold;
    font-size: 1.2em; 
}


.info-cards {
    
    height: 25vh; 
    
    display: flex;
    justify-content: center;
    align-items: center; 
    gap: 20px; 
    padding: 0 10px; 
    background-color: #ffffff; 
    color: #333; 
}

.card {
    background-color: #ffffff; 
    border: 1px solid #ccc;
    height: 85%; 
    padding: 10px; 
    width: 30%;
    max-width: 350px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.05);
    border-radius: 8px; 
    display: flex; 
    flex-direction: column;
    justify-content: center;
}

.card h3 {
    color: #4a4a4a;
    margin-top: 0;
    border-bottom: 2px solid #ff4500;
    padding-bottom: 3px;
    margin-bottom: 5px;
    font-size: 1em; 
}

.card p {
    font-size: 0.8em; 
    color: #666;
}

.card a {
    color: #ff4500;
    text-decoration: none;
    font-weight: bold;
    display: block;
    margin-top: 5px;
    font-size: 0.8em;
}


footer {
   
    height: 10vh; 
    background-color: #333;
    color: #ccc;
    font-size: 0.9em;
    
    display: flex;
    justify-content: center;
    align-items: center;
}

footer p {
    margin: 0;
}

style-menu.css

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    text-align: center;
    color: #333;
}

header {
    background-color: #666; 
    padding: 20px 0;
    color: #fff;
}

.header-content {
    max-width: 1200px;
    margin: 0 auto;
}

h1 {
    font-size: 2em;
    margin-bottom: 10px;
    color: #fff;
}

nav ul {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
    justify-content: center;
    gap: 20px;
}

nav a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
    padding: 5px 10px;
}

nav a:hover {
    color: #ffd700;
}


.menu-container {
    padding: 40px 20px;
    max-width: 1200px;
    margin: 0 auto;
}

.menu-grid {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
}

.menu-item {
    background-color: #fff;
    border: 1px solid #ccc;
    border-radius: 8px;
    overflow: hidden;
    width: 300px;
    text-align: left;
    padding: 15px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.menu-item img {
    width: 100%;
    height: auto;
    border-radius: 4px;
    margin-bottom: 10px;
}

.menu-item h4 {
    margin: 5px 0;
    color: #ff4500; 
}

.menu-item .description {
    font-size: 0.9em;
    color: #666;
    height: 40px;
    overflow: hidden;
}

.menu-item .price {
    font-weight: bold;
    color: #333;
    margin-top: 10px;
}

footer {
    background-color: #666; 
    color: #ccc;
    padding: 10px 0;
    font-size: 0.9em;
}
```

## OUTPUT:
![alt text](<Screenshot 2025-10-09 135402.png>)
![alt text](<Screenshot 2025-10-09 135611.png>)
![alt text](<Screenshot 2025-10-09 135748.png>)
![alt text](<Screenshot 2025-10-09 135733.png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
