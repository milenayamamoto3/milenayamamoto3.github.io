<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portifólio Milena Yamamoto</title>
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,300;0,700;0,900;1,300;1,700;1,900&display=swap" rel="stylesheet">
    <!-- Dev Icon Fonts -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.15.1/devicon.min.css">
    <!-- CSS do Projeto-->
    <link rel="stylesheet" href="css/styles.css">
</head>
<body>
    <main id="container">
      <aside id="bio-container">
        <h2>山本真浪!</h2>
        <img id="bio-img" src="./img/meuperfil.jpeg" alt="Milena Yamamoto">
        <p>初めまして。👋, 私は山本真浪とお申します!<span class="highlight">Python開発者</span>.</p>
        <p id="welcome-text">ようこそ!</p>
        <ul id="social-container">
          <li><a href="https://www.linkedin.com/in/milena-manamy-9bb9b124a/" target="_blank"><ion-icon name="logo-linkedin"></ion-icon></a></li>
        </ul>
        <div id="email-container">
          <ion-icon name="mail-outline"></ion-icon><a href="mailto:milymanamy3@gmail.com">milymanamy3@gmail.com</a>
        </div>
      </aside> 
      <section id="about-container">
        <h1 id="name">山本真浪</h1>
        <p id="title"><span class="highlight">Python開発者</span></p>
        <p class="description">現在、<span class="highlight">Pythonプログラミング言語</span> と <span class="highlight">IT管理</span>を勉強中です。</p>
        <p class="description"><b>私のスキルについてはまだ習得しておらず、そこに記載されているのは単なるトレーニングテストです。</b></p>
        <a href="https://github.com/milenayamamoto3" id="btn-projects"><ion-icon name="share-social-outline"></ion-icon><span>プロジェクトを見る</span></a>
        <h2 id="skills-section-title">私のスキル</h2>
        <p class="description">私が習得している技術を知ってください:</p>
        <div id="skills-container">
          <div class="skills-box">
            <p class="skills-title">Front-end</p>
            <i class="devicon-html5-plain colored"></i>
            <i class="devicon-css3-plain colored"></i>
            <i class="devicon-javascript-plain colored"></i>
          </div>
          <div class="skills-box">
            <p class="skills-title">Back-end</p>
            <i class="devicon-php-plain colored"></i>
            <i class="devicon-nodejs-plain colored"></i>
            <i class="devicon-python-plain colored"></i>
          </div>
          <div class="skills-box">
            <p class="skills-title">Databases</p>
            <i class="devicon-mysql-plain colored"></i>
            <i class="devicon-mongodb-plain colored"></i>
          </div>
          <div class="skills-box">
            <p class="skills-title">Front-end Frameworks</p>
            <i class="devicon-react-plain colored"></i>
            <i class="devicon-vuejs-plain colored"></i>
          </div>
          <div class="skills-box">
            <p class="skills-title">Back-end Frameworks</p>
            <i class="devicon-laravel-plain colored"></i>
            <i class="devicon-django-plain colored"></i>
          </div>
          <div class="skills-box">
            <p class="skills-title">Tools</p>
            <i class="devicon-linux-plain colored"></i>
            <i class="devicon-docker-plain colored"></i>
          </div>
        </div>
    </section>
    </main>
    <!-- Ion Icons -->  
    <script type="module" src="https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.esm.js"></script>
</body>
</html>