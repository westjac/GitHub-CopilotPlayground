<template>
  <h1>{{ msg }}</h1>
</template>

<script>
export default {
    name: 'vueTest',
    data () {
        return {
            msg: 'Hello Vue!'
        }
    }
}

</script>

<style>
h1 {
    color: red;
}
</style>