<template>
  <div id="app">
    <div id="nav">
    </div>
    <router-view></router-view>
  </div>
</template>

<style lang="sass">
#app 
  font-family: Avenir, Helvetica, Arial, sans-serif
  -webkit-font-smoothing: antialiased
  -moz-osx-font-smoothing: grayscale
  text-align: center
  color: #2c3e50
  

body
  height: 100vh
  background-color: #eee

#nav 
  padding: 30px

  a 
    font-weight: bold
    color: #2c3e50

    &.router-link-exact-active 
      color: #42b983
    
  

</style>
