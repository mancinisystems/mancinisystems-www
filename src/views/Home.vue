<template>
  <div class="home">
    <img src="../assets/mslogo.svg">
    <HomeHero msg="Premier Computer Consulting"/>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import HelloWorld from '@/components/HelloWorld.vue'; // @ is an alias to /src
import HomeHero from '@/components/HomeHero.vue';

@Component({
  components: {
    HelloWorld,
    HomeHero,
  },
})
export default class Home extends Vue {}
</script>
