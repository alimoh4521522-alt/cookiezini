[abc.index.html](https://github.com/user-attachments/files/24522217/abc.index.html)
[Uploading abc.<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Cookiezini | Premium Cookies</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
  <div class="logo">🍪 Cookiezini</div>
  <nav>
    <a href="index.html">Home</a>
    <a href="cookies.html">Cookies</a>
    <a href="about.html">About</a>
    <a href="order.html">Order</a>
    <a href="contact.html">Contact</a>
  </nav>
  <button id="langToggle">AR</button>
</header>

<section class="hero">[abc.css](https://github.com/user-attachments/files/24522218/abc.css)
body {
  margin: 0;
  font-family: 'Poppins', sans-serif;
  background: #f8f1e7;
  color: #3b2a1a;
}

header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px 40px;
  background: #3b2a1a;
  color: #fff;
}

nav a {
  margin: 0 15px;
  color: #fff;
  text-decoration: none;
}

.hero {
  text-align: center;
  padding: 120px 20px;
  background: linear-gradient(#f8f1e7, #e6d3b3);
}

.hero h1 {
  font-size: 48px;
}

.btn {
  background: #3b2a1a;
  color: #fff;
  padding: 15px 30px;
  text-decoration: none;
  border-radius: 30px;
}

.whatsapp {
  position: fixed;
  bottom: 20px;
  right: 20px;
  background: #25D366;
  color: #fff;
  padding: 15px 20px;
  border-radius: 50px;
  text-decoration: none;
}



🌍 script.js (Language Toggle – basic)

const toggle = document.getElementById("langToggle");
let arabic = false;

toggle.onclick = () => {
  arabic = !arabic;
  document.body.dir = arabic ? "rtl" : "ltr";
  toggle.innerText = arabic ? "EN" : "AR";
};
  <h1>Freshly Baked. Premium Taste.</h1>
  <p>Handcrafted cookies made with love.</p>
  <a class="btn" href="order.html">Order Now</a>
</section>

<a class="whatsapp" href="https://wa.me/201091063009" target="_blank">
  WhatsApp Order
</a>

<script src="script.js"></script>
</body>
</html>


index.html…]()
