<script>
    import Title from './components/AppTitle.vue'
    import Jumbo from './components/Jumbo.vue'
    export default {
        components: {
            Title,
            Jumbo
        },
        data () {
            return {
                message: 'Welcome to my Vue app!'
            }
        }
    }
</script>

<template>
    <Title/>
    <Jumbo/>
</template>

<style scoped>
</style>