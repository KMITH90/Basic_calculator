# Basic_calculator
<!DOCTYPE html>
<html>
<head>
<title>Calculator</title><br />
<style>
html{
    background-image: url("https://shorturl.at/Yzu8L");
}<br />
body{
    place-items: center;
    display: grid;
    background-image: url("https://shorturl.at/hjsuN");
    background-size: cover;
}<br />
table{
    border-style: outset;
    padding: 0%;
    border-spacing: 7px;
    border-width: 10px;
    border-color: rgb(113, 2, 113);
    background-color:rgb(255, 255, 255);
}<br />
input[type="button"] {
        width: 50px;
        height: 30px;
        border-style: outset;
        color: white ;
        background-color: rgb(113, 2, 113);
        border-radius: 3px;
 }<br />
 input[type="text"]{
    border-style:inset;
    background-color:rgb(229, 200, 255);
    border-radius: 5px;
    height: 30px;
    width: 230px;
 }<br />
 h1{
    font-style:oblique;
  color: rgb(81, 12, 95);
  text-align: center;
 }<br />
</style>
</head>
<body>
<div class="main">
<table>
  <h1>CALCULATOR</h1>
  <tr>
    <td colspan="4">
      <input id="display" type="text">
    </td>
  </tr>
  <tr>
    <td><input type="button" value="C"
onclick="document.getElementById('display').value = ''"></td>
    <td><input type="button" value="."
onclick="document.getElementById('display').value = '.'"></td>
    <td><input type="button" value="%"
onclick="document.getElementById('display').value +='%'"></td>
    <td><input type="button" value="/"
onclick="document.getElementById('display').value +='/'"></td>
  </tr>
  <tr>
    <td><input type="button" value="1"
onclick="document.getElementById('display').value +='1'"></td>
    <td><input type="button" value="2"
onclick="document.getElementById('display').value +='2'"></td>
    <td><input type="button" value="3"
onclick="document.getElementById('display').value +='3'"></td>
    <td><input type="button" value="+"
onclick="document.getElementById('display').value +='+'"></td>
  </tr>
  <tr>
    <td><input type="button" value="4"
onclick="document.getElementById('display').value +='4'"></td>
    <td><input type="button" value="5"
onclick="document.getElementById('display').value +='5'"></td>
    <td><input type="button" value="6"
onclick="document.getElementById('display').value +='6'"></td>
    <td><input type="button" value="-"
onclick="document.getElementById('display').value +='-'"></td>
  </tr>
  <tr>
    <td><input type="button" value="7"
onclick="document.getElementById('display').value +='7'"></td>
    <td><input type="button" value="8"
onclick="document.getElementById('display').value +='8'"></td>
    <td><input type="button" value="9"
onclick="document.getElementById('display').value +='9'"></td>
    <td><input type="button" value="*"
onclick="document.getElementById('display').value +='*'"></td>
  </tr>
  <tr>
    <td><input type="button" value="0"
onclick="document.getElementById('display').value +='0'"></td>
    <td><input type="button" value="00"
onclick="document.getElementById('display').value +='00'"></td>
    <td><input type="button" value="="
onclick="document.getElementById('display').value =eval(document.getElementById('display').value)"></td>
    <td><input type="button" value="E"
onclick="document.getElementById('display').value = document.getElementById('display').value.slice(0, -1)"></td>
        
  </tr>
</table>
</div>
</body>
</html>
