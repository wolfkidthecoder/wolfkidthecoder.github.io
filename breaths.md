layout: page
title: “breaths”
permalink: /breaths/
<style>
body {background-color: black;}
body {color: white;}
input[type=number] {
  background-color: #ffffff;
  color: black;
}
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
</style>
<div id = "leave">
<center>
<form>
Enter your age:
<input type="number" id="age" name="age" placeholder="age" color="white">
</form>
<br><br><br><br><br><br>
<div>
<button onclick="clicked()">click me</button>
</div>
</center>
</div>
<center>
<h1 id="heading"> 
lalalalaaaaaaaaaaa
</h1>
</center><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
<script>
var left
function clicked ()
{
document.getElementById("leave").style.display = "none";
var amount = 672768000; 
var age = document.getElementById("age").value;
left = amount - age * 8409600;
console.log(left);
document.getElementById("heading").innerHTML = "You have "+left+" breaths left";
setInterval(down,3000)
}
function down ()
{
left = left - 1
document.getElementById("heading").innerHTML = "You have "+left+" breaths left";
}
</script>
