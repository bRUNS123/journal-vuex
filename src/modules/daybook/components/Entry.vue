<template>
  <div class="entry-container mb-3 pointer p-2" @click="$router.push({name: 'entry', params: {id:10}})">
    <div class="entry-title d-flex">
        <span class="text-success fs-5 fw-bold">10</span>
        <span class="mx-1 fs-5">Enero</span>
        <span class="mx-2 fw-light">2023, Martes</span>
    </div>
  

  <div class="entry-description">Non dolor commodo laboris amet laboris amet enim Lorem anim est elit laborum reprehenderit. Sunt occaecat elit eiusmod excepteur cillum velit reprehenderit minim. Mollit excepteur laborum consequat non adipisicing consectetur occaecat laboris sunt in consequat ipsum. Magna ea officia nostrud non nostrud elit enim occaecat enim nisi do consectetur duis deserunt. Mollit ipsum Lorem pariatur irure elit commodo qui.
    </div>
</div>
</template>


<script>
export default {

}
</script>

<style lang="scss" scoped>
.entry-container {
    border-bottom: 1px solid #2c3e50;
    transition: 0.2s all ease-in;

    &:hover {
        background-color: lighten($color: grey, $amount: 45);
        transition: 0.2s all ease-in;
    }

    .entry-description {
        font-size: 12px;
    }
}

</style>