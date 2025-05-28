# Ex02 Commercial Website
## Date:

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

#### index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>FlexCommerce</title>
  <link rel="stylesheet" href="style.css" />
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />
</head>
<body>

  <!-- Header -->
  <header>
    <div class="logo">FlexCommerce</div>
    <nav>
      <ul class="nav-links">
        <li><a href="#home">Home</a></li>
        <li><a href="#products">Products</a></li>
        <li><a href="#about">About Us</a></li>
        <li><a href="#contact">Contact</a></li>
        <li><a href="#account">Account</a></li>
      </ul>
    </nav>
  </header>

  <!-- Home Section -->
  <section class="home" id="home">
    <div class="home-content">
      <h1>Welcome to FlexCommerce</h1>
      <p>Your Next Favorite Gadget Awaits</p>
      <p>Quality, performance, and style — all in one place.</p>
      <p>Your one-stop solution for quality products and services.</p>
      <a href="#products" class="btn">Shop Now</a>
    </div>
  </section>

    <!-- Products Section -->
    <section class="products" id="products">
    <h2>Our Products</h2>
    <div class="product-container">

      <!-- Smartwatch -->
      <div class="product-card">
        <img src="C:\Users\thula\OneDrive\Documents\website\images\smart.png" alt="Smartwatch" />
        <h3>Smartwatch</h3>
        <p>Stay connected and healthy with our latest smartwatch.</p>
        <button>Add to Cart</button>
        <a href="smartwatch.html" class="see-details-btn">See Details</a>
      </div>

      <!-- Wireless Earbuds -->
      <div class="product-card">
        <img src="C:\Users\thula\OneDrive\Documents\website\images\earbuds.png" alt="Wireless Earbuds" />
        <h3>Wireless Earbuds</h3>
        <p>Experience true wireless freedom and premium sound.</p>
        <button>Add to Cart</button>
        <a href="earbuds.html" class="see-details-btn">See Details</a>
      </div>

      <!-- Portable Charger -->
      <div class="product-card">
        <img src="C:\Users\thula\OneDrive\Documents\website\images\power.png" alt="Portable Charger" />
        <h3>Portable Charger</h3>
        <p>Charge anywhere with our high-capacity portable charger.</p>
        <button>Add to Cart</button>
        <a href="charger.html" class="see-details-btn">See Details</a>
      </div>

      <!-- Bluetooth Speaker -->
      <div class="product-card">
        <img src="C:\Users\thula\OneDrive\Documents\website\images\bluetooth.png" alt="Bluetooth Speaker" />
        <h3>Bluetooth Speaker</h3>
        <p>Powerful sound with compact design. Take it anywhere.</p>
        <button>Add to Cart</button>
        <a href="speaker.html" class="see-details-btn">See Details</a>
      </div>

      <!-- Mini Drone -->
      <div class="product-card">
        <img src="C:\Users\thula\OneDrive\Documents\website\images\drone.png" alt="Mini Drone" />
        <h3>Mini Drone</h3>
        <p>Capture amazing aerial shots with our mini drone.</p>
        <button>Add to Cart</button>
        <a href="drone.html" class="see-details-btn">See Details</a>
      </div>
  </section>



  <!-- About Section -->
  <section class="about" id="about" style="background-color: #1e1e1e; color: #ffffff; padding: 40px 20px; text-align: center;">
    <h2 style="color: #ffcc00;">About Us</h2>
    <p style="max-width: 800px; margin: 20px auto;">
      Welcome to <strong>FlexCommerce</strong> — your trusted destination for modern gadgets and innovative electronics. 
      Founded with a vision to deliver cutting-edge technology at your fingertips, we strive to create a seamless shopping experience that combines convenience, quality, and affordability.
    </p>
    <p style="max-width: 800px; margin: 20px auto;">
      Our mission is to empower everyday users by offering top-rated products that blend functionality and style. Whether it's smartwatches, wireless earbuds, power banks, or drones — 
      we bring you the latest tech innovations at unbeatable prices.
    </p>
    <p style="max-width: 800px; margin: 20px auto;">
      We believe in putting the customer first. That’s why our dedicated support team is always ready to assist, and our fast, reliable delivery ensures your products arrive quickly and securely.
    </p>
    <p style="max-width: 800px; margin: 20px auto;">
      <strong>Why choose FlexCommerce?</strong>
      <ul style="list-style: disc; text-align: left; max-width: 700px; margin: 20px auto; padding-left: 20px;">
        <li>Wide range of tech gadgets and accessories</li>
        <li>Handpicked quality and tested products</li>
        <li>Secure payments and easy returns</li>
        <li>Excellent customer support</li>
        <li>Trusted by thousands of happy customers</li>
      </ul>
    </p>
    <p style="max-width: 800px; margin: 20px auto;">
      Join the FlexCommerce family today and explore a world where technology meets trust.
    </p>
  </section>


  <!-- Contact Section -->
  <section class="contact" id="contact">
    <h2>Contact Us</h2>
    <p>Email: info@flexcommerce.com | Phone: +91 12345 67890</p>
  </section>

  <!-- Account Section -->
    <section class="account" id="account" style="background-color: #1e1e1e; color: #fff; padding: 40px 20px; text-align: center; max-width: 600px; margin: 50px auto; border-radius: 10px;">
      <h2 style="color: #ffcc00;">User Account</h2>
      
      <p>
        <a href="#login-form" style="color: #1e90ff; text-decoration: underline; cursor: pointer; margin-right: 20px;">Login</a>
        <a href="#signup" style="color: #1e90ff; text-decoration: underline; cursor: pointer;">Sign Up</a>
      </p>
      
      <!-- Login Form (visible when #login-form is targeted) -->
      <div id="login-form" style="display: none; text-align: left; margin-top: 30px; background-color: #292929; padding: 20px; border-radius: 8px;">
        <h3>Login</h3>
        <form>
          <label for="name" style="display:block; margin-bottom:6px;">Name</label>
          <input type="text" id="name" name="name" required style="width: 100%; padding: 8px; margin-bottom: 15px; border-radius: 4px; border: none;" />

          <label for="password" style="display:block; margin-bottom:6px;">Password</label>
          <input type="password" id="password" name="password" required style="width: 100%; padding: 8px; margin-bottom: 15px; border-radius: 4px; border: none;" />

          <label for="mobile" style="display:block; margin-bottom:6px;">Mobile Number</label>
          <input type="tel" id="mobile" name="mobile" required pattern="[0-9]{10}" placeholder="10-digit mobile" style="width: 100%; padding: 8px; margin-bottom: 15px; border-radius: 4px; border: none;" />

          <label for="email" style="display:block; margin-bottom:6px;">Email ID</label>
          <input type="email" id="email" name="email" required style="width: 100%; padding: 8px; margin-bottom: 15px; border-radius: 4px; border: none;" />

          <label for="address" style="display:block; margin-bottom:6px;">Address</label>
          <textarea id="address" name="address" required rows="3" style="width: 100%; padding: 8px; border-radius: 4px; border: none;"></textarea>

          <button type="submit" style="margin-top: 15px; padding: 10px 20px; background-color: #007bff; color: white; border: none; border-radius: 6px; cursor: pointer;">
            Submit
          </button>
        </form>
        <p style="margin-top: 10px;"><a href="#account" style="color: #888;">Close</a></p>
      </div>

      <!-- Sign Up Section (visible when #signup is targeted) -->
      <div id="signup" style="display: none; margin-top: 30px; text-align: center;">
        <h3>Sign Up with Google</h3>
        <a href="https://accounts.google.com/signin" target="_blank" rel="noopener noreferrer" style="display: inline-block; margin-top: 15px;">
          <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAMwAAADACAMAAAB/Pny7AAABJlBMVEX////lQzU0o1NCgO/2twQ+fu/T3vpMhu83eu/n7v1znvLo8P32tQCGq/TlQTMwolD++vr1sQAnn0rkPC3kNiX3zMn//vr97cz98dfg6fz4/PlDqV/6393409H+9fTjKRLpZlzqbGPzr6r5zWnJ5NDr9e386ej0trLxnpj1wb7sfXXkMB3nTD7vlY/nVkrrdGv857L4yFj3vCv61Hz4w0X74KT++On09/7735NajfHD1Pm02b1VsG0AmjrW69yRy6DuiIDjHwD4zb/seUDvijvxnDP0qzDrdEnoW0HlODzwkDLqakypwfdklPGUtPW+u0SnuVPfvDqLtl5Wqle9v1V7wIxqrVRjtHxFksFWobBUp5VOjd9LkstXn7lPop5Bo3RHo4ORu9p6j5UwAAAH4klEQVR4nO2aa3fSSBiAQwgW2zShSahKuBW5lgAt1nbbAKGrrq7b1nph0VrX3f//J3YmKS2XTO7DgGeeL3o8wJnH9zIzb8IwFAqFQqFQKBQKhUKhUCgUCoVCoVAolF+NVCqVh6RILyQU+Wo2m0s3aqVSHVJrpHO5bDVPell+SeWruUapvl/UlPPzQqHQBBQK5wVFK+7XS41cdW3ClKpmG/VhUWs2FVkWYtMIgqw0m1pxWG9k18Enn6sN99qyMqcxZyS0O61adsUzrlobFtvCfEBshMBHtL1WeoV1svWOJsiCm8m9T6y9X6qSXrQ91VZb9mry4FMsrWB0ssOmQ504+BS0xmrppKqlWNO/iYVc2FslnXyjo8gBVSCKPMyuSqPOtjQlaFgshOZebSWCk28U5TBhsWwUrZUlbWKGJUDdLyILnTTpVMt13HdIbwhym2yXToEUi0bFtNHqBLfQVK0dnUsMptqQmE2qHq0LCM55i5RLSwjdxeZQ2jlCLsNmxC6CUiTnEm2KgQawlybjkm/9Oi6pUizqHAMuZDZN2JOjdYkRc2HSvvZKwcLxM0qRlEu249VFVpqFQhOcqcFfzs2/IFzahOoFFL8nF3CJPBeKrVo6Z9EotYqFc8UuRIpGqCczTM3D7QUOyNr17MxQFo5p00NlIT7g/E8qLkzOvZEJstxG3k8aHW3mXiqQyzGmuu8WGHD87TheHNPmHOf+00ViLqlazNkF1ETHdUABdYSJS2MpC7cj57LDgMV5GezlG/uaTNol1XJOMlkb5rxtGNU6sIEu5C7LOc0xMODq6/l6lWqARtAm6JLfbzqlmFL0Nc7LFUm6ML87bZfAxee4KEtyILN7+OpP9HMX3y5kOeC6rzXUkbHZWSsX5pDnuDdtexlid96AHHSBDPfHW7vYyGvmwryALhy380pbdNFqpIer/nhyZMlw3Pt388Ufq6/EFN87L7mJDPfmrTaTavL+ij6bRHH84t4FFM6raRuwkZNenU8esswsnNfv7vuAINTXq2CYXauXPfDmr8kGKq/XbsnALONmZUCqWTaCUFqzwDDHz+dcYKqZF7X1C8zuwdGCDOzRoHCUEunF+WX35XyW3RUOaGXrFhjm+Dc7F1g4SmvdKsauZO4K5/267THzu8wU/NGx65dPnj0KzEn0LrsHtiUDZQ7dv711tRGUy0c4ZHh7GZ7/zYPMdiIoG2cYZF7uIALDPfEiE0/Eg5HEIfMCJdPdxStzEb0MspnxR5hltqPvAE9RzWznOW6ZrSXKeKj/UDKbj6OX6aJkDjDLXGKQQW0zOx6aWRiZxOmvJLPxbIkyTzHLxKlMQBncaUZlXGRItWYsDQApg3nTTJxikCF1nMERGXIHTQwnAHJXAAxnM3KXs83oT83g2oyQ8XZtDi5zFf19JuRAYzugCp6bZrhR09Z20o2lyqDaGd/9UHb98snFphvINMQw0ECNZ/mja8nIuNs8dmbrbMPeJnmKQ8Z2cM7zHz+xUm8Q/ufPEHmWvIx+z7R/pMHzHz6LLCvp4X9+EyWDYZ4BOD5ckOl+YSFirxL2x08uUTIYOjNjPmyeseG5j9esaMqwoUNzhqj+xMYFFpm5B7TA5ZNquoA8Cx2aK2TJYJibQ6Z3Gh505L/Ze0QPDc2JR6eIzpzAcDIzmXqpAXSx68/ilEzPfa9x4gLlksBTMszU6yZmirHTSKMwifb4EiWzgWP/N5nkGc9Np5gVGjZMol2gjqEJXCXDTF7R4rtfPrPziKoe2AZdMXE8u4yJ2c/47vWCilk2Qc8BW+hzWRxbljHWa40f51NsUjbjYDYnqLaMN8vgC6ecTYrdN4EgNicXiCMmlMHwoOmB3cNrVUTJgNj4b2knZ6iCAeB4ODtFWUS7BDoJOLkkLnEGhmEyI8lBBtiUffU0x7jgLX/IgHUKDbDRfQRnC7nBmIE5xdeXLTKGY2jAfmN4bQOZynbCKS5Ybv+zDHouNuzYW3Aq+vhrHNmV4YUZ0xlziozu2AOAjciO3Csno49USf12irbB8WrGApWxc2gsHZfrGlABn5LYm+8om+Qm3lZ2x8Bhq5noSOIYfVarGKokWb8h/bxN2tYNlheA7NAlVxuwTEkCxZOZNcpkKgOj15/6vqT+sD0BJK+W4wL+Zz3IwIX2++pILw8mlHVjLPb7s1kqSv98X2zQCSwTJlsGrmXzsFS4eLXX66nQTbKJqSjd3M4HZ2lJBin3vMXmbrl3ICP488fcQQDfbdmGjO7Lxo35Hp3cXFqSWTYuu40/RPXm9sEmgWW+7GRjeGlp3m3En18nPXqpBYPFBgTn28ZdcPAMMZ1tRlHb3HxPmKOypatAG8P5OuDbRvr3Np7ANCl3t9FVr/uNR5vejzghl8g7NOzR/xFSsWyijI0UYpIYBeVRZIUjij2yLuZ5Ppr9E97pyKow5vU3iuBIqhH6YWIUDIzQXU2UHC5zywUEpx8qOJK4GmGxqOhs8OCI/ZAP3iKnMrK7eXlSUSN4jyBqzL7m0wd8nng/RjAwxirr3QeajPyMc5fMQAc+ouQuBGPYGxvl1VWBVAb6yMVHFCVJhSaD1UywGYCPMerBydlCDQEN8K/qyNDLlTUwschU4JRs1FOlPkSy/uibAdF1EJK1MZkAjODkD2AAgAOcB1bWJyJ2ZO4gvQ4KhUKhUCgUCoVCoVAoFAqFQqFQKBRKxPwPSysiUJY3JvEAAAAASUVORK5CYII=" 
              alt="Google Sign Up" width="60" height="60" style="cursor: pointer;" />
        </a>
        <p style="margin-top: 10px;"><a href="#account" style="color: #888;">Close</a></p>
      </div>

    </section>

    <style>
      /* CSS to show/hide login and signup based on target */
      #login-form:target {
        display: block !important;
      }

      #signup:target {
        display: block !important;
      }
    </style>


  <!-- Footer -->
  <footer>
    <div class="social-icons">
      <a href="#"><i class="fab fa-facebook-f"></i></a>
      <a href="#"><i class="fab fa-twitter"></i></a>
      <a href="#"><i class="fab fa-instagram"></i></a>
    </div>
    <p>&copy; 2025 FlexCommerce. All rights reserved.</p>
  </footer>

