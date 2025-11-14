<template>
  <div class="bg-gray-200 flex flex-col gap-2 w-screen justify-center items-center mt-10 pt-10 pb-10">
    <div class="w-1/3 flex monocraft-text flex-col gap-2 justify-center items-center ">
      <img src="../../assets/cat.png" class="rounded-xl" />
      <br>
      <h1 class="text-3xl font-bold minecraft-text">¡Hola!</h1>
      <br>
      <p class="text-xl italic">Este texto está siendo mostrado en un archivo llamado TestingGround.vue<br><br>
        También, este texto esta dentro del componente ExampleIssue1.vue, que es llamado en TestingGround.vue,
        esto para que vean donde se declaran los componentes y como importarlos<br><br>
        POR FAVOR,
        cuando hagan
        pruebas de sus componentes, importenlos y utilizenlos aquí en TestingGround y NO en App.vue<br>Esto es
        para evitar conflictos innecesarios de modificaciones que se hagan en App.vue<br><br>En ese mismo archivo del
        ExampleIssue pueden revisar como utilizar las fuentes incluidas</p>
      <p class="text-xl italic"><br>PERO, POR FAVOR, cualquier prueba que hagan
        para ver
        que sus
        componentes funcionen, no lo dejen aquí, asegurense de dejar este archivo como estaba cuando
        clonaron su rama</p><br>
      <p class="text-xl italic">Puntos extra [1-5] a quien <que class="font-4xl border-b-1">agregue</que>
        contenido a sus componentes que sea spam de
        mi <a href="https://mcpedl.com/user/r401/" class="text-xl italic text-indigo-600 border-b-2">portafolio</a> de
        Add-Ons de Bedrock</p>
      <p class="pt-6 text-3xl font-bold minercraftory-text">¡Gracias!</p><br>
      <img src="../../assets/chinese.gif" class="w-100 rounded-lg"></img>
    </div>
    <ExampleHeadlessUI></ExampleHeadlessUI>
  </div>
</template>

<style scoped>
.monocraft-text {
  font-family: 'Monocraft';
}

.minecraft-text {
  font-family: 'MinecraftSolid';
}

.minercraftory-text {
  font-family: 'Minercraftory';
}
</style>

<script setup>
//El script tiene que ir con setup pls
import ExampleHeadlessUI from '../ExampleHeadlessUI/ExampleHeadlessUI.vue'
</script>