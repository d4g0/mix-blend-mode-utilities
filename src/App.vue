<template>
  <div class="bg-gray-100 min-h-screen">
    <!-- banner -->
    <div
      class="
        w-full
        flex flex-col
        items-center
        justify-center
        pt-20
        pb-10
        px-8
        bg-gradient-to-b
        from-rose-50
        to-gray-100
        font-sans
      "
    >
      <h1 class="text-[#212121] font-bold text-3xl md:text-4xl">
        Tailwindcss
        <a href="https://tailwindcss.com/docs/mix-blend-mode" class="text-amber-500 hover:text-amber-700">Mix Blend Mode</a>
        Utilities
      </h1>
      <div class="pt-8">
        <p class="sm:text-center">
          by
          <a
            href="https://github.com/d4g0"
            class="font-bold font-mono text-amber-500 hover:text-amber-700"
          >
            d4g0
          </a>
        </p>
        <p class="pt-2">
          Just add the class:
          <code class="bg-orange-200 rounded-md px-1">mix-blend-x</code> where
          <code class="bg-orange-200 rounded-md px-1">x</code> can be:
        </p>
      </div>
    </div>
    <div
      class="
        font-sans
        w-full
        p-8
        justify-center
        items-center
        grid grid-cols-1
        sm:grid-cols-2
        gap-x-6 gap-y-12
        lg:grid
        md:grid-cols-3
        lg:gap-16
        xl:grid-cols-4
      "
    >
      <div>
        <p class="w-full text-center pb-2 font-medium text-[#212121]">normal</p>
        <div
          class="
            shadow-xl
            relative
            h-60
            w-full
            rounded-lg
            bg-rose-600
            overflow-hidden
          "
        >
          <img
            :src="imgUrl"
            class="absolute w-full h-full object-cover mix-blend-normal"
          />
        </div>
      </div>
      <div>
        <p class="w-full text-center pb-2 font-medium text-[#212121]">screen</p>
        <div
          class="
            shadow-xl
            relative
            h-60
            w-full
            rounded-lg
            bg-rose-600
            overflow-hidden
          "
        >
          <img
            :src="imgUrl"
            class="absolute w-full h-full object-cover mix-blend-screen"
          />
        </div>
      </div>

      <div>
        <p class="w-full text-center pb-2 font-medium text-[#212121]">
          overlay
        </p>
        <div
          class="
            shadow-xl
            relative
            h-60
            w-full
            rounded-lg
            bg-rose-600
            overflow-hidden
          "
        >
          <img
            :src="imgUrl"
            class="absolute w-full h-full object-cover mix-blend-overlay"
          />
        </div>
      </div>

      <div>
        <p class="w-full text-center pb-2 font-medium text-[#212121]">darken</p>
        <div
          class="
            shadow-xl
            relative
            h-60
            w-full
            rounded-lg
            bg-rose-600
            overflow-hidden
          "
        >
          <img
            :src="imgUrl"
            class="absolute w-full h-full object-cover mix-blend-darken"
          />
        </div>
      </div>

      <div>
        <p class="w-full text-center pb-2 font-medium text-[#212121]">hidden</p>
        <div
          class="
            shadow-xl
            relative
            h-60
            w-full
            rounded-lg
            bg-rose-600
            overflow-hidden
          "
        >
          <img
            :src="imgUrl"
            class="absolute w-full h-full object-cover mix-blend-lighten"
          />
        </div>
      </div>

      <div>
        <p class="w-full text-center pb-2 font-medium text-[#212121]">
          color-dodge
        </p>
        <div
          class="
            shadow-xl
            relative
            h-60
            w-full
            rounded-lg
            bg-rose-600
            overflow-hidden
          "
        >
          <img
            :src="imgUrl"
            class="absolute w-full h-full object-cover mix-blend-color-dodge"
          />
        </div>
      </div>

      <div>
        <p class="w-full text-center pb-2 font-medium text-[#212121]">
          color-burn
        </p>
        <div
          class="
            shadow-xl
            relative
            h-60
            w-full
            rounded-lg
            bg-rose-600
            overflow-hidden
          "
        >
          <img
            :src="imgUrl"
            class="absolute w-full h-full object-cover mix-blend-color-burn"
          />
        </div>
      </div>

      <div>
        <p class="w-full text-center pb-2 font-medium text-[#212121]">
          hard-light
        </p>
        <div
          class="
            shadow-xl
            relative
            h-60
            w-full
            rounded-lg
            bg-rose-600
            overflow-hidden
          "
        >
          <img
            :src="imgUrl"
            class="absolute w-full h-full object-cover mix-blend-hard-light"
          />
        </div>
      </div>

      <div>
        <p class="w-full text-center pb-2 font-medium text-[#212121]">
          soft-light
        </p>

        <div
          class="
            shadow-xl
            relative
            h-60
            w-full
            rounded-lg
            bg-rose-600
            overflow-hidden
          "
        >
          <img
            :src="imgUrl"
            class="absolute w-full h-full object-cover mix-blend-soft-light"
          />
        </div>
      </div>

      <div>
        <p class="w-full text-center pb-2 font-medium text-[#212121]">
          blend-difference
        </p>
        <div
          class="
            shadow-xl
            relative
            h-60
            w-full
            rounded-lg
            bg-rose-600
            overflow-hidden
          "
        >
          <img
            :src="imgUrl"
            class="absolute w-full h-full object-cover mix-blend-difference"
          />
        </div>
      </div>

      <div>
        <p class="w-full text-center pb-2 font-medium text-[#212121]">
          blend-exclusion
        </p>
        <div
          class="
            shadow-xl
            relative
            h-60
            w-full
            rounded-lg
            bg-rose-600
            overflow-hidden
          "
        >
          <img
            :src="imgUrl"
            class="absolute w-full h-full object-cover mix-blend-exclusion"
          />
        </div>
      </div>

      <div>
        <p class="w-full text-center pb-2 font-medium text-[#212121]">
          blend-hue
        </p>
        <div
          class="
            shadow-xl
            relative
            h-60
            w-full
            rounded-lg
            bg-rose-600
            overflow-hidden
          "
        >
          <img
            :src="imgUrl"
            class="absolute w-full h-full object-cover mix-blend-hue"
          />
        </div>
      </div>

      <div>
        <p class="w-full text-center pb-2 font-medium text-[#212121]">
          blend-saturation
        </p>
        <div
          class="
            shadow-xl
            relative
            h-60
            w-full
            rounded-lg
            bg-rose-600
            overflow-hidden
          "
        >
          <img
            :src="imgUrl"
            class="absolute w-full h-full object-cover mix-blend-saturation"
          />
        </div>
      </div>

      <div>
        <p class="w-full text-center pb-2 font-medium text-[#212121]">
          blend-color
        </p>
        <div
          class="
            shadow-xl
            relative
            h-60
            w-full
            rounded-lg
            bg-rose-600
            overflow-hidden
          "
        >
          <img
            :src="imgUrl"
            class="absolute w-full h-full object-cover mix-blend-color"
          />
        </div>
      </div>

      <div>
        <p class="w-full text-center pb-2 font-medium text-[#212121]">
          luminosity
        </p>
        <div
          class="
            shadow-xl
            relative
            h-60
            w-full
            rounded-lg
            bg-rose-600
            overflow-hidden
          "
        >
          <img
            :src="imgUrl"
            class="absolute w-full h-full object-cover mix-blend-luminosity"
          />
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import { ref } from "vue";
import imgUrl from "./assets/coral_n_galapagos.jpg";
import { TransitionRoot, TransitionChild } from "@headlessui/vue";
var show = ref(false);
</script>


