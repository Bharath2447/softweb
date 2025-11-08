# Ex.07 Restuarant Website
## Date: 08.10.2025

## AIM:
To develop a static Resturant website to display the menu and services provided by the resturant.

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
home.html
```
<html>
    <head>
        <title>Home</title>
        <link rel="stylesheet" href="style1.css">
    </head>
    <body>
        <div class="background">
        <div class="contents">
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </div>
        <div class="restname">
            <h1><b>BELLA CUCINA</b></h1>
        </div >
        <div class="line">
            The taste of Italy!
        </div>
        <div class="lines">
            <i>"Where every bite feels like home in Italy."</i>
            <p>A cozy Italian bistro that brings authentic pasta, wood-fired pizzas, and rich sauces straight from traditional Italian recipes.</p>
        </div>
        <div class="image1">
            <img src="Image1.jpg" width="600" height="300">
        </div>
        <div class="image2">
            <img src="Image2.jpg" width="600" height="300">
        </div>
        <footer class="copyrights">
            &copy; Bharath K - (212224230036)
        </footer>
        </div>
    </body>
</html>
```
menu.html
```
<html>
    <head>
        <title>Menu</title>
        <link rel="stylesheet" href="style2.css">
    </head>
    <body>
        <div class="background">
        <div class="contents">
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </div>
        <div class="menu">
            <h1><b>MENU</b></h1>
        </div >
        <div class="menugrid">
            <div class="menuitem">
                <img src="Pizza.jpg" width="300" height="150">
                <h1>Pizza</h1>
                <p>Rs. 190</p>
            </div>
            <div class="menuitem">
                <img src="Pasta.jpg" width="300" height="150">
                <h1>Pasta</h1>
                <p>Rs. 180</p>
            </div>
            <div class="menuitem">
                <img src="Risotto.jpg" width="300" height="150">
                <h1>Risotto</h1>
                <p>Rs. 200</p>
            </div>
            <div class="menuitem">
                <img src="Lasagna.jpg" width="300" height="150">
                <h1>Lasagna</h1>
                <p>Rs. 220</p>
            </div>
            <div class="menuitem">
                <img src="Focaccia.jpg" width="300" height="150">
                <h1>Focaccia</h1>
                <p>Rs. 170</p>
            </div>
            <div class="menuitem">
                <img src="Arrosticini.jpg" width="300" height="150">
                <h1>Arrosticini</h1>
                <p>Rs. 210</p>
            </div>
            <div class="menuitem">
                <img src="Gelato.jpg" width="300" height="150">
                <h1>Gelato</h1>
                <p>Rs. 150</p>
            </div>
            <div class="menuitem">
                <img src="Tiramisu.jpg" width="300" height="150">
                <h1>Tiramisu</h1>
                <p>Rs. 200</p>
            </div>
        </div>
        <footer class="copyrights">
            &copy; Bharath K - (212224230036)
        </footer>
        </div>
    </body>
</html>
```
admin.html
```
<html>
    <head>
        <title>Admin</title>
        <link rel="stylesheet" href="style3.css">
    </head>
    <body>
        <div class="background">
        <div class="contents">
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </div>
        <div class="admin">
            <h1><b>ADMINISTRATION TEAM</b></h1>
        </div>
        <div class="admingrid">
            <div class="adminlist">
                <img src="Mypic.jpg" width="130" height="250">
                <h1>Bharath K</h1>
                <p class="post">CEO</p>
            </div>
            <div class="adminlist">
                <img src="Vijay.jpg" width="130" height="250">
                <h1>Vijay</h1>
                <p class="post">Marketing Manager</p>
            </div>
            <div class="adminlist">
                <img src="Dhoni.jpg" width="130" height="250">
                <h1>Dhoni</h1>
                <p class="post">Operations Manager</p>
            </div>
            <div class="adminlist">
                <img src="Samantha.jpg" width="130" height="250">
                <h1>Samantha</h1>
                <p class="post">HR Manager</p>
            </div>
            <div class="adminlist">
                <img src="Taehyung.jpg" width="130" height="250">
                <h1>Taehyung</h1>
                <p class="post">Executive Chef</p>
            </div>
            <div class="adminlist">
                <img src="Virat.jpg" width="130" height="250">
                <h1>Virat</h1>
                <p class="post">Customer Service Manager</p>
            </div>
        </div>
        <footer class="copyrights">
            &copy; Bharath K - (212224230036)
        </footer>
        </div>
    </body>
</html>
```
contact.html
```
<html>
    <head>
        <title>Contact</title>
        <link rel="stylesheet" href="style4.css">
    </head>
    <body>
        <div class="background">
        <div class="contents">
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </div>
        <div class="contact">
            <h1><b>CONTACT</b></h1>
        </div>
        <div class="info">
            <h1>Visit us at:</h1>
            <p>Bella Cucina<br>123, Maple Street,<br>Riverside Street, CA 173081<br>India</p>
            <br>
            <h1>Phone:</h1>
            <p>+91 98765 43210</p>
            <br>
            <h1>Email ID:</h1>
            <p>bellacucina123@gmail.com</p>
        </div>
        <footer class="copyrights">
            &copy; Bharath K - (212224230036)
        </footer>
        </div>
    </body>
</html>
```

## OUTPUT:
![alt text](<Screenshot 2025-11-08 105435.png>)
![alt text](<Screenshot 2025-11-08 110454.png>)
![alt text](<Screenshot 2025-11-08 105839.png>)
![alt text](<Screenshot 2025-11-08 110551.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
