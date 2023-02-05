<script setup >
import { ref } from 'vue'

const headers = [
  { text: "小說網", value: "web" },
  { text: "書名", value: "book_name" },
  { text: "網址", value: "url" },
  { text: "操作", value: "action" },

];

const items = [
  { web: "思兔", book_name: "GSW", url: '', action: 'G' },
  { web: "小說網", book_name: "LAL", url: '', action: 'F' },
  { web: "思兔", book_name: "BKN", url: '', action: 'F' },
  { web: "小說網", book_name: "MIL", url: '', action: 'F' },
];
</script>

<template>
  <p>歷史紀錄</p>
  <EasyDataTable :headers="headers" :items="items">
  </EasyDataTable>

</template>

<style scoped>

</style>
