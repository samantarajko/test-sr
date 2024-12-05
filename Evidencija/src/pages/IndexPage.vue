<template>
  <q-page class="flex flex-center">
    <img
      alt="Quasar logo"
      src="~assets/quasar-logo-vertical.svg"
      style="width: 200px; height: 200px"
    >
  </q-page>

  <btn
        class="q-mt-xl"
        color="white"
        text-color="blue"
        unelevated
        to='EvidencijaPage'
        label="Evidencija"
        no-caps
      />
      
</template>



<script setup>
defineOptions({
  name: 'IndexPage'
});
</script>
