# Ex.07 Restaurant Website
# Date:27.11.2024
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
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Restaurant Name</title>
<style>

    body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        background-color: #f8f8f8;
        background-image: url(image.jpg);
            background-size: cover;
              background-position: 100%;
              background-repeat: no-repeat;
    }

    header {
        background-color: #333;
        color: white;
        padding: 20px 0;
        text-align: center;
    }

    nav {
        display: flex;
        justify-content: center;
        background-color: #444;
    }

    nav a {
        color: white;
        padding: 14px 20px;
        text-decoration: none;
        text-align: center;
    }

    nav a:hover {
        background-color: #555;
    }

    section {
        padding: 20px;
        text-align: center;
    }

    .menu-item {
        margin: 50px;
        padding: 10px;
        border: 10px solid #ddd;
        background-color: white;
        display: inline-block;
        width: 200px;
        vertical-align: top;
    }

    footer {
        background-color: #333;
        color: white;
        padding: 10px;
        text-align: center;
    }
</style>
</head>
<body>

    <header>
        <h1 style="color: white;">HOME-STYLE COOKING</h1>
    </header>

    <nav>
        <a href="#about">About Us</a>
        <a href="#menu">Menu</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="about">
        <h2 style="color: white;">About Us</h2>
        <p style="color: white;">WELCOME TO HOME-STYLE COOKING, ENJOY OUR DELICIOUS MEAL .</p>
    </section>

    <section id="menu">
        <h2 style="color: white;">Our Menu</h2>

        <div class="menu-item">
            <h3 style="color: black;">BIRYANI </h3>
            <img src="Chicken-Biryani-Recipe image 1.jpg" width="200" height="">
            <p style="color: black ;"><strong>$100</strong></p>
        </div>

        <div class="menu-item">
            <h3 style="color: black;">BURGER </h3>
            <img src="image. 2.jpg" width="200" height="">
            <p style="color: black ;"><strong> $250 </strong></p>
        </div>

        <div class="menu-item">
            <h3 style="color: black;">SAPATHI WITH FISH</h3>
            <img src="image. 3.jpg" width="160"  height="">
            <p style="color: black ;"><strong>$150</strong></p>
        </div>
    </section>

    <section id="contact">
        <h2 style="color: white;">Contact Us</h2>
        <p style="color: white;">7522 South Street, South Indian Food , Chennai</p>
        <p style="color: white;">Email:mani07052007@gmail.com</p>
        <p style="color: white;">Phone: 1234567890</p>
    </section>

    <footer>
        <p>&copy; 2024 HOME-STYLE COOKING . ALL RIGHTS REVERVED.</p>
    </footer>

</body>
</html>

```
# OUTPUT:
![alt text](<Screenshot (3).png>)
# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
