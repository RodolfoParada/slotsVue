<template>
  <div class="card">
    <div class="header" v-if="this.$slots.header">
        <slot name="header"></slot>
    </div>
    <slot></slot>
  </div>
</template>


<script>
export default {
  name: "ACard",
};
</script>

<style scoped>
.card {
  background: #666;
  color: white;
  border-radius: 6px;
  padding: 1rem;
}

.header {
    border-bottom: 1px solid #fff;
    padding-bottom: 1rem;
    margin-bottom: 1rem;
}
</style>