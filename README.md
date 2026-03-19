# DINO-a-las-drogas-
Información contra las drogas 
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Recuadros</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #0f172a;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        .contenedor {
            display: grid;
            grid-template-columns: repeat(3, 150px);
            gap: 15px;
        }

        .cuadro {
            width: 150px;
            height: 150px;
            background-color: #1e293b;
            color: white;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            border-radius: 10px;
            font-size: 14px;
            font-weight: bold;
            box-shadow: 0 0 10px rgba(0,0,0,0.5);
        }
    </style>
</head>
<body>

<div class="contenedor">
    <div class="cuadro">Metanfetamina</div>
    <div class="cuadro">Éxtasis</div>
    <div class="cuadro">Inhalantes</div>
    <div class="cuadro">Poppers</div>
    <div class="cuadro">Cannabis</div>
    <div class="cuadro">Vape</div>
    <div class="cuadro">Nicotina</div>
    <div class="cuadro">Alcohol</div>
    <div class="cuadro">Fentanilo</div>
</div>

</body>
</html>