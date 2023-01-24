<html lang="en-US">
  <head>
    <link rel="icon" type="image/x-icon" href="f:/.New folder/.SpiLixture/2. Website/images/spilixture_logo.ico">
    <title>SpiLixture</title>
    <style>
      body {
        font-family: "Minecraft Ten", sans-serif;
        background-image: url(https://preview.redd.it/ifsaqo1yi38a1.png?width=1920&format=png&auto=webp&v=enabled&s=f6035f4da94c7e574d44d6f5ae887181a6e46e3a);
      }

      .sidenav {
        height: 100%;
        width: 0;
        position: fixed;
        z-index: 1;
        top: 0;
        left: 0;
        background-color: #E7E9ED;
        overflow-x: hidden;
        transition: 0.4s;
        padding-top: 60px;
      }

      .sidenav a {
        padding: 8px 8px 8px 32px;
        text-decoration: none;
        font-size: 25px;
        color: #242627;
        display: block;
        transition: 0.4s;
      }

      .sidenav a:hover {
        color: #58585A;
      }

      .sidenav .closebtn {
        position: absolute;
        top: 0;
        right: 25px;
        font-size: 36px;
        margin-left: 50px;
      }
    </style>
  </head>
  <body>
    <bgsound src="f:/.New folder/.SpiLixture/2. Website/sounds/Crisis Remix.mp3" />
    <div id="mySidenav" class="sidenav">
      <a href="javascript:void(0)" class="closebtn" onclick="closeNav()">&times;</a>
      <a class="active" href="#">Home</a>
      <a href="#">Cape</a>
      <a href="#">Downloads</a>
      <a href="#">FAQ</a>
    </div>
    <div>
      <h1 style="color:white; background-color: #3C8727; text-align:center;">WELCOME TO THE OFFICIAL <br>SITE OF SPILIXTURE </h1>
    </div>
    <span style="font-size:30px;cursor:pointer" onclick="openNav()">&#9776;</span>
    <script>
      function openNav() {
        document.getElementById("mySidenav").style.width = "250px";
        document.body.style.backgroundColor = "rgba(0,0,0,0.75)";
      }

      function closeNav() {
        document.getElementById("mySidenav").style.width = "0";
        document.body.style.backgroundColor = "white";
      }
    </script>
  </body>
</html>
