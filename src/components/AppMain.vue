<script>
import MainFilmList from "./MainFilmList.vue"
import MainSeriesList from "./MainSeriesList.vue"
export default {
  data() {
    return {
      
    }
  },
  components: {
    MainFilmList,
    MainSeriesList,
  }
}
</script>

<template>
<h2>Main content</h2>
<MainFilmList />
<MainSeriesList />
</template>

<style scoped>
</style>