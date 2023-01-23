<template>
  <div class="flex min-h-screen">
    <div
      class="flex top-0 left-0 w-16 border-r dark:bg-gray-900 bg-white border-gray-200 dark:border-gray-800 text-center flex-col justify-between"
    >
      <div class="divide-y divide-gray-200 dark:divide-gray-800">
        <div class="flex justify-center p-3 pt-6"><Logo /></div>
        <div class="p-3 flex justify-center m-3 pt-8"><Links /></div>
        <div class="p-3 flex justify-center m-3 pt-8"><Settings /></div>
      </div>
      <div class="mb-7 space-y-8"><ToggleDark /></div>
    </div>
    <div
      class="w-72 border-r dark:bg-gray-900 bg-white border-gray-200 dark:border-gray-800"
    >
      <Messages />
    </div>
  </div>
</template>
<script lang="ts">
export default {
  name: "dashboard",
};
</script>
<script setup lang="ts">
import Logo from "./sidebar-components/Logo.vue";
import Links from "./sidebar-components/Links.vue";
import Settings from "./sidebar-components/Settings.vue";
import ToggleDark from "./sidebar-components/ToggleDark.vue";
import Messages from "./Messages.vue";
</script>
