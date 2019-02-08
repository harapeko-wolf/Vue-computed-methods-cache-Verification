<template>
  <div>
    <div>
      <h2>Computed</h2>
      <ol>
        <li>{{ computedNumber }}</li>
        <li>{{ computedNumber }}</li>
        <li>{{ computedNumber }}</li>
      </ol>
    </div>
    <div>
      <h2>Methods</h2>
      <ol>
        <li>{{ methodsNumber() }}</li>
        <li>{{ methodsNumber() }}</li>
        <li>{{ methodsNumber() }}</li>
      </ol>
    </div>
  </div>
</template>

<script>
export default {
  name: "Cash",
  data() {
    return {};
  },
  computed: {
    computedNumber: function() {
      return Math.random();
    }
  },
  methods: {
    methodsNumber: function() {
      return Math.random();
    }
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1,
h2 {
  font-weight: normal;
}
ul {
  // list-style: ;
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
