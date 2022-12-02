<template>
  <div>
    <header-search />
    <QRandSlider />
    <DoubleBanner/>
    <GenderBanner/>
    <PopulerKategoriler/>
    <MyFooter />
  </div>
</template>

<script>
import QRandSlider from '~/components/QRandSlider.vue'

export default {
  name: 'DefaultLayout',
  components: { QRandSlider },
}
</script>
