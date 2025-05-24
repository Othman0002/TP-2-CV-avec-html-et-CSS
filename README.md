# TP-2-CV-avec-html-et-CSS
mon cv professionnel ( html , css)
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CV-OTHMAN-BAHAMMOU-SMI</title>
    <style>
        /* Style général */
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: #333;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f9f9f9;
        }
        
        /* En-tête */
        header {
            text-align: center;
            margin-bottom: 30px;
            padding-bottom: 20px;
            border-bottom: 2px solid #3498db;
        }
        
        h1 {
            color: #2c3e50;
            margin-bottom: 5px;
        }
        
        .titre {
            color: #3498db;
            font-weight: normal;
            margin-top: 0;
        }
        
        /* Sections */
        section {
            margin-bottom: 25px;
            background: white;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        
        h2 {
            color: #3498db;
            border-bottom: 1px solid #eee;
            padding-bottom: 5px;
        }
        
        /* Expériences et formations */
        .item {
            margin-bottom: 15px;
        }
        
        .date {
            font-weight: bold;
            color: #7f8c8d;
        }
        
        .poste {
            font-weight: bold;
            color: #2c3e50;
        }
        
        /* Compétences */
        ul {
            padding-left: 20px;
        }
        
        li {
            margin-bottom: 5px;
        }
        
        /* Pied de page */
        footer {
            text-align: center;
            margin-top: 30px;
            color: #7f8c8d;
            font-size: 0.9em;
        }
    </style>
</head>
<body>
    <header>
        <h1>BAHAMMOU OTHMAN</h1>
        <p class="titre">Étudiant en Sciences Mathématiques et Informatique (SMI)</p>
        <p>✉️ othman.bahammou@email.com | 📞 +212 664-210678 | 🌍 Ouarzazate, Maroc</p>
    </header>

    <section>
        <h2>Profil</h2>
        <p>Étudiant motivé en SMI avec une passion pour le développement informatique et les mathématiques appliquées. Capacité à travailler en équipe et à résoudre des problèmes complexes.</p>
    </section>

    <section>
        <h2>Formation Académique</h2>
        <div class="item">
            <span class="date">2025 - Présent</span>
            <p class="poste">Licence en Sciences Mathématiques et Informatique</p>
            <p>Université Ibn Zohr, Faculté des Sciences, Ouarzazate</p>
        </div>
        
        <div class="item">
            <span class="date">2021 - 2022</span>
            <p class="poste">Baccalauréat Sciences physiques A</p>
            <p>Lycée Assou oubaslam saghrou, tinghir</p>
            <p>Mention : Bien</p>
        </div>
    </section>

    <section>
        <h2>Compétences Techniques</h2>
        <ul>
            <li><strong>Programmation</strong> : Python, Java, C, HTML/CSS</li>
            <li><strong>Base de données</strong> : SQL, MySQL</li>
            <li><strong>Mathématiques</strong> : Algèbre, Analyse, Statistiques</li>
            <li><strong>Langues</strong> : 
                <ul>
                    <li>Arabe (Langue maternelle)</li>
                    <li>Français (Courant)</li>
                    <li>Anglais (Intermédiaire)</li>
                </ul>
            </li>
        </ul>
    </section>

    <section>
        <h2>Projets Académiques</h2>
        <div class="item">
            <p class="poste">Développement d'une application web de gestion des stagiaires</p>
            <ul>
                <li>Conception et implémentation en php</li>
                <li>Gestion des notes et absences des étudiants</li>
                <li>Interface utilisateur simple</li>
            </ul>
        </div>
        
        <div class="item">
            <p class="poste">Création d'un site web statique</p>
            <ul>
                <li>HTML5 et CSS3</li>
                <li>Design responsive</li>
                <li>Présentation d'une association étudiante</li>
            </ul>
        </div>
    </section>

    <section>
        <h2>Expérience Professionnelle</h2>
        <div class="item">
            <span class="date">Été 2023</span>
            <p class="poste">Stage d'observation</p>
            <p>Centre Informatique Municipal, Ouarzazate</p>
            <ul>
                <li>Maintenance des équipements informatiques</li>
                <li>Support technique aux utilisateurs</li>
                <li>Installation de logiciels</li>
            </ul>
        </div>
    </section>

    <section>
        <h2>Centres d'Intérêt</h2>
        <ul>
            <li>Programmation compétitive</li>
            <li>Mathématiques appliquées</li>
            <li>Nouvelles technologies</li>
            <li>Lecture scientifique</li>
        </ul>
    </section>

    <footer>
        <p>Dernière mise à jour : janvier 2024</p>
    </footer>
</body>
</html>
