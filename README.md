<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Page Moderne - Violet et Noir</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #0e0e10;
            color: #e3e3e3;
            line-height: 1.8;
        }
        header {
            background-color: #9147ff;
            color: white;
            padding: 20px 0;
            text-align: center;
            font-size: 2.2em;
            font-weight: bold;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.5);
        }
        .content {
            max-width: 1400px;
            margin: 20px auto;
            padding: 20px;
        }
        .content-block {
            background-color: #1f1f23;
            border-radius: 10px;
            padding: 20px;
            margin-bottom: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.5);
            transition: transform 0.3s, box-shadow 0.3s;
        }
        .content-block:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.8);
        }
        .content-block img {
            max-width: 100%;
            border-radius: 10px;
            margin: 15px 0;
        }
        a {
            color: #9147ff;
            text-decoration: none;
            font-weight: bold;
        }
        a:hover {
            text-decoration: underline;
            color: #bf94ff;
        }
        footer {
            text-align: center;
            padding: 15px 0;
            background-color: #9147ff;
            color: white;
            position: relative;
            bottom: 0;
            width: 100%;
            box-shadow: 0 -4px 8px rgba(0, 0, 0, 0.5);
        }
        .nav-bar {
            background-color: #1f1f23;
            padding: 10px 0;
            display: flex;
            justify-content: space-around;
            align-items: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.5);
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        .nav-bar a {
            color: #e3e3e3;
            text-decoration: none;
            font-weight: bold;
            padding: 10px 15px;
        }
        .nav-bar a:hover {
            color: #9147ff;
        }
    </style>
</head>
<body>
    <header>
        Plus de choses à savoir sur nightwariz !
    </header>

    <nav class="nav-bar">
        <a href="file:///C:/Users/Melvyn/Documents/HTML%20Site%20ChatGPT/index.html">Accueil</a>
        <a href="#section1">Biographie</a>
        <a href="#section2">Passions et divertissement</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="content">
        <div class="content-block" id="section1">
            <h2>Biographie</h2>
            <p>nightwariz est un joueur Rocket League (champion 3), Fortnite (diamant 1) et Brawl Stars (Mythique 2) qui fait découvrir ses passions pour un jour, peut-être, devenir un grand Youtubeur !!.</p>
            <img src="file:///C:/Users/Melvyn/Downloads/E%202024-12-16%2011.27.25%20-%20A%20bold%20and%20modern%20logo%20design%20with%20a%20space-themed%20background%20featuring%20stars,%20glowing%20nebulae,%20and%20vibrant%20shades%20of%20blue%20and%20purple.%20At%20the%20center,%20t.webp" alt="Description de l'image 1">
            <p><a href="https://example.com/link1" target="_blank"></a></p>
        </div>

        <div class="content-block" id="section2">
            <h2>Passions et divertissement</h2>
            <p>Il joue à Rocket League (champion 3), Fortnite (diamant 1) et Brawl Stars (Mythique 2) et veut partager cela avec ses abonnés.</p>
            <img src="file:///C:/Users/Melvyn/Downloads/tkt.PNG" alt="Description de l'image 2">
            <p><a href="https://example.com/link2" target="_blank"></a></p>
        </div>
    </div>

    <footer id="contact">
        <p>&copy; NY_Yaxo</p>
        <p>RETROUVEZ-LE ICI -> <a href="https://www.youtube.com/@NY.Yaxoytb" target="_blank">www.youtube.com/@NY.Yaxoytb</a></p>
    </footer>
</body>
</html>
