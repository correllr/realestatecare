<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      Caring is in our nature
    </p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  margin: 20px 0;
  color: rgba(0,170,162,1);
}
p {
  display: inline-block;
  font-size: 150%;
  margin:auto;
  color: white;
  background:linear-gradient(90deg, rgba(71,94,108,1) 0%, rgba(20,27,31,1) 50%);
  padding: 1rem 1.5rem;
  border-radius: 0.5rem;
}
</style>
