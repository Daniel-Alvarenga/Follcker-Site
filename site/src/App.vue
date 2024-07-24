<template>
  <img src="https://github.com/Daniel-Alvarenga/Follcker/blob/main/src/assets/source/image/logo.png" alt="Follcker" />
  <Page />
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component';
import Page from './components/Page.vue';

@Options({
  components: {
    Page,
  },
})
export default class App extends Vue { }
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
