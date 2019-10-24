<template>
  <div class="home">
    <div class="container">
      <!-- Breadcrumb start -->
      <nav aria-label="breadcrumb">
        <ol class="breadcrumb">
          <li class="breadcrumb-item">
            <a href="#">Home</a>
          </li>
          <li class="breadcrumb-item">
            <a href="#">Clothing</a>
          </li>
          <li class="breadcrumb-item">
            <a href="#">Men's Clothing</a>
          </li>
          <li class="breadcrumb-item">
            <a href="#">Shirts</a>
          </li>
        </ol>
      </nav>
      <!-- Breadcrumb end -->

      <div class="main">
        <div class="row">
          <!-- Shirt image start -->
          <div class="col-md-4">
            <div class="swag-shirt text-left card shadow">
              <img src="../assets/img/1.jpeg" alt class="swag-shirt-img" />
            </div>

            <div class="bg-light p15">
              <div class="slider">
                <div class="row">
                  <div class="col-md-3">
                    <img src="../assets/img/1.jpeg" alt class="swag-shirt-var1-img" />
                  </div>
                  <div class="col-md-3">
                    <img src="../assets/img/1.jpeg" alt class="swag-shirt-var1-img" />
                  </div>
                  <div class="col-md-3">
                    <img src="../assets/img/1.jpeg" alt class="swag-shirt-var1-img" />
                  </div>
                  <div class="col-md-3">
                    <img src="../assets/img/1.jpeg" alt class="swag-shirt-var1-img" />
                  </div>
                </div>
              </div>
            </div>

            <!-- <hooper :itemsToShow="3">
              <slide>slide 1</slide>
              <slide>slide 2</slide>
              <slide>slide 3</slide>
              <slide>slide 4</slide>
              <slide>slide 5</slide>
              <slide>slide 6</slide> 
            </hooper>
            
              <swiper-slide :options="swiperOptionh" class="slider">
                <swiper :options="swiperOptionv">
                  <swiper-slide>
                    <img src="../assets/img/1.jpeg" class="swag-shirt-var1-img" />
                  </swiper-slide>
                  <swiper-slide>
                    <img src="../assets/img/1.jpeg" class="swag-shirt-var1-img" />
                  </swiper-slide>

                  <div class="swiper-pagination swiper-pagination-v" slot="pagination"></div>
                </swiper>
              <div class="swiper-pagination swiper-pagination-h" slot="pagination"></div>
            </swiper-slide>-->

            <!-- Slider container -->
            <!-- <div class="swiper-container">
              <div class="swiper-wrapper">
                <div class="swiper-slide"><img src="../assets/img/1.jpeg" alt class="swag-shirt-var1-img" /></div>
                <div class="swiper-slide"><img src="../assets/img/1.jpeg" alt class="swag-shirt-var1-img" /></div>
                <div class="swiper-slide"><img src="../assets/img/1.jpeg" alt class="swag-shirt-var1-img" /></div>
                <div class="swiper-slide"><img src="../assets/img/1.jpeg" alt class="swag-shirt-var1-img" /></div>
              </div>
            </div>-->
            <!-- Slider container end -->
          </div>

          <!-- Shirt image end -->

          <div class="col-md-8">
            <div class="bg-light p15">
              <div class="section1">
                <!-- Shirt Name and Prize start -->
                <div class="shirt-title fjalla-one f26 text-left border-bottom-gray">
                  <div class="text-uppercase">Lines full sleeve shirt with rollup</div>
                  <div class="shirt-price mb15">
                    <span class="rupee-symbol">&#8377;</span>
                    2,899
                  </div>
                </div>
                <!-- Shirt Name and Prize end -->
              </div>

              <div class="section2 border-bottom-gray mt10">
                <div class="mb15">
                  <div class="row">
                    <div class="col-md-6">
                      <!-- Sizes start -->
                      <div class="sizes">
                        <div
                          class="size-text f20 opensans-semibold text-uppercase text-left mb10"
                        >Size</div>
                        <ul class="text-left f22 list-inline list-unstyled text-uppercase">
                          <li class="list-inline-item">
                            <a href="#" class="size-list border bg-light">s</a>
                          </li>
                          <li class="list-inline-item">
                            <a href="#" class="size-list border my-1 bg-light">m</a>
                          </li>
                          <li class="list-inline-item">
                            <a href="#" class="size-list border bg-light">l</a>
                          </li>
                          <li class="list-inline-item">
                            <a href="#" class="size-list border my-1 bg-light">xl</a>
                          </li>
                          <li class="list-inline-item">
                            <a href="#" class="size-list border bg-light">xxl</a>
                          </li>
                        </ul>
                        <div class="size-chart text-left f12">
                          <a href="#" class="text-muted">Size chart</a>
                        </div>
                      </div>
                    </div>
                    <!-- Sizes end -->

                    <!-- Select color start -->

                    <div class="col-md-6">
                      <div class="select-color">
                        <div class="text-uppercase f20 opensans-semibold text-left">Select Color</div>
                        <div class="shirt-color text-left">
                          <ul class="list-inline list-unstyled">
                            <li class="list-inline-item">
                              <a href="#">
                                <div class="shirt-color-img">
                                  <img
                                    src="../assets/img/1.jpeg"
                                    alt
                                    class="swag-shirt-color-img shadow"
                                  />
                                </div>
                              </a>
                            </li>
                            <li class="list-inline-item">
                              <a href="#">
                                <div class="shirt-color-img">
                                  <img
                                    src="../assets/img/1.jpeg"
                                    alt
                                    class="swag-shirt-color-img shadow"
                                  />
                                </div>
                              </a>
                            </li>
                            <li class="list-inline-item">
                              <a href="#">
                                <div class="shirt-color-img">
                                  <img
                                    src="../assets/img/1.jpeg"
                                    alt
                                    class="swag-shirt-color-img shadow"
                                  />
                                </div>
                              </a>
                            </li>
                            <li class="list-inline-item">
                              <a href="#">
                                <div class="shirt-color-img">
                                  <img
                                    src="../assets/img/1.jpeg"
                                    alt
                                    class="swag-shirt-color-img shadow"
                                  />
                                </div>
                              </a>
                            </li>
                          </ul>
                        </div>
                      </div>
                    </div>
                    <!-- Select color end -->
                  </div>
                </div>
              </div>

              <!-- Special Offers start -->
              <div class="section3 border-bottom-gray">
                <div class="f20 opensans-semibold text-uppercase text-left mt10">Special Offers</div>
                <ul class="list-unstyled text-left mb10">
                  <li>Instant 5% discount on all prepaid orders.</li>
                  <li
                    class="text-muted"
                  >Offer applicable over current promotions and discounts T&amp;C.</li>
                </ul>
              </div>
              <!-- Special Offers end -->

              <!-- Description start -->
              <div class="section4 border-bottom-gray">
                <div class="f20 opensans-semibold text-uppercase text-left mt10">Description</div>
                <ul class="list-unstyled mb10">
                  <li
                    class="text-left text-muted"
                  >Lorem ipsum dolor sit amet consectetur adipisicing elit. Quod sapiente temporibus sed quis fugiat fuga non modi. Corporis, non adipisci!</li>
                </ul>
              </div>
              <!-- Description end -->

              <!-- Specification start -->
              <div class="section5 border-bottom-gray">
                <div class="f20 opensans-semibold text-uppercase text-left mt10">Specification</div>
                <div class="mb10">
                  <div class="row">
                    <div class="col-md-6">
                      <div class="specification">
                        <div class="row">
                          <div class="col-md-5 col-sm-5 col-xs-5 text-left">
                            <div class="specification">Brand</div>
                          </div>
                          <div class="col-md-7 col-sm-7 col-xs-7 text-left">
                            <div class="specification-text text-muted">MaroSwag</div>
                          </div>
                        </div>

                        <div class="row">
                          <div class="col-md-5 col-sm-5 col-xs-5 text-left">
                            <div class="specification">Collection</div>
                          </div>
                          <div class="col-md-7 col-sm-7 col-xs-7 text-left">
                            <div class="specification-text text-muted">Amten Prints</div>
                          </div>
                        </div>

                        <div class="row">
                          <div class="col-md-5 col-sm-5 col-xs-5 text-left">
                            <div class="specification">Sleeve</div>
                          </div>
                          <div class="col-md-7 col-sm-7 col-xs-7 text-left">
                            <div class="specification-text text-muted">Half Sleeve</div>
                          </div>
                        </div>

                        <div class="row">
                          <div class="col-md-5 col-sm-5 col-xs-5 text-left">
                            <div class="specification">Fabric</div>
                          </div>
                          <div class="col-md-7 col-sm-7 col-xs-7 text-left">
                            <div class="specification-text text-muted">56% Cotton, 44% Tensel</div>
                          </div>
                        </div>

                        <div class="row mb10">
                          <div class="col-md-5 col-sm-5 col-xs-5 text-left">
                            <div class="specification">Base color</div>
                          </div>
                          <div class="col-md-7 col-sm-7 col-xs-7 text-left">
                            <div class="specification text-muted">White</div>
                          </div>
                        </div>
                      </div>
                    </div>
                    <div class="col-md-6">
                      <div class="wash-care opensans-semibold text-uppercase text-left">Wash care</div>
                      <div
                        class="text-left text-muted"
                      >Lorem ipsum dolor, sit amet consectetur adipisicing elit. Saepe deleniti porro ut dolorum sint ab veritatis aspernatur earum quod nostrum.</div>
                    </div>
                  </div>
                </div>
              </div>
              <!-- Specification end -->

              <div class="section6">
                <div class="mt10 mb10 text-left">
                  <!-- <div class="row mb20">

                  <div class="col-md-4">
                    <div class="form-check">
                        <input type="checkbox" class="form-check-input" id="exampleCheck1" />
                        <label class="form-check-label text-muted f14">Add to compare</label>
                      </div>
                  </div>
                  <div class="col-md-4">
                    <a href="#" class="offers text-muted f14">Offers?</a>
                  </div>
                  <div class="col-md-4">
                    <div class="text-muted f14">Buy 1 Get 1 Free</div>
                  </div>
                  </div>-->

                  <ul class="list-inline mb20 f14">
                    <li class="list-inline-item">
                      <form action>
                        <input type="checkbox" id="fruit" name="fruit" value="Apple" />
                        <label for="fruit">Add to compare</label>
                      </form>
                      <!-- https://stackoverflow.com/questions/4148499/how-to-style-a-checkbox-using-css -->
                      <!-- https://www.youtube.com/watch?v=cXVbsTT5gU8 -->
                    </li>
                    <li class="list-inline-item mx-5">
                      <a href="#" class="offers text-muted">Offers?</a>
                    </li>
                    <li class="list-inline-item text-muted">Buy 1 Get 1 Free</li>
                  </ul>

                  <!-- Add to cart button -->
                  <button
                    type="submit"
                    class="btn text-uppercase text-white f22 cart-btn mr-4 mb15"
                  >Add to cart</button>

                  <!-- Add to Wishlist button -->
                  <button
                    type="submit"
                    class="btn text-uppercase text-white f22 wishlist-btn mb15"
                  >Add to Wishlist</button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

