<!DOCTYPE html>

<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portafolio de Carol Zavala</title>
</head>
    
<body>

<header>
    <h1>¡Hola! 👋 Soy Carol</h1>
</header>

<section>
    <h2>Sobre Mí</h2>
    <p>Soy Ingeniera en TIC’s con especialidad en desarrollo de aplicaciones. Me apasiona el desarrollo, el diseño, y sobre todo aprender cosas nuevas.</p>
</section>

<section>
    <h2>Redes Sociales</h2>
    <div class="social-buttons">
        <a href="https://www.linkedin.com/in/carol-zavala/" class="social-button" target="_blank">
            <img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" alt="LinkedIn">
        </a>
        <a href="https://github.com/CarolZavala" class="social-button" target="_blank">
            <img src="https://cdn-icons-png.flaticon.com/512/733/733553.png" alt="GitHub">
        </a>
        <a href="https://x.com/caro_zav" class="social-button" target="_blank">
            <img src="https://cdn-icons-png.flaticon.com/512/733/733579.png" alt="Twitter">
        </a>
        <a href="#" class="social-button" target="_blank">
            <img src="https://cdn-icons-png.flaticon.com/512/1384/1384063.png" alt="Instagram">
        </a>
    </div>
</section>

<section>
    <h2>Habilidades</h2>
    <ul>
        <li><strong>Lenguajes de programación:</strong> JavaScript</li>
        <li><strong>Frameworks:</strong> React, Vue</li>
        <li><strong>Herramientas:</strong> Git</li>
    </ul>
</section>

<section>
    <h2>Proyectos Destacados</h2>
    <ul>
        <li><strong>[Proyecto 1]</strong>: Breve descripción del proyecto y tecnologías utilizadas. <a href="ENLACE_AL_PROYECTO_1" target="_blank">Ver proyecto</a></li>
        <li><strong>[Proyecto 2]</strong>: Breve descripción del proyecto y tecnologías utilizadas. <a href="ENLACE_AL_PROYECTO_2" target="_blank">Ver proyecto</a></li>
    </ul>
</section>

<section>
    <h2>Contacto</h2>
    <p>Puedes contactarme a través de <a href="mailto:carolalexandrazavala@gmail.com">mi email</a>.</p>
</section>

</body>
</html>

<style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            color: #333;
        }

        header {
            text-align: center;
            background: url('https://media.giphy.com/media/3o6nURg3qg7PZLgllq/giphy.gif') no-repeat center;
            background-size: cover;
            color: white;
            padding: 60px 20px;
        }

        header h1 {
            font-size: 3rem;
            margin: 0;
        }

        section {
            padding: 20px;
            margin: 20px;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
        }

        h2 {
            color: #007acc;
        }

        ul {
            list-style-type: none;
            padding: 0;
        }

        ul li {
            margin: 10px 0;
        }

        a {
            text-decoration: none;
            color: #007acc;
        }

        a:hover {
            text-decoration: underline;
        }

        .social-buttons {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin-top: 10px;
        }

        .social-button {
            display: inline-block;
            width: 50px;
            height: 50px;
            background-color: #fff;
            border-radius: 50%;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
            transition: transform 0.2s, background-color 0.3s;
        }

        .social-button img {
            width: 30px;
            height: 30px;
            margin: 10px;
        }

        .social-button:hover {
            transform: scale(1.1);
            background-color: #f0f0f0;
        }
    </style>
