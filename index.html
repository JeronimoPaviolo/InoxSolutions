<!DOCTYPE html>  
<html lang="es">  
<head>  
  <meta charset="UTF-8">  
  <meta name="viewport" content="width=device-width, initial-scale=1.0">  
  <title>Cotizador | Acero Inoxidable</title>  
  <style>  
    :root {  
      --bg: #f8f9fa;  
      --card-bg: #ffffff;  
      --text: #1a1a1a;  
      --accent: #4a5568;  
      --border: #e2e8f0;  
      --radius: 8px;  
    }  
  
    body {  
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;  
      background-color: var(--bg);  
      color: var(--text);  
      display: flex;  
      justify-content: center;  
      padding: 40px 20px;  
      margin: 0;  
    }  
  
    .container {  
      width: 100%;  
      max-width: 480px;  
      background: var(--card-bg);  
      padding: 32px;  
      border-radius: var(--radius);  
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.05);  
      border: 1px solid var(--border);  
    }  
  
    h1 {  
      font-size: 1.5rem;  
      font-weight: 600;  
      letter-spacing: -0.5px;  
      margin-bottom: 8px;  
    }  
  
    p.subtitle {  
      color: #666;  
      font-size: 0.9rem;  
      margin-bottom: 24px;  
    }  
  
    .form-group {  
      margin-bottom: 20px;  
    }  
  
    label {  
      display: block;  
      font-size: 0.85rem;  
      font-weight: 600;  
      margin-bottom: 6px;  
      text-transform: uppercase;  
      letter-spacing: 0.5px;  
    }  
  
    select, input {  
      width: 100%;  
      padding: 12px;  
      border: 1px solid var(--border);  
      border-radius: var(--radius);  
      font-size: 1rem;  
      box-sizing: border-box;  
      outline: none;  
      transition: border-color 0.2s;  
    }  
  
    select:focus, input:focus {  
      border-color: var(--accent);  
    }  
  
    .grid-2 {  
      display: grid;  
      grid-template-columns: 1fr 1fr;  
      gap: 12px;  
    }  
  
    .result-box {  
      margin-top: 28px;  
      padding: 20px;  
      background: #f1f5f9;  
      border-radius: var(--radius);  
      text-align: center;  
    }  
  
    .result-box span {  
      display: block;  
      font-size: 0.85rem;  
      color: #64748b;  
    }  
  
    .price {  
      font-size: 2rem;  
      font-weight: 700;  
      color: var(--text);  
      margin-top: 4px;  
    }  
  
    .btn-whatsapp {  
      display: block;  
      width: 100%;  
      padding: 14px;  
      margin-top: 16px;  
      background-color: #000;  
      color: #fff;  
      text-align: center;  
      text-decoration: none;  
      border-radius: var(--radius);  
      font-weight: 600;  
      box-sizing: border-box;  
      transition: opacity 0.2s;  
    }  
  
    .btn-whatsapp:hover {  
      opacity: 0.85;  
    }  
  </style>  
</head>  
<body>  
  
<div class="container">  
  <h1>Cotizador de Acero</h1>  
  <p class="subtitle">Calcula el presupuesto estimado para tu proyecto a medida.</p>  
  
  <div class="form-group">  
    <label for="tipo">Tipo de Trabajo</label>  
    <select id="tipo" onchange="calcular()">  
      <option value="parrilla">Parrilla a medida</option>  
      <option value="mesada">Mesada industrial</option>  
      <option value="baranda">Baranda / Pasamanos</option>  
    </select>  
  </div>  
  
  <div class="form-group grid-2">  
    <div>  
      <label for="ancho">Ancho (cm)</label>  
      <input type="number" id="ancho" value="80" oninput="calcular()">  
    </div>  
    <div>  
      <label for="largo">Largo / Prof. (cm)</label>  
      <input type="number" id="largo" value="50" oninput="calcular()">  
    </div>  
  </div>  
  
  <div class="form-group">  
    <label for="calidad">Calidad del Acero</label>  
    <select id="calidad" onchange="calcular()">  
      <option value="1">AISI 430 (Uso estándar interior)</option>  
      <option value="1.3">AISI 304 (Alta resistencia / Exterior)</option>  
    </select>  
  </div>  
  
  <div class="result-box">  
    <span>Estimado aproximado</span>  
    <div class="price" id="precio">$0</div>  
  </div>  
  
  <a id="btn-ws" href="#" target="_blank" class="btn-whatsapp">Solicitar Confirmación por WhatsApp</a>  
</div>  
  
<script>  
  // Tarifas base por cm2 según tipo de trabajo  
  const preciosBase = {  
    parrilla: 0.8,  
    mesada: 0.6,  
    baranda: 0.4  
  };  
  
  const miTelefonoWhatsApp = "5491112345678"; // Reemplaza con tu número (código de país + área + número)  
  
  function calcular() {  
    const tipo = document.getElementById('tipo').value;  
    const ancho = parseFloat(document.getElementById('ancho').value) || 0;  
    const largo = parseFloat(document.getElementById('largo').value) || 0;  
    const multiplicadorCalidad = parseFloat(document.getElementById('calidad').value);  
  
    const area = ancho * largo;  
    const total = Math.round(area * preciosBase[tipo] * multiplicadorCalidad);  
  
    // Formatear precio  
    document.getElementById('precio').innerText = `$ ${total.toLocaleString('es-AR')}`;  
  
    // Crear mensaje predefinido para WhatsApp  
    const textoWhatsApp = encodeURIComponent(  
      `¡Hola! Hice una cotización en la web para una *${tipo}* de *${ancho}x${largo} cm*. El estimado fue de *$${total.toLocaleString('es-AR')}*. Me gustaría coordinar detalles.`  
    );  
      
    document.getElementById('btn-ws').href = `https://wa.me/${miTelefonoWhatsApp}?text=${textoWhatsApp}`;  
  }  
  
  // Inicializar cálculo al cargar  
  calcular();  
</script>  
  
</body>  
</html>  
