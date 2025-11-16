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
home.html

<html>
<head>
    <link href="design.css" rel="stylesheet">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">        
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js">
    </script>
  
  <title>INDIAN CUISINE</title>
  <style>
    
    .navi
    {
        font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;

    }

    .banner {
      background-image: url("food.avif"); 
      background-size: cover;
      background-position: center;
      height: 250px;
      position: relative;
      display: flex;
      align-items: center;
      justify-content: center;
      color: rgb(241, 238, 238);
      text-shadow: 2px 2px 6px rgba(0, 0, 0, 0.7);
      word-spacing: 30;
    }

    .banner h1 {

      font-family:cursive;
      font-size: 60px;
      margin: 0;
      font-weight: bold;
    }
    .box-section {
  display: flex;
  flex-direction: row;     
  justify-content: flex-start;
  gap: 50px;               
  margin-top: 40px;       
  margin-left: 40px;   
  margin-right: 40px;   
}

.info-box {
  background-color:rgb(100, 86, 94);
  color: whitesmoke;
  width: 800px;
  height: 410px;
  display: flex;
  font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
  border-radius: 10px;
  font-size: 20px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
  
}
.menu-content h3 {
  margin-left: 50;
  font-size: 20px;
  margin-bottom: 4px;

}
.menu-content h2 {
  margin-left: 50;
  font-size: 20px;
  margin: top 2px;
  font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;

}


.menu-content p {
  margin-left: 50;
  font-size: 15px;
  margin-bottom: 10px;
  font-weight: normal;
}
.image
{
  margin-left: 60;
 
}
  </style>
</head>
<body>
    <div class="navi">
    <nav class="navbar navbar-expand-sm bg-dark">
            <ul class="navbar-nav">
                <li class="nav-item bg-dark mx-3">
                    <a class="nav-link text-white" href="home.html">HOME</a>
                </li>
                <li class="nav-item bg-dark mx-3">
                    <a class="nav-link text-white" href="menu.html">MENU</a>

                </li>
                <li class="nav-item bg-dark mx-3">
                    <a class="nav-link text-white" href="team.html">ADMINISTRATION</a>
                </li>
                <li class="nav-item bg-dark mx-3">
                    <a class="nav-link text-white" href="contact.html">CONTACT US</a>
                </li>

            </ul>
        </nav>
    </div>

  <div class="banner">
    <h1>THE INDIAN ESSENCE</h1> 
  </div>
  
    <div class="box-section">
        <div class="info-box">
          <div class="menu-content">
            <center>
              <h2 ">Our New Menu:</h2>
                
              <img class="image" src="tofu-tikka-masala.webp" height="200" width="200">
                <br>

              <h3 style="margin-top: 4;">*   TOFU TIKKA MASALA</h3>
              <p>A INDIAN FUSION OF TOFU WITH MOUTH WATERING MASALA</p>

              <h3 style="margin-top: 4;">*  MALAI PANEER  </h3>
              <p>A CREAMY ,WHITE CURRY MADE WITH PANEER CHEESE</p>
            </center>
          </div>
        </div>
          
          
        <div class="info-box">
          <div class="menu-content">
            <center>
              <h2 style="margin-left: 50 ;">Book Your Table:</h2>
              <img class="image" src="tables.jpeg" width="225" height="225" style="margin-left: 70;">
              <br>
              <h3 style="margin-top: 9;margin-left: 70;">  Book your seats online now !!</h3>
              <p style="margin-top: 9;margin-left: 70;">Have a great time with your family and friends..</p>
              <p style="margin-top: 9;margin-left: 70;">Book your table atleast before 1 day at our website</p>
            </center>
          </div>
        </div>
        <div class="info-box">
          <div class="menu-content">
            <center>
              <h2 style="margin-left:100;">Opening Hours :</h2>
              <img class="image" src="images.jpeg" width="225" height="225" style="margin-left: 100;">
              <br>
             
              <h3 style="margin-top: 9;margin-left: 90;">  Opens at !!</h3>
              <p style="margin-top: 9;margin-left: 90;">Day : Monday - Sunday</p>
              <p style="margin-top: 9;margin-left: 90;">Timings : 1:00am to 11:00pm </p>

            </center>
          </div>
        </div>
        
        
      </div>
    
