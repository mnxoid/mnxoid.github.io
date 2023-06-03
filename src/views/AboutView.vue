<template>
  <div class="about">
    <div class="spacer"></div>
    <h1>This is an about page</h1>
    <div class="text">Some description coming soon</div>
    <div class="spacer"></div>
  </div>
</template>

<style scoped>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    align-items: center;
  }
}

.spacer {
  flex-grow: 1;
}
</style>
