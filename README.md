sanjoies/
├── index.html
├── sobre.html
├── galeria.html
├── contacte.html
└── style.css
<!-- index.html -->
<!DOCTYPE html>
<html lang="ca">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>SAN JOIES | Anells de compromís amb significat</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1 class="logo">SAN JOIES</h1>
    <nav>
      <ul>
        <li><a href="index.html" class="active">Inici</a></li>
        <li><a href="sobre.html">Sobre Nosaltres</a></li>
        <li><a href="galeria.html">Galeria</a></li>
        <li><a href="contacte.html">Contacte</a></li>
      </ul>
    </nav>
  </header>

  <section class="hero">
    <div class="hero-content">
      <h2>El moment més especial mereix un anell que parli des del cor</h2>
      <a href="galeria.html" class="btn">Descobreix els nostres anells</a>
    </div>
  </section>

  <footer>
    <p>© 2025 SAN JOIES · Tots els drets reservats</p>
  </footer>
</body>
</html>

<!-- sobre.html -->
<!DOCTYPE html>
<html lang="ca">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sobre Nosaltres | SAN JOIES</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1 class="logo">SAN JOIES</h1>
    <nav>
      <ul>
        <li><a href="index.html">Inici</a></li>
        <li><a href="sobre.html" class="active">Sobre Nosaltres</a></li>
        <li><a href="galeria.html">Galeria</a></li>
        <li><a href="contacte.html">Contacte</a></li>
      </ul>
    </nav>
  </header>

  <section class="about">
    <h2>La nostra història</h2>
    <p>
      A SAN JOIES creiem que cada anell de compromís ha de tenir un significat únic, 
      com la història que representa. Des de fa anys, creem peces que simbolitzen 
      amor, compromís i eternitat.  
    </p>
    <p>
      Els nostres artesans treballen amb passió per transmetre emoció en cada detall, 
      combinant tradició i modernitat per donar vida a anells que parlen des del cor.
    </p>
  </section>

  <footer>
    <p>© 2025 SAN JOIES · Tots els drets reservats</p>
  </footer>
</body>
</html>

<!-- galeria.html -->
<!DOCTYPE html>
<html lang="ca">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Galeria | SAN JOIES</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1 class="logo">SAN JOIES</h1>
    <nav>
      <ul>
        <li><a href="index.html">Inici</a></li>
        <li><a href="sobre.html">Sobre Nosaltres</a></li>
        <li><a href="galeria.html" class="active">Galeria</a></li>
        <li><a href="contacte.html">Contacte</a></li>
      </ul>
    </nav>
  </header>

  <section class="gallery">
    <h2>Galeria d’Anells de Compromís</h2>
    <div class="gallery-grid">
      <img src="https://images.unsplash.com/photo-1522335789203-aabd1fc54bc9" alt="Anell d'or amb diamant">
      <img src="https://images.unsplash.com/photo-1589128777074-22d5cde475a0" alt="Anell de plata amb pedra blava">
      <img src="https://images.unsplash.com/photo-1504805572947-34fad45aed93" alt="Anell d'or rosa">
      <img src="https://images.unsplash.com/photo-1610465299997-fd8d2dfc6f43" alt="Anell minimalista amb brillant">
      <img src="https://images.unsplash.com/photo-1621605815971-7e9ec4e0b5a1" alt="Anell amb detall floral">
      <img src="https://images.unsplash.com/photo-1616627563754-2cc53ed7b3c7" alt="Anell amb safir elegant">
    </div>
  </section>

  <footer>
    <p>© 2025 SAN JOIES · Tots els drets reservats</p>
  </footer>
