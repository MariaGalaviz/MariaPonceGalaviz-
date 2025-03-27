<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi CV</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .container {
            width: 80%;
            max-width: 800px;
            margin: 20px auto;
            background: white;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .header {
            text-align: center;
        }
        .header img {
            width: 150px;
            border-radius: 50%;
        }
        h1, h2 {
            color: #333;
        }
        .section {
            margin-bottom: 20px;
        }
        .section h2 {
            border-bottom: 2px solid #007BFF;
            padding-bottom: 5px;
        }
        .section p, .section ul {
            margin: 10px 0;
        }
    </style>
</head>
<body>

    <div class="container">
        <div class="header">
            <img src="foto.jpg" alt="Foto de perfil">
            <h1>Tu Nombre</h1>
            <p>Ingeniero en Sistemas de la Información</p>
        </div>

        <div class="section">
            <h2>Contacto</h2>
            <p>Email: tuemail@example.com</p>
            <p>Teléfono: +52 123 456 7890</p>
            <p>LinkedIn: <a href="#">linkedin.com/in/tuusuario</a></p>
        </div>

        <div class="section">
            <h2>Experiencia Laboral</h2>
            <h3>Empresa ABC - Desarrollador de Software</h3>
            <p>2022 - Actualidad</p>
            <ul>
                <li>Desarrollo de aplicaciones web con HTML, CSS y JavaScript.</li>
                <li>Implementación de bases de datos SQL y NoSQL.</li>
            </ul>

            <h3>Empresa XYZ - Analista de Sistemas</h3>
            <p>2019 - 2022</p>
            <ul>
                <li>Optimización de sistemas internos y automatización de procesos.</li>
                <li>Soporte y mantenimiento de infraestructura tecnológica.</li>
            </ul>
        </div>

        <div class="section">
            <h2>Educación</h2>
            <h3>Universidad de Sonora</h3>
            <p>Ingeniería en Sistemas de la Información (2015 - 2019)</p>
        </div>

        <div class="section">
            <h2>Habilidades</h2>
            <ul>
                <li>Desarrollo Web (HTML, CSS, JavaScript, React)</li>
                <li>Gestión de Bases de Datos (MySQL, MongoDB)</li>
                <li>Programación en Python y Java</li>
                <li>Administración de Sistemas y Redes</li>
            </ul>
        </div>

        <div class="section">
            <h2>Idiomas</h2>
            <p>Español - Nativo</p>
            <p>Inglés - Avanzado</p>
        </div>
    </div>

</body>
</html>
