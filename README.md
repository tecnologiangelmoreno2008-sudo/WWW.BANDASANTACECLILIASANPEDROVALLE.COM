# WWW.BANDASANTACECLILIASANPEDROVALLE.COM
 :root {
            --rojo: #8b0000;
            --oro: #d4af37;
            --texto: #2f2f2f;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #fdfdfd 0%, #f4ebd0 100%);
            color: var(--texto);
        }

        .navbar {
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.08);
        }

        .navbar-brand {
            font-weight: 700;
            letter-spacing: 0.08em;
        }

        .navbar .form-control {
            min-width: 180px;
            border-radius: 999px;
            border: 1px solid rgba(255, 255, 255, 0.25);
            background: rgba(255, 255, 255, 0.12);
            color: white;
        }

        .navbar .form-control::placeholder {
            color: rgba(255, 255, 255, 0.75);
        }

        .navbar .form-control:focus {
            background: white;
            color: #222;
            box-shadow: none;
        }

        .navbar .btn-outline-light {
            border-radius: 999px;
            padding: 0.35rem 0.8rem;
        }

        .hero-card {
            background: rgba(255, 255, 255, 0.95);
            border: 1px solid #eee;
            border-radius: 1.2rem;
            box-shadow: 0 8px 25px rgba(0, 0, 0, 0.08);
        }

        .titulo-principal {
            font-size: clamp(1.8rem, 4vw, 3rem);
            font-weight: 800;
            color: var(--rojo);
            text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.1);
            line-height: 1.15;
        }

        .subtitulo {
            color: #6c6c6c;
            font-size: clamp(1rem, 2.3vw, 1.25rem);
        }

        .video-title {
            font-size: clamp(1.8rem, 4vw, 2.4rem);
            font-weight: 800;
            color: var(--rojo);
            text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.12);
            margin-bottom: 1rem;
            position: relative;
        }

        .video-title::after {
            content: "";
            display: block;
            width: 5rem;
            height: 0.35rem;
            margin-top: 0.75rem;
            border-radius: 999px;
            background: linear-gradient(90deg, var(--rojo), var(--oro));
        }

        .video-card {
            background: white;
            border-radius: 1.2rem;
            box-shadow: 0 8px 25px rgba(0, 0, 0, 0.08);
            padding: 1rem;
        }

        .frase-nubecita {
            position: relative;
            background: rgba(255, 255, 255, 0.96);
            border: 1px solid rgba(212, 175, 55, 0.35);
            box-shadow: 0 14px 40px rgba(0, 0, 0, 0.08);
            border-radius: 2rem;
            padding: 1.6rem 1.4rem;
            margin: 1.75rem 0;
            backdrop-filter: blur(8px);
        }

        .frase-nubecita::before {
            content: "";
            position: absolute;
            top: -18px;
            left: 1.4rem;
            width: 60px;
            height: 34px;
            background: rgba(255, 255, 255, 0.95);
            border-radius: 50%;
            box-shadow: 28px 10px 0 rgba(255, 255, 255, 0.95), 50px 18px 0 rgba(255, 255, 255, 0.95);
        }

        .frase-nubecita h3 {
            color: var(--rojo);
            margin-bottom: 0.75rem;
        }

        .frase-nubecita p {
            color: #3a3a3a;
            font-size: 1.05rem;
            line-height: 1.75;
            margin-bottom: 0;
        }

        .carousel-item img {
            height: 320px;
            object-fit: cover;
            border-radius: 1rem;
        }

        @media (max-width: 768px) {
            .carousel-item img {
                height: 240px;
            }

            .hero-card {
                padding: 1.25rem;
            }
        }
<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BANDA SANTA CECILIA SAN PEDRO VALLE</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-sRIl4kxILFvY47J16cr9ZwB07vP4J8+LH7qKQnuqkuIAvNWLzeN8tE5YBujZqJLB" crossorigin="anonymous">
    <link rel="stylesheet" href="estilo.css">
</head>

