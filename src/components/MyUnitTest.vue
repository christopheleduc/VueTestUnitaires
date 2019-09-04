<template>
<span>{{ message }}</span>
</template>

<script>
export default {
  data() {
    return {
      message: 'bonjour !'
    }
  },
  created () {
    this.message = 'au revoir !'
  }
}
</script>

<style scoped>
</style>
