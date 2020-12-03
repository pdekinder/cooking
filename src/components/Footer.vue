<template>
  <div class="footer ui segment">
	Cooking app
  </div>
</template>

<script>
export default {
  name: "Footer"
}
</script>

<style scoped>
  .footer { /* Increased specificity for SO snippet priority */
    position: absolute;
    bottom: 0;
    width: 100%;
    color: #aaa;
    display: flex;
    justify-content: center;
    align-items: center;
    white-space: pre;
  }

  a {
    color: #aaa;
  }

  a:hover {
    text-decoration: underline;
  }
</style>