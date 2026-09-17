<html lang="en">

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="Velvet Crumb - handcrafted premium cakes baked fresh for every celebration.">
<title>Velvet Crumb | Premium Cakes & Desserts</title>
@import url('https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700&family=Playfair+Display:wght@400;500;600&display=swap');
:root{
  --cream:#fffaf3;
  --paper:#fffdf9;
  --ink:#29231f;
  --muted:#746961;
  --accent:#9c5f4d;
  --accent-dark:#754235;
  --rose:#ead4ca;
  --gold:#c79b62;
  --line:#eadfd5;
  --shadow:0 24px 70px rgba(62,39,25,.13)}
*{box-sizing:border-box;margin:23%;padding:0}
html{scroll-behavior:smooth}
body{font-family:"DM Sans",sans-serif;background:var(--cream);color:var(--ink);line-height:1.6}
a{text-decoration:none;color:inherit}
button{font:inherit}
.container{width:min(1180px,92%);margin:auto}
header{
  position:fixed;top:0;left:0;right:0;z-index:20;
  background:rgba(255,250,243,.86);backdrop-filter:blur(18px);
  border-bottom:1px solid rgba(234,223,213,.8)
}
.nav{height:78px;display:flex;align-items:center;justify-content:space-between;gap:30px}
.logo{font-family:"Playfair Display",serif;font-size:28px;font-weight:700;letter-spacing:-.5px}
.logo span{color:var(--accent)}
.navlinks{display:flex;gap:30px;font-size:14px;color:#4e4540}
.navlinks a:hover{color:var(--accent)}
.navbtn,.hero-btn,.order-btn{
  display:inline-flex;align-items:center;justify-content:center;
  background:var(--ink);color:#fff;border:0;border-radius:999px;
  padding:13px 22px;font-weight:600;cursor:pointer;transition:.25s
}
.navbtn:hover,.hero-btn:hover,.order-btn:hover{transform:translateY(-2px);background:var(--accent-dark)}
.hero{
  min-height:100vh;padding-top:78px;display:grid;place-items:center;
  background:
   radial-gradient(circle at 85% 20%,rgba(234,212,202,.8),transparent 30%),
   radial-gradient(circle at 12% 80%,rgba(199,155,98,.12),transparent 28%);
  overflow:hidden
}
.hero-grid{display:grid;grid-template-columns:1fr 1fr;align-items:center;gap:55px;padding:70px 0}
.eyebrow{text-transform:uppercase;letter-spacing:3px;font-size:12px;font-weight:700;color:var(--accent);margin-bottom:18px}
h1{font-family:"Playfair Display",serif;font-size:clamp(52px,7vw,92px);line-height:.98;letter-spacing:-3px;max-width:720px}
h1 em{font-style:italic;color:var(--accent)}
.hero p{max-width:540px;color:var(--muted);font-size:17px;margin:26px 0 30px}
.hero-actions{display:flex;gap:13px;flex-wrap:wrap}
.hero-btn{padding:15px 26px}
.secondary{background:transparent;color:var(--ink);border:1px solid var(--line)}
.secondary:hover{background:#fff}
.hero-visual{position:relative;min-height:570px}
.cake-photo{
  position:absolute;inset:20px 0 0 35px;border-radius:45% 45% 18px 18px;
  background:
   linear-gradient(180deg,rgba(255,255,255,.02),rgba(0,0,0,.1)),
   url("https://images.unsplash.com/photo-1578985545062-69928b1d9587?auto=format&fit=crop&w=1600&q=90") center/cover;
  box-shadow:var(--shadow);transform:rotate(2deg)
}
.badge{
  position:absolute;left:-15px;bottom:50px;background:rgba(255,253,249,.94);
  border:1px solid var(--line);border-radius:50%;width:145px;height:145px;
  display:grid;place-items:center;text-align:center;padding:20px;font-family:"Playfair Display",serif;
  box-shadow:0 15px 40px rgba(62,39,25,.12)
}
.section{padding:110px 0}
.section-head{text-align:center;max-width:700px;margin:0 auto 50px}
.section-head h2{font-family:"Playfair Display",serif;font-size:clamp(38px,5vw,58px);line-height:1.05}
.section-head p{color:var(--muted);margin-top:14px}
.cakes{display:grid;grid-template-columns:repeat(3,1fr);gap:22px}
.card{background:var(--paper);border:1px solid var(--line);border-radius:24px;overflow:hidden;transition:.3s}
.card:hover{transform:translateY(-8px);box-shadow:var(--shadow)}
.card-img{height:310px;background-size:cover;background-position:center}
.card-body{padding:23px}
.card-body h3{font-family:"Playfair Display",serif;font-size:25px}
.card-body p{color:var(--muted);font-size:14px;margin:7px 0 17px}
.price-row{display:flex;align-items:center;justify-content:space-between}
.price{font-weight:700;font-size:18px}
.small-btn{border:1px solid var(--line);background:#fff;border-radius:999px;padding:9px 15px;cursor:pointer}
.small-btn:hover{border-color:var(--accent);color:var(--accent)}
.story{background:#2d2521;color:white}
.story-grid{display:grid;grid-template-columns:1fr 1fr;gap:70px;align-items:center}
.story-img{
  min-height:520px;border-radius:28px;background:
  url("https://images.unsplash.com/photo-1551024506-0bccd828d307?auto=format&fit=crop&w=1400&q=90") center/cover;
}
.story h2{font-family:"Playfair Display",serif;font-size:clamp(40px,5vw,62px);line-height:1.05}
.story p{color:#d8cec7;margin:20px 0;max-width:520px}
.points{display:grid;grid-template-columns:1fr 1fr;gap:18px;margin-top:30px}
.point{border-top:1px solid #5c5049;padding-top:14px}
.point strong{display:block;color:#fff}
.point span{font-size:13px;color:#bcaea5}
.gallery{display:grid;grid-template-columns:1.3fr .7fr .9fr;grid-template-rows:250px 250px;gap:14px}
.gallery div{border-radius:20px;background-size:cover;background-position:center}
.g1{grid-row:1/3;background-image:url("https://images.unsplash.com/photo-1571115177098-24ec42ed204d?auto=format&fit=crop&w=1200&q=90")}
.g2{background-image:url("https://images.unsplash.com/photo-1602351447937-745cb720612f?auto=format&fit=crop&w=900&q=90")}
.g3{background-image:url("https://images.unsplash.com/photo-1588195538326-c5b1e0a4f1f3?auto=format&fit=crop&w=900&q=90")}
.g4{grid-column:2/4;background-image:url("https://images.unsplash.com/photo-1488477181946-6428a0291777?auto=format&fit=crop&w=1200&q=90")}
.reviews{display:grid;grid-template-columns:repeat(3,1fr);gap:20px}
.review{padding:28px;background:#fff;border:1px solid var(--line);border-radius:22px}
.stars{color:var(--gold);letter-spacing:3px}
.review p{margin:15px 0;color:#5d544e}
.review b{font-size:14px}
.cta{
  margin-bottom:80px;border-radius:30px;padding:75px 30px;text-align:center;color:#fff;
  background:linear-gradient(135deg,#8e5142,#bb7c68)
}
.cta h2{font-family:"Playfair Display",serif;font-size:clamp(40px,5vw,62px)}
.cta p{margin:12px auto 25px;max-width:600px;color:#f8e9e2}
.cta .hero-btn{background:#fff;color:#302824}
footer{padding:35px 0;border-top:1px solid var(--line);font-size:13px;color:var(--muted)}
.footer{display:flex;justify-content:space-between;gap:20px;flex-wrap:wrap}
.toast{
  position:fixed;bottom:25px;left:50%;transform:translate(-50%,20px);
  background:#29231f;color:white;padding:13px 20px;border-radius:999px;
  opacity:0;pointer-events:none;transition:.3s;z-index:50
}
.toast.show{opacity:1;transform:translate(-50%,0)}
@media(max-width:850px){
  .navlinks{display:none}
  .hero-grid,.story-grid{grid-template-columns:1fr}
  .hero{min-height:auto}
  .hero-grid{padding:65px 0 85px}
  .hero-visual{min-height:430px}
  .cake-photo{inset:15px 5% 0}
  .cakes,.reviews{grid-template-columns:1fr}
  .gallery{grid-template-columns:1fr 1fr;grid-template-rows:220px 220px 220px}
  .g1{grid-row:auto}
  .g4{grid-column:auto}
}
@media(max-width:520px){
  h1{letter-spacing:-2px}
  .nav{height:68px}
  .hero{padding-top:68px}
  .hero-visual{min-height:350px}
  .badge{width:110px;height:110px;font-size:13px}
  .section{padding:80px 0}
  .points{grid-template-columns:1fr}
}
</style>
</head>
<body>
<header>
  <div class="container nav">
    <a class="logo" href="#">Velvet <span>Crumb</span></a>
    <nav class="navlinks">
      <a href="#cakes">Cakes</a>
      <a href="#story">Our Story</a>
      <a href="#gallery">Gallery</a>
      <a href="#reviews">Reviews</a>
    </nav>
    <a class="navbtn" href="#order">Order a Cake</a>
  </div>
</header>

<main>
<section class="hero">
  <div class="container hero-grid">
    <div>
      <div class="eyebrow">Handcrafted • Fresh Daily • Made With Love</div>
      <h1>Cakes made for <em>beautiful</em> moments.</h1>
      <p>Elegant celebration cakes, dreamy desserts and handcrafted pastries, baked fresh in small batches for the people and moments that matter most.</p>
      <div class="hero-actions">
        <a class="hero-btn" href="#cakes">Explore Cakes</a>
        <a class="hero-btn secondary" href="#story">Discover Our Story</a>
      </div>
    </div>
    <div class="hero-visual">
      <div class="cake-photo" aria-label="Premium chocolate cake"></div>
      <div class="badge">Baked fresh<br>every morning<br>✦</div>
      </div>
<section class="section" id="cakes">
  <div class="container">
    <div class="section-head">
      <div class="eyebrow">The Signature Collection</div>
      <h2>Your next favourite cake is waiting.</h2>
      <p>From timeless classics to modern showstoppers, every cake is finished by hand.</p>
    </div>
    <div class="cakes">
      <article class="card">
        <div class="card-img" style="background-image:url('https://images.unsplash.com/photo-1578985545062-69928b1d9587?auto=format&fit=crop&w=1200&q=90')"></div>
        <div class="card-body"><h3>Velvet Chocolate</h3><p>Dark chocolate sponge, silky ganache and a delicate cocoa finish.</p><div class="price-row"><span class="price">₹1,499</span><button class="small-btn" onclick="order('Velvet Chocolate')">Order</button></div></div>
      </article>
      <article class="card">
        <div class="card-img" style="background-image:url('https://images.unsplash.com/photo-1535141192574-5d4897c12636?auto=format&fit=crop&w=1200&q=90')"></div>
        <div class="card-body"><h3>Strawberry Cloud</h3><p>Vanilla chiffon, fresh strawberries and clouds of whipped cream.</p><div class="price-row"><span class="price">₹1,599</span><button class="small-btn" onclick="order('Strawberry Cloud')">Order</button></div></div>
      </article>
      <article class="card">
        <div class="card-img" style="background-image:url('https://images.unsplash.com/photo-1551024506-0bccd828d307?auto=format&fit=crop&w=1200&q=90')"></div>
        <div class="card-body"><h3>Golden Caramel</h3><p>Buttery caramel, vanilla sponge and a glossy salted caramel crown.</p><div class="price-row"><span class="price">₹1,699</span><button class="small-btn" onclick="order('Golden Caramel')">Order</button></div></div>
      </article>
    </div>
  </div>
</section>

<section class="section story" id="story">
  <div class="container story-grid">
    <div class="story-img"></div>
    <div>
      <div class="eyebrow" style="color:#d9aa91">Made the old-fashioned way</div>
      <h2>Simple ingredients. Serious cake.</h2>
      <p>We believe the best cakes start with real butter, premium chocolate, fresh fruit and enough time to get every detail right.</p>
      <div class="points">
        <div class="point"><strong>100% Fresh</strong><span>Baked in small batches every day.</span></div>
        <div class="point"><strong>Hand Finished</strong><span>Every decoration gets a personal touch.</span></div>
        <div class="point"><strong>Custom Orders</strong><span>Designed around your celebration.</span></div>
        <div class="point"><strong>Premium Ingredients</strong><span>Nothing artificial where it matters.</span></div>
      </div>
    </div>
  </div>
</section>

<section class="section" id="gallery">
  <div class="container">
    <div class="section-head">
      <div class="eyebrow">A little cake inspiration</div>
      <h2>Made to be remembered.</h2>
    </div>
    <div class="gallery">
      <div class="g1"></div><div class="g2"></div><div class="g3"></div><div class="g4"></div>
    </div>
  </div>
</section>

<section class="section" id="reviews">
  <div class="container">
    <div class="section-head">
      <div class="eyebrow">Sweet words</div>
      <h2>Loved at first bite.</h2>
    </div>
    <div class="reviews">
      <article class="review"><div class="stars">★★★★★</div><p>“The chocolate cake was unbelievably soft and rich. It looked gorgeous and tasted even better.”</p><b> Denish Murry.</b></article>
      <article class="review"><div class="stars">★★★★★</div><p>“The perfect birthday cake. Beautiful presentation, fresh ingredients and genuinely lovely service.”</p><b>Vilika Sumi.</b></article>
      <article class="review"><div class="stars">★★★★★</div><p>“I ordered a custom cake and the final result was stunning. Everyone asked where it came from!”</p><b>Jency Puro.</b></article>
    </div>
  </div>
</section>

<section class="container" id="order">
  <div class="cta">
    <div class="eyebrow" style="color:#f6d5c7">Your celebration starts here</div>
    <h2>Let's bake something unforgettable.</h2>
    <p>Tell us what you're celebrating and we'll help you choose or create the perfect cake.</p>
    <button class="hero-btn" onclick="order('Custom Cake')">Start Your Order</button>
  </div>
</section>
</main>

<footer>
  <div class="container footer">
    <div><strong>Velvet Crumb</strong> · Premium Cakes & Desserts</div>
    <div>Freshly baked in Dimapur, Nagaland · Open daily 9 AM – 6 PM</div>
    <div>© <span id="year"></span> Velvet Crumb</div>
  </div>
</footer>

<div class="toast" id="toast"></div>
<script>
document.getElementById("year").textContent = new Date().getFullYear();
function order(name){
  const toast=document.getElementById("toast");
  toast.textContent="Thanks! Your "+name+" enquiry has been started. 🍰";
  toast.classList.add("show");
  setTimeout(()=>toast.classList.remove("show"),3200);
}
</script>
</body>
</html>
