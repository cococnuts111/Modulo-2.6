<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Perfil</title>

    <style>
        body{
            font-family: Arial, sans-serif;
            background: #1e1e2f;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }

        .perfil{
            background: white;
            width: 320px;
            padding: 25px;
            border-radius: 15px;
            text-align: center;
            box-shadow: 0 5px 15px rgba(0,0,0,0.3);
        }

        .perfil img{
            width: 120px;
            height: 120px;
            border-radius: 50%;
            border: 4px solid #4a90e2;
        }

        h1{
            margin: 15px 0 5px;
            color: #333;
        }

        p{
            color: #666;
            font-size: 15px;
        }

        .boton{
            display: inline-block;
            margin-top: 15px;
            padding: 10px 20px;
            background: #4a90e2;
            color: white;
            text-decoration: none;
            border-radius: 8px;
            transition: 0.3s;
        }

        .boton:hover{
            background: #357abd;
        }
    </style>
</head>
<body>

    <div class="perfil">
        <img src="https://i.imgur.com/2DhmtJ4.jpg" alt="Foto de perfil">

        <h1>Tu Nombre</h1>

        <p>Estudiante de Desarrollo de Software 💻</p>

        <p>Me gusta la programación, las apps y las bases de datos.</p>

        <a href="#" class="boton">Seguir</a>
    </div>

</body>
</html>
