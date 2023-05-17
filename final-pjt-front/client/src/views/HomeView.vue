<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/Reelix.png" />
    <MainView />
    <TopRatedView />
    <PopularView />
  </div>
</template>

<script>
// @ is an alias to /src
import MainView from "@/components/MainView.vue";
import PopularView from "@/components/PopularView.vue";
import TopRatedView from "@/components/TopRatedView.vue";

export default {
  name: "HomeView",
  components: {
    MainView,
    PopularView,
    TopRatedView,
  },
};
</script>
