<template>
  <div class="task">
    <div>
      <h3>{{ task.title }}</h3>
    </div>
    <div>
      <p>{{ task.details }}</p>
    </div>
  </div>
</template>

<script>
export default {
  props: ['task' ],
};
</script>

<style></style>
