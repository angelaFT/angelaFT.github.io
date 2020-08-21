<template>
  <div class="home">
    <div class="home-title">Playground for a</div>
    <div class="main-content">
      <div class="dot" />
      <div class="main-content__img">
        <img src="../assets/speaker.svg">
      </div>
      <div class="dot" />
    </div>
    <div class="home-title">Wizard of Light Bulb Moments</div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'Home',
};
</script>

<style lang="scss">
  .home {
    background-color: #ffb853;
    height: calc(100vh - 2.5rem);

    .home-title {
      font-family: 'Oxygen', sans-serif;
      text-align: center;
      letter-spacing: 2px;

      &:first-of-type {
        padding-top: 3rem;
        font-size: small;
      }
    }
  }
  .main-content {
    display: flex;
    justify-content: center;
    align-items: center;

    &__img {
      border: 3px solid black;
      margin: 2rem 1.5rem;

      img {
        width: 30vw;
        height: 30vh;
        margin: 2rem 6rem;
        transform: rotateZ(45deg);
      }
     }

    .dot {
      border-radius: 50%;
      border: .35rem solid black;
      color: black;
    }
  }
</style>
