<template>
  <header class="bg-zinc-800 w-full border-white/10 border border-y-[1px]">
    <div
      class="p-4 flex items-center gap-16 justify-between max-w-main mx-auto w-full"
    >
      <div>
        <NuxtImg src="/allegro-logo.svg" width="193" height="43" />
      </div>
      <SearchBar />
      <Navigation />
      <UserDetails />
    </div>
  </header>
</template>

<script setup></script>

<style lang="scss" scoped></style>
