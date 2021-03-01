<template>
  <div class="container px-6 mx-auto md:max-w-4xl">
    <section class="sec py-16 px-auto">
      <div class="work_fig">
        <img class="w-full" src="/img/dummy_1000_618.png" alt="" />
      </div>
      <h2 class="h2 text-2xl font-bold tracking-wider leading-none pt-10">
        アイコン・その他
      </h2>
      <p class="summary text-sm text-gray-700 tracking-wide leading-none pt-4">
        デザイン（Sketch） | 1-3days
      </p>
      <p class="credit text-base tracking-wide leading-7 pt-6">
        アプリ内で使用したアイコンなど。
      </p>
      <div class="pagenation pt-20 flex justify-between">
        <button class="back_btn py-8">
          <nuxt-link to="/" class="btn btn-primary hover:text-blue-600"
            >◀ TOP</nuxt-link
          >
        </button>
        <!-- <button class="next_btn py-8">
          <nuxt-link to="/work01" class="btn btn-primary hover:text-blue-600"
            >NEXT ▶</nuxt-link
          >
        </button> -->
      </div>
    </section>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.container {
  line-height: 1;
}
</style>
