<template>
    <div style="width: 100%; paddint-top: 10%;">
        <h1>Test</h1>
        <Splide :options="{ rewind: true }">
            <SplideSlide>
                <img src="image1.jpg" alt="Sample 1">
            </SplideSlide>
            <SplideSlide>
                <img src="image2.jpg" alt="Sample 2">
            </SplideSlide>
        </Splide>
        <!-- <slick
            ref="slick"
            :options="slickOptions"
            @afterChange="handleAfterChange"
            @beforeChange="handleBeforeChange"
            @breakpoint="handleBreakpoint"
            @destroy="handleDestroy"
            @edge="handleEdge"
            @init="handleInit"
            @reInit="handleReInit"
            @setPosition="handleSetPosition"
            @swipe="handleSwipe"
            @lazyLoaded="handleLazyLoaded"
            @lazyLoadError="handleLazeLoadError">
            <a href="http://placehold.it/2000x1000"><img src="http://placehold.it/2000x1000" alt=""></a>
            <a href="http://placehold.it/2000x1000"><img src="http://placehold.it/2000x1000" alt=""></a>
            <a href="http://placehold.it/2000x1000"><img src="http://placehold.it/2000x1000" alt=""></a>
            <a href="http://placehold.it/2000x1000"><img src="http://placehold.it/2000x1000" alt=""></a>
            <a href="http://placehold.it/2000x1000"><img src="http://placehold.it/2000x1000" alt=""></a>
        </slick> -->
        <!-- <swiper class="swiper" :options="swiperOption">
            <swiper-slide>Slide 1</swiper-slide>
            <swiper-slide>Slide 2</swiper-slide>
            <swiper-slide>Slide 3</swiper-slide>
            <swiper-slide>Slide 4</swiper-slide>
            <swiper-slide>Slide 5</swiper-slide>
            <swiper-slide>Slide 6</swiper-slide>
            <swiper-slide>Slide 7</swiper-slide>
            <swiper-slide>Slide 8</swiper-slide>
            <swiper-slide>Slide 9</swiper-slide>
            <swiper-slide>Slide 10</swiper-slide>
            <div class="swiper-button-prev" slot="button-prev"></div>
            <div class="swiper-button-next" slot="button-next"></div>
        </swiper> -->
        <!-- <swiper ref="mySwiper" :options="swiperOptions">
            <swiper-slide>Slide 1</swiper-slide>
            <swiper-slide>Slide 2</swiper-slide>
            <swiper-slide>Slide 3</swiper-slide>
            <swiper-slide>Slide 4</swiper-slide>
            <swiper-slide>Slide 5</swiper-slide>
            <div class="swiper-pagination" slot="pagination"></div>
        </swiper> -->
        <!-- <FlickingOne 
            ref="flicking"
            :options="{ align: 'prev', circular: true }"
            @move-end="onMoveEnd"
        >
            <div class="panel">
                <img style="width: 100%" src="https://images.unsplash.com/photo-1553095066-5014bc7b7f2d?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8Mnx8d2FsbCUyMGJhY2tncm91bmR8ZW58MHx8MHx8&w=1000&q=80" />
            </div>
            <div class="panel">
                <img style="width: 100%" src="https://images.unsplash.com/photo-1553095066-5014bc7b7f2d?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8Mnx8d2FsbCUyMGJhY2tncm91bmR8ZW58MHx8MHx8&w=1000&q=80" />
            </div>
            <div class="panel">
                <img style="width: 100%" src="https://images.unsplash.com/photo-1553095066-5014bc7b7f2d?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8Mnx8d2FsbCUyMGJhY2tncm91bmR8ZW58MHx8MHx8&w=1000&q=80" />
            </div>
        </FlickingOne>
        <FlickingTwo 
            ref="flicking"
            :options="{ align: 'prev', circular: true }"
            @move-end="onMoveEnd"
        >
            <div class="panel">
                <img style="width: 100%" src="https://images.unsplash.com/photo-1553095066-5014bc7b7f2d?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8Mnx8d2FsbCUyMGJhY2tncm91bmR8ZW58MHx8MHx8&w=1000&q=80" />
            </div>
            <div class="panel">
                <img style="width: 100%" src="https://images.unsplash.com/photo-1553095066-5014bc7b7f2d?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8Mnx8d2FsbCUyMGJhY2tncm91bmR8ZW58MHx8MHx8&w=1000&q=80" />
            </div>
            <div class="panel">
                <img style="width: 100%" src="https://images.unsplash.com/photo-1553095066-5014bc7b7f2d?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8Mnx8d2FsbCUyMGJhY2tncm91bmR8ZW58MHx8MHx8&w=1000&q=80" />
            </div>
        </FlickingTwo> -->
        <!-- <button v-on:click="nextClick">Test Next</button> -->
    </div>
</template>

