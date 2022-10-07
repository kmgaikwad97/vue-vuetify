<template>
<div class="photos pa-6">
    <h1>This is Photos Page</h1>
    <!-- <div class="imgs" v-for="images in img" :key="images.id">
        <v-container class="grey lighten-5">
            <v-row >
                <template v-for="n in 12" >
                    <v-col :key="n" cols="4">
                        <v-img :lazy-src="images.lazySrc" max-height="150" max-width="250" :src="images.imgSrc"></v-img>
                    </v-col>
                    <v-responsive v-if="n === 2" :key="`width-${n}`" width="100%"></v-responsive>
                </template>
            </v-row>
        </v-container>
        
    </div> -->
</div>
</template>

<script>
export default {
    data() {
        return {
            img: [{
                    id: 1,
                    imgSrc: "https://picsum.photos/id/11/500/300",
                    lazySrc: "https://picsum.photos/id/11/10/6",
                },
                {
                    id: 2,
                    imgSrc: "https://picsum.photos/id/11/500/300",
                    lazySrc: "https://picsum.photos/id/11/10/6",
                },
                {
                    id: 3,
                    imgSrc: "https://picsum.photos/id/11/500/300",
                    lazySrc: "https://picsum.photos/id/11/10/6",
                },
                {
                    id: 4,
                    imgSrc: "https://picsum.photos/id/11/500/300",
                    lazySrc: "https://picsum.photos/id/11/10/6",
                },
                {
                    id: 5,
                    imgSrc: "https://picsum.photos/id/11/500/300",
                    lazySrc: "https://picsum.photos/id/11/10/6",
                },
                {
                    id: 6,
                    imgSrc: "https://picsum.photos/id/11/500/300",
                    lazySrc: "https://picsum.photos/id/11/10/6",
                },
                {
                    id: 7,
                    imgSrc: "https://picsum.photos/id/11/500/300",
                    lazySrc: "https://picsum.photos/id/11/10/6",
                },
                {
                    id: 8,
                    imgSrc: "https://picsum.photos/id/11/500/300",
                    lazySrc: "https://picsum.photos/id/11/10/6",
                },
                {
                    id: 9,
                    imgSrc: "https://picsum.photos/id/11/500/300",
                    lazySrc: "https://picsum.photos/id/11/10/6",
                },
                {
                    id: 10,
                    imgSrc: "https://picsum.photos/id/11/500/300",
                    lazySrc: "https://picsum.photos/id/11/10/6",
                },
            ]
        }
    }
};
</script>

<style>
</style>
