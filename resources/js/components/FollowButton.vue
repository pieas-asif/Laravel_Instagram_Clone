<template>
  <div>
    <button class="ml-4 btn btn-primary font-weight-bold" @click="followUser">Follow</button>
  </div>
</template>

<script>
export default {
  mounted() {
    console.log("Component mounted.");
  },
  methods: {
    followUser() {
      alert("Inside");
    }
  }
};
</script>
