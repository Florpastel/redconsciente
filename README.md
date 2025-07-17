<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Red Consciente - Ciberseguridad y prevención digital</title>
<style>
  /* Reset básico */
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
    color: #f0f0f0;
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 20px;
  }

  header {
    padding: 2rem 1rem;
    text-align: center;
  }

  header h1 {
    font-size: 3rem;
    color: #ff6f61;
    text-shadow: 1px 1px 5px rgba(255,111,97,0.8);
    animation: pulse 2.5s infinite;
  }

  header p {
    margin-top: 0.5rem;
    font-size: 1.2rem;
    color: #ffc8b0;
  }

  @keyframes pulse {
    0%, 100% { text-shadow: 1px 1px 5px rgba(255,111,97,0.8); }
    50% { text-shadow: 1px 1px 20px rgba(255,111,97,1); }
  }

  main {
    max-width: 900px;
    width: 100%;
    background: rgba(255, 255, 255, 0.05);
    border-radius: 15px;
    padding: 2rem;
    box-shadow: 0 0 15px rgba(255,111,97,0.6);
    margin-bottom: 3rem;
  }

  section {
    margin-bottom: 2rem;
  }

  section h2 {
    font-size: 2rem;
    margin-bottom: 1rem;
    color: #ff8b7d;
    border-bottom: 2px solid #ff6f61;
    padding-bottom: 0.3rem;
  }

  section p {
    font-size: 1.1rem;
    line-height: 1.5;
    color: #f0e6dc;
  }

  /* Imágenes con animación suave */
  .img-container {
    display: flex;
    justify-content: center;
    margin-top: 1rem;
    margin-bottom: 1rem;
  }

  .img-container img {
    max-width: 100%;
    height: auto;
    border-radius: 15px;
    box-shadow: 0 0 10px #ff6f61;
    animation: float 6s ease-in-out infinite;
  }

  @keyframes float {
    0%, 100% {
      transform: translateY(0);
      filter: drop-shadow(0 0 5px #ff6f61);
    }
    50% {
      transform: translateY(-15px);
      filter: drop-shadow(0 0 15px #ff6f61);
    }
  }

  /* Responsive */
  @media (max-width: 600px) {
    header h1 {
      font-size: 2.2rem;
    }

    main {
      padding: 1rem;
    }

    section h2 {
      font-size: 1.5rem;
    }
  }

</style>
</head>
<body>

<header>
  <h1>Red Consciente</h1>
  <p>Ciberseguridad, prevención de grooming y bullying digital</p>
</header>

<main>
  <section>
    <h2>¿Qué hacemos?</h2>
    <p>En Red Consciente ofrecemos educación y herramientas para que jóvenes, familias y escuelas puedan prevenir y actuar frente a problemáticas digitales como el grooming, sexting, ciberacoso y bullying.</p>
    <div class="img-container">
      <img src="https://images.unsplash.com/photo-1556740749-887f6717d7e4?auto=format&fit=crop&w=800&q=80" alt="Persona usando computadora con seguridad digital" />
    </div>
  </section>

  <section>
    <h2>Temáticas centrales</h2>
    <p>
      <strong>Grooming:</strong> Identificación y prevención de contactos inapropiados.<br />
      <strong>Ciberacoso:</strong> Cómo detectar y denunciar situaciones de acoso digital.<br />
      <strong>Sexting:</strong> Riesgos y consecuencias de compartir imágenes o mensajes íntimos.<br />
      <strong>Bullying digital:</strong> Estrategias para fomentar ambientes seguros y respetuosos.
    </p>
    <div class="img-container">
      <img src="https://images.unsplash.com/photo-1504384308090-c894fdcc538d?auto=format&fit=crop&w=800&q=80" alt="Grupo de adolescentes en conversación" />
    </div>
  </section>
</main>

</body>
</html>
