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
     },
     beforeCreate() {
    console.log('Component is about to be created.');
  },
  created() {
    console.log('Component has been created.');
    this.$emit("About page has been created");
  },
  beforeMount() {
    console.log('Component is about to be mounted.');
  },
  mounted() {
    console.log('Component has been mounted.');
  },
  beforeUpdate() {
    console.log('Component is about to update.');
  },
  updated() {
    console.log('Component has been updated.');
  },
  beforeUnmount() {
    console.log('Component is about to be unmounted.');
  },
  unmounted() {
    console.log('Component has been unmounted.');
  }
 }
 
 </script>
 
 <!-- Add "scoped" attribute to limit CSS to this component only -->
 <style scoped>
 
 .about{
     color: royalblue;
 }
 
 </style>
 