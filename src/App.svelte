<script>
  import svelteLogo from './assets/svelte.svg'
  import viteLogo from '/vite.svg'
</script>


<header>
  <h1>Portafolio Camilo.json</h1>
  <iframe src="http://localhost:5173/#Experiencia" frameborder="0" title="Youtube video player"></iframe>

<nav>
  <a href="#Experiencia">Experiencia</a>
  <a href="#Proyectos">Proyectos</a>
  <a target="_blank" href="https://github.com/programadorisgod" rel="noreferrer" >GitHub</a>
</nav>

</header>



<main>
  
  <p>+3 años de experiencia como <strong>Ingeniero de sistemas</strong>. Creador, divulgador de programación y sub CEO de vopper community.</p>

<section>
  <h2 id="Experiencia">Experiencia</h2>
  <ul>
    <li>Universidada Popular del cesar - 2021</li>
    <li>Ministerio de cultura - 2023 </li>
  </ul>
</section>


<aside>
   <h3>Mis tecnologías favoritas</h3>
      <ul>
        <li>JavaScript</li>
        <li>NodeJS</li>
        <li>
          Svelte
        </li>
        <li>Svelkit</li>
        <li>TypeScript</li>
        <li>Docker</li>
        <li>Python</li>
        <li>Deno</li>
      </ul>
</aside>

<section id="Proyectos">
  <h3>Proyectos realizados</h3>
    <article>
      <header>
        <h4>ClassMaster</h4>
      </header>
      <p>Desarrollo de un aplicativo web para la gestion docente, con una interfaz amigable y moderna</p>
      <footer>
        <small>
          Tecnologías utilizadas: ReactJS, NodeJS, Express, MongoDB
        </small>
      </footer>
    </article>

    <article>
       <header>
          <h4>SafeSync</h4>
       </header>
       <p>Desarrollo app para almacenamiento en la nube</p>
       <footer> 
          <small> 
            Tecnologías utilizadas: Flutter, nodeJS, Express, MongoDB
          </small>
       </footer>
    </article>
</section>

<section>
  <h2>Contactame</h2>
  <form action="/" method="post">
    <fieldset>
      <legend>Información Personal</legend>
      <div>
        <label>Nombre:
          <input type="text" id="name" name="name" placeholder="Camilo" required>
          </label>
      </div>

       <label>
         Correo:
         <input type="email" placeholder="camilo@gmail.com" required>
       </label>

    </fieldset>

    <fieldset>
      <legend>Información Adicional</legend>
      <label >
         Teléfono:
         <input type="tel" placeholder="30420020"  required>
      </label>
    </fieldset>
   <input type="submit" value="enviar">
  </form>
</section>
<img loading="lazy" src={svelteLogo} alt="logo_svelte">
</main>


