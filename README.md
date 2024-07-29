<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Acuerdo de Usuario</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 20px; }
    h2 { color: #333; }
    p { font-size: 14px; }
  </style>
</head>
<body>
  <div>
    <h2>Acuerdo de Usuario</h2>
    <p>Al usar Llama Carlos, reconoces y aceptas los riesgos asociados con compartir información personal de salud en una plataforma que no cumple con HIPAA. Aceptas nuestros términos y condiciones, y nuestra política de privacidad.</p>
    <input type="checkbox" id="agreeCheckbox" required> Acepto los términos y condiciones.
    <button onclick="submitForm()">Enviar</button>
  </div>
  <script>
    function submitForm() {
      if (document.getElementById('agreeCheckbox').checked) {
        alert('¡F
