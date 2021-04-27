<template>
  <div class="footer-container">
    <div class="footer-item1">
      <div class="item1-contents">
        <img src="../assets/logo.svg" alt="" />
        <a>Home</a>
        <a>Blog</a>
        <a>Features</a>
        <a>Pricing</a>
        <a>Documentation</a>
      </div>
      <p class="copyright">Copyright © 2018 by Random site</p>
    </div>
    <div class="footer-item2">
      <div class="footer-icons">
        <img src="../assets/socialmedia.png" alt="" />
      </div>
      <button class="footer-button">Get started</button>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.footer-container {
  display: grid;
  grid-template-columns: 1fr 1fr;
  background: #ffffff;
  padding: 93px 117px;
}
.item1-contents {
  display: flex;
  align-items: center;
  justify-content: center;
}
.item1-contents a {
  font-family: Quicksand;
  font-weight: 500;
  font-size: 12px;
  letter-spacing: 0.05em;
  color: #697ca6;
  text-shadow: 0px 0px 5px #e6e6e6;
  margin-right: 42px;
}
.item1-contents img {
  margin-right: 73px;
}
.copyright {
  font-family: Quicksand;
  font-weight: 500;
  font-size: 12px;
  letter-spacing: 0.05em;
  color: #aeb8d0;
  margin: 28px 0px 0px 100px;
}
.footer-item2 {
  display: flex;
  align-items: center;
  margin-left: auto;
}
.footer-button {
  width: 113px;
  height: 43px;
  background: #d2e1ff;
  border-radius: 2px;
  font-family: Quicksand;
  font-weight: bold;
  font-size: 13px;
  color: #3a79ff;
  border: none;
  margin-left: 44px;
}
</style>
