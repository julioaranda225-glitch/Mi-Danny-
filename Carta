<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Para Mi Danny 🌻</title>

<link href="https://fonts.googleapis.com/css2?family=Dancing+Script&family=Playfair+Display&display=swap" rel="stylesheet">

<style>

body {
    margin: 0;
    padding: 0;
    background: linear-gradient(#fdf6e3, #fff);
    font-family: 'Playfair Display', serif;
    overflow-x: hidden;
}

/* 🌻 Fondo decorativo */
.sunflower {
    position: fixed;
    width: 100px;
    opacity: 0.2;
}

.sunflower1 { top: 5%; left: 3%; }
.sunflower2 { bottom: 5%; right: 3%; }

/* 📜 Carta */
.carta {
    max-width: 800px;
    margin: 60px auto;
    padding: 50px;
    background: #fffdf7;
    border-radius: 10px;
    box-shadow: 0 10px 30px rgba(0,0,0,0.1);
    line-height: 1.8;
}

/* ✍️ Título */
.titulo {
    font-family: 'Dancing Script', cursive;
    font-size: 40px;
    color: #d4a017;
}

/* ✨ Párrafos animados */
.parrafo {
    opacity: 0;
    transform: translateY(20px);
    transition: all 1s ease;
    margin-bottom: 20px;
}

.parrafo.visible {
    opacity: 1;
    transform: translateY(0);
}

/* 🔘 Botón */
.boton {
    display: block;
    margin: 40px auto;
    padding: 15px 25px;
    background: #d4a017;
    color: white;
    border: none;
    border-radius: 10px;
    cursor: pointer;
}

/* 💛 Firma */
.firma {
    margin-top: 40px;
    font-family: 'Dancing Script', cursive;
    font-size: 28px;
    text-align: right;
}

</style>
</head>

<body>

<img src="https://i.imgur.com/4M7IWwP.png" class="sunflower sunflower1">
<img src="https://i.imgur.com/4M7IWwP.png" class="sunflower sunflower2">

<!-- 🎵 Música -->
<audio id="musica" loop>
  <source src="https://www.bensound.com/bensound-music/bensound-slowmotion.mp3" type="audio/mpeg">
</audio>

<div class="carta">

<div class="titulo">Mi Danny,</div>
<p class="parrafo">Amor de mi vida y para mi vida…</p>

<button class="boton" onclick="iniciar()">Ábrelo solo si estás lista para sentir 💛</button>

<div id="contenido">

<p class="parrafo">A veces me pongo a pensar y no sé qué es más doloroso: si haber vivido algo tan real contigo y ahora extrañarlo, o nunca haberlo vivido. Pero si soy honesto, te volvería a elegir incluso sabiendo cómo termina cada distancia, porque fuiste la casualidad más linda de mi vida.</p>

<p class="parrafo">Me diste algo que nadie más ha podido darme. Incluso lograste regalarme el mejor cumpleaños en medio del caos, de las complicaciones y de todo lo que no estaba a nuestro favor. Y eso no se olvida.</p>

<p class="parrafo">Cuando pensé que lo tendría todo, tú ya no estabas. Y en ese momento comprendí que tú eras todo.</p>

<p class="parrafo">A veces creo que Dios, la vida o la energía sabía que la única forma de separarnos era poniendo un océano entre nosotros, porque de otra forma simplemente no habría sido posible.</p>

<p class="parrafo">El hombre que hoy ves tiene tu nombre escondido en cada logro. Es gracias a ti. Todo ese crédito es tuyo.</p>

<p class="parrafo">No tengo corazón, porque te lo di. Y si soy honesto, creo que te lo llevaste contigo. Y lo peor es que ni siquiera quiero que me lo devuelvas.</p>

<p class="parrafo">Eres hermosa, encantadora… esa mezcla rara de paz, fuego, dulzura y locura que no se repite. Mi Danny…</p>

<p class="parrafo">Te amo más que nunca. De esa forma que no se va, que no se olvida.</p>

<p class="parrafo">Hoy estamos lejos, pero hay cosas que no saben de distancia… como ese “hoy y siempre”.</p>

<p class="parrafo">Te amo… mujer mía, esposa mía, madre de mis hijos.</p>

<p class="parrafo">Algún día… me vas a hacer papá.</p>

<p class="parrafo">No fuiste algo bonito… fuiste algo que me cambió para siempre.</p>

<div class="firma">De tu ingeniero 💛</div>

</div>
</div>

<script>

function iniciar() {
    const musica = document.getElementById("musica");
    musica.play();

    const parrafos = document.querySelectorAll(".parrafo");

    let i = 0;

    function mostrar() {
        if (i < parrafos.length) {
            parrafos[i].classList.add("visible");
            i++;
            setTimeout(mostrar, 1200);
        }
    }

    mostrar();
}

</script>

</body>
</html>
