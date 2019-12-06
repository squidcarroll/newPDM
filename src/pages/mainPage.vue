/* eslint-disable */
<template>
  <div class="content">
    <div class="md-layout md-gutter">
      <div class="md-layout-item md-size-20">
        <login></login>
      </div>
      <div class="md-layout-item">
        <showData></showData>
      </div>
    </div>
  </div>
</template>

<script>
import tableify from 'tableify'
import showData from '../components/showData'
import login from '../components/login'

export default {
  name: 'mainPage',
  components: {
    showData,
    login
  },
  data() {
    return {}
  },
  methods: {}
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1,
h2 {
  font-weight: normal;
  color: white;
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
.content {
  padding: 20px;
}
</style>
