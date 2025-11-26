<template>
<div>
  <div>hello world</div>
  <el-input-number v-model="input" :min="1" :max="10" :step="1"></el-input-number>
</div>
</template>

<script>
export default {
  data () {
    return {
      input: 1
    };
  }
};
</script>
