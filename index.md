<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Portafolio de Camilo Bolaños - Desarrollador Web y Diseñador Creativo">
    <meta name="author" content="Camilo Bolaños">
    <title>Camilo Bolaños | Portafolio</title>

    <!-- Favicon -->
    <link rel="icon" href="assets/favicon.ico" type="image/x-icon">

    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap" rel="stylesheet">

    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">

    <!-- Estilos CSS -->
    <style>
        /* Reset básico */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Poppins', sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f9f9f9;
        }

        a {
            text-decoration: none;
            color: inherit;
        }

        /* Header */
        header {
            background: #2c3e50;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }

        header h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }

        header p {
            font-size: 1.2rem;
            color: #bdc3c7;
        }

        /* Navegación */
        nav {
            display: flex;
            justify-content: center;
            background: #34495e;
            padding: 10px 0;
        }

        nav a {
            color: #ecf0f1;
            margin: 0 15px;
            font-size: 1rem;
            transition: color 0.3s ease;
        }

        nav a:hover {
            color: #1abc9c;
        }

        /* Secciones principales */
        section {
            padding: 60px 20px;
            text-align: center;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
        }

        /* Acerca de mí */
        #about {
            background: #fff;
        }

        #about img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            margin-bottom: 20px;
        }

        /* Proyectos */
        #projects {
            background: #ecf0f1;
        }

        .project {
            display: inline-block;
            width: 30%;
            margin: 1%;
            background: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }

        .project:hover {
            transform: translateY(-10px);
        }

        .project img {
            width: 100%;
            border-radius: 8px;
        }

        /* Contacto */
        #contact {
            background: #2c3e50;
            color: #fff;
        }

        #contact form {
            max-width: 600px;
            margin: 0 auto;
            text-align: left;
        }

        #contact input, #contact textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: none;
            border-radius: 5px;
        }

        #contact button {
            background: #1abc9c;
            color: #fff;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background 0.3s ease;
        }

        #contact button:hover {
            background: #16a085;
        }

        /* Footer */
        footer {
            background: #34495e;
            color: #bdc3c7;
            text-align: center;
            padding: 10px 0;
        }

        footer a {
            color: #1abc9c;
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Camilo Bolaños</h1>
        <p>Desarrollador Web & Diseñador Creativo</p>
    </header>

    <!-- Navegación -->
    <nav>
        <a href="#about">Acerca de mí</a>
        <a href="#projects">Proyectos</a>
        <a href="#contact">Contacto</a>
    </nav>

    <!-- Acerca de mí -->
    <section id="about">
        <div class="container">
            <img src="assets/profile.jpg" alt="Camilo Bolaños">
            <h2>Acerca de mí</h2>
            <p>Hola, soy Camilo Bolaños, un apasionado desarrollador web y diseñador creativo con más de 5 años de experiencia en la creación de soluciones digitales innovadoras. Me especializo en desarrollo frontend, UX/UI y optimización de rendimiento.</p>
        </div>
    </section>

    <!-- Proyectos -->
    <section id="projects">
        <div class="container">
            <h2>Mis Proyectos</h2>
            <div class="project">
                <img src="assets/project1.jpg" alt="Proyecto 1">
                <h3>Proyecto 1</h3>
                <p>Descripción breve del proyecto 1.</p>
            </div>
            <div class="project">
                <img src="assets/project2.jpg" alt="Proyecto 2">
                <h3>Proyecto 2</h3>
                <p>Descripción breve del proyecto 2.</p>
            </div>
            <div class="project">
                <img src="assets/project3.jpg" alt="Proyecto 3">
                <h3>Proyecto 3</h3>
                <p>Descripción breve del proyecto 3.</p>
            </div>
        </div>
    </section>

    <!-- Contacto -->
    <section id="contact">
        <div class="container">
            <h2>Contacto</h2>
            <form action="mailto:tuemail@example.com" method="post" enctype="text/plain">
                <input type="text" name="name" placeholder="Tu nombre" required>
                <input type="email" name="email" placeholder="Tu correo electrónico" required>
                <textarea name="message" rows="5" placeholder="Tu mensaje" required></textarea>
                <button type="submit">Enviar</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2023 Camilo Bolaños. Todos los derechos reservados. | 
            <a href="https://github.com/tuusuario" target="_blank"><i class="fab fa-github"></i></a> 
            <a href="https://linkedin.com/in/tuusuario" target="_blank"><i class="fab fa-linkedin"></i></a>
        </p>
    </footer>

</body>
</html>
