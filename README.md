# ojedajacqueline.github.io
pagina estatica
<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0 user-scalable=no">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css" integrity="sha512-KfkfwYDsLkIlwQp6LFnl8zNdLGxu9YAA1QvwINks4PhcElQSvqcyVLLD9aMhXd13uQjoXtEKNosOWaZqXgel0g==" crossorigin="anonymous" referrerpolicy="no-referrer"
    />
    <link rel="stylesheet" href="estilo.css">
    <title>LP Desarrollador Web</title>
</head>

<body>
    <!-- SECCION I N I C I O -->
    <section id="inicio">
        <div class="contenido">
            <header>
                <div class="contenido-header">
                    <h1>/LP/</h1>
                    <nav id="nav" class="">
                        <ul id="links">
                            <li><a href="#inicio" class="seleccionado" onclick="seleccionar(this)">INICIO</a></li>
                            <li><a href="#sobremi" onclick="seleccionar(this)">SOBRE MI</a></li>
                            <li><a href="#servicios" onclick="seleccionar(this)">SERVICIOS</a></li>
                            <li><a href="#portfolio" onclick="seleccionar(this)">PORTFOLIO</a></li>
                            <li><a href="#contacto" onclick="seleccionar(this)">CONTACTO</a></li>
                        </ul>
                    </nav>

                    <!-- Icono del menu responsive -->
                    <div id="icono-nav" onclick="responsiveMenu()">
                        <i class="fa-solid fa-bars"></i>
                    </div>


                    <div class="redes">
                        <a href="#"><i class="fa-brands fa-youtube"></i></a>
                        <a href="#"><i class="fa-brands fa-facebook"></i></a>
                        <a href="#"><i class="fa-brands fa-instagram-square"></i></a>
                    </div>
                </div>
            </header>
            <div class="presentacion">
                <p class="bienvenida">Bienvenidos</p>
                <h2>Soy <span>Ojeda Jacqueline</span>, Desarrollador Web</h2>
                <p class="descripcion">Lorem ipsum dolor sit amet consectetur adipisicing elit. Soluta, </p>
                <a href="#portfolio">Ir a Portafolio</a>
            </div>
        </div>
    </section>

    <!-- SECCION S O B R E M I -->
    <section id="sobremi">
        <div class="contenedor-foto">
            <img src="img/CCC.jpg" alt="">
        </div>
        <div class="sobremi">
            <p class="titulo-seccion">Sobre Mi</p>
            <h2>Hola, Soy <span>Jacqueline Ojeda</span> </h2>
            <h3>Desarrollador Web</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consectetur reprehenderit voluptatibus blanditiis nulla adipisci iste fuga expedita, ea exercitationem dicta, similique rem, atque soluta recusandae ipsam autem. Sapiente, quo ducimus?</p>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Porro nam a beatae natus.</p>
            <a href="#">Descargar CV</a>
        </div>
    </section>

    <!-- SECCION S E R V I C I O S -->
    <section id="servicios">
        <h3 class="titulo-seccion">MIS SERVICIOS</h3>
        <div class="fila">
            <div class="servicio">
                <span class="icono"> <i class="fa-solid fa-code"></i></span>
                <h4>Diseño de Sitios Web</h4>
                <hr>
                <ul class="servicios-tag">
                    <li>Web</li>
                    <li>Graphic</li>
                    <li>SEO</li>
                </ul>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Suscipit voluptatibus rem illum sunt, asperiores!</p>
            </div>
            <div class="servicio">
                <span class="icono"><i class="fa-solid fa-file-code"></i></span>
                <h4>Porgramación PHP</h4>
                <hr>
                <ul class="servicios-tag">
                    <li>Web</li>
                    <li>Graphic</li>
                    <li>SEO</li>
                </ul>
                <p>I have been providing web design services with great success for 9 years. The client is very happy</p>
            </div>
            <div class="servicio">
                <span class="icono"><i class="fa-solid fa-arrow-trend-up"></i></span>
                <h4>Posicionamiento SEO</h4>
                <hr>
                <ul class="servicios-tag">
                    <li>Web</li>
                    <li>Graphic</li>
                    <li>SEO</li>
                </ul>
                <p>I have been providing web design services with great success for 9 years. The client is very happy</p>
            </div>
        </div>
        <div class="fila">
            <div class="servicio">
                <span class="icono"><i class="fa-solid fa-database"></i></span>
                <h4>Alojamiento de Sitios</h4>
                <hr>
                <ul class="servicios-tag">
                    <li>Web</li>
                    <li>Graphic</li>
                    <li>SEO</li>
                </ul>
                <p>I have been providing web design services with great success for 9 years. The client is very happy</p>
            </div>
            <div class="servicio">
                <span class="icono"><i class="fa-solid fa-palette"></i></span>
                <h4>Diseñador Gráfico</h4>
                <hr>
                <ul class="servicios-tag">
                    <li>Web</li>
                    <li>Graphic</li>
                    <li>SEO</li>
                </ul>
                <p>I have been providing web design services with great success for 9 years. The client is very happy</p>
            </div>
            <div class="servicio">
                <span class="icono"><i class="fa-solid fa-person-circle-question"></i></span>
                <h4>Consultor Externo</h4>
                <hr>
                <ul class="servicios-tag">
                    <li>Web</li>
                    <li>Graphic</li>
                    <li>SEO</li>
                </ul>
                <p>I have been providing web design services with great success for 9 years. The client is very happy</p>
            </div>
        </div>
    </section>

    <!-- SECCION H A B I L I D A D E S -->
    <div class="contenedor-skills" id="skills">
        <h3>HABILIDADES </h3>
        <div class="skill">
            <div class="info">
                <p> <span class="lista"> </span>Html & Css</p>
                <span class="porcentaje">95%</span>
            </div>

            <div class="barra">
                <div class="" id="html"></div>
            </div>
        </div>
        <div class="skill">
            <div class="info">
                <p> <span class="lista"> </span>Javascript</p>
                <span class="porcentaje">90%</span>
            </div>

            <div class="barra">
                <div class="" id="js"></div>
            </div>
        </div>
        <div class="skill">
            <div class="info">
                <p> <span class="lista"> </span>Bases de Datos</p>
                <span class="porcentaje">90%</span>
            </div>

            <div class="barra">
                <div class="" id="bd"></div>
            </div>
        </div>
        <div class="skill">
            <div class="info">
                <p> <span class="lista"> </span>Photoshop</p>
                <span class="porcentaje">85%</span>
            </div>

            <div class="barra">
                <div class="" id="ps"></div>
            </div>
        </div>
    </div>

    <!-- SECCION PORTAFOLIO -->
    <section id="portfolio">
        <h3 class="titulo-seccion">Mis Proyectos</h3>
        <div class="fila">
            <div class="proyecto">
                <div class="overlay"></div>
                <img src="img/proyecto1.jpg" alt="">
                <div class="info">
                    <h4>Descripcion Proyecto</h4>
                    <p>Diseño Web</p>
                </div>
            </div>
            <div class="proyecto">
                <div class="overlay"></div>
                <img src="img/proyecto2.jpg" alt="">
                <div class="info">
                    <h4>Descripcion Proyecto</h4>
                    <p>Diseño Web</p>
                </div>
            </div>
            <div class="proyecto">
                <div class="overlay"></div>
                <img src="img/proyecto3.jpg" alt="">
                <div class="info">
                    <h4>Descripcion Proyecto</h4>
                    <p>Diseño Web</p>
                </div>
            </div>
        </div>
        <div class="fila">
            <div class="proyecto">
                <div class="overlay"></div>
                <img src="img/proyecto4.jpg" alt="">
                <div class="info">
                    <h4>Descripcion Proyecto</h4>
                    <p>Diseño Web</p>
                </div>
            </div>
            <div class="proyecto">
                <div class="overlay"></div>
                <img src="img/proyecto5.jpg" alt="">
                <div class="info">
                    <h4>Descripcion Proyecto</h4>
                    <p>Diseño Web</p>
                </div>
            </div>
            <div class="proyecto">
                <div class="overlay"></div>
                <img src="img/proyecto6.jpg" alt="">
                <div class="info">
                    <h4>Descripcion Proyecto</h4>
                    <p>Diseño Web</p>
                </div>
            </div>
        </div>
        <div class="fila">
            <div class="proyecto">
                <div class="overlay"></div>
                <img src="img/proyecto7.jpg" alt="">
                <div class="info">
                    <h4>Descripcion Proyecto</h4>
                    <p>Diseño Web</p>
                </div>
            </div>
            <div class="proyecto">
                <div class="overlay"></div>
                <img src="img/proyecto8.jpg" alt="">
                <div class="info">
                    <h4>Descripcion Proyecto</h4>
                    <p>Diseño Web</p>
                </div>
            </div>
            <div class="proyecto">
                <div class="overlay"></div>
                <img src="img/proyecto9.jpg" alt="">
                <div class="info">
                    <h4>Descripcion Proyecto</h4>
                    <p>Diseño Web</p>
                </div>
            </div>
        </div>
    </section>

    <!-- SECCTION C O N T A C T O -->
    <section id="contacto">
        <h3 class="titulo-seccion">Contactanos ahora</h3>
        <div class="contenedor-form">
            <form action="">
                <div class="fila mitad">
                    <input type="text" placeholder="Nombre Completo *" class="input-mitad">
                    <input type="email" placeholder="Dirección de Email" class="input-mitad">
                </div>
                <div class="fila">
                    <input type="text" placeholder="Tema..." class="input-full">
                </div>
                <div class="fila">
                    <textarea name="" id="" cols="30" rows="10" placeholder="Tu Mensaje..." class="input-full"></textarea>
                </div>

                <input type="submit" value="Enviar Mensaje" class="btn-enviar">
            </form>
        </div>
    </section>

    <!-- SECCION FOOTER -->
    <footer>
        <p>Todos los derechos reservados - 2022</p>
        <div class="redes">
            <a href="#"><i class="fa-brands fa-youtube"></i></a>
            <a href="#"><i class="fa-brands fa-facebook"></i></a>
            <a href="#"><i class="fa-brands fa-instagram-square"></i></a>
        </div>

    </footer>

    <script src="script.js"></script>
