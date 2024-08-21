<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RunGirl</title>
    <link href="https://fonts.googleapis.com/css2?family=Anton&display=swap" rel="stylesheet">
    <style>
        /* Asegúrate de que no haya márgenes ni padding en el html y body */
        html, body {
            margin: 0;
            padding: 0;
            height: 100%; /* Asegura que ocupe toda la altura de la pantalla */
        }

        body {
            font-family: 'Anton', sans-serif; /* Fuente divertida */
            color: white;
            background-color: #FF89BB; /* Fondo general */
        }

        /* Encabezado con imagen de fondo y título */
        header {
            background-image: url('https://github.com/user-attachments/assets/75ca29e8-c11b-4ff5-834d-7241c36efe57'); /* URL de la imagen */
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
            height: 100vh; /* Ocupa toda la altura de la ventana */
            width: 100vw; /* Ocupa toda la anchura de la ventana */
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            position: relative;
            color: white;
        }

        header h1 {
            font-size: 7em; /* Aumenta el tamaño del título */
            margin: 0;
            text-shadow: 2px 2px 5px rgba(0,0,0,0.7); /* Sombra para destacar el texto */
        }

        /* Galería de imágenes */
        .gallery {
            background-color: #FF94DF; /* Rosa claro */
            padding: 50px 0;
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            overflow: hidden;
            position: relative;
            width: 100%; /* Asegura que la galería ocupe toda la anchura */
        }

        .gallery img {
            margin: 0px;
            width: 400px;  /* Ancho más grande */
            height: 300px; /* Alto más grande */
            object-fit: cover;
            border-radius: 10px;
        }

        .gallery img:hover {
            transform: rotate(3deg);
        }

        /* Frase inspiradora */
        .inspiration {
            background-color: #FF69B4; /* Rosa vivo */
            padding: 50px 20px;
            text-align: center;
            font-size: 2.5em;
            font-style: italic;
        }

        /* Sección "Quién Soy" */
        .about {
            background-color: #FF5A7F; /* Rosa intenso */
            padding: 50px 20px;
            text-align: center;
            color: white;
        }

        .about h2 {
            font-size: 2.5em;
            margin-bottom: 20px;
        }

        .about p {
            font-size: 1.2em;
            max-width: 800px;
            margin: auto;
        }

        /* Sección de eventos */
        .events {
            background-image: url('https://github.com/user-attachments/assets/2b90fe2b-7a11-407a-a6d9-63379f8e078e'); /* Imagen de fondo */
            background-size: cover;
            background-attachment: fixed;
            background-position: center;
            background-repeat: no-repeat;
            padding: 50px 20px;
            text-align: center;
            color: white;
            width: 100%; /* Asegura que la sección de eventos ocupe toda la anchura */
        }

        .events h2 {
            font-size: 2.5em;
            margin-bottom: 20px;
        }

        .events p {
            font-size: 1.2em;
            max-width: 800px;
            margin: auto;
        }

        /* Pie de página */
        footer {
            background-color: #FF7070; /* Rosa coral */
            padding: 20px;
            text-align: center;
            color: white;
            font-size: 0.9em;
            width: 100%; /* Asegura que el pie de página ocupe toda la anchura */
        }
    </style>
</head>
<body>
    <header>
        <h1>RunGirl</h1> <!-- Único título -->
    </header>

    <section class="gallery">
        <img src="imagen1.jpg" alt="Correr en la naturaleza">
        <img src="imagen2.jpg" alt="Correr en la ciudad">
        <img src="imagen3.jpg" alt="Correr en la playa">
        <!-- Agrega más imágenes según sea necesario -->
    </section>

    <section class="inspiration">
        "Cada zancada es un paso más cerca de tus sueños."
    </section>

    <section class="about">
        <h2>Quién Soy</h2>
        <p>¡Hola! Soy Fátima, fundadora de "RunGirl". He encontrado en el running una forma de expresar mi pasión, mi libertad, y mi determinación. Este espacio es para todas las niñas y mujeres que buscan inspirarse, superarse y conectar con el poder del running.</p>
    </section>

    <section class="events">
        <h2>Próximos Eventos</h2>
        <p>Únete a nosotros en nuestras próximas carreras y eventos de running en todo el país. Ya sea que estés comenzando o seas una corredora experimentada, tenemos algo para ti.</p>
    </section>

    <footer>
        © 2024 RunGirl. Todos los derechos reservados. 
    </footer>
</body>
</html>
