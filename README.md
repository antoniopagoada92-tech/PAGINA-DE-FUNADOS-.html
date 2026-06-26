# PAGINA-DE-FUNADOS-.html
Paginas para funar
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Broma</title>
<style>
body{
  margin:0;
  background:black;
  overflow:hidden;
  color:red;
  font-family:Arial,sans-serif;
}
.marquee{
  position:absolute;
  font-size:40px;
  font-weight:bold;
  animation:mover 4s linear infinite;
}
@keyframes mover{
  from{transform:translateX(-100vw);}
  to{transform:translateX(100vw);}
}
</style>
</head>
<body>
<script>
for(let i=0;i<100;i++){
  let t=document.createElement("div");
  t.className="marquee";
  t.innerText="PUTO";
  t.style.top=Math.random()*window.innerHeight+"px";
  t.style.animationDelay=(Math.random()*4)+"s";
  document.body.appendChild(t);
}
</script>
</body>
</html>
