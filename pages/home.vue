<template>
  <div>
    <Top />
    <Menu />
    <Curtains />
  </div>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>

<style>
  :root {
    --color1: wheat;
    --color2: midnightblue;
    --minh: 90vh;
  }

  html, body {
    height: 100%;
    width: 100%;
    margin: unset;
    font-family: serif;
    /*font-family: WaterBrush;*/
  }

  @font-face {
    font-family: 'WaterBrush';
    src: url(/WaterBrush-Regular.ttf);
  }

  @font-face {
    font-family: 'Ubuntu';
    src: url(/Ubuntu-Light.ttf);
  }

  @font-face {
    font-family: 'Dancing';
    src: url(/DancingScript-VariableFont_wght.ttf);
  }
</style>
