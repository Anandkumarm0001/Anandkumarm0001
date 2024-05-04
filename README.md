
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <title>Portfolio</title>
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet" />
  <style>
    * {
      margin: 0;
      padding: 0;
    }

    body {
      background-color: rgb(0, 0, 36);
      color: white;
      font-family: "Poppins", sans-serif;
    }

    nav {
      display: flex;
      justify-content: space-around;
      align-items: center;
      height: 45px;
      background-color: rgb(18, 18, 62);
      width: 75%;
      margin: 15px 188px ;
      border-radius: 3px
      
    }

    nav ul {
      display: flex;
      justify-content: center;
    }

    nav ul li {
      list-style: none;
      margin: 0 23px;
    }

    nav ul li a {
      text-decoration: none;
      color: white;
    }

    nav ul li a:hover {
      color: rgb(199, 199, 243);
      font-size: 1.01rem;
    }

    .left {
      font-size: 1.5rem;
    }

    .firstsection {
      display: flex;
      justify-content: space-around;
      align-items: center;
      margin: 123px 0;
    }

    .firstsection>div {
      width: 30%;
    }

    .leftsection {
      font-size: 2.4rem;
    }
    .leftsection .btn{
      padding: 12px 10px;
      background: rgb(23, 26, 54);
      color: white;
      border: 2px solid white;
      border-radius: 5px;
      font-size: 12px;
      margin-top: 30px;
      box-shadow: 1px 1.7px white;
    }

    .rightsection img {
      width: 80%;
    }

    .purple {
      color: rgb(182, 111, 248);
    }

    #element {
      color: rgb(182, 111, 248);
    }

    .secondsection {
      max-width: 80vw;
      margin: auto;
      height: 80vh;
    }

    main hr {
      border: 0;
      background-color: rgb(182, 111, 248);
      height: 1.2px;
      margin: 60px 84px;
    }

    .secondsection h1 {
      font-size: 1.7rem;
    }

    .text-grey {
      color: rgb(182, 111, 248);
    }

    .secondsection .box {
      background-color: white;
      width: 80vw;
      height: 2px;
      margin: 56px 0;
      display: flex;
    }

    .secondsection .vertical {
      height: 60px;
      background-color: white;
      width: 1px;
      margin: 0 100px;
    }

    .image-top {
      width: 50px;
      position: relative;
      top: -51px;
      left: -25px;
    }

    .vertical-title {
      font-size: 16px;
      position: relative;
      top: 20px;
      width: 150px;
    }

    .vertical-desc {
      position: relative;
      top: 21px;
      color: gray;
      width: 150px;
      font-size: 9px;
    }

    .image-top-M {
      width: 100px;
      position: relative;
      top: -55px;
      left: -45px;
    }

    .image-top-L {
      width: 44px;
      position: relative;
      top: -42px;
      left: -25px;
      border-radius: 3px 3px;
    }

    footer {
      background-color: rgb(36, 44, 69);
    }

    .footer {
      display: flex;
      padding: 23px 122px;
      justify-content: space-evenly;
      color: white;
    }
    .footer ul{
      list-style: none;
    }
    .footer > div{
      width: 223px;
    }
    footer .footer-rights{
       text-align: center;
       padding: 7px 40px;
       color: rgb(214, 209, 209);
       font-size: small;
       
    }
  </style>
</head>

