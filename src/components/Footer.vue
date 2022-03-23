<template>
  <v-footer
    padless
    class="mt-auto"
  >
    <v-col
      class="text-center"
      cols="12"
    >  
      <v-card-text class="body-2">
        <strong>Todos los derechos reservados {{ new Date().getFullYear() }} — Facultad de Química, UNAM.</strong>
        Esta página puede ser reproducida con fines no lucrativos, siempre y cuando no se mutile, se cite la fuente completa y su dirección electrónica. 
        Contiene enlaces con diversos portales de entidades y organizaciones académicas, estudiantiles y profesionales, así como con páginas personales cuyos contenidos son de la responsabilidad
        exclusiva de sus titulares. <a href="https://quimica.unam.mx/aviso-de-privacidad/" >Aviso de privacidad</a>
      </v-card-text>
    </v-col>
  </v-footer>
</template>


<script>
  export default {
    data: () => ({
    }),
  }
</script>