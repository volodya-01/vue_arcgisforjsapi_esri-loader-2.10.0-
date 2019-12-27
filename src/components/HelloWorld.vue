<template>
  <div class="views">
    <mapshow/>
  </div>
</template>

<script>
import mapshow from './mapshow'
export default {
  name: 'HelloWorld',
  components:{
    mapshow
  },
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
@import "@/styles/global.scss";
.views {
  display: flex;
  flex-flow: column;
  justify-content: center;
  align-items: center;
  width: vw(1920);
  height: vh(1080);
  }

</style>
