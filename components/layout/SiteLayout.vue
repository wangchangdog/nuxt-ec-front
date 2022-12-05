<template>
  <div>
    <SiteHeader />
    <div class="container">
      <div class="row">
        <div class="col-md-3">
          <SiteSideBar />
        </div>
        <div class="col-md-9">
          <nuxt />
        </div>
      </div>
    <SiteFooter />
  </div>
</template>

<script lang="ts">
export default  {
  name: 'SiteLayout'
}
</script>