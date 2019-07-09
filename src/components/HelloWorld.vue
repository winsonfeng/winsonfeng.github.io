<template>
    <div class="hello">
        <p>{{ content1 }}</p>
    </div>
</template>

<script>
    export default {
        name: 'helloworld',
        data() {
            return{
                content1:"winson"
            };
        },
        // mounted() {
        //     this.axios.post("http://api.komavideo.com/news/list").then( aa => {
        //         this.content1=aa.data;
        //     })
        // }
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped  slot-scope=" " lang="scss">
    @import 'assets/css/index.scss';
</style>
