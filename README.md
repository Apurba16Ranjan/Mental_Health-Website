<!DOCTYPE html>
<head>
<style>
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: none;
}

li {
  float: right;
}

li a {
  display: block;
  color: black;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

li a:hover {
  background-color: white;
}



.button {
  display: inline-block;
  border-radius: 4px;
  background-color: red;
  border: none;
  color: #FFFFFF;
  text-align: center;
  font-size: 17px;
  padding: 5px;
  width: 200px;
  height: 30px;
  transition: all 0.5s;
  cursor: pointer;
  margin: 8px;
 float:right;
}

.button span {
  cursor: pointer;
  display: inline-block;
  position: relative;
  transition: 0.5s;
}

.button span:after {
  content: '\00bb';
  position: absolute;
  opacity: 0;
  top: 0;
  right: -20px;
  transition: 0.5s;
}

.button:hover span {
  padding-right: 30px;
}

.button:hover span:after {
  opacity: 1;
  right: 0;
}
.button {width: 130px;}

.button1 {font-size: 10px;}
.button2 {font-size: 15px; float:left;
background-color: #f4511e;
  border: none;
  color: white;
  padding: 16px 32px;
  text-align: center;
  margin: 4px 2px;
  opacity: 0.6;
  transition: 0.3s;
  display: inline-block;
  text-decoration: none;
  cursor: pointer;}

li.ex1 {
  margin-left: 100px;
}
h1.ex1 {
  margin-left: 100px;
}
p.ex1 {
  margin-left: 100px;
}
button2.ex1 {
  margin-left: 100px;
}


</style>
</head>
<body bgcolor="pink">
<ul>
<button class="button" style="vertical-align:middle"><span>Contact us </span></button>
  <li class="ex1" style="float:left"><a href="#title">Title</a></li>
  <li><a href="#about">About</a></li>
  <li><a href="#features">Features</a></li>
  <li><a href="#medical resources">Medical Resources</a></li>
  <li><a href="#play game">Play Game</a></li>
  <li><a href="#music">Music</a></li>
</ul>
<h1 class="ex1" style="font-size:70px;">Learn To Accept<br>Imperfections
</h1>
<p class="ex1" style="font-size:22px;">You don’t have to control your thoughts. You just<br>have to stop letting them control you.<br>
One small crack does not mean that you are broken,<br>it means that you were put to the test and you didn’t<br>fall apart.</p>

<button2 class="ex1 button2">MENTAL HEALTH</button>

</body>
</html>
