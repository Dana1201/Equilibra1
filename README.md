
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Equilibra | Bienestar emocional</title>
<style>

/* FONDO GENERAL CON IMAGEN SUAVE */
body{
font-family:Arial, Helvetica, sans-serif;
margin:0;
color:#333;
background-image:linear-gradient(rgba(255,255,255,0.85), rgba(255,255,255,0.85)), url("https://images.unsplash.com/photo-1500530855697-b586d89ba3ee");
background-size:cover;
background-attachment:fixed;
background-position:center;
}

/* HERO */
header{
background-image:linear-gradient(rgba(0,0,0,0.45),rgba(0,0,0,0.45)), url("https://images.unsplash.com/photo-1506126613408-eca07ce68773");
background-size:cover;
background-position:center;
color:white;
padding:90px 20px;
text-align:center
}

header h1{
font-size:46px;
margin-bottom:10px
}

header p{
font-size:18px;
max-width:650px;
margin:auto
}

.btn{
display:inline-block;
margin-top:25px;
background:white;
color:#333;
padding:12px 25px;
text-decoration:none;
border-radius:6px;
font-weight:bold
}

section{
padding:60px 20px;
max-width:1000px;
margin:auto
}

section h2{
text-align:center;
margin-bottom:25px
}

section p{
text-align:center;
max-width:700px;
margin:auto;
margin-bottom:30px
}

.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:20px
}

.card{
background:white;
padding:22px;
border-radius:10px;
box-shadow:0 2px 10px rgba(0,0,0,0.08);
text-align:center;
transition:all 0.25s ease;
cursor:pointer
}

/* EFECTO HOVER MÁS LLAMATIVO */
.card:hover{
transform:scale(1.07);
background:#7de2c3;
color:#1b3a3a;
box-shadow:0 10px 20px rgba(0,0,0,0.15);
}

.card:active{
transform:scale(1.07);
background:#5fd6b1;
}

.problem{
background:rgba(255,255,255,0.6);
border-radius:12px;
padding:50px 20px
}

.form-section{
background:rgba(255,255,255,0.75);
border-radius:12px
}

form{
max-width:480px;
margin:auto;
background:white;
padding:35px;
border-radius:12px;
box-shadow:0 2px 12px rgba(0,0,0,0.08)
}

label{
font-weight:bold
}

input,select{
width:100%;
padding:12px;
margin-top:8px;
margin-bottom:18px;
border-radius:6px;
border:1px solid #ccc;
font-size:14px
}

button{
width:100%;
padding:14px;
background:#4CAF8D;
color:white;
border:none;
border-radius:8px;
font-size:16px;
cursor:pointer;
transition:0.2s
}

button:hover{
background:#3d9e78
}

footer{
text-align:center;
padding:25px;
background:#222;
color:white
}

</style>
</head>
<body>

<header>
<h1>Equilibra</h1>
<p>Encuentra equilibrio entre tu vida, trabajo y bienestar emocional con herramientas simples desde tu celular.</p>
<a class="btn" href="#registro">Quiero probarlo</a>
<br><br>
<a class="btn" href="encuesta.html">Responder encuesta rápida</a>
</header>

<section>
<h2>Bienvenido a Equilibra</h2>
<p>Sabemos que la vida entre trabajo, estudio y responsabilidades puede ser estresante. Equilibra es un espacio digital pensado para ayudarte a reducir el estrés, mejorar tu bienestar emocional y encontrar pequeños momentos de calma durante tu día.</p>
<p>Nuestra misión es ofrecer herramientas simples y accesibles para que jóvenes entre 20 y 30 años puedan cuidar su salud mental sin complicaciones.</p>
</section>

<section class="problem">
<h2>El problema</h2>
<div class="grid">

<div class="card">
<h3>Estrés constante</h3>
<p>Muchos jóvenes enfrentan presión por trabajo, estudio y responsabilidades.</p>
</div>

<div class="card">
<h3>Poco tiempo</h3>
<p>No todos tienen tiempo para asistir a terapias o actividades de bienestar.</p>
</div>

<div class="card">
<h3>Falta de herramientas</h3>
<p>Es difícil encontrar soluciones simples y accesibles para el bienestar emocional.</p>
</div>

</div>
</section>

<section>
<h2>Nuestra solución</h2>
<p>Equilibra ofrece herramientas digitales que ayudan a mejorar el bienestar emocional de forma simple, rápida y accesible desde cualquier lugar.</p>

