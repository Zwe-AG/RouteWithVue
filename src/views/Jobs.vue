<template>
        <h1>Welcome to our jobs</h1>
        <div v-for="job in jobs" :key="job.id">
            <router-link :to="{name:'JobDetail',params:{id:job.id}}">
                <h1>{{ job.title }}</h1>
            </router-link>  
        </div>
</template>

<script>
    export default {
        data() {
            return {
                jobs : [
                    {id:"1",title:"Web Developer"},
                    {id:"2",title:"Andriod Developer"},
                    {id:"3",title:"IOS Developer"},
                ]
            }
        },
    }
</script>

<style  scoped>
</style>
