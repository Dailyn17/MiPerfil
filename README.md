<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Perfil</title>
    <link rel="stylesheet" href="Estilos.css">
</head>
<body>
    <header>
        <h1>Mi Perfil</h1>
    </header>
    <section>
        <h2>Sobre Mí</h2>
        <p>Soy una persona responsable y dedicada a todo lo que me gusta, amante de todo lo relacionado con la tecnología.</p>
    </section>
    <section>
        <h2>Experiencia</h2>
        <p>Mi experiencia radica en trabajos que he realizado ya sea como redactora de páginas web y manejar bases de datos.</p>
    </section>
    <section>
        <h2>Educación</h2>
        <p>Bachiller, cuento con cursos de idiomas, diseño de páginas web y atención al cliente, y actualmente estoy estudiando informática en la universidad, donde he aprendido más sobre programación.</p>
    </section>

    <!-- Nueva sección del formulario de contacto -->
    <section>
        <h2>Contacto</h2>
        <form id="contactForm">
            <label for="name">Nombre:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Correo Electrónico:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Mensaje:</label>
            <textarea id="message" name="message" required></textarea>

            <button type="submit">Enviar</button>
        </form>
        <div id="responseMessage"></div>
    </section>

    <script src="script.js"></script>
</body>
</html>
