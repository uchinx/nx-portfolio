<template>
  <div class="border-wrapper">
    <section>
      <div class="left">
        <div class="info">
          <div class="top">
            <h1>Thinh Nguyen</h1>
            <br>
            <p>I'm a software engineer who tackles complex challenges with Go at work and tinkers with innovative projects in Rust on my own time</p>
          </div>
          <div class="bottom">
            <p style="margin-bottom: 5px;">@uchinka</p>
            <div class="socials">
              <ul>
                <li><img src="https://www.svgrepo.com/download/325236/github.svg" alt="github"></li>
              </ul>
            </div>
          </div>
        </div>
      </div>
      <div class="right">
        <img src="/unnamed.png" alt="avatar">
      </div>
    </section>
  </div>
</template>

<style lang="scss" scoped>
.border-wrapper {
  position: relative;
  background: linear-gradient(to right, rgb(220, 58, 158), #00c9a7);
  padding: 1px;
}

section {
  border: 1px solid #ddd;
  padding: 2rem;
  display: flex;
  flex-direction: row;
  justify-content: space-evenly;
  background-color: #fff;

  >div.left {
    flex: 5;
  }

  >div.right {
    flex: 3;
    overflow: hidden;

    >img {
      height: 230px;
      filter: opacity(0.8);
      -o-object-fit: cover;
      object-fit: cover;
      background-position: center;
      width: 255px;
    }
  }

  .info {
    display: flex;
    flex-direction: column;
    height: 100%;
    justify-content: space-between;
  }

  .socials {
    ul {
      padding: 0px;
      list-style: none;
      margin: 0;

      li {
        display: inline-block;
        padding-right: 15px;

        img {
          width: 28px;
          height: 28px;
        }
      }
    }
  }
}
</style>
