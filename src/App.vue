<template>
  <img class="logo" alt="sbw logo" src="./assets/sbw-logo.svg">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style lang="sass">
#app 
  @import "https://fonts.googleapis.com/css2?family=Nunito&display=swap"

*
  padding: 0
  margin: 0
  box-sizing: border-box

html
  font-size: 10px
  font-family: 'Nunito', sans-serif

body
  background-color: rgb(28, 27, 34)
  color: white
  min-height: 100vh
  display: flex
  align-items: center
  justify-content: center

section
  width: 100%

.container
  width: 90%
  max-width: 450px
  margin: 0 auto

form
  width: 100%
  background-color: rgb(42, 41, 42)
  padding: 20px
  border-radius: 8px

.number-fact
  width: 100%
  background-color: rgb(42, 41, 42)
  padding: 20px
  border-radius: 8px
  margin-top: 20px
  height: auto
  font-size: 20px

input[type="number"]
  width: 70%
  height: 40px
  border-radius: 4px
  outline: none
  border: none
  background-color: #3a3a3b
  font-size: 24px
  color: aliceblue
  padding-left: 10px

button
  display: inline-block
  width: 25%
  font-size: 24px
  height: 40px
  background-color: #3a3a3b
  color: aliceblue
  border: none
  outline: none
  cursor: pointer
  margin-left: 10px
  border-radius: 4px
</style>
