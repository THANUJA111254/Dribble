# Project Responsive Web Design using Bootstrap
## Date:20.05.25

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :

home.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Urban Threads – Fashion Store</title>
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet"/>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <a class="navbar-brand" href="#">
      <img src="logo.png" width="40" height="40" alt="Urban Threads Logo" />
      <span class="ml-2">Urban Threads</span>
    </a>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ml-auto">
        <li class="nav-item"><a class="nav-link" href="#">Home</a></li>
        <li class="nav-item"><a class="nav-link" href="#">About</a></li>
        <li class="nav-item"><a class="nav-link" href="#">Contact</a></li>
      </ul>
    </div>
  </nav>

  <header class="header text-white text-center">
    <div class="container">
      <h1 class="display-4">Urban Threads</h1>
      <p class="lead">Style that speaks your vibe</p>
    </div>
  </header>

  <div class="container my-5">
    <div class="row">

      <!-- Product 1 -->
      <div class="col-md-3 mb-4">
        <div class="card h-100">
          <img src="zara-denim.jpg" class="card-img-top" alt="Zara Denim Jacket" />
          <div class="card-body">
            <h5 class="card-title">Zara Denim Jacket</h5>
            <p class="card-text">Trendy blue jacket with button-down front.</p>
            <p class="price">$59.99</p>
            <a href="#" class="btn btn-primary">Buy Now</a>
          </div>
        </div>
      </div>

      <!-- Product 2 -->
      <div class="col-md-3 mb-4">
        <div class="card h-100">
          <img src="levis-jeans.jpg" class="card-img-top" alt="Levi’s Slim Fit Jeans" />
          <div class="card-body">
            <h5 class="card-title">Levi’s Slim Fit Jeans</h5>
            <p class="card-text">Comfortable stretch jeans for everyday wear.</p>
            <p class="price">$49.99</p>
            <a href="#" class="btn btn-primary">Buy Now</a>
          </div>
        </div>
      </div>

      <!-- Product 3 -->
      <div class="col-md-3 mb-4">
        <div class="card h-100">
          <img src="nike-airmax.jpg" class="card-img-top" alt="Nike Air Max" />
          <div class="card-body">
            <h5 class="card-title">Nike Air Max Sneakers</h5>
            <p class="card-text">Cushioned comfort for all-day style.</p>
            <p class="price">$89.99</p>
            <a href="#" class="btn btn-primary">Buy Now</a>
          </div>
        </div>
      </div>

      <!-- Product 4 -->
      <div class="col-md-3 mb-4">
        <div class="card h-100">
          <img src="adidas-ultraboost.jpg" class="card-img-top" alt="Adidas Ultraboost" />
          <div class="card-body">
            <h5 class="card-title">Adidas Ultraboost</h5>
            <p class="card-text">Lightweight performance running shoes.</p>
            <p class="price">$99.99</p>
            <a href="#" class="btn btn-primary">Buy Now</a>
          </div>
        </div>
      </div>

      <!-- Product 5 -->
      <div class="col-md-3 mb-4">
        <div class="card h-100">
          <img src="fossil-watch.jpg" class="card-img-top" alt="Fossil Watch" />
          <div class="card-body">
            <h5 class="card-title">Fossil Chronograph Watch</h5>
            <p class="card-text">Brown leather strap with multifunction dial.</p>
            <p class="price">$129.99</p>
            <a href="#" class="btn btn-primary">Buy Now</a>
          </div>
        </div>
      </div>

      <!-- Product 6 -->
      <div class="col-md-3 mb-4">
        <div class="card h-100">
          <img src="rayban.jpg" class="card-img-top" alt="Ray-Ban Aviators" />
          <div class="card-body">
            <h5 class="card-title">Ray-Ban Aviators</h5>
            <p class="card-text">Classic metal-frame aviators with UV protection.</p>
            <p class="price">$79.99</p>
            <a href="#" class="btn btn-primary">Buy Now</a>
          </div>
        </div>
      </div>

      <!-- Product 7 -->
      <div class="col-md-3 mb-4">
        <div class="card h-100">
          <img src="wildcraft-backpack.jpg" class="card-img-top" alt="Wildcraft Backpack" />
          <div class="card-body">
            <h5 class="card-title">Wildcraft Backpack</h5>
            <p class="card-text">Durable everyday backpack with compartments.</p>
            <p class="price">$39.99</p>
            <a href="#" class="btn btn-primary">Buy Now</a>
          </div>
        </div>
      </div>

      <!-- Product 8 -->
      <div class="col-md-3 mb-4">
        <div class="card h-100">
          <img src="tommy-bag.jpg" class="card-img-top" alt="Tommy Hilfiger Bag" />
          <div class="card-body">
            <h5 class="card-title">Tommy Crossbody Bag</h5>
            <p class="card-text">Compact crossbody with signature branding.</p>
            <p class="price">$64.99</p>
            <a href="#" class="btn btn-primary">Buy Now</a>
          </div>
        </div>
      </div>

    </div>
  </div>

  <footer class="text-center bg-dark text-white py-3">
    &copy; 2025 Urban Threads. All rights reserved.
  </footer>

  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```
buypage.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Urban Threads - Buy Products</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background: #f3f4f6;
    }

    header {
      background-color: #222;
      color: white;
      padding: 20px 0;
      text-align: center;
    }

    header img {
      width: 60px;
      height: 60px;
      border-radius: 50%;
      vertical-align: middle;
    }

    header h1 {
      display: inline-block;
      margin-left: 15px;
      font-size: 2rem;
      vertical-align: middle;
    }

    .container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 30px;
      padding: 40px;
      max-width: 1200px;
      margin: auto;
    }

    .product-card {
      background: white;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
      padding: 15px;
      text-align: center;
      transition: transform 0.3s;
    }

    .product-card:hover {
      transform: translateY(-5px);
    }

    .product-card img {
      width: 100%;
      height: 220px;
      object-fit: contain;
      background-color: #f4f4f4;
      border-radius: 10px;
    }

    .product-title {
      font-size: 18px;
      margin: 15px 0 5px;
      color: #333;
    }

    .product-price {
      color: #28a745;
      font-weight: bold;
      margin-bottom: 10px;
    }

    .btn-container {
      display: flex;
      justify-content: center;
      gap: 10px;
    }

    .btn {
      padding: 10px 15px;
      font-size: 14px;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      text-decoration: none;
      color: white;
      transition: background 0.3s;
    }

    .btn-buy-now {
      background-color: #6a0dad;
    }

    .btn-buy-now:hover {
      background-color: #4b0082;
    }

    .btn-add-to-cart {
      background-color: #495057;
    }

    .btn-add-to-cart:hover {
      background-color: #343a40;
    }

    footer {
      text-align: center;
      padding: 15px;
      background-color: #222;
      color: white;
      font-size: 14px;
    }
  </style>
</head>
<body>
  <header>
    <img src="logo.png" alt="Urban Threads Logo" />
    <h1>Urban Threads</h1>
  </header>

  <div class="container">
    <!-- Product 1 -->
    <div class="product-card">
      <img src="zara-denim.jpg" alt="Zara Denim Jeans" />
      <h2 class="product-title">Zara Denim Jeans</h2>
      <p class="product-price">$120</p>
      <div class="btn-container">
        <a href="#" class="btn btn-buy-now">Buy Now</a>
        <a href="#" class="btn btn-add-to-cart">Add to Cart</a>
      </div>
    </div>

    <!-- Product 2 -->
    <div class="product-card">
      <img src="levis-jeans.jpg" alt="Levi's Slim Fit Jeans" />
      <h2 class="product-title">Levi's Slim Fit Jeans</h2>
      <p class="product-price">$150</p>
      <div class="btn-container">
        <a href="#" class="btn btn-buy-now">Buy Now</a>
        <a href="#" class="btn btn-add-to-cart">Add to Cart</a>
      </div>
    </div>

    <!-- Product 3 -->
    <div class="product-card">
      <img src="nike-airmax.jpg" alt="Nike Air Max Shoes" />
      <h2 class="product-title">Nike Air Max Shoes</h2>
      <p class="product-price">$180</p>
      <div class="btn-container">
        <a href="#" class="btn btn-buy-now">Buy Now</a>
        <a href="#" class="btn btn-add-to-cart">Add to Cart</a>
      </div>
    </div>

    <!-- Product 4 -->
    <div class="product-card">
      <img src="adidas-ultraboost.jpg" alt="Adidas Ultraboost" />
      <h2 class="product-title">Adidas Ultraboost</h2>
      <p class="product-price">$170</p>
      <div class="btn-container">
        <a href="#" class="btn btn-buy-now">Buy Now</a>
        <a href="#" class="btn btn-add-to-cart">Add to Cart</a>
      </div>
    </div>

    <!-- Product 5 -->
    <div class="product-card">
      <img src="fossil-watch.jpg" alt="Fossil Chronograph Watch" />
      <h2 class="product-title">Fossil Chronograph Watch</h2>
      <p class="product-price">$220</p>
      <div class="btn-container">
        <a href="#" class="btn btn-buy-now">Buy Now</a>
        <a href="#" class="btn btn-add-to-cart">Add to Cart</a>
      </div>
    </div>

    <!-- Product 6 -->
    <div class="product-card">
      <img src="rayban.jpg" alt="Ray-Ban Aviator Sunglasses" />
      <h2 class="product-title">Ray-Ban Aviator Sunglasses</h2>
      <p class="product-price">$140</p>
      <div class="btn-container">
        <a href="#" class="btn btn-buy-now">Buy Now</a>
        <a href="#" class="btn btn-add-to-cart">Add to Cart</a>
      </div>
    </div>

    <!-- Product 7 -->
    <div class="product-card">
      <img src="wildcraft-backpack.jpg" alt="Wildcraft Backpack" />
      <h2 class="product-title">Wildcraft Backpack</h2>
      <p class="product-price">$80</p>
      <div class="btn-container">
        <a href="#" class="btn btn-buy-now">Buy Now</a>
        <a href="#" class="btn btn-add-to-cart">Add to Cart</a>
      </div>
    </div>

    <!-- Product 8 -->
    <div class="product-card">
      <img src="tommy-bag.jpg" alt="Tommy Hilfiger Bag" />
      <h2 class="product-title">Tommy Hilfiger Bag</h2>
      <p class="product-price">$160</p>
      <div class="btn-container">
        <a href="#" class="btn btn-buy-now">Buy Now</a>
        <a href="#" class="btn btn-add-to-cart">Add to Cart</a>
      </div>
    </div>
  </div>

  <footer>
    &copy; 2024 Urban Threads. All Rights Reserved.
  </footer>
</body>
</html>

```
about.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>About Us - Urban Threads</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&display=swap');

        body {
            margin: 0;
            font-family: 'Poppins', Arial, sans-serif;
            background: linear-gradient(rgba(0, 0, 0, 0.65), rgba(0, 0, 0, 0.65)), 
                url('c:/Users/admin/OneDrive/Desktop/web development/project/about.avif') no-repeat center center fixed;
            background-size: cover;
            color: #f0f0f0;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            padding: 40px 20px;
        }

        .about-section {
            max-width: 900px;
            margin: 0 auto;
            background: rgba(30, 30, 30, 0.85);
            padding: 40px 50px;
            border-radius: 12px;
            box-shadow: 0 12px 25px rgba(0, 0, 0, 0.7);
            animation: fadeInUp 1s ease forwards;
        }

        h1 {
            font-size: 3rem;
            margin-bottom: 20px;
            text-align: center;
            color: #ffb300;
            letter-spacing: 2px;
            text-shadow: 0 0 8px #ffb300;
        }

        h3 {
            color: #ffcc00;
            margin-bottom: 12px;
            letter-spacing: 1px;
            text-shadow: 0 0 6px #ffcc00;
        }

        p {
            font-weight: 300;
            line-height: 1.6;
            margin-bottom: 25px;
            color: #ddd;
        }

        ul {
            padding-left: 25px;
            list-style-type: square;
            color: #eee;
            font-weight: 300;
            margin-bottom: 40px;
        }

        ul li {
            margin-bottom: 10px;
        }

        /* Responsive grid for content */
        .row {
            display: flex;
            flex-wrap: wrap;
            gap: 30px;
            justify-content: center;
        }

        .col-md-6 {
            flex: 1 1 450px;
            min-width: 280px;
        }

        /* Footer */
        footer {
            text-align: center;
            background: #111;
            color: #bbb;
            padding: 15px 10px;
            font-size: 0.9rem;
            margin-top: 50px;
            box-shadow: inset 0 1px 3px rgba(255, 255, 255, 0.1);
        }

        /* Animations */
        @keyframes fadeInUp {
            0% {
                opacity: 0;
                transform: translateY(30px);
            }
            100% {
                opacity: 1;
                transform: translateY(0);
            }
        }

        /* Hover effect for list items */
        ul li:hover {
            color: #ffcc00;
            cursor: default;
            transition: color 0.3s ease;
        }

    </style>
