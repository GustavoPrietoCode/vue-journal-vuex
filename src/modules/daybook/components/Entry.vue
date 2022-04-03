<template>
  <div
    class="entry-container mb-3 pointer p-2"
    @click="$router.push({ name:'entry', params: {id:1}})"
    >

    <!-- titulo -->
    <div class="entry-title d-flex">
        <span class="text-success fs-5 fw-bold">03</span>
        <span class="mx-1 fs-5">Abril</span>
        <span class="mx-2 fw-light">2022, domingo</span>
    </div>

    <div class="entry-description">
      Culpa nulla nulla fugiat officia nostrud laboris sit sint sit enim. Id laboris amet id veniam labore cillum ipsum. Id consectetur sint amet et eu ipsum do mollit. Aliquip culpa deserunt sunt pariatur adipisicing sit cillum id commodo.
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.entry-container{
  border-bottom: 1px solid #2c3e50;
  transition: 0.2s all ease-in;

  &:hover{
    background-color: lighten($color: grey, $amount: 45);
    transition: 0.2s all ease-in;
  }

  .entry-description{
    font-size: 12px;
  }
}
</style>