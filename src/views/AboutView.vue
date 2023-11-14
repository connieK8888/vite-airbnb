<template>
  <div class="about">
    <h1>This is an about page</h1>
    <MyCard></MyCard>
  </div>
</template>

<script>
// eslint-disable-next-line import/no-unresolved
import MyCard from '@/components/MyCard.vue';

export default {
  name: 'AboutView',
  components: {
    MyCard,
  },
};
</script>