// import { Hooper, Slide } from "hooper";

export default {
  // data() {
  //   return {
  //     swiperOptionh: {
  //       pagination: ".swiper-pagination-h",
  //       paginationClickable: true,
  //       spaceBetween: 50
  //     },
  //     swiperOption: {
  //       centeredSlides: true,
  //       autoplay: 5000,
  //       loop: true,
  //       pagination: ".swiper-pagination",
  //       slidesPerView: 1,
  //       paginationClickable: true,
  //       spaceBetween: 30,
  //       keyboardControl: true,
  //       nextButton: ".swiper-button-next",
  //       prevButton: ".swiper-button-prev"
  //     }
  //   };
  // },
  name: "home",
  components: {
    // HelloWorld
    // Hooper,
    // Slide
  }
};
</script>

<style lang="scss" scoped>
@import "~@/scss/import";

.breadcrumb {
  padding-left: 0px;
  background-color: transparent;
  color: black;

  a {
    color: black;
  }
}

.breadcrumb-item + .breadcrumb-item::before {
  content: ">";
  color: black;
}

.main {
  .swag-shirt {
    .swag-shirt-img {
      width: 100%;
      height: auto;
    }
  }

  .slider {
    width: 100%;
    height: auto;

    .swag-shirt-var1-img {
      width: 100%;
      height: auto;
    }
  }
}

