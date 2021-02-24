<template>
  <div id="app">
    <h1>Blog Post Creator</h1>
    <blog-post-creator class="rteditor"></blog-post-creator>
  </div>
</template>

<script>
import BlogPostCreator from './components/BlogPostCreator.vue'

export default {
  name: 'app',
  components: {
    BlogPostCreator
  }
}
</script>

<style scoped>
h1 {
  margin: 10px 0px 0px 20px;
}

.rteditor {
  margin: 0px 20px 0px 20px;
}
</style>