<script>
    // import FlickingOne from "@egjs/vue3-flicking";
    // import FlickingTwo from "@egjs/vue3-flicking";
    // import "@egjs/vue3-flicking/dist/flicking.css";
    // import "@egjs/vue3-flicking/dist/flicking-inline.css";
    // import Axios from 'axios'

    // import { Swiper, SwiperSlide } from 'vue-awesome-swiper'
    // import 'swiper/css/swiper.css'
    // import Slick from 'vue-slick';

    import { Splide, SplideSlide } from '@splidejs/vue-splide'
    import '@splidejs/splide/dist/css/themes/splide-default.min.css'

    export default {
        name: 'TestPlugin',
        components: {
            Splide,
            SplideSlide
        },
        // components: { FlickingOne, FlickingTwo },
        // components: {
        //     Swiper,
        //     SwiperSlide
        // },
        // components: { Slick },

        data () {
            return {
                value: 0,
                // swiperOption: {
                //     navigation: {
                //         nextEl: '.swiper-button-next',
                //         prevEl: '.swiper-button-prev'
                //     }
                // }
                // swiperOptions: {
                //     pagination: {
                //         el: '.swiper-pagination'
                //     },
                // }
                // slickOptions: {
                    // slidesToShow: 3,
                // },
            }
        },

        mounted() {
            // console.log(VueSlick)
            // this.GetData()
            // console.log(this.$store.state.LoginStatus)
            // let data = {
            //     "userName": "nurkartiko",
            //     "password": "P@ssw0rd"
            // }

            // let config = {
            //     url: "https://dev-be.kompasdata.id/api/Account",
            //     method: "post",
            //     headers: {
            //         "Content-Type": "application/json"
            //     },
            //     data: JSON.stringify(data)
            // }

            // let configGet = {
            //     url: "https://dev-be.kompasdata.id/api/Account",
            //     method: "get",
            //     headers: {
            //         "Authorization": "Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJJZCI6IjVhMTE0YmJmLTY2OTYtNDI3Ny05ZDQ4LTg1MmY0MTc3NDFjYyIsImh0dHA6Ly9zY2hlbWFzLnhtbHNvYXAub3JnL3dzLzIwMDUvMDUvaWRlbnRpdHkvY2xhaW1zL25hbWUiOiJudXJrYXJ0aWtvIiwiaHR0cDovL3NjaGVtYXMueG1sc29hcC5vcmcvd3MvMjAwNS8wNS9pZGVudGl0eS9jbGFpbXMvZW1haWxhZGRyZXNzIjoibnVya2FydGlrb0BnbWFpbC5jb20iLCJodHRwOi8vc2NoZW1hcy54bWxzb2FwLm9yZy93cy8yMDA1LzA1L2lkZW50aXR5L2NsYWltcy9uYW1laWRlbnRpZmllciI6IjkyMzRlMDAxLTBhNTktNDU3OS1iYjYxLTVmZGZiMGRmMjIwYiIsImh0dHA6Ly9zY2hlbWFzLm1pY3Jvc29mdC5jb20vd3MvMjAwOC8wNi9pZGVudGl0eS9jbGFpbXMvZXhwaXJhdGlvbiI6IkphbiBUaHUgMDYgMjAyMiAwNDo1Mjo0NiBBTSIsIm5iZiI6MTY0MTM1ODM2NiwiZXhwIjoxNjQxNDQ0NzY2LCJpc3MiOiJodHRwczovL2xvY2FsaG9zdDo3MTY4IiwiYXVkIjoiaHR0cHM6Ly9sb2NhbGhvc3Q6NzE2OCJ9.4XGYjQMTxd9WetXmni0bR54OScc2ULQ3dxYgKiuqw5s",  
            //     },
            // }

            // let configKgContent = {
            //     url: "https://kgcontent-api.kgmedia.id/api/auth/login",
            //     method: "post",
            //     headers: { "Content-Type": "application/json" },
            //     data: JSON.stringify({
            //         username: "arjuna@kompas.com",
            //         password: "kompas@labs"
            //     })
            // }

            // Axios(configKgContent).then(response => {
            //     console.log(response)
            // }).catch(err => {
            //     console.log(err)
            // })
        },

        methods: {
            // nextClick() {
            //     this.$refs.flicking.next()
            // },

            // GetData() {
            //     Axios('https://my-json-server.typicode.com/typicode/demo/db').then(response => {
            //         console.log(response)
            //     }).catch(err => {
            //         console.log(err.message)
            //     })
            // }
        }
    }
</script>

<style>
    /* @import url("node_modules/@egjs/vue-flicking/dist/flicking.css");
    @import url("node_modules/@egjs/vue-flicking/dist/flicking-inline.css"); */
    /* @import url("node_modules/@egjs/vue-flicking/dist/flicking.css");
    @import url("node_modules/@egjs/vue-flicking/dist/flicking-inline.css"); */
</style>
