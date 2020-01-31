<template>
  <div class="container">
    <div class="banner">
      <img class="logo" src=".././assets/logo.png"/>
      <label class="title">优能EnableU组织及人才发展</label>
    </div>
    <div class="menu">
      <img class="hamburger"/>
      <input class="search"/>
      <label class="login">登录</label>
      <label class="divider">｜</label>
      <label class="signup">注册</label>
    </div>
    <div class="cover">
      <img class="cover-image" src=".././assets/cover.jpg"/>
    </div>
    <div class="selections">
      <div class="selection-container">
        <img class="selection" src=".././assets/1.png"/>
        <label class="selection-text">优能介绍</label>
      </div>
      <div class="selection-container">
        <img class="selection" src=".././assets/2.png"/>
        <label class="selection-text">专家介绍</label>
      </div>
      <div class="selection-container">
        <img class="selection" src=".././assets/3.png"/>
        <label class="selection-text">好友专享</label>
      </div>
      <div class="selection-container">
        <img class="selection" src=".././assets/4.png"/>
        <label class="selection-text">合作联系</label>
      </div>
    </div>

    <div class="article">
      <img class="article-image"  src=".././assets/001.jpg"/>
      <label class="article-title">DISC 和 Motivator 激励因子的团队作用</label>
    </div>
    <div class="article">
      <img class="article-image"  src=".././assets/002.jpg"/>
      <label class="article-title">DISC 和 Motivator 激励因子的团队作用</label>
    </div>
    <div class="article">
      <img class="article-image"  src=".././assets/003.jpg"/>
      <label class="article-title">DISC 和 Motivator 激励因子的团队作用</label>
    </div>
    <div class="article">
      <img class="article-image"  src=".././assets/004.jpg"/>
      <label class="article-title">DISC 和 Motivator 激励因子的团队作用</label>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home',
}
</script>

<style scoped>
.container {
  display: flex;
  flex-direction: column;
}

.banner {
  width: 7.5rem;
  height: 1.15rem;
  display: flex;
}

.logo {
  margin-top: 0.115rem;
  margin-left: 0.26rem;
  width: 0.88rem;
  height: 0.88rem;
}

.title {
  font-size: 0.366rem;
  align-self: center;
  margin-left: 0.3rem;
}

.menu {
  width: 7.5rem;
  height: 0.61rem;
  background: #2b2b2b;
  display: flex;
}

.hamburger {
  width: 0.387rem;
  height: 0.293rem;
  align-self: center;
  margin-left: 0.26rem;
}

.search {
  width: 2.655rem;
  height: 0.418rem;
  align-self: center;
  border: none;
  margin-left: 2.2rem;
}

.login {
  font-size: 0.25rem;
  color: white;
  align-self: center;
  margin-left: 0.21rem;
}

.divider {
  font-size: 0.25rem;
  color: white;
  align-self: center;
}

.signup {
  font-size: 0.25rem;
  color: white;
  align-self: center;
}

.cover {
  width: 7.5rem;
  height: 2.34rem;
}

.cover-image {
  width: 100%;
  height: 100%;
}

.selections {
  width: 6.1rem;
  height: 1.86rem;
  display: flex;
  align-self: center;
  justify-content: space-between;
}

.selection-container {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.selection-text {
  margin-top: 0.125rem;
  font-size: 0.25rem;
}

.selection {
  width: 0.784rem;
  height: 0.784rem;
  margin-top: 0.355rem;
}

.article {
  width: 7.5rem;
  height: 1.725rem;
  margin-bottom: 0.105rem;
  display: flex;
}

.article-image {
  width: 2.72rem;
  height: 1.725rem;
  margin-left: 0.26rem;
}

.article-title {
  margin-left: 0.17rem;
  margin-top: 0.18rem;
  width: 3.95rem;
  font-size: 0.25rem;
}
</style>
