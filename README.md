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
    width: 90%;
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

  /* Placeholder para chatbot */
  .chatbot-placeholder {
    margin-top: 2rem;
    background-color: #ff6f61;
    padding: 1rem 1.5rem;
    border-radius: 10px;
    color: white;
    font-weight: bold;
    font-size: 1.2rem;
    box-shadow: 0
