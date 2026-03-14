# Ex.06 Restaurant Website
## Date:14.3.2026

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
Publish the website in Localhost.

## PROGRAM:
first.html
```
<html>
    <head>
        <title>Restaurant</title>
    </head>
    <link rel="stylesheet" href="home.css">
    <body>
        <div class="bg">
            <nav>
                <div class="pgs">
                    <a href="first.html">Home</a>
                    <a href="menu.html">Menu</a>
                    <a href="admin.html">Admin</a>
                    <a href="cntct.html">Contact</a>
                </div>
            </nav>
            <div class="head">
                <h1>Safron Court</h1>
                <i>
                    <h2>Good Food Good Mood</h2>
                </i>
            </div>
            <div class="photo">
                <img src="c:\Users\acer\Desktop\WEB APPLICATION\restaurant1.jpg" width="300" height="200">
            </div>
            <div class="pic">
                <img src="c:\Users\acer\Desktop\WEB APPLICATION\r2.jpg" width="300" height="200">
            </div>
            <div class="footer">
                Created by Abinaya(25014971)
            </div>
        </div>
    </body>
</html>
```
home.css
```
.bg
{
    background-image: url(f1.webp);
    width:100%;
    height:100%;
    background-repeat: no-repeat;
    background-size: cover;
}
nav
{
    
    background-color: pink;
    left:0%;
    width:100%;
    position: fixed;
    top: 0%;
    padding:10px 90px;
}
nav a
{
    color:lavender;
    margin: 25px;
}
nav a:hover
{
    color: aquamarine;
}
.head
{
    text-align: center;
    color: black;
    padding: 15px;
    font-size: larger;
}
.photo
{
    border:solid 5px black ;
    border-radius: 7px;
    position: absolute;
    left:250px;
    bottom:250px;
}
.pic
{
     border:solid 5px black ;
    border-radius: 7px;
    position: absolute;
    left:700px;
    bottom:250px;
}
.footer
{
    bottom: 0%;
    position: fixed;
    background: palevioletred;
    color:black;
    left:0%;
    text-align: center;
    padding: 12px;
    width:100%;
}  
```
menu.html
```
<html>
    <head>
        <title>Menu</title>
        <link href="menu.css" rel="stylesheet">
    </head>
    <body>
        <div class="bg">
            <nav>
                <div class="pgs">
                    <a href="first.html">Home</a>
                    <a href="menu.html">Menu</a>
                    <a href="admin.html">Admin</a>
                    <a href="cntct.html">Contact</a>
                </div>
            </nav>
            <div class="container1">
                <div class="container2">
                    <div class="item1">
                        <img src="c:\Users\acer\Desktop\WEB APPLICATION\white.jpg">
                    </div>
                    <div class="item2">
                        <h2>White Sauce Pasta</h2>
                    </div>
                    <div class="item3">
                        <h4>299/-</h4>
                    </div>
                </div>
                <div class="container2">
                    <div class="item1">
                        <img src="c:\Users\acer\Desktop\WEB APPLICATION\pizza.jpg">
                    </div>
                    <div class="item2">
                        <h2>Pizza</h2>
                    </div>
                    <div class="item3">
                        <h4>399/-</h4>
                    </div>
                </div>
                <div class="container2">
                    <div class="item1">
                        <img src="c:\Users\acer\Desktop\WEB APPLICATION\spaghetti.jpg">
                    </div>
                    <div class="item2">
                        <h2>Spaghetti</h2>
                    </div>
                    <div class="item3">
                        <h4>259/-</h4>
                    </div>
                </div>
                <div class="container2">
                    <div class="item1">
                        <img src="c:\Users\acer\Desktop\WEB APPLICATION\brownie.jpg">
                    </div>
                    <div class="item2">
                        <h2>Brownie</h2>
                    </div>
                    <div class="item3">
                        <h4>279/-</h4>
                    </div>
                </div>
            </div>
            <div class="footer">
                Created by Abinaya(25014971)
            </div>
        </div>
    </body>
</html>
```
menu.css
```
.bg
{
    background-image: url(f1.webp);
    width:100%;
    height:100%;
    background-repeat: no-repeat;
    background-size: cover;
}
nav
{
    
    background-color: pink;
    left:0%;
    width:100%;
    position: fixed;
    top: 0%;
    padding:10px 90px;
}
nav a
{
    color:lavender;
    margin: 25px;
}
nav a:hover
{
    color: aquamarine;
}
.container1
{
    display: flex;
    gap:100px;
    padding: 100px;
}
.container2
{
    display:flex;
    flex-direction: column;
    border: solid 5px wheat;
    border-radius: 5px;
    top: 500px;
    background-color: azure;
    padding: 10px;

}
.footer
{
    bottom: 0%;
    position: fixed;
    background: palevioletred;
    color:black;
    left:0%;
    text-align: center;
    padding: 12px;
    width:100%;
}  
```
cntct.html
```
<html>
    <head>
        <title>Contact Us</title>
        <link href="cntct.css" rel="stylesheet">
    </head>
    <body>
        <div class="bg">
            <nav>
                <div class="pgs">
                    <a href="first.html">Home</a>
                    <a href="menu.html">Menu</a>
                    <a href="admin.html">Admin</a>
                    <a href="cntct.html">Contact</a>
                </div>
            </nav>
            <div class="cntct">
                Visit us on :
            </div>
            <div class="add">
                Saffron Court,
                <br>
                21,French Colony,
                <br>
                Pondicherry.
            </div>
            <div class="delivery">
                For Online Delivery :
            </div>
            <div class="app">
                Visit Our Website:www.saffroncourt.com
                <br>
                Fatest delivery
            </div>
            <div class="details">
                For further Details:
            </div>
            <div class="phn">
                Contact Number : 9456003580
                <br>
                Email : saffroncourt@gmail.com
            </div>
            <div class="footer">
                Created by Abinaya(25014971)
            </div>
        </div>
    </body>
</html>
```
cntct.css
```
.bg
{
    background-image: url(f1.webp);
    width:100%;
    height:100%;
    background-repeat: no-repeat;
    background-size: cover;
}
nav
{
    
    background-color: pink;
    left:0%;
    width:100%;
    position: fixed;
    top: 0%;
    padding:10px 90px;
}
nav a
{
    color:lavender;
    margin: 25px;
}
nav a:hover
{
    color: aquamarine;
}
.cntct
{
    top: 100px;
    left:400px;
    font-weight: bold;
    position: absolute;
    color:aquamarine;

}
.add
{
    position: absolute;
    left: 400px;
    top: 130px;
    color: azure;
}
.delivery
{
    top: 300px;
    left: 300px;
    color: beige;
    position: absolute;

}
.app
{
    position: absolute;
    left: 310px;
    top: 320px;
    color:beige;
}
.details
{
    position: absolute;
    color: blanchedalmond;
    top:400px;
    left: 300px;
}
.phn
{
    position: absolute;
    color: burlywood;
    top: 430px;
    left: 300px;
}
.footer
{
    bottom: 0%;
    position: fixed;
    background: palevioletred;
    color:black;
    left:0%;
    text-align: center;
    padding: 12px;
    width:100%;
}  
```
admin.html
```
<html>
    <head>
        <title>Admin</title>
        <link href="admin.css" rel="stylesheet">
    </head>
    <body>
        <div class="bg">
            <nav>
                <div class="pgs">
                    <a href="first.html">Home</a>
                    <a href="menu.html">Menu</a>
                    <a href="admin.html">Admin</a>
                    <a href="cntct.html">Contact</a>
                </div>
            </nav>
            <div class="container1">
                <div class="container2">
                    <div class="item1">
                        <img src="c:\Users\acer\Desktop\WEB APPLICATION\sk1.jpg" >
                    </div>
                    <div class="item2">
                        <h2>Sivakarthikeyan</h2>
                    </div>
                    <div class="item3">
                        <h4>Managing Director</h4>
                    </div>
                </div>
                <div class="container2">
                    <div class="item1">
                        <img src="c:\Users\acer\Desktop\WEB APPLICATION\dhruv.jpg">
                    </div>
                    <div class="item2">
                        <h2>Dhruv Vikram</h2>
                    </div>
                    <div class="item3">
                        <h4>Executive Chef</h4>
                    </div>
                </div>
                <div class="container2">
                    <div class="item1">
                        <img src="c:\Users\acer\Downloads\WhatsApp Image 2026-03-14 at 10.44.05 PM.jpeg">
                    </div>
                    <div class="item2">
                        <h2>Abinaya</h2>
                    </div>
                    <div class="item3">
                        <h4>CEO</h4>
                    </div>
                </div>
                <div class="container2">
                    <div class="item1">
                        <img src="c:\Users\acer\Desktop\WEB APPLICATION\download (1).jpg">
                    </div>
                    <div class="item2">
                        <h2>Virat Kholi</h2>
                    </div>
                    <div class="item3">
                        <h4>Market Head</h4>
                    </div>
                </div>
            </div>
            <div class="footer">
                Created by Abinaya(25014971)
            </div>
        </div>
    </body>
</html>
```
admin.css
```
.bg
{
    background-image: url(f1.webp);
    width:100%;
    height:100%;
    background-repeat: no-repeat;
    background-size: cover;
}
nav
{
    
    background-color: pink;
    left:0%;
    width:100%;
    position: fixed;
    top: 0%;
    padding:10px 90px;
}
nav a
{
    color:lavender;
    margin: 25px;
}
nav a:hover
{
    color: aquamarine;
}
.container1
{
    display: flex;
    gap:100px;
    padding: 100px;
}
.container2
{
    display:flex;
    flex-direction: column;
    border: solid 5px wheat;
    border-radius: 5px;
    top: 500px;
    background-color: azure;
    padding: 10px;

}
.footer
{
    bottom: 0%;
    position: fixed;
    background: palevioletred;
    color:black;
    left:0%;
    text-align: center;
    padding: 12px;
    width:100%;
}  
```

## OUTPUT:
![alt text](<abinaya/Screenshot (63).png>)
![alt text](<abinaya/Screenshot (64).png>)
![alt text](<abinaya/Screenshot (65).png>)
![alt text](<abinaya/Screenshot (66).png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
