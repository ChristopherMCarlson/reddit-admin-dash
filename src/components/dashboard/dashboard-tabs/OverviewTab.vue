<template>
  <div class="overview-tab pt-2 layout">
    <div class="mb-2"></div>
    <div class="row">
      <div class="flex xs12 xl6 mb-5">
        <div class="overview-tab__item d-flex align--center">
          <div class="overview-tab__item-icon fill-height mr-2">
            <va-icon-vue/>
          </div>
          <div class="text--bold">{{$t('dashboard.tabs.overview.built')}}</div>
        </div>
      </div>

      <div class="flex xs12 xl6 mb-5">
        <div class="overview-tab__item d-flex align--center">
          <div class="overview-tab__item-icon fill-height mr-2">
            <va-icon-responsive/>
          </div>
          <div class="text--bold">{{$t('dashboard.tabs.overview.mobile')}}</div>
        </div>
      </div>
    </div>

    <div class="row">
      <div class="flex xs12 xl6 mb-5">
        <div class="overview-tab__item d-flex align--center">
          <div class="overview-tab__item-icon fill-height mr-2">
            <va-icon-free/>
          </div>
          <div class="text--bold">{{$t('dashboard.tabs.overview.free')}}</div>
        </div>
      </div>

      <div class="flex xs12 xl6 mb-5">
        <div class="overview-tab__item d-flex align--center">
          <div class="overview-tab__item-icon fill-height mr-2">
            <va-icon-rich/>
          </div>
          <div class="text--bold">{{$t('dashboard.tabs.overview.components')}}</div>
        </div>
      </div>
    </div>

    <div class="row">
      <div class="flex xs12 xl6 mb-5">
        <div class="overview-tab__item d-flex align--center">
          <div class="overview-tab__item-icon fill-height mr-2">
            <va-icon-fresh/>
          </div>
          <div class="text--bold">{{$t('dashboard.tabs.overview.fresh')}}</div>
        </div>
      </div>

      <div class="flex xs12 xl6">
        <div class="overview-tab__item d-flex align--center">
          <div class="overview-tab__item-icon fill-height mr-2">
            <va-icon-clean-code/>
          </div>
          <div class="text--bold">{{$t('dashboard.tabs.overview.nojQuery')}}</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import VaIconVue
  from 'vuestic-ui/src/components/vuestic-components/va-icon/va-iconset/VaIconVue.vue'
import VaIconFree
  from 'vuestic-ui/src/components/vuestic-components/va-icon/va-iconset/VaIconFree.vue'
import VaIconFresh
  from 'vuestic-ui/src/components/vuestic-components/va-icon/va-iconset/VaIconFresh.vue'
import VaIconResponsive
  from 'vuestic-ui/src/components/vuestic-components/va-icon/va-iconset/VaIconResponsive.vue'
import VaIconRich
  from 'vuestic-ui/src/components/vuestic-components/va-icon/va-iconset/VaIconRich.vue'
import VaIconCleanCode
  from 'vuestic-ui/src/components/vuestic-components/va-icon/va-iconset/VaIconCleanCode.vue'

export default {
  name: 'overview-tab',
  components: {
    VaIconCleanCode,
    VaIconRich,
    VaIconResponsive,
    VaIconFresh,
    VaIconFree,
    VaIconVue,
  },
}
</script>

<style lang="scss">
.overview-tab {
  &__item {
    height: 55px;

    &-icon {
      min-width: 65px;
      max-width: 65px;
    }
  }
}
</style>
