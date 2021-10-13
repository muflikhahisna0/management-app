<template>
  <div class="flex h-screen bg-white font-sans">
    <sidebar-layout
      class="border-white-100 bg-purple-900 text-white border-r p-4 w-1/6"
    />
    <div class="text-gray-700  w-screen">
      <navbar-layout class="p-4" />
      <content-layout class="p-4" />
      <footer-layout class="p-4" />
    </div>
  </div>
</template>

<script>
import ContentLayout from "../components/layout/ContentLayout.vue";
import FooterLayout from "../components/layout/FooterLayout.vue";
import NavbarLayout from "../components/layout/NavbarLayout.vue";
import SidebarLayout from "../components/layout/SidebarLayout.vue";
export default {
  components: { SidebarLayout, NavbarLayout, FooterLayout, ContentLayout },
};
</script>

<style></style>
