# Homeinteriordesign.github.io
/*Entry for Pulzion Web Des contest*/
<!DOCTYPE html>
<html lang="en">
<head>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
</head>
<html>
    <title>Interior Design</title>

    <style>
        .grid-container1 {
          display: grid;
          height: 120px;
          justify-content: space-evenly;
          font-family: 'Times New Roman', serif;
          color :rgb(255, 255, 255);
         /* grid-template-columns: 50px 50px 50px; /*Make the grid smaller than the container*/
          grid-gap: 50px;
          background-color: #000000;
          position:relative;
          padding: 10px;
          z-index: 1;
        }

        .grid-container2 {
          display: grid;
          height: 50px;
          width: 9999px;
          justify-content: center;
          font-family: 'Times New Roman';
          color :white;
         /* grid-template-columns: 50px 50px 50px; /*Make the grid smaller than the container*/
          grid-gap: 10px;
          background-color: #ff0000;
          position:absolute;
          top:120px;
          padding: 15px;
          z-index: 0;
        }

        .box {
            background-color: rgba(255, 137, 137, 0.8);
              text-align: center;
              padding: 5px;
              font-size: 25px;}

  .searchbox {
     background-color: rgb(216, 117, 117);
     text-align: left;
     padding: 4px;
     font-size: 20px;
     color: black;
     }    

.search-container button {
  float: right;
  padding: 6px 10px;
  margin-top: 8px;
  margin-right: 16px;
  background: #ddd;
  font-size: 17px;
  border: none;
  cursor: pointer;
}

.search-container button:hover {
  background: rgb(255, 255, 255);             
}
    
.dropdown {
  position: relative;
  display: inline-block;
}

.dropdown-content {
  display: none;
  position: absolute;
  background-color: #2b2a2a;
  min-width: 270px;
  box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
  padding: 12px 16px;
  z-index: 1;
}

.dropdown:hover .dropdown-content {
  display: block;
}



    .anch:link, .anch:visited
    {  background-color: rgba(253, 168, 168, 0.8);
      color:white;
      padding: 5px;
      text-align: center;
      display: inline block;
      font-size: 25px;}
    
     .anch:hover, .anch:active
    { background-color: rgb(145, 223, 145);}
 

        table, th, td {
      border: 1px solid black;
      border-collapse: collapse;
      background-color: rgb(196, 195, 195);
      align-self: center;
      position:relative;
      background-position: bottom;
    }

    th,td{
      padding: 2px;
      text-align: center;
      font-size: 20px;
    }

  .tabel{
    position:relative;
    background-position: left;
  }

  .imag{
    width:280px ; 
    height:280px;
    border:4px solid black;
    border-color: rgb(0, 0, 0);
    position:absolute; 
    left:550px;
    top:670px;
  }

  footer {
  text-align: center;
  padding: 5px;
  background-color: rgb(66, 65, 65);
  color: white;
  font-size: 20px;
  }

        </style>

<script>
    $('.carousel').carousel({
      interval: 2000
    })
    
    function setnew1(){
        document.getElementById("mp").src="Londonlook1.jpg"}

    function setold1(){
        document.getElementById("mp").src="back1.jfif"}

        function setnew2(){
        document.getElementById("mq").src="Tokyolympic2.jpg"}

    function setold2(){
        document.getElementById("mq").src="back2.jfif"}
  
        function setnew3(){
        document.getElementById("mr").src="Miami pRoject3.jpg"}

    function setold3(){
        document.getElementById("mr").src="back3.jfif"}


  </script>


<body>

    <div class="grid-container1">

        <link type="text/css" rel="stylesheet" href="cascadepic.css">
    <hr><img style="position:absolute; left:670px; top:12px;"class="circular--square" src="maindp.jfif" width="109px" height="95px"/></hr>
<header style="font-size: 70px; position:absolute; left:810px; top: 5px;">  <b>Home Design</b> </header>
<header style="font-size: 25px; position:absolute; left:1260px; top: 54px;"> By Aniesh Das</header>
</div>

