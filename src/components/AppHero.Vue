<script>
    export default{
        data() {
            return {
                immagine: 'jumbotron.jpeg'
            }
        }
    }
</script>

<template>
    <div>
        <img class="pic" src="/images/idiocracy.jpeg" alt="jumbotron">
    </div>
    
</template>

<style scoped>
    div {
        text-align: center;
        width: 40%;
        margin: auto;
    }
    .pic {
       width: 100%
    }
</style>