# geldaufkonto.github.io
<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Innovative Produkte</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { font-family: 'Inter', sans-serif; background: #f8f9fa; color: #212529; scroll-behavior: smooth; }
    header { background: #ffffff; padding: 20px 40px; box-shadow: 0 2px 4px rgba(0,0,0,0.05); display: flex; justify-content: space-between; align-items: center; }
    header h1 { font-size: 24px; color: #111827; }
    nav a { margin-left: 20px; text-decoration: none; color: #374151; font-weight: 500; }
    .hero { text-align: center; padding: 100px 20px; background: linear-gradient(to right, #6366f1, #3b82f6); color: white; animation: fadeIn 1.5s ease-in-out; }
    .hero h2 { font-size: 48px; margin-bottom: 20px; }
    .hero p { font-size: 18px; margin-bottom: 30px; }
    .hero a { background: white; color: #3b82f6; padding: 12px 24px; border-radius: 8px; text-decoration: none; font-weight: 600; transition: background 0.3s; }
    .hero a:hover { background: #e0e7ff; }
    .products { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 30px; padding: 60px 40px; }
    .product { background: white; border-radius: 12px; padding: 20px; box-shadow: 0 2px 10px rgba(0,0,0,0.05); text-align: center; transition: transform 0.3s; }
    .product:hover { transform: translateY(-5px); }
    .product img { max-width: 100%; border-radius: 8px; }
    .product h3 { margin: 15px 0 10px; font-size: 20px; }
    .product p { font-size: 14px; color: #6b7280; }
    .newsletter { background: #ffffff; padding: 60px 20px; text-align: center; }
    .newsletter h2 { font-size: 32px; margin-bottom: 20px; color: #111827; }
    .newsletter input[type="email"] { padding: 12px; width: 250px; max-width: 100%; border: 1px solid #d1d5db; border-radius: 8px; margin-right: 10px; }
    .newsletter button { padding: 12px 20px; background: #3b82f6; color: white; border: none; border-radius: 8px; font-weight: 600; cursor: pointer; transition: background 0.3s; }
    .newsletter button:hover { background: #2563eb; }
    footer { text-align: center; padding: 40px 20px; background: #111827; color: #d1d5db; }
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>
  <header>
    <h1>Innovativ24</h1>
    <nav>
      <a href="#products">Produkte</a>
      <a href="#newsletter">Newsletter</a>
      <a href="#contact">Kontakt</a>
    </nav>
  </header>
  <section class="hero">
    <h2>Entdecke die Produkte von morgen</h2>
    <p>Wir bringen Innovationen auf den Markt – einfach, schnell, zuverlässig.</p>
    <a href="#products">Jetzt entdecken</a>
  </section>
  <section id="products" class="products">
    <div class="product">
      <img src="https://via.placeholder.com/300x200" alt="Produkt 1">
      <h3>Smart Bottle</h3>
      <p>Die Flasche, die dein Trinkverhalten analysiert.</p>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/300x200" alt="Produkt 2">
      <h3>EcoBrush</h3>
      <p>Nachhaltige Zahnbürste mit Wechselkopf-Technologie.</p>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/300x200" alt="Produkt 3">
      <h3>AirClean Mini</h3>
      <p>Mobiler Luftreiniger fürs Büro oder unterwegs.</p>
    </div>
  </section>
  <section id="newsletter" class="newsletter">
    <h2>Newsletter abonnieren</h2>
    <form>
      <input type="email" placeholder="Deine E-Mail-Adresse" required>
      <button type="submit">Abonnieren</button>
    </form>
  </section>
  <footer id="contact">
    <p>&copy; 2025 Innovativ24 – Alle Rechte vorbehalten.</p>
  </footer>
</body>
</html>
