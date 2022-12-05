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
