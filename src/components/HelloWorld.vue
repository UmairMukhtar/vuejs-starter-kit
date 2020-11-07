<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      This is a simple vue js starter template for your awesome vue js website .
    </p>
    <h3>Follow Me for more updates</h3>
    <ul>
      <li>
        <a
          href="https://web.facebook.com/AenUmair/"
          target="_blank"
          rel="noopener"
          >Facebook</a
        >
      </li>
      <li>
        <a
          href="
https://pk.linkedin.com/in/umair-mukhtar-828510153"
          target="_blank"
          rel="noopener"
          >Linkedin</a
        >
      </li>
    </ul>
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
