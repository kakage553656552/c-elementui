<template>
  <div style="margin: 20px;width: 500px;">
    <el-steps direction="horizontal" :active="2">
      <el-step icon="el-icon-success" title="步骤 1"description="serthwserh serth ser hserh "></el-step>
      <el-step title="步骤 2" description="sert hserth serh ser h"></el-step>
      <el-step title="步骤 3"></el-step>
    </el-steps>
  </div>
</template>

<script>
export default {
  data () {
    return {
      input: 'Hello Element UI!'
    };
  }
};
</script>
