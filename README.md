<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PDF Görüntüleyici</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f4f4f4;
        }
        .pdf-container {
            width: 80%;
            height: 90%;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        iframe {
            width: 100%;
            height: 100%;
            border: none;
        }
    </style>
</head>
<body>
    <div class="pdf-container">
        <iframe src="https://raw.githubusercontent.com/kullanici-adi/depo-adi/ana/AHMANBEK.pdf"></iframe>
    </div>
</body>
</html>
