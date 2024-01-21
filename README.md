<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      font-family: 'Arial', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
    }
    .container {
      margin: 20px auto;
      max-width: 800px;
      padding: 30px;
      background-color: #fff;
      box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
      border-radius: 8px;
    }
    h1, h2, p {
      color: #333;
    }
    h1 {
      color: #3498db;
      text-align: center;
    }
    h2 {
      margin-top: 20px;
      border-bottom: 2px solid #3498db;
      padding-bottom: 5px;
    }
    .toggle-button {
      background-color: #3498db;
      color: #fff;
      padding: 8px 12px;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }
    .hidden {
      display: none;
    }
  </style>
  <title>Manual de Bienvenida</title>
</head>
<body>
  <div class="container">
    <h1>Bienvenido a [Nombre de la Empresa]</h1>
    <p>Estamos emocionados de darte la bienvenida a nuestro equipo. Este manual tiene como objetivo proporcionarte la información 
	necesaria para que tu integración a la empresa sea exitosa. Si tienes alguna pregunta, no dudes en preguntar a tu supervisor
	o al departamento de Recursos Humanos.</p>
	
	<h2>1. Introducción</h2>
    <button class="toggle-button" onclick="toggleContent('intro')">Mostrar/ocultar</button>
    <p id="intro" class="hidden">En [Nombre de la Empresa], nos dedicamos a [descripción breve y contexto de la empresa].</p>
	
    <h2>2. Misión</h2>
    <button class="toggle-button" onclick="toggleContent('mision')">Mostrar/ocultar</button>
    <p id="mision" class="hidden">Trabajamos para[descripción breve de la misión de la empresa]</p>
	
	<h2>3. Visión </h2>
    <button class="toggle-button" onclick="toggleContent('visión')">Mostrar/ocultar</button>
    <p id="visión" class="hidden">Buscamos [Descripción breve de la visión de la empresa]</p>
    
    <h2>4. Políticas y Normativas</h2>
    <button class="toggle-button" onclick="toggleContent('policies')">Mostrar/ocultar</button>
    <p id="policies" class="hidden"> Horarios de Trabajo: Conoce los horarios de trabajo establecidos y las politicas de puntualidad. 
	Vestimenta: Entiende las expectativas en cuanto al código de vestimenta.
	Te recomendamos revisar detenidamente nuestras políticas internas y normativas para asegurarte de un ambiente de trabajo respetuoso y eficiente.</p>
    
    <!-- Repite el patrón para otros puntos -->
    <h2>5. Organigrama</h2>
    <button class="toggle-button" onclick="toggleContent('organigrama')">Mostrar/ocultar</button>
    <p id="organigrama" class="hidden">Encuentra tu lugar en nuestra estructura organizativa [Incluir organigrama si es posible]</p>
	
	<h2>6. Beneficios y Recursos </h2>
    <button class="toggle-button" onclick="toggleContent('recursos')">Mostrar/ocultar</button>
    <p id="recursos" class="hidden">Salarios y Pagos: Información sobre cómo se procesan los salarios y beneficios adicionales.
	Seguridad Social: Detalles sobre los beneficios de seguridad social disponibles.</p>
	
	<h2>7. Entorno Laboral. </h2>
    <button class="toggle-button" onclick="toggleContent('Entorno')">Mostrar/ocultar</button>
    <p id="Entorno" class="hidden">Cultura Organizacional: Descubre la cultura que valoramos y fomentamos en nuestra empresa.
	Comunicación: Métodos y Canales dentro de la empresa.</p>
	
	<h2>8. Desarrollo profesional </h2>
    <button class="toggle-button" onclick="toggleContent('Desarrollo')">Mostrar/ocultar</button>
    <p id="Desarrollo" class="hidden">Programas de Formación: Oportunidades para mejorar tus habilidades y conocimientos.
	Evaluaciones de Desempeño: Proceso de evaluación y retroalimentación.</p>
	
	<h2>9. Contactos Utiles </h2>
    <button class="toggle-button" onclick="toggleContent('contacto')">Mostrar/ocultar</button>
    <p id="contacto" class="hidden">Supervisor: [Nombre y contacto del supervirsor], Recursos Humanos: [Detalles para contactar al departamento de recursos humanos].</p>
	
	<p>¡Esperamos que encuentres esta información útil! Estamos aquí para apoyarte en cada paso de tu viaje en [Nombre de la empresa] ¡Bienvenido a la familia!</p>

  </div>

  <script>
    function toggleContent(sectionId) {
      var content = document.getElementById(sectionId);
      content.classList.toggle('hidden');
    }
  </script>
</body>
</html>
