<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Latihan Box Model</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <style>html,
body,
div,
span,
applet,
object,
iframe,
h1,
h2,
h3,
h4,
h5,
h6,
p,
blockquote,
pre,
a,
abbr,
acronym,
address,
big,
cite,
code,
del,
dfn,
em,
img,
ins,
kbd,
q,
s,
samp,
small,
strike,
strong,
sub,
sup,
tt,
var,
b,
u,
i,
center,
dl,
dt,
dd,
ol,
ul,
li,
fieldset,
form,
label,
legend,
table,
caption,
tbody,
tfoot,
thead,
tr,
th,
td,
article,
aside,
canvas,
details,
embed,
figure,
figcaption,
footer,
header,
hgroup,
menu,
nav,
output,
ruby,
section,
summary,
time,
mark,
audio,
video {
  margin: 0;
  padding: 0;
  border: 0;
  font-size: 100%;
  font: inherit;
  vertical-align: baseline;
}
/* HTML5 display-role reset for older browsers */
article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
menu,
nav,
section {
  display: block;
}
body {
  line-height: 1;
}
ol,
ul {
  list-style: none;
}
blockquote,
q {
  quotes: none;
}
blockquote:before,
blockquote:after,
q:before,
q:after {
  content: "";
  content: none;
}
table {
  border-collapse: collapse;
  border-spacing: 0;
}
/* Style */

body {
  font: 16px/28px arial, sans-serif;
  background-color: #eaeaea;
  background-image: url(gambar/wheat.png);
  color: #333;
}

.container {
  width: 960px;
  margin: auto;
  background-color: white;
}

.header {
  padding: 20px;
  padding-bottom: 10px;
}

.header .judul {
  font-size: 40px;
  font-weight: bold;
}

.header ul li {
  display: inline-block;
  margin-top: 20px;
  margin-right: 10px;
}

.header a {
  text-decoration: none;
  color: salmon;
  padding: 3px;
}

.header a:hover {
  background-color: lightskyblue;
  color: white;
}

.hero {
  height: 320px;
  background-image: url(gambar/hero.jpg);
  background-size: cover;
  background-position: 0 -100;
  border-top: 5px solid salmon;
  border-bottom: 5px solid lightskyblue;
}
.main {
  width: 600px;
  padding: 20px;
  box-sizing: border-box;
  float: left;
}

.main h2 {
  font-size: 25px;
  font-weight: bold;
}

.main .penulis {
  font-size: 11px;
  margin-top: 2px;
}

.main .penulis a {
  color: salmon;
  text-decoration: none;
}

.main .penulis a:hover {
  background-color: lightskyblue;
  color: white;
}

.main p {
  margin-bottom: 20px;
  font-size: 14px;
}

/* Sidebar */

.sidebar {
  width: 300px;
  float: right;
  padding: 20px;
}

.sidebar h3 {
  font-weight: bold;
  color: #333;
}

.sidebar img {
  width: 70px;
  height: 70px;
  float: left;
  padding-right: 10px;
}

.sidebar p {
  font: 12px/18px arial;
}

/* Footer */

.footer {
  background-color: #333;
  padding: 10px;
}

.footer .copy {
  color: #eaeaea;
  text-align: center;
  font-size: 12px;
}

/* Clear Fix */
.cf:before,
.cf:after {
  content: " "; /* 1 */
  display: table; /* 2 */
}

.cf:after {
  clear: both;
}

/**
 * For IE 6/7 only
 * Include this rule to trigger hasLayout and contain floats.
 */
.cf {
  *zoom: 1;
}
</style>
  <body>
    <div class="container">
      <div class="header">
        <h1 class="judul">My Website</h1>
        <ul>
          <li>
            <a href="#">home</a>
            <a href="#">about</a>
            <a href="#">products</a>
            <a href="#">service</a>
            <a href="#">contact</a>
          </li>
        </ul>
      </div>
      <div class="hero"></div>
      <div class="content cf">
        <div class="main">
          <h2>Judul Artikel</h2>
          <p class="penulis">
            ditulis oleh <a href="#">lukman Ferdiansyah</a> pada malam sabtu
            tangal 13, agustus 2021.
          </p>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Facilis
            alias quibusdam sunt quia distinctio corporis sed quo? Ullam at
            optio odio iusto, commodi labore omnis autem, ad itaque architecto
            sed?
          </p>
          <p>
            Lorem ipsum dolor, sit amet consectetur adipisicing elit.
            Blanditiis, dignissimos labore facere enim suscipit accusamus
            deleniti sequi, amet dolore qui doloribus quas dicta nulla impedit
            ducimus numquam consequatur illum libero, quia fugit magnam.
            Deleniti, ullam. Voluptates nemo veniam nisi perspiciatis rem at
            eligendi beatae optio provident, impedit, recusandae quidem facere.
            Quae, sed! Distinctio voluptates optio laudantium pariatur, aut
            itaque, perspiciatis numquam fuga cum quaerat eaque fugiat beatae.
            Consequuntur, magnam facere itaque id recusandae adipisci laudantium
            facilis. Corporis voluptatibus sed voluptates minus quod rem atque,
            natus mollitia est consequuntur? Incidunt corrupti unde minus
            ratione itaque facere doloribus dolorum tenetur nisi facilis.
          </p>
          <p>
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Corporis
            repudiandae, beatae laboriosam nisi earum vel tempore quidem
            inventore quasi, et minima pariatur exercitationem iste modi nulla
            ut quo odit animi sit. Quaerat alias molestiae cupiditate a dolores
            impedit nostrum eum laboriosam nihil nobis rerum molestias quia
            iusto iure, eveniet quis, provident temporibus ipsam unde reiciendis
            quas magni esse! Dignissimos molestias labore ut unde provident
            possimus corporis nemo sapiente in, nihil et numquam, repellat modi
            reiciendis repellendus beatae quos voluptatibus aperiam.
          </p>
        </div>
        <div class="sidebar">
          <h3>Tentang Penulis</h3>
          <img src="gambar/img100.jpg" alt="Lukman Ferdiansyah" />
          <p>
            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quasi,
            adipisci officiis quidem illo natus possimus odit recusandae
            voluptatibus, blanditiis, velit totam! Necessitatibus, tempore vero
            totam enim assumenda ex distinctio id?
          </p>
        </div>
      </div>
      <div class="footer">
        <p class="copy">Copyright 2021. Lukman Ferdiansyah.</p>
      </div>
    </div>
  </body>
</html>
