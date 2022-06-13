<template>
    <div id="wrapper" class="divided">

        <Banner></Banner>

        <Posts></Posts>

        <Footer></Footer>

    </div>
</template>

<script>

    import Footer from './Footer.vue'
    import Banner from './Banner.vue'
    import Posts from './Posts.vue'

    export default {
        
        components: {
            Footer, Banner, Posts
        },

        data() {
            return {   }
        }
    }

</script>