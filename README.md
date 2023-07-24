<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Escape Game Harry Potter - L'Énigme de Poudlard</title>
  <link href="https://fonts.googleapis.com/css2?family=Courgette&display=swap" rel="stylesheet">
  <style>
    /* Utilise la police Courgette pour le texte principal de la page */
    body {
      font-family: "Courgette", cursive;
      background-image: url("https://i.etsystatic.com/15156453/r/il/2cee44/3146705882/il_fullxfull.3146705882_oflm.jpg");
      background-size: cover;
    }
    .header {
      text-align: center;
      padding: 20px;
      background-color: #725e49;
      color: #FFFFFF;
    }
    .container {
      max-width:1000px;
      margin: 0 auto;
      padding: 20px;
      background-color: #FFF8DC; /* Couleur claire pour l'intérieur du parchemin */
      border: 10px solid #FFF8DC; /* Bordure foncée pour délimiter le parchemin */
      box-shadow: 5px 5px 5px #837159; /* Ombre pour donner du relief au parchemin */
    }
    .start-button {
      display: block;
      width: 200px;
      margin: 0 auto;
      padding: 15px;
      background-color: #4CAF50;
      color: #FFFFFF;
      text-align: center;
      text-decoration: none;
      font-size: 24px;
      border-radius: 8px;
      transition: background-color 0.3s;
    }
    .start-button:hover {
      background-color: #0d250f;
    }
    /* Augmente la taille de la police des titres h2 */
    h2 {
      font-size: 28px; /* Double la taille de la police des titres h2 */
    }
    /* Augmente la taille de la police des paragraphes */
    p {
      font-size: 24px; /* Double la taille de la police des paragraphes */
    }
    /* Augmente la taille de la police des liens */
    a {
      font-size: 24px; /* Met la taille de la police des liens à 32px */
    }
    /* Personnalise la taille du logo */
    .logo {
      max-width: 200px; /* Ajuste cette valeur selon la taille souhaitée */
      display: block;
      margin: 0 auto 20px;
    }
    .play-button {
      position: absolute;
      top: 15px;
      left: 15px;
      cursor: pointer;
      background-color: #4b4b4b;
      color: #000000;
      padding: 5px 10px;
      border-radius: 5px;
    }
  </style>
</head>
<body>
    <div class="header">
    <!-- Image logo -->
    <img src="C:\Users\Vincent\Desktop\01-08\images\800px-Blason_Relief_-_Harry_Potter_hpbig.png" alt="Logo Escape Game Harry Potter" class="logo">
    <h1>To :</h1>
    <p>Albert Duck 
    <p>6 rue Anna Politkovskaia
    <p>A côté de la piscine 
    <p>31200 Toulouse
    </p>
  </div>
  <audio id="ambianceSonore">
    <source src="C:\Users\Vincent\Desktop\01-08\Sons\Hp_theme_piano.mp3" type="audio/mpeg">
    <!-- Ajoutez d'autres sources si nécessaire pour une compatibilité avec différents navigateurs -->
    <!-- Par exemple : <source src="chemin/vers/mon-fichier-audio.ogg" type="audio/ogg"> -->
  </audio>
  <div class="play-button" onclick="toggleAmbianceSonore()">Play / Pause</div>
  <div class="container">
    <h2>A l'attention de Albert Duck</h2>
    <p>Très cher Albert,

    <p> Je me permets de m'adresser à vous en tant que représentant de l'école de sorcellerie Poudlard, afin de vous présenter mes humbles excuses pour une regrettable méprise qui remonte à 19 ans de cela. Il semble qu'une inexcusable erreur ait été commise à cette époque, et c'est avec une profonde consternation que nous avons pris conscience que votre lettre d'admission n'a jamais été dûment délivrée.
      
    <p>  Lorsqu'il est question de circonstances inexplicables, il nous a été révélé que le hibou magique, spécialement chargé de livrer votre précieuse lettre, a été victime d'une petite mésaventure. Ce facétieux hibou, ayant un appétit insatiable pour les graines les plus délicieuses, s'est laissé séduire par une délicieuse réserve de graines enchantées lors de sa mission. Emporté par son goût pour la gastronomie, notre courrier volant a préféré faire une halte gourmande plutôt que de mener à bien sa tâche.
      
   <p> Je tiens à exprimer toute la sincérité de nos regrets quant à cette situation qui, je le comprends parfaitement, a pu susciter déception et frustration. Néanmoins, nous désirons aujourd'hui rectifier cette malencontreuse circonstance. La prestigieuse école de Poudlard souhaite ardemment vous offrir une seconde chance, une occasion nouvelle de vous permettre de faire partie de notre établissement, où le savoir magique et l'excellence pédagogique se conjuguent harmonieusement.
      
   <p> Au sein de notre institution, nous reconnaissons en vous des aptitudes exceptionnelles et un potentiel magique indéniable. Par conséquent, nous souhaitons ardemment vous accueillir parmi nous, dans un esprit de bienveillance et de dévouement à votre épanouissement personnel et académique.
      
   <p> L'expérience qui vous attend à Poudlard s'avère être une immersion dans un monde ensorcelant, où les connaissances prodigieuses côtoient les mystères les plus fascinants. Vous y découvrirez l'art subtil de la magie, et tisserez des liens indéfectibles avec d'autres esprits éclairés et ambitieux.
      
    <p>Sachez que notre équipe pédagogique, constituée des plus éminents professeurs en la matière, œuvrera sans relâche pour vous apporter un enseignement de qualité, éclairé par la passion et l'expertise. Nous serons honorés de vous guider dans votre parcours d'apprentissage, afin que votre potentiel se déploie pleinement et que vous puissiez réaliser des prouesses magiques dignes des plus grands sorciers et sorcières de notre temps.
      
    <p> Si cette proposition suscite votre intérêt, nous vous invitons à vous rendre au Chemin de Traverse, où vous pourrez acquérir vos fournitures scolaires auprès des commerces spécialisés, avant d'embarquer à bord du Poudlard Express, en direction de notre école majestueuse.
      
   <p>En vous adressant ces mots, je tiens à vous assurer que nous mettrons tout en œuvre pour vous permettre de vivre pleinement cette opportunité exceptionnelle. Si vous décidez de nous rejoindre, nous vous promettons une expérience inoubliable, riche en découvertes et en apprentissages.
      
   <p> Veuillez, je vous prie, agréer, très cher Albert, l'expression de nos plus sincères regrets, et l'assurance de notre bienveillance et de notre profonde reconnaissance.
      
   <p> Bien amicalement,
      
   <p> Octave M.
   <p> Directeur de Poudlard</p>

    <a class="start-button" href="C:\Users\Vincent\Desktop\01-08\page2.html">Accepter l'invitation</a>
  </div>
  <script>
    var ambianceSonore = document.getElementById('ambianceSonore');
    var isPlaying = false;

    // Fonction pour démarrer ou arrêter l'ambiance sonore
    function toggleAmbianceSonore() {
      if (!isPlaying) {
        ambianceSonore.play();
      } else {
        ambianceSonore.pause();
      }
      isPlaying = !isPlaying;
    }
  </script>
  </body>
</html>
# nikitabirthday
Site anniversaire nikita
