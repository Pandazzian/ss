<template>
  <div>
    <nav class="navbar navbar-expand-lg navbar-light bg-light" style="position: sticky;top: 0;">
      <a class="navbar-brand" href="#">
        <img src="/assets/img/logo.png" width="30px" height="30px" class="d-inline-block align-top" alt="">
        Sangsook
      </a>
      <div class="collapse navbar-collapse ml-auto" id="navbarNav" style="justify-content: flex-end;">
        <ul class="navbar-nav">
          <li class="nav-item active">
            <a class="nav-link" href="#">about us<span class="sr-only">(current)</span></a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">contact us</a>
          </li>
        </ul>
      </div>
    </nav>
    <Nuxt/>
  </div>
</template>

<script>
export default {
  name: "main_overlay"
}
</script>

<style scoped>

</style>
