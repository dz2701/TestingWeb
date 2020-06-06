<template>
  <div>
    <span>
      <button>{{message}}</button>
    </span>
  </div>
</template>

<script>
export default{
  data:new Promise(function(resolve, reject) {
    message: "click this button!"
  });
}
</script>

<style>
span {
  font-size:1.2em;
}
</style>
