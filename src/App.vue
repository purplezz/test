<template>
  <div class="app-container">
    <h1>Vue3 iframe 示例项目</h1>
    <div class="iframe-container">
      <iframe 
        title="Preview" 
        src="https://28b3f3d7-ce73-4282-b646-9a793c9c6aee-v2-figmaiframepreview.figma.site" 
        allow="autoplay" 
        class="preview-iframe"
      ></iframe>
    </div>
  </div>
</template>

<script setup lang="ts">
// 组件逻辑
</script>

<style scoped>
.app-container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 20px;
  font-family: Arial, sans-serif;
}

.iframe-container {
  margin-top: 20px;
  border: 1px solid #eaeaea;
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
}

.preview-iframe {
  width: 100%;
  height: 800px;
  border: none;
}
</style>