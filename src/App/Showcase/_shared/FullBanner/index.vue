<template>
  <a href="#" class="d-block text-gray-90">
    <div class="bg-img-hero pt-3" :style="`background-image: url('https://transvelo.github.io/electro-html/2.0/assets/img/1400X206/img1.jpg');`">
      <div class="space-top-2-md p-4 pt-4 pt-md-5 pt-lg-6 pt-xl-5 pb-lg-4 px-xl-8 px-lg-6">
        <div class="flex-horizontal-center overflow-auto overflow-md-visble">
          <h1 class="text-lh-38 font-size-24 font-weight-light mb-0 flex-shrink-0 flex-md-shrink-1">
            SHOP AND <strong>SAVE BIG</strong> ON HOTTEST TABLETS
          </h1>
          <div class="flex-content-center ml-4 flex-shrink-0">
            <div class="bg-primary rounded-lg px-6 py-2">
              <em class="font-size-14 font-weight-light">STARTING AT</em>
              <div class="font-size-30 font-weight-bold text-lh-1">
                <sup class="">$</sup>79<sup class="">99</sup>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </a>
</template>

<script>
export default {
  props: {
    image: String
  }
};
</script>

<style></style>
