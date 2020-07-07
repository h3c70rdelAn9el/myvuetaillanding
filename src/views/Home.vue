<template>
  <div>
    <Hero />
    <Features />
  </div>
</template>

<script>
// @ is an alias to /src
import Hero from '@/components/Hero.vue';
import Features from '@/components/Features.vue'

export default {
  name: 'Home',
  components: {
    Hero,
    Features
  }
}
</script>
