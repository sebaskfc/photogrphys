# photogrphys
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sebastian Valencia Photography</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }
        header {
            background-color: #333;
            color: white;
            padding: 1rem;
            text-align: center;
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 1rem;
        }
        .gallery img {
            margin: 0.5rem;
            max-width: 300px;
            height: auto;
            border: 2px solid #ccc;
            border-radius: 5px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1rem;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Galería de Fotografía</h1>
    </header>
    <div class="gallery">
        <img src="c:\Users\valen\Pictures\_MG_0007.JPG" alt="Foto 1">
        <img src="c:\Users\valen\Pictures\_MG_0025.JPG" alt="Foto 2">
     
    </div>
    <section class="services">
        <h2>Servicios</h2>
        <ul>
            <li>Fotografía de bodas</li>
            <li>Sesiones de retrato</li>
            <li>Fotografía de eventos</li>
            <li>Fotografía de productos</li>
        </ul>




        
    </sectio</div></section>
    <section class="about"></section>
        <h2>Sobre Mí</h2>
        <p>Hola, soy Sebastian Valencia, un fotógrafo apasionado por capturar momentos únicos y especiales. Bienvenido a mi galería en línea.</p>
    </section>
    <section class="contact">
        <h2>Contacto</h2>
        <form action="mailto:example@example.com" method="post" enctype="text/plain">
            <label for="name">Nombre:</label>
            <input type="text" id="name" name="name" required>
            <br>
            <label for="email">Correo Electrónico:</label>
            <input type="email" id="email" name="email" required>
            <br>
            <label for="message">Mensaje:</label>
            <textarea id="message" name="message" rows="4" required></textarea>
            <br>
            <input type="submit" value="Enviar">
        </form>
    </section>

    


    
<center>
    <section class="testimonials"></section>
        <h2>Testimonios</h2>
        <blockquote>
            <p>"Sebastian capturó nuestro día especial de una manera increíble. Las fotos son hermosas y estamos muy agradecidos."</p>
            <cite>- Juan y Maria</cite>
        </blockquote>
        <blockquote>
            <p>"Las sesiones de retrato con Sebastian son siempre divertidas y los resultados son impresionantes."</p>
            <cite>- Laura G.</cite>
        </blockquote>
    </section>
</center>


<section class="banner">
    <div class="banner-text">
        <p id="banner-message">Capturando momentos únicos</p>
    </div>
</section>

<style>
    .banner {
        background-color: #444;
        color: white;
        text-align: center;
        padding: 2rem;
        margin: 1rem 0;
        border-radius: 5px;
    }
    .banner-text {
        font-size: 1.5rem;
        animation: changeText 10s infinite;
    }
    @keyframes changeText {
        0% { opacity: 0; }
        10% { opacity: 1; }
        30% { opacity: 1; }
        40% { opacity: 0; }
        100% { opacity: 0; }
    }
</style>

<script>
    const messages = [
        "Capturando momentos únicos",
        "Fotografía profesional para cada ocasión",
        "Transformando recuerdos en arte",
        "Tu historia a través de mi lente"
    ];
    let messageIndex = 0;

    function changeBannerText() {
        const bannerMessage = document.getElementById('banner-message');
        bannerMessage.style.opacity = 0;
        setTimeout(() => {
            messageIndex = (messageIndex + 1) % messages.length;
            bannerMessage.textContent = messages[messageIndex];
            bannerMessage.style.opacity = 1;
        }, 1000);
    }

    setInterval(changeBannerText, 10000);
</script>


<center>
<section class="faq">
    <h2>Preguntas Frecuentes</h2>
    <div class="faq-item">
        <h3>¿Cómo puedo reservar una sesión de fotos?</h3>
        <p>Puedes reservar una sesión de fotos contactándome a través del formulario de contacto en esta página o enviando un correo electrónico: valenciaaguirresebastian7@gmail.com</p>
    </div>
    <div class="faq-item">
        <h3>¿Cuánto tiempo dura una sesión de fotos?</h3>
        <p>La duración de una sesión de fotos depende del tipo de sesión. Generalmente, una sesión de retrato dura entre 1 y 2 horas.</p>
    </div>
    <div class="faq-item">
        <h3>¿Cuándo recibiré mis fotos?</h3>
        <p>Recibirás tus fotos editadas dentro de 2 a 3 semanas después de la sesión.</p>
    </div>
    <div class="faq-item">
        <h3>¿Ofreces servicios de impresión de fotos?</h3>
        <p>Sí, ofrezco servicios de impresión de fotos en varios tamaños y formatos. Puedes consultar los detalles durante la sesión.</p>
    </div>
</section>

</center>



    <footer>
        <p>&copy; 2023 Fotografía Ejemplar. Todos los derechos reservados.</p>
    </footer>




    
</script>
</body>
</html>
