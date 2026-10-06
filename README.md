<!DOCTYPE html>
<html lang="kk">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Жиһаз | Жеке тапсырыспен жиһаз жасау</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background: #f7f5f1;
    color: #222;
    line-height: 1.5;
}

.container {
    width: min(1180px, 92%);
    margin: auto;
}

/* HEADER */

header {
    position: absolute;
    width: 100%;
    top: 0;
    z-index: 10;
    padding: 25px 0;
}

.nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    font-size: 25px;
    font-weight: 700;
    letter-spacing: 2px;
}

nav {
    display: flex;
    gap: 30px;
}

nav a {
    color: white;
    text-decoration: none;
    font-size: 15px;
}

/* HERO */

.hero {
    min-height: 720px;
    display: flex;
    align-items: center;
    color: white;

    background:
    linear-gradient(rgba(0,0,0,.48), rgba(0,0,0,.48)),
    url("https://images.unsplash.com/photo-1600607687920-4e2a09cf159d?auto=format&fit=crop&w=2000&q=90")
    center/cover;
}

.hero-content {
    max-width: 720px;
    padding-top: 60px;
}

.hero h1 {
    font-size: clamp(42px, 6vw, 76px);
    line-height: 1.05;
    margin-bottom: 25px;
}

.hero p {
    font-size: 20px;
    max-width: 600px;
    margin-bottom: 35px;
}

.buttons {
    display: flex;
    gap: 15px;
    flex-wrap: wrap;
}

.btn {
    display: inline-block;
    padding: 16px 28px;
    border-radius: 50px;
    text-decoration: none;
    font-weight: 600;
    transition: .3s;
}

.btn-primary {
    background: #222;
    color: white;
}

.btn-primary:hover {
    transform: translateY(-3px);
}

.btn-light {
    background: white;
    color: #222;
}

/* SECTIONS */

section {
    padding: 100px 0;
}

.section-title {
    font-size: 45px;
    margin-bottom: 15px;
}

.section-subtitle {
    color: #777;
    margin-bottom: 45px;
}

/* PRODUCTS */

.products {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 22px;
}

.card {
    background: white;
    border-radius: 22px;
    overflow: hidden;
    transition: .3s;
}

.card:hover {
    transform: translateY(-7px);
}

.card img {
    width: 100%;
    height: 280px;
    object-fit: cover;
}

.card-content {
    padding: 25px;
}

.card h3 {
    font-size: 23px;
    margin-bottom: 8px;
}

.card p {
    color: #777;
}

/* ABOUT */

.about {
    background: #ebe7df;
}

.about-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 60px;
    align-items: center;
}

.about img {
    width: 100%;
    border-radius: 25px;
}

.about-text p {
    color: #666;
    margin: 20px 0;
}

.features {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 20px;
    margin-top: 30px;
}

.feature {
    font-weight: 600;
}

/* STEPS */

.steps {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 20px;
}

.step {
    background: white;
    padding: 30px;
    border-radius: 20px;
}

.number {
    font-size: 42px;
    font-weight: 700;
    color: #b3a48d;
    margin-bottom: 20px;
}

/* PORTFOLIO */

.portfolio {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 15px;
}

.portfolio img {
    width: 100%;
    height: 320px;
    object-fit: cover;
    border-radius: 18px;
}

/* CTA */

.cta {
    background: #222;
    color: white;
    text-align: center;
}

.cta h2 {
    font-size: 48px;
    margin-bottom: 20px;
}

.cta p {
    color: #ccc;
    margin-bottom: 30px;
}

/* FOOTER */

footer {
    background: #151515;
    color: white;
    padding: 40px 0;
}

.footer {
    display: flex;
    justify-content: space-between;
    gap: 30px;
}

/* MOBILE */

@media (max-width: 800px) {

    nav {
        display: none;
    }

    .hero {
        min-height: 650px;
    }

    .hero h1 {
        font-size: 45px;
    }

    .products,
    .portfolio {
        grid-template-columns: 1fr;
    }

    .about-grid {
        grid-template-columns: 1fr;
    }

    .steps {
        grid-template-columns: 1fr 1fr;
    }

    .cta h2 {
        font-size: 36px;
    }

    .footer {
        flex-direction: column;
    }
}
</style>
</head>

<body>

<header>
<div class="container nav">

<div class="logo">
FURNITURE
</div>

<nav>
<a href="#catalog">Каталог</a>
<a href="#about">Біз туралы</a>
<a href="#works">Жұмыстар</a>
<a href="#contact">Байланыс</a>
</nav>

</div>
</header>


<!-- HERO -->

<section class="hero">

<div class="container hero-content">

<p>ЖЕКЕ ТАПСЫРЫСПЕН ЖИҺАЗ ЖАСАУ</p>

<h1>
Сіздің үйіңізге арналған
ерекше жиһаз
</h1>

<p>
Өлшеміңізге, интерьеріңізге және қалауыңызға сай
сапалы жиһаз жасаймыз.
</p>

