<template>
  <header class="shadow w-screen">
    <nav>
      <nav class="flex items-center justify-between flex-wrap p-6 bg-gradient-to-b from-blue-500 via-green-400 to-blue-500">
        <div class="flex items-center flex-shrink-0 text-white mr-6">
          <px-icon class="mr-2" />
          <router-link
          :to="{ name: 'home' }"
          class="font-semibold text-xl tracking-tight"
            >PlatziExchange</router-link>
        </div>
        <div
          class="
            hidden
            sm:block
            w-full
            blok
            flex-grow
            lg:flex lg:items-center lg:wauto
          "
        >
          <div class="text-sm lg:flex-grow"></div>
        </div>
      </nav>
    </nav>
  </header>
</template>

<script>
import PxIcon from '@/components/PxIcon'
export default {
  name: 'PxHeader',
  components: { PxIcon },
}
</script>
