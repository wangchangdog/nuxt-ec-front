<template>
  <SiteHeader />
  <div class="">
    <div class="">
      <div class="">
        <SiteSideBar />
      </div>
      <div class="">
        <NuxtPage />
      </div>
    </div>
  </div>
  <SiteFooter />
</template>

<script>
import SiteFooter from '~/components/layout/SiteFooter.vue'
import SiteHeader from '~/components/layout/SiteHeader.vue'
import SiteSideBar from '~/components/layout/SiteSideBar.vue'
import NuxtPage from '~/components/ui/NuxtPage.vue'

export default {
  name: 'App',
  layout: 'SiteLayout',
  components: {
    SiteHeader,
    SiteFooter,
    SiteSideBar,
    NuxtPage,
  }
}
</script>