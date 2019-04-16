<template>
  <div>
    Hello {{ name }}
  </div>
</template

<script>
export default {
  computed: {
    name () {
      return 'World'
    }
  }
}
</script>