</body>
<footer style="background-color:rgba(6, 8, 5, 0.581);height: 150;width: 1600px;color: white;text-align: center;font-family: cursive;font-size: 5;margin-top:30;">
    <h2 style="font-size:medium; margin-top: 4;">IndianCEmail@gmail.com </h2> <h2 style="font-size:medium;">📞Contact number : +91 6369869924</h2><br>
    <h2 style="font-size:medium;">Address  : No 8, Ghandhi street ,Anna nagar ,Chennai</h2>
    <br>
    <h2 style="font-size:medium;">----------❤️DEVELOPED BY MADHUMITHA B❤️--------- </h2>
</footer>

</html>

menu.html

<html>
<head>
    <link href="design.css" rel="stylesheet">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">        
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js">
    </script>
  
  <title>Indian Cuisine</title>
  <style>
    .navi {
        font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    }
    
    .menu-section {
      background-color: #db9a44;
      padding: 30px;
      color: #fff;
      text-align: center;
      font-family: 'times new roman';
      font-weight: bold;
    }

    .menu-title {
      color: white;
      font-size: 32px;
      margin-bottom: 30px;
      font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
      font-weight: bold;
    }

    .menu-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
      justify-items: center;
    }

    .menu-card {
      background-color: white;
      color: black;
      border-radius: 8px;
      overflow: hidden;
      width: 200px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.3);
      text-align: center;
      border: 1px solid #D4AF37;
    }

    .menu-card img {
      width: 100%;
      height: 150px;
      object-fit: cover;
    }

    .menu-card h3 {
      font-size: 18px;
      margin: 10px 0 5px;
      color: #8B0000;
    }

    .menu-card p {
      font-size: 14px;
      padding: 0 10px 10px;
    }
  </style>
</head>
<body>
    <div class="navi">
    <nav class="navbar navbar-expand-sm bg-dark">
            <ul class="navbar-nav">
                <li class="nav-item bg-dark mx-3">
                    <a class="nav-link text-white" href="home.html">HOME</a>
                </li>
                <li class="nav-item bg-dark mx-3">
                    <a class="nav-link text-white" href="menu.html">MENU</a>
                </li>
                <li class="nav-item bg-dark mx-3">
                    <a class="nav-link text-white" href="team.html">Golden Pagodas TEAM</a>
                </li>
                <li class="nav-item bg-dark mx-3">
                    <a class="nav-link text-white" href="contact.html">CONTACT US</a>
                </li>
            </ul>
        </nav>
    </div>
    
    <div class="menu-section">
      <h2 class="menu-title">Flavors Of India</h2>
      <div class="menu-grid">
        <div class="menu-card">
          <img src="mutton.jpeg" alt="mutton"><br><br>
          <h3>Madurai Mutton Chukka</h3>
          <p>Boneless mutton pieces slow-cooked with dry-roasted spices and shallots. Dry, spicy, and packed with intense flavor.

