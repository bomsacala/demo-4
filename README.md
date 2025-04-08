
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="/resources/css/style-1.css">
    <script src="/resources/js/script-12.js"></script>
    <script src="/resources/js/script-15.js"></script>
    <script src="/resources/js/script-66.js"></script>
    <title>WebCodem</title>
</head>
<body>
    <div class="menu">
      <div>WEBCODEM</div>
      <div class="menu__item" onclick="document.querySelector('.menu__dropdown').classList.toggle('menu__dropdown--active')"><svg id="toggleGear" class="gear" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="m9.25 22l-.4-3.2q-.325-.125-.613-.3t-.562-.375L4.7 19.375l-2.75-4.75l2.575-1.95Q4.5 12.5 4.5 12.337v-.674q0-.163.025-.338L1.95 9.375l2.75-4.75l2.975 1.25q.275-.2.575-.375t.6-.3l.4-3.2h5.5l.4 3.2q.325.125.613.3t.562.375l2.975-1.25l2.75 4.75l-2.575 1.95q.025.175.025.338v.674q0 .163-.05.338l2.575 1.95l-2.75 4.75l-2.95-1.25q-.275.2-.575.375t-.6.3l-.4 3.2h-5.5Zm2.8-6.5q1.45 0 2.475-1.025T15.55 12q0-1.45-1.025-2.475T12.05 8.5q-1.475 0-2.488 1.025T8.55 12q0 1.45 1.012 2.475T12.05 15.5Z"/></svg></div></div>
    <div class="menu__dropdown">
    <div class="menu__item">
        <div id="userContainer" class="a">
            <p id="userText" onclick="chooseProfilePicture()">Usuario</p>
        </div>
    </div>
    <br>
    <div class="menu__item">
        <svg xmlns="http://www.w3.org/2000/svg" width="1em" height="1em" viewBox="0 0 24 24" class="a">
            <path fill="currentColor" d="M7.5 2c-1.79 1.15-3 3.18-3 5.5s1.21 4.35 3.03 5.5C4.46 13 2 10.54 2 7.5A5.5 5.5 0 0 1 7.5 2m11.57 1.5l1.43 1.43L4.93 20.5L3.5 19.07zm-6.18 2.43L11.41 5L9.97 6l.42-1.7L9 3.24l1.75-.12l.58-1.65L12 3.1l1.73.03l-1.35 1.13zm-3.3 3.61l-1.16-.73l-1.12.78l.34-1.32l-1.09-.83l1.36-.09l.45-1.29l.51 1.27l1.36.03l-1.05.87zM19 13.5a5.5 5.5 0 0 1-5.5 5.5c-1.22 0-2.35-.4-3.26-1.07l7.69-7.69c.67.91 1.07 2.04 1.07 3.26m-4.4 6.58l2.77-1.15l-.24 3.35zm4.33-2.7l1.15-2.77l2.2 2.54zm1.15-4.96l-1.14-2.78l3.34.24zM9.63 18.93l2.77 1.15l-2.53 2.19z" />
        </svg>
        <select id="themeSelect" class="lang">
            <option value="dark">Oscuro</option>
            <option value="light">Claro</option>
        </select>
    </div>
    <div class="menu__item">
        <iconify-icon icon="ion:logo-tiktok" class="a"></iconify-icon><script src="https://code.iconify.design/iconify-icon/1.0.7/iconify-icon.min.js"></script> <a href="https://www.tiktok.com/@good.gaddiel?_t=8cwDAq1gBAk&_r=1" class="a">TikTok</a>
    </div>
    <div class="menu__item">
        <iconify-icon icon="fluent:person-support-24-regular" class="a"></iconify-icon><script src="https://code.iconify.design/iconify-icon/1.0.7/iconify-icon.min.js"></script> <a href="./soporte" class="a">Soporte</a>
    </div>
    </div>
    <br>
    <br>
    <div style="text-align: center;">
    <span class="letter">¡B</span>
    <span class="letter">I</span>
    <span class="letter">E</span>
    <span class="letter">N</span>
    <span class="letter">V</span>
    <span class="letter">E</span>
    <span class="letter">N</span>
    <span class="letter">I</span>
    <span class="letter">D</span>
    <span class="letter">O</span>
    <span class="letter">S!</span>
    <br>
    <br>
        <div style="border-left: 5px solid #007bff; padding-left: 10px;"><p>A mi página web, donde les mostraré lo que he aprendido sobre programación. Me apasiona crear páginas web con diferentes efectos, transiciones y elementos. Para ello, utilizo tres lenguajes de programación: html, css y javascript.</p></div>
        <div style="border-left: 5px solid #007bff; padding-left: 10px;"><p>Aquí les dejo un ejemplo de una página que he hecho usando estos tres lenguajes. Espero que les agrade y que me dejen sus opiniones y consejos para seguir aprendiendo. Gracias por su visita.</p></div>
        </div>
        <footer padding: 5px; text-align: center;">
        <a href="./funciones" style="color: #f3f3f3; text-decoration: none; margin: 0 10px; font-size: 16px; margin-right: -10px;">
        <svg xmlns="http://www.w3.org/2000/svg" width="1em" height="1em" viewBox="0 0 24 24" style="vertical-align: middle; margin-bottom: 2px;">
            <path fill="currentColor" d="M4 3a1 1 0 0 0-1 1v6a1 1 0 0 0 1 1h6a1 1 0 0 0 1-1V4a1 1 0 0 0-1-1zm0 10a1 1 0 0 0-1 1v6a1 1 0 0 0 1 1h6a1 1 0 0 0 1-1v-6a1 1 0 0 0-1-1zm10 0a1 1 0 0 0-1 1v6a1 1 0 0 0 1 1h6a1 1 0 0 0 1-1v-6a1 1 0 0 0-1-1zm1 6v-4h4v4zM5 9V5h4v4zm0 10v-4h4v4zm11-8V8h-3V6h3V3h2v3h3v2h-3v3z" />
        </svg> Funciones
       </a>       
       <a href="./codebot-4o" style="color: #f3f3f3; text-decoration: none; margin: 0 15px; font-size: 16px; margin-right: -10px;">  
           CodeBot
       </a>
       <a href="./postbook" style="color: #f3f3f3; text-decoration: none; margin: 0 15px; font-size: 16px; margin-right: -10px;">  
           PostBook
       </a>
       <a href="./marketplace" style="color: #f3f3f3; text-decoration: none; margin: 0 15px; font-size: 16px; margin-right: -10px;">
        Marketplace
        <svg xmlns="http://www.w3.org/2000/svg" width="1em" height="1em" viewBox="0 0 24 24" style="vertical-align: middle; margin-bottom: 2px;">
            <path fill="currentColor" d="M19 6h-2c0-2.8-2.2-5-5-5S7 3.2 7 6H5c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V8c0-1.1-.9-2-2-2m-7-3c1.7 0 3 1.3 3 3H9c0-1.7 1.3-3 3-3m7 17H5V8h14zm-7-8c-1.7 0-3-1.3-3-3H7c0 2.8 2.2 5 5 5s5-2.2 5-5h-2c0 1.7-1.3 3-3 3" />
        </svg>
     </a>
        </footer>
        <div style="text-align: center;">
        <div style="border-left: 5px solid #007bff; padding-left: 10px;"><p>Funciones en desarrollo</p></div>
        <div style="border-left: 5px solid #007bff; padding-left: 10px;"><p>Las funciones están en desarrollo y pueden contener bugs o fallos por el momento. Estamos trabajando para mejorarlas continuamente.</p></div>
        <div style="border-left: 5px solid #007bff; padding-left: 10px;"><p>Por el momento, ¡son completamente gratis!</p></div>
        <footer class="estilo">
        <br>
  <a href="./términos">Términos</a>
  <a href="./privacidad">Privacidad</a>
  <a href="./seguridad">Seguridad</a>
  <a href="./contacto">Contacto</a>
  <div class="container"> 
  <img id="imagen1" alt="Logo" class="image"> 
  <span class="text">&copy; 2025 WebCodem, Tec.</span> 
  </div>
  <br>
  </footer>
</div>
    <div style="text-align: center;">
    <div id="valoracion-section">
  <h5>¡Valora nuestra página!</h5>
  <div>
    <input type="radio" name="rating" value="1" onclick="enviarValoracion('1')"> 1
    <input type="radio" name="rating" value="2" onclick="enviarValoracion('2')"> 2
    <input type="radio" name="rating" value="3" onclick="enviarValoracion('3')"> 3
    <input type="radio" name="rating" value="4" onclick="enviarValoracion('4')"> 4
    <input type="radio" name="rating" value="5" onclick="enviarValoracion('5')"> 5
  </div>
    <h6>Nota: Te recomendamos que utilices las funciones de esta página antes de valorarla.</h6>
</div>
</div>
<script src="/resources/js/script-61.js"></script>
<script src="/resources/js/script-62.js"></script>
<script src="/resources/js/script-31.js"></script>
<script src="/resources/js/script-28.js"></script>
</body>
</html>
