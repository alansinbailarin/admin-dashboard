<template>
  <div class="mt-6">
    <div class="flex justify-between items-center px-3 mb-2">
      <div>
        <p class="uppercase text-gray-600 text-sm font-semibold">Pinned</p>
      </div>
      <div>
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="16"
          height="16"
          fill="currentColor"
          class="bi bi-pencil-square"
          viewBox="0 0 16 16"
        >
          <path
            d="M15.502 1.94a.5.5 0 0 1 0 .706L14.459 3.69l-2-2L13.502.646a.5.5 0 0 1 .707 0l1.293 1.293zm-1.75 2.456-2-2L4.939 9.21a.5.5 0 0 0-.121.196l-.805 2.414a.25.25 0 0 0 .316.316l2.414-.805a.5.5 0 0 0 .196-.12l6.813-6.814z"
          />
          <path
            fill-rule="evenodd"
            d="M1 13.5A1.5 1.5 0 0 0 2.5 15h11a1.5 1.5 0 0 0 1.5-1.5v-6a.5.5 0 0 0-1 0v6a.5.5 0 0 1-.5.5h-11a.5.5 0 0 1-.5-.5v-11a.5.5 0 0 1 .5-.5H9a.5.5 0 0 0 0-1H2.5A1.5 1.5 0 0 0 1 2.5v11z"
          />
        </svg>
      </div>
    </div>
    <div class="overflow-auto h-44 rounded-md">
      <RouterLink
        to="#"
        class="flex items-center space-x-2 hover:bg-gray-100 dark:hover:bg-gray-800 transition-all duration-300 ease-in-out p-3 rounded-md"
      >
        <img
          class="rounded-full w-10 flex-shrink-0"
          src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?ixlib=rb-1.2.1&amp;ixid=eyJhcHBfaWQiOjEyMDd9&amp;auto=format&amp;fit=facearea&amp;facepad=2&amp;w=256&amp;h=256&amp;q=80"
          alt=""
        />
        <div class="flex-1 min-w-0">
          <div class="flex justify-between items-center">
            <p class="font-semibold text-gray-700 dark:text-white text-base">
              Alan Pacheco
            </p>
            <span class="text-xs"> 07:26 P.M. </span>
          </div>
          <div class="flex justify-between items-center -mt-0.5">
            <p class="text-sm text-gray-500 truncate dark:text-gray-400">
              Hola, ¿Como estas hoy?
            </p>
            <span
              class="inline-flex items-center justify-center w-4 h-4 ml-2 text-xs font-semibold text-white bg-orange-400 rounded-full"
            >
              2
            </span>
          </div>
        </div>
      </RouterLink>
      <RouterLink
        to="#"
        class="flex items-center space-x-2 hover:bg-gray-100 dark:hover:bg-gray-800 transition-all duration-300 ease-in-out p-3 rounded-md"
      >
        <img
          class="rounded-full w-10 flex-shrink-0"
          src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?ixlib=rb-1.2.1&amp;ixid=eyJhcHBfaWQiOjEyMDd9&amp;auto=format&amp;fit=facearea&amp;facepad=2&amp;w=256&amp;h=256&amp;q=80"
          alt=""
        />
        <div class="flex-1 min-w-0">
          <div class="flex justify-between items-center">
            <p class="font-semibold text-gray-700 dark:text-white text-base">
              Miguel Mendez
            </p>
            <span class="text-xs"> 10:26 A.M. </span>
          </div>
          <div class="flex justify-between items-center -mt-0.5">
            <p class="text-sm text-gray-500 truncate dark:text-gray-400"></p>
            <span
              class="inline-flex items-center justify-center w-4 h-4 ml-2 text-xs font-semibold text-white bg-orange-400 rounded-full"
            >
              2
            </span>
          </div>
        </div>
      </RouterLink>
      <RouterLink
        to="#"
        class="flex items-center space-x-2 hover:bg-gray-100 dark:hover:bg-gray-800 transition-all duration-300 ease-in-out p-3 rounded-md"
      >
        <img
          class="rounded-full w-10 flex-shrink-0"
          src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?ixlib=rb-1.2.1&amp;ixid=eyJhcHBfaWQiOjEyMDd9&amp;auto=format&amp;fit=facearea&amp;facepad=2&amp;w=256&amp;h=256&amp;q=80"
          alt=""
        />
        <div class="flex-1 min-w-0">
          <div class="flex justify-between items-center">
            <p class="font-semibold text-gray-700 dark:text-white text-base">
              Alan Pacheco
            </p>
            <span class="text-xs"> 07:26 P.M. </span>
          </div>
          <div class="flex justify-between items-center -mt-0.5">
            <p class="text-sm text-gray-500 truncate dark:text-gray-400">
              Hola, ¿Como estas hoy?
            </p>
            <span
              class="inline-flex items-center justify-center w-4 h-4 ml-2 text-xs font-semibold text-white bg-orange-400 rounded-full"
            >
              2
            </span>
          </div>
        </div>
      </RouterLink>
      <RouterLink
        to="#"
        class="flex items-center space-x-2 hover:bg-gray-100 dark:hover:bg-gray-800 transition-all duration-300 ease-in-out p-3 rounded-md"
      >
        <img
          class="rounded-full w-10 flex-shrink-0"
          src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?ixlib=rb-1.2.1&amp;ixid=eyJhcHBfaWQiOjEyMDd9&amp;auto=format&amp;fit=facearea&amp;facepad=2&amp;w=256&amp;h=256&amp;q=80"
          alt=""
        />
        <div class="flex-1 min-w-0">
          <div class="flex justify-between items-center">
            <p class="font-semibold text-gray-700 dark:text-white text-base">
              Alan Pacheco
            </p>
            <span class="text-xs"> 07:26 P.M. </span>
          </div>
          <div class="flex justify-between items-center -mt-0.5">
            <p class="text-sm text-gray-500 truncate dark:text-gray-400">
              Hola, ¿Como estas hoy?
            </p>
            <span
              class="inline-flex items-center justify-center w-4 h-4 ml-2 text-xs font-semibold text-white bg-orange-400 rounded-full"
            >
              2
            </span>
          </div>
        </div>
      </RouterLink>
      <RouterLink
        to="#"
        class="flex items-center space-x-2 hover:bg-gray-100 dark:hover:bg-gray-800 transition-all duration-300 ease-in-out p-3 rounded-md"
      >
        <img
          class="rounded-full w-10 flex-shrink-0"
          src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?ixlib=rb-1.2.1&amp;ixid=eyJhcHBfaWQiOjEyMDd9&amp;auto=format&amp;fit=facearea&amp;facepad=2&amp;w=256&amp;h=256&amp;q=80"
          alt=""
        />
        <div class="flex-1 min-w-0">
          <div class="flex justify-between items-center">
            <p class="font-semibold text-gray-700 dark:text-white text-base">
              Alan Pacheco
            </p>
            <span class="text-xs"> 07:26 P.M. </span>
          </div>
          <div class="flex justify-between items-center -mt-0.5">
            <p class="text-sm text-gray-500 truncate dark:text-gray-400">
              Hola, ¿Como estas hoy?
            </p>
            <span
              class="inline-flex items-center justify-center w-4 h-4 ml-2 text-xs font-semibold text-white bg-orange-400 rounded-full"
            >
              2
            </span>
          </div>
        </div>
      </RouterLink>
      <RouterLink
        to="#"
        class="flex items-center space-x-2 hover:bg-gray-100 dark:hover:bg-gray-800 transition-all duration-300 ease-in-out p-3 rounded-md"
      >
        <img
          class="rounded-full w-10 flex-shrink-0"
          src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?ixlib=rb-1.2.1&amp;ixid=eyJhcHBfaWQiOjEyMDd9&amp;auto=format&amp;fit=facearea&amp;facepad=2&amp;w=256&amp;h=256&amp;q=80"
          alt=""
        />
        <div class="flex-1 min-w-0">
          <div class="flex justify-between items-center">
            <p class="font-semibold text-gray-700 dark:text-white text-base">
              Alan Pacheco
            </p>
            <span class="text-xs"> 07:26 P.M. </span>
          </div>
          <div class="flex justify-between items-center -mt-0.5">
            <p class="text-sm text-gray-500 truncate dark:text-gray-400">
              Hola, ¿Como estas hoy?
            </p>
            <span
              class="inline-flex items-center justify-center w-4 h-4 ml-2 text-xs font-semibold text-white bg-orange-400 rounded-full"
            >
              2
            </span>
          </div>
        </div>
      </RouterLink>
    </div>
  </div>
</template>
<script lang="ts">
export default {
  name: "Pinned",
};
</script>
<script setup lang="ts">
import { RouterLink } from "vue-router";
</script>
