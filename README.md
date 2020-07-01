<!DOCTYPE html>
<!--Assignment 2 for CSC 101-->
<!--Best viewed in Google Chrome and Safari-->
<html>
  <head>
    <meta charset="utf-8" />
    <title>Sharna J Hossain's Profile & Gallery</title>
    <link rel="stylesheet" href="assets/main.css" />
  <style>
  @font-face {
  font-family:Oswald;
  src: url('Oswald-Regular.ttf');
}

body {
  font-family: Oswald, "Oswald", sans-serif;
  margin:0;
  padding:0;
  background-image: url('halftone-yellow.png');
}

h1,h2,h3,h4,h5,h6 {
    margin:0;
    padding:0;
}

a:link, a:visited, a:active {
  text-decoration: none;
}


h2 {
  font-size: 80px;
  text-align:center;
}

h3 {
  font-size: 50px;
  text-align:center;
}

header a:link, a:visited, a:active {
  color:white;
}

header a:hover {
  color:#FC1070;
}

header {
  width:100%;
  height:80px;
  background-color:black;
  color:white;

}

.title {
  font-size:50px;
  float:left;
  margin-left: 30px;

}
  </style>
</head>
<body>
    <header>
      <h1 class="title">Sharna J Hossain's Profile</h1>
      <ul class="nav">
        <li><a href="index.html">Home</a></li>
        <li><a href="index.html">Profile</a></li>
        <li><a href="pages/gallery.html">Gallery</a></li>
      </ul>
    </header>

    <main>
      <img class="portrait" src="assets/my-picture.JPG" alt="me" />

      <div class="Bio">
        <h2>Who am I?</h2>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas
          auctor metus velit, ut porta dolor vestibulum eget. Aliquam non dictum
          massa. Pellentesque porttitor mattis ex, et tincidunt ex ornare ut.
          Pellentesque urna nibh, lobortis vel nunc at, lobortis pulvinar
          tellus. Mauris aliquam quam eu aliquet auctor. Duis risus libero,
          lobortis ac efficitur eu, rutrum in odio. Cras semper, quam vitae
          cursus maximus, leo nisi sodales nisi, ut porttitor turpis sapien eget
          magna. Sed blandit, lectus ac condimentum fermentum, lorem neque
          fermentum neque, ac porta est justo ut nunc. Nunc sed augue aliquet
          metus cursus convallis vitae vel velit. Nunc quis tincidunt arcu.
          Integer et semper nulla. Donec semper urna quis purus venenatis, vel
          euismod tortor sollicitudin. Etiam vitae massa sit amet tortor
          sollicitudin rutrum ut sed nibh. Nam ut urna sed sem dapibus egestas
          ut vel ante. Integer pulvinar tortor ut libero molestie mollis.
        </p>

        <h3>More Info</h3>
        <ul>
          <li>Born on June 7, 1997</li>
          <li>Hobbies:</li>
          <ul>
            <li>Coding</li>
            <li>Makeup</li>
            <li>Graphic Design</li>
          </ul>
          <li>Favorite TV Shows:</li>
          <ul>
            <li>Game of Thrones</li>
            <li>She's Gotta Have It</li>
            <li>Mr Robot</li>
          </ul>
        </ul>
      </div>
    </main>
