<template>
  <div class="app-header">
    <h1>精模云</h1>
    <div>
      <span @click="go">机床</span>
    </div>
  </div>
</template>
<script setup>
const router = useRouter();
function go() {
  console.log(1);
  router.push(`/equipment`);
}
</script>
<style>
.app-header {
  display: flex;
  max-width: 1184px;
  margin: 0 auto;
}
</style>
