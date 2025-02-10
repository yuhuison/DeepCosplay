<script setup lang="ts" generic="T extends any, O extends any">
defineOptions({
  name: 'IndexPage',
})
</script>

<template>
  <div class="h-lg w-5xl flex overflow-hidden rounded-3xl bg-blue pb-1 pr-1 pt-1">
    <div class="w-12 bg-blue" />
    <div class="flex flex-1 flex-col overflow-hidden rounded-3xl bg-amber">
      <div class="h-12 bg-emerald" />
      <div class="w-full flex flex-1 bg-coolGray">
        <div class="w-48" />
        <div class="flex flex-1 flex-col bg-dark">
          <div class="h-12" />
          <div />
        </div>
      </div>
    </div>
  </div>
</template>
