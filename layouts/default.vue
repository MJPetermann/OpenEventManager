<template>
    <div class="container">
      <HeaderNavbar />
      <div class="content">
        <slot />
      </div>
    </div>
</template>

<style scoped lang="scss">
.container {
  min-height: 100vh;
  background-color: $background;
}
.content{
  margin-left: 20vw;
}
</style>

<style>
* {
  margin: 0;
  border: 0;
  padding: 0;
}
</style>