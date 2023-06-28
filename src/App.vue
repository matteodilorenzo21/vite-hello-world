<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';
export default {
    data() {
        return {};
    },
    components: { AppTitle, AppHero }
}
</script>

<template>
<!-- App Title -->
<AppTitle />

<!-- App Hero -->
<AppHero class="text-center" />
</template>

<style>

</style>