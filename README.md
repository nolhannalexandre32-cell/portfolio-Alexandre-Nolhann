# portfolio-Alexandre-Nolhann[CV.HTML](https://github.com/user-attachments/files/34316731/CV.HTML)

<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Portfolio BTS SIO - Prénom Nom</title>
 
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
 
<style>
:root{
--primary:#00bfff;
--dark:#0f172a;
--dark2:#1e293b;
--text:#f8fafc;
}
 
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
scroll-behavior:smooth;
}
 
body{
background:var(--dark);
color:var(--text);
}
 
nav{
position:fixed;
top:0;
width:100%;
background:rgba(15,23,42,.95);
backdrop-filter:blur(10px);
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 10%;
z-index:1000;
}
 
nav h2{
color:var(--primary);
}
 
nav ul{
display:flex;
list-style:none;
gap:25px;
}
 
nav a{
color:white;
text-decoration:none;
transition:.3s;
}
 
nav a:hover{
color:var(--primary);
}
 
.hero{
min-height:100vh;
display:flex;
align-items:center;
justify-content:space-between;
padding:0 10%;
}
 
.hero-text{
max-width:600px;
}
 
.hero-text h1{
font-size:4rem;
}
 
.hero-text span{
color:var(--primary);
}
 
.hero-text p{
margin:20px 0;
color:#cbd5e1;
line-height:1.8;
}
 
.btn{
display:inline-block;
padding:12px 30px;
background:var(--primary);
color:white;
text-decoration:none;
border-radius:50px;
transition:.3s;
}
 
.btn:hover{
transform:translateY(-5px);
}
 
.hero img{
width:350px;
border-radius:50%;
border:5px solid var(--primary);
}
 
section{
padding:100px 10%;
}
 
.section-title{
text-align:center;
font-size:2.5rem;
margin-bottom:50px;
color:var(--primary);
}
 
.about{
display:grid;
grid-template-columns:1fr 1fr;
gap:50px;
}
 
.card{
background:var(--dark2);
padding:30px;
border-radius:15px;
}
 
.skills{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(150px,1fr));
gap:20px;
}
 
.skill{
background:var(--dark2);
padding:20px;
text-align:center;
border-radius:10px;
transition:.3s;
}
 
.skill:hover{
transform:translateY(-10px);
border:1px solid var(--primary);
}
 
.projects{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
gap:30px;
}
 
.project{
background:var(--dark2);
border-radius:15px;
overflow:hidden;
transition:.3s;
}
 
.project:hover{
transform:scale(1.03);
}
 
.project img{
width:100%;
height:200px;
object-fit:cover;
}
 
.project-content{
padding:20px;
}
 
.contact{
text-align:center;
}
 
.contact p{
margin:15px 0;
}
 
footer{
text-align:center;
padding:30px;
background:#020617;
color:#94a3b8;
}
 
@media(max-width:900px){
 
.hero{
flex-direction:column;
text-align:center;
padding-top:120px;
}
 
.hero img{
margin-top:50px;
width:250px;
}
 
.about{
grid-template-columns:1fr;
}
 
.hero-text h1{
font-size:2.8rem;
}
 
}
</style>
</head>
 
<body>
 
<nav>
<h2>Portfolio</h2>
<ul>
<li><a href="#about">À propos</a></li>
<li><a href="#skills">Compétences</a></li>
<li><a href="#projects">Projets</a></li>
<li><a href="#contact">Contact</a></li>
</ul>
</nav>
 
<section class="hero">
<div class="hero-text">
<h1>Bonjour, je suis <span>Prénom Nom</span></h1>
<p>
Étudiant en BTS SIO passionné par le développement web,
les réseaux informatiques et la cybersécurité.
Mon objectif est de développer des solutions innovantes
tout en renforçant mes compétences techniques.
</p>
 
<a href="#contact" class="btn">Me contacter</a>
</div>
 
<img src="https://via.placeholder.com/350" alt="Photo">
</section>
 
<section id="about">
<h2 class="section-title">À propos</h2>
 
<div class="about">
<div class="card">
<h3>Profil</h3>
<br>
<p>
Étudiant en BTS Services Informatiques aux Organisations.
Curieux, autonome et motivé, je suis passionné par
les nouvelles technologies et l'informatique.
</p>
</div>
 
<div class="card">
<h3>Formation</h3>
<br>
<p>
BTS SIO (SLAM / SISR)<br>
Lycée XXXXX<br>
2025 - 2027
</p>
</div>
</div>
</section>
 
<section id="skills">
<h2 class="section-title">Compétences</h2>
 
<div class="skills">
<div class="skill">HTML5</div>
<div class="skill">CSS3</div>
<div class="skill">JavaScript</div>
<div class="skill">PHP</div>
<div class="skill">MySQL</div>
<div class="skill">Python</div>
<div class="skill">Linux</div>
<div class="skill">Git / GitHub</div>
</div>
</section>
 
<section id="projects">
<h2 class="section-title">Mes Projets</h2>
 
<div class="projects">
 
<div class="project">
<img src="https://picsum.photos/600/400?1">
<div class="project-content">
<h3>Application de Gestion</h3>
<p>Système complet de gestion développé en PHP et MySQL.</p>
</div>
</div>
 
<div class="project">
<img src="https://picsum.photos/600/400?2">
<div class="project-content">
<h3>Site E-Commerce</h3>
<p>Boutique en ligne responsive avec espace administrateur.</p>
</div>
</div>
 
<div class="project">
<img src="https://picsum.photos/600/400?3">
<div class="project-content">
<h3>Infrastructure Réseau</h3>
<p>Architecture réseau configurée sous Cisco Packet Tracer.</p>
</div>
</div>
 
</div>
</section>
 
<section id="contact">
<h2 class="section-title">Contact</h2>
 
<div class="contact">
<p>📧 email@exemple.com</p>
<p>💼 LinkedIn : linkedin.com/in/votreprofil</p>
<p>💻 GitHub : github.com/votreprofil</p>
</div>
</section>
 
<footer>
© 2026 - Portfolio BTS SIO | Prénom Nom
</footer>
 
</body>
</html>

Ce modèle a un rendu proche d'un vrai portfolio de développeur junior avec design moderne, responsive et professionnel.

Sépare le HTML et le CSSAjoute un formulaire de contactAjoute une section CV téléchargeable
