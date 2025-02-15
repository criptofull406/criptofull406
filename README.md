- 👋 Hi, I’m @criptofull406
- 👀 I’m interested in ...el desarrollo y nuevas tecnologias
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ALQUILER DE CASA AUTO Y MÁS</title>
    <style>
        /* Estilos Generales */
        body {
            font-family: 'Poppins', Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
            line-height: 1.6;
        }
        h1, h2, h3 {
            color: #0074D9;
            text-align: center;
        }
        p {
            color: #555;
        }
        a {
            color: #0074D9;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }

        /* Header */
        header {
            background: linear-gradient(135deg, #0074D9, #28A745);
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        header img {
            width: 120px;
            margin-bottom: 10px;
        }
        header h1 {
            font-size: 28px;
            margin: 0;
        }
        header p {
            font-size: 16px;
            margin: 5px 0 0;
        }

        /* Formulario */
        form {
            max-width: 600px;
            margin: 20px auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        label {
            display: block;
            margin-top: 15px;
            font-weight: bold;
            color: #333;
        }
        input, select, textarea {
            width: 100%;
            padding: 10px;
            margin-top: 5px;
            border: 1px solid #ccc;
            border-radius: 5px;
            transition: border-color 0.3s ease;
        }
        input:focus, select:focus, textarea:focus {
            border-color: #0074D9;
            outline: none;
        }
        button {
            display: block;
            width: 100%;
            padding: 12px;
            background: #0074D9;
            color: white;
            border: none;
            border-radius: 5px;
            font-size: 16px;
            cursor: pointer;
            margin-top: 20px;
            transition: background 0.3s ease;
        }
        button:hover {
            background: #0056b3;
        }

        /* Sección de Pagos */
        .payment-section {
            margin-top: 20px;
            text-align: center;
        }
        .payment-section p {
            font-size: 14px;
            color: #555;
        }
        .payment-section a {
            color: #28A745;
            font-weight: bold;
        }
        .payment-section a:hover {
            text-decoration: underline;
        }

        /* Publicaciones */
        .publicaciones {
            margin-top: 20px;
            padding: 20px;
            background: white;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .publicacion {
            margin-bottom: 20px;
            padding: 15px;
            border: 1px solid #ddd;
            border-radius: 8px;
        }
        .publicacion.normal {
            border-left: 5px solid #0074D9;
        }
        .publicacion.clasificado {
            border-left: 5px solid #FFC107;
        }
        .publicacion.premium {
            border-left: 5px solid #28A745;
        }
        .publicacion h4 {
            margin: 0 0 10px;
        }
        .publicacion p {
            margin: 5px 0;
        }

        /* Footer */
        footer {
            background: #333;
            color: white;
            padding: 20px;
            text-align: center;
            margin-top: 20px;
        }
        footer a {
            color: #0074D9;
            margin: 0 10px;
        }
        footer a:hover {
            text-decoration: underline;
        }

        /* Botones de Redes Sociales */
        .social-buttons {
            margin-top: 20px;
            text-align: center;
        }
        .social-buttons a {
            display: inline-block;
            margin: 0 10px;
            font-size: 24px;
            color: #fff;
            background: #0074D9;
            width: 40px;
            height: 40px;
            line-height: 40px;
            text-align: center;
            border-radius: 50%;
            transition: background 0.3s ease;
        }
        .social-buttons a:hover {
            background: #0056b3;
        }

        /* Nota de Seguridad */
        .security-note {
            margin-top: 20px;
            text-align: center;
            font-size: 14px;
            color: #e74c3c;
        }

        /* Animaciones y Responsive */
        @media (max-width: 768px) {
            header img {
                width: 100px;
            }
            form {
                padding: 15px;
            }
        }
    </style>
</head>
<body>
    <!-- Encabezado con Logo y Nombre -->
    <header>
        <img src="ruta/a/tu-logo.png" alt="Logo de ALQUILER DE CASA AUTO Y MÁS">
        <h1>ALQUILER DE CASA AUTO Y MÁS</h1>
        <p>Por toda Cuba | Aceptamos Criptofull</p>
    </header>

    <!-- Selector de Roles -->
    <form id="role-selector" style="text-align: center; margin: 20px auto;">
        <label for="user-role">Selecciona tu rol:</label>
        <select id="user-role" onchange="toggleForm()">
            <option value="cliente">Cliente (Busco alquilar)</option>
            <option value="arrendatario">Arrendatario (Quiero publicar)</option>
        </select>
    </form>

    <!-- Formulario para Clientes -->
    <form id="cliente-form" action="#" method="post" enctype="multipart/form-data" style="display: none;">
        <h2>Buscar Alquiler</h2>
        <label for="tipo-busqueda">¿Qué estás buscando?</label>
        <select id="tipo-busqueda" name="tipo-busqueda">
            <option value="casa">Casa</option>
            <option value="auto">Auto</option>
        </select>

        <label for="localidad-busqueda">Localidad:</label>
        <input type="text" id="localidad-busqueda" name="localidad-busqueda" placeholder="Ejemplo: Centro Habana">

        <button type="submit">Buscar</button>
    </form>

    <!-- Formulario para Arrendatarios -->
    <form id="arrendatario-form" action="#" method="post" enctype="multipart/form-data" style="display: none;">
        <h2>Solicitar Publicación</h2>
        <p>Completa el formulario para solicitar la publicación de tu propiedad o vehículo.</p>

        <label for="tipo-publicacion">Tipo de Anuncio:</label>
        <select id="tipo-publicacion" name="tipo-publicacion">
            <option value="normal">Anuncio Normal ($5 USD - 7 días)</option>
            <option value="clasificado">Anuncio Clasificado ($10 USD - 15 días)</option>
            <option value="premium">Anuncio Premium ($20 USD - 30 días)</option>
        </select>

        <label for="descripcion">Descripción:</label>
        <textarea id="descripcion" name="descripcion" rows="4" placeholder="Describe tu propiedad o vehículo"></textarea>

        <label for="contacto">Datos de Contacto:</label>
        <input type="text" id="contacto" name="contacto" placeholder="Teléfono o correo electrónico">

        <div class="payment-section">
            <p>Una vez completado el formulario, contacta al soporte mediante WhatsApp para realizar el pago.</p>
            <a href="https://wa.me/TU_NUMERO_DE_WHATSAPP?text=Hola,%20quiero%20publicar%20una%20propiedad%20o%20vehículo." 
               target="_blank" 
               style="display: block; text-align: center; padding: 10px; background: #25D366; color: white; border-radius: 5px; text-decoration: none; font-size: 16px;">
                Contactar al Soporte por WhatsApp
            </a>
        </div>

        <button type="submit">Enviar Solicitud</button>
    </form>

    <!-- Sección de Publicaciones -->
    <section class="publicaciones">
        <h2>Anuncios Activos</h2>

        <!-- Ejemplo de Publicación Normal -->
        <div class="publicacion normal">
            <h4>Casa en Alquiler - Centro Habana</h4>
            <p><strong>Tipo:</strong> Anuncio Normal</p>
            <p><strong>Descripción:</strong> Casa de dos pisos con tres habitaciones, garaje y aire acondicionado.</p>
            <p><strong>Contacto:</strong> +53 XXXXXXXXX</p>
            <p><strong>Vigencia:</strong> 30 días restantes</p>
            <button onclick="renovarAnuncio('normal')">Renovar Anuncio</button>
            <button onclick="eliminarAnuncio('normal')">Eliminar Anuncio</button>
        </div>

        <!-- Ejemplo de Publicación Clasificada -->
        <div class="publicacion clasificado">
            <h4>Auto Toyota Corolla 2022</h4>
            <p><strong>Tipo:</strong> Anuncio Clasificado</p>
            <p><strong>Descripción:</strong> Auto en excelente estado, aire acondicionado, GPS incluido.</p>
            <p><strong>Contacto:</strong> +53 XXXXXXXXX</p>
            <p><strong>Vigencia:</strong> 15 días restantes</p>
            <button onclick="renovarAnuncio('clasificado')">Renovar Anuncio</button>
            <button onclick="eliminarAnuncio('clasificado')">Eliminar Anuncio</button>
        </div>

        <!-- Ejemplo de Publicación Premium -->
        <div class="publicacion premium">
            <h4>Apartamento en Vedado</h4>
            <p><strong>Tipo:</strong> Anuncio Premium</p>
            <p><strong>Descripción:</strong> Apartamento moderno con vista al mar, tres habitaciones, piscina privada.</p>
            <p><strong>Contacto:</strong> +53 XXXXXXXXX</p>
            <p><strong>Vigencia:</strong> 7 días restantes</p>
            <button onclick="renovarAnuncio('premium')">Renovar Anuncio</button>
            <button onclick="eliminarAnuncio('premium')">Eliminar Anuncio</button>
        </div>
    </section>

    <!-- Botones de Redes Sociales -->
    <div class="social-buttons">
        <a href="https://facebook.com/tupagina" target="_blank"><i class="fab fa-facebook"></i></a>
        <a href="https://instagram.com/tupagina" target="_blank"><i class="fab fa-instagram"></i></a>
        <a href="https://wa.me/TU_NUMERO_DE_WHATSAPP" target="_blank"><i class="fab fa-whatsapp"></i></a>
    </div>

    <!-- Footer -->
    <footer>
        <p>&copy; 2023 ALQUILER DE CASA AUTO Y MÁS</p>
        <p>Contacto: info@alquilerdecubafull.com | Teléfono: +53 XXXXXXXXX</p>
        <div>
            <a href="https://wa.me/TU_NUMERO_DE_WHATSAPP" target="_blank"><i class="fab fa-whatsapp"></i></a>
            <a href="https://facebook.com/tupagina" target="_blank"><i class="fab fa-facebook"></i></a>
            <a href="https://instagram.com/tupagina" target="_blank"><i class="fab fa-instagram"></i></a>
        </div>
    </footer>

    <!-- Font Awesome para íconos -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">

    <!-- Script para alternar entre roles -->
    <script>
        function toggleForm() {
            const role = document.getElementById("user-role").value;
            const clienteForm = document.getElementById("cliente-form");
            const arrendatarioForm = document.getElementById("arrendatario-form");

            if (role === "cliente") {
                clienteForm.style.display = "block";
                arrendatarioForm.style.display = "none";
            } else if (role === "arrendatario") {
                clienteForm.style.display = "none";
                arrendatarioForm.style.display = "block";
            }
        }

        // Función para renovar un anuncio
        function renovarAnuncio(tipo) {
            alert(`Renovando anuncio ${tipo}. Por favor, contacte al soporte para realizar el pago.`);
            window.location.href = `https://wa.me/TU_NUMERO_DE_WHATSAPP?text=Hola,%20quiero%20renovar%20mi%20anuncio%20${tipo}.`;
        }

        // Función para eliminar un anuncio
        function eliminarAnuncio(tipo) {
            if (confirm(`¿Estás seguro de que deseas eliminar tu anuncio ${tipo}?`)) {
                alert(`Anuncio ${tipo} eliminado exitosamente.`);
                // Aquí puedes añadir lógica para eliminar el anuncio del sistema
            }
        }
    </script>
</body>
</html>
