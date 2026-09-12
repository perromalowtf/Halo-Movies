<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mi Tarjeta Digital</title>
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
      background-color: #0f172a;
      color: #f8fafc;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      padding: 20px;
    }
    .card {
      background-color: #1e293b;
      width: 100%;
      max-width: 400px;
      padding: 30px 20px;
      border-radius: 20px;
      text-align: center;
      box-shadow: 0 10px 25px rgba(0,0,0,0.3);
    }
    .avatar {
      width: 100px;
      height: 100px;
      border-radius: 50%;
      object-fit: cover;
      margin-bottom: 15px;
      border: 3px solid #38bdf8;
    }
    h1 { font-size: 1.5rem; margin-bottom: 5px; }
    p.subtitle { color: #94a3b8; font-size: 0.95rem; margin-bottom: 25px; }
    .links { display: flex; flex-direction: column; gap: 12px; }
    .btn {
      display: block;
      background-color: #334155;
      color: #fff;
      text-decoration: none;
      padding: 14px 20px;
      border-radius: 12px;
      font-weight: 600;
      transition: all 0.2s ease;
      border: 1px solid #475569;
    }
    .btn:hover, .btn:active {
      background-color: #38bdf8;
      color: #0f172a;
    }
  </style>
</head>
<body>

  <div class="card">
    <!-- Cambia la URL de la imagen por tu foto o logo -->
    <img class="avatar" src="https://via.placeholder.com/100" alt="Foto de perfil">
    
    <h1>Tu Nombre o Marca</h1>
    <p class="subtitle">Especialidad / Descripción breve</p>

    <div class="links">
      <!-- Sustituye los enlaces (#) por tus URLs reales -->
      <a href="https://wa.me/TU_NUMERO" class="btn" target="_blank">💬 Enviar WhatsApp</a>
      <a href="https://instagram.com/TU_USUARIO" class="btn" target="_blank">📸 Instagram</a>
      <a href="mailto:tu-correo@email.com" class="btn">✉️ Enviar Correo</a>
      <a href="https://tusitio.com" class="btn" target="_blank">🌐 Sitio Web / Portafolio</a>
    </div>
  </div>

</body>
</html>
