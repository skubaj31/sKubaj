<template>
  <div id="app" class="app-container">
    <Header />
    <aboutYou />
    <Projects />
    <Skills />
    <Contact />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import aboutYou from "./components/aboutYou.vue";
import Contact from "./components/Contact.vue";
import Projects from "./components/Projects.vue";
import Skills from "./components/Skills.vue";

export default {
  name: "App",
  components: {
    Header,
    aboutYou,
    Contact,
    Projects,
    Skills,
  },
};
</script>