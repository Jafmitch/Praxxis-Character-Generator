<template>
    <div>
        <character-header></character-header>
    </div>
</template>

<script>
import CharacterHeader from "./components/CharacterHeader.vue";
export default {
    components: { CharacterHeader },
    name: "App",
};
</script>

<style>
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
}
</style>
