<template>
    <div class="about">
     This is Home Component
    </div>
 </template>
 
 <script>
 
 export default{
     name:"AboutPage",
     props: {
       about: String
     }
 }
 
 </script>
 
 <!-- Add "scoped" attribute to limit CSS to this component only -->
 <style scoped>
 
 .about{
     color: royalblue;
 }
 
 </style>
 