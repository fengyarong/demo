<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h1>
 <router-link to="day01">跳转至HelloVue</router-link>
  </h1>
  </div>
</template>
 
<script>
export default {
  name: 'hello',
  data () {
    return {
      msg: 'hello world'
  }
}
}
</script>
