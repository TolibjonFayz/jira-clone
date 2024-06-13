<template>
  <div class="btn">Button</div>
</template>

<script setup></script>

<style lang="scss" scoped>
.btn {
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  display: inline;
  padding: 5px 15px;
  background: aqua;
  cursor: pointer;
  &:hover {
    transition: all ease-in-out 0.2s;
    background-color: aquamarine;
  }
}
</style>
