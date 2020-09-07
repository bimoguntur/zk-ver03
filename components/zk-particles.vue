<template>
    <kinesis-container class="fullscreen">

        <vue-particles
        color="#dedede"
        :particleOpacity="0.7"
        :particlesNumber="80"
        shapeType="circle"
        :particleSize="4"
        linesColor="#dedede"
        :linesWidth="1"
        :lineLinked="true"
        :lineOpacity="0.4"
        :linesDistance="150"
        :moveSpeed="3"
        :hoverEffect="true"
        hoverMode="grab"
        :clickEffect="true"
        clickMode="push"
        class="fullscreen"
        >
        </vue-particles>
    </kinesis-container>
    
</template>

<script>
export default {
    name: "zk-particles"

}
</script>

<style>
.zk_particles {
  width: 100vw;
  background-color: white;
}


</style>