<template>
<img alt="Vue logo" src="./assets/logo.png">
<MonsterSlayer />
</template>

<script>
import MonsterSlayer from './components/MosterSlayer.vue'

export default {
    name: 'App',
    components: {
        MonsterSlayer
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
</style>
