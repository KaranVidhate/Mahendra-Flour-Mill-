# Mahendra-Flour-Mill-
Mahendra Flour Mill – Fresh and nutritious wheat flour ground on traditional stone chakki for soft and tasty rotis.
<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mahendra Flour Mill</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
  <style>
    body { font-family: 'Poppins', sans-serif; margin:0; padding:0; }
    header { background:#6b3e26; color:white; padding:15px; text-align:center; }
    nav { display:flex; justify-content:center; background:#8b5a2b; flex-wrap:wrap; }
    nav a { color:white; padding:10px 15px; text-decoration:none; }
    nav a:hover { background:#6b3e26; }
    .hero { background:url('https://images.unsplash.com/photo-1604908176997-125f25cc6f3d'); background-size:cover; color:white; text-align:center; padding:100px 20px; }
    .section { padding:40px 20px; text-align:center; }
    .products { display:flex; flex-wrap:wrap; justify-content:center; gap:20px; }
    .card { border:1px solid #ddd; padding:20px; width:250px; border-radius:10px; }
    footer { background:#333; color:white; text-align:center; padding:15px; }
    button { background:#6b3e26; color:white; border:none; padding:10px 20px; border-radius:5px; cursor:pointer; }
    .lang-toggle { position:absolute; top:10px; right:10px; }
    iframe { width:100%; height:300px; border:0; }
  </style>
  <script>
    function toggleLanguage() {
      const en = document.querySelectorAll('.en');
      const mr = document.querySelectorAll('.mr');
      en.forEach(e => e.style.display = e.style.display === 'none' ? 'block' : 'none');
      mr.forEach(e => e.style.display = e.style.display === 'none' ? 'block' : 'none');
    }
  </script>
</head>
<body><header>
  <h1>Mahendra Flour Mill</h1>
  <p class="en">Fresh • Pure • Stone Ground Flour</p>
  <p class="mr" style="display:none;">ताजे • शुद्ध • पारंपरिक दळलेले पीठ</p>
  <button class="lang-toggle" onclick="toggleLanguage()">EN / मराठी</button>
</header><nav>
  <a href="#home">Home</a>
  <a href="#about">About</a>
  <a href="#products">Products</a>
  <a href="#contact">Contact</a>
</nav><section class="hero" id="home">
  <h2 class="en">Healthy Flour for Healthy Life</h2>
  <h2 class="mr" style="display:none;">आरोग्यदायी जीवनासाठी उत्तम पीठ</h2>
  <p class="en">We provide high-quality stone-ground wheat flour.</p>
  <p class="mr" style="display:none;">आम्ही पारंपरिक पद्धतीने दळलेले पौष्टिक पीठ देतो.</p>
  <a href="https://wa.me/917420033083"><button>Order on WhatsApp</button></a>
</section><section class="section" id="about">
  <h2>About Us</h2>
  <p class="en">Mahendra Flour Mill provides fresh and hygienic flour using traditional stone grinding methods.</p>
  <p class="mr" style="display:none;">महेंद्र फ्लोअर मिल पारंपरिक दगडी गिरणीतून ताजे आणि स्वच्छ पीठ तयार करते.</p>
</section><section class="section" id="products">
  <h2>Our Products</h2>
  <div class="products">
    <div class="card">
      <h3>Wheat Flour</h3>
      <p>Fresh Chakki Atta</p>
    </div>
  </div>
</section><section class="section" id="contact">
  <h2>Contact Us</h2>
  <p>Phone: 7420033083</p>
  <p>Email: mahendraflourmill@gmail.com</p>
  <p>Address: Your Location Here</p>
  <iframe src="https://maps.app.goo.gl/2fSpi9TACX37Rn228?g_st=ac"></iframe>
</section><footer>
  <p>© 2026 Mahendra Flour Mill</p>
</footer></body>
</html>
