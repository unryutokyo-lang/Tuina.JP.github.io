style.css
body {
  margin: 0;
  font-family: "Hiragino Mincho ProN", "Yu Mincho", serif;
  color: #222;
  background-color: #f7f6f4;
  line-height: 1.8;
}

.header {
  background: #1f1f1f;
  color: #fff;
}

.header-inner {
  max-width: 1100px;
  margin: 0 auto;
  padding: 20px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  font-size: 20px;
  letter-spacing: 2px;
}

.nav {
  list-style: none;
  display: flex;
  gap: 20px;
}

.nav a {
  color: #fff;
  text-decoration: none;
  font-size: 14px;
}

.hero {
  height: 70vh;
  background: url("img/hero.jpg") center / cover no-repeat;
  display: flex;
  align-items: center;
  justify-content: center;
}

.hero-text {
  background: rgba(0,0,0,0.4);
  color: #fff;
  padding: 40px;
  text-align: center;
}

.section {
  max-width: 900px;
  margin: 0 auto;
  padding: 80px 20px;
}

.section h3 {
  font-size: 24px;
  margin-bottom: 30px;
  border-bottom: 1px solid #ccc;
  padding-bottom: 10px;
}

.bg {
  background: #eceae6;
}

.menu {
  list-style: none;
  padding: 0;
}

.menu li {
  margin-bottom: 30px;
}

.footer {
  background: #1f1f1f;
  color: #ccc;
  text-align: center;
  padding: 20px;
  font-size: 12px;
}
