<template>
<div class="home">
   
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <router-link to='csc'>
      <button>登录页面
      </button>
    </router-link>
    <pd/>
    </div>
</template>

<script>
import csc from './csc'
export default {
  components:{
   pd:csc
  },
  props:{},
  data(){
    return {
    }
  },
  watch:{},
  computed:{},
  methods:{},
  created(){},
  mounted(){}
}
</script>
<style scoped>
</style>
