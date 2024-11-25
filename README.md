# portfolio_27
<!DOCTYPE html>
<html lang="en">
<head>
  <title> Khyla Portfolio</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
<header>
  <h1>Khyla Bautista Portfolio</h1>
  <nav>
    <ul>
      <li><a href="#about">About Me</a></li>
      <li><a href="#skills">Output</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>
</header>

<main>
  <section id="about">
    <h2>About Me</h2>
    <div class="about-container">
      <img src="khyla.jpg" alt="Rohan Baba Shaik" class="profile-picture">
      <p class="about-content">
      I have a deep passion for photo editing and photography.Photo editing allows me to bring life to ordinary images, enhancing their colors and details or transforming them into creative works of arts. Photography, on the other hand, enables me to capture meaningful moment and showcase the beauty of the worl. This passion allows me to express my creativity and see the world form unique perspectives, making every moment captured truly special.
      </p>
    </div>
  </section>

  <section id="Output">
    <h2>Output</h2>
    <div class="project-container">
      <div class="project">
        <div class="project-image">
          <img src="philippine.jpg" alt="PHILIPPINE FLAG">
        </div>
        <div class="project-content">
          <h3>PHILIPPINE FLAG</h3>
          <p>This task about creating a digital version of the philippine flag using Inkscape. The design should include the blue and red bands, white triangle,golden sun with eight rays,and three stars, keeping the corect sizes and colors to represent the flag accurately and respectfully.</p>
          <ul class="project-tech">
            
          </ul>
        </div>
      </div>

  
    <div class="project-container">
      <div class="project">
        <div class="project-image">
          <img src="invite.jpg" alt="invitation">
        </div>
        <div class="project-content">
          <h3>INVITATION</h3>
          <p>Invitation card this activity is about making an attractive and clear inivitation for an event using Inkscape. The goal is use color,fonts and layout creatively to grab attention and share event details in a simple but eye catching way</p>
          <ul class="project-tech">
            
          </ul>
        </div>
      </div>
      <div class="project">
        <div class="project-image">
          <img src="view.jpg" alt="view">
        </div>
        <div class="project-content">
          <h3>VIEW</h3>
          <p>This activity is about drawing a 3D object in 2D by showing it form the front, side and top views. This helps to clearly see and understand its shape.</p>
          <ul class="project-tech">
            
          </ul>
        </div>
      </div>
    </div>
  </section>

      

  <<section id="contact"> 
    <h2>Contact Me</h2>
    <div class="contact-container">
      <form class="contact-form" action="https://formspree.io/f/xqakbyjl" method="POST">
        <div class="form-group">
          <label for="name">Name</label>
          <input type="text" id="name" name="name" required>
        </div>
        <div class="form-group">
          <label for="email">Email</label>
          <input type="email" id="email" name="email" required>
        </div>
        <div class="form-group">
          <label for="phone">Phone (Optional)</label>
          <input type="tel" id="phone" name="phone">
        </div>
        <div class="form-group">
          <label for="message">Message</label>
          <textarea id="message" name="message" required></textarea>
        </div>
        <button type="submit" class="submit-btn">Send Message</button>
      </form>
    </div>
</section>
</main>

<footer>
  <nav class="footer-nav">
    <ul>
      <li><a href="#about">About Me</a></li>
      <li><a href="#Output">Output</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>
  <hr class="footer-divider">
  <div class="social-links">
    <a href="#" target="_blank">LinkedIn</a>
    <a href="https://github.com/kakaisalastre" target="_blank">GitHub</a>
  </div>
  <div class="copyright">&copy; 2024 Rohan Baba</div>
</footer>
</body>
</html>
body {
  font-family: "Segoe UI", Roboto, Helvetica, Arial, serif;
  margin: 0;
  padding: 0;
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}

h1, h2, h3, h4 {
  font-family: Montserrat, sans-serif;
}

h2 {
  position: relative;
  padding-bottom: 0.5em;
}

