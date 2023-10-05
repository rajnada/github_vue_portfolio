<template>
  <div class="container sections-wrapper py-5">
    <div class="row">
      <div class="primary col-lg-8 col-12">
        <AboutMe />
        <projects />
        <Experience />
      </div>
      <div class="secondary col-lg-4 col-12">
        <BasicInfo />
      </div>
    </div>
  </div>
</template>

<script>
import AboutMe from "./Aboutme.vue";
import Projects from "./Projects.vue";
import Experience from "./Experience.vue";
import BasicInfo from "./BasicInfo.vue";
export default {
  components: { AboutMe, Projects, Experience, BasicInfo }
};
</script>

<style></style>
