<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Portafolio personal de Never Rojas Campos">
    <title>Portafolio | Never Rojas</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;700&display=swap" rel="stylesheet">
</head>
<body>
    <header>
        <nav>
            <h1>Never Rojas</h1>
            <ul>
                <li><a href="#about">Sobre Mí</a></li>
                <li><a href="#projects">Proyectos</a></li>
                <li><a href="#contact">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="hero">
            <h2>¡Hola! Soy Never Rojas Campos</h2>
            <p>Especialista en Redes, Ciberseguridad y Programación. Aquí está mi trabajo.</p>
            <a href="#projects" class="btn">Ver Proyectos</a>
        </section>

        <section id="about">
            <h3>Sobre Mí</h3>
            <p>Soy un apasionado de la tecnología con experiencia en redes, ciberseguridad y desarrollo de software. Mi objetivo es crear soluciones innovadoras que marquen la diferencia.</p>
        </section>

        <section id="projects">
            <h3>Proyectos Destacados</h3>
            <div class="project">
                <img src="images/proyecto1.jpg" alt="Proyecto 1">
                <h4>Proyecto 1</h4>
                <p>Descripción breve del proyecto.</p>
            </div>
            <div class="project">
                <img src="images/proyecto2.jpg" alt="Proyecto 2">
                <h4>Proyecto 2</h4>
                <p>Descripción breve del proyecto.</p>
            </div>
        </section>

        <section id="contact">
            <h3>Contacto</h3>
            <form id="contact-form">
                <input type="text" name="name" placeholder="Nombre" required>
                <input type="email" name="email" placeholder="Correo Electrónico" required>
                <textarea name="message" placeholder="Mensaje" required></textarea>
                <button type="submit">Enviar</button>
            </form>
        </section>
    </main>

    <footer>
        <p>© 2024 Never Rojas Campos - Todos los derechos reservados.</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>

