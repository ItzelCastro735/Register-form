<script setup>
import Form from "./components/Form.vue";
</script>

<template>
  <div class="main">
    <div class="main-info">
      <h2>Learn to code by watching others</h2>
      <p>See how experienced developers solve problems in real-time. Watching scripted tutorials is great, but understanding how developers think is invaluable</p>
    </div>
    <Form></Form>
  </div>
</template>

<style scoped>
.main {
  width: 100%;
  height: 100vh;
  background-color: hsl(0, 100%, 74%);
  background-image: url('./assets/bg-intro-desktop.png');
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 30px;
}

.main .main-info {
  width: 450px;
  height: auto;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  justify-content: center;
}

.main .main-info h2 {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 50px;
  font-weight: 600;
  color: white;
  margin: 0;
}

.main .main-info p {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 16px;
  font-weight: 400;
  color: white;
}

@media screen and (max-width: 900px) {
  .main {
    flex-direction: column;
  }

  .main .main-info {
    text-align: center;
    align-items: center;
  }
}

@media screen and (max-width: 540px) {
  .main .main-info {
    width: 90%;
  }

  .main .main-info h2 {
    font-size: 30px;
  }

  .main .main-info p {
    line-height: 20px;
  }
}
</style>
