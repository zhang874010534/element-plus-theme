<script setup>
import { ref } from 'vue'
import {ElButton} from 'element-plus'
defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <el-button type="primary">按钮</el-button>
</template>

