<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RunGirl</title>
    <!-- Corrección del enlace a Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Anton&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            font-family: 'Anton', sans-serif; /* Corrección en el uso de la fuente */
            color: white;
            background-color: #FF89BB; /* Fondo general */
        }

        /* Encabezado con título */
        header {
            background-color: #C48BFF; /* Lila */
            color: white;
            padding: 50px 0;
            text-align: center;
            font-size: 3em;
            font-weight: bold;
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
            background-image: url('evento_fondo.jpg'); /* Imagen de fondo */
            background-size: cover;
            background-attachment: fixed;
            padding: 50px 20px;
            text-align: center;
            color: white;
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
        }
    </style>
</head>
<body>
    <header>
        RunGirl
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
