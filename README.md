# moawia-project.index
project
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="style.css" />
    <title>Muawiya Mohamed</title>
  </head>

  <body>
    <div class="container">
      <video class="video-loop" autoplay loop muted>
        <source src="./video-loop.mp4" type="video/mp4">
      </video>
      <header class="header">
        <nav class="navigation">
          <ul class="navigation--list">
            <li><a href="#" class="navigation--link">Bio</a></li>
            <li><a href="#" class="navigation--link">Skills</a></li>
            <li><a href="#" class="navigation--link">Media</a></li>
            <li><a href="#" class="navigation--link">Projects</a></li>
            <li><a href="#" class="navigation--link">My Clients</a></li>
            <li><a href="#" class="navigation--link">Contact</a></li>
          </ul>
        </nav>
        <div class="toggle">
          <h3 class="toggle--title">Switch Theam</h3>
          <input
            type="checkbox"
            name="toggle checkbox"
            id="toggle"
            class="toggle--checkbox"
          />
          <label for="toggle" class="toggle--label"></label>
        </div>
      </header>

      <section id="bio" class="bio section">
        <div class="bio--data">
          <h1 class="bio--heading">
            Hi There, I'm A passionate Software Engineer
          </h1>
          <p class="bio--objective">
            My name is <span class="bio--name">Muawiya Mohamed</span>, a
            co-founder of
            <a href="https://almdrasa.com/" class="bio--almdrasa"
              >Almdrasa.com</a
            >
            software Engineer and a content creator who publish content on
            <a
              href="https://www.facebook.com/share/14TnLwzdbph/"
              class="bio--facebook"
              >Facebook</a
            >
          </p>

          <a href="" class="bio--links say-hi-link">Say Hi</a>
          <a href="" class="bio--links find-out-link"
            >Download CV <span class="bio--arrow">↓</span></a
          >
        </div>
        <div class="bio--bic-content">
          <img
            src="./images/WhatsApp Image 2025-12-28 at 2.283.png"
            class="bio--pic"
            alt="image of muawiya mohamed"
          />
        </div>
      </section>

      <section id="skills" class="skills section section--with-bg">
        <h2 class="h2-heading">skills</h2>

        <ul class="skills--list">
          <li class="skills--item">
            <h2 class="">Html</h2>
            <span class="skills--years">1 year</span>
          </li>
          <li class="skills--item">
            <h2 class="">Css</h2>
            <span class="skills--years">1 year</span>
          </li>
          <li class="skills--item">
            <h2 class="">Video Editing</h2>
            <span class="skills--years">2 year</span>
          </li>
          <li class="skills--item">
            <h2 class="">Graphic Design</h2>
            <span class="skills--years">2 year</span>
          </li>
          <li class="skills--item">
            <h2 class="">IDCL</h2>
            <span class="skills--years">3 year</span>
          </li>
          <li class="skills--item">
            <h2 class="">Runner</h2>
            <span class="skills--years">3 year</span>
          </li>
        </ul>
      </section>

      <source id="media" class="media section">
        <video class="media--video" poster="./images/thumbnail.jpg" controls>
          <source src="./video.mp4" type="video/mp4" />
        </video>
      </section>

      <section id="projects" class="projects section">
        <h2 class="h2-heading">My Featured<br> Projects</h2>
        <div class="projects--main">
          <img class="projects--img" src="./images/معرض الكتاب العربي_Page_2.jpg" alt="Arab Book Fair" />
          <div class="projects-data">
            <h3 class="h3-heading">My Project</h3>
            <p class="projects--description">
              The design was created for the Arab Book Fair held in New York.
            </p>
            <a href="" class="projects--links" target="_blank"> </a>
            <a href="https://drive.google.com/file/d/1HAVxBmH6rXvegQTZO2eyPVvYr_M7lI13/view?usp=sharing"  class="projects--links" target="_blank">Drive Link</a>
          </div>

          
          <div class="projects-data">
            <h3 class="h3-heading">My Project</h3>
            <p class="projects--description">
             Members participating in the Arab Book Fair held in New York
            </p>
            <a href="https://drive.google.com/file/d/1HAVxBmH6rXvegQTZO2eyPVvYr_M7lI13/view?usp=sharing" class="projects--links" target="_blank">Drive Link </a>
          </div>
<img class="projects--img" src="./images/معرض الكتاب العربي_Page_1.jpg" alt="Arab Book Fair" />
        </div>
      </section>
    </div>
  </body>
</html>
