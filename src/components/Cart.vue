<template>
    <div>
        <h1>购物车</h1>
        {{name}}
    </div>
</template>
<script>
    import { mapState } from "vuex"
    export default{
        computed: {
            ...mapState("cart",["name"])
        }
    }
</script>