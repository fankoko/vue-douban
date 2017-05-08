<template>
<!-- 快速导航栏 -->
  <div class="nav-bar">
  <div class="Quick start">
    <router-link to="/" slot="left">
      <mt-button>影院热映</mt-button>
    </router-link>
    <router-link to="/" slot="right">
      <mt-button>欧美新碟榜</mt-button>
    </router-link>
    <router-link to="/" slot="left">
      <mt-button>注册账号</mt-button>
    </router-link>
    <router-link to="/" slot="right">
      <mt-button>登录豆瓣</mt-button>
    </router-link>
  </div>
  </div>
</template>

<script>

export default {
  name: 'nav-bar',
  data () {
    return {
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.nav-bar{
  height: 10rem;
  padding:0 2rem;
  margin: 1.2em 0;
}
.nav-bar a{
  margin-right: 3px;
}
.nav-bar button{
  width: 16rem;
  margin-top: 0.8rem;
  padding: 0;
  border-radius: 0;
  background-color: rgb(246, 246, 246);
  font-size: 1.5rem;

}
</style>
