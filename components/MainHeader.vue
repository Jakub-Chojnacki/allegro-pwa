<template>
  <header class="bg-zinc-800 w-full">
    <div
      class="p-4 flex items-center gap-16 justify-between max-w-[1600px] mx-auto w-full"
    >
      <div>
        <NuxtImg src="/allegro-logo.svg" width="193" height="43" />
      </div>

      <div class="flex mx-4 flex-1">
        <div class="flex items-center relative w-full">
          <input
            placeholder="czego szukasz?"
            class="bg-inherit p-2 border-slate-100 border w-full border-r-0"
          />
          <div
            class="flex items-center gap-2 border-slate-100 border-l-0 border-r-0 h-full border text-[24px] px-2 text-white/70"
          >
            <Icon name="ic:twotone-manage-search" class="" />
            <Icon name="ic:outline-camera-alt" class="" />
          </div>
        </div>
        <div class="relative">
          <input
            value="Wszystkie kategorie"
            class="bg-inherit border-slate-100 border h-full text-white p-2 border-r-0 text-sm"
          />
          <Icon
            name="mdi:chevron-down"
            class="text-[32px] text-gray-500 absolute right-4 top-1/2 translate-y-[-50%] translate-x-[10px]"
          />
        </div>

        <button class="bg-orange-600 text-white px-4 rounded-sm">SZUKAJ</button>
      </div>

      <nav class="text-white/70 text-[32px] flex items-center gap-4">
        <Icon name="tabler:truck-delivery" />
        <Icon name="material-symbols:favorite-outline" />
        <Icon name="mdi:comment-multiple-outline" />
        <Icon name="material-symbols:notifications-outline" />
        <Icon name="material-symbols:shopping-bag-outline" />
      </nav>
      <div className="flex flex-row items-center h-full gap-1 text-gray-500 ">
        <span class="text-white block">Imię</span>
        <Icon name="mdi:chevron-down" class="text-[32px] text-gray-500" />
      </div>
    </div>
  </header>
</template>

<script setup></script>

<style lang="scss" scoped></style>
