# Ex02 Commercial Website
## Date: 28.07.2026

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
```
###INDEX.HTML:
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ShopEasy</title>
<link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <div class="logo">🛍 ShopEasy</div>

    <nav>
        <a href="#">Home</a>
        <a href="#">Products</a>
        <a href="#">Offers</a>
        <a href="#">Contact</a>
    </nav>
</header>

<section class="banner">
    <h1>Big Sale 50% OFF</h1>
    <p>Latest Fashion, Electronics & Accessories</p>
    <a href="#" class="btn">Shop Now</a>
</section>

<section class="products">

    <h2>Featured Products</h2>

    <div class="container">

        <div class="card">
            <img src="https://images.unsplash.com/photo-1542291026-7eec264c27ff?w=400" alt="Shoes">
            <h3>Nike Shoes</h3>
            <p>₹2,499</p>
            <button>Buy Now</button>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1511707171634-5f897ff02aa9?w=400" alt="Phone">
            <h3>Smart Phone</h3>
            <p>₹24,999</p>
            <button>Buy Now</button>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1505740420928-5e560c06d30e?w=400" alt="Headphones">
            <h3>Headphones</h3>
            <p>₹1,999</p>
            <button>Buy Now</button>
        </div>

    </div>

</section>

<footer>
    <p>© 2026 ShopEasy | All Rights Reserved</p>
</footer>

</body>
</html>
```
```
### STYLE.CSS
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial,sans-serif;
}

body{
    background:#f5f5f5;
}

header{
    background:#222;
    color:#fff;
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:15px 50px;
}

.logo{
    font-size:28px;
    font-weight:bold;
}

nav a{
    color:white;
    text-decoration:none;
    margin-left:20px;
    font-size:18px;
}

nav a:hover{
    color:orange;
}

.banner{
    height:400px;
    background:url("https://images.unsplash.com/photo-1523381210434-271e8be1f52b?w=1600") center/cover;
    color:white;
    text-align:center;
    padding-top:120px;
}

.banner h1{
    font-size:50px;
}

.banner p{
    font-size:22px;
    margin:20px 0;
}

.btn{
    background:orange;
    color:white;
    padding:15px 35px;
    text-decoration:none;
    border-radius:5px;
    font-size:20px;
}

.products{
    padding:50px;
}

.products h2{
    text-align:center;
    margin-bottom:40px;
    font-size:35px;
}

.container{
    display:flex;
    justify-content:center;
    gap:30px;
    flex-wrap:wrap;
}

.card{
    width:280px;
    background:white;
    border-radius:10px;
    overflow:hidden;
    text-align:center;
    box-shadow:0 5px 10px rgba(0,0,0,0.2);
}

.card img{
    width:100%;
    height:220px;
    object-fit:cover;
}

.card h3{
    margin:15px 0;
}

.card p{
    color:green;
    font-size:22px;
    font-weight:bold;
}

.card button{
    margin:20px;
    padding:10px 30px;
    background:#007BFF;
    color:white;
    border:none;
    border-radius:5px;
    cursor:pointer;
}

.card button:hover{
    background:#0056b3;
}

footer{
    background:#222;
    color:white;
    text-align:center;
    padding:20px;
    margin-top:40px;
}
```
 
## OUTPUT
<img width="1920" height="1200" alt="Screenshot 2026-07-28 154314" src="https://github.com/user-attachments/assets/29908ae2-4dac-4a90-a35c-11f19342ea12" />
<img width="1920" height="1200" alt="Screenshot 2026-07-28 154329" src="https://github.com/user-attachments/assets/764387b3-fc79-48e8-acca-8ff82dad85a7" />



## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
