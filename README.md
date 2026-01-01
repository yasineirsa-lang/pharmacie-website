# pharmacie-website
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>Pharmacie Santé Plus</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>

<header>
    <div class="container header-content">
        <h1>Pharmacie Santé Plus</h1>
        <nav>
            <a href="#">Accueil</a>
            <a href="#">Produits</a>
            <a href="#">Services</a>
            <a href="#">Contact</a>
        </nav>
    </div>
</header>

<section class="hero">
    <div class="container hero-content">
        <div>
            <h2>Votre santé, notre priorité</h2>
            <p>
                Nous vous proposons des médicaments, des produits
                pharmaceutiques et des conseils professionnels
                pour votre bien-être.
            </p>
            <a class="btn" href="#">Découvrir nos produits</a>
        </div>
        <img src="images/hero.svg" alt="Pharmacie">
    </div>
</section>

<section class="services container">
    <h2>Nos services</h2>
    <div class="cards">
        <div class="card">
            <h3>Médicaments</h3>
            <p>Large choix de médicaments certifiés et sécurisés.</p>
        </div>
        <div class="card">
            <h3>Conseils</h3>
            <p>Accompagnement et conseils professionnels.</p>
        </div>
        <div class="card">
            <h3>Parapharmacie</h3>
            <p>Produits de soins, hygiène et bien-être.</p>
        </div>
    </div>
</section>

<footer>
    <p>© 2026 Pharmacie Santé Plus – Tous droits réservés</p>
</footer>

</body>
</html>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    background-color: #f5f7fa;
    color: #333;
}

.container {
    width: 90%;
    max-width: 1100px;
    margin: auto;
}

header {
    background-color: #1abc9c;
    padding: 20px 0;
    color: white;
}

.header-content {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

nav a {
    color: white;
    margin-left: 20px;
    text-decoration: none;
    font-weight: bold;
}

.hero {
    background: linear-gradient(135deg, #1abc9c, #16a085);
    color: white;
    padding: 60px 0;
}

.hero-content {
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 30px;
}

.hero img {
    width: 300px;
}

.hero h2 {
    font-size: 36px;
    margin-bottom: 15px;
}

.hero p {
    margin-bottom: 20px;
    line-height: 1.6;
}

.btn {
    background-color: white;
    color: #16a085;
    padding: 10px 20px;
    text-decoration: none;
    font-weight: bold;
    border-radius: 5px;
}

.services {
    padding: 60px 0;
    text-align: center;
}

.services h2 {
    margin-bottom: 40px;
    color: #16a085;
}

.cards {
    display: flex;
    gap: 20px;
}


.card {
    background-color: white;
    padding: 25px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    flex: 1;
}

.card h3 {
    color: #1abc9c;
    margin-bottom: 10px;
}

footer {
    background-color: #1abc9c;
    color: white;
    text-align: center;
    padding: 15px;
}