<div class="container" style="position: absolute; left:540px;top:170px; background-position:top ;">
    <div id="myCarousel" class="carousel slide" data-ride="carousel">
      <!-- Indicators -->
      <ol class="carousel-indicators">
        <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
        <li data-target="#myCarousel" data-slide-to="1"></li>
        <li data-target="#myCarousel" data-slide-to="2"></li>
      </ol>
  
      <!-- Wrapper for slides -->
      <div class="carousel-inner">
        <div class="item active" data-interval="500">
          <img src="photo1.JPG" alt="Los Angeles" style="width:100%;">
        </div>
        <div class="item" data-interval="500">
          <img src="photo2.jfif" alt="Chicago" style="width:100%;">
        </div>
      
        <div class="item" data-interval="500">
          <img src="photo3.jfif" alt="New york" style="width:100%;">
        </div>
      </div>
  
      <!-- Left and right controls -->
      <a class="left carousel-control" href="#myCarousel" data-slide="prev">
        <span class="glyphicon glyphicon-chevron-left"></span>
        <span class="sr-only">Previous</span>
      </a>
      <a class="right carousel-control" href="#myCarousel" data-slide="next">
        <span class="glyphicon glyphicon-chevron-right"></span>
        <span class="sr-only">Next</span>
      </a>
    </div>
  </div>

<div class="grid-container2">
    <div id="gallery" class="box" style="position: absolute; left:600px; top: 3px;"><a class="anch" href="https://ani-das.github.io/Homeinteriordesign.github.io/" target="_blank">Home</a></div>
    <div id="more" class="box" style="position: absolute; left:800px; top: 3px;"><a class="anch" href="https://ani-das.github.io/Myportfolio.github.io/" target="_blank">About</a></div>
    <div class="box" style="position: absolute; left:1000px; top: 3px;"><a class="anch" href="https://ani-das.github.io/Myportfolio.github.io/" target="_blank">Socials</a></div>
    <div class="box" style="position: absolute; left:1200px; top: 3px;"><a class="anch" href="https://ani-das.github.io/Myportfolio.github.io/" target="_blank">Contact</a></div>
    <div class="searchbox" style="position: absolute; left:1400px; top: 3px;">
      <form action="/action_page.php">
      <input type="text" placeholder="Search.." name="search">
      <button type="submit"><i class="fa fa-search"></i></button>
    </form>
    </div>
</div>



<table style="width:400px; height: 890px;">
    <tr>
       <th>
        <div class="dropdown">
          <span><b>Contents v </b></span>
          <div class="dropdown-content">
            <p><div class="box" ><a class="anch" href="#gallery" target="_blank">1.Gallery</a></div></p>
            <p><div class="box" ><a class="anch" href="#port" target="_blank">2.Portfolio</a></div></p>
            <p><div class="box" ><a class="anch" href="#major" target="_blank">3.Major projects</a></div></p>
            <p><div class="box" ><a class="anch" href="#more" target="_blank">4.More</a></div></p>
          </div>
        </div> </th>
    </tr>
    <tr>
       <td> 
        <div class="dropdown">
          Gallery
          <div class="dropdown-content">
            <p><div class="box" ><a class="anch" href="www.interiordesign.com" target="_blank">-Living room</a></div></p>
            <p><div class="box" ><a class="anch" href="www.interiordesign.com" target="_blank">-Kitchen</a></div></p>
            <p><div class="box" ><a class="anch" href="www.interiordesign.com" target="_blank">-Dining Hall</a></div></p>
            <p><div class="box" ><a class="anch" href="www.interiordesign.com" target="_blank">-Bathroom</a></div></p>
          </div>
        </div>   
      </td>
    </tr>
    <tr>
       <td id="port"> 
        <div class="dropdown">
          Portfolio
          <div class="dropdown-content">
            <p><div class="box" ><a class="anch" href="www.interiordesign.com" target="_blank">-London Project</a></div></p>
            <p><div class="box" ><a class="anch" href="www.interiordesign.com" target="_blank">-Miami Project</a></div></p>
            <p><div class="box" ><a class="anch" href="www.interiordesign.com" target="_blank">-Tokyo Project</a></div></p>
          </div>
        </div>    
        </td>
    </tr>
    <tr>
        <td id="major"> Major Projects </td>
    </tr>
    <tr><td></td></tr>
</table>

<img class="imag" style="position:absolute; left:550px;top:700px;" id="mp" onmouseover="setnew1()" onmouseout="setold1()" src="back1.jfif">
<img class="imag" style="position:absolute; left:1050px;top:700px;" id="mq" onmouseover="setnew2()" onmouseout="setold2()" src="back2.jfif">
<img class="imag" style="position:absolute; left:1550px;top:700px;" id="mr" onmouseover="setnew3()" onmouseout="setold3()" src="back3.jfif">

<footer>
  <p>Author: Aniesh Das<br>
  <a href="mailto:anieshpictmun@gmail.com">anieshpictmun@gmail.com</a></p>
</footer>

</body>

    </html>
