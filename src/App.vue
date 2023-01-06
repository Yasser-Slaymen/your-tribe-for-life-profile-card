<script setup>
import Title from './components/Title.vue'
import Specialty from './components/Specialty.vue'
import Interests from './components/Interests.vue'

</script>

<template>
<div class="container">
  <img alt="logo" class="photo" src="./assets/ys.jpg"  />
  <img alt="logo" class="svg" src="./assets/tr.svg" />
  <img alt="logo" class="logo" src="./assets/logo.svg" />

  <section class="title"><Title/></section>
  <section class="special"><Specialty/></section>
  <section class="interests"><Interests/></section>
  
</div>
</template>

<style scoped>
.container{
  display: grid;
  grid-template-columns:repeat(10,10%);
  grid-template-rows: repeat(10,10%);
  width: 31vw;
  height:90vh;
  border-radius: 2%;
  margin: 0;
  background-color:rgba(255, 255, 255,1);
  padding: 0;
  position:relative;
  top: 1em;
}
.title{
  grid-column:3/10;
}
img{
 grid-column:6/8 ;
    grid-row:2/6 ;
    width:14vw;
    height:31vh;
    object-fit:cover;
    /* background-color:rgba(0, 0, 0,1); */
    border-radius: 8px;
    z-index: 999;
}
.svg{
  grid-column:3/4 ;
    width: 1.5vw;
    z-index: 999;
}
.special{
  grid-column:2/7;
  grid-row:3/8 ;
}
.interests{
grid-column:1/7 ;
grid-row:7/10 ;
}
.logo{
  grid-column:8/11 ;
  grid-row:10/11 ;
  width:6em;
  height: 1.5em;
}
</style>
