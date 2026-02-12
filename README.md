<!DOCTYPE html>
<!-- Le dice al navegador que estamos usando HTML5 -->

<html lang="es">
<!-- Elemento raíz del documento. lang="es" indica que está en español -->

<head>
<meta charset="UTF-8">
<!-- Permite usar acentos, ñ, símbolos, etc. -->

<title>Hello World 1999</title>
<!-- Título que aparece en la pestaña del navegador -->

<style>
/* ===== CSS INTERNO ===== */
/* Todo lo que está aquí adentro es diseño */

    body{
        background-color:#ff00c3; /* Fondo azul intenso 90s */
        color:#d49cfc; /* Texto verde fosforescente */
        font-family:"Comic Sans MS", cursive; /* Tipografía noventera obligatoria */
        text-align:center; /* Centra el texto */
        margin:0; /* Quita márgenes por defecto del navegador */
        padding:0; /* Quita espacio interno por defecto */
    }

    h1{
        font-size:50px; /* Tamaño grande para el HELLO KITTI */
        text-shadow: 3px 3px #ff00ff; /* Sombra rosa tipo efecto viejo internet */
        margin-top:50px; /* Espacio arriba del título */
    }

    .box{
        border:5px dashed #e8a8e8; /* Borde punteado rosa */
        margin:40px auto; /* Espacio exterior y centrado automático */
        padding:20px; /* Espacio interno */
        width:70%; /* Ancho del contenedor */
        background-color:#ffffff; /* Fondo negro dentro del cuadro */
    }

    .blink{
        animation: blink 1s infinite; 
        /* Aplica animación llamada "blink" cada 1 segundo en loop infinito */
    }

    @keyframes blink{
        /* Definimos cómo funciona la animación */
        0%{opacity:1;}   /* Visible */
        50%{opacity:0;}  /* Invisible */
        100%{opacity:1;} /* Visible otra vez */
    }

    footer{
        margin-top:40px; /* Espacio arriba del footer */
        font-size:14px; /* Texto más pequeño */
    }

</style>

</head>

<body>
<!-- Aquí empieza el contenido visible de la página -->

<marquee behavior="alternate" scrollamount="10">
<!-- Texto que se mueve (etiqueta obsoleta, perfecta para estética 90s) -->
✨ Bienvenidx a mi página experimental ✨
</marquee>

<h1 class="blink">HELLO WORLD</h1>
<!-- Título principal con clase "blink" para que parpadee -->

<div class="box">
    <!-- Contenedor con borde y fondo negro -->
    <p>Esta página fue creada en Visual Studio Code.</p>
    <p>Modo net.art activado.</p>
    <p>Estética: 1997 pero con conciencia crítica.</p>
</div>

<marquee direction="right" scrollamount="6">
<!-- Otro texto desplazándose hacia la derecha -->
💾 Under Construction 💾 Under Construction 💾
</marquee>

<footer>
    <!-- Pie de página -->
    © 1999 - Gabriela Najera - Internet Forever
</footer>

</body>
</html>
