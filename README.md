<img width="1440" height="1440" alt="IMG_20251231_102352_799" src="https://github.com/user-attachments/assets/1efe3bd9-21e2-4c73-83b4-bd500e604a87" />
# Rfx_studio-
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Rahul Portfolio</title>

<!-- Fonts -->
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500&family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">

<style>
*{
  margin:0;
  padding:0;
  box-sizing:border-box;
}

body{
  background: linear-gradient(180deg,#0b0b12,#1a0b2e);
  color:white;
  font-family: 'Inter', sans-serif;
}

/* Navbar */
header{
  display:flex;
  justify-content:space-between;
  padding:20px;
}

.logo{
  font-family:'Poppins',sans-serif;
  font-size:24px;
  color:#a855f7;
  font-weight:600;
}

nav a{
  margin-left:20px;
  text-decoration:none;
  color:#ccc;
}

nav a:hover{
  color:#a855f7;
}

/* Hero */
.hero{
  text-align:center;
  padding:80px 20px;
}

.hero h3{
  color:#a855f7;
  letter-spacing:3px;
  font-family:'Poppins',sans-serif;
}

.hero h1{
  font-size:48px;
  font-weight:700;
  letter-spacing:2px;
  font-family:'Poppins',sans-serif;
}

.hero p{
  color:#a1a1aa;
  margin-top:10px;
}

/* Buttons */
.btn{
  padding:12px 20px;
  border-radius:30px;
  border:1px solid #a855f7;
  text-decoration:none;
  color:white;
  margin:10px;
  display:inline-block;
}

.primary{
  background:#a855f7;
  box-shadow:0 0 15px #a855f7;
}

/* Cards */
.card{
  background:rgba(139,92,246,0.08);
  margin:20px;
  padding:20px;
  border-radius:15px;
  backdrop-filter:blur(10px);
}

/* About */
.about-container{
  display:flex;
  align-items:center;
  gap:20px;
  flex-wrap:wrap;
}

.profile{
  width:120px;
  height:120px;
  border-radius:50%;
  object-fit:cover;
  border:3px solid #a855f7;
  box-shadow:0 0 20px #a855f7;
}

/* Skills */
.skill{
  margin-top:15px;
}

.bar{
  background:#333;
  height:8px;
  border-radius:10px;
  overflow:hidden;
}

.bar div{
  height:100%;
  background:linear-gradient(90deg,#8b5cf6,#a855f7);
}

/* Social */
.social{
  margin-top:20px;
}

.insta{
  display:flex;
  align-items:center;
  gap:12px;
  padding:12px 15px;
  border-radius:12px;
  text-decoration:none;
  background:rgba(139,92,246,0.08);
  border:1px solid rgba(168,85,247,0.3);
  transition:0.3s;
}

.insta:hover{
  transform:translateY(-3px);
  box-shadow:0 0 15px #a855f7;
}

.icon{
  font-size:20px;
}

.text small{
  color:#a1a1aa;
  display:block;
  font-size:12px;
}

.text strong{
  color:white;
  font-size:14px;
}

/* Contact */
.contact{
  text-align:center;
}

.contact-box{
  margin:15px 0;
  color:#ccc;
}

/* Mobile */
@media(max-width:600px){
  .hero h1{
    font-size:32px;
  }

  .about-container{
    flex-direction:column;
    text-align:center;
  }
}
</style>
</head>

<body>

<header>
  <div class="logo">RFX</div>
  <nav>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section class="hero">
  <h3>VIDEO EDITOR</h3>
  <h1>RAHUL</h1>
  <p>Cinematic Video Editing & Motion Graphics</p>

  <a href="#contact" class="btn primary">Hire Me</a>
  <a href="#about" class="btn">About Me</a>
</section>

<section id="about" class="card">
  <div class="about-container">
    <img src="profile.png" class="profile">

    <div>
      <h2 style="font-family:Poppins;">Rahul</h2>
      <p>
        Focused and creative student with 2+ years of hands-on video editing experience.
        I specialize in cinematic edits and storytelling.
      </p>
    </div>
  </div>
</section>

<section class="card">
  <h2 style="font-family:Poppins;">Skills</h2>

  <div class="skill">
    <p>Video Editing</p>
    <div class="bar"><div style="width:95%"></div></div>
  </div>

  <div class="skill">
    <p>Motion Graphics</p>
    <div class="bar"><div style="width:90%"></div></div>
  </div>

  <div class="skill">
    <p>Color Grading</p>
    <div class="bar"><div style="width:85%"></div></div>
  </div>
</section>

<section id="contact" class="card contact">
  <h2 style="font-family:Poppins;">Ready to work?</h2>

  <p>Let's create something cinematic together.</p>

  <div class="contact-box">
    📞 9900809042 <br>
    ✉️ rahulxeditzrahulxeditz@gmail.com <br>
    📍 Bengaluru, India
  </div>

  <!-- Instagram Pro -->
  <div class="social">
    <a href="https://www.instagram.com/rfxs_tudio?igsh=dWNnd3h5bTdvOHM5" target="_blank" class="insta">
      <span class="icon">📸</span>
      <div class="text">
        <small>Instagram</small>
        <strong>@rfxs_tudio</strong>
      </div>
    </a>
  </div>

  <a href="https://wa.me/919900809042" class="btn primary">Get in Touch</a>
</section>

</body>
</html>
