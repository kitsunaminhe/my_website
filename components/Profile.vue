<template>
  <section class="profile py-20">
    <div class="profile_detail flex max-w-screen-lg mx-auto">
      <div class="profile_fig flex items-center">
        <img class="w-24 mx-auto" src="img/profile.png" alt="" />
      </div>
      <div class="profile_txt text-center ml-10">
        <h3 class="profile_ttl font-bold text-left leading-none ml-1">
          MORE PROFILE
        </h3>
        <div class="profile_btn_wrap flex justify-between md:space-x-5">
          <button
            class="profile_btn p-4 bg-blue-300 hover:bg-white border border-blue-300 hover:border-solid w-40 rounded-full mt-6 hover:text-blue-300 font-bold text-white"
          >
            <a class="profile_btn_txt" href="mailto:kitsuna.minhe@gmail.com"
              >Mail</a
            >
          </button>
          <button
            class="profile_btn p-4 bg-blue-300 hover:bg-white border border-blue-300 hover:border-solid w-40 rounded-full mt-6 hover:text-blue-300 font-bold text-white"
          >
            <a class="profile_btn_txt" href="https://trello.com/b/YMgvRqEb/memo"
              >Skill Detail</a
            >
          </button>
          <!-- <button
            class="profile_btn p-4 bg-blue-300 hover:bg-white border border-blue-300 hover:border-solid w-40 rounded-full mt-6 hover:text-blue-300 font-bold text-white"
          >
            <nuxt-link class="profile_btn_txt" to="/">Wantedly</nuxt-link>
          </button> -->
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {}
</script>