.section1 {
  .shirt-price {
    .rupee-symbol {
      margin-top: -3px;
    }
  }
}

.section2 {
  .sizes {
    .size-list {
      padding: 1px 10px;
      color: black;

      &:hover {
        background-color: $gray-dark-color !important;
      }
    }

    .size-chart {
      text-decoration: underline;
    }
  }

  .shirt-color-img {
    width: 64px;
    height: 60px;
    .swag-shirt-color-img {
      width: 100%;
      height: 100%;
    }
  }
}

.section6 {
  .offers {
    text-decoration: underline;
  }
  .cart-btn,
  .wishlist-btn {
    background: $gray-dark-color;
    padding: 2px 30px;
    border-radius: 0px;
  }

  input[type="checkbox"] + label {
    display: block;
    margin: 0.2em;
    cursor: pointer;
    // padding: 2em;
  }

  input[type="checkbox"] {
    display: none;
  }

  input[type="checkbox"] + label:before {
    content: "\2714";
    border: 0.1em solid gray;
    border-radius: 0;
    display: inline-block;
    width: 1.3em;
    height: 1.3em;
    padding-left: 0.2em;
    padding-bottom: 0.3em;
    // padding: 0.3em 0.2em;
    margin-right: 0.2em;
    // vertical-align: bottom;
    color: transparent;
    // transition: .2s;
  }

  input[type="checkbox"] + label:active:before {
    transform: scale(0);
  }

  input[type="checkbox"]:checked + label:before {
    background-color: gray;
    border-color: gray;
    color: #fff;
  }

  input[type="checkbox"]:disabled + label:before {
    transform: scale(1);
    border-color: #aaa;
  }

  input[type="checkbox"]:checked:disabled + label:before {
    transform: scale(1);
    background-color: #bfb;
    border-color: #bfb;
  }
}
</style>
