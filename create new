<!DOCTYPE html>
<html lang="es">

<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Baúl de los Juegos Cafetería</title>

<link href="https://fonts.googleapis.com/css2?family=Cinzel+Decorative:wght@400;700&family=Montserrat:wght@300;400;600&family=Orbitron:wght@400;600;700&family=Playfair+Display:wght@600;700&family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    scroll-behavior:smooth;
}

body{
    font-family:'Poppins',sans-serif;
    background:#1C100B; /* Espresso Oscuro */
    color:#FDFBF7; /* Crema Suave */
    overflow-x:hidden;
}

/* FONDO */

.background-carousel{
    position:fixed;
    top:0;
    left:0;
    width:100%;
    height:100%;
    z-index:-2;
    background-size:cover;
    background-position:center;
    animation:carouselBg 25s infinite;
    filter:brightness(0.35);
}

.background-overlay{
    position:fixed;
    top:0;
    left:0;
    width:100%;
    height:100%;
    background:rgba(28, 16, 11, 0.85); /* Tono Espresso transparente */
    z-index:-1;
}

@keyframes carouselBg{

    0%{
        background-image:url('https://images.unsplash.com/photo-1495474472287-4d71bcdd2085?auto=format&fit=crop&w=1400&q=80');
    }

    25%{
        background-image:url('https://images.unsplash.com/photo-1521017432531-fbd92d768814?auto=format&fit=crop&w=1400&q=80');
    }

    50%{
        background-image:url('https://images.unsplash.com/photo-1511920170033-f8396924c348?auto=format&fit=crop&w=1400&q=80');
    }

    75%{
        background-image:url('https://images.unsplash.com/photo-1554118811-1e0d58224f24?auto=format&fit=crop&w=1400&q=80');
    }

    100%{
        background-image:url('https://images.unsplash.com/photo-1495474472287-4d71bcdd2085?auto=format&fit=crop&w=1400&q=80');
    }

}

/* SIDEBAR */

.sidebar{
    width:240px;
    height:100vh;
    position:fixed;
    background:rgba(28, 16, 11, 0.95);
    display:flex;
    flex-direction:column;
    z-index:1000;
    backdrop-filter:blur(10px);
    border-right:2px solid rgba(168, 124, 81, 0.4); /* Café Moka */
}

.logo{
    display:flex;
    justify-content:center;
    align-items:center;
    padding:20px 15px;
}

.logo-img{
    width:110px;
    height:110px;
    border-radius:50%;
    object-fit:cover;
    border:2px solid #A87C51;
    box-shadow:0 0 15px rgba(168, 124, 81, 0.5);
}

.sidebar a{
    padding:16px 22px;
    color:#FDFBF7;
    text-decoration:none;
    transition:0.3s;
    border-left:4px solid transparent;
    font-weight:500;
}

