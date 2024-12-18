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
            font-size: 20px;
        }
        header {
            background-color: #9147ff;
            color: white;
            padding: 60px 0;
            text-align: center;
            font-size: 3.5em;
            font-weight: bold;
            box-shadow: 0 8px 15px rgba(0, 0, 0, 0.6);
        }
        .content {
            max-width: 1800px;
            margin: 60px auto;
            padding: 50px;
        }
        .content-block {
            background-color: #1f1f23;
            border-radius: 20px;
            padding: 40px;
            margin-bottom: 50px;
            box-shadow: 0 8px 15px rgba(0, 0, 0, 0.6);
            transition: transform 0.3s, box-shadow 0.3s;
        }
        .content-block:hover {
            transform: translateY(-15px);
            box-shadow: 0 12px 25px rgba(0, 0, 0, 0.9);
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
            padding: 40px 0;
            background-color: #9147ff;
            color: white;
            position: relative;
            bottom: 0;
            width: 100%;
            box-shadow: 0 -8px 15px rgba(0, 0, 0, 0.6);
            font-size: 1.5em;
        }
        .nav-bar {
            background-color: #1f1f23;
            padding: 30px 0;
            display: flex;
            justify-content: space-around;
            align-items: center;
            box-shadow: 0 8px 15px rgba(0, 0, 0, 0.6);
            position: sticky;
            top: 0;
            z-index: 1000;
            font-size: 1.5em;
        }
        .nav-bar a {
            color: #e3e3e3;
            text-decoration: none;
            font-weight: bold;
            padding: 20px 30px;
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
        <a href="#">Accueil</a>
        <a href="#section1">Biographie</a>
        <a href="#section2">Passions</a>
    </nav>

    <div class="content">
        <div class="content-block" id="section1">
            <h2>Biographie</h2>
            <p>nightwariz est un joueur Rocket League (champion 3), Fortnite (diamant 1) et Brawl Stars (Mythique 2) qui fait découvrir ses passions pour un jour, peut-être, devenir un grand Youtubeur !!</p>
        </div>

        <div class="content-block" id="section2">
            <h2>Passions et divertissement</h2>
            <p>Il joue à Rocket League (champion 3), Fortnite (diamant 1) et Brawl Stars (Mythique 2) et veut partager cela avec ses abonnés.</p>
        </div>
    </div>

    <footer>
        <p>&copy; NY_Yaxo</p>
        <p>Retrouvez-le ici : <a href="https://www.youtube.com/@NY.Yaxoytb" target="_blank">www.youtube.com/@NY.Yaxoytb</a></p>
    </footer>
</body>
</html>
