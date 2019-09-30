<template>
  <div class="container">
    <div class="row justify-content-center">
      <div class="col-md-8">
        <div class="card">
          <div class="card-header">Example Component</div>

          <div class="card-body">I'm an example component.</div>

          <router-link to="/c1">Go to C1</router-link>
          <router-link to="/c2">Go to C2</router-link>

          <!-- route outlet -->
          <!-- component matched by the route will render here -->
          <router-view></router-view>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  mounted() {
    console.log("Component mounted.");
  }
};
</script>
