<template>
  <header>
      <h1> {{valor }}</h1>
  </header>
</template>

<script>
export default {
  data() {
    return {
      valor : " Forget Exploded by Lin Fnx"
    }
  }

}
</script>


<style scoped>
  header{ 
    background-color: rgb(255, 0, 212);
    height: 50px;
    width: 100%;
    position: fixed;
    top: 0px;
    text-align: center;
    color: white;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    

}

</style>