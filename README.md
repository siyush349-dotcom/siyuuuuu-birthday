<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>For Siyuuuuu 💙</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
}

body{
background:linear-gradient(180deg,#0b1d3a,#133c7a);
color:white;
text-align:center;
overflow-x:hidden;
}

section{
min-height:100vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
padding:30px;
}

h1{
font-size:3rem;
margin-bottom:20px;
animation:fade 2s ease;
}

p{
font-size:1.1rem;
max-width:700px;
line-height:1.8;
}

.btn{
margin-top:25px;
padding:12px 25px;
border:none;
border-radius:30px;
background:white;
color:#133c7a;
font-size:18px;
cursor:pointer;
}

.gallery{
display:flex;
gap:15px;
flex-wrap:wrap;
justify-content:center;
margin-top:25px;
}

.gallery img{
width:220px;
height:300px;
object-fit:cover;
border-radius:15px;
box-shadow:0 0 15px rgba(255,255,255,.3);
}

.heart{
font-size:70px;
animation:beat 1s infinite;
}

@keyframes beat{
50%{
transform:scale(1.2);
}
}

@keyframes fade{
from{
opacity:0;
transform:translateY(30px);
}
to{
opacity:1;
transform:translateY(0);
}
}

.stars{
position:fixed;
width:100%;
height:100%;
top:0;
left:0;
z-index:-1;
background:url('https://i.imgur.com/8IuucQZ.png');
animation:move 80s linear infinite;
}

@keyframes move{
from{background-position:0 0;}
to{background-position:0 2000px;}
}
</style>
</head>

<body>

<div class="stars"></div>

<section>
<h1>💙 For Siyuuuuu 💙</h1>

<p>
1 July...
A day that became special because someone special was born.
</p>

<button class="btn"
onclick="document.getElementById('memories').scrollIntoView({behavior:'smooth'})">
Open 💙
</button>
</section>

<section id="memories">
<h1>✨ Memories ✨</h1>

<p>
Some moments don't need a reason to be remembered.
</p>

<div class="gallery">
<img src="photo1.jpg">
<img src="photo2.jpg">
<img src="photo3.jpg">
</div>
</section>

<section>
<h1>🌸 About You 🌸</h1>

<p>
A girl who cares.<br><br>

A girl who keeps trying even when things are difficult.<br><br>

A girl who thinks about others before herself.<br><br>

A girl who stays real in a world full of filters.<br><br>

A girl called Siyuuuuu. 💙
</p>
</section>

<section>
<h1>🎂 Happy Birthday 🎂</h1>

<p>
Happy Birthday, Siyuuuuu 💙
<br><br>

You are one of those people who make others feel valued without even trying.
<br><br>

Your kindness, your efforts, and your genuine heart make you special.
<br><br>

May this year bring you happiness, peace, success and beautiful memories.
<br><br>

Whenever life gets difficult,
remember that you are stronger than you think.
<br><br>

Keep smiling.
Keep shining.
Keep being you. 💙
</p>
</section>

<section>
<div class="heart">💙</div>

<h1>One Last Thing...</h1>

<p style="font-size:1.5rem;">
Thank You For Being You, Siyuuuuu 💙
</p>

<br>

<p>
May your smile never fade.
</p>
</section>

</body>
</html># siyuuuuu-birthday
A special birthday surprise for someone special 💙
