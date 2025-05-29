<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div class="profile">
    <img src="./assets/saya.jpg" alt="Foto Profil" class="profile-pic" />
    <h1>Fattah Fitriansyah</h1>
    <p>Saya merupakan mahasiswa prodi teknik informatika semester 4</p>
  </div>
</template>


<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.profile {
  text-align: center;
  padding: 2rem;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
.profile-pic {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  object-fit: cover;
  margin-bottom: 1rem;
}
</style>