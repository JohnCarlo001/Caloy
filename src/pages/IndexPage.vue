<template>
  <q-page class="flex flex-center">
    <q-layout view="lHh Lpr lFf">
      <q-page-container>
        <q-page class="flex flex-center">
          <page-link />
        </q-page>
      </q-page-container>
    </q-layout>
  </q-page>
</template>

<script>

import { defineComponent } from 'vue'
import PageLink from 'src/components/PageLink.vue';


export default defineComponent({
  name: 'IndexPage',
  components : {
    PageLink 
  }
})
</script>
