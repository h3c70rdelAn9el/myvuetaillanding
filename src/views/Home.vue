<template>
  <div>
    <Hero />
    <Features />
    <ActionCall />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
import Hero from '@/components/Hero.vue';
import Features from '@/components/Features.vue'
import ActionCall from '@/components/ActionCall.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'Home',
  components: {
    Hero,
    Features,
    ActionCall,
    Footer
  }
}
</script>
