<template>
    <div id="app">
        <router-view/>
    </div>
</template>

<script>
    import Navbar from './components/Navbar.vue'
    export default {
        name: 'App',
        components: {
            Navbar
        }

    }
</script>

<style>
    #app {
        font-family: 'Avenir', Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
    }
    /* TOGGLE THIS 'ALL-CONTAINERS OUTLINE' TO AID IN CSS LAYOUT */
    /* * {
        outline: black;
        outline-style: solid;
        outline-width: 1px;

    } */
</style>