<template>
  <header>

    <TopNavbar></TopNavbar>
    <CatalogNavbar></CatalogNavbar>

    <!--
    <nav class="nav navbar-expand-lg py-2 navbar-dark bg-dark text-bg-light">
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
              aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>


    </nav>
    -->
  </header>
</template>

<script>
import DropdownMenu from "@/components/Menu/DropdownMenu";
import CatalogNavbar from "@/components/Navbar/CatalogNavbar";
import TopNavbar from "@/components/Navbar/TopNavbar";
export default {
  name: "Header",
  components: {TopNavbar, CatalogNavbar, DropdownMenu}
}
</script>

<style scoped>


</style>