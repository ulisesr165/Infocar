<!DOCTYPE html><html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Infocar | Información Automotriz Profesional</title>
  <meta name="description" content="Infocar: diagramas eléctricos, manuales automotrices, ECU, transmisiones y diagnóstico profesional. Información inmediata para técnicos y talleres." />  <!-- SEO Básico -->  <meta name="keywords" content="diagramas eléctricos, manuales automotrices, información automotriz, ECU, diagnóstico automotriz, infocar" />  <!-- Estilos -->  <style>
    :root {
      --bg: #0c0f14;
      --bg-dark: #080a0f;
      --primary: #e63946;
      --secondary: #1f2937;
      --text: #e5e7eb;
      --muted: #9ca3af;
      --accent: #22c55e;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    body {
      background: linear-gradient(rgba(0,0,0,.65), rgba(0,0,0,.85)), url('https://images.unsplash.com/photo-1515923167421-9a1f83f41a35?auto=format&fit=crop&w=1600&q=80') center/cover no-repeat fixed;
      color: var(--text);
    }

    a { text-decoration: none; color: inherit; }

    header {
      padding: 60px 20px 80px;
      text-align: center;
      background: rgba(0,0,0,.55);
    }

    header h1 {
      font-size: 2.6rem;
      letter-spacing: 1px;
    }

    header h1 span {
      color: var(--primary);
    }

    header p {
      margin-top: 15px;
      font-size: 1.1rem;
      color: var(--muted);
      max-width: 720px;
      margin-left: auto;
      margin-right: auto;
    }

    .cta {
      margin-top: 30px;
      display: inline-block;
      background: var(--primary);
      padding: 15px 30px;
      border-radius: 8px;
      font-weight: bold;
      transition: transform .2s, box-shadow .2s;
    }

    .cta:hover {
      transform: scale(1.05);
      box-shadow: 0 0 25px rgba(230,57,70,.6);
    }

    section {
      padding: 70px 20px;
