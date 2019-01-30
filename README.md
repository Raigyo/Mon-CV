# Becode

## HTML: CV

20190116

Aim of the exercice:
- [x] Using CSS 3
- [x] Learning Grids with CSS



<!doctype html>
<html lang="fr">
<head>
  <meta charset="utf-8">
  <title>CV Vincent Chilot</title>
   <link rel="stylesheet" type="text/css" href="style.css">
  <!--[if lt IE 9]>
  <script src="//html5shim.googlecode.com/svn/trunk/html5.js"></script>
  <![endif]-->
  <style>
  body{
    margin: 25px;
  }
  h1{
    font-size: 30px;
  }
  h2{
    font-size: 22px;
  }
  .grid-container-head {
    width: 80%;
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-template-rows: 1fr;
    grid-template-areas: "boxH1 boxH2";
    grid-template-columns: 25% 75%;
  }
  .grid-container-section {
    width: 80%;
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-template-rows: 1fr;
    grid-template-areas: "box1 box1" "box2 box3";
    grid-template-columns: 25% 75%;
  }
  .boxH1 { grid-area: boxH1; }
  .boxH2 { grid-area: boxH2; }
  .box1 { grid-area: box1; }
  .box2 { grid-area: box2; }
  .box3 { grid-area: box3; }
  </style>
</head>
<body>
<h1>CV de Vincent Chilot</h1>
<header class="grid-container-head">
  <div class="boxH1">
    <figure><img src="profile-picture.jpg" alt="Photo Vincent Chilot"/></figure>
  </div>
  <div class="boxH2">
    <h2>Informations personnelles</h2>
    <p>CHILOT Vincent Daniel Yves</p>
    <p><a href="http://www.linkedin.com/in/vincent-chilot-4a254315b">http://www.linkedin.com/in/vincent-chilot-4a254315b</a></p>
    <p>Sexe Homme | Date de naissance 25/01/1975 (43 ans) | Nationalité Belge</p>
  </div>
</header>
<section class="grid-container-section">
  <div class="box1">
    <h2>Expérience professionnelle</h2>
  </div>
  <div class="box2">
    <p>2019</p>
    <p>2002-2018</p>
    <p>1998-2001</p>
  </div>
  <div class="box3">
    <p>Développeur junior chez Becode Liège</p>
    <p>Développeur Web – Intégrateur - Rédacteur technique - Tipik Communication Agency SA</p>
    <p>Educateur - Animateur - ASBL « Maison Bizzzarre », rue Saint Léonard, Liège</p>
  </div>
</section>
<section class="grid-container-section">
  <div class="box1">
    <h2>Formations</h2>
  </div>
  <div class="box2">
    <p>Décembre 2017</p>
    <p>Septembre 2017</p>
    <p>Juin 2015</p>
  </div>
  <div class="box3">
    <p>Drupal CMS / DG COM Multisite - Novacomm</p>
    <p>Accessibilité Web pour designers et développeurs - Anysurfer</p>
    <p>Gestion print et contrôle de qualité - Tipik Communication Agency</p>
  </div>
</section>
</body>