<div class="buttons">

<a class="btn btn-primary"
href="https://wa.me/77000000000">
WhatsApp арқылы тапсырыс беру
</a>

<a class="btn btn-light" href="#works">
Жұмыстарымыз
</a>

</div>

</div>

</section>


<!-- CATALOG -->

<section id="catalog">

<div class="container">

<h2 class="section-title">
Біз не жасаймыз?
</h2>

<p class="section-subtitle">
Әр жоба — сіздің кеңістігіңізге арнайы жасалады.
</p>

<div class="products">

<div class="card">
<img src="https://images.unsplash.com/photo-1556912173-3bb406ef7e77?auto=format&fit=crop&w=1000&q=80">
<div class="card-content">
<h3>Ас үй жиһазы</h3>
<p>Ыңғайлы әрі заманауи ас үй гарнитурлары.</p>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1595428774223-ef52624120d2?auto=format&fit=crop&w=1000&q=80">
<div class="card-content">
<h3>Шкафтар</h3>
<p>Жеке өлшем бойынша функционалды шкафтар.</p>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1616486338812-3dadae4b4ace?auto=format&fit=crop&w=1000&q=80">
<div class="card-content">
<h3>Гардероб</h3>
<p>Киімдеріңізге арналған стильді сақтау жүйелері.</p>
</div>
</div>

</div>

</div>

</section>


<!-- ABOUT -->

<section class="about" id="about">

<div class="container about-grid">

<img src="https://images.unsplash.com/photo-1586023492125-27b2c045efd7?auto=format&fit=crop&w=1200&q=80">

<div class="about-text">

<h2 class="section-title">
Неліктен біз?
</h2>

<p>
Біз жиһазды дайын үлгі бойынша ғана емес,
сіздің үйіңіздің өлшемі мен интерьеріне
сай жеке жобамен жасаймыз.
</p>

<div class="features">

<div class="feature">✓ Жеке өлшем</div>
<div class="feature">✓ Заманауи дизайн</div>
<div class="feature">✓ Сапалы материал</div>
<div class="feature">✓ Ұқыпты өндіріс</div>
<div class="feature">✓ Кәсіби монтаж</div>
<div class="feature">✓ Жеке тәсіл</div>

</div>

</div>

</div>

</section>


<!-- STEPS -->

<section>

<div class="container">

<h2 class="section-title">
Қалай жұмыс істейміз?
</h2>

<p class="section-subtitle">
Тапсырыстан дайын жиһазға дейін — барлығы 4 қадам.
</p>

<div class="steps">

<div class="step">
<div class="number">01</div>
<h3>Өтінім</h3>
<p>Бізге WhatsApp арқылы жазасыз.</p>
</div>

<div class="step">
<div class="number">02</div>
<h3>Өлшем</h3>
<p>Жоба мен өлшемдерді талқылаймыз.</p>
</div>

<div class="step">
<div class="number">03</div>
<h3>Өндіріс</h3>
<p>Жиһазыңызды дайындаймыз.</p>
</div>

<div class="step">
<div class="number">04</div>
<h3>Монтаж</h3>
<p>Дайын жиһазды орнатып береміз.</p>
</div>

</div>

</div>

</section>


<!-- PORTFOLIO -->

<section id="works">

<div class="container">

<h2 class="section-title">
Біздің жұмыстар
</h2>

<p class="section-subtitle">
Соңғы жобаларымыз.
</p>

<div class="portfolio">

<img src="https://images.unsplash.com/photo-1600566753086-00f18fb6b3ea?auto=format&fit=crop&w=1000&q=80">

<img src="https://images.unsplash.com/photo-1600210492486-724fe5c67fb0?auto=format&fit=crop&w=1000&q=80">

<img src="https://images.unsplash.com/photo-1600607688969-a5bfcd646154?auto=format&fit=crop&w=1000&q=80">

<img src="https://images.unsplash.com/photo-1618220179428-22790b461013?auto=format&fit=crop&w=1000&q=80">

<img src="https://images.unsplash.com/photo-1616486338812-3dadae4b4ace?auto=format&fit=crop&w=1000&q=80">

<img src="https://images.unsplash.com/photo-1617104678098-de229db51175?auto=format&fit=crop&w=1000&q=80">

</div>

</div>

</section>


<!-- CTA -->

<section class="cta" id="contact">

<div class="container">

<h2>
Жиһазыңызды бірге жасайық
</h2>

<p>
Жобаңызды талқылау үшін бізге жазыңыз.
</p>

<a class="btn btn-light"
href="https://wa.me/77000000000">
WhatsApp арқылы жазу
</a>

</div>

</section>


<footer>

<div class="container footer">

<div>
<strong>FURNITURE</strong>
<p>Жеке тапсырыспен жиһаз жасау</p>
</div>

<div>
<p>📞 +7 700 000 00 00</p>
<p>📍 Орал, Қазақстан</p>
</div>

</div>

</footer>

</body>
</html>
