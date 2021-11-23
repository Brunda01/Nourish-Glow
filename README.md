<!DOCTYPE html>
<html lang="en" dir="ltr">
<head>
    <meta charset="utf-8">
    <title>Nourish & Glow</title>
    <link rel="stylesheet" href="./gym.css">

    <!-- CSS code -->
<style>

 body {
      color: white;
      margin: 0px;
      padding: 0px;
      background: url('img/gym bg.jpg');
      background-size: 5300px;
      background-repeat: no-repeat;
      font-size: 50pt;
      }

.left {
  display: inline-block;
  position: absolute;
  left: 34px;
  top: 20px;
  text-align:left;
}

.left img {
  width: 250px;
  height: 250px;

}

.mid {
  display: block;
  width: 33%;
  margin: 29px auto;
  font-size: 59pt;

}

.right {
  position: absolute;
  right: 34px;
  display: inline-block;
  top: 90px;
  font-size: 100pt;

}

.navbar {
  display: inline-block;
}

.navbar li {
  display: inline-block;
}

.navbar li a {
  color: white;
  text-decoration: none;
  padding: 34px 23px;
}

.navbar li a:hover, .navbar li a.active {
  color: grey;
  text-decoration: underline;

}

.container {
  border: 5px solid white;
  margin: 95px 189px;
  padding: 75px;
  width: 33%;
  border-radius: 30px;
  font-size: 40pt;
  background-color: black;
  color: white;
}

.form-group input {
  text-align: center;
  font-size: 35pt;
  width: 1088px;
  padding: 27px;
  border: 2px solid black;
  margin: 18px auto;
  display: block;
  border-radius: 20px;

}

.btn {
  background-color: lightgrey;
  color: black;
  font-size: 40pt;
  border: 2px solid grey;
  margin: 0px 9px;
  padding: 4px 14px;
  cursor: pointer;
  border-radius: 10px;

}

.container h1 {
  text-align: center;
}

.container button {
  display: block;
  width: 23%;
  margin:auto;
}

.right button {
  background-color: white;
  color: black;
  border: 6px solid grey;
  font-size: 40pt;
  margin: auto;

}

</style>

<!-- CSS code ends -->

</head>
  <body>
    <header class="header">
      <!-- Left box for logo-->
      <div class="left">
        <img src="img/img.png" alt="">

      </div>

      <!-- Mid box for navbar -->
      <div class="mid">
        <ul class="navbar">


        <li><a href="#" class="active">Home</a></li>
        <li><a href="#">About us</a></li>
        <li><a href="#">Fitness calculator</a></li>
        <li><a href="#">Contact us</a></li>

        </ul>
      </div>

      <!-- Right box for title -->
      <div class="right">
      <em>Nourish & Glow</em>
      <br>

      <button class="btn">Call us</button>
      <button class="btn">Email us</button>

      </div>

    </header>
    <br>
    <br>

<div class="container">
   <h1>Join the best gym of chittoor now</h1>
   <form class="noaction.php">

     <div class="form-group">
       <input type="text" name="" placeholder="Enter your Name">
     </div>

     <div class="form-group">
       <input type="text" name="" placeholder="Enter your Age">
     </div>

     <div class="form-group">
       <input type="text" name="" placeholder="Enter your Gender">
     </div>

     <div class="form-group">
       <input type="text" name="" placeholder="Enter your Contact number">
     </div>

     <br>
     <br>

     <button class="btn">Submit</button>

   </form>
</div>


  </body>
</html>
