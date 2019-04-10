<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import Tennis from '@/components/Tennis.vue'; // @ is an alias to /src

@Component({
  components: {
    Tennis,
  },
})
export default class Home extends Vue {}
</script>
