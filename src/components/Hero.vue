<template>
    <div class="container">
        <div class="jumbo">
            <Title/>
        </div>
    </div>
</template>

<script>

import Title from './Titolo.vue'

export default {
    name: '',
    components:{
        Title
    }
}
</script>

<style>
    .container{
        width: 90%;
        height: 500px ;
        margin: 0 auto;
    }
    .jumbo{
        width: 90%;
        height: 35%;
        background-color: rebeccapurple;
        display: flex;
        justify-content: center;
        align-items: center;
    }
</style>