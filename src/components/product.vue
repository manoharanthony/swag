<template>
  <div class="similar-product">
    <div class="product-text text-uppercase fjalla-one f32 text-white">You may also like</div>
    <div class="row">
      <div class="col-md-3" v-for="shirt in shirts" v-bind:key="shirt.index">
        <div class="bg-light mt40">
          <div class="product-img">
            <img src="../assets/img/1.jpeg" alt class="swag-shirt-img" />
          </div>
          <div class="pl-2">
            <div class="product-price text-left fjalla-one f20 pt10">
              <span class="rupee-symbol">&#8377;</span>
              {{shirt.price}}
            </div>
            <div class="product-name text-left f14 mb10">{{shirt.name}}</div>
            <div class="buy-btn text-left">
              <button type="submit" class="btn text-white f18 cart-btn mb15">Buy</button>
            </div>
          </div>
        </div>
      </div>

      <div class="col-md-3">
        <div class="product-img">
          <img src alt />
        </div>
        <div class="product-title">Full Sleeve Shirt Rollup</div>

        <div class="product-size">
          <ul class="text-left list-unstyled list-inline">
            <li class="list-inline-item">
              <a href class="size-list">S</a>
            </li>
            <li class="list-inline-item">
              <a href class="size-list">M</a>
            </li>
            <li class="list-inline-item">
              <a href class="size-list">L</a>
            </li>
            <li class="list-inline-item">
              <a href class="size-list">XL</a>
            </li>
            <li class="list-inline-item">
              <a href class="size-list">XXL</a>
            </li>
          </ul>
          <div class="size-chart">
            <a href="#">Size Chart</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      shirts: [
        {
          price: "2999",
          name: "Lines full sleeve shirt"
        },
        {
          price: "2799",
          name: "Lines full sleeve shirt with rollup"
        },
        {
          price: "2899",
          name: "Lines full sleeve"
        },
        {
          price: "2699",
          name: "Lines full sleeve shirt with rollup"
        }
      ]
    };
  }
};
</script>

<style lang="scss" scoped>
@import "~@/scss/import";

.product-text {
  background-color: $gray-dark-color;
}

.product-img {
  .swag-shirt-img {
    width: 100%;
    height: auto;
  }
}

.cart-btn {
  background: $gray-dark-color;
  padding: 0px 36px;
  border-radius: 0px;
}
</style>
