<template>
  <div
  class="entry-container mb-3 pointer p-2"
  @click="$router.push({ name: 'entry', params: { id: 10 }})"
  >
<!-- Titulo -->
    <div class="entry-title d-flex">
        <span class="text-success fs-5 fw-bold">08</span>
        <span class="mx-1 fs-5">Enero</span>
        <span class="mx-2 fw-light">2024, lunes </span>
    </div>

    <div class="entry-description">
Laboris aute labore voluptate esse sint eiusmod. Culpa magna voluptate minim veniam tempor qui magna duis cillum. Excepteur eiusmod exercitation amet sit non Lorem velit pariatur Lorem qui est.
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.entry-container {
  border-bottom: 2px solid #ff51cc;
  transition: 0.2s all ease-in;

  &:hover {
    background-color: lighten($color: rgb(252, 31, 204), $amount: 60);
    transition: 0.2s all ease-in;
  }

  .entry-description {
    font-size: 12px
  }
}
</style>