</body>
</html>
```
#### smartwatch.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Portable Charger Details</title>
  <link rel="stylesheet" href="style.css" />
  <style>
    body {
      background-color: #121212;
      color: #ffffff;
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }

    .product-detail-container {
      background-color: #1e1e1e;
      color: #ffffff;
      padding: 30px;
      border-radius: 12px;
      max-width: 800px;
      margin: 50px auto;
      box-shadow: 0 0 20px rgba(255, 255, 255, 0.1);
      text-align: center;
    }

    .product-detail-container img {
      max-width: 100%;
      height: auto;
      margin-bottom: 20px;
      border-radius: 10px;
    }

    .product-description h2,
    .product-features h2 {
      color: #ffcc00;
    }

    .product-description p,
    .product-features ul {
      color: #dddddd;
      text-align: left;
      max-width: 700px;
      margin: auto;
    }

    .product-features ul {
      list-style: disc;
      padding-left: 20px;
    }

    .buy-now {
      margin-top: 30px;
    }

    .buy-now button {
      padding: 10px 20px;
      margin: 10px;
      background-color: #007bff;
      color: white;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }

    .buy-now button:hover {
      background-color: #0056b3;
    }
  </style>
</head>
<body>
   <main class="product-detail-container">
   <h1>Smartwatch</h1>
   <img src="C:\Users\thula\OneDrive\Documents\website\images\smart.png" alt="Smartwatch" />

    <section class="product-description">
    <h2>Product Description</h2>
    <p>Stay connected and healthy with our latest smartwatch. Quality, performance, and style in one device.</p>
    </section>

    <section class="product-features">
    <h2>Features</h2>
    <ul>
      <li>Heart rate monitoring</li>
      <li>Sleep tracking</li>
      <li>Water resistant up to 50 meters</li>
      <li>Notifications for calls and messages</li>
      <li>Battery life up to 7 days</li>
    </ul>
  </section>

    <section class="buy-now">
      <button>Add to Cart</button>
      <button>Buy Now</button>
    </section>
  </main>

</body>
</html>
```
#### earbuds.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Wireless Earbuds Details</title>
  <link rel="stylesheet" href="style.css" />
  <style>
    body {
      background-color: #121212;
      color: #ffffff;
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }

    .product-detail-container {
      background-color: #1e1e1e;
      color: #ffffff;
      padding: 30px;
      border-radius: 12px;
      max-width: 800px;
      margin: 50px auto;
      box-shadow: 0 0 20px rgba(255, 255, 255, 0.1);
      text-align: center;
    }

    .product-detail-container img {
      max-width: 100%;
      height: auto;
      margin-bottom: 20px;
      border-radius: 10px;
    }

    .product-description h2,
    .product-features h2 {
      color: #ffcc00;
    }

    .product-description p,
    .product-features ul {
      color: #dddddd;
      text-align: left;
      max-width: 700px;
      margin: auto;
    }

    .product-features ul {
      list-style: disc;
      padding-left: 20px;
    }

    .buy-now {
      margin-top: 30px;
    }

    .buy-now button {
      padding: 10px 20px;
      margin: 10px;
      background-color: #007bff;
      color: white;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }

    .buy-now button:hover {
      background-color: #0056b3;
    }
  </style>
