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

<a class="volver" href="Pagina.html">← Volver a la página principal</a>

</div>

</body>
</html>
