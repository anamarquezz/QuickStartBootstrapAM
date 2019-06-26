<template>
    <div class="alert alert-primary" role="alert">{{propiedadNueva}}</div>
</template>

<script>
import { mapState, mapActions} from "vuex";
export default {
    name: "mivista",
    data(){

    },
    computed: {
        ...mapState({
            propiedadNueva: 'propiedadNueva'
        })
    },
    methods:{}
}
</script>