</head>
<body>

  <main class="product-detail-container">
    <h1>Wireless Earbuds</h1>
    <img src="C:\Users\thula\OneDrive\Documents\website\images\earbuds.png" alt="Wireless Earbuds" />

    <section class="product-description">
      <h2>Product Description</h2>
      <p>Experience true wireless freedom and premium sound quality with our latest wireless earbuds. Perfect for music, calls, and workouts.</p>
    </section>

    <section class="product-features">
      <h2>Features</h2>
      <ul>
        <li>Bluetooth 5.3 with instant pairing</li>
        <li>High-fidelity audio and deep bass</li>
        <li>Up to 30 hours battery with case</li>
        <li>Touch controls for music and calls</li>
        <li>Water and sweat resistant (IPX5)</li>
        <li>Noise isolation and voice assistant support</li>
      </ul>
    </section>

    <section class="buy-now">
      <button>Add to Cart</button>
      <button>Buy Now</button>
    </section>
  </main>

</body>
</html>
```
#### charger.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Portable Charger Details</title>
  <link rel="stylesheet" href="style.css" />
  <style>
    body {
      background-color: #121212;
      color: #ffffff;
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }

    .product-detail-container {
      background-color: #1e1e1e;
      color: #ffffff;
      padding: 30px;
      border-radius: 12px;
      max-width: 800px;
      margin: 50px auto;
      box-shadow: 0 0 20px rgba(255, 255, 255, 0.1);
      text-align: center;
    }

    .product-detail-container img {
      max-width: 100%;
      height: auto;
      margin-bottom: 20px;
      border-radius: 10px;
    }

    .product-description h2,
    .product-features h2 {
      color: #ffcc00;
    }

    .product-description p,
    .product-features ul {
      color: #dddddd;
      text-align: left;
      max-width: 700px;
      margin: auto;
    }

    .product-features ul {
      list-style: disc;
      padding-left: 20px;
    }

    .buy-now {
      margin-top: 30px;
    }

    .buy-now button {
      padding: 10px 20px;
      margin: 10px;
      background-color: #007bff;
      color: white;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }

    .buy-now button:hover {
      background-color: #0056b3;
    }
  </style>
</head>
<body>

  <main class="product-detail-container">
    <h1>Portable Charger</h1>
    <img src="C:\Users\thula\OneDrive\Documents\website\images\power.png" alt="Portable Charger" />

    <section class="product-description">
      <h2>Product Description</h2>
      <p>Charge anywhere with our high-capacity portable charger. Stay powered up on the go with fast-charging technology.</p>
    </section>

    <section class="product-features">
      <h2>Features</h2>
      <ul>
        <li>10,000mAh high-capacity battery</li>
        <li>Dual USB output ports</li>
        <li>Fast charging supported</li>
        <li>LED battery level indicator</li>
        <li>Compact and lightweight design</li>
        <li>Compatible with all USB devices</li>
      </ul>
    </section>

    <section class="buy-now">
      <button>Add to Cart</button>
      <button>Buy Now</button>
    </section>
  </main>

</body>
</html>
```
#### speaker.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Bluetooth Speaker Details</title>
  <link rel="stylesheet" href="style.css" />
  <style>
    body {
      background-color: #121212;
      color: #ffffff;
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }

    .product-detail-container {
      background-color: #1e1e1e;
      color: #ffffff;
      padding: 30px;
      border-radius: 12px;
      max-width: 800px;
      margin: 50px auto;
      box-shadow: 0 0 20px rgba(255, 255, 255, 0.1);
      text-align: center;
    }

    .product-detail-container img {
      max-width: 100%;
      height: auto;
      margin-bottom: 20px;
      border-radius: 10px;
    }

    .product-description h2,
    .product-features h2 {
      color: #ffcc00;
    }

    .product-description p,
    .product-features ul {
      color: #dddddd;
      text-align: left;
      max-width: 700px;
      margin: auto;
    }

    .product-features ul {
      list-style: disc;
      padding-left: 20px;
    }

    .buy-now {
      margin-top: 30px;
    }

    .buy-now button {
      padding: 10px 20px;
      margin: 10px;
      background-color: #007bff;
      color: white;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }

    .buy-now button:hover {
      background-color: #0056b3;
    }
  </style>
