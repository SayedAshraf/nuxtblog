<template>
  <div class="post-card-body">
    <h3>
      <nuxt-link :to="`/blog/${post.id}`">
        <span @click="UpdateSelectedPost(post)">
          {{ post.title }}
        </span>
      </nuxt-link>
    </h3>
    <p>{{ post.body }}</p>
  </div>
</template>

<script>
export default {
  name: "blog",
};
</script>

<style lang="scss" scoped>
</style>