<body>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="Index.html">BANDA SANTA CECILIA</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto align-items-lg-center">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="Index.html">Inicio</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="MomentosDeLaBanda.html">Historia</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="Videos.html">Videos</a>
                    </li>   
                    <li class="nav-item">
                        <a class="nav-link" href="Publicaciones.html">Publicaciones</a>
                    </li>   
    </nav>

    <main class="container py-4 py-md-5">
        <section class="row g-4 align-items-center mb-4">
            <div class="col-lg-7">
                <div class="hero-card p-4 p-md-5">
                    <p class="mb-2 fw-bold text-uppercase" style="letter-spacing: 0.25em; color: var(--rojo);">Tradición
                        y cultura</p>
                    <h1 class="titulo-principal mb-3">Banda de Músicos Santa Cecilia de San Pedro</h1>
                    <h2 class="subtitulo mb-3">Tradición, Cultura y Patrimonio Musical desde 1952</h2>
                    <p class="lead mb-0">
                        La Banda de Músicos Santa Cecilia de San Pedro es una agrupación tradicional del Valle del
                        Cauca,
                        fundada en 1952, dedicada a preservar y difundir la música colombiana con identidad y orgullo.
                    </p>
                </div>
            </div>
            <div class="col-lg-5">
                <div id="carouselExample" class="carousel slide" data-bs-ride="carousel">
                    <div class="carousel-inner">
                        <div class="carousel-item active">
                            <img src="IMG/equipo juvenil y mayores en las procesisones de las semana santa.png"
                                class="d-block w-100" alt="Banda en procesiones de Semana Santa">
                        </div>
                        <div class="carousel-item">
                            <img src="IMG/feriadecali2025grupojuvenilymayores.png" class="d-block w-100"
                                alt="Banda en Feria de Cali">
                        </div>
                        <div class="carousel-item">
                            <img src="IMG/grupo mas cerca de juvenil.png" class="d-block w-100"
                                alt="Grupo juvenil de la banda">
                        </div>
                        <div class="carousel-item">
                            <img src="IMG/grupoviejo.png" class="d-block w-100" alt="Grupo de la banda">
                        </div>
                    </div>
                    <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample"
                        data-bs-slide="prev">
                        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                        <span class="visually-hidden">Anterior</span>
                    </button>
                    <button class="carousel-control-next" type="button" data-bs-target="#carouselExample"
                        data-bs-slide="next">
                        <span class="carousel-control-next-icon" aria-hidden="true"></span>
                        <span class="visually-hidden">Siguiente</span>
                    </button>
                </div>
            </div>

            <h1 class="video-title">90 Años, Banda Santa Cecilia</h1>
            <video width="500" height="460" controls>
                <source src="Videos/90 Años, Banda Santa Cecilia (San Pedro, Valle del Cauca).mp4" type="video/mp4">
                Tu navegador no soporta la reproducción de videos.
            </video>









        </section>











































































        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js"
            integrity="sha384-FKyoEForCGlyvwx9Hj09JcYn3nv7wiPVlz7YYwJrWVcXK/BmnVDxM+D2scQbITxI"
            crossorigin="anonymous"></script>
</body>

</html>
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Historia de la Banda</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-sRIl4kxILFvY47J16cr9ZwB07vP4J8+LH7qKQnuqkuIAvNWLzeN8tE5YBujZqJLB" crossorigin="anonymous">
    <link rel="stylesheet" href="estilo.css">
</head>

