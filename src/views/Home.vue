<template>
  <div>
    <Hero />
    <Features />
    <ActionCall />
  </div>
</template>

<script>
// @ is an alias to /src
import Hero from '@/components/Hero.vue';
import Features from '@/components/Features.vue'
import ActionCall from '@/components/ActionCall.vue'

export default {
  name: 'Home',
  components: {
    Hero,
    Features,
    ActionCall
  }
}
</script>
