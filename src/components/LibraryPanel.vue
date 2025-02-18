<script setup></script>

<template>
  <section class="library-panel">
    <h2>Tracklists</h2>
    <div class="folder">
      <div class="folder__header">
        <img src="../assets/icons/caret--right.svg" class="icon-medium" alt="caret right" />
        <img src="../assets/icons/folder.svg" class="icon-medium" alt="folder" />
        <h3>Progressive</h3>
      </div>
    </div>
  </section>
</template>

<style scoped lang="scss">
.library-panel {
  background-color: var(--carbon-gray-);
  border-right: 1px solid #393939;
  height: 100%;
  width: 16rem;
  position: fixed;
  top: 3rem;
  left: 0;
  padding: 1rem;

  .folder {
    &__header {
      display: flex;
      flex-flow: row nowrap;
      column-gap: 8px;

      .icon-medium {
        width: 1rem;
      }
    }
  }
}
</style>
