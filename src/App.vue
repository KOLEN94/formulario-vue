<template lang="pug">
 #app
    img(src="https://static.platzi.com/media/user_upload/Page%201-d8d869f4-7130-4ae9-9907-2fa809bd136a.jpg")
    h1 {{ msg }}
    form(id=form-platzi)
      div
        label(for="nombre") Nombre
        input(type="text" name="nombre" id="nombre")
      div
        label(for="apellidos") Apellidos
        input(type="text" name="apellidos" id="apellidos")
      div
        label(for="cargo") Cargo
        input(type="text" name="cargo" id="cargo")
      div
        button(type="submit" value="enviar") Enviar
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style lang="scss">
  @import './scss/main.scss';
</style>