<div class="grid">

<div class="card">
<h3>Ejercicios de relajación</h3>
<p>Técnicas rápidas para reducir el estrés en pocos minutos.</p>
</div>

<div class="card">
<h3>Recomendaciones personalizadas</h3>
<p>Consejos adaptados a tu estado emocional.</p>
</div>

<div class="card">
<h3>Contenido de bienestar</h3>
<p>Información útil para cuidar tu salud mental.</p>
</div>

<div class="card">
<h3>Acceso desde tu celular</h3>
<p>Herramientas disponibles cuando las necesites.</p>
</div>

</div>
</section>

<section>
<h2>Beneficios</h2>

<div class="grid">

<div class="card">Reducir el estrés diario</div>
<div class="card">Mejorar tu bienestar emocional</div>
<div class="card">Encontrar equilibrio en tu rutina</div>
<div class="card">Cuidar tu salud mental fácilmente</div>

</div>

</section>

<section id="registro" class="form-section">
<h2>Prueba Equilibra</h2>
<p>Estamos validando esta idea. Regístrate para ser de las primeras personas en probar la plataforma.</p>

<form action="https://formsubmit.co/alvarezdana440@gmail.com" method="POST">

<label>Nombre</label>
<input type="text" name="Nombre" placeholder="Tu nombre" required>

<label>Email</label>
<input type="email" name="Email" placeholder="Tu correo" required>

<label>Edad</label>
<input type="number" name="Edad" placeholder="Tu edad" required>

<label>¿Te gustaría probar esta herramienta?</label>
<select name="Interes">
<option>Sí</option>
<option>No</option>
<option>Tal vez</option>
</select>

<button type="submit">Quiero probar Equilibra</button>

</form>

</section>

<footer>
<p>Equilibra - MVP de validación de idea de negocio</p>
</footer>

</body>
</html>

<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Encuesta | Equilibra</title>

<style>

body{
font-family: Arial, Helvetica, sans-serif;
margin:0;

background-image:
linear-gradient(rgba(255,255,255,0.65), rgba(255,255,255,0.65)),
url("https://images.unsplash.com/photo-1507525428034-b723cf961d3e");

background-size:cover;
background-position:center;
background-repeat:no-repeat;
background-attachment:fixed;
}

.container{
max-width:700px;
margin:80px auto;
background:white;
padding:40px;
border-radius:12px;
box-shadow:0 6px 20px rgba(0,0,0,0.15);
}

h1{
text-align:center;
margin-bottom:10px;
}

p{
text-align:center;
margin-bottom:30px;
color:#555;
}

label{
font-weight:bold;
display:block;
margin-top:20px;
}

input, textarea, select{
width:100%;
padding:12px;
margin-top:8px;
border-radius:6px;
border:1px solid #ccc;
font-size:14px;
}

textarea{
resize:vertical;
min-height:80px;
}

button{
margin-top:25px;
width:100%;
padding:14px;
background:#4CAF8D;
color:white;
border:none;
border-radius:8px;
font-size:16px;
cursor:pointer;
transition:0.2s;
}

button:hover{
background:#3d9e78;
}

.volver{
display:block;
text-align:center;
margin-top:20px;
text-decoration:none;
color:#4CAF8D;
font-weight:bold;
}

</style>
</head>

<body>

<div class="container">

<h1>Encuesta Equilibra</h1>

<p>Tu opinión nos ayudará a mejorar esta idea de bienestar emocional.</p>

<form action="https://formsubmit.co/alvarezdana440@gmail.com" method="POST">

<label>¿Cómo resuelves este problema hoy?</label>
<textarea name="Solucion_actual" placeholder="Ej: meditación, ejercicio, terapia, apps de bienestar..."></textarea>

<label>¿Cuánto pagarías por una herramienta así?</label>
<select name="Precio">
<option>$20.000 COP al mes</option>
<option>$30.000 COP al mes</option>
<option>$50.000 COP al mes</option>
<option>No pagaría</option>
</select>

<label>¿Qué es lo que MÁS te gusta de esta idea?</label>
<textarea name="Lo_que_mas_gusta"></textarea>

<label>¿Qué cambiarías o mejorarías?</label>
<textarea name="Cambios"></textarea>

<button type="submit">Enviar respuestas</button>

</form>

<a class="volver" href="readme.html">← Volver a la página principal</a>

</div>

</body>
</html>


