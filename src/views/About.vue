<template>
  <div class="about">

    <dev v-bind:picture = "require('@/assets/duran.jpg')" v-bind:name="'Princess Joy Duran'"  v-bind:description="'Project Manager'"></dev>
    <dev v-bind:picture = "require('@/assets/sugal.jpg')" v-bind:name="'Lorly S. Sugal'" v-bind:description="'Project Developer'"></dev>
    <dev v-bind:picture = "require('@/assets/nadela.jpg')" v-bind:name="'Mellyne Grace Nadela'" v-bind:description="'Project Developer'"></dev>
    <dev v-bind:picture = "require('@/assets/erim.jpg')" v-bind:name="'Jakeniel Erim'" v-bind:description="'Project Developer'"></dev>

  </div>

</template>

<script>
import dev from "@/components/developers";
export default {
  components:{
    dev
  }
};
</script>





