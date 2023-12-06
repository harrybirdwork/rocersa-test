<template>
  <div>
    <NuxtWelcome
      :follow-twitter="data.twitter"
      :read-docs="data.docs"
      :star-git-hub="data.github"
    />
  </div>
</template>

<script setup>
const { data } = await useFetch('/api/test');
</script>
