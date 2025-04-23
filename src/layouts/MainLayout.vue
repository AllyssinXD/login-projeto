<template>
  <div>
    <background />
    <Uilogo/>
    <Uilogo />
    <UiButton :label="'Entrar'" />
    <UiButton
      class="register"
      :label="'Cadastre-se'"
      :click="
        () => {
          router.push('/register')
        }
      "
    />
  </div>
</template>

<script setup>
// import background from '../components/BackgroundBody.vue';
// import logo from '../components/logoLogin.vue';
// import btn from '../components/ButtonInput.vue';
import { UiButton, background, Uilogo } from '../components/index.js'
import { useRouter } from 'vue-router'

const router = useRouter()
</script>

<style>
.register {
  top: 500px;
}
</style>
