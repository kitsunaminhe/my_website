<template>
  <div>
    <!-- <nav class="navbar h-16 bg-blue-100 mb-3">
      <div class="container h-16 flex items-center pl-3">
        <a class="navbar-logo font-bold text-gray-900" href="/">LP SITE</a>
      </div>
    </nav> -->
    <div class="container mx-auto">
      <nuxt />
    </div>
    <footer class="footer text-center bg-white shadow-2xl">
      <p class="text-base font-bold py-20">&copy;2021 H</p>
    </footer>
  </div>
</template>

<script>
export default {}
</script>

<style>
html {
  font-family: Amiko, -apple-system, BlinkMacSystemFont, Roboto, 'Segoe UI',
    'Helvetica Neue', HelveticaNeue, YuGothic, 'Yu Gothic Medium', 'Yu Gothic',
    Verdana, Meiryo, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}

b,
strong,
.bold {
  font-family: -apple-system, BlinkMacSystemFont, Roboto, 'Segoe UI semibold',
    'Helvetica Neue', HelveticaNeue, YuGothic, 'Yu Gothic', 'Segoe UI', Verdana,
    Meiryo, sans-serif;
}
a,
a:focus {
  outline: none;
}
</style>
