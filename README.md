# Ex.06 Restaurant Website
## Date:19/11/2025

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

home.html

<html>
<head>
    <title>MY CAFE</title>
    <meta charset="utf-8">
    <link rel="stylesheet" href="style.css">
</head>
<body>
<div class="container">
    <div class="nav">
        <a href="home.html" class="active">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </div>
    <div class="tit">
       <h5D>Happy Bean cafe</h5>
    </div>
    <div class="quote-box">
    <p>“Where every cup tells a warm story.”</p>
    </div>
    <div class="offer-box">
        <img src="dis.png" alt="Weekend coffee" class="offer-image">
        <div class="offer-text">
            <h4>Weekend Offer</h4>
            <p class="offer-quote">“Sip more, spend less this weekend.”</p> 
            <p class="offer-line">Enjoy 10% off on all drinks every Saturday & Sunday!</p>
        </div>
    </div>
</div>
<footer class="f">
    <p>&copy; LOGA SRI M - (25012855)</p>
</footer>

</body>
</html>


menu.html

<html>
<head>
    <title>Cafe Menu</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="menu-container">
    <div class="nav">
        <a href="home.html">HOME</a>
        <a href="menu.html" class="active">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </div>

    <h1 class="menu-title">Our Menu</h1>

    <div class="cards">

        <div class="card">
            <img src="es.png" alt="Espresso">
            <h3>Espresso-399/-</h3>
            <p>Strong single shot of rich coffee.</p>
        </div>

        <div class="card">
            <img src="latte.png" alt="Latte">
            <h3>Latte-250/-</h3>
            <p>Espresso with steamed milk and light foam.</p>
        </div>

        <div class="card">
            <img src="cap.png" alt="Cappuccino">
            <h3>Cappuccino-299/-</h3>
            <p>Equal parts espresso, milk and foam.</p>
        </div>

        <div class="card">
            <img src="mo.png" alt="Mocha">
            <h3>Mocha-190/-</h3>
            <p>Chocolate flavored coffee with cream.</p>
        </div>

        <div class="card">
            <img src="am.png" alt="Americano">
            <h3>Americano-350/-</h3>
            <p>Espresso topped with hot water.</p>
        </div>

        <div class="card">
            <img src="cb.png" alt="Cold Brew">
            <h3>Cold Brew-260/-</h3>
            <p>Slow-brewed chilled coffee over ice.</p>
        </div>

        <div class="card">
            <img src="f.png" alt="Frappe">
            <h3>Frappe-200/-</h3>
            <p>Blended iced coffee with cream.</p>
        </div>

        <div class="card">
            <img src="hc.png" alt="Hot Chocolate">
            <h3>Hot Chocolate-150/-</h3>
            <p>Creamy cocoa topped with marshmallows.</p>
        </div>

        <div class="card">
            <img src="mt.png" alt="Masala Tea">
            <h3>Masala Tea-180/-</h3>
            <p>Spiced Indian tea brewed with milk.</p>
        </div>

        <div class="card">
            <img src="cc.png" alt="Choco Chip Cookie">
            <h3>Choco Chip Cookie-259/-</h3>
            <p>Freshly baked cookie with chocolate chips.</p>
        </div>
    </div>
</div>
<footer class="f">
    <p>&copy; LOGA SRI M - (25012855)</p>
</footer>
</body>
</html>

admin.html 

