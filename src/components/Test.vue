<template>
  <div class="hello">
    <h1 class="text-blue-500 font-bold my-8 text-2xl">{{ msg }}</h1>
    <p>
      Second Component
    </p>
  </div>
</template>

<script>
export default {
    name: "HelloWorld",
    props: {
        msg: String,
    },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
