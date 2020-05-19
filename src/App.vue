<template lang="pug">
  #app
    Top
    Marquee1
    Content
</template>

<script>
import Top from './components/Top'
import Marquee1 from './components/Marquee1'
import Content from './components/Content'

export default {
  name: 'App',
  components: {
    Top,
    Marquee1,
    Content
  }
}
</script>
