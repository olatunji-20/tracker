<template>

  <h1> {{ topic }} </h1>
  
  
</template>

<script>
export default {
  name: 'lead',
  data() {
    return {
      topic: "APPT. TRACKER"
    }
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  color: blue;
  font-family:'Courier New', Courier, monospace;
  font-size: 2rem;
}

@media screen and (max-width: 400px) {
  h1 {
    font-size: 1.5rem;
  }
}
</style>
