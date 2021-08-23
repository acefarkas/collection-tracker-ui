<template>
  <collection-table />
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import CollectionTable from '@/components/CollectionTable.vue';

@Component({
  components: {
    CollectionTable,
  },
})
export default class Collection extends Vue {}
</script>
