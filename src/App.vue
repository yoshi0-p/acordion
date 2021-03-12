<template>
 <div>
  <div class="gray flame">
    <button v-on:click= "acr" >アコーディオン</button>
  </div>
  <div class= "white flame" v-if = "acr">
  </div>
  </div>
</template>

<style scoped>
.flame{
  height:50px;
  width:400px;
  border: medium solid #000000;
}
.gray{
  background-color:gray;
}
</style>