<template>
  <div class="content">
    <Logo />
    <h1>Veuve Michel</h1>
    <p>IGP Coteaux du Salagou<br />34800 Octon, Hérault, Languedoc</p>
    <p>Site en construction<br />Mise en ligne juin 2020</p>
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
    color: $colorSoil;
    &:last-child {
      font-size: 1.2em;
      font-weight: 700;
    }
  }
}
</style>
