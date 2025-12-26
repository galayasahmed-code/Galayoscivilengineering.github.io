* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
  background: #f4f6f8;
  color: #333;
}

header {
  background: #0b2c4a;
  color: #fff;
  padding: 25px 15px;
  text-align: center;
}

header h1 {
  margin: 0;
  font-size: 26px;
}

nav {
  margin-top: 10px;
}

nav a {
  color: #ffffff;
  text-decoration: none;
  margin: 0 12px;
  font-weight: bold;
}

nav a:hover {
  text-decoration: underline;
}

main {
  max-width: 1000px;
  margin: auto;
  padding: 30px 15px;
}

section {
  background: #ffffff;
  padding: 25px;
  margin-bottom: 25px;
  border-radius: 6px;
}

section h2 {
  color: #0b2c4a;
  margin-top: 0;
}

ul {
  padding-left: 20px;
}

footer {
  background: #0b2c4a;
  color: white;
  text-align: center;
  padding: 15px;
  font-size: 14px;
}

/* Mobile responsive */
@media (max-width: 600px) {
  header h1 {
    font-size: 20px;
  }

  nav a {
    display: block;
    margin: 6px 0;
  }
}
