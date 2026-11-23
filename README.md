
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<meta name="description" content="My Digital Hub - Personal website, social media, technology and gaming.">

<title>My Digital Hub | Personal Website</title>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  scroll-behavior: smooth;
}

body {
  font-family: Arial, sans-serif;
  background: #0c0c0f;
  color: #f5f5f5;
  line-height: 1.7;
}

a {
  text-decoration: none;
  color: inherit;
}

header {
  position: sticky;
  top: 0;
  z-index: 100;
  background: rgba(12,12,15,0.96);
  border-bottom: 1px solid #292932;
  padding: 18px 8%;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  font-size: 21px;
  font-weight: bold;
  letter-spacing: 1px;
}

.logo span {
  color: #8b9cff;
}

nav {
  display: flex;
  gap: 22px;
  flex-wrap: wrap;
}

nav a {
  color: #bdbdc7;
  font-size: 13px;
}

nav a:hover {
  color: #8b9cff;
}

.hero {
  min-height: 480px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  padding: 80px 20px;
  background:
    radial-gradient(circle at top, #252c4b, #0c0c0f 65%);
}

.hero .tag {
  color: #a5b1ff;
  border: 1px solid #454c75;
  padding: 7px 16px;
  border-radius: 30px;
  font-size: 12px;
  margin-bottom: 22px;
}

.hero h1 {
  font-size: clamp(38px, 7vw, 65px);
  letter-spacing: 2px;
  margin-bottom: 15px;
}

.hero h1 span {
  color: #8b9cff;
}

.hero p {
  color: #bdbdc7;
  max-width: 580px;
}

.hero-button {
  display: inline-block;
  margin-top: 25px;
  background: #8b9cff;
  color: #101018;
  padding: 12px 25px;
  border-radius: 8px;
  font-weight: bold;
  border: none;
  cursor: pointer;
}

.hero-button:hover {
  background: white;
}

.container {
  max-width: 1050px;
  margin: auto;
  padding: 65px 25px;
}

.section-title {
  font-size: 27px;
  margin-bottom: 10px;
}

.section-subtitle {
  color: #92929e;
  margin-bottom: 28px;
  font-size: 14px;
}

.about-box {
  background: #17171d;
  border: 1px solid #292932;
  border-radius: 14px;
  padding: 30px;
}

.about-box p {
  color: #c5c5cf;
  margin-bottom: 15px;
}

.grid {
  display: grid;
  grid-template-columns:
    repeat(auto-fit, minmax(220px, 1fr));
  gap: 20px;
}

.card {
  background: #17171d;
  border: 1px solid #292932;
  border-radius: 14px;
  padding: 25px;
  transition: 0.3s;
  overflow-wrap: anywhere;
}

.card:hover {
  transform: translateY(-5px);
  border-color: #8b9cff;
}

.card .icon {
  font-size: 32px;
  margin-bottom: 12px;
}

.card h3 {
  margin-bottom: 8px;
}

.card p {
  color: #a7a7b2;
  font-size: 14px;
}

.card-button {
  display: inline-block;
  margin-top: 15px;
  padding: 9px 16px;
  border-radius: 7px;
  background: #272b40;
  color: #b9c4ff;
  font-size: 13px;
  font-weight: bold;
  border: none;
  cursor: pointer;
}

.card-button:hover {
  background: #3a4266;
}

.game-name {
  color: #a5b1ff;
  font-weight: bold;
  margin-top: 12px;
  font-size: 14px;
}

.contact-box {
  text-align: center;
  background: #17171d;
  border: 1px solid #292932;
  padding: 35px 20px;
  border-radius: 14px;
}

.contact-box p {
  color: #bdbdc7;
  margin: 10px 0;
  overflow-wrap: anywhere;
}

footer {
  background: #08080b;
  border-top: 1px solid #26262c;
  text-align: center;
  padding: 28px 15px;
  color: #858591;
  font-size: 13px;
}

@media(max-width: 650px) {
  header {
    flex-direction: column;
    gap: 14px;
    padding: 16px 10px;
  }

  nav {
    justify-content: center;
    gap: 13px;
  }

  nav a {
    font-size: 12px;
  }

  .container {
    padding: 45px 18px;
  }
}
</style>
</head>

<body>

<!-- HEADER -->
<header>
  <div class="logo">MY <span>DIGITAL HUB.</span></div>

  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#socials">Socials</a>
    <a href="#gaming">Gaming</a>
    <a href="#contact">Contact</a>
  </nav>
</header>


<!-- HOME -->
<section class="hero" id="home">

  <div class="tag">
    WELCOME TO MY PERSONAL WEBSITE
  </div>

  <h1>MY <span>DIGITAL HUB</span></h1>

  <p>
    A personal space where I share my interests,
    explore technology, showcase my hobbies,
    and connect with others.
  </p>

  <a href="#about" class="hero-button">
    Explore My Website
  </a>

</section>


<!-- ABOUT ME -->
<section class="container" id="about">

  <h2 class="section-title">About Me</h2>

  <p class="section-subtitle">
    Get to know me and my digital journey.
  </p>

  <div class="about-box">

    <p>
      I'm a student who enjoys learning new things,
      exploring technology, and discovering opportunities
      to improve my knowledge and skills.
    </p>

    <p>
      I created this website, My Digital Hub, as a personal
      space where I can share a little about myself,
      showcase my interests, and connect with others.
    </p>

    <p>
      This website serves as a digital introduction to who
      I am, what I do, and some of the things I find interesting.
    </p>

    <p>
      Feel free to explore my socials and learn more about me.
    </p>

    <p>
      Thank you for visiting My Digital Hub.
      I hope you enjoy exploring!
    </p>

  </div>
</section>


<!-- SOCIAL MEDIA -->
<section class="container" id="socials">

  <h2 class="section-title">Social Media</h2>

  <p class="section-subtitle">
    Let's connect through my social media accounts.
  </p>

  <div class="grid">

    <div class="card">

      <div class="icon">📸</div>

      <h3>Instagram</h3>

      <p>
        Follow me on Instagram and explore my profile.
      </p>

      <a class="card-button"
        href="https://www.instagram.com/w.clhev?lqvp=MXR4ZnJwN29ycm9yaA=="
        target="_blank"
        rel="noopener noreferrer">
        Visit Instagram ↗
      </a>

    </div>

    <div class="card">

      <div class="icon">👥</div>

      <h3>Facebook</h3>

      <p>
        Connect with me on Facebook.
      </p>

      <a class="card-button"
        href="https://www.facebook.com/share/1L1jC6ZaUb/"
        target="_blank"
        rel="noopener noreferrer">
        Visit Facebook ↗
      </a>

    </div>

  </div>
</section>


<!-- GAMING SECTION -->
<section class="container" id="gaming">

  <h2 class="section-title">My Gaming World</h2>

  <p class="section-subtitle">
    Explore my gaming profiles and connect with me in-game!
  </p>

  <div class="grid">

    <!-- MOBILE LEGENDS -->
    <div class="card">

      <div class="icon">🎮</div>

      <h3>Mobile Legends: Bang Bang</h3>

      <p>
        My Mobile Legends gaming profile.
      </p>

      <div class="game-name">
        IGN: w.clh3v
      </div>

      <div class="game-name">
        Player ID: 2077483409
      </div>

      <div class="game-name">
        Server ID: 17230
      </div>

      <button class="card-button"
        onclick="copyGameID('2077483409')">
        Copy Player ID
      </button>

      <button class="card-button"
        onclick="copyGameID('17230')">
        Copy Server ID
      </button>

    </div>


    <!-- CALL OF DUTY MOBILE -->
    <div class="card">

      <div class="icon">🎯</div>

      <h3>Call of Duty: Mobile</h3>

      <p>
        My Call of Duty: Mobile gaming profile.
      </p>

      <div class="game-name">
        IGN: w.clhev
      </div>

      <div class="game-name">
        Player ID: 7491908307460816897
      </div>

      <button class="card-button"
        onclick="copyGameID('7491908307460816897')">
        Copy Player ID
      </button>

    </div>

  </div>

</section>


<!-- CONTACT -->
<section class="container" id="contact">

  <h2 class="section-title">Contact Information</h2>

  <p class="section-subtitle">
    Have something to share? Feel free to reach out.
  </p>

  <div class="contact-box">

    <div class="icon">✉️</div>

    <h3>Let's Connect!</h3>

    <p>Email Address:</p>

    <p>
      <strong>ufounddmartin@gmail.com</strong>
    </p>

    <a class="hero-button"
      href="mailto:ufounddmartin@gmail.com">
      Send Me an Email
    </a>

  </div>

</section>


<!-- FOOTER -->
<footer>

  <p>© 2026 My Digital Hub. All Rights Reserved.</p>

  <p>Designed with passion and creativity.</p>

  <p>Thank you for visiting!</p>

</footer>


<!-- JAVASCRIPT -->
<script>

function copyGameID(id) {

  navigator.clipboard.writeText(id)
    .then(() => {
      alert("ID copied successfully: " + id);
    })
    .catch(() => {
      alert("Unable to copy. Please copy manually: " + id);
    });

}

console.log("Welcome to My Digital Hub!");

</script>

</body>
</html>
