<template>
  <ion-app>
    <ion-header>
        <ion-navbar>
            <ion-title>Ionic</ion-title>
        </ion-navbar>
    </ion-header>
    <ion-content padding>
        <p><router-link to="/">Go home</router-link></p>
        <h1>啦啦啦</h1>
    </ion-content>
  </ion-app>
</template>
 
<script>
export default {
  name: 'Detail',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>
 
<style scoped>
 
</style>
