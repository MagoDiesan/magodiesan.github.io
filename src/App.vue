<template>
  <div class="full-height">
    <heads></heads>
    <mains></mains>
    <foot></foot>
  </div>
</template>

<script>
import heads from './components/head-section.vue';
import mains from './components/main-section.vue';
import foot from './components/foot.vue';

export default {
  name: 'app',
  components : {
    heads,
    mains,
    foot
  }
}
</script>
