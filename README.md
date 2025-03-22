
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Page d'Accueil</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f4f4f4;
            padding: 50px;
        }
        h1 {
            color: #333;
        }
        button {
            padding: 10px 20px;
            font-size: 16px;
            background-color: #007BFF;
            color: white;
            border: none;
            cursor: pointer;
        }
        button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <h1>Bienvenue sur ma page d'accueil</h1>
    <p>Ceci est un exemple de page HTML simple.</p>
    <button onclick="afficherMessage()">Cliquez-moi</button>
    
    <script>
        function afficherMessage() {
            alert("Bonjour et bienvenue !");
        }
    </script>
</body>
</html>