<body>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="Index.html">BANDA SANTA CECILIA</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto align-items-lg-center">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="Index.html">Inicio</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="MomentosDeLaBanda.html">Historia</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="Videos.html">Videos</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="Publicaciones.html">Publicaciones</a>
                    </li>
    </nav>
    <main class="container py-4 py-md-5">
        <section class="row g-4 align-items-center mb-4">
            <h1 class="titulo-principal mb-3">Historia de la Banda Santa Cecilia de San Pedro, Valle del Cauca</h1>
            <br>
            <p>La Banda Santa Cecilia de San Pedro, Valle del Cauca, es una agrupación musical que representa el
                talento, la cultura y las tradiciones de su municipio. A lo largo de los años se ha convertido en un
                símbolo de identidad para la comunidad, formando generaciones de músicos y llevando el nombre de San
                Pedro a diferentes escenarios del departamento y del país.
                <br><br>
                Según las imágenes y el material audiovisual, la historia de la banda está marcada por el esfuerzo de
                directores, maestros, músicos y familias que han trabajado unidos para mantener viva la tradición
                bandística del municipio. La agrupación ha servido como una escuela artística donde niños y jóvenes
                aprenden disciplina, responsabilidad, trabajo en equipo y amor por la música.
                <br><br>
                Desde sus inicios, la banda ha participado en desfiles, actos cívicos, celebraciones religiosas,
                concursos y festivales de bandas musicales, destacándose por la calidad de sus interpretaciones y el
                compromiso de sus integrantes. Con el paso del tiempo, muchos de sus músicos han crecido dentro de la
                institución, pasando de ser estudiantes a convertirse en referentes y apoyo para las nuevas
                generaciones.
            </p>
            <h2 class="titulo-principal mb-3">Las fotografías muestran la evolución de la agrupación:</h2>
            <ol>
                <li>Los jóvenes músicos participan activamente en los ensayos y presentaciones.</li>
                <li>La banda cuenta con diferentes familias instrumentales como percusión, saxofones, clarinetes,
                    trombones, trompetas y tubas.</li>
                <li>Ha realizado presentaciones en escenarios importantes y conciertos especiales ante cientos de
                    espectadores.</li>
                <li>También participa en desfiles y actividades culturales que fortalecen las tradiciones del municipio.
                </li>
                <li>La unión entre músicos, directores, padres de familia y comunidad ha sido fundamental para su
                    crecimiento.</li>
            </ol>
            <br>
            <p>Uno de los aspectos más valiosos de la Banda Santa Cecilia es su capacidad para reunir a varias
                generaciones de músicos. En el video se observa el reconocimiento a quienes hicieron parte de la
                historia de la agrupación y contribuyeron a su desarrollo durante décadas, permitiendo que hoy continúe
                siendo una institución cultural de gran importancia para San Pedro.
                <br>
                Actualmente, la banda sigue formando nuevos talentos y representando con orgullo al municipio en
                diferentes eventos y concursos, demostrando que la música es una herramienta de transformación social y
                cultural.
                <br><br>
            <h3 class="titulo-principal mb-3">Conclusión</h3>
            La Banda Santa Cecilia de San Pedro no es solamente una agrupación musical; es una familia y un
            patrimonio cultural del municipio. Su historia refleja dedicación, perseverancia y pasión por la música,
            valores que continúan inspirando a las nuevas generaciones de músicos sampedreños y fortaleciendo la
            identidad cultural de la región.
            </p>
            <br>
            <div class="frase-nubecita">
                <h3 class="titulo-principal mb-3">Frase conmemorativa</h3>
                <p>"Noventa años de historia, tradición y música al servicio de la cultura de San Pedro, Valle del
                    Cauca;
                    formando generaciones y llevando con orgullo el nombre de nuestro municipio a cada escenario."</p>
            </div>
            <img src="IMG/Banda Santa Cecilia San pedro90añosdehistoria.jpg">
            <br>











































        </section>
    </main>






















    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-FKyoEForCGlyvwx9Hj09JcYn3nv7wiPVlz7YYwJrWVcXK/BmnVDxM+D2scQbITxI"
        crossorigin="anonymous"></script>
</body>

