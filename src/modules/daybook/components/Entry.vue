<template>
    <div
        class=" entry-container mb-3 pointer p-2"
        @click="$router.push({ name: 'entry', params: { id: 10 } } )">
    
        <div class="entry-title d-flex">
            <span class="text-success fs-5 fw-bold">20</span>
            <span class="mx-1 fs-5">Julio</span>
            <span class="mx-2 fw-light">2023</span>

        </div>

        <div class=" entry-description">
            Adipisicing occaecat fugiat eiusmod minim est. Officia sint anim anim enim nisi. Ea ut dolore aliqua deserunt adipisicing anim. Nostrud tempor mollit duis aliquip laborum fugiat dolore exercitation cupidatat veniam aliqua in. Laborum velit in velit amet quis nisi esse non dolor consequat mollit excepteur exercitation et. Sunt pariatur dolor veniam culpa id. Aliqua tempor amet aute cupidatat qui in incididunt enim veniam proident commodo.
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
    transition:  0.2s all ease-in;

    &:hover {
        background-color: lighten($color: grey, $amount: 45);
        transition:  0.2s all ease-in;
    }
    .entry-description {
        font-size: 12px;
    }
 }
</style> 