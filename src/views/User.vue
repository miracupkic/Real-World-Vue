<template>
  <div class="user">
      <h1>This is {{username}} state of a curent route User</h1>
      <p>$route.params.username - {{$route.params.username}}</p>
  </div>
</template>

<script>
export default {
    props:["username"]

}
</script>

<style>

</style>