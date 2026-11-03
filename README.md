# portfolio-Alexandre-Nolhann[CV.HTML](https://github.com/user-attachments/files/34316731/CV.HTML)

<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CV-ALEXANDRE NOLHANN</title>

    <style>
        * {
            box-sizing: border-box;
            margin: 9;
            padding: 3;
        }

        body {
            font-family: Arial, sans-serif;
            background: #f2f4f7;
            color: #333;
            line-height: 1.3;
        }

        .cv {
            max-width: 1050px;
            margin: 30px auto;
            background: WHITE;
            display: grid;
            grid-template-columns: 300px 1fr;
            box-shadow: 0 5px 25px rgba(0, 0, 0, 0.1);
        }

        /* COLONNE GAUCHE */
        .sidebar {
            background: #172554;
            color: white;
            padding: 35px 25px;
        }

        .photo {
            width: 130px;
            height: 130px;
            background: #ddd;
            border-radius: 50%;
            margin: 0 auto 20px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #555;
            font-size: 14px;
        }

        .sidebar h1 {
            text-align: center;
            font-size: 26px;
            margin-bottom: 5px;
        }

        .job {
            text-align: center;
            color: #93c5fd;
            margin-bottom: 30px;
        }

        .sidebar h2 {
            font-size: 17px;
            border-bottom: 2px solid #3b82f6;
            padding-bottom: 5px;
            margin: 25px 0 12px;
        }

        .sidebar p,
        .sidebar li {
            font-size: 14px;
            margin-bottom: 8px;
        }

        .sidebar ul {
            list-style: none;
        }

        /* CONTENU PRINCIPAL */
        .content {
            padding: 40px;
        }

        .section {
            margin-bottom: 30px;
        }

        .section h2 {
            color: #172554;
            font-size: 22px;
            border-bottom: 2px solid #3b82f6;
            padding-bottom: 6px;
            margin-bottom: 18px;
        }

        .experience,
        .formation {
            margin-bottom: 22px;
        }

        .experience h3,
        .formation h3 {
            color: #222;
            font-size: 18px;
        }

        .date {
            color: #2563eb;
            font-size: 14px;
            font-weight: bold;
        }

        .experience p,
        .formation p {
            font-size: 15px;
            margin-top: 5px;
        }

        .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }

        .skill {
            background: #dbeafe;
            color: #172554;
            padding: 8px 14px;
            border-radius: 20px;
            font-size: 14px;
        }

        /* VERSION MOBILE */
        @media (max-width: 700px) {
            .cv {
                margin: 0;
                display: block;
            }

            .sidebar {
                padding: 30px 20px;
            }

            .content {
                padding: 30px 20px;
            }
        }

        /* IMPRESSION */
        @media print {
            body {
                background: white;
            }

            .cv {
                margin: 0;
                box-shadow: none;
            }
        }
    </style>
</head>

<body>

    <div class="cv">

        <!-- COLONNE GAUCHE -->
        <aside class="sidebar">

            <div class="photo">
                PHOTO
            </div>

            <h1>Nolhann Alexandre</h1>
            <p class="job">TECHNICIEN SUPERIEUR</p7>

            <h2>Contact</h2>

            <p>📍 Abymes, Guadeloupe</p>
            <p>📞 06 90 15 60 87</p>
            <p>✉️ Nolhannalxandre8@gmail.com</p>

            <h2>Compétences</h2>

            <ul>
                <li>HTML / CSS</li>
                <li>Python</li>
            </ul>

            <h2>Langues</h2>

            <ul>
                <li>🇫🇷 Français : langue maternelle</li>
                <li>🇫🇷 Français : courant</li>
                <li>🇬🇧 Anglais: intermédiaire</li>
            </ul>

            <h2>Déplacement</h2>

            <ul>
                <li> 🚗Voiture</li>
                <li> 🚍Bus</li>
                <li> 👣à Pied</li>
            </ul>

            <h2>Centres d'intérêt</h2>

            <ul>
                <li>💻 Informatique</li>
                <li>⚽ Sport</li>
                <li>🎮 Jeux vidéo</li>
                <li>🎵 Musique</li>
            </ul>



        </aside>


        <!-- CONTENU PRINCIPAL -->
        <main class="content">

            <section class="section">
                <h2>Profil</h2>

                <p>
                    Passionné par l'infirmatique et les nouvelles technologies,
                    je suis une personne motivée, sérieuse et curieuse. Je souhaite
                    mettre mes compétences au service d'une entreprise et continuer
                    à développer mon expérience professionnelle.
                </p>
            </section>


            <section class="section">
                <h2>Expériences professionnelles</h2>

                <div class="experience">
                    <span class="date">2023 - Il y'a 3ans</span>
                    <h3>Etudiant — au lycée de Chevalier de Saint Geroge </h3>

                    <p>
                        Le  Lycée Chevalier de Saint George avec la filier CIEL (Informatique,Reseaux et Cyber-sécurité)
                    </p>
                </div>

                <div class="experience">
                    <span class="date">2023 - 2026</span>
                    <h2>Stagiaire en Informatique et reseaux</h2>

                    <p>
                       <h4> Participation dans les entreprises</h4>
                    <p> - Technicien sur auto mobile à AUTO+
                    <p>- Informaticien et Réparateur à ASSISTE PC
                    <p>- Technicien chez ELECTRONIQUE 54
                    <p>- Polyvalant à DIGICEL.
                </div>

            </section>


            <section class="section">
                <h2>Formations</h2>

                <div class="formation">
                    <span class="date">2025 - 2026</span>
                    <p>Lycée / École — Guadeloupe</p>
                </div>

                <div class="formation">
                    <span class="date">2026</span>
                    <h3>Baccalauréat</h3>
                    <p6>Lycée Chevaier de Saint George — Guadeloupe </p6>
                </div>

            </section>


            <section class="section">
                <h2>Compétences techniques</h2>

                <div class="skills">
                    <span class="skill">HTML</span>
                    <span class="skill">CSS</span>
                    <span class="skill">Python</span>
                </div>

            </section>


            <section class="section">
                <h2>Projets</h2>

                <div class="experience">
                    <h3>Informaticie en réseau</h3>
                </div>
            </section>

        </main>

    </div>

</body>
</html>
