<template>
  <div>
    <h1>Index Seite</h1>
    <div>das ist HTML!!</div>
    {{ data }}
  </div>
</template>

<script setup lang="ts">

const { data } = useFetch("/api/hello");

</script>