</p>
        </div>
        <div class="menu-card">
          <img src="chenna poda.jpeg" alt="Sweet  Savoury"><br><br>
          <h3>Chhena Poda </h3>
          <p>A sweet made by baking fresh cottage cheese mixed with sugar, cardamom, and semolina. It's caramelized and has a smoky flavor.</p>
        </div>
        <div class="menu-card">
          <img src="Bhutte Ka Kees.jpeg" alt="Snack"><br><br>
          <h3>Bhutte Ka Kees</h3>
          <p>A spicy street snack made from grated corn cooked with milk, spices, and ghee. Creamy and flavorful with a slight crunch.</p>
        </div>
        <div class="menu-card">
          <img src="Kongunadu Chicken Fry.jpeg" alt="Chicken"><br><br>
          <h3>Kongunadu Chicken Fry</h3>
          <p>A dry-style chicken dish from the Kongu region, flavored with freshly ground spices, black pepper, and coconut. Known for its bold, earthy taste.</p>
        </div>
        <div class="menu-card">
          <img src="Machha Chadchadi.jpeg" alt="Fish"><br><br>
          <h3>Machha Chadchadi</h3>
          <p>Freshwater fish cooked in a mustard seed and garlic paste with turmeric and raw banana or potato. Pungent and tangy, served with rice.</p>
        </div>
        <div class="menu-card">
          <img src="chicken-kassa-1.jpg" alt="Chiken"><br><br>
          <h3>Chicken kassa</h3>
          <p>A dry-style chicken curry where the meat is slow-cooked with a masala of onions, garlic, ginger, and roasted spices until the oil separates. It's bold, earthy, and slightly smoky, often enjoyed with roti or rice.</p>
        </div>
        <div class="menu-card">
          <img src="laal-maas-1.webp" alt="Mutton"><br><br>
          <h3>Laal Mass</h3>
          <p>A fiery red mutton curry made with dried mathania chilies and yogurt. It's bold, spicy, and full of rustic flavors.</p>
        </div>
        <div class="menu-card">
          <img src="final-bebica-output-1.webp" alt="Dessert"><br><br>
          <h3>Bebinca</h3>
          <p>A traditional Goan layered dessert made with coconut milk, eggs, sugar, and flour. It's rich, dense, and slightly caramelized.</p>
        </div>
        <div class="menu-card">
          <img src="images (1).jpeg" alt="Dessert"><br><br>
          <h3>Sandesh with Nolen Gur</h3>
          <p>Soft paneer-based sweet infused with date palm jaggery (nolen gur).</p>
        </div>
        <div class="menu-card">
          <img src="Aam Panna.jpeg" alt="Refresher"><br><br>
          <h3>Aam Panna</h3>
          <p>A tangy summer cooler made from raw mango pulp, black salt, and mint. Known to fight heatstroke and refresh instantly.</p>
        </div>
        <div class="menu-card">
          <img src="Lemon Jaljeera.jpeg" alt="Refresher"><br><br>
          <h3>Lemon Jaljeera </h3>
          <p>A tangy drink made with lemon juice and jaljeera powder (cumin, black salt, mint). Served cold to beat the heat and boost digestion.</p>
        </div>
        <div class="menu-card">
          <img src="Kokum Sharbat.jpg" alt="Refresher"><br><br>

        <h3>Kokum Sharbat </h3>
          <p>A tangy, sweet drink made from kokum fruit pulp, cumin, and sugar.</p>
        </div>
      </div>
    </div>
</body>
<footer style="background-color:#333;height:150px;width:100%;color:white;text-align:center;font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;font-size:5px;margin-top:30px;">
    <h2 style="font-size:medium; margin-top:4px;">Email :IndianCEmail@gmail.com </h2>
    <h2 style="font-size:medium;">Contact number : +91 6369869924</h2><br>
    <h2 style="font-size:medium;">Address:Address  : No 8, Ghandhi street ,Anna nagar ,Chennai </h2>
    <br>
    <h2 style="font-size:medium;">----------Where Every Region Tells A Story ----------</h2>
</footer>
</html>

team.html