</html>
<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Banda Santa Cecilia - Publicaciones</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-sRIl4kxILFvY47J16cr9ZwB07vP4J8+LH7qKQnuqkuIAvNWLzeN8tE5YBujZqJLB" crossorigin="anonymous">
    <style>
        :root {
            --rojo: #8b0000;
            --oro: #d4af37;
            --azul: #0d47a1;
            --crema: #f7efd9;
            --texto: #2f2f2f;
            --blanco: #ffffff;
        }

        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: var(--texto);
            background: linear-gradient(135deg, var(--crema) 0%, #ffffff 100%);
        }

        header {
            background: linear-gradient(135deg, var(--rojo), var(--azul));
            color: white;
            padding: 28px 20px;
            text-align: center;
            box-shadow: 0 6px 18px rgba(0, 0, 0, 0.18);
        }

        header h1 {
            margin: 0 0 8px;
            font-size: clamp(1.6rem, 3.2vw, 2.3rem);
        }

        header p {
            margin: 0;
            opacity: 0.95;
            font-size: 1rem;
        }

        .contenedor {
            max-width: 900px;
            margin: 24px auto 40px;
            padding: 0 16px;
        }

        .panel {
            background: rgba(255, 255, 255, 0.96);
            padding: 22px;
            border-radius: 18px;
            box-shadow: 0 10px 24px rgba(0, 0, 0, 0.08);
            border: 1px solid rgba(212, 175, 55, 0.2);
        }

        .panel h2 {
            margin-top: 0;
            color: var(--rojo);
        }

        .campo {
            margin-bottom: 12px;
        }

        label {
            display: block;
            margin-bottom: 6px;
            font-weight: 600;
            color: var(--azul);
        }

        select,
        textarea,
        input[type="file"] {
            width: 100%;
            border-radius: 10px;
            border: 1px solid #d7cfa6;
            padding: 10px 12px;
            font-size: 1rem;
            background: #fffdf7;
        }

        textarea {
            min-height: 110px;
            resize: vertical;
        }

        button {
            margin-top: 8px;
            background: linear-gradient(135deg, var(--rojo), var(--oro));
            color: white;
            border: none;
            padding: 10px 18px;
            border-radius: 999px;
            cursor: pointer;
            font-weight: 700;
            transition: transform 0.2s ease;
        }

        button:hover {
            transform: translateY(-1px);
        }

        .ayuda {
            margin-top: 10px;
            font-size: 0.92rem;
            color: #6b6b6b;
        }

        .publicacion {
            background: var(--blanco);
            margin-top: 20px;
            padding: 18px;
            border-radius: 16px;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.08);
            border-left: 6px solid var(--oro);
        }

        .encabezado {
            display: flex;
            justify-content: space-between;
            align-items: center;
            gap: 10px;
            margin-bottom: 6px;
        }

        .autor {
            margin: 0;
            color: var(--rojo);
            font-weight: 700;
        }

        .fecha {
            margin: 0;
            color: #808080;
            font-size: 0.86rem;
        }

        .texto-publicacion {
            margin: 10px 0 0;
            line-height: 1.6;
            white-space: pre-wrap;
        }

        img,
        video {
            width: 100%;
            display: block;
            margin-top: 12px;
            border-radius: 12px;
            object-fit: cover;
            max-height: 420px;
        }

        .acciones-publicacion {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin-top: 14px;
        }

        .action-btn,
        .btn-delete {
            border: none;
            border-radius: 999px;
            padding: 8px 12px;
            font-weight: 600;
            cursor: pointer;
            background: #f7efd9;
            color: var(--azul);
        }

        .action-btn:hover,
        .btn-delete:hover {
            transform: translateY(-1px);
        }

        .btn-delete {
            background: #ffe3e3;
            color: var(--rojo);
        }

        .comentarios {
            margin-top: 14px;
            padding-top: 12px;
            border-top: 1px solid #eee;
        }

        .comentario-item {
            background: #fcfaf2;
            border-radius: 10px;
            padding: 8px 10px;
            margin-bottom: 8px;
        }

        .comentario-item p {
            margin: 2px 0 0;
            line-height: 1.5;
        }

        .comentario-item small {
            color: #7a7a7a;
        }

        .input-comentario {
            width: 100%;
            min-height: 70px;
            border-radius: 10px;
            border: 1px solid #d7cfa6;
            padding: 8px 10px;
            margin-top: 8px;
            resize: vertical;
        }

        .vacio {
            text-align: center;
            padding: 24px;
            color: #6b6b6b;
            background: #fcfaf2;
            border-radius: 14px;
            border: 1px dashed #d7cfa6;
            margin-top: 16px;
        }

        @media (max-width: 600px) {
            .encabezado {
                flex-direction: column;
                align-items: flex-start;
            }
        }
    </style>
