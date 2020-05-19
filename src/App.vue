<template lang="pug">
  #app
    Top
    Marquee1
    Content
    Footer
</template>

<script>
import Top from './components/Top'
import Marquee1 from './components/Marquee1'
import Content from './components/Content'
import Footer from './components/Footer'

export default {
  name: 'App',
  components: {
    Top,
    Marquee1,
    Content,
    Footer
  }
}
</script>
