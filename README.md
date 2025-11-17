<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Registro de Problemas del Liceo</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: #f0f2f5;
            margin: 0;
            padding: 0;
        }

        header {
            background: #1a73e8;
            color: white;
            padding: 20px;
            text-align: center;
        }

        .container {
            max-width: 700px;
            margin: 30px auto;
            background: white;
            padding: 25px;
            border-radius: 12px;
            box-shadow: 0 0 15px rgba(0,0,0,0.1);
        }

        h2 {
            color: #333;
        }

        label {
            font-weight: bold;
        }

        input, textarea {
            width: 100%;
            padding: 12px;
            margin-top: 8px;
            margin-bottom: 15px;
            border-radius: 8px;
            border: 1px solid #ccc;
            background: #fafafa;
        }

        button {
            width: 100%;
            padding: 12px;
            background: #1a73e8;
            color: white;
            border: none;
            font-size: 16px;
            border-radius: 8px;
            cursor: pointer;
        }

        button:hover {
            background: #0c5bcc;
        }

        .pie {
            text-align: center;
            margin-top: 40px;
            font-size: 13px;
            color: #777;
        }

        .pie a {
            color: #1a73e8;
        }
    </style>
</head>
<body>

<header>
    <h1>Registro de Problemas del Liceo</h1>
    <p>Enviá tu sugerencia, queja o problema de forma anónima o con tu nombre.</p>
</header>

<div class="container">
    <h2>Formulario</h2>

    <label>Tu nombre (opcional):</label>
    <input type="text" placeholder="Anónimo">

    <label>Descripción del problema:</label>
    <textarea placeholder="Escribe aquí el problema o sugerencia..."></textarea>

    <button>Enviar problema</button>

</div>

<div class="pie">
    Página creada por estudiantes del liceo |
    <a href="#">Ver más proyectos</a>
</div>

</body>
</html>
