<template>
  <div class="hyy">
    <div
      class="card "
      v-motion-slide-left
      
    >
    <CarDetailHero />
      <CarDetailAttribute />
      <CarDetailDescription />
      <CarDetailContact />
    </div>
    <div v-motion-slide-visible-once-left >
      <CarDetailHero />
      <CarDetailAttribute />
      <CarDetailDescription />
      <CarDetailContact />
    </div>
  </div>
</template>

<script>

</script>
