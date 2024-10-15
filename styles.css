<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contacto Espacial</title>
  <style>
    /* Estilo básico para la página */
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #000;
      color: #fff;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      min-height: 100vh;
      background-image: url('https://source.unsplash.com/1600x900/?space');
      background-size: cover;
      background-repeat: no-repeat;
      background-attachment: fixed;
    }

    h1 {
      font-size: 3em;
      text-align: center;
      margin-top: 0.5em;
    }

    p {
      text-align: center;
      max-width: 600px;
      margin: 0 auto;
      font-size: 1.2em;
    }

    /* Estilo del formulario */
    .formulario {
      background-color: rgba(0, 0, 0, 0.8);
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0px 0px 20px rgba(255, 255, 255, 0.3);
      width: 100%;
      max-width: 400px;
      margin-top: 1em;
    }

    .formulario input, .formulario textarea, .formulario button {
      width: 100%;
      padding: 10px;
      margin-top: 10px;
      border: none;
      border-radius: 5px;
      font-size: 1em;
    }

    .formulario input, .formulario textarea {
      background-color: #333;
      color: #fff;
      resize: none;
    }

    .formulario button {
      background-color: #1e90ff;
      color: #fff;
      font-weight: bold;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }

    .formulario button:hover {
      background-color: #0b60a7;
    }
  </style>
</head>
<body>

  <h1>Bienvenido al Espacio</h1>
  <p>Únete a nuestra misión exploratoria y descubre los misterios del universo. Completa el formulario a continuación para ser parte de la aventura.</p>

  <!-- Formulario de contacto -->
  <div class="formulario">
    <form id="contactForm">
      <label for="name">Nombre:</label>
      <input type="text" id="name" name="name" required placeholder="Tu nombre">
      
      <label for="email">Correo electrónico:</label>
      <input type="email" id="email" name="email" required placeholder="Tu correo electrónico">
      
      <label for="message">Mensaje:</label>
      <textarea id="message" name="message" rows="5" required placeholder="Escribe tu mensaje aquí..."></textarea>
      
      <button type="submit">Enviar</button>
    </form>
  </div>

  <script>
    // Validación simple de formulario y alertas
    document.getElementById('contactForm').addEventListener('submit', function(e) {
      e.preventDefault(); // Evitar el envío tradicional

      // Captura los valores del formulario
      const name = document.getElementById('name').value;
      const email = document.getElementById('email').value;
      const message = document.getElementById('message').value;

      // Validación básica
      if (name === '' || email === '' || message === '') {
        alert('Por favor, completa todos los campos.');
        return;
      }

      // Mensaje de confirmación
      alert('Gracias por contactarnos, ' + name + '. Te responderemos pronto.');
      
      // Limpiar el formulario
      document.getElementById('contactForm').reset();
    });
  </script>
</body>
</html>