<body>
  <header>
    <nav>
      <div class="left">Anand's Portfolio</div>
      <div class="right">
        <ul>
          <li><a href="/">Home</a></li>
          <li><a href="/">About</a></li>
          <li><a href="/">Services</a></li>
          <li><a href="/">Project</a></li>
          <li><a href="/">Contact Me</a></li>
        </ul>
      </div>
    </nav>
  </header>
  <main>
    <section class="firstsection">
      <div class="leftsection">
        Hi, My name is <span class="purple">Anand</span>
        <div>and I am passionate</div>
        <span id="element"></span>
        <div class="buttom">
          <button class="btn">Download Resume</button>
          <button class="btn">Visit Github</button>
        </div>
      </div>
      <div class="rightsection">
        <img src="images/bg.png" alt="" />
      </div>
    </section>
    <hr />
    <section class="secondsection">
      <span class="text-grey">What I have done so far</span>
      <h1>Work Experience</h1>
      <div class="box">
        <div class="vertical">
          <img class="image-top" src="images/developer.png" alt="" />
          <div class="vertical-title">HTML Developer</div>
          <div class="vertical-desc">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Vero,
            aliquid! Lorem ipsum dolor, sit amet consectetur adipisicing elit.
            Facilis, autem.
          </div>
        </div>
        <div class="vertical">
          <img class="image-top" src="images/css.png" alt="" />
          <div class="vertical-title">HTML Developer</div>
          <div class="vertical-desc">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Vero,
            aliquid! Lorem ipsum dolor, sit amet consectetur adipisicing elit.
            Facilis, autem.
          </div>
        </div>
        <div class="vertical">
          <img class="image-top-M" src="images/bootsharpt.png" alt="" />
          <div class="vertical-title">HTML Developer</div>
          <div class="vertical-desc">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Vero,
            aliquid! Lorem ipsum dolor, sit amet consectetur adipisicing elit.
            Facilis, autem.
          </div>
        </div>
        <div class="vertical">
          <img class="image-top-L" src="images/js.webp" alt="" />
          <div class="vertical-title">HTML Developer</div>
          <div class="vertical-desc">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Vero,
            aliquid! Lorem ipsum dolor, sit amet consectetur adipisicing elit.
            Facilis, autem LORE,
          </div>
        </div>
      </div>
      </div>
    </section>
    <footer>
      <div class="footer">
        <div class="footer-first">Anand's Developer Portfolio</div>
        <div class="footer-second">
          <ul>
            <li>Home </li>
            <li> About</li>
            <li>Services</li>
            <li>Contact</li>
          </ul>
        </div>
        <div class="footer-third">
          <ul>
            <li>Home</li>
            <li> About</li>
            <li>Services</li>
            <li>Contact</li>
          </ul>
        </div>
        <div class="footer-fourth">
          <ul>
            <li>Home</li>
            <li> About</li>
            <li>Services</li>
            <li>Contact</li>
          </ul>
        </div>
      </div>
      <div class="footer-rights">
        copyright &#169;	anandportfolio.com || All right reserved
      </div>
    </footer>
  </main>
  <script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>
  <script>
    var typed = new Typed("#element", {
      strings: ["Web Developer", "&amp; Web Designer."],
      typeSpeed: 50,
    });
  </script>
</body>

</html><h1 align="center">Hi 👋, I'm Anand Mahato</h1>
<h3 align="center">A passionate frontend developer from India</h3>

<p align="left"> <img src="https://komarev.com/ghpvc/?username=anandkumarm0001&label=Profile%20views&color=0e75b6&style=flat" alt="anandkumarm0001" /> </p>

<p align="left"> <a href="https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=anandkumarm0001" alt="anandkumarm0001" /></a> </p>

<p align="left"> <a href="https://twitter.com/" target="blank"><img src="https://img.shields.io/twitter/follow/?logo=twitter&style=for-the-badge" alt="" /></a> </p>

- 📫 How to reach me **anandkumarm0001@gmail.com**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://linkedin.com/in/anand mahato" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="anand mahato" height="30" width="40" /></a>
<a href="https://instagram.com/anurag_o01" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="anurag0o1" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://getbootstrap.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="bootstrap" width="40" height="40"/> </a> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a> <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://nodejs.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/> </a> </p>

<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=anandkumarm0001&show_icons=true&locale=en&layout=compact" alt="anandkumarm0001" /></p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=anandkumarm0001&show_icons=true&locale=en" alt="anandkumarm0001" /></p>

<p><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=anandkumarm0001&" alt="anandkumarm0001" /></p>


