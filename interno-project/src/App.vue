<template>
  <div id="app">
    <div class="container">
      <header-component></header-component> 
    </div>
    <project-intro-component></project-intro-component>
    <div class="container">
      <projects-component></projects-component>
      <footer-component></footer-component>
    </div>
  </div>
  
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue'
import FooterComponent from './components/FooterComponent.vue'
import ProjectIntroComponent from './components/ProjectIntroComponent.vue'
import ProjectsComponent from './components/ProjectsComponent.vue'

export default {
  name: 'App',
  components: {
    HeaderComponent,
    FooterComponent,
    ProjectIntroComponent,
    ProjectsComponent
  },
};
</script>

<style>
.container {
  width: 1200px;
  margin:  0 360px 0 360px;
}
</style>