h2:after {
  content: "";
  position: absolute;
  bottom: 0;
  left: 0;
  width: 150px;
  height: 3px;
  background: linear-gradient(to right, #c53750, #a1253d);
}

/* Header Style */
header {
  background: linear-gradient(to right, #f38198, #f3c5c5);
  color: #ffffff;
  padding: 1em;
  text-align: left;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}

header h1 {
  margin: 0;
  text-align: left;
  color: white;
  text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
}

header nav {
  width: 100%;
  margin-top: 1em;
}

header nav ul {
  list-style-type: none;
  padding: 0;
  display: flex;
  justify-content: left;
  flex-wrap: wrap;
}

header nav ul li {
  margin-right: 0.5em;
  margin-bottom: 0.5em;
}

header nav ul li a {
  display: block;
  color: white;
  text-decoration: none;
  border: 1px solid white;
  padding: 0.5em 1em;
  transition: all 0.3s ease;
}

header nav ul li a:hover {
  background-color: #ffffff;
  color: #c53750;
  border-radius: 10px;
}

/* Main content */
main {
  flex-grow: 1;
  padding: 2em;
}

/* About Me Section*/
#about {
  margin-bottom: 2em;
  padding: 2em;
  background-color: #fff;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
  border-radius: 8px;
}

#about h2 {
  color: #333;
  padding-bottom: 0.5em;
  margin-bottom: 1em;
}

.about-container {
  display: flex;
  align-items: flex-start;
  gap: 2em;
}

.profile-picture {
  width: 200px;
  height: 200px;
  border-radius: 50%;
  object-fit: cover;
  border: 3px solid #f38198;
}

.about-content {
  flex: 1;
  line-height: 1.6;
  text-align: justify;
  margin: 0;
}

/* Skills Section */
#skills {
  margin-bottom: 2em;
  padding: 2em;
  background-color: #fff;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
  border-radius: 8px;
}

#skills h2 {
  color: #333;
  padding-bottom: 0.5em;
  margin-bottom: 1em;
}

.skills-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}

.skill-category {
  width: 48%;
  margin-bottom: 1.5em;
}

.skill-category h3 {
  color: #f38198;
  margin-bottom: 0.5em;
}

.skill-category ul {
  list-style-type: none;
  padding-left: 0;
}

.skill-category li {
  margin-bottom: 0.5em;
  padding-left: 1.5em;
  position: relative;
}

/* Projects Section */
#projects {
  margin-bottom: 2em;
  padding: 2em;
  background-color: #fff;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
  border-radius: 8px;
}

.project-container {
  display: flex;
  flex-wrap: wrap;
  gap: 2em;
}

.project {
  flex: 1 1 calc(50% - 1em);
  display: flex;
  flex-direction: column;
}

.project-image {
  flex: 1;
  max-width: 50%;
}

.project-image img {
  width: 100%;
  height: auto;
  object-fit: cover;
}

.project-content {
  flex: 1;
  padding: 1.5em;
  display: flex;
  flex-direction: column;
}

.project h3 {
  margin-top: 0;
  color: #333;
}

.project p {
  flex-grow: 1;
  margin-bottom: 1em;
}

.project-tech {
  list-style: none;
  padding: 0;
  display: flex;
  flex-wrap: wrap;
  gap: 0.5em;
  margin-bottom: 1em;
}

.project-tech li {
  background-color: #f38198;
  color: white;
  padding: 0.3em 0.8em;
  border-radius: 20px;
  font-size: 0.9em;
}

/* Resume Section */
#resume {
  margin-bottom: 2em;
  padding: 2em;
  background-color: #fff;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
  border-radius: 8px;
}

#resume h2 {
  color: #333;
  padding-bottom: 0.5em;
  margin-bottom: 1em;
}

#resume h3 {
  color: #f38198;
  margin-top: 1.5em;
  margin-bottom: 0.5em;
}

#resume ul {
  list-style-type: none;
  padding-left: 0;
}

#resume li {
  margin-bottom: 1em;
}

#resume table {
  width: 100%;
  border-collapse: collapse;
  margin-top: 1em;
}

#resume th, #resume td {
  border: 1px solid #ddd;
  padding: 12px;
  text-align: left;
}

#resume th {
  background-color: #f3c5c5;
  color: #333;
  font-weight: bold;
}

#resume tr:nth-child(even) {
  background-color: #f9f9f9;
}

#resume ol {
  margin-left: 1.5em;
  padding-left: 0;
}

#resume ol li {
  margin-bottom: 0.5em;
}

/* Contact section */
#contact {
  margin-bottom: 2em;
  padding: 2em;
  background-color: #fff;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
  border-radius: 8px;
}

#contact h2 {
  color: #333;
  margin-bottom: 1em;
}

.contact-container {
  display: flex;
  gap: 2em;
}

.contact-form {
  flex: 1;
  max-width: 500px;
}

.contact-info {
  flex: 1;
}

.form-group {
  margin-bottom: 1.5em;
}

.form-group label {
  display: block;
  margin-bottom: 0.5em;
  color: #333;
  font-weight: bold;
}

