<template>
  <div>
      <h2>Jumbotron</h2>
  </div>
</template>

<script>
export default {
    name: "Hero"
}
</script>

<style scoped>
    div {
        width: 100%;
        height: 300px;
        background-color: lightgrey;
        position: relative;
    }

    h2 {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
    }
</style>