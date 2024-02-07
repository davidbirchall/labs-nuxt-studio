<template>
  <div class="logo">
    <span>Logo</span>
  </div>
</template>

<style lang="scss">
  .logo {
    background-color: #f1f1f1;
    border: 1px solid #ccc;
    height: 60px;
    position: relative;
    width: 200px;

    span {
      position: absolute;
      top: 50%;
      right: 50%;
      transform: translate(50%, -50%);
    }
  }
</style>