/* Base Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

html {
  scroll-behavior: smooth;
  font-size: 100%;
}

@media (max-width: 480px) {
  html {
    font-size: 90%;
  }
}

body {
  font-family: 'Poppins', sans-serif;
  background:#000;
  color: #fff;
  overflow-x: hidden;
  padding-top: 80px;
}

/* Navbar */

.navbar {
  width: 100%;
  padding: 20px 40px;
  position: fixed;
  top: 0;
  left: 0;
  background: #000;
  box-shadow: 0 2px 8px rgba(255, 165, 0, 0.2);
  display: flex;
  justify-content: space-between;
  align-items: center;
  z-index: 1000;
}

nav a {
  color: #ffffff;           /* normal text: white */
  font-size: 15px;
  padding: 6px 10px;
  border-radius: 8px;
  transition: all 0.2s;
  outline: none;            /* remove default focus box */
  background: transparent;  /* normal background: black page shows through */
}

/* Hover: orange background, white text */
nav a:hover {
  background: #ffa500;      /* orange */
  color: #ffffff;           /* white text for contrast */
}

/* Active (while clicking): black background with orange text */
nav a:active {
  background: #000000;      /* black box */
  color: #ffa500;           /* orange text for contrast */
}

.navbar .logo {
  font-size: 24px;
  font-weight: 700;
  color: #ffa500;
}

.nav-links {
  list-style: none;
  display: flex;
  gap: 30px;
}

.nav-links li a {
  text-decoration: none;
  color: #fff;
  font-weight: 500;
  transition: color 0.3s;
}

.menu-icon {
  display: none;
  font-size: 24px;
  cursor: pointer;
  color: #ffa500;
}

/* Hero Section */
.hero {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  align-items: center;
  padding: 80px 10%;
  min-height: 100vh;
  background: #000;
}

.hero-left {
  flex: 1 1 500px;
  z-index: 1;
}

.hero-left .tagline {
  font-size: 14px;
  color: #ccc;
  margin-bottom: 20px;
  letter-spacing: 2px;
}

.hero-left h1 {
  font-size: clamp(2.2rem, 6vw, 3rem);
  font-weight: 700;
  margin-bottom: 30px;
  color: #fff;
}

.hero-left h1 span {
  color: #ffa500;
}

.buttons {
  display: flex;
  gap: 15px;
  flex-wrap: wrap;
}

.btn {
  padding: 12px 24px;
  border-radius: 8px;
  font-weight: 600;
  text-decoration: none;
  display: inline-block;
  transition: all 0.3s;
}

.btn.primary {
  background: #ffa500;
  color: #000;
}

.btn.primary:hover {
  background: #fff;
  color: #000;
  box-shadow: 0 0 10px #ffa500;
}

.btn.outline {
  border: 2px solid #ffa500;
  color: #ffa500;
}

.btn.outline:hover {
  background: #ffa500;
  color: #000;
}

/* Hero Image */
.hero-right {
  flex: 1 1 400px;
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
  z-index: 0;
}

.hero-right img {
  width: 550px;
  height: 550px;
  object-fit: cover;
  border-radius: 50%;
  border: 4px solid #ffa500;
  box-shadow: 0 4px 12px rgba(255, 165, 0, 0.3);
}

.bg-skew {
  position: absolute;
  top: 0;
  right: 0;
  width: 120%;
  height: 100%;
  background: #121212;
  transform: skewX(-15deg);
  z-index: -1;
}

/* About Section */
.about-section {
  padding: 60px 20px;
  background: #121212;
  color: #fff;
}

.container {
  max-width: 1100px;
  margin: auto;
}

.about-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 40px;
  align-items: center;
}

.about-img img {
  width: 300px;
  max-width: 400px;
  height: 450px;
  border-radius: 12px;
  object-fit: cover;
  box-shadow: 0 4px 20px rgba(255, 165, 0, 0.3);
}

.about-content h2 {
  font-size: clamp(1.8rem, 5vw, 2.5rem);
  margin-bottom: 15px;
  color: #ffa500;
}

.about-content p {
  font-size: 16px;
  margin-bottom: 10px;
  color: #ccc;
}

.interests span {
  display: inline-block;
  margin-right: 15px;
  background: #2a2a2a;
  padding: 6px 12px;
  border-radius: 20px;
  font-size: 14px;
  color: #ffa500;
}

