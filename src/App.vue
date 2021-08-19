<template>
  <div class="app ">
    <div class="bg-dark text-white p-3.5 text-start " id="nav">
      <router-link class="ml-20" id="rout" to="/">Cp Ecommerce</router-link> 
   
    </div>
    <router-view/>
  </div>
</template>

<style lang="css" scoped>
  #nav{
    font-size: 30px;
    font-weight: bold;
    font-family: Georgia, 'Times New Roman', Times, serif;
  }
 
 
</style>

