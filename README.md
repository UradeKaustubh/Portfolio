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
