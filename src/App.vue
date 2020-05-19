<template lang="pug">
  #app
    Top
    Marquee1
    Content
    Footer
    //- 版權宣告
    <div>Icons made by <a href="http://www.dariusdan.com/" title="Darius Dan">Darius Dan</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a></div>
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
