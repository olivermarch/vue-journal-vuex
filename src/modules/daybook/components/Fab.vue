<template>
    <button class="btn btn-primary">
        <i class="fa fa-2x"
           :class="icon">
        </i>
    </button>
</template>

<script>
export default {

    props: {
        icon: {
            type: String,
            default: 'fa-plus'
        }
    }

}
</script>

<style lang="scss" scoped>

    button{
        position: fixed;
        bottom: 20px;
        right: 20px;
        width: 70px;
        height: 70px;
        border-radius: 100%;
        filter:  drop-shadow(5px 5px 5px rgb(117, 117, 117));

    }

</style>