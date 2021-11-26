<script setup>
import { ref } from "vue";

const count = ref(0);
</script>

<template>
  <aside
    class="
      p-3
      text-center
      bg-gradient-to-r
      from-pink-500
      via-red-500
      to-yellow-500
    "
  >
    <p class="text-sm font-medium text-white">
      Basic Setup of Vue3 (Vite) with Tailwind
    </p>
  </aside>

  <section>
    <div class="px-4 py-24 mx-auto max-w-screen-xl sm:px-6 lg:px-8">
      <div class="max-w-3xl mx-auto text-center">
        <h1
          class="
            leading-5
            text-3xl
            font-extrabold
            text-transparent
            sm:text-6xl
            bg-clip-text bg-gradient-to-r
            from-green-300
            via-blue-500
            to-purple-600
          "
        >
          Mikes Tailwind CSS Playground
        </h1>

        <p class="max-w-xl mx-auto mt-6 text-lg">
          Hi, Du kannst diese Seite modifizieren indem du die Datei
          'src/components/HelloWorld.vue' editierst.
        </p>
      </div>
    </div>
  </section>
</template>

<style scoped>
a {
  color: #42b983;
}
</style>
