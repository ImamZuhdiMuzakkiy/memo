<template>
  <main>
    <div class="container">
      <header>
        <h1 class="title">Memo</h1>
        <button>+</button>
      </header>
      <div>[card]</div>
    </div>
  </main>
</template>

<style scoped>
  main {
    height: 100vh;
    width: 100vw;
  }

  .container {
    max-width: 900px;
    padding: 10px;
    margin: 0 auto;
  }

  header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 20px;
  }
</style>