<template>
  <div>
    <SiteHeader />
    <div class="container">
      <div class="row">
        <div class="col-md-3">
          <SiteSideBar />
        </div>
        <div class="col-md-9">
          <NuxtPage />
        </div>
      </div>
    </div>
    <SiteFooter />
  </div>
</template>

<script>
import SiteFooter from '~/components/layout/SiteFooter.vue'
import SiteHeader from '~/components/layout/SiteHeader.vue'
import SiteSideBar from '~/components/layout/SiteSideBar.vue'
import NuxtPage from '~/components/ui/NuxtPage.vue'

export default {
  name: 'Index',
  components: {
    SiteHeader,
    SiteFooter,
    SiteSideBar,
    NuxtPage
  }
}
</script>