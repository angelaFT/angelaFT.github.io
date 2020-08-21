<template>
  <div id="app">
    <nav>
      <div>
        <router-link to="/">Home</router-link>
        <router-link to="/about">About</router-link>
      </div>
    </nav>
    <router-view/>
  </div>
</template>

<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css2?family=BioRhyme:wght@300&family=Oxygen&display=swap');

  #app {
    nav {
      background-color: transparent;
      display: flex;
      justify-content: flex-end;
      align-items: center;

      a {
        margin-right: 2em;
        font-family: 'BioRhyme', serif;
        text-decoration: none;
      }
    }
  }
</style>
