<template>
  <div class="img-wrapper">
    <img class="photo p-1 rounded" src="/recent_photo.jpg" alt="近影" />
    <img
      class="photo p-1 rounded"
      src="/kuma_photo.jpg"
      alt="インターネットでのアイコン"
    />
  </div>
</template>

<script>
export default {
  name: 'PortfolioImages',
}
</script>

<style lang="scss">
.navbar {
  background-color: $color-green;
  color: $color-white;
  font-size: 32px;
  padding: 0 32px;
}

.img-wrapper {
  display: float;
}

.photo {
  width: 200px;
}
</style>
