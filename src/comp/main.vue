<template>
  <div class="layout">
    <the-header />
    <div class="main-content">
      <the-sidebar />
      <main class="content">
        <div class="flex justify-content-center">
          <Card/>
        </div>
        <!--<router-view></router-view>-->
      </main>
    </div>
    <the-footer />
  </div>
</template>

<script setup>
import TheHeader from './header.vue'
import TheFooter from './footer.vue'
import TheSidebar from './siderbar.vue'
import Card from './card.vue'
</script>

<style scoped>
.layout {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}

.main-content {
  width: 100%;
  display: flex;
  flex: 1;
}

.content {
  flex: 1;
  padding: 20px;
}
</style>
