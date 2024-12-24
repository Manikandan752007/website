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
```
admin :
</html>
<!DOCTYPE html>
<html>
    <head>
        <title>ADMINISTRATION</title>
        <style>
             body{
                background-size: 1550px;

                background-repeat: no-repeat;
                background-color: aquamarine;

            }.image-row {
                    display: flex;
                    gap: 1.4%;
                }
                .image-row img{
                    width: 170PX;
                    height: 180PX;

                }
                footer {
                    
                     color: white;
                     padding: 2px;
                     text-align: center;
                }
        </style>
            </head>
            <center>
                <body>
                    
                   <br><br><br><br>
                    <h3 style="color: brown;"> OUR MASTERS :</h3>
        <style>
            
        </style>
        
        <div  class="image-row">
            <div>
                <br><p style="color: brown; font-family: Arial, Helvetica, sans-serif;" >01.ATUL KOCHHAR</p>
               
                <b style="color: rgb(234, 36, 36);"> ( Exp: 22 years )</b>
            </div>
            <BR><img src="https://th.bing.com/th/id/OIP.29sq3N2575pkvFxArboS8QAAAA?rs=1&pid=ImgDetMain">
                
                <div>
                    <p style="color: brown; font-family: Arial, Helvetica, sans-serif;">02.TOBBY MEGUIRE</p>
                    
                    <b style="color: rgb(225, 53, 53);"> ( Exp: 8 years )</b>
                </div>
                <img src="https://th.bing.com/th/id/OIP.FqhLFiEnV8mZRhdeX82V4QHaE8?w=640&h=427&rs=1&pid=ImgDetMain">

                <div>
                    <p style="color: brown; font-family: Arial, Helvetica, sans-serif;">03.KRISHA YEAGER</p>
                    
                    <b style="color:rgb(215, 38, 38);"> ( Exp : 11 years )</b>
                </div>
                <img src="https://img.freepik.com/free-photo/low-angle-male-employee-coffee-shop_23-2148366548.jpg">

                <div>
                    <p style="color: brown; font-family: Arial, Helvetica, sans-serif;">04.NATIEL;</p>
                    
                    <b style="color: rgb(201, 51, 51);"> ( Exp : 6 years )</b>
                </div>
                <img src="https://cdn.shopify.com/s/files/1/0865/4126/files/0BE3A7E4-52D2-4E08-BEC5-09AAB3230AAF.jpg?v=1586354109">

                <div>
                    <p style="color: brown; font-family: Arial, Helvetica, sans-serif;">05.ANDREW GARFIELD</p>
                    
                    <b style="color: rgb(176, 42, 42);"> ( Exp : 10 years )</b>
                </div>
                <img src="https://s.hdnux.com/photos/70/73/36/14923653/3/rawImage.jpg">
               
            </div>
            <br>
            <br>
            <br>
        </center><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
        <footer>
            <p>&copy; 2024 Hungry Bites. All Rights Reserved</p>
        </footer>
    </body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Menu</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      background-color: #f5f5f5;
      margin: 0;
      padding: 0;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
    }

    h1 {
      font-family: 'Georgia', serif;
      color: #6b8e23;
      margin: 20px 0;
    }

    .menu {
      width: 80%;
      max-width: 800px;
      border: 1px solid #ddd;
      border-radius: 8px;
      background-color: #fff;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }

    .menu-section {
      padding: 20px;
      border-bottom: 1px solid #ddd;
    }

    .menu-section:last-child {
      border-bottom: none;
    }

    .menu-item {
      display: flex;
      justify-content: space-between;
      padding: 10px 0;
    }

    .menu-item-name {
      font-weight: bold;
      color: #333;
    }

    .menu-item-price {
      color: #888;
    }
  </style>
</head>
<body>
  <h1>Menu</h1>
  <div class="menu">
    <div class="menu-section">
      <h2>Classic Teas</h2>
      <div class="menu-item">
        <span class="menu-item-name">Green Tea</span>
        <span class="menu-item-price">50 Rs</span>
      </div>
      <div class="menu-item">
        <span class="menu-item-name">Black Tea</span>
        <span class="menu-item-price">30 Rs</span>
      </div>
      <div class="menu-item">
        <span class="menu-item-name">Herbal Tea</span>
        <span class="menu-item-price">80 Rs</span>
      </div>
    </div>
    <div class="menu-section">
      <h2>Specialty Teas</h2>
      <div class="menu-item">
        <span class="menu-item-name">Chai Tea</span>
        <span class="menu-item-price">40 Rs</span>
      </div>
      <div class="menu-item">
        <span class="menu-item-name">Matcha Tea</span>
        <span class="menu-item-price">50 Rs</span>
      </div>
      <div class="menu-item">
        <span class="menu-item-name">Oolong Tea</span>
        <span class="menu-item-price">45 Rs</span>
      </div>
      <div class="menu-item">
        <span class="menu-item-name">carrot Tea</span>
        <span class="menu-item-price">45 Rs</span>
      </div>
      <div class="menu-item">
        <span class="menu-item-name"> Yellow Tea</span>
        <span class="menu-item-price">45 Rs</span>
      </div>
      <div class="menu-item">
        <span class="menu-item-name">Pu-erh Tea</span>
        <span class="menu-item-price">45 Rs</span>
      </div>
    </div>
    <div class="menu-section">
      <h2>Iced Teas</h2>
      <div class="menu-item">
        <span class="menu-item-name">Iced Green Tea</span>
        <span class="menu-item-price">50 Rs</span>
      </div>
      <div class="menu-item">
        <span class="menu-item-name">Iced Black Tea</span>
        <span class="menu-item-price">50 Rs</span>
      </div>
      <div class="menu-item">
        <span class="menu-item-name">Hypiscas Tea</span>
        <span class="menu-item-price">50 Rs</span>
      </div>
      <div class="menu-item">
        <span class="menu-item-name">Iced Herbal Tea</span>
        <span class="menu-item-price">70 Rs</span>
      </div>
    </div>
  </div>
</body>
</html>

```
# OUTPUT:
![Screenshot (3)](https://github.com/user-attachments/assets/b5829475-d476-4635-999e-4dbb4fd2ebef)

![Screenshot 2024-12-23 192456](https://github.com/user-attachments/assets/755c17f2-7c3c-4a66-a585-c5931c524dc7)

![Screenshot 2024-12-24 214253](https://github.com/user-attachments/assets/c66b0a0b-8cd7-486e-809b-70590843b3ef)




# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