</head>

<body>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="Index.html">BANDA SANTA CECILIA</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto align-items-lg-center">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="Index.html">Inicio</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="MomentosDeLaBanda.html">Historia</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="Videos.html">Videos</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="Publicaciones.html">Publicaciones</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
    <header>
        <h1>🎺 Banda Santa Cecilia</h1>
        <p>90 años de historia, tradición y música en San Pedro, Valle del Cauca</p>
    </header>

    <div class="contenedor">
        <section class="panel">
            <h2>Crear publicación</h2>

            <div class="campo">
                <label for="rol">Publicado por</label>
                <select id="rol">
                    <option value="Administrador">Autor de la Pagina web</option>
                    <option value="Director de la banda">Director de la banda</option>
                    <option value="Miembro de la banda">Miembro de la banda</option>
                     <option value="Visitante">Visitante</option>
                </select>
            </div>

            <div class="campo">
                <label for="texto">Mensaje</label>
                <textarea id="texto" placeholder="Escribe una noticia, saludo o recuerdo para la banda..."></textarea>
            </div>

            <div class="campo">
                <label for="archivo">Adjuntar imagen o video</label>
                <input type="file" id="archivo" accept="image/*,video/*">
            </div>

            <button onclick="publicar()">Publicar</button>
            <p class="ayuda">Las publicaciones se guardan en este navegador para que permanezcan visibles aunque cierres
                o recargues la página.</p>
        </section>

        <div id="muro"></div>
    </div>

    <script>
        const STORAGE_KEY = "bandaSantaCeciliaPublicaciones";
        const DB_NAME = "bandaSantaCeciliaDB";
        const STORE_NAME = "archivos";
        let publicaciones = cargarPublicaciones();
        let dbPromise = abrirBaseDeDatos();

        renderPublicaciones();

        async function publicar() {
            const texto = document.getElementById("texto").value.trim();
            const rol = document.getElementById("rol").value;
            const archivoInput = document.getElementById("archivo");
            const archivo = archivoInput.files[0];

            if (!texto && !archivo) {
                alert("Debe escribir algo o seleccionar una imagen o video.");
                return;
            }

            const archivoTipo = archivo ? archivo.type : null;
            let archivoId = null;

            if (archivo) {
                archivoId = `${Date.now()}-${Math.random().toString(16).slice(2)}`;
                await guardarArchivo(archivoId, archivo);
            }

            const nuevaPublicacion = {
                id: Date.now(),
                autor: rol,
                texto: texto,
                fecha: new Date().toISOString(),
                likes: 0,
                comentarios: [],
                archivoId: archivoId,
                archivoTipo: archivoTipo,
                archivoNombre: archivo ? archivo.name : ""
            };

            publicaciones.unshift(nuevaPublicacion);
            guardarPublicaciones();
            await renderPublicaciones();

            document.getElementById("texto").value = "";
            archivoInput.value = "";
        }

        function cargarPublicaciones() {
            try {
                const datos = localStorage.getItem(STORAGE_KEY);
                const guardadas = datos ? JSON.parse(datos) : [];
                return guardadas.map(publicacion => ({
                    ...publicacion,
                    likes: Number(publicacion.likes || 0),
                    comentarios: Array.isArray(publicacion.comentarios) ? publicacion.comentarios : []
                }));
            } catch (error) {
                console.error("No se pudieron cargar las publicaciones", error);
                return [];
            }
        }

        function guardarPublicaciones() {
            localStorage.setItem(STORAGE_KEY, JSON.stringify(publicaciones));
        }

        async function renderPublicaciones() {
            const muro = document.getElementById("muro");

            if (publicaciones.length === 0) {
                muro.innerHTML = '<div class="vacio">Aún no hay publicaciones. ¡Anuncia la próxima actividad de la banda aquí!</div>';
                return;
            }

            const publicacionesHTML = await Promise.all(publicaciones.map(crearPublicacionHTML));
            muro.innerHTML = publicacionesHTML.join("");
        }

        async function crearPublicacionHTML(publicacion) {
            const fecha = new Date(publicacion.fecha).toLocaleString("es-ES", {
                dateStyle: "medium",
                timeStyle: "short"
            });

            let contenidoArchivo = "";
            if (publicacion.archivoId) {
                const blob = await obtenerArchivo(publicacion.archivoId);
                if (blob && publicacion.archivoTipo?.startsWith("image")) {
                    const url = URL.createObjectURL(blob);
                    contenidoArchivo = `<img src="${url}" alt="Imagen publicada">`;
                } else if (blob && publicacion.archivoTipo?.startsWith("video")) {
                    const url = URL.createObjectURL(blob);
                    contenidoArchivo = `<video controls preload="metadata"><source src="${url}" type="${publicacion.archivoTipo}"></video>`;
                }
            } else if (publicacion.archivoData && publicacion.archivoTipo?.startsWith("image")) {
                contenidoArchivo = `<img src="${publicacion.archivoData}" alt="Imagen publicada">`;
            } else if (publicacion.archivoData && publicacion.archivoTipo?.startsWith("video")) {
                contenidoArchivo = `<video controls src="${publicacion.archivoData}"></video>`;
            }

            const comentariosHTML = (publicacion.comentarios || []).map(comentario => `
                <div class="comentario-item">
                    <small>${escaparHTML(comentario.autor || "Visitante")} · ${new Date(comentario.fecha).toLocaleString("es-ES", { dateStyle: "short", timeStyle: "short" })}</small>
                    <p>${escaparHTML(comentario.texto)}</p>
                </div>
            `).join("");

            return `
                <article class="publicacion">
                    <div class="encabezado">
                        <h3 class="autor">${escaparHTML(publicacion.autor)}</h3>
                        <p class="fecha">${fecha}</p>
                    </div>
                    ${publicacion.texto ? `<p class="texto-publicacion">${escaparHTML(publicacion.texto)}</p>` : ""}
                    ${contenidoArchivo}
                    <div class="acciones-publicacion">
                        <button class="action-btn" onclick="darLike(${publicacion.id})">👍 Me gusta (${Number(publicacion.likes || 0)})</button>
                    </div>
                    <div class="comentarios">
                        ${comentariosHTML}
                        <textarea id="comentario-${publicacion.id}" class="input-comentario" placeholder="Escribe un comentario..."></textarea>
                        <button class="action-btn" onclick="agregarComentario(${publicacion.id})">Comentar</button>
                    </div>
                </article>
            `;
        }

        function darLike(id) {
            const publicacion = publicaciones.find(item => item.id === id);
            if (!publicacion) return;

            const key = `like-${id}`;
            const yaDioLike = sessionStorage.getItem(key) === "1";

            if (yaDioLike) {
                publicacion.likes = Math.max(0, Number(publicacion.likes || 0) - 1);
                sessionStorage.removeItem(key);
            } else {
                publicacion.likes = Number(publicacion.likes || 0) + 1;
                sessionStorage.setItem(key, "1");
            }

            guardarPublicaciones();
            renderPublicaciones();
        }

        function agregarComentario(id) {
            const publicacion = publicaciones.find(item => item.id === id);
            if (!publicacion) return;

            const textarea = document.getElementById(`comentario-${id}`);
            const texto = textarea?.value.trim();
            if (!texto) {
                alert("Escribe un comentario antes de publicar.");
                return;
            }

            publicacion.comentarios = publicacion.comentarios || [];
            publicacion.comentarios.unshift({
                id: Date.now(),
                autor: "Visitante",
                texto: texto,
                fecha: new Date().toISOString()
            });

            guardarPublicaciones();
            renderPublicaciones();
        }

        function escaparHTML(texto) {
            return String(texto)
                .replace(/&/g, "&amp;")
                .replace(/</g, "&lt;")
                .replace(/>/g, "&gt;")
                .replace(/\"/g, "&quot;")
                .replace(/'/g, "&#39;");
        }

        function abrirBaseDeDatos() {
            return new Promise((resolve, reject) => {
                const solicitud = indexedDB.open(DB_NAME, 1);

                solicitud.onupgradeneeded = () => {
                    const db = solicitud.result;
                    if (!db.objectStoreNames.contains(STORE_NAME)) {
                        db.createObjectStore(STORE_NAME, { keyPath: "id" });
                    }
                };

                solicitud.onsuccess = () => resolve(solicitud.result);
                solicitud.onerror = () => reject(solicitud.error);
            });
        }

        async function guardarArchivo(id, archivo) {
            const db = await dbPromise;
            return new Promise((resolve, reject) => {
                const transaccion = db.transaction(STORE_NAME, "readwrite");
                const almacen = transaccion.objectStore(STORE_NAME);
                const solicitud = almacen.put({ id, archivo });
                solicitud.onsuccess = () => resolve();
                solicitud.onerror = () => reject(solicitud.error);
            });
        }

        async function obtenerArchivo(id) {
            const db = await dbPromise;
            return new Promise((resolve, reject) => {
                const transaccion = db.transaction(STORE_NAME, "readonly");
                const almacen = transaccion.objectStore(STORE_NAME);
                const solicitud = almacen.get(id);
                solicitud.onsuccess = () => resolve(solicitud.result?.archivo || null);
                solicitud.onerror = () => reject(solicitud.error);
            });
        }
    </script>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-FKyoEForCGlyvwx9Hj09JcYn3nv7wiPVlz7YYwJrWVcXK/BmnVDxM+D2scQbITxI"
        crossorigin="anonymous"></script>
</body>

</html>
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Videos Banda Santa Cecilia</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-sRIl4kxILFvY47J16cr9ZwB07vP4J8+LH7qKQnuqkuIAvNWLzeN8tE5YBujZqJLB" crossorigin="anonymous">
    <link rel="stylesheet" href="estilo.css">
</head>

<body>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="Index.html">BANDA SANTA CECILIA</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto align-items-lg-center">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="Index.html">Inicio</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="MomentosDeLaBanda.html">Historia</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="Videos.html">Videos</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="Publicaciones.html">Publicaciones</a>
                    </li>
    </nav>
    <main class="container py-4 py-md-5">
        <h1 class="video-title">Presentación de la Banda</h1>
        <video width="500" height="460" controls>
            <source
                src="Videos/Banda Santa Cecilia de San Pedro Valle en Tocancipa - Mosaico de Viaje por mi Pacifico.mp4"
                type="video/mp4">
            Tu navegador no soporta la reproducción de videos.
        </video>
        <main class="container py-4 py-md-5">
            <h1 class="video-title">Taller de Música con la Banda Santa Cecilia (Mayores de Edad)</h1>
            <video width="500" height="460" controls>
                <source src="Videos/Banda Santa Cecilia San Pedro Valle - Corozal y Sincelejo.mp4" type="video/mp4">
                Tu navegador no soporta la reproducción de videos.
            </video>
            <br>
            <main class="container py-4 py-md-5">
                <h1 class="video-title">Procesión de Semana Santa 2017</h1>
                <video width="500" height="460" controls>
                    <source src="Videos/Banda Santa Cecilia San Pedro Valle PROCESION SEMANA SANTA 2017.mp4"
                        type="video/mp4">
                    Tu navegador no soporta la reproducción de videos.
                </video>
                <br>
                <main class="container py-4 py-md-5">
                    <h1 class="video-title">Canto a la Alegría - Banda Juvenil Santa Cecilia</h1>
                    <video width="500" height="460" controls>
                        <source src="Videos/canto a la alegría Banda juvenil Santa Cecilia.mp4" type="video/mp4">
                        Tu navegador no soporta la reproducción de videos.
                    </video>
                    <br>




                    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js"
                        integrity="sha384-FKyoEForCGlyvwx9Hj09JcYn3nv7wiPVlz7YYwJrWVcXK/BmnVDxM+D2scQbITxI"
                        crossorigin="anonymous"></script>
</body>

</html>
