<template>
  <div class="flex">
    <SideBar />
    <div class="m-6 grow grid grid-cols-5 gap-4">
      <VideoCard v-for="_ in 50" />
    </div>
  </div>
</template>
