<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Plataforma IA</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Plataforma de Inteligencia Artificial</h1>
        <nav>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#servicios">Servicios</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <section id="inicio" class="seccion">
        <h2>Bienvenido a nuestra plataforma de IA</h2>
        <p>Descubre el poder de la inteligencia artificial para transformar tu negocio.</p>
        <button id="boton-inicio">Comienza ahora</button>
    </section>

    <section id="servicios" class="seccion">
        <h2>Nuestros servicios</h2>
        <div class="servicios-grid">
            <div class="servicio">
                <h3>Análisis de datos</h3>
                <p>Extraemos información valiosa de tus datos para tomar decisiones informadas.</p>
            </div>
            <div class="servicio">
                <h3>Visión por computadora</h3>
                <p>Desarrollamos sistemas de reconocimiento de imágenes y videos.</p>
            </div>
            <div class="servicio">
                <h3>Procesamiento de lenguaje natural</h3>
                <p>Creamos chatbots y asistentes virtuales para mejorar la comunicación con tus clientes.</p>
            </div>
        </div>
    </section>

    <section id="contacto" class="seccion">
        <h2>Contáctanos</h2>
        <form id="formulario-contacto">
            <input type="text" placeholder="Nombre" required>
            <input type="email" placeholder="Correo electrónico" required>
            <textarea placeholder="Mensaje" required></textarea>
            <button type="submit">Enviar mensaje</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Plataforma IA. Todos los derechos reservados.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>

body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #333;
    color: #fff;
    padding: 1em 0;
    text-align: center;
}

header nav ul {
    list-style: none;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin: 0 1em;
}

header nav ul li a {
    color: #fff;
    text-decoration: none;
}

.seccion {
    padding: 2em;
    text-align: center;
    margin-bottom: 2em;
}

.seccion h2 {
    color: #007bff;
}

.servicios-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 1em;
}

.servicio {
    background-color: #fff;
    padding: 1.5em;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

#formulario-contacto {
    display: flex;
    flex-direction: column;
    align-items: center;
}

#formulario-contacto input, #formulario-contacto textarea {
    width: 80%;
    padding: 1em;
    margin-bottom: 1em;
    border: 1px solid #ddd;
    border-radius: 4px;
}

button {
    background-color: #007bff;
    color: #fff;
    padding: 1em 2em;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 1em 0;
}
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #333;
    color: #fff;
    padding: 1em 0;
    text-align: center;
}

header nav ul {
    list-style: none;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin: 0 1em;
}

header nav ul li a {
    color: #fff;
    text-decoration: none;
}

.seccion {
    padding: 2em;
    text-align: center;
    margin-bottom: 2em;
}

.seccion h2 {
    color: #007bff;
}

.servicios-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 1em;
}

.servicio {
    background-color: #fff;
    padding: 1.5em;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

#formulario-contacto {
    display: flex;
    flex-direction: column;
    align-items: center;
}

#formulario-contacto input, #formulario-contacto textarea {
    width: 80%;
    padding: 1em;
    margin-bottom: 1em;
    border: 1px solid #ddd;
    border-radius: 4px;
}

button {
    background-color: #007bff;
    color: #fff;
    padding: 1em 2em;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 1em 0;
}
