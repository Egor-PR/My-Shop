<template>
  <header class="header">
    <div class="header-top">
      <div class="header-top-search">
        <img src="" alt="" />
      </div>
      <a href="" class="header-logo">My shop</a>
      <div class="header-top-rigth">
        <div href="" class="header-top-rigth__cart">
          <a href="">
            <img src="/svg/header-icon-shop.png" alt="cart" />
          </a>
        </div>
      </div>
    </div>
  </header>
</template>
<style lang="scss" scoped>
.header {
  height: 132px;
  background: #fff;
  &-top {
    display: flex;
    align-items: center;
    justify-content: space-between;
    height: 70px;
    border-bottom: 1px solid rgba(0, 0, 0, 0.1);
    &-rigth {
      display: flex;
      align-items: center;
      &-cart {
        margin-right: 15px;
      }
    }
  }
  &-logo {
    color: black;
    font-size: 24px;
    text-decoration: none;
  }
}
</style>