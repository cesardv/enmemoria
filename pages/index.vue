<template>
  <div class="container">
    <div class="section links">
      <Nav />
    </div>
    <div class="section tribute">
      <h1 class="title">In memoriam</h1>
      <img height="292" src="~/assets/frontimage.png" alt="In memoriam" />
      <div class="subtitle"><div class="name">{{ $config.name }}</div>{{ $config.dates }}</div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss">

</style>
