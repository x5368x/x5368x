<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio - x5368x</title>
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Devicon (para iconos de tecnología) -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.15.1/devicon.min.css">
    
    <!-- Font Awesome (para iconos sociales) -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">
    
    <!-- Google Fonts: Inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;700&display=swap" rel="stylesheet">

    <style>
        /* Estilo base para el cuerpo del documento */
        body {
            font-family: 'Inter', sans-serif;
            background-color: #111827; /* bg-gray-900 */
            color: #f3f4f6; /* text-gray-100 */
        }
        /* Contenedor principal para centrar el contenido */
        .main-container {
            max-width: 800px;
            margin: 0 auto;
            padding: 2rem;
        }
        /* Estilo para los títulos de las secciones */
        h2 {
            font-size: 1.875rem; /* text-3xl */
            font-weight: 700; /* font-bold */
            text-align: center;
            margin-bottom: 2rem;
            letter-spacing: 0.05em;
        }
        /* Estilo para los subtítulos de las secciones */
        h3 {
            font-size: 1.25rem; /* text-xl */
            font-weight: 600; /* font-semibold */
            margin-bottom: 0.75rem;
            color: #9ca3af; /* text-gray-400 */
        }
        /* Estilo para los íconos de tecnología */
        .tech-icon {
            display: inline-flex;
            align-items: center;
            gap: 0.5rem; /* gap-2 */
            background-color: #1f2937; /* bg-gray-800 */
            padding: 0.5rem 1rem;
            border-radius: 0.5rem; /* rounded-lg */
            font-size: 1rem; /* text-base */
            transition: transform 0.2s, background-color 0.2s;
        }
        .tech-icon:hover {
            transform: translateY(-2px);
            background-color: #374151; /* bg-gray-700 */
        }
        .tech-icon i {
            font-size: 1.5rem; /* Aumenta el tamaño del icono */
        }
    </style>
</head>
<body>

    <div class="main-container">

        <!-- Encabezado con el nombre de usuario -->
        <header class="text-center mb-12">
            <h1 class="text-4xl font-bold text-white">Rendimiento.</h1>
        </header>

        <!-- Sección de Tecnologías y Herramientas -->
        <section class="mb-12">
            <h2 class="text-2xl font-bold mb-6 text-center">Tecnologías y Herramientas</h2>
            <div class="flex flex-wrap justify-center gap-4">
                <!-- Fila 1 -->
                <span class="tech-icon"><i class="devicon-linux-plain colored"></i> Linux</span>
                <span class="tech-icon"><i class="devicon-docker-plain colored"></i> Docker</span>
                <span class="tech-icon"><i class="devicon-kubernetes-plain colored"></i> Kubernetes</span>
                <span class="tech-icon"><i class="devicon-ansible-plain colored"></i> Ansible</span>
                <span class="tech-icon"><i class="devicon-terraform-plain colored"></i> Terraform</span>
                <span class="tech-icon"><i class="devicon-githubactions-plain colored"></i> GitHub Actions</span>
                 <!-- Fila 2 -->
                <span class="tech-icon"><i class="devicon-bash-plain"></i> Bash</span>
                <span class="tech-icon"><i class="devicon-python-plain colored"></i> Python</span>
                <span class="tech-icon"><i class="devicon-go-plain colored"></i> Go</span>
                <span class="tech-icon"><i class="devicon-nodejs-plain colored"></i> Node.js</span>
                <span class="tech-icon"><i class="devicon-git-plain colored"></i> Git</span>
                <span class="tech-icon"><i class="devicon-postgresql-plain colored"></i> PostgreSQL</span>
                <span class="tech-icon"><i class="devicon-mongodb-plain colored"></i> MongoDB</span>
            </div>
        </section>

        <!-- Sección de Filosofía de Trabajo -->
        <section class="mb-12">
            <h2 class="text-2xl font-bold mb-8 text-center">Mi Filosofía de Trabajo</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Columna 1: Código Limpio -->
                <div class="bg-gray-800 p-6 rounded-lg border border-gray-700">
                    <h3 class="font-bold text-xl mb-3 text-white">Código Limpio</h3>
                    <p class="text-gray-300">
                        Creo que el software debe ser legible y mantenible. Un código limpio es la base de un producto sostenible y colaborativo.
                    </p>
                </div>
                <!-- Columna 2: Automatización -->
                <div class="bg-gray-800 p-6 rounded-lg border border-gray-700">
                    <h3 class="font-bold text-xl mb-3 text-white">Automatización</h3>
                    <p class="text-gray-300">
                        Busco automatizar todo, desde la infraestructura (IaC) hasta el CI/CD. La automatización reduce errores y acelera la entrega de valor.
                    </p>
                </div>
                <!-- Columna 3: Rendimiento -->
                <div class="bg-gray-800 p-6 rounded-lg border border-gray-700">
                    <h3 class="font-bold text-xl mb-3 text-white">Rendimiento</h3>
                    <p class="text-gray-300">
                        Diseño y optimizo sistemas para que sean rápidos, eficientes en el uso de recursos y capaces de escalar bajo cualquier demanda.
                    </p>
                </div>
            </div>
        </section>

        <!-- Sección de Contacto -->
        <section>
            <h2 class="text-2xl font-bold mb-6 text-center">¡Conecta Conmigo!</h2>
            <div class="flex justify-center items-center gap-6">
                <a href="#" class="tech-icon text-lg"><i class="fab fa-linkedin colored"></i> LinkedIn</a>
                <a href="#" class="tech-icon text-lg"><i class="fab fa-twitter colored"></i> Twitter</a>
                <a href="#" class="tech-icon text-lg"><i class="fas fa-envelope colored"></i> Email</a>
            </div>
        </section>

    </div>

    <!-- Botón de perfil flotante -->
    <button class="fixed bottom-5 right-5 bg-gray-700 hover:bg-gray-600 text-white w-12 h-12 rounded-full flex items-center justify-center shadow-lg">
        <i class="fas fa-user"></i>
    </button>

</body>
</html>

