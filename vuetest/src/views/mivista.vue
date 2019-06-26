<template>
    <div class="alert alert-primary" role="alert">Mi Vista</div>
</template>

<script>
import {mapState, mapActions} from "vuex";
export default {
    name: "mivista",
    components:{},
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
