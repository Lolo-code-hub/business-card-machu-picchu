# business-card-machu-picchu
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Business Card - Machu Picchu</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f4f4f4;
            font-family: Arial, sans-serif;
        }
        .card {
            width: 400px;
            background: #fff;
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            overflow: hidden;
        }
        .card-header {
            height: 200px;
            background: url('https://upload.wikimedia.org/wikipedia/commons/e/eb/Machu_Picchu%2C_Peru.jpg') no-repeat center/cover;
        }
        .card-content {
            padding: 20px;
            text-align: center;
        }
        .title {
            font-size: 22px;
            font-weight: bold;
            color: #333;
        }
        .info {
            font-size: 14px;
            margin: 10px 0;
            color: #555;
        }
        .card-footer {
            background: #f1f1f1;
            padding: 15px;
            text-align: center;
        }
    </style>
</head>
<body>
    <div class="card">
        <div class="card-header"></div>
        <div class="card-content">
            <div class="title">Machu Picchu, Peru</div>
            <div class="info">Patrimoniu UNESCO | Altitudine: 2,430m</div>
            <div class="info">Un sit arheologic spectaculos al civilizației incașe, situat în Munții Anzi.</div>
        </div>
        <div class="card-footer">
            <p>📍 Locație: Regiunea Cusco, Peru</p>
            <p>📅 Perioadă recomandată: Mai - Octombrie</p>
            <p>🔗 <a href="https://whc.unesco.org/en/list/274/" target="_blank">Mai multe informații</a></p>
        </div>
    </div>
</body>
</html>
