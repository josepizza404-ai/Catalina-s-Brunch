<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Catalina’s Brunch</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family:'Poppins',sans-serif;
    background:#f8f6f2;
    color:#333;
}

header{
    background:linear-gradient(135deg,#6bb6d9,#8fd3f4);
    color:white;
    text-align:center;
    padding:60px 20px;
}

header h1{
    font-size:3rem;
    letter-spacing:2px;
}

header p{
    margin-top:10px;
    font-size:1.1rem;
}

.container{
    max-width:1100px;
    margin:auto;
    padding:40px 20px;
}

.menu-card{
    background:white;
    border-radius:20px;
    overflow:hidden;
    box-shadow:0 10px 30px rgba(0,0,0,0.1);
}

.menu-card img{
    width:100%;
    display:block;
}

.info{
    text-align:center;
    padding:35px 20px;
}

.info h2{
    color:#6bb6d9;
    margin-bottom:15px;
    font-size:2rem;
}

.info p{
    margin-bottom:20px;
    color:#666;
}

.buttons{
    display:flex;
    justify-content:center;
    gap:15px;
    flex-wrap:wrap;
}

.buttons a{
    text-decoration:none;
    padding:14px 24px;
    border-radius:12px;
    font-weight:600;
    transition:0.3s;
}

.whatsapp{
    background:#25D366;
    color:white;
}

.facebook{
    background:#1877F2;
    color:white;
}

.buttons a:hover{
    transform:translateY(-3px);
}

footer{
    text-align:center;
    padding:25px;
    color:#777;
    font-size:14px;
}
</style>
</head>

<body>

<header>
    <h1>Catalina’s Brunch</h1>
    <p>Desayunos y brunch gourmet</p>
</header>

<div class="container">

    <div class="menu-card">

        <!-- CAMBIA menu.jpg POR TU IMAGEN -->
        <img src="menu.jpg" alt="Menú Catalina’s Brunch">

        <div class="info">
            <h2>Bienvenidos</h2>

            <p>
                Disfruta de nuestros deliciosos chilaquiles, hot cakes,
                desayunos especiales y bebidas gourmet.
            </p>

            <div class="buttons">
                <a class="whatsapp" href="https://wa.me/521XXXXXXXXXX">
                    WhatsApp
                </a>

                <a class="facebook" href="#">
                    Facebook
                </a>
            </div>
        </div>

    </div>

</div>

<footer>
    © 2026 Catalina’s Brunch
</footer>

</body>
</html>
