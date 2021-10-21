<template>
  <div class="hello">
    <h2 class="bg-red">{{ heading }}</h2>
    <p>{{ bodyContent }}</p>
  </div>

</template>

<script>
export default {
  data:function(){
    return {
      heading:"Welcome to our first application in Vue",
      bodyContent:"This is a message from the component. And WOW! it works!"
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h2{
}
</style>
