<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Perfil</title>

    <style>
        body{
            font-family: Arial, sans-serif;
            background-color: #f0f2f5;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        .perfil{
            background: white;
            width: 320px;
            padding: 20px;
            border-radius: 15px;
            text-align: center;
            box-shadow: 0px 4px 10px rgba(0,0,0,0.2);
        }

        .perfil img{
            width: 120px;
            height: 120px;
            border-radius: 50%;
            border: 4px solid #3498db;
        }

        .perfil h1{
            margin: 15px 0 5px;
            color: #333;
        }

        .perfil p{
            color: #666;
            font-size: 14px;
        }

        .boton{
            display: inline-block;
            margin-top: 15px;
            padding: 10px 20px;
            background: #3498db;
            color: white;
            text-decoration: none;
            border-radius: 8px;
            transition: 0.3s;
        }

        .boton:hover{
            background: #2980b9;
        }
    </style>
</head>
<body>

    <div class="perfil">
        <img src="https://via.placeholder.com/120" alt="Foto de perfil">

        <h1>Carlos Borja</h1>

        <p>Estudiante de Desarrollo de Software</p>

        <p>Me gusta la programación, las bases de datos y crear aplicaciones.</p>

        <a href="#" class="boton">Seguir</a>
    </div>

</body>
</html>
