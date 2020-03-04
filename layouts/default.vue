<template>
  <div>
    <TheHeader />
    <main class="main-content">
      <nuxt />
    </main>
    <TheFooter />
  </div>
</template>
<script>
import TheHeader from '@/components/Core/TheHeader'
import TheFooter from '@/components/Core/TheFooter'
export default {
  components: {
    TheHeader,
    TheFooter
  }
}
</script>