<html>
<head>
    <link href="design.css" rel="stylesheet">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">        
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js">
    </script>
  
  <title>Golden Pagodas Team - Siju Minfu Chinese Restaurant</title>
  <style>
    .navi {
        font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    }
    
    .menu-section {
      background-color: #ac5600;
      padding: 30px;
      color: #fff;
      text-align: center;
      font-family: 'times new roman';
      font-weight: bold;
      
    }

    .menu-title {
      color: white;
      font-size: 32px;
      margin-bottom: 30px;
      font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
      font-weight: bold;
    }

    .menu-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
      justify-items: center;
    }

    .menu-card {
      background-color: white;
      color: black;
      border-radius: 8px;
      overflow: hidden;
      width: 200px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.3);
      text-align: center;
      border: 1px solid #D4AF37;
    }

    .menu-card img {
      width: 100%;
      height: 250px;
      object-fit: cover;
    }

    .menu-card h3 {
      font-size: 18px;
      margin: 10px 0 5px;
      
      color: #8B0000;
    }

    .menu-card p {
      font-size: 14px;
      padding: 0 10px 10px;
    }
  </style>
</head>
<body>
    <div class="navi">
    <nav class="navbar navbar-expand-sm bg-dark">
            <ul class="navbar-nav">
                <li class="nav-item bg-dark mx-3">
                    <a class="nav-link text-white" href="home.html">HOME</a>
                </li>
                <li class="nav-item bg-dark mx-3">
                    <a class="nav-link text-white" href="menu.html">MENU</a>
                </li>
                <li class="nav-item bg-dark mx-3">
                    <a class="nav-link text-white" href="team.html">Golden Pagodas Team</a>
                </li>
                <li class="nav-item bg-dark mx-3">
                    <a class="nav-link text-white" href="contact.html">CONTACT US</a>
                </li>
            </ul>
        </nav>
    </div>
    
    <div class="menu-section">
      <h2 class="menu-title">TOP CHEF</h2>
      <div class="menu-grid">
        <div class="menu-card">
          <img src="Sanjeev Kapoor.jpeg" alt="Tanjiro">
          <h3>Sanjeev Kapoor</h3>
          <p>A well-known face on Indian television, Sanjeev Kapoor is a celebrity chef and entrepreneur whose recipes are loved across the country.</p>
        </div>
        <div class="menu-card">
          <img src="Vikas Khanna.jpeg" alt="Nezuko">
          <h3>Vikas Khanna</h3>
          <p>Vikas Khanna is an Indian-American Michelin star celebrity chef, restaurateur and cookbook writer. He is one of the judges of MasterChef India since its beginning.</p>
        </div>
        <div class="menu-card">
          <img src="Garima Arora.jpeg" alt="Zenitsu">
          <h3>Garima Arora</h3>
          <p>Garima Arora is the first Indian woman to receive a Michelin star. She's also a MasterChef India judge. </p>
        </div>
        <div class="menu-card">
          <img src="Manish Mehrotra.jpeg" alt="Inosuke">
          <h3>Manish Mehrotra</h3>
          <p>A prominent figure in Indian cuisine, including South Indian flavors, and recognized as one of the top 20 chefs in India</p>
        </div>
        <div class="menu-card">
          <img src="Padma Lakshmi.jpeg" alt="Shinobu">
          <h3>Padma Lakshmi</h3>
          <p>Padma Lakshmi is a globally recognized South Indian chef, known for her work on "Top Chef" and the Hulu show "Taste the Nation." She's also a successful cookbook author and food writer.</p>
        </div>
        <div class="menu-card">
          <img src="Mythrayie Iyer.jpeg" alt="Giyu">
          <h3>Mythrayie Iyer</h3>
          <p>Mythrayie S Iyer is the head chef at Farmlore, a restaurant known for its cuisine-agnostic approach.</p>
        </div>
      </div>
    </div>
</body>
<footer style="background-color:#333;height:150px;width:100%;color:white;text-align:center;font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;font-size:5px;margin-top:30px;">
   <br> <h2 style="font-size:medium; margin-top:4px;">Email : IndianCEmail@gmail.com</h2>
    <h2 style="font-size:medium;">📞Contact number :+91 6369869924</h2><br>
    <h2 style="font-size:medium;">Address: No 8, Ghandhi street ,Anna nagar ,Chennai</h2>
    <br>
    <h2 style="font-size:medium;">----------Where Every Region Tells A Story ----------</h2>
