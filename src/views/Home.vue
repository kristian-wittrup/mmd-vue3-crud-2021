<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <ProjectCreate />
    <ProjectList />
  </div>
</template>

<script>
// @ is an alias to /src
import ProjectCreate from '@/components/ProjectCreate.vue'
import ProjectList from '@/components/ProjectList.vue'

export default {
  name: 'Home',
  components: {
    ProjectCreate,
    ProjectList
  }
}
</script>
