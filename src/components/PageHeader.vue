<script></script>

<template>
  <header id="header">
    <div class="pageview-container">
      <RouterLink to="/" class="pageview-button">FeliFlix</RouterLink>
      <!-- <span class="pageview-button">Gêneros</span> -->
    </div>
  </header>
</template>

<style scoped>
#header {
  color: rgb(219, 23, 23);
  background-color: rgb(0, 0, 0);
  font-size: 2rem;

  display: flex;
  flex-direction: row;
  justify-content: center;
}
.pageview-container {
  cursor: default;

  display: flex;
  flex-direction: row;
  gap: 1vw;
  justify-content: center;
  align-items: center;
}
.pageview-button {
  padding: 5px;
  cursor: pointer;
}
.pageview-button:hover {
  background-color: rgb(151, 31, 31);
  color: #ffb2ae;
}
.sla {
  color: rgb(219, 23, 23);
  background-color: rgb(0, 0, 0);
  font-size: 2rem;

  display: flex;
  flex-direction: row;
  justify-content: center;
  cursor: grab;
  border: none;
}
</style>
