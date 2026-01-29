# amyyy
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My First Website</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>My Portfolio</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="about.html">About</a>
      <a href="contact.html">Contact</a>
      <button id="darkModeBtn">🌙</button>
    </nav>
  </header>

  <section class="hero">
    <img src="images/profile.jpg" alt="Profile picture">
    <h2>Welcome!</h2>
    <p>I’m learning web development and this is my first complete website.</p>
  </section>

  <script src="script.js"></script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Contact</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Contact Me</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="about.html">About</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <section class="content">
    <form id="contactForm">
      <input type="text" id="name" placeholder="Your Name">
      <input type="email" id="email" placeholder="Your Email">
      <textarea id="message" placeholder="Your Message"></textarea>
      <button type="submit">Send</button>
      <p id="error"></p>
    </form>
  </section>

  <script src="script.js"></script>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  background: #f4f4f4;
  color: #333;
}

header {
  background: #222;
  color: white;
  padding: 15px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

nav a {
  color: white;
  margin: 0 10px;
  text-decoration: none;
}

nav a:hover {
  text-decoration: underline;
}

.hero {
  text-align: center;
  padding: 40px;
}

.hero img {
  width: 150px;
  border-radius: 50%;
}

.content {
  padding: 40px;
}

form input, form textarea {
  display: block;
  width: 100%;
  margin: 10px 0;
  padding: 10px;
}

button {
  padding: 10px;
  background: #222;
  color: white;
  border: none;
  cursor: pointer;
}

button:hover {
  background: #555;
}

/* Dark mode */
.dark {
  background: #121212;
  color: white;
}
