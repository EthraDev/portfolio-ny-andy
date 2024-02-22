<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Title from './components/Title.vue';
</script>

<template>
  <main>

    <div>
      <Title title="DEVELOPPEUR BACKEND" class="margin-top"/>
      <Title title="PRODUCTEUR AUDIOVISUEL" />
      <img src="./assets/nyandylpb.png" alt="ny_andy" class="img-ny-andy">
    </div>

    <Title title="NY ANDY" class="margin-top position-right"/>
    <Title title="RADRIANARIMANANA" class="position-right"/>
  </main>
</template>

<style scoped>
.margin-top {
    margin-top: 50px;
}

.img-ny-andy {
    width: 555px;
    height: 250px;
    object-fit: cover;
    object-position: 50% 30%;
}

.position-right {
    text-align: right;
}
</style>