<html>
<head>
    <title>Cafe Crew</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="admin-container">
    <div class="nav">
        <a href="home.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html" class="active">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </div>

    <h1 class="admin-title">OUR CREW</h1>

    <div class="admin-row">

        <div class="admin-card">
            <img src="meme.jpg">
            <div class="admin-info">
                <h3>LOGA SRI M</h3>
                <p class="role">CEO</p>
                <p>Leads the cafe with a focus on quality and customer happiness.</p>
            </div>
        </div>

        <div class="admin-card">
            <img src="s.png">
            <div class="admin-info">
                <h3>Shinchan</h3>
                <p class="role">Marketing Manager</p>
                <p>Creates campaigns that make every coffee lover find us.</p>
            </div>
        </div>

        <div class="admin-card">
            <img src="d.png">
            <div class="admin-info">
                <h3>Doraemon</h3>
                <p class="role">Operations Manager</p>
                <p>Ensures smooth daily operations and fast service.</p>
            </div>
        </div>

        <div class="admin-card">
            <img src="nob.png">
            <div class="admin-info">
                <h3>Nobita</h3>
                <p class="role">HR Manager</p>
                <p>Takes care of the team and training.</p>
            </div>
        </div>

        <div class="admin-card">
            <img src="he.png">
            <div class="admin-info">
                <h3>Himawari</h3>
                <p class="role">Executive Chef</p>
                <p>Designs the signature coffee and dessert menu.</p>
            </div>
        </div>

        <div class="admin-card">
            <img src="hy.png">
            <div class="admin-info">
                <h3>Heidi</h3>
                <p class="role">Customer Service Manager</p>
                <p>Makes sure every guest leaves with a smile.</p>
            </div>
        </div>

    </div>
</div>
<footer class="f">
    <p>&copy; LOGA SRI M - (25012855)</p>
</footer>
</body>
</html>

contact.html

<html>
<head>
    <title>Cafe Contact</title>
    <meta charset="utf-8">
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="contact-container">
    <div class="nav">
        <a href="home.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html" class="active">CONTACT</a>
    </div>
    <div class="contactquote">
        <p>“We are already brewing your next hello.”</p>
    </div>

    <div class="contact-card">
        <h1>Contact Us</h1>
        <p class="contact-quote">“Life begins after coffee.”</p>

        <div class="contact-details">
            <p><strong>Phone:</strong> 9876556789 </p>
            <p><strong>Email:</strong> hello@happybeancafe.com</p>
            <p><strong>Address:</strong> Esimerkkikatu 10, 00100 Helsinki, Finland</p>
        </div>
    </div>
</div>
<footer class="f">
    <p>&copy; LOGA SRI M - (25012855)</p>
</footer>
</body>
</html>

style.css

body {
    margin: 0;
}
.container {
    width: 100%;
    height: 730px;
    background-image: url("ibg.png");
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
    position: relative;
}
.nav {
    position: absolute;
    top: 40px;
    right: 60px;
}
.nav a {
    color: white;
    text-decoration: none;
    font-size: 18px;
    margin-left: 25px;
    font-weight: bold;
}
.nav a:hover {
    color: gold;
}
.nav a.active{
    color: gold;
    border-bottom: 2px solid gold;
}
.tit {
    position: absolute;
    top: 16%;
    left:6%;
    font-family: 'Great Vibes', cursive;
    font-size:60;
    font-weight: 400;
    color: #faecbf;
    letter-spacing: 4px;
    text-transform: uppercase;
}
.quote-box {
    position: absolute;
    margin-top:250px;
    margin-left:210px;
    background: rgba(255, 255, 255, 0.15);
    border-radius: 14px;
    padding:10px;
    backdrop-filter: blur(8px);
    z-index: 2;
    max-width:700px;
}
.quote-box p {
    font-family: 'Poppins', sans-serif;
    font-size: 14px;
    color: #f5f5f5;
    letter-spacing: 1px;
    line-height: 1.6;
}
.offer-box{
    position: fixed;
    bottom: 80px;               
    left: 120px;
    width: 460px;
    background: rgba(0,0,0,0.65);
    border-radius: 22px;
    padding:20px;
    box-shadow: 0 10px 28px rgba(114, 110, 110, 0.4);
    color: #fff;
    text-align: center;
    z-index: 60;
    backdrop-filter: blur(4px);
}
.offer-image{
    width: 300px;
    height: 110px;
    border-radius: 20px;
    object-fit: cover;
    border: 4px solid #ffffff;
    box-shadow: 0 4px 12px rgba(0,0,0,0.35);
    margin-bottom: 10px;
}
.offer-text h4{
    margin: 0 0 6px;
    font-family: 'Poppins', sans-serif;
    font-size: 18px;
    letter-spacing: 2px;
    text-transform: uppercase;
}
.offer-quote{
    margin: 0 0 8px;
    font-family: 'Great Vibes', cursive;
    font-size: 20px;
    color: #c8a3a3;
}
.offer-line{
    font-family: 'Poppins', sans-serif;
    font-size: 18px;
    margin: 0;
    font-weight: 600;
    color: #d59396;
}


