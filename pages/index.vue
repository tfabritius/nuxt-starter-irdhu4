<template>
  <div>
    {{ state }}
  </div>
</template>

<script setup lang="ts">
import { MyInterface } from '@/store/MyInterface.model';

const state = ref<MyInterface>({ id: 1, msg: 'Hello World' });
</script>
