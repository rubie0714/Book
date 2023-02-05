<script setup>
import DataTable from './components/DataTable.vue'
import SearchBar from './components/SearchBar.vue'
</script>

<template>
  <div class="m-5">
    <search-bar>
      <p class="form-label inline-block mb-2 text-gray-700">請輸入書籍網址</p>
    </search-bar>
    <data-table></data-table>
  </div>
</template>

<style scoped>

</style>
