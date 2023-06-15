<template>
  <q-layout view="hhh lpR lfr">

    <q-header reveal elevated class="bg-primary text-white">
      <q-toolbar>
        <q-toolbar-title>
          <div class="header">
            <div class="column">
              First Columnssssss
            </div>
            <div class="column" style="flex: 2;">
              <q-input outlined dense placeholder="Search">
                <template v-slot:prepend>
                  <q-icon name="search" />
                </template>
              </q-input>
            </div>
            <div class="column">
              <img src="src/assets/cart-icon.PNG" alt="" style="width: 50px;">
            </div>
          </div>
        </q-toolbar-title>
      </q-toolbar>
    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>

  </q-layout>
</template>

<style>
.header {
  background-color: rgb(48, 174, 216);
  display: flex;
  align-items: center;
  padding: 10px;
}

.column {
  flex: 1;
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>

<script>
import { ref } from 'vue'

export default {
  setup() {
    const leftDrawerOpen = ref(false)
    const rightDrawerOpen = ref(false)

    return {
      leftDrawerOpen,
      toggleLeftDrawer() {
        leftDrawerOpen.value = !leftDrawerOpen.value
      },

      rightDrawerOpen,
      toggleRightDrawer() {
        rightDrawerOpen.value = !rightDrawerOpen.value
      }
    }
  }
}
</script>