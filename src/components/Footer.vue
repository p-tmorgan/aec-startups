<template>
  <div class="footer container-fluid py-4 text-center">
    <p class="muted">
      <a href="localhost:8080">Cox Design Technology</a>
      <span>|</span>
      <a href="localhost:8080">About</a>
    </p>
  </div>
</template>
<script>
export default {}
</script>

<style lang="scss">
@import '@/assets/scss/app.scss';

.footer {
  font-size: 85%;

  a {
    font-size: 85%;
    font-weight: 400;
    color: $body-color;
  }
  span {
    margin-left: 0.5rem;
    margin-right: 0.5rem;
  }
}
</style>
