# baitapnhom02
html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>HTML5 Layout</title>
  <link rel="stylesheet" href="css/exam03.css">
</head>
<body>
<div class="wrapper">
  <header>
    <h1>Yokyo's Kitchen</h1>
    <nav>
      <ul>
        <li><a href="#" class="current">home</a></li>
        <li><a href="#">classes</a></li>
        <li><a href="#">catering</a></li>
        <li><a href="#">about</a></li>
        <li><a href="#">contact</a></li>
      </ul>
    </nav>
  </header>
  <section class="courses">
    <article>
      <figure>
        <img src="image/bok choi.jpg" alt="Bok Choi"/>
        
        <figcaption>Bok Choi</figcaption>
      </figure>
      <hgroup>
        <h2>Japanese Vegetarian</h2>
        <h3>Five week course in london</h3>
      </hgroup>
      <p>A five week introduction to traditional Japanese.</p>
    </article>
    <article>
      <figure>
        <img src="image/teriyaki.jpg" alt="Teriyaki sauce"/>

        <figcaption>Teriyaki Sauce</figcaption>
      </figure>
      <hgroup>
        <h2>Sauces Masterclass</h2>
        <h3>One day workshop</h3>
      </hgroup>
      <p>An intensive one-day course looking at how to create...</p>
    </article>
  </section>
  <aside>
    <section class="popular-recipes">
      <h2>Popular Recipes</h2>
      <a href="">Yakitori (grilled chicken)</a>
      <a href="">Tsukune (minced chicken patties)</a>
      <a href="">Okonomiyaki (savory pancakess)</a>
      <a href="">Mizutaki (chicken stew)</a>
    </section>
    <section class="contract-details">
      <h2>Contract</h2>
      <p>Yoko's kitchen<br/>
        27 Redchurch Street<br/>
        Shoreditch<br/>
        London E2 7DP</p>
    </section>
  </aside>
  <footer>
    &copy; 2019 Yoko's Kitchen
  </footer>
</div>
</body>
</html>
css
     header, section, footer, aside, nav, article, figure, figcaption{
         display: block;
                      }
body {
  color: #666666;
  background-color: #f9f8f6;
  background-image: url("../image/drakwood.jpg");
  (../image/drakwood.jpg)
  background-position: center;
  font-family: Georgia, Times, Serif;
  line-height: 1.4em;
  margin: 0px;
}
.wrapper {
  width: 940px;
  margin: 20px auto 20px auto;
  border: 2px solid #000000;
  background-color: #ffffff;
}
header {
  height: 160px;
  background-image: url("../image/header.jpg");
  (../image/header.jpg)
}
h1 {
  text-indent: -9999px;
  width: 940px;
  height: 130px;
  margin: 0px;
}
nav, footer {
  clear: both;
  color: #ffffff;
  background-color: #aeaca8;
  height: 30px;
}
nav ul {
  margin: 0px;
  padding: 5px 0px 5px 0px;
}
nav li {
  display: inline;
  margin-right: 40px;
}
nav li a {
  color: #ffffff;
}
nav li a:hover, nav li a.current {
  color: #000000;
}
section.courses {
  float: left;
  width: 659px;
  border-right: 1px solid #eeeeee;
}
article {
  clear: both;
  overflow: auto;
  width: 100%;
}
hgroup {
  margin-top: 40px;
}
figure {
  float: left;
  width: 290px;
  height: 220px;
  padding: 5px;
  margin: 20px;
  border: 1px solid #eeeeee;
}
figcaption {
  font-size: 90%;
  text-align: left;
}
aside {
  width: 230px;
  float: left;
  padding: 0px 0px 0px 20px;
}
