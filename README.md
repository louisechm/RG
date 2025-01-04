# RG
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Roses Guerrières</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fff5f7;
            color: #333;
        }
        header {
            background-color: #ff99cc;
            color: white;
            padding: 1em 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        nav {
            background-color: #ff66b2;
            padding: 0.5em;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-size: 1.2em;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .hero {
            background: url('https://via.placeholder.com/1500x500/ffccdd/ffffff?text=Roses+Guerri%C3%A8res') no-repeat center center/cover;
            height: 50vh;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            text-shadow: 2px 2px 5px #000;
            font-size: 2em;
            text-align: center;
        }
        section {
            padding: 2em;
            line-height: 1.6;
        }
        .actions, .don {
            background-color: #ffe6f2;
            border: 1px solid #ff99cc;
            margin: 2em 0;
            padding: 1em;
            border-radius: 10px;
        }
        footer {
            background-color: #ff99cc;
            color: white;
            text-align: center;
            padding: 1em 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Roses Guerrières</h1>
        <p>Lutter ensemble contre le cancer du sein</p>
    </header>
    <nav>
        <a href="#accueil">Accueil</a>
        <a href="#apropos">À propos</a>
        <a href="#actions">Actions</a>
        <a href="#don">Soutien</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="hero">
        <div>Solidarité, Force, Espoir</div>
    </div>
    <section id="accueil">
        <h2>Bienvenue chez Roses Guerrières</h2>
        <p>Notre mission est de soutenir les femmes atteintes du cancer du sein et de sensibiliser le public à cette cause.</p>
    </section>
    <section id="apropos">
        <h2>À propos</h2>
        <p>Roses Guerrières est une association dédiée à la lutte contre le cancer du sein. Fondée en 2023, elle s'engage à offrir des ressources, du soutien, et des événements communautaires pour aider les femmes et leurs familles à traverser cette épreuve.</p>
    </section>
    <section id="actions" class="actions">
        <h2>Nos Actions</h2>
        <ul>
            <li>Organisation de marches solidaires</li>
            <li>Ateliers de bien-être</li>
            <li>Sensibilisation en milieu scolaire</li>
        </ul>
    </section>
    <section id="don" class="don">
        <h2>Soutenez-nous</h2>
        <p>Participez à nos actions en faisant un don ou en devenant bénévole. Ensemble, nous pouvons faire la différence.</p>
        <button style="background-color: #ff66b2; color: white; padding: 10px 20px; border: none; border-radius: 5px;">Faire un don</button>
    </section>
    <section id="contact">
        <h2>Contactez-nous</h2>
        <form>
            <label for="name">Nom :</label><br>
            <input type="text" id="name" name="name" required><br><br>
            <label for="email">Email :</label><br>
            <input type="email" id="email" name="email" required><br><br>
            <label for="message">Message :</label><br>
            <textarea id="message" name="message" rows="5" required></textarea><br><br>
            <button type="submit" style="background-color: #ff66b2; color: white; padding: 10px 20px; border: none; border-radius: 5px;">Envoyer</button>
        </form>
    </section>
    <footer>
        <p>&copy; 2025 Roses Guerrières - Tous droits réservés</p>
    </footer>
</body>
</html>
