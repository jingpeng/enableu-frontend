<template>
  <div class="container">
    <div class="banner">
    </div>
    <div class="menu">
    </div>
    <div class="cover">
    </div>
    <div class="selection">
    </div>

    <div class="article">
    </div>
    <div class="article">
    </div>
    <div class="article">
    </div>
    <div class="article">
    </div>
    <div class="article">
    </div>
    <div class="article">
    </div>
    <div class="article">
    </div>
    <div class="article">
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home',
}
</script>

<style scoped>
.container {
  display: flex;
  flex-direction: column;
}

.banner {
  width: 7.5rem;
  height: 1.15rem;
  background: red;
}

.menu {
  width: 7.5rem;
  height: 0.61rem;
  background: black;
}

.cover {
  width: 7.5rem;
  height: 2.34rem;
  background: grey;
}

.selection {
  width: 7.5rem;
  height: 1.86rem;
  background: green;
}

.article {
  width: 7.5rem;
  height: 1.725rem;
  margin-bottom: 0.105rem;
  background: purple;
}
</style>
