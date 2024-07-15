<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Práctica diseño menú</title>
    <link rel="stylesheet" href="index.css">
</head>
<body>
    <nav>
        <ul>
            <li><a href="#" class="Logotipo"> Logo </a></li>
        </ul>
        <ul>
            <div>
               <li><a href="#">Portafolio</a></li>
               <li><a href="#">Productos</a></li>
               <li><a href="#">Envíos</a></li>
               <li><a href="#">Acerca de</a></li>
               <li><a href="#">Contacto</a></li>
            </div>
            <div>
                <li><a href="#">Registrarse</a></li>
                <li><a href="#" class="login">Iniciar sesión</a></li>
            </div>
        </ul>
    </nav>
</body>
</html>

nav {
    border: 3px solid #000000; 
    display: flex;
    justify-content: space-between;
    padding: 21px 34px;
}

nav ul {
    display: flex;
    gap: 55px;
    list-style: none;
}

nav ul li a {
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    font-size: 24px;
    text-decoration: none;
}

nav ul li .Logotipo {
    background: #eeefa0;
    display: flex;
    padding: 16px 48px;
}

nav ul div {
    align-items: center;
    display: flex;
    gap: 21px;
}

nav ul div li .login {
    background: #0abe01;
    display: flex;
    padding: 16px 48px;
}