</footer>
</html>

contact.html

<html>
<head>
    <link href="design.css" rel="stylesheet">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">        
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js">
    </script>
  
    <title>Contact Us -THE INDIAN ESSENCE</title>
    <style>
    .navi {
        font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    }
    
    body {
        background-image: url("bg.avif");
        background-size: cover;
    }
    
    .contact-section h1 {
        font-size: 32px;
        color: #f0e7e7;
        margin-bottom: 30px;
        text-align: center;
        font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
      font-weight: bold;
    }

    .contact-box {
        background-color: #167e79;
        color: white;
        padding: 20px;
        margin: 0 auto;
        width: 700px;
        border-radius: 10px;
        box-shadow: 0 4px 8px rgba(0,0,0,0.3);
        margin-top: 50px;
        border: 2px solid #D4AF37;
    }

    .contact-box p {
        font-size: 16px;
        margin: 10px 0;
        margin-top: 20px;
    }
    </style>
</head>
<body>
    <div class="navi">
    <nav class="navbar navbar-expand-sm bg-dark">
            <ul class="navbar-nav">
                <li class="nav-item bg-dark mx-3">
                    <a class="nav-link text-white" href="home.html">HOME</a>
                </li>
                <li class="nav-item bg-dark mx-3">
                    <a class="nav-link text-white" href="menu.html">MENU</a>
                </li>
                <li class="nav-item bg-dark mx-3">
                    <a class="nav-link text-white" href="team.html"> TOP CHEF</a>
                </li>
                <li class="nav-item bg-dark mx-3">
                    <a class="nav-link text-white" href="contact.html">CONTACT US</a>
                </li>
            </ul>
        </nav>
    </div>
    
    <div class="contact-section">
        <br><br>
        <h1>CONTACT US</h1>
        <div class="contact-box">
            <p><strong>Restaurant:</strong> THE INDIAN ESSENCE</p>
            <p><strong>Address:</strong> </p>
            <p><strong>Phone:</strong> +91 6369869924</p>
            <p><strong>Email:</strong> IndianCEmail@gmail.com</p>
            <p><strong>Reservations:</strong> Recommended for dinner service</p>
        </div>
    </div>
</body>
<footer style="background-color:#333;height:150px;width:100%;color:white;text-align:center;font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;font-size:5px;margin-top:30px;">
   <br><br> <h2 style="font-size:medium; margin-top:4px;">Email : IndianCEmail@gmail.com</h2>
    <h2 style="font-size:medium;">📞Contact number :+91 6369869924</h2><br>
    <h2 style="font-size:medium;">Address: Address: No 8, Ghandhi street ,Anna nagar ,Chennai</h2>
    <br>
    <h2 style="font-size:medium;">----------❤️DEVELOPED BY MADHUMITHA B❤️----------</h2>
</footer>
</html>

```
## OUTPUT:

<img width="1044" height="584" alt="Screenshot 2025-11-16 151108" src="https://github.com/user-attachments/assets/aef69aee-a911-4722-8e74-01d51c692e5b" />

<img width="1036" height="602" alt="Screenshot 2025-11-16 151117" src="https://github.com/user-attachments/assets/7a010db5-18b9-477c-ba09-e990ce8712a8" />

<img width="1038" height="597" alt="Screenshot 2025-11-16 151124" src="https://github.com/user-attachments/assets/4debd4df-af46-4677-8b74-6e463a9fc0a1" />

<img width="1031" height="587" alt="Screenshot 2025-11-16 151131" src="https://github.com/user-attachments/assets/b1d73555-1aa5-435d-a5a2-cfb718ba50fa" />


CONTACT
![alt text](<Screenshot 2025-01-02 202745.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
