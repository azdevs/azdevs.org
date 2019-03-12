<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <Main />
    <NewMember />
    <ExistingMember />
    <HelloWorld msg="Welcome to Your Vue.js + TypeScript App" />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'
import Main from '@/components/Main.vue'
import NewMember from '@/components/NewMember.vue'
import ExistingMember from '@/components/ExistingMember.vue'
import HelloWorld from '@/components/HelloWorld.vue' // @ is an alias to /src

@Component({
  components: {
    Main,
    NewMember,
    ExistingMember,
    HelloWorld
  }
})
export default class Home extends Vue {}
</script>
