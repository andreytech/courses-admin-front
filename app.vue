<template>
  <div>
    <NuxtRouteAnnouncer />
    <Index />
  </div>
</template>

<script>
import Index from '~/components/Index.vue'

export default {
  components: {
    Index,
  },
}
</script>