</head>
<body>
    <div class="about-section">
        <h1>About Us</h1>
        <p>
            Welcome to <strong>Urban Threads</strong>, where creativity meets innovation.
            We are passionate about crafting solutions that inspire, engage, and transform.
            Whether you’re here to learn about our journey, explore our projects, or connect with us, you’ve come to the right place.
        </p>
        <div class="row">
            <div class="col-md-6">
                <h3>Who We Are</h3>
                <p>
                    We are a team of dedicated professionals with a shared mission to deliver excellence.
                    From innovative designs to seamless functionality, we specialize in bringing ideas to life.
                </p>

                <h3>Our Vision</h3>
                <p>
                    To create a world where technology and creativity coexist harmoniously,
                    empowering businesses and individuals to achieve their goals.
                </p>
            </div>
            <div class="col-md-6">
                <h3>Why Choose Us?</h3>
                <ul>
                    <li>Expertise in cutting-edge technologies</li>
                    <li>Customer-centric approach</li>
                    <li>Commitment to quality and innovation</li>
                    <li>Responsive & modern designs</li>
                    <li>Continuous support and updates</li>
                </ul>
            </div>
        </div>
    </div>

    <footer>
        &copy; 2024 Urban Threads. All rights reserved.
    </footer>
</body>
</html>
```
contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Contact Us - Urban Threads</title>
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet" />
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&display=swap');

        body {
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
            font-family: 'Poppins', Arial, sans-serif;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: flex-start;
            align-items: center;
            padding: 40px 20px;
            color: #cce7ff;
        }

        /* Navbar Logo Container */
        .navbar-logo-container {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 15vh;
            margin-bottom: 40px;
        }

        .navbar-brand {
            display: flex;
            align-items: center;
            text-decoration: none;
            color: #00ffe7;
            font-weight: 700;
            font-size: 2.5rem;
            letter-spacing: 2px;
            text-shadow: 0 0 8px #00ffe7aa;
            transition: transform 0.3s ease;
        }
        .navbar-brand:hover {
            transform: scale(1.1);
            text-shadow: 0 0 15px #00ffe7ff;
        }

        .navbar-brand img {
            margin-right: 20px;
            width: 90px;
            height: 90px;
            border-radius: 50%;
            object-fit: cover;
            border: 3px solid #00ffe7;
            box-shadow:
                0 0 10px #00ffe7aa,
                0 0 20px #00ffe7cc,
                0 0 30px #00ffe7ff;
            transition: box-shadow 0.3s ease;
        }
        .navbar-brand img:hover {
            box-shadow:
                0 0 15px #00fff7ee,
                0 0 30px #00fff7ff,
                0 0 45px #00fff7ff;
        }

        /* Contact Container */
        .contact-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            background: rgba(10, 30, 45, 0.85);
            backdrop-filter: blur(10px);
            padding: 40px 50px;
            border-radius: 20px;
            box-shadow: 0 15px 40px rgba(0, 255, 231, 0.5);
            max-width: 900px;
            width: 100%;
            gap: 40px;
        }

        /* Contact Form and Info */
        .contact-form, .contact-info {
            flex: 1 1 400px;
            color: #cce7ff;
        }

        /* Headings */
        h3 {
            font-weight: 600;
            font-size: 2rem;
            margin-bottom: 30px;
            text-shadow: 0 0 8px #00ffe7cc;
        }

        /* Form Styles */
        label {
            font-weight: 500;
            color: #a0dfff;
        }

        input.form-control, textarea.form-control {
            border-radius: 12px;
            border: none;
            padding: 15px 20px;
            font-size: 1rem;
            background: #0c1f2e;
            color: #cce7ff;
            box-shadow: inset 0 0 8px #00ffe7aa;
            transition: box-shadow 0.3s ease;
        }
        input.form-control::placeholder, textarea.form-control::placeholder {
            color: #70cfffaa;
        }
        input.form-control:focus, textarea.form-control:focus {
            box-shadow: 0 0 12px #00fff7;
            outline: none;
            border: none;
            background: #0d2437;
        }

        /* Submit Button */
        button.btn-primary {
            background: linear-gradient(45deg, #00ffe7, #00c8c8);
            border: none;
            font-weight: 600;
            padding: 15px 0;
            border-radius: 30px;
            font-size: 1.2rem;
            box-shadow: 0 8px 15px rgba(0, 255, 231, 0.6);
            transition: background 0.4s ease;
            width: 100%;
            cursor: pointer;
            color: #003f3f;
        }
        button.btn-primary:hover {
            background: linear-gradient(45deg, #00c8c8, #00ffe7);
            box-shadow: 0 12px 20px rgba(0, 255, 231, 0.9);
            color: #000;
        }

        /* Contact Info Text */
        .contact-info p {
            font-size: 1.1rem;
            margin-bottom: 18px;
            text-shadow: 0 0 4px rgba(0,0,0,0.8);
        }

        .contact-info strong {
            color: #00ffe7;
        }

        /* Follow Us Heading */
        .contact-info h4 {
            margin-top: 40px;
            font-weight: 600;
            text-shadow: 0 0 8px #00ffe7cc;
        }

        /* Social icons */
        .social-icons {
            margin-top: 20px;
        }

        .social-icons a {
            color: #00ffe7;
            font-size: 1.8rem;
            margin-right: 20px;
            transition: color 0.3s ease, transform 0.3s ease;
            text-decoration: none;
            display: inline-block;
        }
        .social-icons a:hover {
            color: #70f0ff;
            transform: scale(1.3);
        }

        /* Responsive */
        @media (max-width: 768px) {
            .contact-container {
                flex-direction: column;
                padding: 30px 20px;
            }
            .contact-form, .contact-info {
                flex: 1 1 100%;
            }
        }

    </style>
    <!-- Font Awesome for social icons -->
    <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
</head>
<body>

    <div class="navbar-logo-container">
        <a class="navbar-brand" href="#">
            <img src="logo.png" alt="Urban Threads Logo" />
            Urban Threads
        </a>
    </div>

    <div class="contact-container">
        <div class="contact-form">
            <h3>Send Us a Message</h3>
            <form>
                <div class="form-group">
                    <label for="name">Full Name</label>
                    <input type="text" class="form-control" id="name" placeholder="Enter your full name" required />
                </div>
                <div class="form-group">
                    <label for="email">Email Address</label>
                    <input type="email" class="form-control" id="email" placeholder="Enter your email" required />
                </div>
                <div class="form-group">
                    <label for="message">Your Message</label>
                    <textarea class="form-control" id="message" rows="5" placeholder="Write your message" required></textarea>
                </div>
                <button type="submit" class="btn btn-primary btn-block">Submit</button>
            </form>
        </div>

        <div class="contact-info">
            <h3>Get in Touch</h3>
            <p><strong>Phone:</strong> +91 98457 15327</p>
            <p><strong>Email:</strong> UrbanThreads123@gmail.com</p>

            <h4>Follow Us</h4>
           
        </div>
    </div>

</body>
</html>
```
styles.css
```
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap');

body {
  font-family: 'Poppins', sans-serif;
  background-color: #f9f9f9;
  color: #333;
}

.header {
  background: linear-gradient(90deg, #1e3c72, #2a5298);
  padding: 60px 0;
  color: white;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
}

.header h1 {
  font-weight: 600;
  font-size: 3rem;
}

.header p {
  font-size: 1.2rem;
}

.card {
  border: none;
  border-radius: 15px;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
  overflow: hidden;
}

.card:hover {
  transform: translateY(-8px);
  box-shadow: 0 12px 24px rgba(0, 0, 0, 0.15);
}

.card-img-top {
  height: 220px;
  object-fit: cover;
}

.card-title {
  font-weight: 600;
  font-size: 1.1rem;
}

.card-text {
  font-size: 0.95rem;
  color: #555;
}

.price {
  font-size: 1.05rem;
  color: #1e88e5;
  font-weight: 600;
}

.btn-primary {
  background-color: #1e88e5;
  border: none;
  border-radius: 25px;
  padding: 8px 20px;
  transition: background-color 0.3s ease;
}

.btn-primary:hover {
  background-color: #1565c0;
}

footer {
  background-color: #2c3e50;
  font-size: 0.9rem;
}

.navbar-brand span {
  font-size: 1.3rem;
  font-weight: 600;
  color: #f1f1f1;
}

.nav-link {
  color: #ddd !important;
  transition: color 0.3s ease;
}

.nav-link:hover {
  color: #ffffff !important;
}

@media (max-width: 768px) {
  .card-img-top {
    height: 180px;
  }

  .header h1 {
    font-size: 2.4rem;
  }
}
```




## OUTPUT:
![Screenshot 2025-05-20 122830](https://github.com/user-attachments/assets/6e6553df-5b8f-420b-ba63-09ad16f47f22)

![Screenshot 2025-05-20 122909](https://github.com/user-attachments/assets/6b46439b-4966-4271-96b0-8608e6881ac8)


![Screenshot 2025-05-20 123125](https://github.com/user-attachments/assets/d9d2b031-e7b5-443f-b044-68db188ac5cf)


![Screenshot 2025-05-20 123221](https://github.com/user-attachments/assets/a41ce176-6bbe-4db0-836b-e54b40ef7148)






## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
