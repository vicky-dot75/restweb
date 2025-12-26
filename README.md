# Ex.06 Restaurant Website
## Date:

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

about.html
```
<html>
    <head>
        <link href="admin.css" rel="stylesheet"/>
    </head>
    <body>
        <div class="image">
            <img src="logo.png">
        </div>
        <div class="chefs">
            <div class="layout">
                <div>
                    <img src="download (9).jpg"/>
                    <h4><b>Head-Chef: Walter White</b></h4>
                </div>
                <div>
                    <img src="Shraddha Kapoor's beautiful face pic.jpg"/>
                    <h4><b>Sous Chef: Jesse Pinkman</b></h4>
                </div>
                <div>
                    <img src="download (6).jpg">
                    <h4><b>Manager: Thomas Shelby</b></h4>
                </div>
                <div>
                    <img src="download (7).jpg">
                    <h4>Line cook: Ella</h4>
                </div>
                <div>
                    <img src="download (8).jpg">
                    <h4>Waiter: John Cena</h4>
                </div>
                <div>
                    <img src="Chris Hemsworth.jpg"/>
                    <h4>Steward: Dwayne Johnson</h4>
                </div>
            </div>
        </div>
    </body>
</html>
```
```

booking.html
<html>
    <head>
        <title> Reservation</title>
        <style>
            body{
                background-color: beige;
            }
            form{
                text-align: center;
                font-size: 20px;
            }
            .image{
                text-align: center;
                
            }
            a{
                text-decoration: none;
                color: black;
            }
        </style>
        </head>

        <body>
            <div class="image">
                 <img src="logo.png">
            </div>
            <form>
                <label> Enter your name </label>
                <input type="text" ><br>
                <label> Phone number</label>
                <input type="number"><br>
                <label> E-mail id</label>
                <input type="email"><br>
                <label> Reservation date </label>
                <input type="date"><br>
                <label> Reservation Time</label>
                <input type="time"><br>
                <label> Number of People</label>
                <select>
                    <option>1</option> 
                    <option> 2 </option>
                    <option> More than 2</option>
                </select><br>
                <label for="cash"> Mode of Pay</label>
                <select name="cash" id="cash">
                    <option> Cash</option> 
                    <option> UPI</option>
                    <option> Card</option>

                </select>
               
            </form>
            <h1 style="text-align: center;"> <a href="C:\Users\admin\Desktop\web development\confirm.html"> Continue</a></h1>
            <h1 style="text-align: center;"> For more queries,contact:<br>
                phone:9876543210<br>
                saporidiitalaia78@gmail.com<br>
            </h1>
       
        </body>
</html>

bro.html
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Italian Restaurant</title>
    <link href="rest.css" rel="stylesheet">
</head>
<body>
    <header>
        <div class="logo">
            <img src="logo.png" alt="Logo">
            <h1>Sapori Di Italia</h1>
        </div>
        <nav>
            <a href="booking.html">Book now</a>
            <a href="menu.html">Menu</a>
            <a href="About.html">Admin</a>
            <a href="Contact.html"> Contact us</a>

        </nav>
    </header>

    <div class="hero">
        <h1>40% Off This Weekend</h1>
        <p>Where Taste Meets Luxury.</p>
    </div>

    <div class="cards">
        <div class="card">
            <img src="Screenshot 2025-12-26 133608.png" alt="Our New Menu">
            <h2>Our New Menu</h2>
        </div>
        <div class="card">
            <img src="Dine Restaurant Food - Free photo on Pixabay.jpg"alt="Book a Table">
            <h2>Book a Table</h2>
        </div>
        <div class="card">
            <img src="Ilustração do horário de funcionamento da empresa com foto _ Vetor Grátis.jpg" alt="Opening Hours">
            <h2>Opening Hours</h2>
        </div>
    </div>

    <footer>
        <p> Designed and developed by vignes</p>
        <p>© 2025 Sapori Di Italia. All rights reserved.</p>
    </footer>
</body>
</html>

```
```

content.html

<html>
    <head>
        <style>
            .one{
                text-align: center;
                font-family: 'Times New Roman', Times, serif;
            }
            .image
            {
                text-align: center;
            }
    </style>
    </head>
    <body>
        <div class="image">
    
            <img src="logo.png" alt="Logo">
        
        </div>
        <div class="one">
        <h1 >Contact Us</h1>
        <h2> Address: ITC Grand Chola, 63, Anna Salai, Guindy, Chennai, Tamil Nadu 600032</h2>
        <h2> Phone:9876543210</h2>
        <h2>Email :saporidiitalaia78@gmail.com</h2>
        </div>
    </body>
</html>

admin.css

body{
    margin: 0;
    padding: 0;
}
.layout{
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    grid-template-rows: 1fr 1fr 1fr;
    height: 70%;
    width: 80%;
}
.layout div{
    height: 70%;
    width: 80%;
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-bottom: -15px;

}
img{
    height: 250px;
    width: 250px;
    margin-bottom: -10px;
}
.chefs{
    height:100%;
    display: flex;
    justify-content: center;
    align-items: center;
}
.image
{
    text-align: center;
    width:90%;
}

menu.html

<html>
    <head>
        <title> Menu</title>
        <style>
            body{
                background-image: url('Dine Restaurant Food - Free photo on Pixabay.jpg');
                background-repeat: no-repeat;
                background-size: cover;
            }
            table.center{
                background-color: transparent ;
                color: beige;
                margin-left: auto;
                margin-right: auto;
                font-size: 40px;
                font-family: cursive;
                backdrop-filter: blur(10px);
                border: 1px solid beige;
                padding: 10px;
            } 
        </style>
        </head>
        <body>
           
                <h1 style="text-align: center; color: beige;"> Menu</h1>
                
                
                <table class="center">
                    <tr>
                    <th> S.no</th>
                         <th> Items </th>
                         <th> Price</th>
                        </tr>
                    <tr>
                         <td> 1</td>
                         <td> Margherita</td>
                         <td> 80</td>
                        
                     </tr>\
                     <tr>
                        <td> 2 </td>
                        <td> Pepperoni</td>
                        <td> 220</td>
                    </tr>
                    <tr>
                        <td> 3</td>
                        <td> Lasagna </td>
                        <td> 200</td>
                    </tr>
                    <tr> 
                        <td> 4</td>
                        <td> Mojito</td>
                        <td> 70</td>
                    </tr>
                    <tr>
                        <td> 5</td>
                        <td> Mozarella  Caprese</td>
                        <td> 250</td>
                    </tr>
                    <tr>
                        <td> 6</td>
                        <td> Wings</td>
                        <td> 140</td>
                    </tr>
                    <tr>
                        <td> 7</td> 
                        <td> Fried Calamari </td>
                        <td> 240</td>                       
                    </tr>
                    <tr>
                        <td> 8</td>
                        <td> Spicy Arrabiata</td>
                        <td> 200</td>
                    </tr>
                    <tr>
                        <td> 9</td>
                        <td> Ratatouille</td>
                        <td> 300</td>
                    </tr>
                </table>
                </div>
        </body>
</html>

```
```
rest.css

 body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
        }
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px;
            background-color :white;
            color: rgb(0, 253, 42);
        }
        header .logo {
            display: flex;
            padding-left: 40%;
            align-items: center;
        }
        header .logo img {
            height: 50px;
            margin-right: 10px;
        }
        nav a {
            margin: 0 10px;
            color: rgb(255, 69, 1);
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .hero {
            background: url('back.jpg') center/cover no-repeat;
            color: white;
            text-align: center;
            padding: 100px 20px;
            position: relative;
        }
        .hero h1 {
            font-size: 3rem;
            margin-bottom: 10px;
        }
        .hero p {
            font-size: 1.2rem;
        }
        .cards {
            display: flex;
            justify-content: center;
            gap: 20px;
            padding: 20px;
        }
        .card {
            background-color: #fdf4e3;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            width: 30%;
            text-align: center;
            padding: 20px;
        }
        .card img {
            width: 100%;
            border-radius: 8px;
        }
        .card h2 {
            margin-top: 15px;
            font-size: 1.5rem;
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #ff0000;
            color: white;
        }

```

## OUTPUT:

![alt text](<suriya/restmap/static/Screenshot (24).png>)

![alt text](<suriya/restmap/static/Screenshot (25).png>)

![alt text](<suriya/restmap/static/Screenshot (26).png>)

![alt text](<suriya/restmap/static/Screenshot (27).png>)

![alt text](<suriya/restmap/static/Screenshot (28).png>)

![alt text](<suriya/restmap/static/Screenshot (29).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
