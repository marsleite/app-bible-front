<template>
  <div class="container">
    <h1>Login</h1>

    <div class="input-container">
      <input type="text" class="" v-model="username" placeholder="Username">
      <input type="password" class="" v-model="password" placeholder="Password">
    </div>
  </div>
</template>

<script>
export default {
  name: 'Login',
  username: '',
  password: '',
}
</script>

<style lang="scss">
  .input-container {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    margin-top: 20px;
  }
</style>