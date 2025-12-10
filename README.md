<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Prueba Git y Laravel — Marco Antonio Valerio</title>
  <style>
    :root {
      --bg: #0f172a;
      --bg2: #1e293b;
      --accent: #38bdf8;
      --text: #e5e7eb;
      --muted: #94a3b8;
      --card: #0b1220;
      --shadow: rgba(0,0,0,0.35);
    }
    * { box-sizing: border-box; }
    body {
      margin: 0;
      min-height: 100vh;
      display: grid;
      place-items: center;
      background: radial-gradient(1000px 500px at 20% 10%, var(--bg2), var(--bg));
      color: var(--text);
      font-family: system-ui, -apple-system, Segoe UI, Roboto, Ubuntu, Cantarell, "Helvetica Neue", Arial, "Noto Sans", sans-serif;
    }
    .card {
      width: min(720px, 92vw);
      background: linear-gradient(180deg, rgba(56,189,248,0.08), rgba(56,189,248,0) 30%), var(--card);
      border: 1px solid rgba(148,163,184,0.25);
      border-radius: 16px;
      box-shadow: 0 10px 30px var(--shadow);
      padding: 28px 28px 24px;
      backdrop-filter: blur(6px);
    }
    .badge {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      font-weight: 600;
      letter-spacing: 0.2px;
      color: var(--accent);
      background: rgba(56,189,248,0.12);
      border: 1px solid rgba(56,189,248,0.35);
      padding: 6px 10px;
      border-radius: 999px;
    }
    .title {
      margin: 16px 0 8px;
      font-size: clamp(24px, 4vw, 36px);
      line-height: 1.15;
      font-weight: 800;
    }
    .subtitle {
      margin: 0 0 12px;
      font-size: clamp(14px, 2.5vw, 18px);
      color: var(--muted);
    }
    .name {
      margin: 18px 0 0;
      font-size: clamp(16px, 3vw, 22px);
      font-weight: 700;
      color: var(--accent);
      letter-spacing: 0.3px;
    }
    .footer {
      margin-top: 18px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      border-top: 1px dashed rgba(148,163,184,0.3);
      padding-top: 14px;
      color: var(--muted);
      font-size: 14px;
    }
    .pill {
      padding: 4px 10px;
      border-radius: 999px;
      border: 1px solid rgba(148,163,184,0.35);
      background: rgba(148,163,184,0.12);
    }
  </style>
</head>
<body>
  <main class="card" role="main" aria-label="Mensaje de prueba">
    <span class="badge" aria-label="Estado">
      ✓ Demo
      <span class="pill">Git + Laravel</span>
    </span>

    <h1 class="title">Esta es una prueba de mi Git y Laravel</h1>
    <p class="subtitle">Página de demostración con estilos HTML simples.</p>
    <p class="name">"Marco Antonio Valerio"</p>

    <div class="footer">
      <span>Construido con HTML + CSS</span>
      <span class="pill">v1.0</span>
    </div>
  </main>
</body>
</html>
