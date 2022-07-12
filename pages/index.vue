<template>
  <div>
    <Header :headline="headline" :name="name" :tags="tags" />
    <Hero />
  </div>
</template>

<script>
import Header from "../components/Header.vue";
import Hero from "../components/Hero.vue";

export default {
  components: {
    Header,
    Hero,
  },
  data() {
    return {
      headline: "Hello! I am",
      name: "Saad",
      tags: [
        "#Software Engineer",
        "#Developer",
        "#Explorer",
        "#Gamer",
        "#Weeb",
      ],
    };
  },
};
</script>

<style>
</style>
