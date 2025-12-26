<template>
  <div class="my-area">
    <div class="num">
      <span>Number 1</span>
      <input v-model="n1" type="text" data-testid="n1" />
    </div>
    <div class="num">
      <span>Number 2</span>
      <input v-model="n2" type="text" data-testid="n2" />
    </div>
  </div>
</template>

<script setup lang="ts">
import { ref } from "vue";
const n1 = ref(1);
const n2 = ref(2);
</script>

<style scoped>
.my-area {
  border: 1px solid #eee;
  padding: 20px;
}
.num {
  margin: 1em 0;
}
.sum {
  font-weight: bold;
}
</style>
