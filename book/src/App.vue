<template>
    <div>
      <router-view></router-view>
      <Tab></Tab>
    </div>
</template>
<script>
  import Tab from './base/Tab.vue'
    export default {
        data(){
            return {}
        },
        methods: {},
        computed: {},
        components: {Tab}
    }
</script>
<style>
  *{margin: 0;padding:0;  }
  ul,li{list-style: none}
  a{text-decoration: none}

  .content{
    position: fixed;width: 100%;
    top: 40px;
    bottom: 50px;
    overflow: auto;
  }

</style>
