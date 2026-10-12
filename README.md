# mi-primer-proyecto
Mi primera web con GitHub y Copilot
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi primera web</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #121212;
            color: white;
            text-align: center;
            padding-top: 100px;
        }

        button {
            padding: 15px 30px;
            font-size: 18px;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            background: #0078d4;
            color: white;
        }

        button:hover {
            background: #005ea6;
        }

        #texto {
            margin-top: 30px;
            font-size: 24px;
        }
    </style>
</head>
<body>

    <h1>🚀 Mi primera web en GitHub</h1>

    <button onclick="saludar()">
        Pulsa aquí
    </button>

    <p id="texto"></p>

    <script>
        function saludar() {
            document.getElementById("texto").innerHTML =
                "¡Hola Miquel! Tu web funciona correctamente 🎉";
        }
    </script>

</body>
</html>
