<template>
<NavBar/>
<!-- <RouterLink to="/" class="button">Notes</RouterLink>|
<RouterLink to="/stats" class="button">Stats</RouterLink> -->
<div class="container is-max-desktop">
<RouterView />

</div>
</template>

<script setup>
import NavBar from './components/Layout/NavBar.vue';


</script>

<style>
@import 'bulma/css/bulma.min.css';
</style>