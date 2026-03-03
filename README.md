<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sim’s Urban Gallery</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
body{
  margin:0;
  font-family:'Poppins',sans-serif;
  background:#fdf6ec; /* light cream */
  color:#333;
}

/* HEADER */
header{
  background:#1e3a5f; /* elegant blue */
  color:white;
  padding:15px 30px;
  display:flex;
  justify-content:space-between;
  align-items:center;
  flex-wrap:wrap;
}

.logo-area{
  display:flex;
  align-items:center;
  gap:15px;
}

.logo-area img{
  height:55px;
}

.brand{
  font-size:20px;
  font-weight:700;
}

.tagline{
  font-size:12px;
  opacity:0.8;
}

.contact-btn{
  background:white;
  color:#1e3a5f;
  padding:8px 18px;
  border-radius:20px;
  text-decoration:none;
  font-weight:600;
}

/* HERO */
.hero{
  text-align:center;
  padding:70px 20px;
  background:#e8f1fa;
}

.hero h1{
  font-size:34px;
  color:#1e3a5f;
  margin-bottom:10px;
}

.hero p{
  font-size:16px;
  margin-bottom:20px;
}

.hero a{
  display:inline-block;
  padding:12px 25px;
  background:#1e3a5f;
  color:white;
  text-decoration:none;
  border-radius:25px;
  margin:8px;
  transition:0.3s;
}

.hero a:hover{
  background:#16304d;
}

/* PRODUCTS */
.products{
  display:flex;
  flex-wrap:wrap;
  justify-content:center;
  gap:30px;
  padding:60px 20px;
}

.card{
  background:white;
  width:260px;
  padding:15px;
  border-radius:15px;
  box-shadow:0 8px 20px rgba(0,0,0,0.08);
  text-align:center;
  transition:0.3s;
}

.card:hover{
  transform:translateY(-6px);
}

.card img{
  width:100%;
  height:220px;
  object-fit:cover;
  border-radius:10px;
}

.card h3{
  margin:12px 0 8px;
  color:#1e3a5f;
}

.card p{
  font-size:14px;
}

.card a{
  display:inline-block;
  margin-top:10px;
  padding:8px 18px;
  background:#1e3a5f;
  color:white;
  text-decoration:none;
  border-radius:20px;
}

/* FOOTER */
footer{
  background:#1e3a5f;
  color:white;
  text-align:center;
  padding:25px;
}
</style>
</head>

<body>

<header>
  <div class="logo-area">
    <!-- Upload your logo file and name it logo.png -->
    <img src="logo.png" alt="Logo">
    <div>
      <div class="brand">Sim’s Urban Gallery</div>
      <div class="tagline">Celebrating Style, Bringing Elegance Home.</div>
    </div>
  </div>

  <a href="tel:+918809941608" class="contact-btn">Call Now</a>
</header>

<section class="hero">
  <h1>Premium Ladies Collection</h1>
  <p>Dresses • Burqhas • Bed Sheets • Marriage Mosquito Nets</p>
  <p>📞 +91 88099 41608</p>

  <a href="https://wa.me/918809941608">WhatsApp Us</a>
  <a href="tel:+918809941608">Call Now</a>
</section>

<section class="products">

  <div class="card">
    <img src="https://images.unsplash.com/photo-1593032465171-8b2e0c44d3ad">
    <h3>Indian Dresses</h3>
    <p>Premium quality stylish collections for every occasion.</p>
    <a href="https://wa.me/918809941608">Enquire Now</a>
  </div>

  <div class="card">
    <img src="https://images.unsplash.com/photo-1583394838336-acd977736f90">
    <h3>Premium Burqhas</h3>
    <p>Elegant, modest and comfortable designs.</p>
    <a href="https://wa.me/918809941608">Enquire Now</a>
  </div>

  <div class="card">
    <img src="https://images.unsplash.com/photo-1600585154340-be6161a56a0c">
    <h3>Designer Bed Sheets</h3>
    <p>Soft fabric with luxury finish for your home.</p>
    <a href="https://wa.me/918809941608">Enquire Now</a>
  </div>

  <div class="card">
    <img src="https://images.unsplash.com/photo-1621897463908-7f86b36d5e7e">
    <h3>Marriage Mosquito Nets</h3>
    <p>Beautiful decorative wedding collections.</p>
    <a href="https://wa.me/918809941608">Enquire Now</a>
  </div>

</section>

<footer>
  © 2026 Sim’s Urban Gallery  
  <br> 📞 +91 88099 41608
</footer>

</body>
</html>
