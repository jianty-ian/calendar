<template>
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <div class="container">
        <CalenderCard></CalenderCard>
    </div>
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
</template>

<script>
import CalenderCard from './components/CalenderCard.vue'

export default {
    name: 'App',
    components: {
        CalenderCard
    }
}
</script>

<style>
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
}
.container{
    padding: 0px 400px;
}
@media screen and (max-width:1904px) { 
    .container{
        padding: 0px 200px;
    }
}
@media screen and (max-width:1264px) { 
    .container{
        padding: 0px 100px;
    }
}
@media screen and (max-width:960px) { 
    .container{
        padding: 0px 50px;
    }
}

</style>