.sidebar a:hover{
    background:linear-gradient(90deg, #A87C51, #4A2E1B);
    color:#FDFBF7;
    border-left:4px solid #FDFBF7;
    padding-left:28px;
}

/* CONTENIDO */

.content{
    margin-left:240px;
    padding:25px;
    width:calc(100% - 240px);
}

.section{
    display:none;
    background:rgba(74, 46, 27, 0.85); /* Chocolate Intenso con opacidad */
    border-radius:20px;
    padding:35px;
    margin-bottom:25px;
    animation:fade 0.5s ease;
    border:1px solid rgba(168, 124, 81, 0.3);
    box-shadow:0 8px 25px rgba(0,0,0,0.5);
}

.active{
    display:block;
}

@keyframes fade{
    from{
        opacity:0;
        transform:translateY(20px);
    }

    to{
        opacity:1;
        transform:translateY(0);
    }
}

/* TITULOS */

.titulo{
    text-align:center;
    font-size:46px;
    margin-bottom:15px;
    font-family:'Cinzel Decorative',serif;
    background:linear-gradient(90deg, #FDFBF7, #A87C51);
    -webkit-background-clip:text;
    -webkit-text-fill-color:transparent;
}

.subtitulo{
    text-align:center;
    margin-bottom:25px;
    color:#E0D5C1; /* Crema cálido secundario */
}

/* CONTENEDOR DE REEL DE INSTAGRAM */

.instagram-container {
    display: flex;
    justify-content: center;
    width: 100%;
    margin: 20px 0;
}

.instagram-embed-wrapper {
    width: 100%;
    max-width: 450px;
    border-radius: 20px;
    overflow: hidden;
    border: 2px solid rgba(168, 124, 81, 0.3);
    background: #1C100B;
}

/* GRID */

.grid,
.menu-grid,
.games-grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
    margin-top:25px;
}

/* CARD */

.card{
    background:#2B1704; /* Café Granate Oscuro */
    border-radius:18px;
    overflow:hidden;
    box-shadow:0 6px 20px rgba(0,0,0,0.4);
    transition:0.4s;
    border:1px solid rgba(168, 124, 81, 0.3);
    display:flex;
    flex-direction:column;
    justify-content:space-between;
}

.card:hover{
    transform:translateY(-10px);
    border-color:#A87C51;
}

.card-img{
    width:100%;
    height:200px;
    object-fit:cover;
}

.card-content{
    padding:20px;
    text-align:center;
    color:#FDFBF7;
    flex-grow:1;
    display:flex;
    flex-direction:column;
    justify-content:space-between;
}

.card-desc{
    font-size:0.85rem;
    color:#E0D5C1;
    margin:8px 0;
}

.card-price{
    font-size:1.1rem;
    font-weight:bold;
    color:#A87C51;
    margin-top:5px;
}

/* BADGES PARA JUEGOS */

.game-tag{
    display:inline-block;
    padding:4px 10px;
    border-radius:12px;
    font-size:0.75rem;
    font-weight:bold;
    margin:3px;
    text-transform:uppercase;
}

.tag-facil{ background:#2e7d32; color:#fff; }
.tag-intermedio{ background:#ef6c00; color:#fff; }
.tag-avanzado{ background:#c62828; color:#fff; }

.game-info{
    font-size:0.85rem;
    color:#E0D5C1;
    margin:5px 0;
    display:flex;
    justify-content:space-around;
    background:rgba(0,0,0,0.2);
    padding:8px;
    border-radius:10px;
}

/* BOTONES */

button, .btn-action{
    border:none;
    padding:12px 20px;
    border-radius:10px;
    cursor:pointer;
    background:linear-gradient(90deg, #A87C51, #4A2E1B);
    color:#FDFBF7;
    font-weight:bold;
    transition:0.3s;
    margin-top:10px;
    display:inline-block;
    text-decoration:none;
}

button:hover, .btn-action:hover{
    background:linear-gradient(90deg, #4A2E1B, #A87C51);
    transform:scale(1.05);
}

.btn-danger{
    background:#c62828;
    margin-left: 10px;
}

.btn-danger:hover{
    background:#b71c1c;
}

.menu-buttons,
.filter-buttons{
    display:flex;
    justify-content:center;
    gap:10px;
    flex-wrap:wrap;
    margin-bottom:20px;
}

/* FORMULARIOS */

input,
select, textarea{
    width:100%;
    padding:14px;
    border-radius:10px;
    border:1px solid rgba(168, 124, 81, 0.4);
    margin-bottom:15px;
    background:#1C100B;
    color:#FDFBF7;
    font-family: inherit;
}

input::placeholder, textarea::placeholder{
    color:#A87C51;
}

/* TABLA */

table{
    width:100%;
    border-collapse:collapse;
    margin-top:20px;
}

th{
    background:#1C100B;
    color:#A87C51;
    padding:14px;
    border-bottom:2px solid #A87C51;
}

td{
    padding:14px;
    border-bottom:1px solid rgba(168, 124, 81, 0.2);
    text-align:center;
    background:#2B1704;
    color:#FDFBF7;
}

/* CARRITO CONTAINER */

#cart {
    background: #1C100B;
    padding: 20px;
    border-radius: 12px;
    border: 1px solid rgba(168, 124, 81, 0.4);
}

.cart-item {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 8px 0;
    border-bottom: 1px solid rgba(168, 124, 81, 0.2);
}

/* MAPAS / IFRAMES GENERALES */

iframe{
    border-radius:20px;
    width:100%;
}

/* BOTONES FLOTANTES DE REDES SOCIALES */

.social-float-container{
    position:fixed;
    bottom:20px;
    right:20px;
    display:flex;
    flex-direction:column;
    gap:15px;
    z-index:9999;
}

.tiktok-float{
    width:65px;
    height:65px;
    background:#000000;
    border-radius:50%;
    display:flex;
    justify-content:center;
    align-items:center;
    text-decoration:none;
    box-shadow: -2px 2px 0px #25F4EE, 2px -2px 0px #FE2C55, 0 5px 20px rgba(0,0,0,0.5);
    transition:transform 0.3s ease;
}

.tiktok-float:hover{
    transform:scale(1.1);
}

.instagram-float{
    width:65px;
    height:65px;
    background: linear-gradient(45deg, #f09433 0%, #e6683c 25%, #dc2743 50%, #cc2366 75%, #bc1888 100%);
    border-radius:50%;
    display:flex;
    justify-content:center;
    align-items:center;
    text-decoration:none;
    box-shadow: 0 5px 20px rgba(0,0,0,0.5);
    transition:transform 0.3s ease;
}

.instagram-float:hover{
    transform:scale(1.1);
}

/* RESPONSIVE */

@media(max-width:900px){

    .sidebar{
        width:100%;
        height:auto;
        position:relative;
        flex-direction:row;
        flex-wrap:wrap;
        justify-content:center;
    }

    .logo{
        width:100%;
    }

    .logo-img{
        width:80px;
        height:80px;
    }

    .content{
        margin-left:0;
        width:100%;
    }

    .titulo{
        font-size:34px;
    }

}

</style>

</head>

<body>

<div class="background-carousel"></div>
<div class="background-overlay"></div>

<div class="sidebar">

<div class="logo">
    <img src="https://scontent.cdninstagram.com/v/t51.2885-19/432604408_312182838182830_5541074101509791335_n.jpg?stp=dst-jpg_s150x150_tt6&_nc_cat=100&ccb=7-5&_nc_sid=f7ccc5&efg=eyJ2ZW5jb2RlX3RhZyI6InByb2ZpbGVfcGljLnd3dy4xMDgwLkMzIn0%3D&_nc_ohc=5_K-BcaXMkoQ7kNvwFL-ue0&_nc_oc=AdrUM4F-CBzfuKV3jeptqjjTYvzJX_24aY32XjYEX7Co4B3MSBnPqJ-qx8v4dzWQZm_wHdrkgfuBHa3cwGlxC_YQ&_nc_zt=24&_nc_ht=scontent.cdninstagram.com&_nc_ss=7b6a8&oh=00_AQM1HNO8jUHPdc30xj2nDHSlXbvKSvDiGKX8YsnMgQ-Q5w&oe=6AD21289" alt="Logo Baúl de los Juegos" class="logo-img">
</div>

<a href="#" onclick="showSection('inicio')">🏠 Inicio</a>
<a href="#" onclick="showSection('menu')">☕ Menú</a>
<a href="#" onclick="showSection('juegos')">🎲 Juegos</a>
<a href="#" onclick="showSection('reservas')">📌 Reservas</a>
<a href="#" onclick="showSection('nosotros')">🎮 Acerca De Nosotros</a>
<a href="#" onclick="showSection('contactos')">📞 Contactos</a>

</div>

<div class="content">

<div id="inicio" class="section active">

<h1 class="titulo">Baúl de los Juegos</h1>

<p class="subtitulo">
El mejor café y los mejores juegos de mesa en Oruro.
</p>

<!-- Reel de Instagram Integrado -->
<div class="instagram-container">
    <div class="instagram-embed-wrapper">
        <blockquote class="instagram-media" data-instgrm-permalink="https://www.instagram.com/elbauldelosjuegosor/reel/C565N1lM07_/?utm_source=ig_embed&amp;utm_campaign=loading" data-instgrm-version="14" style="background:#FFF; border:0; border-radius:3px; box-shadow:0 0 1px 0 rgba(0,0,0,0.5),0 1px 10px 0 rgba(0,0,0,0.15); margin: 1px; max-width:540px; min-width:326px; padding:0; width:99.375%; width:-webkit-calc(100% - 2px); width:calc(100% - 2px);"></blockquote>
    </div>
</div>

</div>

<div id="menu" class="section">

<h1 class="titulo">Nuestro Menú</h1>

<div class="menu-buttons">
<button onclick="showMenu('hotDrinks')">☕ Bebidas Calientes</button>
<button onclick="showMenu('coldDrinks')">🧊 Bebidas Frías</button>
<button onclick="showMenu('infusions')">🌿 Infusiones</button>
<button onclick="showMenu('desserts')">🍰 Postres y Dulces</button>
<button onclick="showMenu('food')">🥪 Sándwiches y Especiales</button>
<button onclick="showMenu('combos')">🎁 Combos</button>
</div>

<div class="menu-grid" id="menu-container"></div>

<br><br>

<h2>🛒 Tus Pedidos</h2>

<div id="cart">
<p>No hay productos agregados.</p>
</div>

</div>

<div id="juegos" class="section">

<h1 class="titulo">Catálogo de Juegos</h1>

<p class="subtitulo">
Explora todos los juegos de mesa disponibles en nuestro local según su nivel de dificultad.
</p>

<div class="filter-buttons">
    <button onclick="filterJuegos('todos')">🌟 Todos</button>
    <button onclick="filterJuegos('Fácil')">🟢 Fácil</button>
    <button onclick="filterJuegos('Intermedio')">🟡 Intermedio</button>
    <button onclick="filterJuegos('Avanzado')">🔴 Avanzado</button>
</div>

<div class="games-grid" id="juegos-container"></div>

</div>

<div id="reservas" class="section">

<h1 class="titulo">Reservas</h1>

<p class="subtitulo">
Reserva tu mesa o juego preferido. Nos comunicaremos directamente vía WhatsApp.
</p>

<form id="reservationForm">

<input type="text" id="nombre" placeholder="Nombre completo" required>

<input type="tel" id="telefono" placeholder="Número de teléfono de contacto" required>

<input type="text" id="juegoOpcion" placeholder="Juego o área que deseas reservar (Opcional)">

<input type="text" id="fechaHora" placeholder="Fecha y Hora de Reserva (ej: Hoy a las 18:00)" required>

<button type="submit">
📱 Reservar Vía WhatsApp
</button>

</form>

<table>

<thead>
<tr>
<th>Nombre</th>
<th>Teléfono</th>
<th>Reserva / Fecha</th>
</tr>
</thead>

<tbody id="reservationTable">

<tr>
<td colspan="3">
No hay reservas registradas en la sesión actual.
</td>
</tr>

</tbody>

</table>

</div>

<div id="nosotros" class="section">

<h1 class="titulo">Acerca de Nosotros</h1>

<p class="subtitulo">
Un lugar mágico donde el café y los juegos se unen.
</p>

<div class="card">

<div class="card-content">

<h2 style="margin-bottom:15px;">
☕ Ambiente Único
</h2>

<p style="
line-height:1.8;
color:#E0D5C1;
margin-bottom:25px;
">
En Baúl de los Juegos combinamos el mejor café,
postres deliciosos y juegos de mesa para crear
una experiencia inolvidable en Oruro.
</p>

<h2 style="margin-bottom:20px;">
🎥 Nuestro Reel Destacado
</h2>

<!-- Reel de Instagram Integrado también en la sección Nosotros -->
<div class="instagram-container">
    <div class="instagram-embed-wrapper">
        <blockquote class="instagram-media" data-instgrm-permalink="https://www.instagram.com/elbauldelosjuegosor/reel/C565N1lM07_/?utm_source=ig_embed&amp;utm_campaign=loading" data-instgrm-version="14" style="background:#FFF; border:0; border-radius:3px; box-shadow:0 0 1px 0 rgba(0,0,0,0.5),0 1px 10px 0 rgba(0,0,0,0.15); margin: 1px; max-width:540px; min-width:326px; padding:0; width:99.375%; width:-webkit-calc(100% - 2px); width:calc(100% - 2px);"></blockquote>
    </div>
</div>

</div>

</div>

<br><br>

<div class="card">

<img 
src="https://scontent.flpb1-1.fna.fbcdn.net/v/t39.30808-6/430495494_799086435573700_729834499236653182_n.png?stp=dst-png&cstp=mx2000x1000&ctp=s2000x1000&_nc_cat=108&_nc_map=urlgen_bucketless&ccb=1-7&_nc_sid=cc71e4&_nc_ohc=qhMFlkLwRgAQ7kNvwHyurv7&_nc_oc=Adqa-Mo2N30J1KHOShLjXeuvP6MGrHoI2WoP0lUbjhonosnxaK4UMDxkBgFMH2W8-iitGRwHORKavAlRszeNjW36&_nc_zt=23&_nc_ht=scontent.flpb1-1.fna&_nc_gid=g0xFO3S9KpnYt3d-y1sFzA&_nc_ss=7b2a8&oh=00_AQNYx8bGgcBfA_x_y8kVry5rFLxw-8UtKq976T0E6Shi7g&oe=6AD2017A"
alt="Cafetería"
style="
width:100%;
height:350px;
object-fit:cover;
">

<div class="card-content">

<h2 style="margin-bottom:20px;">
📍 Oruro - Bolivia
</h2>

<p style="
margin-bottom:25px;
color:#E0D5C1;
line-height:1.7;
">
Visítanos y disfruta de un espacio acogedor,
ideal para compartir con amigos y familia.
</p>

<iframe
src="https://www.google.com/maps?q=Oruro+Bolivia&output=embed"
width="100%"
height="400"
style="border:0; border-radius:20px; margin-bottom:25px;"
loading="lazy">
</iframe>

<a 
href="https://maps.app.goo.gl/wcRC8qkFUM7PDpkT6?g_st=aw"
target="_blank"
style="text-decoration:none;">

<button>
📍 Ver ubicación exacta
</button>

</a>

</div>

</div>

</div>

<div id="contactos" class="section">

<h1 class="titulo">Contáctanos</h1>

<p class="subtitulo">
Estamos listos para atenderte ☕
</p>

<div class="grid">

<div class="card">

<div class="card-content">

<h2 style="margin-bottom:15px;">
📧 Correo
</h2>

<p style="color:#E0D5C1;">
acodavfito@gmail.com
</p>

<button onclick="
window.location.href=
'mailto:acodavfito@gmail.com'
">
Enviar correo
</button>

</div>

</div>

<div class="card">

<div class="card-content">

<h2 style="margin-bottom:15px;">
📞 Teléfono
</h2>

<p style="color:#E0D5C1;">
+591 76142380
</p>

<button onclick="
window.open(
'https://wa.me/59176142380',
'_blank'
)
">
WhatsApp Directo
</button>

</div>

</div>

<div class="card">

<div class="card-content">

<h2 style="margin-bottom:15px;">
🕒 Horarios
</h2>

<p style="color:#E0D5C1; line-height:1.8;">
Lunes a Domingo<br>
14:00 - 23:00
</p>

</div>

</div>

</div>

</div>

<footer style="
background:rgba(28,16,11,0.95);
color:#FDFBF7;
text-align:center;
padding:18px;
border-radius:15px;
margin-top:20px;
border:1px solid rgba(168,124,81,0.3);
">
© 2026 Baúl de los Juegos Cafetería
</footer>

</div>

<div class="social-float-container">

  <a
  href="https://www.instagram.com/elbauldelosjuegosor?igsh=MW5rbWF0cWx4aXFuYQ=="
  class="instagram-float"
  target="_blank"
  title="Síguenos en Instagram">
    <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" viewBox="0 0 24 24" fill="none" stroke="#FFFFFF" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
      <rect x="2" y="2" width="20" height="20" rx="5" ry="5"></rect>
      <path d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37z"></path>
      <line x1="17.5" y1="6.5" x2="17.51" y2="6.5"></line>
    </svg>
  </a>

  <a
  href="https://www.tiktok.com/@baul.de.los.juegos?_r=1&_t=ZS-98pdduwrg97"
  class="tiktok-float"
  target="_blank"
  title="Síguenos en TikTok">
    <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
      <path d="M9 12a4 4 0 1 0 4 4V4a5 5 0 0 0 5 5" fill="none" stroke="#FFFFFF" stroke-width="2.5"/>
    </svg>
  </a>

</div>

<!-- Script oficial de Instagram para cargar y renderizar los embeds de reels -->
<script async src="//www.instagram.com/embed.js"></script>

<script>

const WHATSAPP_NUMERO = "59176142380";

/* SECCIONES */

function showSection(id){

let sections = document.querySelectorAll('.section');
let links = document.querySelectorAll('.sidebar a');

sections.forEach(sec=>{
    sec.classList.remove('active');
});

document.getElementById(id).classList.add('active');

links.forEach(link=>{
    link.style.display = 'block';
});

links.forEach(link=>{
    let onclickValue = link.getAttribute('onclick');
    if(onclickValue.includes(id)){
        link.style.display = 'none';
    }
});

}

/* MENU COMPLETO EXTRAÍDO DEL PDF */

const menu={

hotDrinks: [
  { name: "Café Básico", desc: "1 onza de café y agua caliente", price: "Bs. 4,5", img: "https://images.unsplash.com/photo-1511920170033-f8396924c348?auto=format&fit=crop&w=900&q=80" },
  { name: "Americano", desc: "1 onza de café y agua", price: "Bs. 8", img: "https://images.unsplash.com/photo-1514432324607-a09d9b4aefdd?auto=format&fit=crop&w=900&q=80" },
  { name: "El Jefe (Expreso simple)", desc: "Café EXPRESO simple", price: "Bs. 6", img: "https://images.unsplash.com/photo-1510591509098-f4fdc6d0ff04?auto=format&fit=crop&w=900&q=80" },
  { name: "El Capo (Expreso doble)", desc: "Café EXPRESO doble", price: "Bs. 7", img: "https://images.unsplash.com/photo-1510591509098-f4fdc6d0ff04?auto=format&fit=crop&w=900&q=80" },
  { name: "Café Bomba", desc: "1 onza de café y barra de chocolate", price: "Bs. 7,5", img: "https://images.unsplash.com/photo-1541167760496-1628856ab772?auto=format&fit=crop&w=900&q=80" },
  { name: "Pandemonium", desc: "1 onza de café y leche caliente", price: "Bs. 9", img: "https://images.unsplash.com/photo-1534778101976-62847782c213?auto=format&fit=crop&w=900&q=80" },
  { name: "Príncipe Mestizo", desc: "1 onza de sultana, 1 onza de café y agua caliente", price: "Bs. 5,5", img: "https://images.unsplash.com/photo-1517256064527-09c73fc73e38?auto=format&fit=crop&w=900&q=80" },
  { name: "Rigor Mortis", desc: "1 onza de té, canela y clavo de olor", price: "Bs. 4,5", img: "https://images.unsplash.com/photo-1576092768241-dec231879fc3?auto=format&fit=crop&w=900&q=80" },
  { name: "Reina de Corazones", desc: "1 onza de té, canela, clavo de olor y k'asi rosa", price: "Bs. 5", img: "https://images.unsplash.com/photo-1576092768241-dec231879fc3?auto=format&fit=crop&w=900&q=80" },
  { name: "Limonagrio", desc: "1 onza de té, canela, clavo de olor, limón", price: "Bs. 6", img: "https://images.unsplash.com/photo-1556679343-c7306c1976bc?auto=format&fit=crop&w=900&q=80" },
  { name: "Te Quiero Más", desc: "1 onza de té, canela, clavo de olor, leche y vainilla", price: "Bs. 9", img: "https://images.unsplash.com/photo-1576092768241-dec231879fc3?auto=format&fit=crop&w=900&q=80" },
  { name: "Perlita", desc: "Leche implosiva", price: "Bs. 8", img: "https://images.unsplash.com/photo-1550583724-b2692b85b150?auto=format&fit=crop&w=900&q=80" },
  { name: "Chocón", desc: "1 barra de chocolate y agua caliente", price: "Bs. 6", img: "https://images.unsplash.com/photo-1542990253-0d0f5be5f0ed?auto=format&fit=crop&w=900&q=80" },
  { name: "Leche Bomba", desc: "1 barra de chocolate y leche", price: "Bs. 11", img: "https://images.unsplash.com/photo-1542990253-0d0f5be5f0ed?auto=format&fit=crop&w=900&q=80" },
  { name: "Matchita", desc: "Té matcha caliente", price: "Bs. 10", img: "https://images.unsplash.com/photo-1536256263959-770b48d82b0a?auto=format&fit=crop&w=900&q=80" },
  { name: "Sultanita", desc: "1 onza de sultana y agua caliente", price: "Bs. 4,5", img: "https://images.unsplash.com/photo-1517256064527-09c73fc73e38?auto=format&fit=crop&w=900&q=80" },
  { name: "Sultán", desc: "1 onza de sultana y leche caliente", price: "Bs. 9", img: "https://images.unsplash.com/photo-1517256064527-09c73fc73e38?auto=format&fit=crop&w=900&q=80" },
  { name: "Cálico", desc: "1 onza de café, barra de chocolate y leche caliente", price: "Bs. 12", img: "https://images.unsplash.com/photo-1541167760496-1628856ab772?auto=format&fit=crop&w=900&q=80" },
  { name: "Caperucita Café", desc: "1 onza de café y cocoa", price: "Bs. 7,5", img: "https://images.unsplash.com/photo-1534778101976-62847782c213?auto=format&fit=crop&w=900&q=80" },
  { name: "Capuchino", desc: "1 parte de café, leche espumosa", price: "Bs. 8", img: "https://images.unsplash.com/photo-1495474472287-4d71bcdd2085?auto=format&fit=crop&w=900&q=80" },
  { name: "Mocachino", desc: "1 parte de café, cocoa y leche espumosa", price: "Bs. 10.5", img: "https://images.unsplash.com/photo-1534778101976-62847782c213?auto=format&fit=crop&w=900&q=80" },
  { name: "Cocoa Latte", desc: "1 parte de cocoa y leche espumosa", price: "Bs. 9", img: "https://images.unsplash.com/photo-1542990253-0d0f5be5f0ed?auto=format&fit=crop&w=900&q=80" },
  { name: "Jhon Coffee", desc: "Café expreso, limón y agua espumosa", price: "Bs. 7", img: "https://images.unsplash.com/photo-1517256064527-09c73fc73e38?auto=format&fit=crop&w=900&q=80" },
  { name: "Divina", desc: "Café expreso, leche y vainilla", price: "Bs. 8", img: "https://images.unsplash.com/photo-1534778101976-62847782c213?auto=format&fit=crop&w=900&q=80" }
],

coldDrinks: [
  { name: "Té Batido", desc: "1 onza de té, leche fría, canela y clavo de olor", price: "Bs. 7", img: "https://images.unsplash.com/photo-1556679343-c7306c1976bc?auto=format&fit=crop&w=900&q=80" },
  { name: "Café Batido", desc: "1 onza de café, leche fría, vainilla", price: "Bs. 7", img: "https://images.unsplash.com/photo-1517701604599-bb29b565090c?auto=format&fit=crop&w=900&q=80" },
  { name: "Sultana Batida", desc: "1 onza de sultana, leche fría", price: "Bs. 7", img: "https://images.unsplash.com/photo-1517701604599-bb29b565090c?auto=format&fit=crop&w=900&q=80" },
  { name: "Chocolate Batido", desc: "Cocoa y leche fría", price: "Bs. 7", img: "https://images.unsplash.com/photo-1542990253-0d0f5be5f0ed?auto=format&fit=crop&w=900&q=80" },
  { name: "Café Frío", desc: "1 onza de café, agua y hielo", price: "Bs. 4.5", img: "https://images.unsplash.com/photo-1517701604599-bb29b565090c?auto=format&fit=crop&w=900&q=80" },
  { name: "Té Helado", desc: "1 onza de té, canela, clavo de olor, agua, limón y hielo", price: "Bs. 5", img: "https://images.unsplash.com/photo-1556679343-c7306c1976bc?auto=format&fit=crop&w=900&q=80" },
  { name: "Sulfrán", desc: "1 onza de sultana y agua fría", price: "Bs. 4", img: "https://images.unsplash.com/photo-1517256064527-09c73fc73e38?auto=format&fit=crop&w=900&q=80" },
  { name: "Hielo Extra", desc: "2 cubos de hielo", price: "Bs. 1", img: "https://images.unsplash.com/photo-1518110168401-f282023d872e?auto=format&fit=crop&w=900&q=80" }
],

infusions: [
  { name: "Jengibre", desc: "1 onza de té, canela, clavo de olor, miel, limón y jengibre", price: "Bs. 8", img: "https://images.unsplash.com/photo-1576092768241-dec231879fc3?auto=format&fit=crop&w=900&q=80" },
  { name: "Poción Verde", desc: "Infusión de cedrón", price: "Bs. 4", img: "https://images.unsplash.com/photo-1576092768241-dec231879fc3?auto=format&fit=crop&w=900&q=80" },
  { name: "Poción Roja", desc: "Infusión de airampu", price: "Bs. 4", img: "https://images.unsplash.com/photo-1576092768241-dec231879fc3?auto=format&fit=crop&w=900&q=80" },
  { name: "Poción de Amor", desc: "Infusión de k'asi rosa", price: "Bs. 4", img: "https://images.unsplash.com/photo-1576092768241-dec231879fc3?auto=format&fit=crop&w=900&q=80" },
  { name: "Poción Amarilla", desc: "Infusión de wira wira", price: "Bs. 4", img: "https://images.unsplash.com/photo-1576092768241-dec231879fc3?auto=format&fit=crop&w=900&q=80" },
  { name: "Poción Simple", desc: "Infusión de manzanilla", price: "Bs. 4", img: "https://images.unsplash.com/photo-1576092768241-dec231879fc3?auto=format&fit=crop&w=900&q=80" },
  { name: "Poción Feliz", desc: "Infusión de anís", price: "Bs. 4", img: "https://images.unsplash.com/photo-1576092768241-dec231879fc3?auto=format&fit=crop&w=900&q=80" }
],

desserts: [
  { name: "Panques CF", desc: "Porción de panques", price: "Bs. 5", img: "https://images.unsplash.com/photo-1565299585323-38d6b0865b47?auto=format&fit=crop&w=900&q=80" },
  { name: "Panque Cumpleañero", desc: "Porción de panques y crema", price: "Bs. 8", img: "https://images.unsplash.com/photo-1565299585323-38d6b0865b47?auto=format&fit=crop&w=900&q=80" },
  { name: "Wafles", desc: "Wafles de vainilla con jalea y fruta", price: "Bs. 8.5", img: "https://images.unsplash.com/photo-1562376552-0d160a2f238d?auto=format&fit=crop&w=900&q=80" },
  { name: "Don Waffle", desc: "Wafles con jalea, fruta y helado", price: "Bs. 12", img: "https://images.unsplash.com/photo-1562376552-0d160a2f238d?auto=format&fit=crop&w=900&q=80" },
  { name: "Affogato", desc: "Café con helado de vainilla y jalea", price: "Bs. 8", img: "https://images.unsplash.com/photo-1592663527359-cf6642f54cff?auto=format&fit=crop&w=900&q=80" },
  { name: "Heladín", desc: "Helado con jalea", price: "Bs. 5", img: "https://images.unsplash.com/photo-1563805042-7684c019e1cb?auto=format&fit=crop&w=900&q=80" },
  { name: "Heladón", desc: "Helado con crema y chispas", price: "Bs. 8", img: "https://images.unsplash.com/photo-1563805042-7684c019e1cb?auto=format&fit=crop&w=900&q=80" },
  { name: "Bola Extra de Helado", desc: "Añade una bola extra de helado", price: "Bs. 4", img: "https://images.unsplash.com/photo-1563805042-7684c019e1cb?auto=format&fit=crop&w=900&q=80" }
],

food: [
  { name: "Sándwich Cero", desc: "Jamón, queso, kétchup y pan", price: "Bs. 5,5", img: "https://images.unsplash.com/photo-1528735602780-2552fd46c7af?auto=format&fit=crop&w=900&q=80" },
  { name: "Sándwich Uno", desc: "Pan molde, jamón, queso criollo, kétchup, orégano", price: "Bs. 5,5", img: "https://images.unsplash.com/photo-1528735602780-2552fd46c7af?auto=format&fit=crop&w=900&q=80" },
  { name: "Sándwich Dos", desc: "Pan molde, queso mozarela, queso criollo, kétchup, orégano", price: "Bs. 6,5", img: "https://images.unsplash.com/photo-1528735602780-2552fd46c7af?auto=format&fit=crop&w=900&q=80" },
  { name: "Sándwich Chicloso", desc: "Pan molde, queso mozarela, kétchup y orégano", price: "Bs. 5", img: "https://images.unsplash.com/photo-1528735602780-2552fd46c7af?auto=format&fit=crop&w=900&q=80" },
  { name: "La Salchichita", desc: "Salchicha, pan de hot dog y aderezos", price: "Bs. 6.5", img: "https://images.unsplash.com/photo-1619740455993-9e612b1af08a?auto=format&fit=crop&w=900&q=80" },
  { name: "Pavita", desc: "Pollo, mayonesa, repollo, pimentón", price: "Bs. 5.5", img: "https://images.unsplash.com/photo-1528735602780-2552fd46c7af?auto=format&fit=crop&w=900&q=80" },
  { name: "Sandwich H", desc: "Pan con huevo", price: "Bs. 5", img: "https://images.unsplash.com/photo-1525351484163-7529414344d8?auto=format&fit=crop&w=900&q=80" },
  { name: "Pizza", desc: "Pizza con queso mozarela y salsa de tomate (Jamón o Salchicha)", price: "Bs. 26", img: "https://images.unsplash.com/photo-1513104890138-7c749659a591?auto=format&fit=crop&w=900&q=80" },
  { name: "Tarwis", desc: "Palitos de tarwi con salsa", price: "Bs. 7", img: "https://images.unsplash.com/photo-1541592106381-b31e9677c0e5?auto=format&fit=crop&w=900&q=80" },
  { name: "Señor Huevo", desc: "Sandwich de huevo con ensalada y papas", price: "Bs. 9", img: "https://images.unsplash.com/photo-1525351484163-7529414344d8?auto=format&fit=crop&w=900&q=80" },
  { name: "Apanadón", desc: "Sandwich de apanado con jamón, huevo, queso, lechuga, tomate y papas", price: "Bs. 14", img: "https://images.unsplash.com/photo-1528735602780-2552fd46c7af?auto=format&fit=crop&w=900&q=80" },
  { name: "Huminta", desc: "Pastelito de choclo con su quesito", price: "Bs. 10", img: "https://images.unsplash.com/photo-1565299585323-38d6b0865b47?auto=format&fit=crop&w=900&q=80" },
  { name: "Napolita Advanced Level", desc: "Milanesa con jamón, quesito, lechuga, tomate y papas", price: "Bs. 14", img: "https://images.unsplash.com/photo-1544025162-d76694265947?auto=format&fit=crop&w=900&q=80" }
],

combos: [
  { name: "Combo 1", desc: "Café básico, té rigor mortis o sultanita con sándwich uno o pavita", price: "Bs. 9", img: "https://images.unsplash.com/photo-1521017432531-fbd92d768814?auto=format&fit=crop&w=900&q=80" },
  { name: "Combo 2", desc: "Un jugo de agua con sándwich uno o pavita", price: "Bs. 8.5", img: "https://images.unsplash.com/photo-1521017432531-fbd92d768814?auto=format&fit=crop&w=900&q=80" },
  { name: "Combo 3", desc: "Café básico, té rigor mortis o sultanita y panque CF", price: "Bs. 8.5", img: "https://images.unsplash.com/photo-1521017432531-fbd92d768814?auto=format&fit=crop&w=900&q=80" },
  { name: "Combo Cumpleañero", desc: "Jugo con leche a tu elección con helado, crema y un sándwich a tu elección", price: "Bs. 19", img: "https://images.unsplash.com/photo-1513151233558-d860c5398176?auto=format&fit=crop&w=900&q=80" }
]

};

/* JUEGOS DE MESA EXTRAÍDOS DEL PDF */

const listaJuegos = [
  { name: "Blast Off!", players: "2-4 Jugadores", time: "20 min", diff: "Fácil", img: "https://images.unsplash.com/photo-1610890716171-6b1bb98ffd09?auto=format&fit=crop&w=900&q=80" },
  { name: "Gatitos en Licuadora", players: "2-4 Jugadores", time: "20-40 min", diff: "Fácil", img: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSRzxI-EQCuAA1ycXGy9sxbvpKHHh6aExVb5hj2bUjN_A&s=10" },
  { name: "¿Alcachofas?, ¡No, Gracias!", players: "2-4 Jugadores", time: "20 min", diff: "Intermedio", img: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcToxjletZJOCLaRwjx4tJOofsUKQD10bk6cD3zuI_X6oQ&s=10" },
  { name: "¡Extinción!", players: "2-6 Jugadores", time: "15 min", diff: "Fácil", img: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTuc8sJaDWBWGiVZCMhpaxmcEUljfBwTRINdFtcz_0ykg&s=10" },
  { name: "Spicy", players: "2-6 Jugadores", time: "15 min", diff: "Intermedio", img: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTwLUxJqGB4rRQIHSThnAhgjApksKSLQhd5NhOqq-P7_A&s=10" },
  { name: "Polilla Tramposa", players: "3-5 Jugadores", time: "15-25 min", diff: "Fácil", img: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRsqHPpqDlXW26Cvdx1PP25PpeakyzQDllbi9Toq0pE3g&s=10" },
  { name: "Bar Bestial", players: "2-4 Jugadores", time: "20 min", diff: "Intermedio", img: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTB1c6KFoiDkNdTxvFY_vdDHpWwQnQacDG0E-fkyzB-MA&s=10" },
  { name: "Set", players: "1+ Jugadores", time: "20 min", diff: "Intermedio", img: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRQMBwzy7o66XXOemaLgCOAq5qaPR9YnQIwtKA3KP87Tw&s=10" },
  { name: "Catan", players: "2-4, 6 Jugadores", time: "75 min", diff: "Intermedio", img: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTfuj5g6fpHEF1Urf4TjHzhf222tHjEjvlshZ6hro2Srw&s=10" },
  { name: "King of Tokyo", players: "2-6 Jugadores", time: "30 min", diff: "Intermedio", img: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRL-WzbJFjAq8XGNm_F7aMz64ATGQUJrukFxMEYEv05EQ&s=10" },
  { name: "Azul", players: "2-4 Jugadores", time: "30-45 min", diff: "Intermedio", img: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSoTt9_EQTGHbupz_28iEBKY13BX16CNz-l_sqGAGOPJQ&s=10" },
  { name: "Azul, Pabellón de Verano", players: "2-4 Jugadores", time: "30-45 min", diff: "Intermedio", img: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ_rqeQD46kLUW0Ol9Gj8eRpAEAjvACGgYe_yyvCdtmkg&s=10" },
  { name: "Bounce Off", players: "2-4 Jugadores", time: "10 min", diff: "Fácil", img: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT98iRNZfp5LXwHsTyIHGM-v1uTQM6Iu3Us2cdBpLBgCg&s=10" },
  { name: "Bounce Off Rock 'N' Rollz!", players: "2-4 Jugadores", time: "10 min", diff: "Intermedio", img: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQR9QS5UDWsG4q7canQ62GZ10hkIjT70C_hkTuSl49-Vw&s" },
  { name: "Khora", players: "2-4 Jugadores", time: "75 min", diff: "Avanzado", img: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTCrl0AUnYLF7Lh4DOD53olrHp-X80G4bB_ZVJ9kv0uYQ&s=10" },
  { name: "Agrícola", players: "2-4 Jugadores", time: "90 min", diff: "Avanzado", img: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTCR5UKqmFYNYeIkM4UpYrJJ88xuE_TErWNWw8f7SZ_nw&s=10" },
  { name: "¡Sí, Señor Oscuro!", players: "3+ Jugadores", time: "20 min", diff: "Intermedio", img: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRoTFfXQmcXuqCxgYKfWVt7EYReu14KV_8R2ugYJZT7RA&s" },
  { name: "Ciudadelas", players: "2-8 Jugadores", time: "40-120 min", diff: "Intermedio", img: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQgiuOAYpfFjaSD7KaGtC4CC0WBvZ9vC304CGITC60s5Q&s=10" },
  { name: "Hombres Lobo de Castronegro", players: "8-26 Jugadores", time: "10-20 min", diff: "Fácil", img: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTmLWw1nmHBT31QlXrrr4GPgUXxGbVtzyM_d7UebjLIMw&s=10" },
  { name: "Port Royal", players: "2-5 Jugadores", time: "10-40 min", diff: "Intermedio", img: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTFYxnUDMXunJeMa4mmdcsK52CJXooEDGHVF87TKmeQEQ&s=10" },
  { name: "Gatitos Explosivos", players: "2-8 Jugadores", time: "10-20 min", diff: "Intermedio", img: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTldL05K1Zb5OzjItAVPr0KKBVYM9CbXvCGhds99KfZYQ&s=10" },
  { name: "Virus! 1, 2 / Halloween", players: "2-6 Jugadores", time: "30 min", diff: "Intermedio", img: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQfxmh9EzJyy7mJdWDXaD2f8K9RsBQYR40mq3zCn17jvQ&s=10" },
  { name: "Dixit", players: "3-6 Jugadores", time: "20-40 min", diff: "Fácil", img: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSuZpWK-hpWSYfMKY6roYmJZkgdyS-KXzlUccrAB9tseA&s=10" },
  { name: "Sushi Go!", players: "2-8 Jugadores", time: "20 min", diff: "Intermedio", img: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS3kbKKuN0rF4gEGO0kjDjAb6PtpmVxmm_5J2tcmpLYyQ&s=10" },
  { name: "Fútbol de Mesa", players: "2 Jugadores", time: "15 min", diff: "Fácil", img: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQuWsZkB64TGR1j4bhiRUsuSbtBHfCLaCkrbdWLJWfCIw&s=10" },
  { name: "¡Basta!", players: "2+ Jugadores", time: ">5 min", diff: "Fácil", img: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQJ-EoardVMOYhczK4xAczIVLHvXXU_xk-IfBLAhY9UAw&s=10" },
  { name: "Connect 4", players: "2 Jugadores", time: "15 min", diff: "Fácil", img: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTCFSQMi3BqKNBD8lG0_YroUNbLCJ_WnHFfYA5TWmPAkw&s=10" },
  { name: "Othello", players: "2 Jugadores", time: "20 min", diff: "Fácil", img: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTfpSsss-fCDAoe2FmnrkBq4p8rtBOkHZpj7Gn13WubEg&s=10" },
  { name: "Ajedrez / Damas / Backgammon", players: "2 Jugadores", time: ">20 min", diff: "Intermedio", img: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRi3b1z5Ir5yt9UVvQuOjOhNgJkH9_j1iCcwf6HFwEgGg&s=10" },
  { name: "Monopolio", players: "2-8 Jugadores", time: ">60 min", diff: "Fácil", img: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQB4UO8XuGhdeAmEB3PeB__nbVL4exBiT4os0W55Nu7-g&s=10" },
  { name: "Secret Hitler", players: "5-10 Jugadores", time: "30 min", diff: "Intermedio", img: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQWvYNHZJlojw92V14yQGfUrt-O7xxyNy_ILCrY4Ckjxg&s=10" },
  { name: "Munchkin", players: "3-6 Jugadores", time: "60 min", diff: "Intermedio", img: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTxoSA5S7HmcgcKgNCiLd6R_-0-DtPNeuGVQ9mjpMO5wA&s=10" },
  { name: "UNO / UNO Flip! / DOS", players: "2-10 Jugadores", time: "15 min", diff: "Fácil", img: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRKGfEC2gPimJNKVxXWDY0HDs-WW1SFyVfW9qS6OMWtXA&s=10" },
  { name: "Unicornios Inestables", players: "2-8 Jugadores", time: "30-45 min", diff: "Intermedio", img: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQGuZN3YgMFvD-GqIIw4spoTBcND40RKevVJCWPVrJelg&s=10" },
  { name: "Here to Slay", players: "2-6 Jugadores", time: "20-40 min", diff: "Intermedio", img: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQCk2b6MjvvnqvrkqKlWIptQL0P-Yoj3WazFkK90FYXFw&s=10" },
  { name: "Magic: The Gathering", players: "2-3 Jugadores", time: "20 min", diff: "Intermedio", img: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR3qrqMdjyyXngPZxXJfHc8DZAKACSJdChuAPxDJmiG0A&s=10" },
  { name: "Jenga / Jenga Tetris", players: ">2 Jugadores", time: "15-20 min", diff: "Fácil", img: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQLng0NFkzv-NCb17HAB3i8pIx7i0zDFsZdWwO245shUg&s" },
  { name: "Pandemic", players: "2-4 Jugadores", time: ">60 min", diff: "Avanzado", img: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQyAdSVAYvDxlLkFF0KahOjNn6MvPJoR-1XmEkt0CrduA&s=10" },
  { name: "Zombicide", players: "1-6 Jugadores", time: ">60 min", diff: "Avanzado", img: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRpddsu9oyGj9-Zb5DOAOmiauhZA1H4dptCPkGlP_N8Aw&s=10" },
  { name: "7 Wonders", players: "2-7 Jugadores", time: ">60 min", diff: "Avanzado", img: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ8fN3AM3LDs3egDUgFU1ntcn7Bye6-X0mITKJodJReiA&s=10" },
];

function filterJuegos(dificultad){
  const container = document.getElementById('juegos-container');
  container.innerHTML = "";

  const juegosFiltrados = dificultad === 'todos' 
    ? listaJuegos 
    : listaJuegos.filter(j => j.diff.toLowerCase() === dificultad.toLowerCase());

  juegosFiltrados.forEach(juego => {
    let tagClass = "tag-facil";
    if(juego.diff === "Intermedio") tagClass = "tag-intermedio";
    if(juego.diff === "Avanzado") tagClass = "tag-avanzado";

    container.innerHTML += `
      <div class="card">
        <img src="${juego.img}" class="card-img" alt="${juego.name}">
        <div class="card-content">
          <div>
            <h3>${juego.name}</h3>
            <span class="game-tag ${tagClass}">${juego.diff}</span>
            <div class="game-info">
              <span>👥 ${juego.players}</span>
              <span>⏱️ ${juego.time}</span>
            </div>
          </div>
          <button onclick="reservarJuegoDirecto('${juego.name}')">📌 Reservar para jugar</button>
        </div>
      </div>
    `;
  });
}

function reservarJuegoDirecto(nombreJuego){
  showSection('reservas');
  document.getElementById('juegoOpcion').value = nombreJuego;
}

function showMenu(type){
const container=document.getElementById('menu-container');
container.innerHTML="";

if(!menu[type]) return;

menu[type].forEach(item=>{
container.innerHTML+=`
<div class="card">
<img src="${item.img}" style="width:100%;height:180px;object-fit:cover;">
<div class="card-content">
<div>
    <h3>${item.name}</h3>
    <p class="card-desc">${item.desc}</p>
    <p class="card-price">${item.price}</p>
</div>
<button onclick="addToCart('${item.name}', '${item.price}')">
🛒 Agregar
</button>
</div>
</div>
`;
});
}

/* CARRITO */

let cartItems=[];

function addToCart(name, price){
cartItems.push({name, price});
renderCart();
}

function removeFromCart(index){
cartItems.splice(index, 1);
renderCart();
}

function renderCart(){
let cart=document.getElementById("cart");

if(cartItems.length===0){
cart.innerHTML="<p>No hay productos agregados.</p>";
return;
}

cart.innerHTML="";

cartItems.forEach((item,index)=>{
cart.innerHTML+=`
<div class="cart-item">
  <span>${index + 1}. <strong>${item.name}</strong> - ${item.price}</span>
  <button class="btn-danger" onclick="removeFromCart(${index})">❌ Quitar</button>
</div>
`;
});

cart.innerHTML += `
<br>
<button onclick="enviarPedidoWhatsApp()">📲 Enviar Pedido por WhatsApp</button>
`;
}

function enviarPedidoWhatsApp(){
if(cartItems.length === 0) return;

let text = "☕ *NUEVO PEDIDO DE MENÚ - Baúl de los Juegos*\n\n";
cartItems.forEach((item, index) => {
    text += `${index + 1}. ${item.name} (${item.price})\n`;
});
text += "\n¡Hola! Quisiera realizar este pedido para mi visita.";

const url = `https://wa.me/${WHATSAPP_NUMERO}?text=${encodeURIComponent(text)}`;
window.open(url, '_blank');
}

/* RESERVAS */

let reservas=[];

document.getElementById("reservationForm")
.addEventListener("submit",function(e){

e.preventDefault();

const nombre = document.getElementById("nombre").value;
const telefono = document.getElementById("telefono").value;
const juego = document.getElementById("juegoOpcion").value || "Mesa general";
const fechaHora = document.getElementById("fechaHora").value;

const reserva={ nombre, telefono, juego, fechaHora };
reservas.push(reserva);
renderReservas();

let mensaje = `🎲 *NUEVA RESERVA - Baúl de los Juegos*\n\n`;
mensaje += `👤 *Nombre:* ${nombre}\n`;
mensaje += `📞 *Teléfono:* ${telefono}\n`;
mensaje += `🎯 *Juego / Mesa:* ${juego}\n`;
mensaje += `📅 *Fecha y Hora:* ${fechaHora}\n\n`;
mensaje += `¡Hola! Quisiera confirmar esta reserva.`;

const url = `https://wa.me/${WHATSAPP_NUMERO}?text=${encodeURIComponent(mensaje)}`;

this.reset();
window.open(url, '_blank');
});

function renderReservas(){
const table=document.getElementById("reservationTable");
table.innerHTML="";

reservas.forEach(reserva=>{
table.innerHTML+=`
<tr>
<td>${reserva.nombre}</td>
<td>${reserva.telefono}</td>
<td>${reserva.juego} (${reserva.fechaHora})</td>
</tr>
`;
});
}

/* INICIALIZACIÓN */
showMenu('hotDrinks');
filterJuegos('todos');
showSection('inicio');

</script>

</body>
</html>
