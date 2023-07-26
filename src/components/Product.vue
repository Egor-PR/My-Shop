<template>
    <div>
  <div class="product">
    <a href="#">
      <img src="/img/product1.jpeg" alt="" class="product-image" />
    </a>
    <a href="#" class="product-name"> Iphone 13 </a>
    <span class="product-price">1000</span>
    <button class="product-button"> Отправить в корзину</button>
  </div>
  <div class="product">
    <a href="#">
      <img src="/img/product2.jpeg" alt="" class="product-image" />
    </a>
    <a href="#" class="product-name"> Iphone 14 Pro Max</a>
    <span class="product-price">2000</span>
    <button class="product-button"> Отправить в корзину</button>
  </div>
  </div>
</template>

<script setup>
</script>
<style lang="scss" scoped>
.product {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin-bottom: 20px;
  &:last-child {
    margin-bottom: 0;
  }
  &-image {
    display: block;
    border: 5px;
  }
  &-name {
    display: block;
    color: black;
    font-size: 25px;
    line-height: 28px;
    text-decoration: none;
  }
  &-price {
    display: block;
    font-size: 20px;
    color: black;
  }
  &-button{
    padding: 20px;
    background:green;
    border-radius: 10px;
  }
}
</style>