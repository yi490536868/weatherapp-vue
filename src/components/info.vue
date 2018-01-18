<template>
    <div class="hello">
        <h1>{{ msg }}</h1>
    </div>
</template>

<script>
    export default {
        mounted(){
            this.demo()
        },
        data () {
            return {
                msg: 'dewdede'
            }
        },
        methods: {
            demo () {
                console.log('demo fun')
            }
        }
    }
</script>

<style scoped>

</style>
