<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>ExoBanque</title>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Poppins,sans-serif;
}

body{

background:
radial-gradient(circle at top,#3b82f630,transparent 35%),
radial-gradient(circle at bottom right,#8b5cf630,transparent 40%),
#050816;

color:white;

overflow-x:hidden;

}

/************* HERO *************/

.hero{

min-height:100vh;

display:flex;
align-items:center;
justify-content:center;

padding:80px 8%;

}

.container{

display:grid;

grid-template-columns:1fr 1fr;

gap:80px;

align-items:center;

max-width:1400px;

width:100%;

}

/************* LEFT *************/

.badge{

display:inline-block;

padding:8px 18px;

background:rgba(99,102,241,.15);

border:1px solid rgba(99,102,241,.4);

border-radius:50px;

color:#9db4ff;

font-size:14px;

margin-bottom:25px;

}

h1{

font-size:70px;

font-weight:800;

line-height:1.1;

margin-bottom:25px;

}

h1 span{

background:linear-gradient(90deg,#6366F1,#8B5CF6,#EC4899);

-webkit-background-clip:text;

-webkit-text-fill-color:transparent;

}

.description{

font-size:19px;

line-height:1.8;

color:#b8c0dd;

max-width:650px;

margin-bottom:40px;

}

.buttons{

display:flex;

gap:20px;

margin-bottom:60px;

}

.btn{

padding:16px 35px;

border-radius:12px;

text-decoration:none;

font-weight:600;

transition:.3s;

}

.btn-primary{

background:#6366F1;

color:white;

}

.btn-primary:hover{

transform:translateY(-4px);

box-shadow:0 15px 40px rgba(99,102,241,.4);

}

.btn-secondary{

border:1px solid rgba(255,255,255,.15);

background:rgba(255,255,255,.05);

color:white;

}

.btn-secondary:hover{

background:white;

color:#111;

}

/************* STATS *************/

.stats{

display:flex;

gap:50px;

flex-wrap:wrap;

}

.stat h2{

font-size:38px;

color:#6366F1;

}

.stat p{

color:#98A2B3;

}

/************* RIGHT *************/

.image{

position:relative;

display:flex;

justify-content:center;

}

.image img{

width:100%;

max-width:650px;

border-radius:25px;

box-shadow:0 40px 80px rgba(0,0,0,.5);

animation:float 4s ease-in-out infinite;

}

.glow{

position:absolute;

width:500px;

height:500px;

background:#6366f1;

filter:blur(180px);

opacity:.25;

z-index:-1;

}

@keyframes float{

0%,100%{

transform:translateY(0);

}

50%{

transform:translateY(-15px);

}

}

@media(max-width:950px){

.container{

grid-template-columns:1fr;

text-align:center;

}

.description{

margin:auto auto 40px;

}

.buttons{

justify-content:center;

}

.stats{

justify-content:center;

}

h1{

font-size:52px;

}

}

</style>

</head>

<body>

<section class="hero">

<div class="container">

<div>

<div class="badge">
🚀 La plus grande banque d'exercices collaborative
</div>

<h1>

Apprenez.<br>

Partagez.<br>

<span>Réussissez.</span>

</h1>

<p class="description">

<strong>ExoBanque</strong> est une plateforme moderne permettant aux élèves,
étudiants et enseignants de publier, rechercher et résoudre des exercices
dans toutes les matières. Découvrez des milliers d'exercices classés par
niveau, accédez aux corrections détaillées et améliorez vos compétences grâce
à une communauté active de passionnés de l'apprentissage.

</p>

<div class="buttons">

<a href="#" class="btn btn-primary">

Explorer les exercices

</a>

<a href="#" class="btn btn-secondary">

Publier un exercice

</a>

</div>

<div class="stats">

<div class="stat">
<h2>10+</h2>
<p>Matières</p>
</div>

<div class="stat">
<h2>7</h2>
<p>Niveaux scolaires</p>
</div>

<div class="stat">
<h2>∞</h2>
<p>Exercices à partager</p>
</div>

</div>

</div>

<div class="image">

<div class="glow"></div>

<img src="https://images.unsplash.com/photo-1522202176988-66273c2fd55f?w=1200&q=80" alt="Étudiants travaillant ensemble">

</div>

</div>

</section>

</body>
</html>
