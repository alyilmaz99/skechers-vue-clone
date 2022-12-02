<template>
  <div>
    <header-search />
    <QRandSlider />
    <DoubleBanner/>
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