</body>

</html>

  @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@200;300;400;500;600&display=swap');
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Montserrat';
        }
        
        html {
            scroll-behavior: smooth;
        }
        /* *********************/
        /* seccion I N I C I O */
        /* *********************/
        
        #inicio {
            background: linear-gradient( rgba(179, 94, 94, 0.7), rgba(0, 0, 0, .7)), url("img/cuantos.jpg");
            background-size: cover;
            background-position: center center;
            height: 100vh;
        }
        
        #inicio .contenido header {
            background-color: rgba(0, 0, 0, .8);
            position: fixed;
            width: 100%;
            z-index: 100;
            top: 0;
        }
        
        #inicio .contenido header .contenido-header {
            max-width: 1100px;
            margin: auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 10px 20px;
        }
        
        #inicio .contenido header .contenido-header h1 {
            text-align: center;
            color: #ff5080;
        }
        
        #inicio .contenido header .contenido-header nav ul {
            list-style: none;
            display: flex;
            align-items: center;
        }
        
        #inicio .contenido header .contenido-header nav ul li a {
            text-decoration: none;
            color: #fff;
            margin: 0 12px;
            font-weight: 400;
            transition: .5s;
        }
        
        #inicio .contenido header .contenido-header nav ul li a:hover {
            color: #ff5080;
        }
        
        #inicio .contenido header .contenido-header .redes a {
            text-decoration: none;
            color: #fff;
            display: inline-block;
            margin-left: 10px;
            transition: .5s;
        }
        
        #inicio .contenido header .contenido-header .redes a:hover {
            color: #ff5080;
        }
        
        #inicio .contenido header .contenido-header .seleccionado {
            color: #ff5080;
        }
        
        #inicio .contenido .presentacion {
            max-width: 1100px;
            height: 100vh;
            margin: auto;
            color: #fff;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
        }
        
        #inicio .contenido .presentacion .bienvenida {
            font-size: 16px;
            margin-bottom: 20px;
            text-transform: uppercase;
            letter-spacing: 5px;
        }
        
        #inicio .contenido .presentacion h2 {
            font-size: 55px;
            margin-bottom: 25px;
            text-align: center;
        }
        
        #inicio .contenido .presentacion h2 span {
            font-size: 25px;
            color: #ff5080;
        }
        
        #inicio .contenido .presentacion .descripcion {
            max-width: 700px;
            margin: 25px auto;
            font-size: 18px;
            text-align: center;
        }
        
        #inicio .contenido .presentacion a {
            text-decoration: none;
            display: inline-block;
            margin: 25px;
            padding: 20px 25px;
            border: 2px solid #fff;
            border-radius: 50px;
            color: #fff;
            font-weight: bold;
            text-transform: uppercase;
            transition: .5s;
        }
        
        #inicio .contenido .presentacion a:hover {
            background-color: #ff5080;
        }
        
        #icono-nav {
            color: #fff;
            display: none;
        }
        /* *********************/
        /* seccion S O B R E  M I */
        /* *********************/
        
        #sobremi {
            max-width: 1100px;
            margin: auto;
            padding: 100px 15px;
            color: #111135;
            display: flex;
        }
        
        #sobremi .contenedor-foto {
            max-width: 400px;
            margin-right: 80px;
        }
        
        #sobremi .contenedor-foto img {
            padding: 20px;
            width: 100%;
            border-radius: 20px;
            background-color: #f3f3f3;
        }
        
        #sobremi .sobremi {
            margin: 0 40px;
        }
        
        #sobremi .sobremi .titulo-seccion {
            font-size: 22px;
            text-transform: uppercase;
            color: #111135;
            text-decoration: underline;
            text-decoration-color: #d3d3d3;
            text-decoration-thickness: 5px;
        }
        
        #sobremi .sobremi h2 {
            font-size: 34px;
            font-weight: bold;
            margin: 20px 0;
            letter-spacing: 2px;
        }
        
        #sobremi .sobremi h2 span {
            color: #ff5080;
        }
        
        #sobremi .sobremi h3 {
            font-size: 18px;
            font-weight: 500;
            text-transform: uppercase;
            margin-bottom: 20px;
            letter-spacing: 1px;
        }
        
        #sobremi .sobremi p {
            font-size: 14px;
            line-height: 25px;
            color: #565656;
            margin-bottom: 12px;
        }
        
        #sobremi .sobremi a {
            display: inline-block;
            text-decoration: none;
            color: #000;
            border-radius: 30px;
            border: 1px solid #000;
            padding: 10px 20px;
            margin-top: 30px;
            transition: .5s;
        }
        
        #sobremi .sobremi a:hover {
            background-color: #ff5080;
            color: #fff;
        }
        /* *********************/
        /* seccion S E R V I C I O S */
        /* *********************/
        
        #servicios {
            padding: 100px 15px;
            text-align: center;
            background-color: #f3f3f3;
        }
        
        #servicios .titulo-seccion {
            text-align: center;
            font-size: 22px;
            text-transform: uppercase;
            color: #111135;
            text-decoration: underline;
            text-decoration-color: #d3d3d3;
            text-decoration-thickness: 5px;
        }
        
        #servicios .fila {
            display: flex;
            justify-content: space-between;
            max-width: 1150px;
            margin: 30px auto;
        }
        
        #servicios .fila .servicio {
            max-width: 350px;
            background-color: #fff;
            padding: 30px;
            margin: 0 5px;
            border-radius: 5px;
            transition: .5s;
        }
        
        #servicios .fila .servicio:hover {
            box-shadow: 5px 5px 10px #565656, -5px -5px 10px #8a8a8a;
        }
        
        #servicios .fila .servicio .icono {
            display: inline-block;
            width: 60px;
            height: 60px;
            border-radius: 50%;
            background-color: #d3d3d3;
            padding: 20px;
            margin-bottom: 25px;
        }
        
        #servicios .fila .servicio h4 {
            font-size: 22px;
            margin-bottom: 25px;
        }
        
        #servicios .fila .servicio hr {
            width: 30%;
            margin: auto;
            color: #000;
            margin-bottom: 25px;
        }
        
        #servicios .fila .servicio ul {
            list-style: none;
            display: flex;
            justify-content: space-around;
            margin-bottom: 10px;
        }
        
        #servicios .fila .servicio p {
            font-size: 14px;
            line-height: 22px;
        }
        /* *********************/
        /* seccion S K I L L S */
        /* *********************/
        
        .contenedor-skills {
            background: linear-gradient( #eb5a5acc, rgba(33, 16, 16, 0.8)), url("img/fondo-skills.jpg");
            background-attachment: fixed;
            background-repeat: no-repeat;
            background-size: cover;
            color: #fff;
            background-position: center center;
            padding: 100px 0;
            text-align: center;
        }
        
        .contenedor-skills .skill {
            max-width: 600px;
            margin: 30px auto;
        }
        
        .contenedor-skills .skill .info {
            display: flex;
            justify-content: space-between;
        }
        
        .contenedor-skills .skill .lista {
            display: inline-block;
            margin-right: 20px;
            height: 10px;
            width: 10px;
            background-color: #fff;
        }
        
        .contenedor-skills .skill .barra {
            background-color: #919191;
            width: 100%;
            height: 6px;
            margin: 10px 0px;
        }
        
        .contenedor-skills .skill .barra .barra-progreso1 {
            background-color: #fff;
            width: 95%;
            height: 6px;
            animation: progreso1 2s forwards;
        }
        
        .contenedor-skills .skill .barra .barra-progreso2 {
            background-color: #fff;
            width: 90%;
            height: 6px;
            animation: progreso2 2s forwards;
        }
        
        .contenedor-skills .skill .barra .barra-progreso3 {
            background-color: #fff;
            width: 90%;
            height: 6px;
            animation: progreso3 2s forwards;
        }
        
        .contenedor-skills .skill .barra .barra-progreso4 {
            background-color: #fff;
            width: 85%;
            height: 6px;
            animation: progreso4 2s forwards;
        }
        
        @keyframes progreso1 {
            0% {
                width: 0;
            }
            100% {
                width: 95%;
            }
        }
        
        @keyframes progreso2 {
            0% {
                width: 0;
            }
            100% {
                width: 90%;
            }
        }
        
        @keyframes progreso3 {
            0% {
                width: 0;
            }
            100% {
                width: 90%;
            }
        }
        
        @keyframes progreso4 {
            0% {
                width: 0;
            }
            100% {
                width: 85%;
            }
        }
        /* *********************/
        /* seccion P O R T F O L I O */
        /* *********************/
        
        #portfolio {
            max-width: 1100px;
            padding: 100px 0;
            margin: auto;
        }
        
        #portfolio .titulo-seccion {
            text-align: center;
            font-size: 22px;
            text-transform: uppercase;
            color: #111135;
            text-decoration: underline;
            text-decoration-color: #d3d3d3;
            text-decoration-thickness: 5px;
        }
        
        #portfolio .fila {
            display: flex;
            justify-content: space-between;
            margin: 30px 0;
        }
        
        #portfolio .fila .proyecto {
            max-width: 450px;
            border: 1px solid #000;
            margin: 0 10px;
            position: relative;
            overflow: hidden;
        }
        
        #portfolio .fila .proyecto img {
            width: 100%;
            height: 100%;
            ;
            filter: grayscale(1);
            object-fit: cover;
            transition: .5s;
        }
        
        #portfolio .fila .proyecto:hover img {
            filter: grayscale(0);
        }
        
        #portfolio .fila .proyecto .info {
            position: absolute;
            left: 0px;
            background-color: rgba(0, 0, 0, 0.8);
            color: #ff5080;
            width: 100%;
            padding: 10px;
            opacity: 0;
            bottom: -40px;
            transition: .5s;
        }
        
        #portfolio .fila .proyecto:hover .info {
            opacity: 1;
            bottom: 0;
        }
        /* *********************/
        /* seccion C O N T A C T O */
        /* *********************/
        
        #contacto {
            padding: 100px 15px;
            background-color: #f3f3f3;
        }
        
        #contacto .titulo-seccion {
            margin-bottom: 20px;
        }
        
        #contacto .contenedor-form {
            max-width: 1100px;
            margin: auto;
        }
        
        #contacto .contenedor-form .fila {
            margin-bottom: 15px;
        }
        
        #contacto .contenedor-form .mitad {
            display: flex;
            justify-content: space-between;
        }
        
        #contacto .contenedor-form input,
        #contacto .contenedor-form textarea {
            padding: 20px;
            border-radius: 20px;
            border: none;
            border: 1px solid #919191;
        }
        
        #contacto .contenedor-form .mitad input {
            width: 48%;
        }
        
        #contacto .contenedor-form .input-full {
            width: 100%;
        }
        
        #contacto .titulo-seccion {
            text-align: center;
            font-size: 22px;
            text-transform: uppercase;
            color: #111135;
            text-decoration: underline;
            text-decoration-color: #d3d3d3;
            text-decoration-thickness: 5px;
        }
        
        #contacto .btn-enviar {
            display: block;
            margin: auto;
            cursor: pointer;
            transition: .5s;
            padding: 10px 15px !important;
        }
        
        #contacto .btn-enviar:hover {
            background-color: #ff5080;
            color: #fff;
        }
        /* *********************/
        /* seccion F O O T E R */
        /* *********************/
        
        footer {
            background-color: #000;
            color: #fff;
            text-align: center;
            padding: 30px 0;
        }
        
        footer a {
            text-decoration: none;
            color: #fff;
            display: inline-block;
            margin: 5px;
            font-size: 26px;
        }
        /* *********************/
        /* seccion R E S P O N S I V E */
        /* *********************/
        
        @media screen and (max-width: 800px) {
            .redes {
                display: none;
            }
            nav {
                display: none;
            }
            nav.responsive {
                display: block;
                background-color: rgba(0, 0, 0, .8);
                width: 100%;
                position: absolute;
                top: 48px;
                left: 0;
                padding: 10px 0;
            }
            nav.responsive ul {
                display: block !important;
                text-align: center;
            }
            nav.responsive ul li {
                margin: 5px 0;
            }
            #icono-nav {
                display: block;
            }
            #inicio .contenido .presentacion h2 {
                font-size: 40px;
            }
            /* seccion SOBRE MI */
            #sobremi {
                padding: 50px 0;
                display: block;
            }
            #sobremi .contenedor-foto {
                max-width: 200px;
                margin: auto;
            }
            #sobremi .contenedor-foto img {
                padding: 8px;
            }
            #sobremi .sobremi .titulo-seccion {
                text-align: center;
            }
            #sobremi .sobremi h2 {
                font-size: 25px;
                text-align: center;
            }
            /* seccion MIS SERVICIOS */
            #servicios {
                padding: 50px 15px;
            }
            #servicios .fila {
                display: block;
            }
            #servicios .fila .servicio {
                margin: 10px auto;
            }
            /* seccion HABLIDADES MI */
            .contenedor-skills {
                padding: 50px 20px;
            }
            /* seccion PORTFOLIO */
            #portfolio {
                padding: 50px 0;
            }
            #portfolio .fila {
                display: block;
            }
            #portfolio .fila .proyecto {
                margin: 10px auto;
            }
            /* seccion CONTACTO */
            #contacto {
                padding: 50px 15px;
            }
            #contacto .contenedor-form .mitad {
                margin-bottom: 15px;
                display: block;
            }
            #contacto .contenedor-form .mitad input {
                width: 100%;
                margin-bottom: 15px;
            }
        }
