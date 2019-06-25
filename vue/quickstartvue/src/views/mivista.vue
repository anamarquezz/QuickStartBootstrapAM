<template>
    <div class="alert alert-primary" role="alert">{{propiedadNueva}}</div>
</template>

<<script>
import { mapState, mapActions, mapGetters } from "vuex";

export default {
    name: "mivista",
    components: {},
    data() {
        return {
        texto: "Mi Vista"
        };
    },
    computed: {
        ...mapState({
            propiedadNueva: "propiedadNueva"
        })
    },
    methods: {}
};

</script>

<style scoped>
<style>