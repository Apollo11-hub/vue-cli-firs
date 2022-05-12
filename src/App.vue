<template>
<div>
  <TitleCompo />
  <JumboTry />
</div>
</template>

<script>

import TitleCompo from "./components/TitleCompo.vue"
import JumboTry from "./components/JumboTry.vue"

export default {
  name: 'App',
  components: {
    TitleCompo,
    JumboTry,
  }
}
</script>

<style lang="scss">

</style>
