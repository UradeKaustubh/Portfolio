<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Kaustubh Urade</title>
  <link rel="icon" href="images/Logo.jpg">
  <link rel="stylesheet" href="style.css" />
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link href="https://fonts.googleapis.com/css2?family=Poppins&family=Satisfy&display=swap" rel="stylesheet" />
  <link href="https://fonts.googleapis.com/css2?family=Chakra Petch&display=swap" rel="stylesheet">
  <script src="https://kit.fontawesome.com/30692d030a.js" crossorigin="anonymous"></script>
  <script src="https://unpkg.com/typed.js@2.0.15/dist/typed.umd.js"></script>
</head>

<body>
  <div id="header">
    <div class="containerr">
      <nav>
        <p class="logo">Portfolio.</p>
        <ul id="sidemenu">
          <li><a href="#header"> Home </a></li>
          <li><a href="#about"> About </a></li>
          <li><a href="#portfolio"> Portfolio </a></li>
          <li><a href="#services"> Services </a></li>
          <li><a href="#contact"> Contact </a></li>
          <i class="fas fa-times" onclick="closemenu()"></i>
        </ul>
        <i class="fas fa-bars" onclick="openmenu()"></i>
      </nav>
      <div class="banner">
        <div class="header-text">
          <h1>Hello World,<br>I'am Kaustubh Urade</h1>
          <p>A Passionate &nbsp;<span class="text"></span></p>
        </div>
        <div>
          <img src="images/banner-image.png">
        </div>
      </div>
    </div>
  </div>
  <div class="blr">
    <div id="about">
      <div class="container">
        <div class="tyt">
          <div class="row">
            <div class="about-col-1">
              <img src="images/user3.jpg" />
            </div>
            <div class="about-col-2">
              <h1 class="sub-title">About Me</h1>
              <p class="about-text">
                I'm Kaustubh Urade, a passionate and Driven Computer
                Engineering Student Seeking Challenging Job or Internship
                Opportunities. Currently honing skills in software development & designing. Eager
                to contribute to a dynamic organization that fosters growth and
                professional development. Open to exciting internship experiences
                and career opportunities in the field of computer engineering.
                Let's connect and explore how we can collaborate!

              </p>
              <div class="tab-title">
                <p class="tab-links active-link" onclick="opentab('skills')">
                  Skills
                </p>
                <p class="tab-links" onclick="opentab('experience')">
                  Experience
                </p>
                <p class="tab-links" onclick="opentab('education')">Education</p>
              </div>
              <div class="tab-contents active-tab" id="skills">
                <ul>
                  <li><span>FrontEnd Developer</span><br />HTML, CSS, JavaScript , ReactJs</li>
                  <li><span>Web Designer</span><br />Figma</li>
                  <li>
                    <span>Praogrammer</span><br />Java, C++, JavaScript
                  </li>
                </ul>
              </div>
              <div class="tab-contents" id="experience">
                <ul>
                  <br>
                  <li><span>Cascode Intern</span><br />Feb-Mar 2023</li>
                  <br><br><br><br><br>
                </ul>
              </div>
              <div class="tab-contents" id="education">
                <ul>
                  <li><span>Sinhgad Academy Of Engineering Pune</span><br>Bachlore Of Engineering (2020 - 2024)</li>
                  <li><span>Lions International Jr College Wani</span><br>HSC (2018 - 2020)</li>
                  <li>
                    <span>Adarsha Heigh School Ghonsa</span><br>SSC (2017 - 2018)
                  </li>
                </ul>
              </div>

            </div>
          </div>
        </div>
      </div>
    </div>
    <div id="portfolio">
      <div class="container">
        <div class="tyt">
          <h1 class="sub-title">My Work</h1>
          <div class="work-list">
            <div class="work">
              <img src="images/work-1.png" />
              <div class="layer">
                <h3>Social Media App</h3>
                <p>
                  Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quos
                  tempore nihil voluptates eaque non earum aliquid numquam. Lorem ipsum dolor sit amet consectetur
                  adipisicing elit. Voluptatem sunt eius a ab libero? Autem quam dolorum accusamus excepturi voluptatem!
                </p>
                <a href="http://github.com/UradeKaustubh" target="_blank"><i class="fa-brands fa-github g"></i></a>
              </div>
            </div>
            <div class="work">
              <img src="images/work-2.png" />
              <div class="layer">
                <h3>Social Media App</h3>
                <p>
                  Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quos
                  tempore nihil voluptates eaque non earum aliquid numquam. Lorem ipsum dolor sit amet consectetur
                  adipisicing elit. Quas tenetur necessitatibus hic id impedit? Incidunt maxime fuga saepe quaerat
                  maiores?
                </p>
                <a href="http://github.com/UradeKaustubh" target="_blank"><i class="fa-brands fa-github g"></i></a>
              </div>
            </div>
            <div class="work">
              <img src="images/work-3.png" />
              <div class="layer">
                <h3>Social Media App</h3>
                <p>
                  Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quos
                  tempore nihil voluptates eaque non earum aliquid numquam. Lorem, ipsum dolor sit amet consectetur
                  adipisicing elit. Quo eveniet asperiores, aperiam dicta aspernatur sint aut dolorum placeat expedita
                  at!
                </p>
                <a href="http://github.com/UradeKaustubh" target="_blank"><i class="fa-brands fa-github g"></i></a>
              </div>
            </div>
          </div>
          <a href="#portfolio" class="btn">See More</a>
        </div>
      </div>
    </div>
    <div id="services">
      <div class="container">
        <div class="tyt">
          <h1 class="sub-title">My Services</h1>
          <div class="services-list">
            <div>
              <i class="fa-solid fa-code"></i>
              <h2>Front-End Development</h2>
              <p>I'm a passionate and dedicated aspiring Front-End Web Developer, eager to embark on a journey of
                turning code into captivating web experiences. Although I'm new to the industry, my enthusiasm and
                commitment are
                boundless. <br> I believe that the front end of a website is the digital handshake with your audience.
              </p>
              <a href="#services">Learn More <i class="fa-solid fa-circle-info"></i></a>
            </div>
            <div>
              <i class="fa-solid fa-palette"></i>
              <h2>Web UI Designing</h2>
              <p>I'm a passionate and enthusiastic aspiring Web UI Designer, with a deep love for creating visually
                captiving and user-centric digital experience.
                While I may be new to the industry, my creativity and dedication know no bounds. <br> I believe in the
                power
                of web design to create stunning and functional online experiences.</p>
              <a href="#services">Learn More <i class="fa-solid fa-circle-info"></i></a>
            </div>
            <div>
              <i class="fa-brands fa-app-store"></i>
              <h2>Software Development</h2>
              <p>As a passionate and aspiring Software Developer, I am committed to delivering high-quality Software
                solutions and contributing to the success of projects. I possess a strong foundation in Java
                programming, software development principles, and a thirst for continuous learning. My goal is to
                collaborate with teams to build efficient, scalable, and user-friendly applications.</p>
              <a href="#services">Learn More <i class="fa-solid fa-circle-info"></i></a>
            </div>
          </div>
          <a href="#services" class="btn">See More </a>
        </div>
      </div>
    </div>
    <div id="contact">
      <div class="container">
        <div class="tyt">
          <div class="row">
            <div class="contact-left">
              <h1 class="sub-title">Contact Me</h1>
              <p><i class="fa-solid fa-envelope"></i>UradeKaustubh@gmail.com</p>
              <p><i class="fa-solid fa-phone"></i>9359312570</p>
              <div class="social-icons">
                <a href="https://www.linkedin.com/in/kaustubhurade" target="_blank"><i
                    class="fa-brands fa-linkedin l "></i></a>
                <a href="http://github.com/UradeKaustubh" target="_blank"><i class="fa-brands fa-github g"></i></a>
                <a href="https://instagram.com/kaustubh._.ll?igshid=MzNlNGNkZWQ4Mg==" target="_blank"><i
                    class="fa-brands fa-instagram i"></i></a>
                <a href="https://twitter.com/UradeKaustubh?t=PpCpResXHCc9G_wW6XFZPg&s=09" target="_blank"><i
                    class="fa-brands fa-square-twitter t"></i></a>
              </div>
              <a href="images/my-cv.pdf" download class="btn btn2">Download CV</a>
            </div>
            <div class="contact-right">
              <form>
                <input type="text" name="name" placeholder="Your Name" required />
                <input type="email" name="email" placeholder="Your Email" required />
                <textarea name="Message" rows="6" placeholder="Your Massage"></textarea>
                <button type="submit" class="btn btn2 ">Submit</button>
              </form>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="copyright">
      <p>
        Copyright ©️ Kaustubh. Made by Love
        <i class="fa-solid fa-heart fa-beat"></i>
      </p>
    </div>
  </div>
  </div>
  <style>
    * {
  margin: 0;
  padding: 0;
  font-family: "Chakra Petch";
  font-weight: 900;
  box-sizing: border-box;
  }

