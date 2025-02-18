<script setup></script>

<template>
  <section class="navigation">
    <h1>DeeJay</h1>
  </section>
</template>

<style scoped lang="scss">
.navigation {
  background-color: var(--carbon-gray-100);
  border-bottom: 1px solid var(--carbon-gray-80);
  height: 3rem;
  width: 100%;
  position: fixed;
  top: 0;
  left: 0;

  h1 {
    font-family: 'IBMPlexSans-SemiBold';
    font-size: 1rem;
    color: var(--carbon-text-dark);
    text-transform: uppercase;
  }
}
</style>
