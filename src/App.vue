<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Title from './components/Title.vue';
</script>

<template>
  <main>

    <section>

      <div class="padding">
        <Title title="DEVELOPPEUR BACKEND" class="margin-top"/>
        <Title title="PRODUCTEUR AUDIOVISUEL" />
        <img src="./assets/nyandylpb.png" alt="ny_andy" class="img-ny-andy">
      </div>

      <div class="padding">
        <Title title="NY ANDY" class="margin-top position-right"/>
        <Title title="RADRIANARIMANANA" class="position-right"/>
      </div>
      
    </section>

    <div class="background-violet relative">
      <img src="./assets/background-personality.png" alt="background personality" class="absolute">
      <p class="text-center">“ Words could describe it of how far I go ”</p>
    </div>

  </main>
</template>

<style scoped>
.padding {
  padding-left: 7rem;
  padding-right: 7rem;
}
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

.text-center {
  text-align: center;
  font-size: 24px;
  z-index: 1;
}

.background-violet {
  background-color: #280841;
  padding: 50px;
  margin-top: 50px;
}

.relative {
  position: relative;
  z-index: 0;
  padding-left: 0;
  padding-right: 0;
}

.absolute {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  z-index: -1;
  object-fit: contain;
  padding: 1.75rem;
}
</style>
