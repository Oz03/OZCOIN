<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Portafolio | Desarrollador Blockchain</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <div class="logo">DevCuba</div>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#habilidades">Habilidades</a></li>
                <li><a href="#proyectos">Proyectos</a></li>
            </ul>
        </nav>
    </header>

    <section id="inicio" class="hero">
        <h1>Hola, soy Programador de Software</h1>
        <p>Especialista en contratos inteligentes y soluciones web.</p>
        <a href="#proyectos" class="btn">Ver mis proyectos</a>
    </section>

    <section id="habilidades">
        <h2>Mis Habilidades</h2>
        <div class="skills-grid">
            <div class="skill-card">Solidity (TRC-20)</div>
            <div class="skill-card">HTML / CSS</div>
            <div class="skill-card">JavaScript</div>
            <div class="skill-card">Python</div>
        </div>
    </section>

    <section id="proyectos">
        <h2>Proyectos Recientes</h2>
        <div class="project-card">
            <h3>OZCOIN (Token TRC-20)</h3>
            <p>Contrato inteligente funcional desplegado en la red de TRON con funciones de Mint y Burn.</p>
        </div>
    </section>

    <footer>
        <p>&copy; 2026 - Creado con pasión desde Cuba</p>
    </footer>
</body>
</html>
/* Configuración General */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

body {
    background-color: #f4f7f6;
    color: #333;
    line-height: 1.6;
}

/* Navegación */
header {
    background: #2c3e50;
    color: white;
    padding: 1rem 0;
    position: fixed;
    width: 100%;
    top: 0;
    z-index: 1000;
}

nav {
    display: flex;
    justify-content: space-around;
    align-items: center;
    max-width: 1200px;
    margin: auto;
}

nav ul {
    display: flex;
    list-style: none;
}

nav ul li a {
    color: white;
    text-decoration: none;
    padding: 0 15px;
}

/* Sección Hero */
.hero {
    height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('https://images.unsplash.com/photo-1555066931-4365d14bab8c?auto=format&fit=crop&w=1000&q=80');
    background-size: cover;
    color: white;
    text-align: center;
    padding: 0 20px;
}

.hero h1 { font-size: 3rem; margin-bottom: 10px; }

.btn {
    margin-top: 20px;
    padding: 10px 25px;
    background: #e74c3c;
    color: white;
    text-decoration: none;
    border-radius: 5px;
}

/* Habilidades y Proyectos */
section {
    padding: 100px 20px;
    max-width: 1200px;
    margin: auto;
    text-align: center;
}

.skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
    gap: 20px;
    margin-top: 30px;
}

.skill-card, .project-card {
    background: white;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
}

.project-card h3 { color: #2c3e50; }
