<template>
  <HeaderComponent />

  <div class="container mx-auto">
    <router-view />
  </div>
</template>

<style>

</style>
<script>
import HeaderComponent from '@/components/Header.vue'

export default {
  components: {
    HeaderComponent,
  },
}
</script>
