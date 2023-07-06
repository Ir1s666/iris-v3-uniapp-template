<template>
  <view @tap="handleAdd">{{ count }}</view>
</template>

<script setup lang="ts">
import { ref } from 'vue';

const count = ref(0);

const handleAdd = () => {
  count.value = count.value + 1;
}
</script>

<style lang="less" scoped></style>
