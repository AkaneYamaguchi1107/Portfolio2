<template>
  <div>
    <div class="hero">
      <h1 class="hero__title">はじめてのNuxt.js</h1>
      <p class="hero__sub-title">はじめてです。</p>
      <div class="hero__button">
        <button class="btn">
          <nuxt-link to="about">アバウトページへ</nuxt-link>
        </button>
      </div>
    </div>
    <div class="section">
      <div class="container">
        <div class="row">
          <div class="col col--4">
            <div style="background: black; padding: 40px; color: white;">
              ITEM1
            </div>
          </div>
          <div class="col col--4">
            <div style="background: black;  padding: 40px; color: white;">
              ITEM1
            </div>
          </div>
          <div class="col col--4">
            <div style="background: black;  padding: 40px; color: white;">
              ITEM1
            </div>
          </div>
          <div class="col col--6">
            <div style="background: black;  padding: 40px; color: white;">
              ITEM1
            </div>
          </div>
          <div class="col col--6">
            <div style="background: black;  padding: 40px; color: white;">
              ITEM1
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.hero {
  padding: 0 16px;
  height: 600px;
  display: flex;
  flex-flow: column;
  justify-content: center;
  color: $color-primary;
  background: center/cover url(/images/hero.jpg);
  @include sp {
    color: blue;
  }
  &__title {
    font-size: 32px;
    font-weight: bold;
    margin-bottom: 24px;
  }
  &__sub-title {
    font-size: 24px;
    margin-bottom: 24px;
  }
}
</style>
