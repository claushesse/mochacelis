<template>
  <footer id="footer" class="bg-grey">
    <b-container>
      <b-row>
        <b-col class="col-12 col-md-6 section-heading">
          <h2>
            <span class="initial">
              {{$t('contact.title')[0]}}</span>{{ $t('contact.title').substr(1)}}
          </h2>
        </b-col>
      </b-row>
      <b-row class="contact-body mb-5">
        <b-col class="col-12 col-md-6">
          <div class="address">
            <p>Bachillerato Popular Trans Mocha Celis</p>
            <p>Av. Federico Lacroze 4181, 5to piso.</p>
            <p>Buenos Aires, Bs. As.</p>
            <p>C1427EDG ARGENTINA</p>
            <p>Tel: +54 (011) 4554-9048</p>
          </div>
          <div class="email-list">
            <p>Consultas generales: </p>
            <a href="info@bachilleratomochacelis.edu.ar">info@bachilleratomochacelis.edu.ar</a>
            <p>Apoyos y donaciones: </p>
            <a href="cooperadora@bachilleratomochacelis.edu.ar">cooperadora@bachilleratomochacelis.edu.ar</a>
            <p>Estudiantes:</p>
            <a href="preceptoria@bachilleratomochacelis.edu.ar">preceptoria@bachilleratomochacelis.edu.ar</a>
          </div>
          <ul class="social-links">
            <li>
              <a
                target="_blank"
                href="https://www.facebook.com/mochacelis/"
                title="Facebook"
              ><font-awesome-icon :icon="['fab', 'facebook-square']" /><span class="sr-only">Facebook</span></a>
            </li>
            <li>
              <a
                target="_blank"
                href="https://www.instagram.com/mochacelis/"
                title="Instagram"
              ><font-awesome-icon :icon="['fab', 'instagram']" /><span class="sr-only">Instagram</span></a>
            </li>
            <li>
              <a
                target="_blank"
                href="https://twitter.com/BachiTransMocha"
                title="Twitter"
              ><font-awesome-icon :icon="['fab', 'twitter']" /><span class="sr-only">Twitter</span></a>
            </li>
             <li class="mt-1 mb-1">
              <a
                target="_blank"
                href="info@bachilleratomochacelis.edu.ar"
                title="Mail"
              ><font-awesome-icon :icon="['fas','envelope']" /><span class="sr-only">Mail</span></a>
            </li>
          </ul>
        </b-col>
        <b-col class="col-12 col-md-6 map">
          <iframe 
            id="map"
            src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d6569.3518211253695!2d-58.458708037097146!3d-34.58706615504157!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0xd437cf863662c1c2!2sBachillerato%20Popular%20Mocha%20Celis!5e0!3m2!1ses-419!2sar!4v1590551191925!5m2!1ses-419!2sar" 
            frameborder="0" style="border:0;" allowfullscreen="" aria-hidden="false" tabindex="0"></iframe>
        </b-col>
      </b-row>
      <b-row>
        <b-col class="col-12">
          <div class="real-footer text-center">
            <small class="mb-3 made-with mt-3" v-html="$t('footer.signature')"></small>
            <div class="licence-cont">
              <a
                rel="license"
                href="http://creativecommons.org/licenses/by-sa/4.0/"
              >
                <img
                  class="mb-2"
                  alt="Licencia Creative Commons"
                  src="static/img/licence.png"
                >
              </a>
              <small class="licence">{{ $t('footer.licence') }} <a href="http://creativecommons.org/licenses/by-sa/4.0/">{{ $t('footer.licenceLinkTitle') }}</a>.</small>
            </div>
          </div>
        </b-col>
      </b-row>
    </b-container>
  </footer>
</template>

<script>
export default {}
</script>
