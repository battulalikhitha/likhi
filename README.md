<html>
<head>
    <title>NAvBar using flexbox</title>
    <title text-align: center>NAvBar using flexbox</title>
<style>
*{
background-color: black;
}
h1{
    background-color: rgb(113, 36, 72);
    color: black;
    background-color: black(113, 36, 72);
    color: darkgreen;
    text-align: center;
}
p{
    color: white;
    color:brown;
    text-align: center;
}
.flex-container {
  display: flex;
  background-color: rgb(26, 59, 93);
  background-color: black(26, 59, 93);
  margin: 0px;
  padding: 5px;
  box-sizing: border-box;
}

.flex-container > div {
  background-color: #f1f1f1; 
  background-color:chartreuse; 
  flex-shrink: 0.6;
  margin: 75px;
  padding: 5px;
  font-size: 55px;
}
#a:hover,#b:hover,#c:hover,#d:hover,a:hover{
    background-color: pink;
    background-color: lightcyan;
}
a{
    text-decoration: none;
    background-color:white ;
    background-color:aliceblue ;
}
</style>
</head>
@@ -43,7 +43,7 @@
<h1>Navbar</h1>

<div class="flex-container">
  <div id="a"><a href="./hello.html">Home</a></div>
  <div id="a"><a href="./hello.html">home</a></div>
  <div id="b"><a href="./about.html">About</a></div>
  <div id="c"><a href="./details.html">Details</a></div>  
  <div id="d"><a href="./contact.html">Contact</a></div>
