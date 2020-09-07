<template>
    <v-container>

    <v-img
    src="~assets/zeke 1280px.png"
    class="zk-hero fullscreen"
    light
    >
    
    <v-row align="center" class="fill-height">
        <v-col cols="4" offset="2">
            <v-card-title>

            <h1>ZEKE KHASELI</h1>
            </v-card-title>

            <v-card-text>

            <h4>Browse or subscribe to get music, albums, and video content from zeke</h4>
            </v-card-text>
            <v-card-actions>

            <v-btn outlined>BROWSE</v-btn>
            <v-btn color="primary">REGISTER</v-btn>
            </v-card-actions>
        </v-col>
    </v-row>
    </v-img>
    </v-container>

    



<!-- <iframe src="https://picsum.photos/id/11/500/300" frameborder="0" allowfullscreen>

</iframe> -->
</template>

<script>
export default {
name: "zk-hero"

}
</script>

<style>
img.zk-hero {
    background: url("@/assets/zeke_bg_1280px.jpg");
}

</style>