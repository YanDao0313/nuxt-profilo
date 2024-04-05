<template>
  <div class="space-y-6">
    <NuxtImg src="/avatar.png" alt="Kris Yan"
      class="ring-2 border ring-gray-200 border-gray-300 dark:ring-white/10 dark:border-gray-800 hover:ring-4 transition-all duration-300 bg-gray-200 dark:bg-gray-900 rounded-full h-12 w-12 sm:h-16 sm:w-16"
      sizes="48px sm:64px" placeholder format="webp" />
    <h1 class="text-xl font-bold tracking-tight text-gray-800 dark:text-gray-100">
      Hello!
    </h1>
    <p class="text-gray-900 dark:text-gray-400">
      This is Kris, I am a student from PRC. I'd love to try sth new.<br />
      OIer or Junior Developer / Blogger / Student @ MZES
    </p>
    <p class="text-gray-900 dark:text-gray-400">
      By day, I'm a student at
      <a href="https://www.scmyzx.com.cn" target="_blank" class="underline">Mian Yang High school</a>, and
      by night (and weekends), I'm busy tinkering with some random tool or app
      that I am building or just struggling with my homework.
    </p>
  </div>
</template>

<script setup>
useSeoMeta({
  title: "Kris Yan",
  description:
    "This is Kris, I am a student from PRC. I'd love to try sth new.",
});
</script>
