# Ex.07 Restaurant Website
## Date:02.01.2025

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
food.html
<html>
    <head>
        <title>BITE BLISS</title>
    </head>
    <style>
    body{
        background-image: url(foodpp.jpg);
        background-size: cover;
        background-color:wheat;
        background-position:center;
        background-blend-mode: color;
        
    }
    </style>
    <ul class="menu-items">
        <li><a href="#HOME">HOME</a></li><br>
        <li><a href="#menu">MENU</a></li>
    </ul>

        <center><h1> BITE BLISS</h1></center>
        <center><P>SAVOR THE FLAVOR,SAVOR THE MOMENT</P></center>
        <hr>
        <center><p style="font-size: medium;font-style: italic;font-weight: bold;">Welcome to Bite Bliss resturant,Where the art of fine dining meets the warmth of a home-cooked meal. Our chefs are inspired by the
             freshest ingredients and the richest flavours from around the world, crafting dishes that are both fimiliar and innovative. From the crackle of
             our wood-fired oven to the sparkle of our expertly curated wine list, every detail is designed to transport you to a place of comfort and joy.
             Whether you're gathering with friends, celebrating a special occasions, or simply savoring a quiet night out,our resturant is your HEAVEN.come,let us
            feed your body and nourish your soul.</p></center>
        <p style="font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;"style="font-size:medium"><h3><center>
        <table>
            <tr>
                <td><img src="CHICKEN POPCORN.jpg" width="200" height="200"></td>
                <td><img src="PIZZA.jpg" width="200" height="200"></td>
                <td><img src="cheese pasta.jpg" width="200" height="200"></td>
            </tr>
            <tr>
                <td><h3><center>CHICKEN POPCORN<br>Price:299</center></h3></td>
                <td><h3><center>PIZZA<br>Price:199</center></h3></td>
                <td><h3><center>CHEESE PASTA<br>Price:249</center></h3></td>
            </tr>
        <center>
            <tr>
                <center>INDULGE IN THE ART OF FINE DINING✔</center><br>
            </tr>
        </center>
            <h2><center>100+ DISHES ARE AVAILABLE</center></h2>
            <h2><center>OPENING OFFER 50% Discount</center></h2>
            <hr>
            <h3>FIND IT!EAT IT!
            </h3>
        </table>
        <hr>
        <section id="menu">
            <a href="C:\Users\Janani S\restweb\menu.html">FOR MORE MENU</a>
        </section>



        <br>
        <section id="click here">
            <div class="form-container">
                <a href="C:\Users\Janani S\restweb\food inform.html">ORDER</a>
            </div>
        </section>
menu.html
<html>
    <head>
        <title>FOOD MENU</title>
        <Center>
            <hr>
            <hr>
            <h1>
            <caption>BITE BLISS</caption><br>
            </h1>
            <h2> FOOD MENU</h2>
        </Center>
            <hr>
            <hr><br>
            <center>
            <h1>SAMOSA<br>
            <img src="samosa.jpg" width="200" height="200">
            <br>PRICE:32</h1><br><hr>
            <h1>BREAD OMELETTE<br>
            <img src="bread oml.jpg" width="200" height="200">
            <br>PRICE:60</h1><br><hr>
            <h1>CHICKEN PUFFS<br>
            <img src="c puffs.jpg" width="200" height="200">
            <br>PRICE:30</h1><br><hr>
            <h1> VEG PUFFS<br>
            <img src="v puffs.jpg" width="200" height="200">
            <br>PRICE:25</h1><br><hr>
            <h1>COFFEE<br>
            <img src="coffee.jpg" width="200" height="200">
            <br>PRICE:30</h1><br><hr>
            <h1>FETTUCCINE ALFEREDO:<br>
            <img src="a f.jpg" width="200" height="200">
            <br>PRICE:239</h1><br><hr>
            <h1>MASALA PURI<br>
            <img src="masala puri.jpg" width="200" height="200"><br>
            <br>PRICE:45</h1><br><hr>
            <h1>PANI PURI<br>
            <img src="pani puri.jpg" width-="200" height="120">
            <br>PRICE:50</h1><br><hr>
            <h1>GOBI 65<br>
            <img src="gobi 65.jpg" width="200" height="200">
            <br>PRICE:60</h1>
            </center>
         </head>
         <body style="background-color:darkgrey;">
            <style>
                h1,h2{
                    font-family:Georgia, 'Times New Roman', Times, serif ;
                    font-size:x-large ;
                    font-style:bold;
                    color:black;
                }
            </style>
</html>
food inform.html
<html>
<head>
    <title>Ordered People's Information</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        .form-container {
            max-width: 400px;
            margin: 0 auto;
            padding: 20px;
            border: 1px solid #ccc;
            border-radius: 10px;
            background-color: #f9f9f9;
        }
        label {
            display: block;
            margin-bottom: 10px;
        }
        input, select {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        button {
            padding: 10px 20px;
            background-color: #28a745;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #218838;
        }
    </style>
</head>
<body>
    <center>

    <h1>Ordered People's Information</h1>

    </center>

    <div class="form-container">
        <form action="submit_form.php" method="POST">
            <label for="name">Full Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter full name" required>

            <label for="food type">food type:</label>
            <input type="number" id="food" name="food" placeholder="Enter food" required>

            <label for="address">Address:</label>
            <input type="text" id="address" name="address" placeholder="Enter address" required>

            <label for="Quantity">Quantity:</label>
            <select id="Quantity" name="Quantity" required>
                <option value="One">One</option>
                <option value="Two">Two</option>
                <option value="Three">Three></option>
            </select>

            <label for="comments">Additional Comments about food:</label>
            <textarea id="comments" name="comments" placeholder="Enter any additional comments" rows="4"></textarea>

            <button type="submit">Submit</button>
        </form>
    </div>

</body>
</html>

```

## OUTPUT:
HOME
![alt text](<Screenshot 2025-01-02 202532.png>)

MENU
![alt text](<Screenshot 2025-01-02 202643.png>)
![alt text](<Screenshot 2025-01-02 202701.png>)
![alt text](<Screenshot 2025-01-02 202714.png>)

CONTACT
![alt text](<Screenshot 2025-01-02 202745.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
