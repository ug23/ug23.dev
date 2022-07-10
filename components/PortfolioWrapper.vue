<template>
  <div>
    <div class="navbar">ug23.dev</div>
    <div class="container">
      <slot></slot>
    </div>
  </div>
</template>

<script>
export default {
  name: 'PortfolioWrapper',
}
</script>

<style lang="scss">
.navbar {
  background-color: $color-green;
  color: $color-white;
  font-size: 32px;
  padding: 0 32px;
}

.container {
  margin-top: 32px;
}
</style>
