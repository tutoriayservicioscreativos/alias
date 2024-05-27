<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tutoría y Servicios Creativos</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        /* Estilos para el formulario */
        .contact-form {
            background-color: #f9f9f9;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            margin-top: 20px;
        }
        .contact-form h2 {
            color: #4caf50; /* Verde */
            margin-bottom: 20px;
        }
        .contact-form label {
            display: block;
            margin-bottom: 10px;
            font-weight: bold;
        }
        .contact-form input[type="text"],
        .contact-form input[type="email"],
        .contact-form textarea {
            width: 100%;
            padding: 8px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .contact-form input[type="submit"] {
            background-color: #4caf50; /* Verde */
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .contact-form input[type="submit"]:hover {
            background-color: #45a049; /* Verde más oscuro */
        }
    </style>
</head>
<body>
    <header>
        <h1>Tutoría y Servicios Creativos</h1>
    </header>
    <section class="services">
        <div class="service">
            <h2>Tutoría en Línea</h2>
            <p>Ofrecemos servicios de tutoría en línea en una variedad de materias escolares y habilidades específicas.</p>
            <p>Precio: $2000 ARS por hora</p>
            <a href="https://link.mercadopago.com.ar/serviciosytutoria" class="button">Pagar con Mercado Pago</a>
        </div>
        <div class="service">
            <h2>Edición de Videos Simples</h2>
            <p>Servicios de edición de video para videos cortos destinados a redes sociales, tutoriales simples, compilaciones, entre otros.</p>
            <p>Precio: $7000 ARS por proyecto</p>
            <a href="https://link.mercadopago.com.ar/serviciosytutoria" class="button">Pagar con Mercado Pago</a>
        </div>
        <div class="service">
            <h2>Diseño Gráfico Básico</h2>
            <p>Ofrecemos servicios de diseño gráfico básico para la creación de logotipos simples, publicaciones en redes sociales, banners y más.</p>
            <p>Precio: $3000 ARS por proyecto</p>
            <a href="https://link.mercadopago.com.ar/serviciosytutoria" class="button">Pagar con Mercado Pago</a>
        </div>
    </section>
    <section class="contact-form">
        <h2>Contacto</h2>
        <form action="#" method="post">
            <label for="name">Nombre:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Correo electrónico:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Mensaje:</label>
            <textarea id="message" name="message" rows="4" required></textarea>
            <input type="submit" value="Enviar">
        </form>
    </section>
    <footer>
        <p>Contacto: elias.gialleonardo260608@gmail.com</p>
    </footer>
</body>
</html>
