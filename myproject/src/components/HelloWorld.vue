<template>
  <footer class="footer-layout theme--primary">
    <div class="padding text-center">
      <h3>Get In Touch</h3>
      <p><i class="fab fa-whatsapp"></i> +52 9848766365</p>
      <p><i class="fas fa-phone"></i> +52 9848766365</p>
      <article>
        <span><i class="far fa-envelope"></i></span>
        <span><i class="fab fa-facebook-square"></i></span>
        <span><i class="fab fa-instagram"></i></span>
      </article>
    </div>
    <div class="footer-layout__items padding text-center">
      <span><i class="far fa-clock"></i></span>
      <article>
        <p>Lunes a viernes de 9:00 am a 6:00 pm
        Sábados de 10:00 am a 2:00 pm
        Atencion fuera de horario, bajo cita previa.</p>
        
      </article>
    </div>
    <div class="footer-layout__items padding text-center">
      <span><i class="fas fa-map-marker-alt"></i></span>
      <article>
        <p>Av 10 Nte entre Calle 20 y
        Av. Constituyentes, Col.
        Centro, Playa del Carmen,
        Q. Roo. C.P. 77710</p>
      </article>
    </div>
    <div class="footer-layout__items padding text-center">
      <a href="" class="arrow"><i class="fas fa-arrow-alt-circle-up"></i></a>
      <article>
        <small>Derechos Reservados. Xtabay. 2018</small>
      </article>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'Footer',
  props:{
    msg:String
  }
}

