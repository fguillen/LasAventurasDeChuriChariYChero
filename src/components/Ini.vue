<template>
  <div>
    <div class="container-sm col-lg-7 px-3 py-3 pt-md-4 pb-md-4 mx-auto text-center">
      <h1 class="display-4">Las aventuras de Churi, Chari y Chero</h1>

      <img class="front-image" src="/assets/image_0.jpg">

      <p class="lead">
        Churi, Chari y Chero no son unos niños normales, ningún niño lo es.
        Churi, Chari y Chero viven en nuestro mundo pero para ellos este mundo es algo diferente.
        Gracias a su imaginación, y a su especial manera de ver, nuevos mundos se abren ante ellos.
        Nuevos y extraños amigos les acompañan. Acompáñalos también tú.
      </p>

      <p class="lead">
        Este libro ha sido creado con la intención de ser leído en voz alta, para disfrutar de una
        experiencia lectora con tus hijos. Una experiencia repleta de aventuras y de encuentros excitantes y llenos de
        emoción.
        Un viaje por las experiencias, la comunicación, la imaginación y la intención de conocer al otro.
      </p>
    </div>

    <div class="container">
      <div class="card-deck mb-3 text-center">
        <div class="card mb-4 shadow-sm">
          <div class="card-header">
            <h4 class="my-0 font-weight-normal">Lee el libro</h4>
          </div>
          <div class="card-body">
            <h1 class="card-title pricing-card-title">Gratis</h1>
            <p class="card-text">
              He escrito este libro para ser leído. Si no tienes dinero o si no estás seguro o segura de si te va a
              gustar,
              no hace falta que pagues nada, puedes leerlo y disfrutarlo completamente gratis.
            </p>
            <router-link to="/read" class="btn btn-primary">Leer gratis</router-link>
          </div>
        </div>
        <div class="card mb-4 shadow-sm">
          <div class="card-header">
            <h4 class="my-0 font-weight-normal">Compra el libro</h4>
          </div>
          <div class="card-body">
            <h1 class="card-title pricing-card-title">18 <small class="text-muted">euros</small></h1>
            <p class="card-text">
              Disfruta del libro en papel o en formato digital. Compártelo, léelo junto con tus hijos o
              deja que tus hijos lo lean ellos solos. Regálaselo a algún amigo o amiga cuando lo hayáis terminado.
            </p>
            <router-link to="/buy" class="btn btn-primary">Comprar el libro</router-link>
          </div>
        </div>
      </div>

      <footer class="pt-4 my-md-5 pt-md-5 border-top">
        <div class="row">
          <div class="col-12 col-md">

            <a href="https://www.registeredcommons.org/grid/RC-01-LIZ0000002793-3"><img
                alt="Registered at RegisteredCommons.org" style="border-width:0"
                src="https://www.registeredcommons.org/rc.gif" /></a>
            <div style="display:none">
              <span xmlns:dc="http://purl.org/dc/elements/1.1/" href="http://purl.org/dc/dcmitype/Text"
                property="dc:title" rel="dc:type">Las aventuras de Churi, Chari y Chero</span>
              was created by <span xmlns:dc="http://purl.org/dc/elements/1.1/" property="dc:title">Guzmán Requena</span>
              on <span xmlns:dc="http://purl.org/dc/elements/1.1/" property="dc:date">2019-12-14</span>.
              License: <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">
                http://creativecommons.org/licenses/by-nc-sa/4.0/ </a>.
              Description: <span xmlns:dc="http://purl.org/dc/elements/1.1/" property="dc:description">Libro de
                aventuras</span>
            </div>

            <small class="d-block mb-3 text-muted">&copy; 2019</small>

          </div>
          <!-- <div class="col-6 col-md">
            <h5>Features</h5>
            <ul class="list-unstyled text-small">
              <li><a class="text-muted" href="#">Cool stuff</a></li>
              <li><a class="text-muted" href="#">Random feature</a></li>
              <li><a class="text-muted" href="#">Team feature</a></li>
              <li><a class="text-muted" href="#">Stuff for developers</a></li>
              <li><a class="text-muted" href="#">Another one</a></li>
              <li><a class="text-muted" href="#">Last time</a></li>
            </ul>
          </div>
          <div class="col-6 col-md">
            <h5>Resources</h5>
            <ul class="list-unstyled text-small">
              <li><a class="text-muted" href="#">Resource</a></li>
              <li><a class="text-muted" href="#">Resource name</a></li>
              <li><a class="text-muted" href="#">Another resource</a></li>
              <li><a class="text-muted" href="#">Final resource</a></li>
            </ul>
          </div>
          <div class="col-6 col-md">
            <h5>About</h5>
            <ul class="list-unstyled text-small">
              <li><a class="text-muted" href="#">Team</a></li>
              <li><a class="text-muted" href="#">Locations</a></li>
              <li><a class="text-muted" href="#">Privacy</a></li>
              <li><a class="text-muted" href="#">Terms</a></li>
            </ul>
          </div> -->
        </div>
      </footer>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'HelloWorld'
  }
</script>

<style scoped>
  p.card-text {
    font-size: 1.2em;
  }

  h1 {
    line-height: 0.8;
  }

  .front-image {
    width: 100%;
  }
</style>
