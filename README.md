# Ex.06 Restaurant Website
## Date:29-12-2025

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
'''
<html>
<head>
    <title>Restaurant WebPage</title>
    <link href="index.css" rel="stylesheet">
</head>
<body>
<div class="container">
    <div class="box">
        <div class="item">
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </div>
    </div>
    <div class="main">
        <h1>Welcome to the Restaurant</h1>
        <h1 class="brand">vaanga sapdalam.</h1>
        <h2>Experience the secret of arabian cuisine</h2>
        <p>
           An Arabian restaurant offers rich, flavorful cuisine inspired by Middle Eastern traditions. It’s known for aromatic spices, grilled meats, fresh bread, and dishes like hummus, kebabs, and biryani. The warm hospitality and traditional décor create a cozy, welcoming dining experience.
        </p>
    </div>
    <div class="images">
        <img src="entrance.png" alt="Image1">
        <img src="interior.png" alt="Image2">
        <img src="menu.png" alt="Image3">
        <img src="kit.jpg" alt="Image4">
    </div>
</div>
<div class="footer">
    <h4>Mothish.S(25010659)</h4>
</div>
</body>
</html>

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body {
    font-family: Georgia, serif;
}
.container {
    background: url("theme.png") no-repeat center center/cover;
    min-height: 100vh;
    width: 100%;
    padding: 30px 40px;
    border: 4px solid cyan;
    border-radius: 10px;
}
.box {
    display: flex;
    justify-content: flex-end;
    margin-bottom: 40px;
}
.item {
    background-color: #eef7fb;
    padding: 15px 30px;
}
.item a {
    margin: 0 18px;
    text-decoration: underline;
    font-weight: bold;
    color: hotpink;
    font-size: 16px;
}
.main {
    text-align: center;
    color: white;
    margin-bottom: 40px;
}
.main h1 {
    font-size: 50px;
}
.main .brand {
    font-size: 70px;
    color: red;
    letter-spacing: 4px;
}
.main h2 {
    margin: 15px 0;
    font-weight: normal;
}
.main p {
    width: 70%;
    margin: 20px auto;
    font-size: 18px;
    line-height: 1.6;
}
.images {
    display: flex;
    justify-content: center;
    gap: 20px;
    margin-bottom: 40px;
}
.images img {
    width: 220px;
    height: 160px;
    object-fit: cover;
    border: 5px solid white;
    border-radius: 10px;
}
.footer {
    background-color: cyan;
    width: 100%;
    text-align: center;
    color: black;
    font-size: 14px;
    bottom: 0;
}
<html>
<head>
    <title>Menu Page</title>
    <link href="menu.css" rel="stylesheet">
</head>
<body>
<div class="container">
    <div class="box">
        <div class="item">
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </div>
    </div>
    <div class="menu-container">
        <h1>MENU</h1>
        <div class="menu-items">

            <div class="menu-card">
                <img src="kunafa.jpg">
                <h3>kunafa</h3>
                <p>Rs.250</p>
            </div>

            <div class="menu-card">
                <img src="LAMB CHops.jpg">
                <h3>Lamb chops</h3>
                <p>Rs.1500</p>
            </div>

            <div class="menu-card">
                <img src="shawarma.jpg">
                <h3>shawarma</h3>
                <p>Rs.200</p>
            </div>

            <div class="menu-card">
                <img src="PISTA.jpg">
                <h3>Pistachio</h3>
                <p>Rs.300</p>
            </div>

            <div class="menu-card">
                <img src="soup.jpg">
                <h3>soup</h3>
                <p>Rs.450</p>
            </div>

            <div class="menu-card">
                <img src="kunafa.jpg">
                <h3>desert</h3>
                <p>Rs. 305</p>
            </div>

           
            </div>
        </div>
    </div>

</div>
<div class="footer">
    <h4>Mothish.S(25010659)</h4>
</div>

</body>
</html>

<html>
<head>
    <title>Menu Page</title>
    <link href="menu.css" rel="stylesheet">
</head>
<body>
<div class="container">
    <div class="box">
        <div class="item">
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </div>
    </div>
    <div class="menu-container">
        <h1>MENU</h1>
        <div class="menu-items">

            <div class="menu-card">
                <img src="kunafa.jpg">
                <h3>kunafa</h3>
                <p>Rs.250</p>
            </div>

            <div class="menu-card">
                <img src="LAMB CHops.jpg">
                <h3>Lamb chops</h3>
                <p>Rs.1500</p>
            </div>

            <div class="menu-card">
                <img src="shawarma.jpg">
                <h3>shawarma</h3>
                <p>Rs.200</p>
            </div>

            <div class="menu-card">
                <img src="PISTA.jpg">
                <h3>Pistachio</h3>
                <p>Rs.300</p>
            </div>

            <div class="menu-card">
                <img src="soup.jpg">
                <h3>soup</h3>
                <p>Rs.450</p>
            </div>

            <div class="menu-card">
                <img src="kunafa.jpg">
                <h3>desert</h3>
                <p>Rs. 305</p>
            </div>

           
            </div>
        </div>
    </div>

</div>
<div class="footer">
    <h4>Mothish.S(25010659)</h4>
</div>

</body>
</html>

<html>
<head>
    <title>Administration Team</title>
    <link rel="stylesheet" href="admin.css">
</head>
<body>
<div class="container">
    <div class="box">
        <div class="item">
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </div>
    </div>
    <h1 class="admin-title">ADMIN'S</h1>
    <div class="team-container">

        <div class="team-card">
            <img src="ceo.jpeg">
            <h3>Mothish.S</h3>
            <p>CEO</p>
        </div>

        <div class="team-card">
            <img src="TANJIRO.png">
            <h3>TANJIRO</h3>
            <p>Marketing Manager</p>
        </div>

        <div class="team-card">
            <img src="WATER.jpg">
            <h3>giyu</h3>
            <p>Operations Manager</p>
        </div>

        <div class="team-card">
            <img src="FIRE.jpg">
            <h3>renguko</h3>
            <p>HR Manager</p>
        </div>

        <div class="team-card">
            <img src="ZeNITSU.jpg">
            <h3>ZeNITSU</h3>
            <p>Executive Chef</p>
        </div>

        <div class="team-card">
            <img src="AKAZA.jpg">
            <h3>AKAZA</h3>
            <p>Customer Service Manager</p>
        </div>

        <div class="team-card">
            <img src="TENGEN.jpg">
            <h3>TENGEN</h3>
            <p>Managing Director</p>
        </div>

    </div>
</div>
<div class="footer">
    <p>&copy;Mothish.S(25010659)</p>
</body>
</html>

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body {
    font-family: Georgia, serif;
}
.container {
    background: url("theme.png") no-repeat center center/cover;
    min-height: 100vh;
    width: 100%;
    padding: 30px 40px;
    border: 4px solid cyan;
    border-radius: 10px;
}
.box {
    display: flex;
    justify-content: flex-end;
    margin-bottom: 30px;
}
.item {
    background-color: #eef7fb;
    padding: 15px 30px;
}
.item a {
    margin: 0 18px;
    font-weight: bold;
    color: hotpink;
    text-decoration: underline;
}
.admin-title {
    font-size: 80px;
    color: greenyellow;
    letter-spacing: 6px;
    margin-bottom: 40px;
    text-align: center;
    text-decoration: underline;
}
.team-container {
    display: flex;
    justify-content: center;
    gap: 20px;
}
.team-card {
    background-color: blanchedalmond;
    width: 200px;
    padding: 15px;
    border-radius: 15px;
    text-align: center;
    box-shadow: 0 8px 18px rgba(0,0,0,0.35);
}
.team-card img {
    width: 140px;
    height: 140px;
    object-fit: cover;
    border-radius: 50%;
    margin-bottom: 15px;
}
.team-card h3 {
    font-size: 18px;
    margin-bottom: 5px;
}
.team-card p {
    font-size: 14px;
}
.footer {
    background-color: cyan;
    width: 100%;
    text-align: center;
    color: black;
    font-size: 14px;
    bottom: 0%;
}

contact.html

<html>
<head>
    <title>Contact Us</title>
    <link rel="stylesheet" href="contact.css">
</head>
<body>

<div class="container">
    <div class="box">
        <div class="item">
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </div>
    </div>
    <div class="contact-content">
        <h1 class="contact-title">CONTACT</h1>
        <div class="contact-details">
            <h2>Come And Visit us at:</h2>
            <p>
                Secret Story<br>
                7, Z-183, 5th Ave, Z Block<br>
                3/122 poonga nagar,kerala<br>
                India
            </p>
            <h2>Phone:</h2>
            <p>+91 98419 04638</p>
            <h2>Email ID:</h2>
            <p>vaangasapdalam@gmail.com</p>
        </div>
    </div>
</div>
<div class="footer">
    <p>&copy;Mothish.S(25010659)</p>
</div>
</body>
</html>

<html>
    <head>
        <title>our Restaurant</title>
        <link href="contact.css4 567" rel="stylesheet">
    </head>
    <body>
            <h1 style="font-size: 100px;" class="Contact">Contact us</h1>
            <div class="tablestyle">
            <table class="table">
                <tr>
                    <td><h1>Visit us </h1></td>
                </tr>
                <tr>
                    <td><h3>3/122 poonga nagar,602001</h3></td>
                </tr>
                <tr>
                    <td><h1>contact Number</h1></td>
                </tr>
                <tr>
                    <td><h3>010101010</h3></td>
                </tr>
                <tr>
                    <td><h1>Email:</h1></td>
                </tr>
                <tr>
                    <td><h3>vaangasapdalam@gmail.com</h3></td>
                </tr>
            </table>
        </div>
        <nav class="nav">
            <ul>
                <li><a href="index.html" style="color: white;">Home</a></li>
                <li><a href="menu.html" style="color: white;">Menu</a></li>
                <li><a href="admin.html" style="color: white;">Admin</a></li>
                <li><a href="contact.html" style="color: white;">Contact</a></li>
            </ul>
        </nav>
        <h2 class="footer">S.Mothish [25010659]</h2>
    </body>
</html>

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body {
    font-family: Georgia, serif;
}
.container {
    background: url("restbg.jpg") no-repeat center center/cover;
    min-height: 100vh;
    width: 100%;
    padding: 30px 40px;
    border: 4px solid cyan;
    border-radius: 10px;
}
.box {
    display: flex;
    justify-content: flex-end;
    margin-bottom: 40px;
}
.item {
    background-color: #eef7fb;
    padding: 15px 30px;
}
.item a {
    margin: 0 18px;
    font-weight: bold;
    color: hotpink;
    text-decoration: underline;
}
.contact-content {
    color: white;
    margin-top: 40px;
}
.contact-title {
    font-size: 90px;
    color: orange;
    letter-spacing: 6px;
    margin-bottom: 40px;
    text-align: center;
    text-decoration: underline;
}
.contact-details h2 {
    font-size: 26px;
    margin: 25px 0 10px;
    text-align: center;
}
.contact-details p {
    font-size: 18px;
    line-height: 1.6;
    text-align: center;
}
.footer {
    background-color: cyan;
    width: 100%;
    text-align: center;
    color: black;
    font-size: 14px;
    bottom: 0%;
}

'''


## OUTPUT:
![alt text](<Screenshot 2025-12-29 103338.png>)
![alt text](<Screenshot 2025-12-29 102556.png>)
![alt text](<Screenshot 2025-12-29 102539.png>)
![alt text](<Screenshot 2025-12-29 102556-1.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
