<template>
  <div>
    <h1>Registrar</h1>
    <UiTextInput type="text" name="username" placeholder="Digite seu nome de usuário" />
    <background />
  </div>
</template>

<script setup>
// import background from '../components/BackgroundBody.vue';
// import logo from '../components/logoLogin.vue';
// import btn from '../components/ButtonInput.vue';
import { UiButton, background, Uilogo, UiTextInput } from '../components/index.js'
</script>

<style>
.register {
  top: 500px;
}
</style>
