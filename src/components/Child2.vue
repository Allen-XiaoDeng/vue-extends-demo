<template>
  <div>Child2</div>
</template>

<script>

import MyVue from '@/MyVue'

export default {
  data() {
    return {
      name: 'child2'
    }
  },
  extends: MyVue,
}
</script>