</body>
</html>
<!-- contacte.html -->
<!DOCTYPE html>
<html lang="ca">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contacte | SAN JOIES</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1 class="logo">SAN JOIES</h1>
    <nav>
      <ul>
        <li><a href="index.html">Inici</a></li>
        <li><a href="sobre.html">Sobre Nosaltres</a></li>
        <li><a href="galeria.html">Galeria</a></li>
        <li><a href="contacte.html" class="active">Contacte</a></li>
      </ul>
    </nav>
  </header>

  <section class="contact">
    <h2>Contacta amb nosaltres</h2>
    <p>Si vols més informació o demanar una cita, omple el formulari i et respondrem aviat.</p>
    <form>
      <label>Nom</label>
      <input type="text" placeholder="El teu nom" required>
      <label>Correu electrònic</label>
      <input type="email" placeholder="exemple@correu.com" required>
      <label>Missatge</label>
      <textarea placeholder="Escriu el teu missatge aquí..." required></textarea>
      <button type="submit" class="btn">Envia</button>
    </form>
  </section>

  <footer>
    <p>© 2025 SAN JOIES · Tots els drets reservats</p>
  </footer>
</body>
</html>
/* style.css */
@import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600&family=Great+Vibes&display=swap');

body {
  margin: 0;
  font-family: 'Playfair Display', serif;
  color: #3b2b2b;
  background-color: #fffafc;
}

/* HEADER */
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 15px 8%;
  background-color: #fff;
  border-bottom: 1px solid #f1dcdc;
}

.logo {
  font-family: 'Great Vibes', cursive;
  font-size: 2rem;
  color: #c59d9d;
}

nav ul {
  list-style: none;
  display: flex;
  gap: 20px;
}

nav a {
  text-decoration: none;
  color: #3b2b2b;
  font-weight: 500;
}

nav a.active, nav a:hover {
  color: #c59d9d;
}

/* HERO */
.hero {
  background: url('https://images.unsplash.com/photo-1604856745528-8eebd5c0aafd') center/cover no-repeat;
  color: white;
  text-align: center;
  padding: 160px 20px;
  position: relative;
}

.hero::after {
  content: '';
  position: absolute;
  top: 0; left: 0; right: 0; bottom: 0;
  background: rgba(0, 0, 0, 0.4);
}

.hero-content {
  position: relative;
  z-index: 2;
}

.hero h2 {
  font-size: 2rem;
  max-width: 600px;
  margin: 0 auto 20px;
  line-height: 1.4;
}

.btn {
  background-color: #c59d9d;
  color: white;
  text-decoration: none;
  padding: 10px 25px;
  border-radius: 30px;
  transition: background 0.3s;
}

.btn:hover {
  background-color: #a67b7b;
}

/* ABOUT */
.about, .contact, .gallery {
  padding: 80px 10%;
  text-align: center;
}

.about p {
  max-width: 700px;
  margin: 15px auto;
  line-height: 1.7;
}

/* GALLERY */
.gallery-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
  margin-top: 30px;
}

.gallery-grid img {
  width: 100%;
  height: 300px;
  object-fit: cover;
  border-radius: 15px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
  transition: transform 0.3s;
}

.gallery-grid img:hover {
  transform: scale(1.03);
}

/* CONTACT */
form {
  max-width: 500px;
  margin: 30px auto 0;
  display: flex;
  flex-direction: column;
  gap: 15px;
}

input, textarea {
  padding: 10px;
  border: 1px solid #e3cfcf;
  border-radius: 8px;
  font-family: inherit;
}

button.btn {
  border: none;
  cursor: pointer;
}

/* FOOTER */
footer {
  background-color: #fff;
  text-align: center;
  padding: 20px;
  border-top: 1px solid #f1dcdc;
  color: #a67b7b;
}

# 💍 SAN JOIES

Benvinguts a **SAN JOIES**, una empresa especialitzada en **anells de compromís amb significat**.

> *"El moment més especial mereix un anell que parli des del cor."*

## 🌸 Sobre nosaltres
A SAN JOIES creem anells que simbolitzen històries úniques. Cada peça està feta amb cura, amor i dedicació, combinant l’artesania tradicional amb un toc
