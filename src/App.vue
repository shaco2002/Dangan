<script setup>  
import {ref} from'vue';
let counter = ref(0);

function add(){
  counter.value++;
}
  function sub(){
  counter.value--;
}

</script>

<template>
<div>
  <h1>{{counter}}</h1> 
      <button @click="add()"> + </button>
     <button @click="sub()"> - </button>
   </div>
  </template>
  <style>
  body{
    text-align: center;  
  }
  </style>
