<template>
  <div>
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
