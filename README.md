<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Arco Iris</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <link rel="stylesheet" href="./stylesheet/style.css">
</head>
<body>
<!-- Header: contiene el logo y los iconos de usuario y menú -->
<header class="bg-light p-3 d-flex justify-content-between align-items-center">
    <!-- Logo de la tienda Arco Iris -->
    <img src="./img/Logo.png" alt="Arco Iris Logo" class="logo" width="110px">
    
    <!-- Iconos de usuario y menú, usando clases de Bootstrap Icons -->
    <div class="icons">
        <i class="bi bi-person-circle">
            <img src="./img/iconos/Icono Usuario.png" alt="icono Menu" width="40px">
        </i>
        <i class="bi bi-list">
            <img src="./img/iconos/Icono Menu.png" alt="icono usuario" width="40px">
        </i>
    </div>
</header>

    <!-- Slider de imágenes -->
    <div id="slider" class="carousel slide" data-ride="carousel">
        <ol class="carousel-indicators">
            <li data-target="#slider" data-slide-to="0" class="active"></li>
            <li data-target="#slider" data-slide-to="1"></li>
            <li data-target="#slider" data-slide-to="2"></li>
        </ol>
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img src="./img/Slider1.jpg" class="d-block w-100" alt="Imagen 1">
                <div class="carousel-caption d-none d-md-block">
                    <h5>Un arco de posibilidades
                    <br>en un solo lugar...</h5>
                </div>
            </div>
            <div class="carousel-item">
                <img src="./img/Slider2.jpg" class="d-block w-100" alt="Imagen 2">
                <div class="carousel-caption d-none d-md-block">
                    <h5>Un arco de posibilidades
                    <br>en un solo lugar...</h5>
                </div>
            </div>
            <div class="carousel-item">
                <img src="./img/Slider3.jpg" class="d-block w-100" alt="Imagen 3">
                <div class="carousel-caption d-none d-md-block">
                    <h5>Un arco de posibilidades
                    <br>en un solo lugar...</h5>
                </div>
            </div>
        </div>
        <a class="carousel-control-prev" href="#slider" role="button" data-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Anterior</span>
        </a>
        <a class="carousel-control-next" href="#slider" role="button" data-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Siguiente</span>
        </a>
    </div>

    <section class="descuentos">
        <h2>Descuentos</h2>
        <img src="./img/Descuentos.jpg" alt="Productos con descuento" class="img-fluid">
    </section>

    
    <div class="container-historia">
        <div class="right-panel">
            <img src="./img/Logo.png" alt="Logo" class="logo" width="546px">
            <img src="./img/Historia ArcoIris.jpg" alt="Imagen Vertical" class="img-vertical" height="768px">
            <p class="texto-justificado">Nosotras nos preocupamos por brindarte todas las herramientas para que crées tu mundo en papel.</p>
        </div>
    </div>



   <footer>
        <div class="footer-content">
            <div class="line"></div>
            <img src="./img/LogoFooter.png" alt="Arco Iris Logo">
            <div class="line"></div>
        </div>
        <div class="footer-bottom">
            <div class="social-icons">
                <a href="https://www.facebook.com/arcoiris.ti.vi"><i class="fab fa-facebook">
                    <img src="./img/iconos/Facebook Footer 1.png" alt="Facebook Icon" width="50px">
                </i></a>
                <a href="https://www.tiktok.com/@bd.airis"><i class="fab fa-tiktok"><img src="./img/iconos/TikTok Footer 1 .png" alt="TikTok Icon" width="50px"></i></a>
                <a href="https://www.instagram.com/arcoiris.ti.vi/?hl=es-la"><i class="fab fa-instagram">
                    <img src="./img/iconos/Instagram Footer 1.png" alt="Instagram Icon" width="50px">
                </i></a>
            </div>
            <div class="site-links">
                <a href="/escolar.html"><i class="fas fa-heart">
                    <img src="./img/iconos/Escolar 1.png" width="50px" alt="Escolar Icon">
                </i></a>
                <a href="/oficina.html"><i class="fas fa-envelope">
                    <img src="./img/iconos/Oficina 1.png" width="50px" alt="Oficina Icon">
                </i></a>
                <a href="/papeleria.html"><i class="fas fa-briefcase">
                    <img src="./img/iconos/Papeleria 1.png" width="50px" alt="Papeleria Icon">
                </i></a>
                <a href="/productos varios.html"><i class="fas fa-home">
                    <img src="./img/iconos/Varios 1.png" width="50px" alt="Varios Icon">
                </i></a>
            </div>
        </div>
    </footer> 



    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
