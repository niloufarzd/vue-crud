<template>
  <div>
    <header-bar></header-bar>
    <data-table></data-table>
    <b-container>
      <b-row class="mt-5">
        <router-view />
      </b-row>
    </b-container>
  </div>
</template>
<script>
import HeaderBar from "@/components/HeaderBar.vue";
import DataTable from "./components/DataTable .vue";

export default {
  components: {
    HeaderBar,
    DataTable,
  },
};
</script>
