<script>
  import catConstruction from "./assets/catConstruction.png";
</script>

<main>
  <div>
    <img src={catConstruction} class="logo" alt="Cat Under Construction" />
  </div>
  <h1>AMS Portfolio</h1>

  <p>Under Construction</p>
  <p>
    Check out <a
      href="https://abbystarnes.github.io/2017-portfolio/"
      target="_blank"
    >
      my old portfolio site
    </a>in the meantime.
  </p>
</main>

<style>
  .logo {
    height: 15em;
    padding: 1.5em;
    will-change: filter;
    transition: filter 300ms;
  }
  .logo:hover {
    filter: drop-shadow(0 0 2em #646cffaa);
  }
</style>
