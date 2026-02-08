<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Be My Valentine 💖</title>

<style>
body{
  margin:0;
  height:100vh;
  background:linear-gradient(135deg,#ff9a9e,#fad0c4);
  overflow:hidden;
  font-family:'Segoe UI',sans-serif;
}

/* Floating hearts */
.heart{
  position:absolute;
  width:20px;
  height:20px;
  background:red;
  transform:rotate(45deg);
  animation:float 8s linear infinite;
  opacity:.6;
}
.heart::before,.heart::after{
  content:'';
  width:20px;height:20px;
  background:red;
  border-radius:50%;
  position:absolute;
}
.heart::before{top:-10px;left:0}
.heart::after{left:-10px;top:0}

@keyframes float{
  0%{transform:translateY(100vh) rotate(45deg);opacity:0}
  20%{opacity:.6}
  100%{transform:translateY(-10vh) rotate(45deg);opacity:0}
}

/* Card */
.container{
  height:100vh;
  display:flex;
  align-items:center;
  justify-content:center;
  z-index:2;
  position:relative;
}
.card{
  background:#fff;
  padding:35px 45px;
  border-radius:25px;
  text-align:center;
  box-shadow:0 15px 30px rgba(0,0,0,.25);
}
h1{
  color:#e63946;
  margin-bottom:25px;
}

/* Buttons */
.buttons{
  position:relative;
  height:160px;
}
button{
  padding:12px 28px;
  font-size:18px;
  border:none;
  border-radius:30px;
  cursor:pointer;
  transition:.3s ease;
}
#yesBtn{
  background:#e63946;
  color:#fff;
}
#noBtn{
  background:#adb5bd;
  position:absolute;
  left:55%;
  top:50%;
}

/* Kiss animation */
.kiss{
  position:absolute;
  font-size:30px;
  animation:kissFloat 2s linear forwards;
}
@keyframes kissFloat{
  0%{transform:translateY(0);opacity:1}
  100%{transform:translateY(-150px);opacity:0}
}
</style>
</head>

<body>

<audio id="bgMusic" autoplay loop>
<source src="https://cdn.pixabay.com/download/audio/2022/03/15/audio_7c0b9b2b98.mp3">
</audio>

<script>
for(let i=0;i<25;i++){
  let h=document.createElement("div");
  h.className="heart";
  h.style.left=Math.random()*100+"vw";
  h.style.animationDuration=6+Math.random()*4+"s";
  h.style.width=h.style.height=10+Math.random()*20+"px";
  document.body.appendChild(h);
}
</script>

<div class="container">
  <div class="card">
    <h1>Sanyukta, will you be my Valentine? 💝</h1>
    <div class="buttons">
      <button id="yesBtn">Yes 💖</button>
      <button id="noBtn">No 🙈</button>
    </div>
  </div>
</div>

<script>
const noBtn=document.getElementById("noBtn");
const yesBtn=document.getElementById("yesBtn");
const music=document.getElementById("bgMusic");
music.volume=0.12;

const excuses=[
  "Are you sure? 😏",
  "Think again 🙄",
  "Wrong choice 😂",
  "Don’t break my heart 💔",
  "Nice try 😜",
  "Still no? 😈"
];

let count=0;
let yesScale=1;

function moveNo(){
  const x=Math.random()*(window.innerWidth-noBtn.offsetWidth);
  const y=Math.random()*(window.innerHeight-noBtn.offsetHeight);
  noBtn.style.left=x+"px";
  noBtn.style.top=y+"px";
  noBtn.innerText=excuses[count%excuses.length];
  count++;

  // Grow YES button
  yesScale+=0.25;
  yesBtn.style.transform=`scale(${yesScale})`;

  music.play();
}

noBtn.addEventListener("mouseover",moveNo);
noBtn.addEventListener("click",moveNo);

yesBtn.addEventListener("click",()=>{
  music.play();
  document.body.innerHTML=`
  <div style="
    height:100vh;
    display:flex;
    align-items:center;
    justify-content:center;
    background:linear-gradient(135deg,#ff758c,#ff7eb3);
    font-family:'Segoe UI',sans-serif;
    text-align:center;
    overflow:hidden;">
    <h1 style="color:white;font-size:38px;">
      Yayyy!! 💕<br>
      Thank you for choosing me your Valentine 😘<br><br>
      <span style="font-size:30px;">Love uhh Bokiii 😘</span>
    </h1>
  </div>`;

  // Kiss animation
  for(let i=0;i<30;i++){
    let k=document.createElement("div");
    k.className="kiss";
    k.innerText="💋";
    k.style.left=Math.random()*100+"vw";
    k.style.top="70vh";
    document.body.appendChild(k);
  }
});
</script>

</body>
</html>
