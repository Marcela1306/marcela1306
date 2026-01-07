<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">

<style>
  body {
    font-family: 'Roboto', sans-serif;
    background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
    margin: 0;
    padding: 20px;
  }
  .fade-in {
    animation: fadeIn 1.5s ease-in-out;
  }
  @keyframes fadeIn {
    from { opacity: 0; transform: translateY(20px); }
    to { opacity: 1; transform: translateY(0); }
  }
  .hover-3d {
    transition: transform 0.3s ease, box-shadow 0.3s ease;
  }
  .hover-3d:hover {
    transform: perspective(1000px) rotateY(10deg) scale(1.05);
    box-shadow: 0 20px 40px rgba(0,0,0,0.4);
  }
  .separator {
    height: 2px;
    background: linear-gradient(90deg, #2a9d8f, #e76f51);
    margin: 30px 0;
    border-radius: 1px;
  }
</style>

<!-- Título con animación 3D y gradiente mejorado -->
<h1 align="center" class="fade-in" style="font-family:'Roboto', sans-serif; font-size:3.5em; background: linear-gradient(45deg, #2a9d8f, #e76f51, #264653); -webkit-background-clip: text; color: transparent; font-weight:700; text-shadow: 2px 2px 4px rgba(0,0,0,0.3);">
  ¡Hola, soy Marcela Álvarez! 👋
</h1>

<!-- Subtítulo con efecto de entrada -->
<h3 align="center" class="fade-in" style="color:#264653; font-family:'Roboto', sans-serif; font-size:1.8em; font-weight:400; margin-top:10px;">
  Desarrolladora Full-Stack Junior | Estudiante de Ingeniería en Computación
</h3>

<!-- Descripción con enlace animado -->
<p align="center" class="fade-in" style="color:#264653; font-family:'Roboto', sans-serif; font-size:1.2em; line-height:1.6;">
   Actualmente explorando <strong style="color:#e76f51; text-shadow: 1px 1px 2px rgba(0,0,0,0.2);">el mundo</strong> <strong style="color:#e76f51; text-shadow: 1px 1px 2px rgba(0,0,0,0.2);">de la tecnologia</strong>, y creciendo profesionalmente.<br>
  📫 Me escribís a: <a href="mailto:agmarcela1301@gmail.com" style="color:#e76f51; text-decoration:none; transition: color 0.3s;" onmouseover="this.style.color='#264653'" onmouseout="this.style.color='#e76f51'">agmarcela1301@gmail.com</a><br>
  ⚡ Curiosidad nica: me encanta el cacao, pero el mondongo no es lo mío 😅
</p>

<p align="center" class="fade-in">
  <img src="https://media.giphy.com/media/l0MYt5jPR6QX5pnqM/giphy.gif" alt="3D animation" width="350" class="hover-3d" style="border-radius:20px; box-shadow: 0 15px 30px rgba(0,0,0,0.3); transform: perspective(1000px) rotateY(-5deg);"/>
</p>

<div class="separator"></div>

<!-- Sección de Proyectos con animación -->
<h3 align="center" class="fade-in" style="color:#2a9d8f; font-family:'Roboto', sans-serif; font-size:2em; font-weight:600;">🚀 Proyectos Destacados</h3>

<p align="center" class="fade-in" style="color:#264653; font-size:1.2em; line-height:1.6;">
  🚜 <strong>Livestock Manager</strong> – Sistema completo para gestionar ganado bovino: vacunas, partos y registros completos. Django + SQL.<br>
  Aprendí a combinar lógica, diseño y bases de datos para crear soluciones prácticas y útiles. (¡Aún aprendiendo a optimizarlo!)
</p>

<p align="center" class="fade-in">
  <img src="https://media.giphy.com/media/xT9IgzoKnwFNmISR8I/giphy.gif" alt="Livestock Manager Demo" width="350" class="hover-3d" style="border-radius:20px; box-shadow: 0 15px 30px rgba(0,0,0,0.3); transform: perspective(1000px) rotateY(5deg);"/>
</p>

<div class="separator"></div>

<h3 align="center" class="fade-in" style="color:#2a9d8f; font-family:'Roboto', sans-serif; font-size:2em; font-weight:600;">💻 Habilidades & Herramientas</h3>
<p align="center" class="fade-in">
  <a href="https://www.python.org/" title="Python">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="60" height="60" class="hover-3d" style="margin:10px;"/>
  </a>
  <a href="https://www.djangoproject.com/" title="Django">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/django/django-plain.svg" width="60" height="60" class="hover-3d" style="margin:10px;"/>
  </a>
  <a href="https://www.w3schools.com/css/" title="CSS3">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="60" height="60" class="hover-3d" style="margin:10px;"/>
  </a>
  <a href="https://www.w3.org/html/" title="HTML5">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="60" height="60" class="hover-3d" style="margin:10px;"/>
  </a>
  <a href="https://www.javascript.com/" title="JavaScript">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="60" height="60" class="hover-3d" style="margin:10px;"/>
  </a>
  <a href="https://git-scm.com/" title="Git">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="60" height="60" class="hover-3d" style="margin:10px;"/>
  </a>
  <a href="https://www.mathworks.com/products/matlab.html" title="MATLAB">
    <img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" width="60" height="60" class="hover-3d" style="margin:10px;"/>
  </a>
  <a href="https://www.chartjs.org/" title="Chart.js">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/chartjs/chartjs-original.svg" width="60" height="60" class="hover-3d" style="margin:10px;"/>
  </a>
</p>


<p align="center" class="fade-in" style="color:#264653; font-size:1.1em; font-style:italic;">
  🌱 S¡Próximos en mi lista: certificaciones!
</p>

<div class="separator"></div>

 
<h3 align="center" class="fade-in" style="color:#2a9d8f; font-family:'Roboto', sans-serif; font-size:2em; font-weight:600;">🤝 Conectemos</h3>
<p align="center" class="fade-in">
  <a href="https://linkedin.com/in/marcela-álvarez-663ba9231" target="_blank">
    <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" width="50" height="50" class="hover-3d" style="margin:0 20px;"/>
  </a>
  <a href="https://www.instagram.com/marce_virginia1/" target="_blank">
    <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" width="50" height="50" class="hover-3d" style="margin:0 20px;"/>
  </a>
</p>

<div class="separator"></div>

<h3 align="center" class="fade-in" style="color:#2a9d8f; font-family:'Roboto', sans-serif; font-size:2em; font-weight:600;">📊 Mis Estadísticas</h3>
<p align="center" class="fade-in">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=marcela1306&layout=compact&theme=radical" alt="Top Languages" style="margin:15px; border-radius:15px; box-shadow: 0 10px 20px rgba(0,0,0,0.2);"/>
  <img src="https://github-readme-stats.vercel.app/api?username=marcela1306&show_icons=true&theme=radical" alt="GitHub Stats" style="margin:15px; border-radius:15px; box-shadow: 0 10px 20px rgba(0,0,0,0.2);"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=marcela1306&theme=radical" alt="Streak Stats" style="margin:15px; border-radius:15px; box-shadow: 0 10px 20px rgba(0,0,0,0.2);"/>
</p>

<!-- Contador de visitas para impacto -->
<p align="center" class="fade-in">
  <img src="https://komarev.com/ghpvc/?username=marcela1306&label=Profile%20views&color=2a9d8f&style=flat" alt="Profile views" />
</p>

<p align="center" class="fade-in" style="font-size:1.2em; color:#264653; font-style:italic; margin-top:30px;">
  <i>Muchas veces me puedo bloquear en código, pero es parte del proceso de crecimiento como junior. 🚀</i>
</p>
