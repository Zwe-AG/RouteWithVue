<template>
    <div>
        <h1>Welcome to my Job Detail</h1>
        <p>{{ id }}</p>
    </div>
</template>

<script>
    export default {
        // data() {
        //     return {
        //         detail_id : this.$route.params.id
        //     }
        // },
        props :['id']
    }
</script>

<style lang="stylus" scoped>

</style>
