<template>
    <div class="mark">
        <h3 id="name" class="title">Mark Marolf</h3>
        <p id="links">Youtube</p>
    </div>
</template>

<script>
export default {
  name: 'main',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.mark{
  font-size: name;

}
</style>
