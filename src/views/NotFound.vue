<template>
  <div class="not-found">
    <NavBar />
    <div class="container">
      <div class="row justify-content-center mt-5">
        <div class="col text-center">
          <img src="../assets/images/notfound.svg" class="mb-5" alt="..." width="300" />
          <h1 class="mb-5"><strong>Oops!!</strong></h1>
          <h4 class="mb-5">The page you are looking for doesn't seem to exist</h4>
          <router-link
            to="/"
            class="btn btn-warning btn-lg text-white"
          >
            Back to Home
          </router-link>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import NavBar from "@/components/NavBar.vue";

export default {
  name: "NotFound",
  components: {
    NavBar,
  },
};
</script>

<style>
</style>