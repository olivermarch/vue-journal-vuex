<template>
    <nav class="navbar bg-primary">
        <a class="navbar-brand text-white"> 
            <img src="@/assets/logo.png" 
                 alt="Vue Logo"
                 height="24"
                 @click="goToHome"
                 class="d-inline-block align-text-top mx-2 pointer">

                 Daybook
        </a>

        <div>
            <button class="btn btn-outline-info mx-2">
                <i class="fa fa-sign-out-alt"></i>
            </button>
        </div>
    </nav>
</template>

<script>

export default {

    methods: {
        goToHome(){
            console.log('jpo;a')
            this.$router.push({name: 'home-view'})
        }
    }
}
</script>