.form-group input,
.form-group textarea {
  width: 100%;
  padding: 0.8em;
  border: 1px solid #ddd;
  border-radius: 4px;
  font-size: 16px;
  font-family: inherit;
  transition: border-color 0.3s ease;
}

.form-group input:focus,
.form-group textarea:focus {
  outline: none;
  border-color: #f38198;
  box-shadow: 0 0 0 2px rgba(243, 129, 152, 0.2);
}

.form-group textarea {
  height: 150px;
  resize: vertical;
}

.submit-btn {
  display: block;
  width: 100%;
  padding: 1em;
  background-color: #f38198;
  color: #ffffff;
  border: none;
  border-radius: 4px;
  font-size: 16px;
  font-weight: bold;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

.submit-btn:hover {
  background-color: #c53750;
}

/* footer Section */
footer {
  background: linear-gradient(to right, #f38198, #f3c5c5);
  color: #ffffff;
  padding: 2em 1em;
  text-align: center;
}

.footer-nav ul {
  list-style-type: none;
  padding: 0;
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  margin-bottom: 1em;
}

.footer-nav ul li {
  margin: 0 1em;
  position: relative;
}

.footer-nav ul li a {
  color: white;
  text-decoration: none;
  transition: color 0.3s ease;
}

.footer-nav ul li a:hover {
  color: #333;
}

.footer-divider {
  border: none;
  border-top: 1px solid rgba(255, 255, 255, 0.5);
  margin: 1em 0;
}

.social-links {
  margin-bottom: 1em;
}

.social-links a {
  color: white;
  text-decoration: none;
  margin: 0 1em;
  transition: color 0.3s ease;
}

.social-links a:hover {
  color: #333;
}

.copyright {
  font-size: 0.9em;
  opacity: 0.8;
}

/* Media Queries */
@media (max-width: 768px) {
  /* Header styles */
  header {
    padding: 1em 0;
  }

  header h1 {
    margin-bottom: 0.5em;
    padding: 0 1em;
    text-align: center;
  }

  header nav ul {
    flex-direction: column;
    margin: 20px;
  }

  header nav ul li {
    width: 100%;
    margin-right: 0;
    margin-bottom: 0.5em;

  }

  header nav ul li a {
    padding: 0.7em 1em;
    border-radius: 0;
  }

  /* About Style */
  #about {
    padding: 1.5em;
  }

  .about-container {
    flex-direction: column;
    align-items: center;
  }

  .profile-picture {
    margin-bottom: 1em;
  }

  /* Skills Style */
  .skill-category {
    width: 100%;
  }

  /* Project Style */
  .project-container {
    flex-direction: column;
  }

  .project {
    width: 100%;
  }

  .project-image {
    width: 100%;
    max-width: 100%;
  }

  .project-image img {
    width: 100%;
    height: auto;
  }

  .project-content {
    width: 100%;
    padding: 1em 0;
  }

  /* Resume Style */
  #resume table, #resume thead, #resume tbody, #resume th, #resume td, #resume tr {
    display: block;
  }

  #resume thead tr {
    position: absolute;
    top: -9999px;
    left: -9999px;
  }

  #resume tr {
    margin-bottom: 1em;
    border: 1px solid #ccc;
  }

  #resume td {
    border: none;
    position: relative;
    padding-left: 50%;
  }

  #resume td:before {
    content: attr(data-label);
    position: absolute;
    left: 6px;
    width: 45%;
    padding-right: 10px;
    white-space: nowrap;
    font-weight: bold;
  }

  /* Contact Style */
  #contact {
    padding: 1.5em;
  }

  .contact-container {
    flex-direction: column;
  }

  .contact-form,
  .contact-info {
    max-width: 100%;
  }

  /* Footer styles */
  footer {
    width: 100%;
    text-align: left;
    padding: 1em;
  }

  .footer-nav ul {
    flex-direction: column;
    /*align-items: flex-start;*/
  }

  .footer-nav ul li {
    margin: 0.5em 0;

  }

  .footer-nav ul li a{
    border-bottom: 1px solid white;
  }
  .footer-nav ul li::before {
    content: '\25e6     ';
    position: relative;
  }


  .social-links {
    display: flex;
    flex-direction: column;
    /*align-items: flex-start;*/
  }

  .social-links a {
    margin: 0.5em 0;
  }

  .copyright {
    margin-top: 1em;
    display: flex;
    align-items: center;
    justify-content: center;
  }
}