</head>
<body>

  <main class="product-detail-container">
    <h1>Bluetooth Speaker</h1>
    <img src="C:\Users\thula\OneDrive\Documents\website\images\bluetooth.png" alt="Bluetooth Speaker" />

    <section class="product-description">
      <h2>Product Description</h2>
      <p>Powerful sound in a compact design. Perfect for both indoor and outdoor entertainment with high-quality audio and deep bass.</p>
    </section>

    <section class="product-features">
      <h2>Features</h2>
      <ul>
        <li>Crystal-clear stereo sound</li>
        <li>Bluetooth 5.0 for seamless pairing</li>
        <li>10-hour battery life</li>
        <li>Water-resistant (IPX4)</li>
        <li>Built-in microphone for calls</li>
        <li>Compact, travel-friendly design</li>
      </ul>
    </section>

    <section class="buy-now">
      <button>Add to Cart</button>
      <button>Buy Now</button>
    </section>
  </main>

</body>
</html>
```
#### drone.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Mini Drone Details</title>
  <link rel="stylesheet" href="style.css" />
  <style>
    body {
      background-color: #121212;
      color: #ffffff;
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }

    .product-detail-container {
      background-color: #1e1e1e;
      color: #ffffff;
      padding: 30px;
      border-radius: 12px;
      max-width: 800px;
      margin: 50px auto;
      box-shadow: 0 0 20px rgba(255, 255, 255, 0.1);
      text-align: center;
    }

    .product-detail-container img {
      max-width: 100%;
      height: auto;
      margin-bottom: 20px;
      border-radius: 10px;
    }

    .product-description h2,
    .product-features h2 {
      color: #ffcc00;
    }

    .product-description p,
    .product-features ul {
      color: #dddddd;
      text-align: left;
      max-width: 700px;
      margin: auto;
    }

    .product-features ul {
      list-style: disc;
      padding-left: 20px;
    }

    .buy-now {
      margin-top: 30px;
    }

    .buy-now button {
      padding: 10px 20px;
      margin: 10px;
      background-color: #007bff;
      color: white;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }

    .buy-now button:hover {
      background-color: #0056b3;
    }
  </style>
</head>
<body>

  <main class="product-detail-container">
    <h1>Mini Drone</h1>
    <img src="C:\Users\thula\OneDrive\Documents\website\images\drone.png" alt="Mini Drone" />

    <section class="product-description">
      <h2>Product Description</h2>
      <p>Capture amazing aerial shots and enjoy a thrilling flying experience with our compact and easy-to-use mini drone.</p>
    </section>

    <section class="product-features">
      <h2>Features</h2>
      <ul>
        <li>HD camera with real-time transmission</li>
        <li>Easy one-key takeoff/landing</li>
        <li>360° flips and rolls</li>
        <li>Lightweight and portable design</li>
        <li>Rechargeable battery with 15-minute flight time</li>
        <li>Beginner-friendly controls</li>
      </ul>
    </section>

    <section class="buy-now">
      <button>Add to Cart</button>
      <button>Buy Now</button>
    </section>
  </main>

</body>
</html>
```
#### styles.css
```
/* Global Styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Segoe UI', sans-serif;
  line-height: 1.6;
  background: #121212;
  color: #f0f0f0;
}

a {
  color: #f0f0f0;
  text-decoration: none;
  transition: color 0.3s ease;
}

a:hover {
  color: #00adb5;
}

/* Header */
header {
  background: #1f1f1f;
  padding: 1rem 2rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  font-size: 1.5rem;
  font-weight: bold;
  color: #00adb5;
}

.nav-links {
  display: flex;
  gap: 1.5rem;
  list-style: none;
}

.nav-links a:hover {
  border-bottom: 2px solid #00adb5;
}

/* Home */
.home {
  background: url('https://via.placeholder.com/1200x400') center/cover no-repeat;
  height: 80vh;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  padding: 2rem;
}

.home-content h1 {
  font-size: 2.5rem;
  margin-bottom: 1rem;
}

.home-content p {
  margin-bottom: 2rem;
  font-size: 1.1rem;
}

.btn {
  padding: 0.75rem 1.5rem;
  background: #00adb5;
  color: #fff;
  border-radius: 5px;
  transition: background 0.3s ease;
}

.btn:hover {
  background: #007b83;
}
/* Hide the checkbox inputs */
.toggle-details {
  display: none;
}

/* Initially hide the product details */
.product-details {
  display: none;
  background-color: #f9f9f9;
  padding: 12px;
  border-radius: 4px;
  margin-top: 12px;
}

/* Style the label as a button */
.see-details-btn {
  display: inline-block;
  margin-top: 12px;
  padding: 8px 16px;
  background-color: #007bff;
  color: white;
  cursor: pointer;
  border-radius: 4px;
  user-select: none;
}

.see-details-btn:hover {
  background-color: #0056b3;
}

/* Show the details when checkbox is checked */
.toggle-details:checked ~ .product-details {
  display: block;
}

/* Products */
.products {
  padding: 3rem 2rem;
  background: #181818;
}

.products h2 {
  text-align: center;
  margin-bottom: 2rem;
  color: #00adb5;
}

.product-grid {
  display: flex;
  gap: 2rem;
  justify-content: center;
  flex-wrap: wrap;
}

.product-card {
  background: #2a2a2a;
  padding: 1rem;
  border-radius: 10px;
  text-align: center;
  width: 200px;
  transition: transform 0.3s ease;
}

.product-card:hover {
  transform: translateY(-10px);
}

.product-card img {
  width: 100%;
  border-radius: 5px;
}

.product-card h3 {
  margin: 0.5rem 0;
}
body {
  background-color: #121212; /* Dark background */
  color: #ffffff;            /* White text for contrast */
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

.product-detail-container {
  background-color: #1e1e1e; /* Darker card background */
  color: #ffffff;            /* Ensures text is white inside the card */
  padding: 30px;
  border-radius: 12px;
  max-width: 800px;
  margin: 50px auto;
  box-shadow: 0 0 20px rgba(255, 255, 255, 0.1);
  text-align: center;
}

/* About, Contact, Account */
.about, .contact, .account {
  padding: 3rem 2rem;
  background: #1f1f1f;
  text-align: center;
}

.about h2, .contact h2, .account h2 {
  color: #00adb5;
  margin-bottom: 1rem;
}

/* Footer */
footer {
  background: #121212;
  padding: 2rem;
  text-align: center;
}

.social-icons {
  margin-bottom: 1rem;
}

.social-icons a {
  color: #f0f0f0;
  margin: 0 10px;
  font-size: 1.2rem;
  transition: color 0.3s ease;
}

.social-icons a:hover {
  color: #00adb5;
}
.products {
  background-color: #111;
  color: #fff;
  text-align: center;
  padding: 50px 20px;
}

.products h2 {
  font-size: 2rem;
  margin-bottom: 30px;
  color: #00bcd4;
}

.product-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 30px;
}

.product-card {
  background-color: #222;
  border-radius: 10px;
  padding: 20px;
  width: 250px;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.product-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 0 10px rgba(0, 188, 212, 0.5);
}

.product-card img {
  width: 100%;
  border-radius: 8px;
  margin-bottom: 15px;
}

.product-card h3 {
  margin: 10px 0;
  color: #00bcd4;
}

.product-card p {
  font-size: 0.9rem;
  margin-bottom: 15px;
}

.product-card button {
  background-color: #00bcd4;
  color: #fff;
  border: none;
  padding: 10px 15px;
  border-radius: 5px;
  cursor: pointer;
}

.product-card button:hover {
  background-color: #0097a7;
}
```
## OUTPUT

