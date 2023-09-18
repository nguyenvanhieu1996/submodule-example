<template>
    <Contact />
</template>


<script lang="ts">
import { Component } from 'nuxt-property-decorator'

@Component({
  components: {
    Contact: () => import('src/modules/templates/contact.vue')
  }
})
</script>