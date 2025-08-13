# Ex02 Commercial Website
## Date:13-08-2025
# Reg no:212223040043
# Name:DIVYA M

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM

#commercial web.html

```
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>EASY CART</title>

    <link rel="stylesheet" href="Ccomweb.css">

  <style>
    body { font-family: Arial; margin: 0; }
    header { background: #333; color: white; padding: 10px; text-align: center; }
    nav { background: #555; display: flex; justify-content: center; }
    nav a { color: white; padding: 10px 15px; text-decoration: none; }
    nav a:hover { background: #777; }
    .products { display: flex; flex-wrap: wrap; gap: 10px; padding: 10px; }
    .card { background: #f9f9f9; padding: 10px; flex: 1 1 200px; text-align: center; border: 1px solid #ccc; }
    img { max-width: 100%; height: auto; }
    footer { background: #333; color: white; text-align: center; padding: 10px; }
  </style>
</head>
<body>

<header>
  <h1>EASY CART</h1>
</header>

<nav>
  <h2 style="color: whitesmoke; padding: 10px;">Mobiles</h2>
    <h2 style="color: whitesmoke; padding: 10px;">Electronics</h2>
  <h2 style="color: whitesmoke; padding: 10px;">Appliances</h2>



</nav>

<section id="mobiles">

  <h2 style="padding:10px;">Mobiles</h2>
  <div class="products">
    <div class="card"><img src="smartphone.png"><h3>Smartphone X</h3><p>₹20,000</p> <button class="add-cart">Add to Cart</button></div>

    <div class="card"><img src="budget.png"><h3>Budget Phone</h3><p>₹10,000</p><button class="add-cart">Add to Cart</button></div>
    <div class="card"><img src="5gpro.png"><h3>Pro 5G</h3><p>₹28,000</p><button class="add-cart">Add to Cart</button></div>
    <div class="card"><img src="lite edition.png"><h3>Lite Edition</h3><p>₹8,500</p><button class="add-cart">Add to Cart</button></div>
  </div>
</section>

<section id="electronics">
  <h2 style="padding:10px;">Electronics</h2>
  <div class="products">
    <div class="card"><img src="laptop pro.png"><h3>Laptop Pro</h3><p>₹50,000</p><button class="add-cart">Add to Cart</button></div>
    <div class="card"><img src="headphones.png"><h3>Headphones</h3><p>₹3,000</p><button class="add-cart">Add to Cart</button></div>
    <div class="card"><img src="dslr camera.png"><h3>DSLR Camera</h3><p>₹45,000</p><button class="add-cart">Add to Cart</button></div>
    <div class="card"><img src="smartwatch.png"><h3>Smart Watch</h3><p>₹5,000</p><button class="add-cart">Add to Cart</button></div>
  </div>
</section>

<section id="appliances">
  <h2 style="padding:10px;">Home Appliances</h2>
  <div class="products">
    <div class="card"><img src="fridge.png"><h3>Refrigerator</h3><p>₹25,000</p><button class="add-cart">Add to Cart</button></div>
    <div class="card"><img src="washing meachine.png"><h3>Washing Machine</h3><p>₹15,000</p><button class="add-cart">Add to Cart</button></div>
    <div class="card"><img src="micro.png"><h3>Microwave Oven</h3><p>₹7,500</p><button class="add-cart">Add to Cart</button></div>
    <div class="card"><img src="ac.png"><h3>Air Conditioner</h3><p>₹32,000</p><button class="add-cart">Add to Cart</button></div>
  </div>
</section>


<section id="contact">

    <h2>Contact</h2>
        <h2 style="color: black; padding: 15px;">Email: divya.m@example.com</h2>
                <h2 style="color: black; padding: 15px;">Address: Chennai, India</h2>

                        <h2 style="color: black; padding: 15px;">Phone: +91-9876543210</h2>



</section>


<footer>
  DIVYA M 212223040043
  <p>&copy; 2025 EASY CART. All rights reserved.</p>
</footer>

</body>
</html>
```
#Ccomweb.css
```
body { 
    font-family: Arial; 
    margin: 0; 
}

header { 
    background: #333; 
    color: white; 
    padding: 10px; 
    text-align: center; 
}

nav { 
    background: #555; 
    display: flex; 
    justify-content: center; 
}

nav a { 
    color: white; 
    padding: 10px 15px; 
    text-decoration: none; 
}

nav a:hover { 
    background: #777; 
}

.products { 
    display: flex; 
    flex-wrap: wrap; 
    gap: 10px; 
    padding: 10px; 
}

.card { 
    background: #f9f9f9; 
    padding: 10px; 
    flex: 1 1 200px; 
    text-align: center; 
    border: 1px solid #ccc; 
}

img { 
    max-width: 100%; 
    height: auto; 
}

footer { 
    background: #333; 
    color: white; 
    text-align: center; 
    padding: 10px; 
}
```
```

## OUTPUT
<img width="1920" height="1080" alt="Screenshot (926)" src="https://github.com/user-attachments/assets/e333819c-b971-4178-859d-f3cff72fca4f" />
<img width="1920" height="1080" alt="Screenshot (927)" src="https://github.com/user-attachments/assets/30dfeb13-c804-449b-b7b1-859b5d091042" />

<img width="1920" height="1080" alt="Screenshot (928)" src="https://github.com/user-attachments/assets/5a09243f-7fe3-4a37-b9e2-8a60a96d2641" />

## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
