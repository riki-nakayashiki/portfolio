<template>
  <section class="background-color">
  </section>
  <!-- Navigation -->
  <NavComponent />
  <!-- Main Section -->
  <main>
    <HomeContent />
    <AboutContent />
    <ExperienceContent />
    <SkillsContent />
    <ContactContent />
  </main>
  <!-- Footer -->
  <footer>
    Footer
  </footer>
</template>

<script>
import NavComponent from './components/pages/NavComponent.vue';
import HomeContent from './components/pages/HomeContent.vue';
import AboutContent from './components/pages/AboutContent.vue';
import ExperienceContent from './components/pages/ExperienceContent.vue';
import SkillsContent from './components/pages/SkillsContent.vue';
import ContactContent from './components/pages/ContactContent.vue';


export default {
  name: 'App',
  components: {
    NavComponent,
    HomeContent,
    AboutContent,
    ExperienceContent,
    SkillsContent,
    ContactContent
  }
}
</script>

<style>
@import '../css/style.css';
/* @import 'https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css'; */
</style>
