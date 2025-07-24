<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Mi Perfil GitHub - Hades</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Inter', sans-serif;
      background: #0f172a;
      color: #f1f5f9;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 2rem;
    }
    .container {
      max-width: 800px;
      width: 100%;
      text-align: center;
    }
    img.avatar {
      width: 150px;
      border-radius: 50%;
      margin-bottom: 1rem;
      border: 3px solid #38bdf8;
    }
    h1 {
      margin: 0.5rem 0;
      font-size: 2.2rem;
    }
    p.bio {
      font-size: 1.1rem;
      color: #94a3b8;
    }
    .links a {
      display: inline-block;
      margin: 0.5rem;
      padding: 0.6rem 1.2rem;
      border-radius: 8px;
      background-color: #1e293b;
      color: #38bdf8;
      text-decoration: none;
      transition: 0.2s ease;
    }
    .links a:hover {
      background-color: #0f172a;
      border: 1px solid #38bdf8;
    }
  </style>
</head>
<body>
  <div class="container">
    <img class="avatar" src="https://avatars.githubusercontent.com/u/00000000?v=4" alt="Tu Foto de Perfil">
    <h1>Hola, soy Hades 👋</h1>
    <p class="bio">
      Desarrollador junior apasionado por la tecnología, aprendiendo Next.js, React y programación en general.
      Amante del anime y la música relajante. 🎧
    </p>

    <div class="links">
      <a href="https://github.com/tuusuario" target="_blank">GitHub</a>
      <a href="https://www.linkedin.com/in/tuusuario" target="_blank">LinkedIn</a>
      <a href="mailto:tuemail@example.com">Contáctame</a>
      <a href="https://tuportafolio.com" target="_blank">Portafolio</a>
    </div>
  </div>
</body>
</html>

