# Ex.06 Restaurant Website
## Date:26.12.2025

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
    <title>VEG DELIGHT</title>
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
       <h5D>VEG DELIGHT</h5>
    </div>
    <div class="quote-box">
    <p>“From soil to soul,pure veg goodness”</p>
    </div>
    <div class="offer-box">
        <img src="yum.jpg" alt="Weekend meals" class="offer-image">
        <div class="offer-text">
            <h4>Weekend Offer</h4>
            <p class="offer-quote">“Every bites tastes like home”</p> 
            <p class="offer-line">Make your weekend tastier with 10% offer on veg meals</p>
        </div>
    </div>
</div>
<footer class="f">
    <p>&copy; Vinodhini M k - (25012248)</p>
</footer>

</body>
</html>
```
```
admin.html

<html>
<head>
    <title>Restuarent Crew</title>
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
            <img src="vino.jpg">
            <div class="admin-info">
                <h3>Vino</h3>
                <p class="role">CEO</p>
                <p>Managing people, quality, and service to keep customers satisfied.</p>
            </div>
        </div>

        <div class="admin-card">
            <img src="gok.jpg">
            <div class="admin-info">
                <h3>Gokul</h3>
                <p class="role">Marketing Manager</p>
                <p>Marketing that brings smiles to every table.</p>
            </div>
        </div>

        <div class="admin-card">
            <img src="lax.jpg">
            <div class="admin-info">
                <h3>Lax</h3>
                <p class="role">Operations Manager</p>
                <p>Promoting food that people love and enjoy.</p>
            </div>
        </div>

        <div class="admin-card">
            <img src="pri.jpg">
            <div class="admin-info">
                <h3>priya</h3>
                <p class="role">HR Manager</p>
                <p>ensures employees feel valued, respected, and motivated.</p>
            </div>
        </div>

        <div class="admin-card">
            <img src="aadhil.jpg">
            <div class="admin-info">
                <h3>Aadhil</h3>
                <p class="role">Executive Chef</p>
                <p>leads the kitchen to serve food that delights people.</p>
            </div>
        </div>

        <div class="admin-card">
            <img src="yuv.jpg">
            <div class="admin-info">
                <h3>Yuvan</h3>
                <p class="role">Customer Service Manager</p>
                <p>Ensuring every guest leaves with a smile.</p>
            </div>
        </div>

    </div>
</div>
<footer class="f">
    <p>&copy; Vinodhini M K - (25012248)</p>
</footer>
</body>
</html>
```
```
menu.html

<html>
<head>
    <title>Veg delight</title>
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
            <img src="palak.jpeg" alt="Palak paneer">
            <h3>palak panner-399/-</h3>
            <p>Where spinach meets perfection.</p>
        </div>

        <div class="card">
            <img src="naan.jpeg" alt="Butter naan">
            <h3>Butter naan-90/-</h3>
            <p>Soft, warm, and buttery — naan perfection.</p>
        </div>

        <div class="card">
            <img src="mushroom.jpeg" alt="Kadai mushroom">
            <h3>kadai mushroom-299/-</h3>
            <p>Where mushrooms meet bold masala.</p>
        </div>

        <div class="card">
            <img src="paneer.jpeg" alt="Paneer buttermasala">
            <h3>Paneer buttermasala-350/-</h3>
            <p>Rich gravy, soft paneer, endless love.</p>
        </div>

        <div class="card">
            <img src="dosa.jpeg" alt="Ghee Dosa">
            <h3>Ghee dosa-100/-</h3>
            <p>Crispy outside, ghee-rich inside</p>
        </div>

        <div class="card">
            <img src="gobi.jpeg" alt="Tandoori Gobi 65">
            <h3>Tandoori Gobi 65-200/-</h3>
            <p>Irresistibly crispy gobi with smoky masala.</p>
        </div>

        <div class="card">
            <img src="payasam.jpeg" alt="Elaneer payasam">
            <h3>Elaneer payasam-150/-</h3>
            <p>A refreshing blend of tender coconut and creamy sweetness.</p>
        </div>

        <div class="card">
            <img src="pongal.jpeg" alt="Ven Pongal">
            <h3>Ven pongal-140/-</h3>
            <p>Traditional Ven Pongal tempered with ghee, cashews, pepper, and cumin</p>
        </div>

        <div class="card">
            <img src="cholebha.jpeg" alt="Chole bhature">
            <h3>Chole bhature-299/-</h3>
            <p>Hearty chole, pillowy bhature, full satisfaction.</p>
        </div>

        <div class="card">
            <img src="tikka.jpeg" alt="Paneer Tikka">
            <h3>Panner Tikka-399/-</h3>
            <p>Tender paneer, marinated and flame-grilled.</p>
        </div>
    </div>
</div>
<footer class="f">
    <p>&copy; Vinodhini M k - (25012248)</p>
</footer>
</body>
</html>

```
```
contact.html

<html>
<head>
    <title>restuarant contact</title>
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
        <p>"Hungry? One call brings food to your table!"</p>
    </div>

    <div class="contact-card">
        <h1>Contact Us</h1>
        <p class="contact-quote">“Your favorite food, one call away.”</p>

        <div class="contact-details">
            <p><strong>Phone:</strong> 9876543210 </p>
            <p><strong>Email:</strong> hello@vegdelight.com</p>
            <p><strong>Address:</strong>469, Airport Rd, TNHB Colony, Civil Aerodrome Post, Coimbatore, Tamil Nadu 641014, India</p>
        </div>
    </div>
</div>
<footer class="f">
    <p>&copy; Vinodhini M K - (25012248)</p>
</footer>
</body>
</html>
```
```
style.css

body {
    margin: 0;
}
.container {
    width: 100%;
    height: 900px;
    background-image: url("veg.jpg");
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
    font-family:georgia;
    font-size:60;
    font-weight: 400;
    color: blue;
    letter-spacing: 4px;
    text-transform: uppercase;
}
.quote-box {
    position: absolute;
    margin-top:250px;
    margin-left:210px;
    background: purple);
    border-radius: 14px;
    padding:10px;
    backdrop-filter: blur(8px);
    z-index: 2;
    max-width:700px;
}
.quote-box p {
    font-family: 'Poppins', sans-serif;
    font-size: 24px;
    color: purpl;
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
    background:url(yum.jpg) no-repeat center/cover;
    padding-top:70px;
}
.menu-title{
    text-align: center;
    margin-bottom: 30px;
    letter-spacing: 3px;
    color: red;
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
    background: blanchedalmond;
    border-radius: 8px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.15);
    padding: 10px;
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
    height: 200px;
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
    height:750px;
    background: url("veg.jpg")center/cover no-repeat;
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
    background: url(thali.jpeg)no-repeat center/cover;
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
    color: red;
}
.contact-card{
    background:burlywood;
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
![alt text](<Screenshot (41).png>)
![alt text](<Screenshot (42).png>)
![alt text](<Screenshot (43).png>)
![alt text](<Screenshot (44).png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
