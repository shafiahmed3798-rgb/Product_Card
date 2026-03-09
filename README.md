# Product Card Design with Hover Effect using CSS
## Date:

## AIM:
To design a Product Card for an E-commerce website using HTML and CSS and apply hover effects, transitions, and styling techniques to create an interactive user interface.

## DESIGN STEPS:

### Step 1:
Create a basic HTML structure using ```<!DOCTYPE html>, <html>, <head>, and <body>```.

### Step 2:
Add a container div for the product card.

### Step 3:
Insert the product image using the ```<img>``` tag.

### Step 4:
Add product name, description, and price using ```<h3>``` and ```<p>``` tags.

### Step 5:
Create an Add to Cart button using the ```<button>``` tag.

### Step 6:
Style the product card using CSS by applying:
<ul>
  <li>width</li>
  <li>padding</li>
  <li>border-radius</li>
  <li>box-shadow</li>
</ul>

### Step 7:
Align the card content using text-align and spacing properties.

### Step 8:
Add hover effects using :hover selector.

### Step 9:
Apply transform: translateY() to move the card slightly upward on hover.

### Step 10:
Increase the box-shadow to create a lifting effect.

### Step 11:
Add transform: scale() to slightly zoom the product image on hover.

### Step 12:
Apply transition property to make the hover animation smooth.

### Step 13:
Create a footer section at the bottom of the page.

### Step 14:
Display Learner Name and Register Number inside the footer.

### Step 15:
Style the footer using background color and center alignment.

### Step 10:
Test your webpage in a browser.

## PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Product Card</title>

<style>

body{
    font-family: Arial, sans-serif;
    background:#f4f4f4;
    display:flex;
    flex-direction:column;
    align-items:center;
    min-height:100vh;
    margin:0;
}

/* Product Card */
.product-card{
    width:300px;
    background:white;
    border-radius:15px;
    overflow:hidden;
    text-align:center;
    padding:20px;
    margin-top:80px;
    transition:0.4s;
    box-shadow:0 4px 10px rgba(0,0,0,0.2);
}

/* Hover Effect */
.product-card:hover{
    transform:translateY(-10px);
    box-shadow:0 12px 25px rgba(0,0,0,0.35);
}

/* Image */
.product-image{
    width:100%;
    border-radius:10px;
    transition:0.4s;
}

/* Image Zoom */
.product-card:hover .product-image{
    transform:scale(1.1);
}

/* Product Name */
.product-name{
    font-size:22px;
    margin-top:15px;
}

/* Description */
.product-desc{
    font-size:14px;
    color:#555;
    margin:10px 0;
}

/* Price */
.price{
    font-size:20px;
    color:#db3c0c;
    font-weight:bold;
}

/* Button */
button{
    margin-top:15px;
    padding:10px 20px;
    border:none;
    border-radius:8px;
    background:#0077ff;
    color:white;
    font-size:16px;
    cursor:pointer;
    transition:0.3s;
}

/* Button Hover */
.product-card:hover button{
    background:#0a8dd9;
}

/* Footer */
footer{
    margin-top:auto;
    width:100%;
    text-align:center;
    background:#d0b4b4;
    color:white;
    padding:15px;
}

</style>
</head>

<body>

    <footer>
Learner Name: SHAFI AHMED M S | Register Number: 25014933
</footer>

<div class="product-card">

<img src="image copy.png"class="product-image">

<h2 class="product-name">Smartphone</h2>

<p class="product-desc">
    The iPhone 16 series introduces Camera Control, Apple Intelligence enhancements, larger displays, new colors, and improved durability, with Pro models offering additional performance and screen upgrades
</p>

<p class="price"> 72,000 </p>

<button>Add to Cart</button>

</div>



</body>
</html>
```

## OUTPUT:
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/55472f9b-8f5a-47f8-b6ec-d6305fcd53d3" />

## RESULT:
The Product Card with Hover Effect was successfully designed using HTML and CSS.
