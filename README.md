<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Page officielle de nightwariz, un joueur passionné de Rocket League, Fortnite et Brawl Stars. Découvrez ses passions et son parcours.">
    <title>Plus de choses à savoir sur nightwariz !</title>
    <style>
        /* Réinitialisation des marges et des paddings pour tous les éléments */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            background-color: #0e0e10;
            color: #e3e3e3;
            line-height: 1.8;
            font-size: 18px;
            overflow-x: hidden;
        }

        header {
            background-color: #9147ff;
            color: white;
            padding: 80px 20px;
            text-align: center;
            font-size: 3.5em;
            font-weight: bold;
            box-shadow: 0 8px 15px rgba(0, 0, 0, 0.6);
        }

        nav {
            background-color: #1f1f23;
            padding: 20px 0;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-shadow: 0 8px 15px rgba(0, 0, 0, 0.6);
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        .nav-bar {
            display: flex;
            gap: 30px;
            font-size: 1.2em;
        }

        .nav-bar a {
            color: #e3e3e3;
            text-decoration: none;
            font-weight: bold;
            padding: 10px 15px;
            transition: color 0.3s, transform 0.3s;
        }

        .nav-bar a:hover {
            color: #9147ff;
            transform: translateY(-3px);
        }

        /* Style du menu déroulant des langues */
        .language-select {
            background-color: #1f1f23;
            border: none;
            color: white;
            font-size: 1em;
            padding: 10px 20px;
            cursor: pointer;
            border-radius: 5px;
        }

        .language-select:hover {
            background-color: #9147ff;
            color: white;
        }

        .content {
            max-width: 1800px;
            margin: 80px auto;
            padding: 50px 20px;
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

        .content-block h2 {
            font-size: 2em;
            color: #9147ff;
            margin-bottom: 20px;
        }

        footer {
            text-align: center;
            padding: 40px 20px;
            background-color: #9147ff;
            color: white;
            position: relative;
            bottom: 0;
            width: 100%;
            box-shadow: 0 -8px 15px rgba(0, 0, 0, 0.6);
            font-size: 1.5em;
        }

        footer a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        footer a:hover {
            color: #bf94ff;
            text-decoration: underline;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            header {
                font-size: 2.5em;
                padding: 60px 20px;
            }

            .nav-bar {
                flex-direction: column;
                gap: 15px;
            }

            .content {
                padding: 30px 15px;
            }

            .content-block {
                padding: 25px;
            }

            .nav-bar a {
                padding: 10px;
            }

            footer {
                font-size: 1.2em;
                padding: 30px 20px;
            }
        }
    </style>
</head>
<body>
    <header id="header">
        Plus de choses à savoir sur nightwariz !
    </header>

    <nav>
        <div class="nav-bar">
            <a href="https://chriskilla.github.io/nightwariz/" target="_blank" id="home-link">Accueil</a>
            <a href="#section1" id="biography-link">Biographie</a>
            <a href="#section2" id="passions-link">Passions</a>
        </div>
        <select class="language-select" id="language-select">
            <option value="fr">Français</option>
            <option value="en">English</option>
            <option value="de">Deutsch</option>
            <option value="es">Español</option>
        </select>
    </nav>

    <div class="content">
        <div class="content-block" id="section1">
            <h2 id="biography-title">Biographie</h2>
            <p id="biography-description">nightwariz est un joueur passionné de jeux vidéo. Actuellement, il est Champion 3 sur Rocket League, Diamant 1 sur Fortnite et Mythique 2 sur Brawl Stars. Il rêve de partager sa passion et de devenir un grand Youtubeur un jour !</p>
        </div>

        <div class="content-block" id="section2">
            <h2 id="passions-title">Passions et divertissement</h2>
            <p id="passions-description">nightwariz aime particulièrement jouer à Rocket League, Fortnite et Brawl Stars. En plus de ses compétences en jeux compétitifs, il veut partager ses expériences et ses stratégies avec ses abonnés pour les aider à progresser et se divertir !</p>
        </div>
    </div>

    <footer>
        <p id="footer-text">© 2024 NY_Yaxo</p>
        <!-- Lien YouTube sans texte supplémentaire -->
        <a href="https://www.youtube.com/@NY.Yaxoytb" target="_blank">www.youtube.com/@NY.Yaxoytb</a>
    </footer>

    <script>
        const translations = {
            fr: {
                header: "Plus de choses à savoir sur nightwariz !",
                biographyTitle: "Biographie",
                biographyDescription: "nightwariz est un joueur passionné de jeux vidéo. Actuellement, il est Champion 3 sur Rocket League, Diamant 1 sur Fortnite et Mythique 2 sur Brawl Stars. Il rêve de partager sa passion et de devenir un grand Youtubeur un jour !",
                passionsTitle: "Passions et divertissement",
                passionsDescription: "nightwariz aime particulièrement jouer à Rocket League, Fortnite et Brawl Stars. En plus de ses compétences en jeux compétitifs, il veut partager ses expériences et ses stratégies avec ses abonnés pour les aider à progresser et se divertir !",
                footerText: "© 2024 NY_Yaxo",
                homeLink: "Accueil",
                biographyLink: "Biographie",
                passionsLink: "Passions"
            },
            en: {
                header: "More to know about nightwariz!",
                biographyTitle: "Biography",
                biographyDescription: "nightwariz is a passionate gamer. Currently, he is Champion 3 in Rocket League, Diamond 1 in Fortnite, and Mythic 2 in Brawl Stars. He dreams of sharing his passion and becoming a top YouTuber someday!",
                passionsTitle: "Passions and Entertainment",
                passionsDescription: "nightwariz loves playing Rocket League, Fortnite, and Brawl Stars. Besides his skills in competitive gaming, he wants to share his experiences and strategies with his followers to help them improve and have fun!",
                footerText: "© 2024 NY_Yaxo",
                homeLink: "Home",
                biographyLink: "Biography",
                passionsLink: "Passions"
            },
            de: {
                header: "Mehr über nightwariz zu wissen!",
                biographyTitle: "Biographie",
                biographyDescription: "nightwariz ist ein leidenschaftlicher Gamer. Derzeit ist er Champion 3 in Rocket League, Diamant 1 in Fortnite und Mythic 2 in Brawl Stars. Er träumt davon, seine Leidenschaft zu teilen und eines Tages ein großer YouTuber zu werden!",
                passionsTitle: "Leidenschaften und Unterhaltung",
                passionsDescription: "nightwariz liebt es, Rocket League, Fortnite und Brawl Stars zu spielen. Neben seinen Fähigkeiten im kompetitiven Gaming möchte er seine Erfahrungen und Strategien mit seinen Followern teilen, um ihnen zu helfen, sich zu verbessern und Spaß zu haben!",
                footerText: "© 2024 NY_Yaxo",
                homeLink: "Startseite",
                biographyLink: "Biographie",
                passionsLink: "Leidenschaften"
            },
            es: {
                header: "¡Más cosas que saber sobre nightwariz!",
                biographyTitle: "Biografía",
                biographyDescription: "nightwariz es un jugador apasionado de videojuegos. Actualmente es Campeón 3 en Rocket League, Diamante 1 en Fortnite y Mítico 2 en Brawl Stars. ¡Sueña con compartir su pasión y convertirse en un gran YouTuber algún día!",
                passionsTitle: "Pasiones y entretenimiento",
                passionsDescription: "A nightwariz le encanta jugar a Rocket League, Fortnite y Brawl Stars. Además de sus habilidades en juegos competitivos, quiere compartir sus experiencias y estrategias con sus seguidores para ayudarles a mejorar y divertirse.",
                footerText: "© 2024 NY_Yaxo",
                homeLink: "Inicio",
                biographyLink: "Biografía",
                passionsLink: "Pasiones"
            }
        };

        const languageSelect = document.getElementById("language-select");

        languageSelect.addEventListener("change", function() {
            const lang = languageSelect.value;
            document.getElementById("header").textContent = translations[lang].header;
            document.getElementById("biography-title").textContent = translations[lang].biographyTitle;
            document.getElementById("biography-description").textContent = translations[lang].biographyDescription;
            document.getElementById("passions-title").textContent = translations[lang].passionsTitle;
            document.getElementById("passions-description").textContent = translations[lang].passionsDescription;
            document.getElementById("footer-text").textContent = translations[lang].footerText;
            document.getElementById("home-link").textContent = translations[lang].homeLink;
            document.getElementById("biography-link").textContent = translations[lang].biographyLink;
            document.getElementById("passions-link").textContent = translations[lang].passionsLink;
        });
    </script>
</body>
</html>
