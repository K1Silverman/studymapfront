<template>
  <div class="hello">
    <h1>Õpimapp</h1>
    <h2>Mis sa uut õppisid:</h2>

    <!-- Options päring andmebaasist -->
    <label for="subject"></label>
    <select id="subject"></select>
    <!-- Nupp, millega saab lisada subjecte Modalis -->
    <button>+</button>

    <vue-editor></vue-editor>
    
  </div>
</template>

<script>
import { VueEditor } from "vue2-editor";

export default {
  name: 'HelloWorld',
  components: {
    VueEditor
  },
  props: {
  },
  data() {
    return{
    }    
  }
}
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
