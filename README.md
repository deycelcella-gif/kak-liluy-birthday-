<!DOCTYPE html>
<html>
<head>
<title>for liluy 🌼</title>

<style>
body{
background:#fff6c9;
font-family:Arial;
text-align:center;
padding:40px;
}

.card{
background:#fffdf0;
padding:30px;
border-radius:25px;
width:360px;
margin:auto;
box-shadow:0 8px 20px rgba(0,0,0,0.1);
}

h1{
color:#d4b200;
}

p{
color:#555;
}

button{
background:#ffe680;
border:none;
padding:10px 18px;
border-radius:15px;
cursor:pointer;
}

#flower{
font-size:50px;
cursor:pointer;
margin:20px;
}

</style>
</head>

<body>

<div class="card">

<h1>for you 🌼</h1>

<p>
thank you for your presence and for being such a cheerful person.  
your energy always brings warmth and happiness to people around you.  
i'm really grateful to know someone as kind and bright as you.  

happy birthday kak liluy ku sayang!! 💛
</p>

<h3>flower game 🌷</h3>

<p>klik bunganya buat dapet poin</p>

<div id="flower" onclick="addPoint()">🌼</div>

<p>score: <span id="score">0</span></p>

<button onclick="moveFlower()">move flower</button>

</div>

<script>

let score = 0

function addPoint(){
score++
document.getElementById("score").innerHTML = score
}

function moveFlower(){
let x = Math.random()*200-100
let y = Math.random()*200-100
document.getElementById("flower").style.transform =
"translate("+x+"px,"+y+"px)"
}

</script>

</body>
</html># kak-liluy-birthday-
