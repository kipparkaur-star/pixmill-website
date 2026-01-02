# pixmill-website
 {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: "Arial", sans-serif;
  color: #2a2a2a;
  line-height: 1.6;
  background: #fff;
}

/* HEADER */
.header {
  background: #000;
  color: #fff;
  padding: 15px 0;
}

.container {
  width: 90%;
  margin: auto;
}

.logo {
  font-size: 24px;
  font-weight: bold;
  float: left;
}

.nav {
  float: right;
}

.nav a {
  color: #fff;
  text-decoration: none;
  margin-left: 20px;
  font-size: 16px;
}

/* HERO */
.hero {
  background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('hero-bg.jpg') center/cover no-repeat;
  color: #fff;
  padding: 120px 0;
  text-align: center;
}

.hero h2 {
  font-size: 2.5rem;
  margin-bottom: 15px;
}

.btn-primary {
  background: #ffbb00;
  padding: 12px 25px;
  color: #000;
  text-transform: uppercase;
  font-weight: bold;
  text-decoration: none;
  display: inline-block;
  margin-top: 15px;
}

/* SECTIONS */
.section {
  padding: 60px 0;
}

.section-light {
  background: #f8f8f8;
}

.section-dark {
  background: #222;
  color: #fff;
}

/* GRID */
.grid {
  display: grid;
  gap: 20px;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
}

.card {
  background: #fff;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 4px 6px rgba(0,0,0,0.1);
  text-align: center;
}

.card h3 {
  margin-bottom: 10px;
  font-size: 1.3rem;
  color: #000;
}

.card p {
  font-size: 0.95rem;
  color: #444;
}

/* FOOTER */
.footer {
  text-align: center;
  padding: 20px;
  background: #000;
  color: #fff;
  margin-top: 40px;
}
