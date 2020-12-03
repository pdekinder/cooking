<template>
  <div class="footer ui segment">
      Favicon made by <a href="https://www.flaticon.com/free-icon/chef_483841" title="Those Icons">Those Icons</a>
      from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a>
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