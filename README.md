# Ex.06 Restaurant Website
## Date:11-11-2024

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
## index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Little Lemon</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header Section -->
    <header>
        <div class="logo">
            <img src="8.jpg" alt="Logo">
        </div>
        <nav>
            <a href="#">Home</a>
            <a href="#">Menu</a>
            <a href="#">Book</a>
            <a href="#">About</a>
        </nav>
    </header>

    <!-- Promo Section -->
    <section class="promo">
        <h2>30% Off This Weekend</h2>
        <p class="promo-line">First we eat, then we do everything else</p>
    </section>

    <!-- Main Content Section -->
    <main>
        <div class="content-box">
            <div class="card">
                <h3>Our New Menu</h3>
                <img src="1st pic.jpg" alt="New Menu">
                <p>Chettinad Chicken</p>
                <a href="#">See our new menu</a>
            </div>
            <div class="card">
                <h3>Book a table</h3>
                <img src="2nd pic.jpg" alt="Book a Table">
                <p>Reserve Now</p>
                <a href="#">Book your table now</a>
            </div>
            <div class="card">
                <h3>Opening Hours</h3>
                <img src="3rd pic.jpg" alt="Opening Hours">
                <p> Happy Meals Now Open</p>
                <p>Mon - Fri: 2pm - 10pm<br>Sat: 2pm - 11pm<br>Sun: 2pm - 9pm</p>
            </div>
        </div>
    </main>

    <!-- Footer Section -->
    <footer>
        <div class="footer-logo">
            <img src="7.jpg" alt="Little Lemon Logo">
        </div>
        <div class="footer-text">
        <p>Creativity is intelligence having fun</p>
    </footer>
</body>
</html>

```
## style.css
```

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    color: #333;
    background-color: #f9f9f9;
}
header {
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 20px;
    background-color: #333; 
    color: #fff;
}

header .logo {
    display: flex;
    align-items: center;
    justify-content: center;
    margin-bottom: 10px;
}

header nav {
    display: flex;
    gap: 15px;
    
    padding: 10px 20px; 
    border-radius: 5px; 
}

header nav a {
    color: #fff;
    text-decoration: none;
    font-size: 20px; 
}

header nav a:hover {
    color: #d3d3d3; 
}

.promo {
    background: url('back.jpg') center/cover no-repeat;
    padding: 50px;
    color: #0f0d0d;
    text-align: center;
}
.promo-line {
    font-size: 2em; 
    color: #fbf7f7;
    font-weight: bold;
}

.promo h2 {
    font-size: 4em;
    margin-bottom: 40px;
}

main {
    display: flex;
    justify-content: center;
    padding: 20px;
}

.content-box {
    display: flex;
    gap: 20px;
}

.card {
    background-color: #f8b052;
    padding: 20px;
    text-align: center;
    width: 600px;
    border-radius: 20px;
}

.card img {
    width: 100%;
    height: auto;
    border-radius: 10px;
    margin-bottom: 10px;
}

.card h3 {
    color: #333;
}

.card a {
    color: #287929;
    text-decoration: none;
}


footer {
    background-color: #f2ebeb;
    color: #191414;
    text-align: center;
    padding: 15px;
    margin-top: 20px;
}

.footer-logo img {
    width: 50px;
    display: flex;
    align-items: center;
    color: #777;
}
```

## OUTPUT:
![alt text](<Screenshot (75)-1.png>)

![alt text](<Screenshot (76)-1.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
