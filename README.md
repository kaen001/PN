<!DOCTYPE html>
<html lang="sv">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tävling – Vinn en Smartbox Frukost för 2</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      padding: 20px;
    }
    .container {
      background-color: #fff;
      max-width: 600px;
      margin: 0 auto;
      padding: 30px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    img.logo {
      max-width: 200px;
      display: block;
      margin: 0 auto 20px;
    }
    h1, p {
      text-align: center;
    }
    form {
      display: flex;
      flex-direction: column;
    }
    label {
      margin-top: 10px;
      font-weight: bold;
    }
    input, select, textarea {
      padding: 10px;
      margin-top: 5px;
      border-radius: 4px;
      border: 1px solid #ccc;
    }
    button {
      margin-top: 20px;
      background-color: #007BFF;
      color: white;
      padding: 12px;
      border: none;
      border-radius: 4px;
      cursor: pointer;
      font-size: 16px;
    }
    button:hover {
      background-color: #0056b3;
    }
    .checkbox-group {
      margin-top: 15px;
    }
  </style>
</head>
<body>
  <div class="container">
    <img src="FIRMA_LOGGA_URL" alt="Företagslogga" class="logo">
    <h1>Vinn en lyxig frukost för två!</h1>
    <p>Delta i vår utlottning genom att fylla i formuläret nedan. Tävlingen pågår under hela mässdagen.</p>
    <form action="#" method="POST">
      <label for="namn">Namn:</label>
      <input type="text" id="namn" name="namn" required>

      <label for="epost">E-post:</label>
      <input type="email" id="epost" name="epost" required>

      <label for="mobil">Mobilnummer:</label>
      <input type="tel" id="mobil" name="mobil" required>

      <label for="företag">Företag:</label>
      <input type="text" id="företag" name="företag">

      <label>Hur skulle det påverka ert företag att ha en enhetlig, digital beställningsprocess gentemot era leverantörer? (Du kan välja flera):</label>
      <div class="checkbox-group">
        <label><input type="checkbox" name="fraga" value="tid"> Vi skulle spara mycket tid och minska manuellt arbete</label><br>
        <label><input type="checkbox" name="fraga" value="kontroll"> Det skulle ge oss bättre kontroll och spårbarhet</label><br>
        <label><input type="checkbox" name="fraga" value="samarbete"> Det skulle förbättra samarbetet med våra leverantörer</label><br>
        <label><input type="checkbox" name="fraga" value="har_redan"> Vi har redan en sådan process på plats</label><br>
        <label><input type="checkbox" name="fraga" value="annat"> Annat</label>
      </div>

      <label for="kommentar">Övriga kommentarer (valfritt):</label>
      <textarea id="kommentar" name="kommentar" rows="3"></textarea>

      <div class="checkbox-group">
        <label><input type="checkbox" name="nyhetsbrev" required> Jag godkänner att mina uppgifter sparas och att jag kan få framtida nyhetsbrev från [Företagsnamn].</label>
      </div>

      <p style="font-size: 12px; margin-top: 10px;">Vi hanterar dina personuppgifter i enlighet med GDPR. Läs mer i vår <a href="#" target="_blank">integritetspolicy</a>.</p>

      <button type="submit">Skicka in och delta</button>
    </form>
  </div>
</body>
</html>
