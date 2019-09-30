<template>
  <div class="container">
    <div class="row justify-content-center">
      <div class="col-md-8">
        <div class="card">
          <div class="card-header">Component 1</div>

          <div class="card-body">I'm an Component 1.</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import xlsx from "xlsx";
import moment from "moment";

export default {
  mounted() {
    console.log("Component mounted.");
  }
};
</script>
