<!doctype html>
<html lang="es">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="theme-color" content="#100b10">
<meta name="description" content="ECLIPSE DUNGEON: RPG de fantasía oscura, exploración de mazmorras y combate por turnos.">
<title>ECLIPSE DUNGEON — Presentación del proyecto</title>
<style>
@import url('https://fonts.googleapis.com/css2?family=Cinzel:wght@500;600;700;800&family=Inter:wght@400;500;600;700&display=swap');
:root{--bg:#100b10;--panel:#1b1218;--panel2:#241820;--gold:#d6b77a;--gold2:#f0d9a2;--muted:#b8a8a8;--red:#9d3f46;--line:#49313a;--white:#f4e9dc}
*{box-sizing:border-box}html{scroll-behavior:smooth}body{margin:0;background:radial-gradient(ellipse at 75% 5%,#40202c 0,transparent 38%),linear-gradient(180deg,#100b10,#160e14 55%,#0d090d);color:var(--white);font-family:Inter,Arial,sans-serif}a{color:inherit;text-decoration:none}.wrap{width:min(1120px,92%);margin:auto}.nav{display:flex;align-items:center;justify-content:space-between;padding:22px 0;border-bottom:1px solid #ffffff18}.brand{font:700 18px Cinzel;color:var(--gold2);letter-spacing:2px}.navlinks{display:flex;gap:22px;color:var(--muted);font-size:13px}.navlinks a:hover{color:var(--gold2)}.hero{min-height:590px;display:grid;grid-template-columns:1.05fr .95fr;align-items:center;gap:30px;padding:70px 0 55px}.eyebrow{font-size:11px;letter-spacing:3px;color:var(--gold);font-weight:700}.hero h1{font:800 clamp(42px,7vw,78px)/.98 Cinzel;margin:18px 0;color:#f5e4c6;text-shadow:0 5px 35px #9b4a3c55}.hero h1 span{color:#c16d68}.lead{color:#cbbaba;line-height:1.8;max-width:570px;font-size:16px}.actions{display:flex;gap:12px;flex-wrap:wrap;margin-top:28px}.btn{padding:13px 19px;border:1px solid var(--gold);font-size:12px;font-weight:700;letter-spacing:1px;text-transform:uppercase;display:inline-flex;align-items:center;justify-content:center;cursor:pointer}.btn.primary{background:linear-gradient(135deg,#c7a66a,#8d5b4b);color:#160e12;border:0}.btn.secondary{color:var(--gold2);background:#ffffff08}.hero-art{height:410px;position:relative;overflow:hidden;border:1px solid #9b6a5b66;background:linear-gradient(180deg,#170e18 0%,#341c2a 52%,#0b080c 100%);box-shadow:0 25px 80px #0009}.moon{position:absolute;width:180px;height:180px;border-radius:50%;background:radial-gradient(circle,#ead5a2,#a96b64 62%,#572c3d 70%,transparent 72%);top:35px;left:calc(50% - 90px);opacity:.85;box-shadow:0 0 75px #d18c6d66}.arch{position:absolute;width:64%;height:85%;left:18%;bottom:-10%;border:20px solid #65404a;border-bottom:0;border-radius:50% 50% 0 0;box-shadow:inset 0 0 0 8px #271722,0 0 0 4px #9c6b5a}.arch:before,.arch:after{content:"";position:absolute;bottom:0;width:24px;height:65%;background:#67434a}.arch:before{left:-32px}.arch:after{right:-32px}.floor{position:absolute;bottom:0;width:100%;height:29%;background:repeating-linear-gradient(170deg,#3b202b 0 2px,#180f17 2px 13px);clip-path:polygon(0 20%,100% 0,100% 100%,0 100%)}.silhouette{position:absolute;z-index:2;bottom:18%;left:50%;transform:translateX(-50%);font-size:145px;filter:drop-shadow(0 0 18px #d5a66b88);color:#d4b47a}.art-caption{position:absolute;z-index:3;bottom:17px;left:20px;font:600 12px Cinzel;letter-spacing:2px;color:var(--gold2)}.art-caption small{display:block;color:#b99b8b;font:10px Inter;letter-spacing:2px;margin-top:6px}.section{padding:65px 0;border-top:1px solid #ffffff12}.section h2{font:700 clamp(26px,4vw,39px) Cinzel;color:var(--gold2);margin:8px 0 14px}.sub{color:var(--muted);line-height:1.7;max-width:720px}.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:15px;margin-top:28px}.card{background:linear-gradient(145deg,#251820,#171016);border:1px solid var(--line);padding:22px;min-height:150px}.ico{font-size:25px;color:var(--gold);margin-bottom:14px}.card h3{font:600 16px Cinzel;color:#f0d9b5;margin:0 0 9px}.card p{font-size:13px;line-height:1.65;color:var(--muted);margin:0}.split{display:grid;grid-template-columns:1fr 1fr;gap:35px;align-items:start}.list{list-style:none;padding:0;margin:22px 0}.list li{padding:12px 0;border-bottom:1px solid #ffffff12;color:#d9c9c0;font-size:14px}.list li:before{content:"✦";color:var(--gold);margin-right:12px}.tag{display:inline-block;border:1px solid #80604e;color:var(--gold2);padding:6px 9px;font-size:10px;letter-spacing:1px;margin:4px 4px 0 0}.heroes{display:grid;grid-template-columns:repeat(3,1fr);gap:10px;margin-top:20px}.hero-card{padding:15px;background:#21171e;border:1px solid #49313a}.hero-card b{display:block;color:var(--gold2);font:600 14px Cinzel;margin:7px 0 4px}.hero-card span{font-size:12px;color:var(--muted)}.symbol{font-size:27px;color:var(--gold)}.steps{counter-reset:step}.step{display:flex;gap:15px;padding:14px 0;border-bottom:1px solid #ffffff12}.step:before{counter-increment:step;content:counter(step,decimal-leading-zero);font:700 18px Cinzel;color:var(--gold)}.step p{margin:0;color:#cbbaba;font-size:13px;line-height:1.6}.contactbox{background:linear-gradient(120deg,#30202a,#1a1118);border:1px solid #6d4b4d;padding:28px;display:flex;align-items:center;justify-content:space-between;gap:25px}.contactbox h3{font:700 23px Cinzel;color:var(--gold2);margin:0 0 8px}.contactbox p{color:var(--muted);font-size:13px;line-height:1.6;margin:0}.qrbox{width:145px;min-width:145px;background:white;padding:10px;text-align:center;color:#222}.qrbox img{width:100%;display:block;min-height:120px}.qrbox small{font-size:10px}.qr-tools{margin-top:18px;padding:18px;border:1px solid var(--line);background:#160f15}.qr-tools label{display:block;font-size:12px;color:var(--gold2);margin-bottom:8px}.qr-tools input{width:100%;padding:12px;background:#0e0a0e;border:1px solid #63434b;color:white;margin-bottom:10px}.qr-tools button{background:#b38b58;color:#160e12;border:0;padding:11px 15px;font-weight:700;cursor:pointer}.foot{padding:28px 0;color:#8f7e82;font-size:11px;display:flex;justify-content:space-between;gap:15px;border-top:1px solid #ffffff12}.note{color:#a99492;font-size:11px;line-height:1.6;margin-top:12px}
@media(max-width:760px){.navlinks{display:none}.hero{grid-template-columns:1fr;padding:48px 0}.hero-art{height:300px}.grid{grid-template-columns:1fr 1fr}.split{grid-template-columns:1fr}.contactbox{align-items:flex-start;flex-direction:column}.heroes{grid-template-columns:1fr 1fr}.foot{flex-direction:column}}
@media(max-width:460px){.grid{grid-template-columns:1fr}.heroes{grid-template-columns:1fr 1fr}.hero h1{font-size:43px}}
</style>
</head>
<body>
<header class="wrap nav">
  <a class="brand" href="#">ECLIPSE DUNGEON</a>
  <nav class="navlinks"><a href="#juego">EL JUEGO</a><a href="#aventureros">AVENTUREROS</a><a href="#sistemas">SISTEMAS</a><a href="#contacto">CONTACTO</a></nav>
</header>
<main>
<section class="wrap hero">
 <div>
  <div class="eyebrow">UN RPG DE FANTASÍA OSCURA</div>
  <h1>La luz se<br><span>está apagando.</span></h1>
  <p class="lead">Bajo las ruinas de Vhal, algo antiguo ha despertado. Reúne a tu compañía, desciende a la Cripta de Vhal y descubre qué aguarda al final del eclipse. Explora habitaciones, enfrenta criaturas y sobrevive a combates estratégicos por turnos.</p>
  <div class="actions"><a class="btn primary" href="#juego">Descubrir el juego</a><a class="btn secondary" href="#contacto">Contactar al desarrollador</a></div>
 </div>
 <div class="hero-art" role="img" aria-label="Ilustración abstracta de una entrada de mazmorra bajo un eclipse">
  <div class="moon"></div><div class="arch"></div><div class="silhouette">◆</div><div class="floor"></div>
  <div class="art-caption">CRIPTA DE VHAL<small>LA EXPEDICIÓN COMIENZA</small></div>
 </div>
</section>
<section class="section" id="juego"><div class="wrap">
 <div class="eyebrow">01 / EL PROYECTO</div><h2>Desciende a la oscuridad</h2>
 <p class="sub">ECLIPSE DUNGEON es un RPG de exploración y combate por turnos. La expedición se desarrolla en mazmorras generadas proceduralmente, con habitaciones conectadas, cofres, enemigos y una salida que conduce a mayores profundidades.</p>
 <div class="grid">
  <article class="card"><div class="ico">⌖</div><h3>Exploración</h3><p>Recorre mapas de 25 × 17 casillas con cinco cámaras conectadas, pasillos, cofres, criaturas y salidas.</p></article>
  <article class="card"><div class="ico">⚔</div><h3>Combate táctico</h3><p>Combates individuales por iniciativa: la velocidad determina el orden de actuación de héroes y enemigos.</p></article>
  <article class="card"><div class="ico">♜</div><h3>Compañía</h3><p>Forma un grupo de cuatro aventureros y distribúyelos entre vanguardia y retaguardia.</p></article>
  <article class="card"><div class="ico">♢</div><h3>Progresión</h3><p>Gana experiencia, sube de nivel, consigue oro y utiliza pociones para mantener al grupo en pie.</p></article>
  <article class="card"><div class="ico">☠</div><h3>Enemigos y jefes</h3><p>Enfrenta ratas de cripta, goblins, esqueletos, arañas, caballeros malditos y al Vigía del eclipse.</p></article>
  <article class="card"><div class="ico">⌘</div><h3>Cooperativo LAN</h3><p>Crea una sala y comparte su código para jugar en red local con hasta cuatro participantes.</p></article>
 </div>
</div></section>
<section class="section" id="aventureros"><div class="wrap split">
 <div><div class="eyebrow">02 / LA COMPAÑÍA</div><h2>Seis héroes.<br>Cuatro lugares.</h2><p class="sub">Elige cuatro personajes de un elenco de seis. Cada aventurero aporta estadísticas, velocidad y una habilidad característica.</p>
 <div class="heroes">
  <div class="hero-card"><div class="symbol">⚔</div><b>Brom</b><span>Guerrero · Golpe sísmico</span></div>
  <div class="hero-card"><div class="symbol">✦</div><b>Nyx</b><span>Maga · Llama umbría</span></div>
  <div class="hero-card"><div class="symbol">➶</div><b>Sable</b><span>Arquera · Disparo certero</span></div>
  <div class="hero-card"><div class="symbol">✚</div><b>Elira</b><span>Clériga · Sanación</span></div>
  <div class="hero-card"><div class="symbol">†</div><b>Vex</b><span>Asesina · Veneno espectral</span></div>
  <div class="hero-card"><div class="symbol">♜</div><b>Kael</b><span>Caballero oscuro · Pacto sangriento</span></div>
 </div></div>
 <div><div class="eyebrow">03 / CÓMO SE JUEGA</div><h2>Explora. Combate. Desciende.</h2><div class="steps">
  <div class="step"><p><b>Explora la Cripta de Vhal.</b><br>Mueve al grupo con WASD o las flechas del teclado.</p></div>
  <div class="step"><p><b>Interactúa con el entorno.</b><br>Usa E o el botón de interacción para abrir cofres y avanzar.</p></div>
  <div class="step"><p><b>Elige tus acciones.</b><br>Ataca, usa habilidades, defiende, consume objetos o espera.</p></div>
  <div class="step"><p><b>Supera al guardián.</b><br>En las profundidades 3 y sus múltiplos aparece un jefe que bloquea el descenso.</p></div>
 </div><p class="note">Los sistemas descritos corresponden a la versión incluida en el archivo del proyecto.</p></div>
</div></section>
<section class="section" id="sistemas"><div class="wrap">
 <div class="eyebrow">04 / TECNOLOGÍA</div><h2>Construido para explorar</h2><p class="sub">El proyecto utiliza herramientas web para renderizar el juego 2D, gestionar la lógica de exploración y habilitar las salas cooperativas.</p>
 <div style="margin-top:18px"><span class="tag">JavaScript</span><span class="tag">Phaser 3</span><span class="tag">Vite</span><span class="tag">Node.js</span><span class="tag">Socket.IO</span><span class="tag">HTML5</span><span class="tag">CSS3</span></div>
 <div class="grid">
  <article class="card"><h3>Modo individual</h3><p>La campaña se guarda en el navegador mediante almacenamiento local y permite continuar una expedición.</p></article>
  <article class="card"><h3>Cooperativo en red local</h3><p>Servidor Socket.IO con salas por código, pensado para partidas en una misma red LAN o Wi-Fi.</p></article>
  <article class="card"><h3>Proyecto ejecutable</h3><p>Se ejecuta desde Visual Studio Code con Node.js y npm, usando los scripts definidos en package.json.</p></article>
 </div>
</div></section>
<section class="section" id="contacto"><div class="wrap">
 <div class="eyebrow">05 / CONTACTO</div><h2>Conoce más sobre el proyecto</h2>
 <div class="contactbox">
  <div><h3>Renee Gabriel Fernandez Urtuvey</h3><p>Desarrollador de ECLIPSE DUNGEON.<br>Para consultas, demostraciones o información del proyecto, utiliza los datos de contacto que se configuren aquí.</p><p class="note">Completa tu correo y WhatsApp en el archivo index.html antes de publicar esta página.</p></div>
  <div class="qrbox"><img id="qrImage" alt="Código QR de esta página"><small>QR DE ESTA PRESENTACIÓN</small></div>
 </div>
 <div class="qr-tools">
  <label for="pageUrl">Dirección pública de esta página (para crear un QR que otros puedan escanear)</label>
  <input id="pageUrl" type="url" placeholder="https://tu-pagina-publicada.com">
  <button id="makeQr">Generar QR</button>
  <p class="note">El QR solo será útil para otras personas cuando publiques la página en Internet e introduzcas aquí su dirección pública.</p>
 </div>
</div></section>
</main>
<footer class="wrap foot"><span>ECLIPSE DUNGEON · RPG DE FANTASÍA OSCURA</span><span>Proyecto de Renee Gabriel Fernandez Urtuvey</span></footer>
<script>
const qrImage=document.getElementById('qrImage');
const pageUrl=document.getElementById('pageUrl');
document.getElementById('makeQr').addEventListener('click',()=>{
 const value=pageUrl.value.trim();
 if(!value || !/^https?:\\/\\//i.test(value)){alert('Introduce una dirección pública válida que comience con https:// o http://');return;}
 qrImage.src='https://api.qrserver.com/v1/create-qr-code/?size=220x220&data='+encodeURIComponent(value);
});
if(location.protocol==='http:'||location.protocol==='https:'){
 pageUrl.value=location.href.split('#')[0];
 qrImage.src='https://api.qrserver.com/v1/create-qr-code/?size=220x220&data='+encodeURIComponent(pageUrl.value);
}
</script>
</body></html>
