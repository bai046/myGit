<template>
  <div id="app">
    <router-view></router-view> 
    <!-- <el-container>
      <el-header>       
        <Header />
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>    
      </el-header>
      <el-main>
          <router-view></router-view>     
      </el-main>
    </el-container> -->
  </div>
</template>

<script>
import Header from "./components/NavBar/studio";

export default {
  name: "App",
  components: {
    Header,
  },
};
</script>

<style>
*{
  margin: 0;
  padding: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  /* color: #2c3e50; */
  /* margin-top: 60px; */
  
}
/*

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
} */
</style>
