<template>
   <div class="all">
    This is Home Component
   </div>
</template>

<script>

export default{
    name:"Home",
    props: {
      input: String
    }
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.all{
    color: blueviolet;
}

</style>
