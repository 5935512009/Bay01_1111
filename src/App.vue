<template >
  <div id="app" class="bg-blue-500 w-full" >
    <div class="grid grid-cols-12">
        <div class="border-solid border-4 border-green-400 col-span-6 xl:col-span-2">
          <div>Name: 'dd'</div>
          <div>color: 'red'</div>
        </div>
        <div class="border-double border-4 border-red-300">bb</div>
        <div class="border-double border-4 border-red-300">bb</div>
        <div class="border-double border-4 border-red-300">bb</div>
        <div class="border-double border-4 border-red-300">bb</div>
        <div class="border-double border-4 border-red-300">bb</div>
        <div class="border-double border-4 border-red-300">bb</div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'App',
  components: {
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
