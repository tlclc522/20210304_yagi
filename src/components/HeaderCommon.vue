<template>
  <div id="firstview">
      <header id="top-header">
        <div class="flex">
          <h1 class="header-logo">estra inc.</h1>
          <nav class="header-nav">
            <ul>
              <li><a href="#">home</a></li>
              <li><a href="#">about</a></li>
              <li><a href="#">service</a></li>
              <li><a href="#">works</a></li>
              <li><a href="#">price</a></li>
              <li><a href="#">contact</a></li>
            </ul>
          </nav>
        </div>
        <div id="hamburger">
      <span></span>
      <span></span>
      <span></span>
    </div>
      </header>
      <p class="catchcopy">機械ではできない仕事を</p>
      <div class="news flex">
        <div class="news-content">
          <p class="news_date">2019/01/01</p>
          <p class="news_title">
            ニュースタイトルがここには入ります。3月の決算報告書
          </p>
        </div>
        <div class="news-icon">news</div>
      </div>
    </div>
    
</template>

<style scoped>
#top-header {
  height: 70px;
  line-height: 70px;
  background: rgba(0, 0, 0, 1);
}

.header-logo {
  font-size: 20px;
  font-weight: bold;
  margin-left: 35px;
  color: #fff;
  line-height: 70px;
}

.header-nav li {
  display: inline-block;
  margin-right: 35px;
  font-size: 16px;
}

.header-nav a {
  color: #fff;
}

@media screen and (max-width: 768px) {
  #hamburger {
    width: 40px;
    height: 40px;
    position: absolute;
    cursor: pointer;
    z-index: 100;
    top: 15px;
    right: 20px;
    transition: 0.4s;
  }
  #hamburger span {
    position: absolute;
    left: 2px;
    display: block;
    width: 35px;
    height: 2px;
    background-color: #fff;
    transition: 0.8s;
  }
  #hamburger span:nth-of-type(1) {
    top: 10px;
  }
  #hamburger span:nth-of-type(2) {
    top: 20px;
  }
  #hamburger span:nth-of-type(3) {
    top: 30px;
  }
  .header-nav {
    display: none;
  }
}

</style>