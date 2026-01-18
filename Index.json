<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>NovaPods Pro</title>
<meta name="viewport" content="width=device-width, initial-scale=1">

<style>
:root {
  --bg:#0b0b10;
  --card:#15151c;
  --border:#24242c;
  --text:#f5f5f7;
  --muted:#9a9aa5;
  --accent:#0a84ff;
}

* { box-sizing:border-box; }

body {
  margin:0;
  font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Inter,Roboto,sans-serif;
  background:var(--bg);
  color:var(--text);
}

header {
  position:sticky;
  top:0;
  z-index:10;
  display:flex;
  justify-content:space-between;
  align-items:center;
  padding:18px 7%;
  border-bottom:1px solid var(--border);
  background:rgba(11,11,16,0.85);
  backdrop-filter:blur(10px);
}

header h1 {
  font-size:18px;
  font-weight:600;
}

nav a {
  color:var(--muted);
  text-decoration:none;
  margin-left:22px;
  font-size:14px;
}

nav a:hover { color:var(--text); }

.hero {
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:60px;
  padding:90px 7%;
  align-items:center;
}

.hero img {
  width:100%;
  max-width:420px;
  border-radius:22px;
  background:#222;
}

.hero h2 {
  font-size:42px;
  margin:0 0 14px;
}

.hero p {
  color:var(--muted);
  max-width:480px;
  line-height:1.6;
}

.price {
  font-size:30px;
  margin:26px 0;
}

.button {
  padding:14px 30px;
  border-radius:999px;
  background:var(--accent);
  color:white;
  border:none;
  font-size:15px;
  cursor:pointer;
}

section {
  padding:70px 7%;
}

.features {
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(240px,1fr));
  gap:28px;
}

.card {
  background:var(--card);
  border:1px solid var(--border);
  border-radius:20px;
  padding:26px;
}

.card h3 {
  margin-top:0;
  font-size:18px;
}

.card p {
  color:var(--muted);
  line-height:1.6;
}

.reviews {
  display:grid;
  gap:26px;
}

.stars {
  color:#ffd60a;
  font-size:14px;
  margin:8px 0;
}

/* CART / CHECKOUT */
.cart {
  position:fixed;
  inset:0;
  background:rgba(0,0,0,0.6);
  display:none;
  justify-content:center;
  align-items:center;
}

.cart-box {
  background:var(--card);
  border-radius:22px;
  width:90%;
  max-width:420px;
  padding:26px;
  border:1px solid var(--border);
}

.cart-box h3 {
  margin-top:0;
}

.cart-item {
  display:flex;
  justify-content:space-between;
  margin:20px 0;
  color:var(--muted);
}

.cart-total {
  display:flex;
  justify-content:space-between;
  font-size:18px;
  margin:24px 0;
}

input {
  width:100%;
  padding:12px;
  border-radius:12px;
  border:1px solid var(--border);
  background:#0f0f15;
  color:var(--text);
  margin-bottom:14px;
}

footer {
  border-top:1px solid var(--border);
  padding:40px;
  text-align:center;
  font-size:13px;
  color:var(--muted);
}

/* Mobile */
@media (max-width:900px) {
  .hero { grid-template-columns:1fr; text-align:center; }
  .hero img { margin:auto; }
}
</style>
</head>

<body>

<header>
  <h1>NovaPods</h1>
  <nav>
    <a href="#features">Features</a>
    <a href="#reviews">Reviews</a>
    <a href="#" onclick="openCart()">Cart</a>
  </nav>
</header>

<div class="hero">
  <img src="https://dummyimage.com/800x800/1a1a1f/ffffff&text=NovaPods+Pro">
  <div>
    <h2>NovaPods Pro</h2>
    <p>
      Designed for everyday listening with balanced sound, deep bass,
      and a comfortable in-ear fit. NovaPods Pro combines performance
      and minimal design without unnecessary distractions.
    </p>
    <div class="price">$129</div>
    <button class="button" onclick="openCart()">Add to Cart</button>
  </div>
</div>

<section id="features">
  <div class="features">
    <div class="card">
      <h3>Active Noise Control</h3>
      <p>
        Dual microphones work together to reduce background noise,
        helping you stay focused whether you're commuting or working.
      </p>
    </div>
    <div class="card">
      <h3>24-Hour Battery Life</h3>
      <p>
        Up to 6 hours on a single charge and multiple recharges
        from the compact case.
      </p>
    </div>
    <div class="card">
      <h3>Instant Pairing</h3>
      <p>
        Seamless pairing with supported devices the moment you open
        the case.
      </p>
    </div>
  </div>
</section>

<section id="reviews">
  <h2 style="margin-bottom:34px;">Customer Reviews</h2>

  <div class="reviews">
    <div class="card">
      <strong>Alex M.</strong>
      <div class="stars">★★★★★</div>
      <p>
        I’ve been using these daily for about two weeks now and I’m honestly
        surprised by how good they sound for the price. The bass is punchy
        without overpowering vocals, and they’re comfortable enough that I
        forget I’m wearing them during long sessions.
      </p>
    </div>

    <div class="card">
      <strong>Jordan R.</strong>
      <div class="stars">★★★★☆</div>
      <p>
        Setup was quick and painless, and connection has been solid so far.
        Battery easily lasts me through the workday. Noise control isn’t
        absolute silence, but it does a great job cutting down background
        noise in public places.
      </p>
    </div>

    <div class="card">
      <strong>Sam T.</strong>
      <div class="stars">★★★★★</div>
      <p>
        Clean design, good fit, and no weird audio dropouts. I mainly use
        them for music and calls, and people say my voice comes through
        clearly. Overall they feel well-built and premium.
      </p>
    </div>
  </div>
</section>

<footer>
  © 2026 NovaPods
</footer>

<!-- CART / CHECKOUT -->
<div class="cart" id="cart">
  <div class="cart-box">
    <h3>Checkout</h3>

    <div class="cart-item">
      <span>NovaPods Pro</span>
      <span>$129</span>
    </div>

    <div class="cart-total">
      <strong>Total</strong>
      <strong>$129</strong>
    </div>

    <input placeholder="Full Name">
    <input placeholder="Email Address">
    <input placeholder="Shipping Address">
    <input placeholder="Card Number">

    <button class="button" style="width:100%;margin-top:10px;">
      Place Order
    </button>

    <p style="margin-top:14px;text-align:center;">
      <a href="#" onclick="closeCart()" style="color:var(--muted);text-decoration:none;">Cancel</a>
    </p>
  </div>
</div>

<script>
function openCart() {
  document.getElementById('cart').style.display = 'flex';
}
function closeCart() {
  document.getElementById('cart').style.display = 'none';
}
</script>

</body>
</html>