/* Skills Section */
/* Skills Section */
.skills-section {
  background: #000; /* black background */
  padding: 60px 0;
  text-align: center;
  overflow: hidden;
}
.skills-section h2 {
  font-size: clamp(2rem, 5vw, 2.5rem);
  margin-bottom: 40px;
  font-weight: 700;
  color: #ffa500; /* orange heading */
}
.skills-slider {
  width: 100%;
  overflow: hidden;
  position: relative;
}
.skills-track {
  display: flex;
  gap: 20px;
  width: max-content;
  animation: scroll-left 25s linear infinite;
}
@keyframes scroll-left {
  0% { transform: translateX(0); }
  100% { transform: translateX(-50%); }
}
.skill-card {
  background: #111; /* dark grey for contrast */
  border-radius: 15px;
  padding: 20px 15px;
  text-align: center;
  box-shadow: 0 4px 12px rgba(255, 165, 0, 0.2); /* orange glow */
  transition: transform 0.3s;
  width: 160px;
  flex: 0 0 auto;
}
.skill-card:hover {
  transform: scale(1.05);
  box-shadow: 0 4px 15px rgba(255, 165, 0, 0.4);
}
.skill-icon {
  width: 80px;
  height: 80px;
  object-fit: contain;
  margin-bottom: 10px;
}
.skill-card h4 {
  font-size: 18px;
  color: #fff;
  font-weight: 600;
  margin: 10px 0 4px;
}
.level-label {
  font-size: 14px;
  font-weight: 600;
  color: #ffa500; /* accent orange */
}

/* Projects Section */
.projects-section {
  padding: 80px 20px;
  background-color: #111;
  text-align: center;
}
.projects-section h2 {
  color: #ffa500;
}
.projects-grid {
  display: flex;
  gap: 30px;
  flex-wrap: wrap;
  justify-content: center;
  margin-top: 40px;
}
.project-card {
  position: relative;
  width: 280px;
  height: 200px;
  overflow: hidden;
  border-radius: 15px;
  box-shadow: 0 4px 15px rgba(255, 165, 0, 0.2);
  cursor: pointer;
  background: #222;
}
.project-card img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  border-radius: 15px;
  transition: all 0.5s ease;
}
.project-info {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  backdrop-filter: blur(8px);
  background-color: rgba(0, 0, 0, 0.6);
  color: #fff;
  opacity: 0;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  padding: 10px;
  transition: opacity 0.5s ease;
}
.project-card:hover img {
  transform: scale(1.1);
  filter: blur(2px);
}
.project-card:hover .project-info {
  opacity: 1;
}
.project-info h3 {
  font-size: 20px;
  margin-bottom: 10px;
  color: #ffa500;
}
.project-info a {
  padding: 6px 14px;
  background: #ffa500;
  color: #000;
  text-decoration: none;
  border-radius: 4px;
  font-weight: 600;
  transition: 0.3s;
}
.project-info a:hover {
  background: #fff;
  color: #000;
}

/* Contact Section */
.contact-section {
  padding: 80px 20px;
  background: #000;
  text-align: center;
}
.contact-section h2 {
  color: #ffa500;
}
.contact-section .container {
  max-width: 600px;
  margin: auto;
}
.contact-form {
  margin-top: 30px;
  padding: 0 10px;
}
.form-group {
  margin-bottom: 20px;
}
.contact-form input,
.contact-form textarea {
  width: 100%;
  padding: 12px 15px;
  border: none;
  border-radius: 8px;
  background: #111;
  color: #fff;
  font-size: 16px;
}
.contact-form input:focus,
.contact-form textarea:focus {
  outline: none;
  box-shadow: 0 0 8px rgba(255, 165, 0, 0.5);
}
.contact-form .btn {
  padding: 10px 20px;
  border: none;
  background: #ffa500;
  color: #000;
  border-radius: 6px;
  font-size: 16px;
  cursor: pointer;
  transition: 0.3s;
}
.contact-form .btn:hover {
  background: #fff;
  transform: scale(1.05);
}

/* Footer */
.footer {
  background-color: #000;
  color: #fff;
  padding: 50px 20px;
  text-align: center;
}
.footer h3 {
  font-size: 24px;
  margin-bottom: 10px;
  color: #ffa500;
}
.footer p {
  margin: 10px 0;
}
.social-icons {
  margin: 20px 0;
}
.social-icons a {
  color: #ffa500;
  font-size: 20px;
  margin: 0 10px;
  transition: 0.3s;
}
.social-icons a:hover {
  color: #fff;
}
.footer .copyright {
  margin-top: 15px;
  font-size: 14px;
  color: #bbb;
}

/* Responsive Fixes */
@media (max-width: 991px) {
  .projects-grid {
    flex-direction: column;
    align-items: center;
  }
}
