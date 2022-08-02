<template>
  <ViewWrapper>
    <h1>Jobs</h1>
    <div v-for="job in jobs" :key="job.id">
      <h2>{{ job.title }}</h2>
    </div>
  </ViewWrapper>
</template>

<script>
import ViewWrapper from "../components/ViewWrapper.vue";
export default {
  data() {
    return {
      jobs: [
        { id: 1, title: "Ninja UX Desiger", details: "UX" },
        { id: 2, title: "Ninja UI Desiger", details: "UI" },
        { id: 3, title: "Ninja Developer", details: "Developer" },
      ],
    };
  },
  components: { ViewWrapper },
};
</script>

<style>
</style>