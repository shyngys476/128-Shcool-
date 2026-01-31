[Uploading index (2).html…]()
<!DOCTYPE html>
<html lang="kk">
<head>
<meta charset="UTF-8">
<title>№128 Мектеп</title>
<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', sans-serif;
}
body {
    background: #0f172a;
    color: white;
}

/* HEADER */
header {
    padding: 50px;
    text-align: center;
    background: linear-gradient(135deg, #2563eb, #1e40af);
}
header h1 {
    font-size: 48px;
}
header p {
    margin-top: 10px;
    font-size: 20px;
    opacity: 0.9;
}

/* NAV */
nav {
    display: flex;
    justify-content: center;
    gap: 25px;
    background: #020617;
    padding: 15px;
}
nav a {
    color: white;
    text-decoration: none;
    font-weight: bold;
    position: relative;
}
nav a::after {
    content: "";
    position: absolute;
    width: 0;
    height: 2px;
    background: #3b82f6;
    left: 0;
    bottom: -5px;
    transition: 0.3s;
}
nav a:hover::after {
    width: 100%;
}

/* SECTIONS */
section {
    padding: 60px 10%;
}
.title {
    font-size: 36px;
    margin-bottom: 30px;
    text-align: center;
}

/* CARDS */
.cards {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 25px;
}
.card {
    background: #020617;
    padding: 25px;
    border-radius: 15px;
    transition: 0.3s;
}
.card:hover {
    transform: translateY(-10px);
    box-shadow: 0 0 25px #2563eb;
}
.card h3 {
    margin-bottom: 10px;
    color: #60a5fa;
}

/* FOOTER */
footer {
    background: #020617;
    text-align: center;
    padding: 20px;
    opacity: 0.7;
}
</style>
</head>

<body>

<header>
    <h1>Алматы қаласы №128 мектеп</h1>
    <p>Білім — болашақтың кілті</p>
</header>

<nav>
    <a href="#about">Мектеп</a>
    <a href="#teachers">Мұғалімдер</a>
    <a href="#subjects">Пәндер</a>
    <a href="#contact">Байланыс</a>
</nav>

<section id="about">
    <h2 class="title">🏫 Мектеп туралы</h2>
    <div class="cards">
        <div class="card">
            <h3>Заманауи білім</h3>
            <p>Мектеп жаңа технологиялармен жабдықталған.</p>
        </div>
        <div class="card">
            <h3>Тәжірибелі ұстаздар</h3>
            <p>Жоғары деңгейлі мұғалімдер сабақ береді.</p>
        </div>
        <div class="card">
            <h3>Қауіпсіз орта</h3>
            <p>Оқушыларға барлық жағдай жасалған.</p>
        </div>
    </div>
</section>

<section id="teachers">
    <h2 class="title">👩‍🏫 Мұғалімдер</h2>
    <div class="cards">
        <div class="card"><h3>Айгүл апай</h3><p>Математика</p></div>
        <div class="card"><h3>Ерлан ағай</h3><p>Қазақ тілі</p></div>
        <div class="card"><h3>Динара апай</h3><p>Ағылшын тілі</p></div>
        <div class="card"><h3>Нұржан ағай</h3><p>Информатика</p></div>
    </div>
</section>

<section id="subjects">
    <h2 class="title">📚 Пәндер</h2>
    <div class="cards">
        <div class="card">Математика</div>
        <div class="card">Қазақ тілі</div>
        <div class="card">Ағылшын тілі</div>
        <div class="card">Информатика</div>
        <div class="card">Тарих</div>
        <div class="card">Дене шынықтыру</div>
    </div>
</section>

<section id="contact">
    <h2 class="title">📞 Байланыс</h2>
    <div class="cards">
        <div class="card">📍 Алматы қаласы</div>
        <div class="card">📞 +7 777 123 45 67</div>
        <div class="card">📧 school128@mail.kz</div>
    </div>
</section>

<footer>
    © 2026 №128 мектеп | Барлық құқықтар қорғалған
</footer>

</body>
</html>
