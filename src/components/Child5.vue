<template>
  <div>Child5</div>
</template>

<script>

import MyVue from '@/MyVue'

export default {
  data() {
    return {
      name: 'child5'
    }
  },
  extends: MyVue
}
</script>