# Raghus_portfolio
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, shrink-to-fit=no">
  <link rel="icon" href="favicon.ico" type="image/x-icon">
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/normalize/8.0.1/normalize.min.css">
  <style>
    * {
      box-sizing: border-box;
    }

    body {
      font-family: 'Roboto', Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: var(--background-color);
      color: var(--text-color);
    }

    .container {
      height: 50%;
      max-width: 1200px;
      margin: 0 auto;
    }

    header {
      background-color: var(--primary-color);
      padding: 20px;
      text-align: center;
      color: white;
      border-bottom: 5px solid var(--secondary-color);
    }

    header h1 {
      font-size: 36px;
      margin: 0;
      text-transform: uppercase;
      letter-spacing: 2px;
    }

    header p {
      font-size: 18px;
      margin: 0;
      font-weight: bold;
    }

    section {
      padding: 40px 20px;
      background-color: white;
      margin: 10px 0;
      border-radius: 10px;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    }

    section h2 {
      font-size: 24px;
      margin-bottom: 20px;
      color: var(--primary-color);
    }

    .project-card {
      color: black;
      border: 2px solid #ccc;
      padding: 20px;
      margin: 15px 5px; /* Adjust the margin for spacing between project cards */
      border-radius: 5px;
      box-shadow: 0 2px 4px rgba(226, 22, 22, 0.1);
      background-color: white;
      display: inline-block; /* Display the project cards inline */
    }

    .project-card img {
      width: 100%;
      max-height: 200px;
      object-fit: cover;
      border-radius: 5px;
    }

    ul {
      list-style: upper-latin;
      /* Remove default margin */
    }

    ul li {
      margin-bottom: 10px;
    }

    footer {
      text-align: center;
      background-color: var(--primary-color);
      padding: 10px 0;
      width: 100%;
      bottom: 0;
      color: white;
    }

    .two {
      width: 50%;
      display: inline-flex;
      vertical-align: top;
    }

    .two ul {
      list-style-type: disc;
      padding-left: 20px;
      margin: 0;
      /* Remove default margin */
    }

    .two li {
      margin-bottom: 10px;
    }


    /* Animation classes */
    .fade-in {
      opacity: 0;
      transform: translateY(20px);
      animation: fadeInAnimation 1s forwards;
    }

    nav a {
      color: white;
      margin: 100px;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
      color: red;
    }

    @keyframes fadeInAnimation {
      from {
        opacity: 0;
        transform: translateY(20px);
      }

      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
  </style>
  <style>
    /* CSS Variables for Colors */
    :root {
      --primary-color: #20232a;
      --secondary-color: #61dafb;
      --background-color: #f9f9f9;
      --text-color: #333;
    }
  </style>
  <title>Your Portfolio</title>
</head>

<body>
  <header>
    <div class="container">
      <h2> Raghu's Portfolio</h2>
    </div>
    <div>
      <nav>
        <a href="#">home</a>
        <a href="#">about</a>
        <a href="#">services</a>
        <a href="#">projects</a>
        <a href="#">contact</a>
      </nav>
    </div>
  </header>

  <section id="about" class="fade-in">
    <div class="container">
      <h2>Brief intro</h2>
      <p>
        Greetings,

        I am Sayimpu Raghuchandra Prasad, a skilled and enthusiastic web developer proficient in HTML, CSS, JavaScript,
        Bootstrap, MySQL, and basic PHP. My passion lies in creating engaging and interactive websites that not only
        meet but exceed expectations. With a good foundation in web development technologies, I am dedicated to
        crafting visually appealing, user-friendly, and functional websites. Through various projects, I have honed my
        ability to bring designs to life and ensure seamless user experiences. As a highly motivated individual, I am
        eager to contribute my expertise to a team in need of a proficient web developer...
      </p>
    </div>
  </section>

  <section id="projects" class="fade-in">
    <div class="container">
      <h2>Projects</h2>
      <!-- Display your projects with images and descriptions -->
      <div class="project-card">
        <img srcset="project1-320w.jpg 320w, project1-480w.jpg 480w, project1-800w.jpg 800w"
          sizes="(max-width: 320px) 280px, (max-width: 480px) 440px, 800px" src="project1-800w.jpg"
          alt=" Personal Portfolio">
        <p> About:A brief introduction to Raghu, highlighting his passion for web development and proficiency in essential technologies.
        </p>
        <p> Projects: A showcase of projects, each displayed in a project card format. The cards feature project descriptions and captivating images to provide visitors with insights into Raghu's work.
        </p>
        <p> Skills: An overview of Raghu's technical skills, organized neatly into two columns for easy readability.
        </p>
        <p>Contact: Information for visitors to reach out to Raghu via email or phone, enabling potential collaborations or inquiries.
        </p>
      </div>

      <div class="project-card">
        <img srcset="project2-320w.jpg 320w, project2-480w.jpg 480w, project2-800w.jpg 800w"
          sizes="(max-width: 320px) 280px, (max-width: 480px) 440px, 800px" src="project2-800w.jpg"
          alt="Project 2 description">
        <p>Project 2 description goes here.</p>
      </div>
    </div>
  </section>

  <section id="skills" class="fade-in">
    <div class="container">
      <h2>Skills</h2>
      <div class="two">
        <ul>
          <li>HTML</li>
          <li>CSS</li>
          <li>JavaScript</li>
        </ul>
      </div>
      <div class="two">
        <ul>
          <li>Bootstrap</li>
          <li>MySQL</li>
          <li>PHP (basic)</li>
        </ul>

      </div>
    </div>
  </section>

  <section id="contact" class="fade-in">
    <div class="container">
      <h2>Achievements</h2>
      <ul>
        <li type="disc">Captained school cricket team.</li>
        <li type="disc"> Played as a vital team member for the college volleyball team, competing at the national inter college level.</li>
        <li type="disc"> Gold medal in state level karate championship(team).</li>
      </ul>
    </div>
  </section>

  <footer>
    <div class="end">
      <p>Email: Sayimpuraghuchandraprasad@gmail.com</p>
      <P> +91 9381768342</P>
    </div>
    <div class="container">
      <p>&copy; end of Rcps Portfolio</p>
    </div>
  </footer>

  <script>
    function addFadeInAnimation(element) {
      element.classList.add('fade-in');
    }

    const sections = document.querySelectorAll('section');

    function checkScroll() {
      sections.forEach((section) => {
        const sectionTop = section.offsetTop;
        const sectionHeight = section.clientHeight;
        const scrollY = window.scrollY || window.pageYOffset;

        if (scrollY > sectionTop - window.innerHeight + sectionHeight / 2) {
          addFadeInAnimation(section);
        } else {
          removeFadeInAnimation(section);
        }
      });
    }

    window.addEventListener('scroll', checkScroll);
    window.addEventListener('resize', checkScroll);
    window.addEventListener('load', checkScroll);
  </script>
</body>

</html>
