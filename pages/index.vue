<template>
  <div class="content">
    <Logo />
    <h1>Veuve Michel</h1>
    <p>Site en construction, mise en ligne prévue pour juin 2020</p>
  </div>
</template>

<script>
import Logo from '~/assets/svg/logo.svg?inline';

export default {
  components: {
    Logo,
  },
};
</script>

<style lang="scss" scoped>
.content {
  text-align: center;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translateX(-50%) translateY(-50%);
  width: 300px;
  svg {
    width: 200px;
    height: 200px;
    fill: $colorSoil;
  }
  p {
    line-height: 1.5em;
  }
}
</style>