html {
  scroll-behavior: smooth;
}

body {
  color: #000000;
  background-image: url(images/BackgroumdGif.gif);
  background-size: cover;
  background-position: center;
  background-attachment: fixed;
  text-align: justify;
}

#header {
  padding: 30px 7%;
}

.container {
  padding: 4% 7%;
}

nav {
  display: flex;
  align-items: center;
  justify-content: space-between;
  flex-wrap: wrap;
}

#sidemenu {
  margin-top: -7px;
}

.logo {
  font-size: 70px;
  background: linear-gradient(to right, #96f6ff, #6ab2fb);
  -webkit-text-fill-color: transparent;
  -webkit-background-clip: text;
  background-clip: none;
}
.logo:hover {
  transition: 0.5s;
}

nav ul li {
  display: inline-block;
  list-style: none;
}

nav ul li a {
  color: #000000;
  font-size: 20px;
  text-decoration: none;
  margin-right: 20px;
  position: relative;
  padding: 8px 15px;
  border-radius: 25px;
  box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
}

nav ul li a:hover {
  bottom: 5px;
  transition: 0.3s;
  background: linear-gradient(to right, #96f6ff, #6ab2fb);
  -webkit-text-fill-color: transparent;
  -webkit-background-clip: text;
  background-clip: none;
}

.banner {
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin-top: 6%;
  background-attachment: fixed;
}

.banner img {
  animation: floatImage 4s ease-in-out infinite;
  padding-left: 10%;
}

@keyframes floatImage {
  0% {
    transform: translateY(0);
  }

  50% {
    transform: translateY(-2.4rem);
  }

  100% {
    transform: translateY(0);
  }
}
.header-text {
  padding-left: 5%;
}

.header-text h1 {
  font-size: 60px;
}

.header-text p {
  font-size: 40px;
  font-weight: bold;
}

.header-text span {
  background: linear-gradient(to right, #96f6ff, #6ab2fb);
  -webkit-text-fill-color: transparent;
  -webkit-background-clip: text;
  background-clip: none;
  font-size: 60px;
  font-weight: bolder;
}

.blr {
  background: transparent;
  backdrop-filter: blur(10px);
  box-shadow: 0 0 30px rgba(0, 0, 0, 0.5);
}

.tyt {
  background: transparent;
  backdrop-filter: blur(70px);
  box-shadow: 0 0 30px rgba(0, 0, 0, 0.5);
  border-radius: 20px;
  padding: 2%;
}

.row {
  display: flex;
  align-items: center;
  justify-content: space-between;
  flex-direction: row;
  flex-wrap: wrap;
}

.about-col-1 {
  flex-basis: 35%;
}

.about-col-1 img {
  width: 100%;
  border-radius: 50px;
}

.about-col-2 {
  flex-basis: 60%;
}
.about-text {
  padding: 50px 0 50px 0;
  font-size: 30px;
}

.sub-title {
  font-size: 60px;
  font-weight: 600;
  background: linear-gradient(#96f6ff, #6ab2fbcb);
  -webkit-text-fill-color: transparent;
  -webkit-background-clip: text;
  background-clip: none;
}

.tab-title {
  display: flex;
  margin: 20px 0 40px 0;
}

.tab-links {
  margin-right: 50px;
  font-size: 23px;
  cursor: pointer;
  position: relative;
  padding: 8px 15px;
  border-radius: 25px;
  box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
}

.tab-links:hover {
  transform: scale(1.06);
  transition: 0.3s;

  background: linear-gradient(to right, #96f6ff, #3a9cff);
  -webkit-text-fill-color: transparent;
  -webkit-background-clip: text;
  background-clip: none;
  box-shadow: 0 5px 10px rgba(0, 0, 0, 0.5);
}
.tab-contents {
  display: flex;
}

.tab-contents ul li {
  font-size: 20px;
  list-style: none;
  margin: 10px 0;
  font-weight: normal;
}

.tab-contents ul li span {
  background: linear-gradient(to right, #96f6ff, #3a9cff);
  -webkit-text-fill-color: transparent;
  -webkit-background-clip: text;
  background-clip: none;
  font-size: 30px;
}

.tab-contents {
  display: none;
}

.tab-contents.active-tab {
  display: block;
}
#portfolio {
  text-align: center;
}

.work-list {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  grid-gap: 40px;
  margin-top: 50px;
}

.work {
  position: relative;
  overflow: hidden;
  border-radius: 50px;
}
.work:hover {
  transition: 1s;
  box-shadow: 10px 5px 20px rgba(0, 0, 0, 0.5);
}

.work img {
  width: 100%;
  display: block;
  transition: transform 0.5s;
}

.layer {
  width: 100%;
  height: 0;
  background: linear-gradient(to right, #96f6ff91, #6ab2fb);
  border-radius: 10px;
  position: absolute;
  left: 0;
  bottom: 0;
  overflow: hidden;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  padding: 0 40px;
  text-align: center;
  font-size: 14px;
  transition: height 0.5s;
}

.layer h3 {
  font-weight: 700;
  font-size: 30px;
  margin-bottom: 20px;
}
.layer p {
  text-align: justify;
  font-size: 20px;
  font-weight: 100;
}

.layer a {
  margin-top: 20px;
  color: #000000;
  text-decoration: none;
  font-size: 28px;
  line-height: 47px;
  background: #fff;
  width: 45px;
  height: 45px;
  border-radius: 50%;
  text-align: center;
}
.layer a:hover {
  transition: 1s;
  color: #fff;
  background: #000000;
  box-shadow: 0px 10px 17px rgb(255, 255, 255);
}

.work:hover img {
  transform: scale(1.1);
}

.work:hover .layer {
  height: 100%;
}

.btn {
  display: block;
  margin: 50px auto;
  width: fit-content;
  padding: 14px 50px;
  border-radius: 15px;
  text-decoration: none;
  color: #000000;
  box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
  font-size: 20px;
}

.btn:hover {
  bottom: 6px;
  background: linear-gradient(to right, #96f6ff, #0273e3);
  -webkit-text-fill-color: transparent;
  -webkit-background-clip: text;
  background-clip: none;
  transition: 0.5s;
  box-shadow: 0 5px 10px rgba(0, 0, 0, 0.5);
}

#services {
  padding: 30px 0;
  text-align: center;
}

.services-list {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  grid-gap: 40px;
  margin-top: 50px;
}

.services-list div {
  background: transparent;
  padding: 40px;
  font-size: 13px;
  border-radius: 50px;
  box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
  background: linear-gradient(#ffffff, rgb(230, 230, 230));
}
.services-list div i {
  font-size: 50px;
  margin-bottom: 30px;
}
.services-list div h2 {
  font-size: 30px;
  margin-bottom: 15px;
}
.services-list div p {
  font-size: 23px;
  font-weight: 100;
  margin-bottom: 20px;
  margin-top: 30px;
  text-align: justify;
}
.services-list div a {
  text-decoration: none;
  color: #000000;
  font-size: 12px;
  margin-top: 20px;
  background-color: transparent;
  padding: 10px;
  border-radius: 15px;
  box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
}
.services-list div a:hover {
  box-shadow: 0 5px 10px rgba(0, 0, 0, 0.5);
}
.services-list div a i {
  font-size: 12px;
}
.services-list div:hover {
  background: linear-gradient(#96f6ff78, #6ab2fbc5);
  transition: 0.5s;
  transform: scale(1.025);
  box-shadow: 0 5px 10px rgba(0, 0, 0, 0.6);
}

#contact {
  padding: 5% 0 4% 0;
}

.contact-left {
  flex-basis: 35%;
  margin-top: -90px;
}

.contact-right {
  flex-basis: 60%;
}

.contact-left p {
  margin-top: 30px;
  font-size: 20px;
}

.contact-left p i {
  background: linear-gradient(#96f6ff, #6ab2fb);
  -webkit-text-fill-color: transparent;
  -webkit-background-clip: text;
  background-clip: none;
  margin-right: 15px;
  font-size: 25px;
}

.social-icons {
  margin-top: 30px;
}

.social-icons a {
  text-decoration: none;
  font-size: 30px;
  margin-right: 15px;
  color: #6a6969;
  display: inline-block;
}

.social-icons .l:hover {
  color: #0077b5;
  transform: translateY(-5px);
}
.social-icons .g:hover {
  color: #000000;
  transform: translateY(-5px);
}
.social-icons .i:hover {
  color: #ff004f;
  transform: translateY(-5px);
}
.social-icons .t:hover {
  color: #88d3ff;
  transform: translateY(-5px);
}

.btn.btn2 {
  display: inline-block;
  border-width: 0;
}

.contact-right form {
  width: 100%;
}
form input,
form textarea {
  width: 100%;
  border: 0;
  outline: none;
  background: transparent;
  backdrop-filter: blur(90px);
  box-shadow: 0 0 30px rgba(0, 0, 0, 0.5);
  border-radius: 20px;
  padding: 15px;
  margin: 15px 0;
  color: #000000;
  font-size: 18px;
  border-radius: 15px;
}

.copyright {
  text-align: center;
  background: transparent;
  backdrop-filter: blur(70px);
  box-shadow: 0 0 30px rgba(0, 0, 0, 0.5);
  border-radius: 20px;
  margin: 0 7% 0 7%;
}

.copyright p {
  padding: 20px;
}

.copyright i {
  color: #ff004f;
}

nav .fas {
  display: none;
}

/* ----------CSS For small screen---------- */

@media only screen and (max-width: 1650px) {
  .banner img {
    width: 90%;
    margin-top: 10%;
  }
  .banner {
    flex-direction: column;
    margin-top: 10%;
    margin-bottom: 10%;
  }
  .layer h3 {
    font-size: 20px;
  }
  .layer p {
    font-size: 15px;
  }
  .services-list div p {
    font-size: 15px;
  }
}

@media only screen and (max-width: 1240px) {
  .banner img {
    width: 0%;
  }
  .banner {
    display: flex;
    align-items: center;
    margin-top: 30%;
    margin-bottom: 30%;
  }

  .header-text h1 {
    font-size: 50px;
  }
  .header-text p {
    font-size: 20px;
  }
  .header-text span {
    font-size: 25px;
  }

  nav .fas {
    display: block;
    font-size: 25px;
  }

  nav ul .fas {
    position: absolute;
    top: 35px;
    left: 125px;
    cursor: pointer;
  }
  nav ul {
    background: linear-gradient(#96f6ff, #6ab2fb);
    position: fixed;
    top: 0;
    right: -200px;
    width: 200px;
    height: fit-content;
    padding-top: 50px;
    z-index: 2;
    transition: right 0.5s;
    border-radius: 15px;
  }

  nav ul li {
    display: block;
    margin: 25px;
    margin-top: 50px;
  }

  nav ul li a:hover {
    bottom: 5px;
    background: linear-gradient(to right, #000000, #000000);
    -webkit-text-fill-color: transparent;
    -webkit-background-clip: text;
    background-clip: none;
    box-shadow: 0 5px 10px rgba(69, 65, 65, 0.899);
  }

  .sub-title {
    font-size: 50px;
    text-align: center;
  }
  .row {
    display: flex;
    flex-wrap: nowrap;
    flex-direction: column;
    padding: 5%;
  }
  .about-col-1 {
    flex-basis: 100%;
  }

  .about-text {
    padding: 20px 0 5px 0;
    font-size: 20px;
  }

  .about-col-2 {
    font-size: 14px;
  }
  .contact-left {
    margin-top: 0;
    text-align: center;
  }
  .btn.btn2 {
    display: block;
  }
}

@media only screen and (max-width: 650px) {
  body {
    color: #000000;
    background-image: url(images/gif121.gif);
    background-size: cover;
    background-position: center;
    background-attachment: fixed;
  }
  .logo {
    font-size: 40px;
  }

  .banner img {
    width: 0;
  }

  .banner {
    display: flex;
    width: 100%;
    align-items: center;
    margin-top: 100%;
    margin-bottom: 100%;
  }

  .blr {
    width: 100%;
  }
  .tyt {
    padding: 15px;
  }
  .header-text h1 {
    font-size: 30px;
  }
  .header-text p {
    font-size: 20px;
  }
  .header-text span {
    font-size: 25px;
  }
  .sub-title {
    font-size: 30px;
    text-align: center;
  }
  .row {
    flex-direction: column;
  }

  .about-col-1 {
    flex-basis: 100%;
  }

  .about-text {
    padding: 20px 0 5px 0;
    font-size: 15px;
  }

  .about-col-2 {
    font-size: 14px;
  }

  .tab-title {
    display: flex;
    margin: 20px 0 20px 0;
  }
  .tab-contents ul li {
    font-size: 12px;
  }
  .tab-contents ul li span {
    font-size: 20px;
  }

  .tab-links {
    font-size: 9px;
    margin-right: 15px;
  }
  .services-list div {
    background: transparent;
    padding: 5%;
  }
  .services-list div i {
    font-size: 40px;
    margin-bottom: 15px;
  }
  .services-list div h2 {
    font-size: 25px;
    font-weight: 700;
    margin-bottom: 0px;
  }
  .services-list div p {
    font-size: 15px;
    font-weight: 300;
    margin-bottom: 20px;
    margin-top: 10px;
  }

  .services-list div a {
    font-size: 10px;
    padding: 7px;
  }
  .services-list div a i {
    font-size: 10px;
  }

  .btn {
    padding: 8px 20px;
    font-size: 12px;
    margin: 20px auto;
  }
  .btn.btn2 {
    display: block;
  }

  .contact-left,
  .contact-right {
    flex-basis: 100%;
  }
  .contact-left {
    margin-top: 0;
    text-align: center;
  }
  form input,
  form textarea {
    font-size: 12px;
  }
  .contact-left p {
    font-size: 15px;
  }
  .contact-left p i {
    font-size: 18px;
    margin-right: 8px;
  }

  .copyright {
    font-size: 14px;
  }
}
  </style>

  <script>
    var typed = new Typed('.text', {
      strings: ["Web Devloper ", "Web Designer", "Java Programmer ", "Gammer "],
      typeSpeed: 50,
      backSpeed: 50,
      backDelay: 1000,
      loop: true
    })
  </script>

  <script>
    var tablinks = document.getElementsByClassName("tab-links");
    var tabcontents = document.getElementsByClassName("tab-contents");

    function opentab(tabname) {
      for (tablink of tablinks) {
        tablink.classList.remove("active-link");
      }
      for (tabcontent of tabcontents) {
        tabcontent.classList.remove("active-tab");
      }
      event.currentTarget.classList.add("active-link");
      document.getElementById(tabname).classList.add("active-tab");
    }
  </script>
  <script>
    var sidemenu = document.getElementById("sidemenu");
    function openmenu() {
      sidemenu.style.right = "0";
    }
    function closemenu() {
      sidemenu.style.right = "-200px";
    }
  </script>
</body>

</html>
