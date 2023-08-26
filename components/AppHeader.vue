<template>
  <div class="wrap-nav-bar">
    <nav>
      <span><a href="#" class="nav-item">HOME</a></span>
      <span><a href="#" class="nav-item">PORTFOLIO</a></span>
      <span><a href="#" class="nav-item">PROJECTS</a></span>
      <span><a href="#" class="nav-item">BLOG</a></span>
    </nav>
  </div>
</template>

<style lang="scss">
  .wrap-nav-bar {
    margin: 1.5rem 0;
    nav {
      display: flex;
      > span {
        flex: 1;
        text-align: center;
        a {
          text-decoration: none;
          font-weight: 700;
          color: #777;
        }
      }
    }
  }
</style>
