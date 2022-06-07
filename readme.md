# Desafio Clase 28: Global & Child Process

## Iniciar proyecto con "node server.js"

### Consigna: USANDO EL OBJETO PROCESS

<ul>
    <li>Se utiliza un archivo .env cargado mediante la librería dotenv.</li>
    <li>Se agregó la ruta '/info' que presenta una vista sencilla los siguientes datos:
        <li>- Argumentos de entrada</li>
        <li>- Path de ejecución</li>
        <li>- Nombre de la plataforma (sistema operativo)</li>
        <li>- Process id</li>
        <li>- Versión de node.js - Carpeta del proyecto</li>
        <li>- Memoria total reservada (rss)</li>
    </li>
    <li>Agregar otra ruta '/api/randoms' que permita calcular un cantidad de números aleatorios en el rango del 1 al 1000 especificada por parámetros de consulta (query).</li>
    <li>Se devuelve al frontend un objeto que contiene como claves los números random generados junto a la cantidad de veces que salió cada uno.</li>
    <li>Esta ruta no es bloqueante. Se utiliza el método fork de child process.</li>
    <li>No hay bloqueo con una cantidad de 500.000.000 de randoms.</li>
</ul>
