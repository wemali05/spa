<template>
    <div>
        <h1>The User Page</h1>
        <hr>
        <button @click="navigateHome" class="btn btn-primary">Go to Home</button>
    </div>
</template>

<script>
export default {
    methods:{
        navigateHome(){
            this.$router.push('/');
        }
    }
}
</script>