#### HOME PAGE:
![{069FC9DB-962A-414A-A532-E4D0CFDAE83B}](https://github.com/user-attachments/assets/f805bd4e-2720-4b27-9c78-a3fd6fbd4d01)

#### PRODUCTS PAGE:
![{AC4D26BF-F4CD-4DA3-93B2-5CCD904CCCE2}](https://github.com/user-attachments/assets/f08059dc-ba71-445c-b0fb-6cec1d5787c5)

#### DETAILS PAGE:
![{3219A4F7-DF79-4F5D-93BD-5D2D9583FA20}](https://github.com/user-attachments/assets/63564a45-d37f-4216-aeae-8ae3031d16ca)

#### ABOUT US:
![{642DAAEE-ECF5-4444-8B5F-15E332949E18}](https://github.com/user-attachments/assets/ba6a4812-2cfa-4115-8863-650c48e89432)

#### CONTACT AND USER ACCOUNT:
![{6CED2664-9CC7-4BE2-896E-27963CBAC7FC}](https://github.com/user-attachments/assets/fabf0229-fdde-4576-a76d-25bcbf3ea7ab)

#### LOGIN:
![{A4A8466A-F9E9-4EBF-B847-CAB1805A3D53}](https://github.com/user-attachments/assets/66de4e9c-28eb-4990-bdc9-53b0f53746e1)

## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
