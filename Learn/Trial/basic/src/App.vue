<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <gambar/>
    <p>Wellcome to the {{store}} store</p>
    <p>Please, visit us at {{address}}</p>
    <ol>
      <li v-for="type in listing" :key="type">{{type}}</li>
    </ol>
    <button @click='klik'>Cek List Kita</button>
    <icon/>
  </div>
</template>

<script>
// import func from '../vue-temp/vue-editor-bridge'
// import HelloWorld from './components/HelloWorld.vue'
import gambar from './components/gambar.vue'
import icon from './components/pictIcon.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld,
    gambar,
    icon
  },
  data: function (){
    return{
      color:{
        1:'black',
        2:'navy',
        3:'maroon'
      },
      store:'Kazan',
      address:'Lemon street no. 51',
          listing:['LCD','Laptop','Accessories']
    }
  },
  methods:{
    klik:function(){
      this.listing=['Ipad','Macbook','Fan'];
    }
  }
}
</script>

<style scoped>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
