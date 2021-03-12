<template>
 <div>
  <div class="gray flame">
    <p v-on:click= "acr" >アコーディオン</p>
  </div>
  <div class= "white flame" v-if = "acr">
  </div>
  </div>
</template>

<style scoped>
.flame{
  height:50px;
  width:400px;
}
.gray{
  background-color:gray;
}
</style>