.menu-container{
    background:url(n.jpg) no-repeat center/cover;
    padding-top:22px;
}
.menu-title{
    text-align: center;
    margin-bottom: 30px;
    letter-spacing: 3px;
    color: antiquewhite;
}
.menu-container .nav{
    position: fixed;
    top: 20px;
    right: 60px;
}
.cards{
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
    padding: 0 40px 40px;
}
.card{
    width: 220px;
    background: #ffffff;
    border-radius: 8px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.15);
    padding: 15px;
    text-align: center;
    transition: transform 0.2s ease, box-shadow 0.2s ease;
    cursor: pointer;
}
.card:hover{
    transform: translateY(-8px) scale(1.03);
    box-shadow: 0 8px 20px rgba(0,0,0,0.25);
}
.card img{
    width: 100%;
    height: 150px;
    object-fit: cover;
    border-radius: 6px;
    margin-bottom: 10px;
}
.card h3{
    margin: 8px 0;
}
.card p{
    font-size: 14px;
    color: #555;
}


.admin-container{
    height:600px;
    background: url("abg.png") center/cover no-repeat;
    padding: 80px 40px 40px;
    color: #fff;
}
.admin-title{
    text-align: center;
    font-size: 40px;
    letter-spacing: 4px;
    margin-bottom:20px;
    text-transform: uppercase;
}
.admin-row{
    display: flex;
    flex-wrap: wrap;           
    justify-content: center;
    gap: 20px;
}
.admin-card{
    width: 260px;              
    display: flex;
    flex-direction: column;
    align-items: center;
    background: rgba(255,255,255,0.9);
    color: #333;
    border-radius: 18px;
    padding: 18px 12px;
    backdrop-filter: blur(4px);
    transition: transform 0.2s ease, box-shadow 0.2s ease;
}
.admin-card:hover{
    transform: translateY(-6px);
    box-shadow: 0 10px 24px rgba(0,0,0,0.35);
}
.admin-card img{
    width: 130px;
    height: 140px;
    border-radius: 50%;
    object-fit: cover;
    margin-bottom: 10px;
}
.admin-info{
    text-align: center;
}
.admin-info h3{
    margin: 0 0 4px;
    font-size: 20px;
}
.admin-info .role{
    margin: 0 0 6px;
    font-weight: 600;
    font-size: 14px;
    color: #b0662d;
}
.admin-info p{
    margin: 0;
    font-size: 13px;
}


.contact-container{
    min-height: 100vh;
    background:url(fb.png) no-repeat center/cover;
    display: flex;
    flex-direction: column;
    align-items: center;
    padding-top: 100px;      
    padding-bottom: 80px;    
}
.contactquote{
    text-align: center;
    margin-bottom: 20px;
}
.contactquote p{
    margin-top:50px;;
    font-family: 'Great Vibes', cursive;
    font-size: 42px;
    color: #ddc9b4;
}
.contact-card{
    background: #ffffff;
    padding: 30px 40px;
    border-radius: 20px;
    margin-top:60px;
    text-align: center;
    max-width: 480px;
    width: 90%;
}
.contact-card h1{
    margin-bottom: 10px;
    letter-spacing: 3px;
    text-transform: uppercase;
}
.contact-quote{
    font-style:normal;
    color: #7a5b3a;
    margin-bottom: 20px;
}
.contact-details p{
    margin: 6px 0;
    font-size: 15px;
}


.f{
    background: #111;
    color: #f5f5f5;
    text-align: center;
    padding: 10px 0;
    font-size: 13px;
    position: fixed;
    bottom: 0;
    left: 0;
    width: 100%;
    z-index: 50;
}
.f p{
    margin: 0;
    letter-spacing: 1px;
}

```

## OUTPUT:

![alt text](<Screenshot (53)-1.png>)

![alt text](<Screenshot (54).png>)

![alt text](<Screenshot (55).png>)

![alt text](<Screenshot (56).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
