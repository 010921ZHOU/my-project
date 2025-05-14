<template>
  <div class="container">
    <h1>明的 Unity 展馆系统</h1>
    <p>可定制、可商用、适用于毕设/展览/教学</p>

    <div class="product">
      <img src="/scene1.jpg" alt="主界面">
      <h2>主场景系统</h2>
      <p>角色移动 + 模型交互 + 拼图 + 答题 + 沉浸影院</p>
      <button @click="goToContact">微信购买</button>
    </div>

    <div class="contact">
      <h3>联系我</h3>
      <img src="/weixin_qr.jpg" alt="微信二维码" width="200" />
      <p>加微信了解更多或定制开发</p>
    </div>
  </div>
</template>

<script setup>
const goToContact = () => {
  window.scrollTo({ top: document.body.scrollHeight, behavior: 'smooth' });
}
</script>

<style scoped>
.container {
  max-width: 800px;
  margin: auto;
  padding: 2rem;
  text-align: center;
}
.product img {
  width: 100%;
  max-height: 300px;
  object-fit: cover;
}
button {
  margin-top: 1rem;
  padding: 0.5rem 1rem;
  background: #42b983;
  color: white;
  border: none;
  border-radius: 8px;
  cursor: pointer;
}
</style>
