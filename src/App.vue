<template>
  <div id="app">

    <div class="clock">
      <digital-clock-vue
        color="black"
        showSeconds
        style="width: 800px; height: 200px;"
      />
    </div>

  </div>

</template>

<script>
  import DigitalClockVue, { DigitalNumber } from 'digital-clock-vue'

  export default {
    components: {
      DigitalClockVue,
      DigitalNumber
    }
  }
</script>

<style>
  body {
    margin: 0;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Roboto', 'Oxygen',
    'Ubuntu', 'Cantarell', 'Fira Sans', 'Droid Sans', 'Helvetica Neue',
    sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
  }

  code {
    font-family: source-code-pro, Menlo, Monaco, Consolas, 'Courier New',
    monospace;
  }

  .clock {
    display: flex;
  }

  .clock {
    text-align: center;
    margin: 0 auto;
    min-height: 100vh;
    justify-content: center;
    align-items: center;
  }
</style>
