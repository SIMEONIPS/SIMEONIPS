<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Certificado Médico Ocupacional</title>
  <style>
    body {
      margin: 0;
      padding: 20px;
      font-family: Arial, sans-serif;
      background-color: #f5f5f5;
      text-align: center;
    }
    .cert-container {
      background-color: white;
      padding: 20px;
      max-width: 500px;
      margin: auto;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    img.certificado {
      width: 100%;
      border-radius: 10px;
    }
    .qr {
      margin-top: 20px;
    }
    .qr img {
      width: 120px;
      height: 120px;
    }
    .footer {
      margin-top: 10px;
      font-size: 12px;
      color: #555;
    }
  </style>
</head>
<body>
  <div class="cert-container">
    <img src="certificado.jpg" alt="Certificado" class="certificado"/>
    <div class="qr">
      <img src="https://api.qrserver.com/v1/create-qr-code/?data=https://simeonips.github.io/SIMEONIPS/&size=120x120" alt="Código QR" />
    </div>
    <div class="footer">
      2025 © Derechos reservados. <br />
      <a href="https://www.simeon.com.co">www.simeon.com.co</a>
   
