<template>
  <div class="p-6 text-gray-600 dark:text-gray-600">
    <div class="">
      <div class="inline-flex items-center cursor-pointer mb-2">
        <p class="uppercase text-sm">all chats</p>
        <svg
          class="w-4 h-4 ml-2"
          aria-hidden="true"
          fill="none"
          stroke="currentColor"
          viewBox="0 0 24 24"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M19 9l-7 7-7-7"
          ></path>
        </svg>
      </div>
      <h1 class="text-3xl dark:text-gray-400">
        Messages <span class="text-indigo-600">(28)</span>
      </h1>
    </div>
    <div class="relative mt-5">
      <div
        class="absolute inset-y-0 left-0 flex items-center pl-3 pointer-events-none"
      >
        <svg
          aria-hidden="true"
          class="w-5 h-5 text-gray-500 dark:text-gray-400"
          fill="none"
          stroke="currentColor"
          viewBox="0 0 24 24"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"
          ></path>
        </svg>
      </div>
      <input
        type="search"
        id="default-search"
        class="block w-full p-3 pl-10 text-gray-900 rounded-lg bg-gray-200 border-none dark:bg-gray-800"
        placeholder="Search..."
        required
      />
    </div>
    <Pinned />
    <AllMessages />
  </div>
</template>
<script lang="ts">
export default {
  name: "messages",
};
</script>
<script setup lang="ts">
import Pinned from "./messages-components/Pinned.vue";
import AllMessages from "./messages-components/AllMessages.vue";
</script>
