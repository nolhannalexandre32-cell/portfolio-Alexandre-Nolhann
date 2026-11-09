# portfolio-Alexandre-Nolhann[CV.HTML](https://github.com/user-attachments/files/34316731/CV.HTML)

<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Portfolio BTS SIO</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Segoe UI, sans-serif;
}

body{
    background:#0f172a;
    color:white;
    overflow-x:hidden;
}

/* Fond informatique */
.background{
    position:fixed;
    width:100%;
    height:100%;
    top:0;
    left:0;
    display:grid;
    grid-template-columns:repeat(auto-fill,50px);
    grid-auto-rows:50px;
    z-index:-1;
}

.background span{
    border:1px solid rgba(255,255,255,0.05);
    background:rgba(128,128,128,0.03);
    transition:0.5s;
}

.background span:hover{
    background:#808080;
    box-shadow:0 0 15px #808080;
}

/* Header */
header{
    padding:20px 10%;
    display:flex;
    justify-content:space-between;
    align-items:center;
}

.logo{
    font-size:28px;
    font-weight:bold;
    color:#e5e7eb;
}

nav a{
    color:white;
    text-decoration:none;
    margin-left:25px;
    transition:0.3s;
}

nav a:hover{
    color:#9ca3af;
}

/* Hero */
.hero{
    min-height:90vh;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    flex-direction:column;
    padding:20px;
}

.hero h1{
    font-size:4rem;
}

.hero h1 span{
    color:#9ca3af;
}

.hero p{
    max-width:700px;
    margin:20px 0;
    color:#d1d5db;
}

.btn{
    display:inline-block;
    padding:12px 30px;
    background:#6b7280;
    color:white;
    text-decoration:none;
    border-radius:8px;
    transition:0.3s;
}

.btn:hover{
    background:#9ca3af;
}

/* Sections */
section{
    padding:80px 10%;
}

h2{
    text-align:center;
    margin-bottom:40px;
    font-size:2rem;
}

.cards{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.card{
    background:rgba(255,255,255,0.05);
    backdrop-filter:blur(5px);
    border-radius:15px;
    padding:25px;
    transition:0.3s;
}

.card:hover{
    transform:translateY(-10px);
    border:1px solid #9ca3af;
}

footer{
    text-align:center;
    padding:30px;
    border-top:1px solid rgba(255,255,255,0.1);
}
</style>
</head>

<body>

<div class="background" id="background"></div>

<header>
    <div class="logo">Portfolio BTS SIO</div>
    <nav>
        <a href="#about">À propos</a>
        <a href="#skills">Compétences</a>
        <a href="#projects">Projets</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section class="hero">
    <h1>Bonjour, je suis <span>Étudiant BTS SIO</span></h1>
    <p>
        Passionné par le développement web, la cybersécurité et les technologies de l'information.
    </p>
    <a href="#projects" class="btn">Voir mes projets</a>
</section>

<section id="skills">
    <h2>Mes Compétences</h2>

    <div class="cards">
        <div class="card">
            <h3>HTML / CSS</h3>
            <p>Création de sites web modernes et responsives.</p>
        </div>

        <div class="card">
            <h3>JavaScript</h3>
            <p>Développement d'interfaces dynamiques.</p>
        </div>

        <div class="card">
            <h3>PHP / MySQL</h3>
            <p>Développement d'applications web et bases de données.</p>
        </div>
    </div>
</section>

<section id="projects">
    <h2>Mes Projets</h2>

    <div class="cards">
        <div class="card">
            <h3>Gestion de Stock</h3>
            <p>Application web complète avec interface administrateur.</p>
        </div>

        <div class="card">
            <h3>Portfolio Personnel</h3>
            <p>Site responsive présentant mes compétences et projets.</p>
        </div>

        <div class="card">
            <h3>Application BTS SIO</h3>
            <p>Projet de gestion développé durant la formation.</p>
        </div>
    </div>
</section>

<footer>
    © 2026 - Portfolio BTS SIO
</footer>

<script>
const background = document.getElementById('background');

for(let i = 0; i < 800; i++){
    const square = document.createElement('span');
    background.appendChild(square);
}
</script>

</body>
</html>
