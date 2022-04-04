<template>
  <div class="container">
    <div class="row">
      <div class="col-12 g-0 mainbar">
        <span class="heading-text">BHN BUGOJNO</span>
        <div class="menu">
          MENU
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<style lang="scss">
  .mainbar {
      background: $maintheme;
      height: 4rem;
      display: flex;
  }
  .menu {
    height: 100%;
    width: 4rem;
    display: flex;
    align-items: center;
    justify-content: center;
    background: $darktheme;
    color: white;
  }
  .heading-text {
    color: white;
    flex-grow: 1;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 1.4rem;
    font-family: 'Quicksand', sans-serif;
  }
</style>
