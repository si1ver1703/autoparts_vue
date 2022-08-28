<template>
  <main class="overflow-hidden">

    <!-- newsLetter_popup Start -->
    <button data-mfp-src="#newsLetter-popup" class="modal-btn d-none"></button>
    <div id="newsLetter-popup" class="mfp-hide p-4" role="dialog">
      <div class="row align-items-center justify-content-sm-between">
        <div class="col-lg-5 d-lg-block d-none">
          <div class="newsLetter-popup__thumb imgenews">
            <img src="src/assets/images/home-three/products-1.jpg" alt="newsletter">
          </div>
        </div>
        <div class="col-lg-7 col-md-8 col-sm-10">
          <div class="newsLetter-popup__content mb-4">
            <div class="text-center"> <a href="index.html" class="logo"> <img
                src="src/assets/images/logo/logo.png" alt="logo"> </a>
              <h2> Join <span>with us.</span> </h2>
              <p> Subscribe to receive news from Karte In a free hour </p>
            </div>
            <form action="#0" class="newsLetter-popup__subscrib-form">
              <div class="input_box"> <input type="email" placeholder="Enter your email Address"
                                             name="email"> <button type="submit" class="subscribe_btn"> Submit </button> </div>
              <div class="form-group "> <input type="checkbox" id="html"> <label for="html"> By providing
                my information, I agree to Karte <a href="#0"> Privacy Policy</a> and <a href="#0">
                  Legal Statement</a> </label> </div>
            </form>
          </div>
        </div>
      </div>
    </div>


    <!-- Start Main Slider -->
    <section class="banner-style-3 overflow-hidden">
      <!-- Banner Carousel -->
      <div class="banner-slide3 slick" data-slick='{"dots": true, "infinite": true, "speed": 600, "slidesToShow": 1,
                "slidesToScroll": 1, "arrows": false, "autoplay": true, "autoplaySpeed": 6000,
                 "fade": false, "pauseOnHover": false}'>

        <!-- Slide -->
        <div class="slide">
          <div class="contant-box position-relative">

            <img class="bg-img hundread-vh" src="src/assets/images/home-three/autoparts1.png" alt="image">

          </div>
        </div>
      </div>
    </section>
    <!-- End Main Slider -->


    <!--Start Products Six-->
    <section class="products-three pt-60 pb-60 overflow-hidden">
      <div class="auto-container container">
        <div class="section-header style3 text-center wow fadeInUp animated">
          <h2>Latest Shoes </h2>
          <p> Weekend Top Brands </p>
        </div>
        <div class="row">
          <div class="col-xl-12">
            <div class="products-three__inner">
              <ul>
                <!--Start Products Six Single-->
                <li class="products-three-single wow fadeInUp animated">
                  <div class="products-three-single-img">
                    <a href="shop-details-3.html" class="d-block"> <img
                        src="src/assets/images/home-three/productss2-1.jpg" class="first-img"
                        alt="" /> <img src="src/assets/images/home-three/productss2-hover-1.png"
                                       alt="" class="hover-img" /> </a>
                    <div class="products-grid-one__badge-box"> <span
                        class="bg_base badge new ">New</span> </div> <a href="cart.html"
                                                                        class="addcart btn--primary style2"> Add To Cart </a>
                    <div class="products-grid__usefull-links">
                      <ul>
                        <li><a href="wishlist.html"> <i class="flaticon-heart"> </i> <span>
                                                            wishlist</span> </a> </li>
                        <li><a href="compare.html"> <i
                            class="flaticon-left-and-right-arrows"></i> <span>
                                                            compare</span> </a> </li>
                        <li><a href="#popup5" class="popup_link"> <i
                            class="flaticon-visibility"></i> <span> quick view</span>
                        </a> </li>
                      </ul>
                    </div>
                  </div>
                  <div id="popup5" class="product-gird__quick-view-popup mfp-hide">
                    <div class="container">
                      <div class="row justify-content-between align-items-center">
                        <div class="col-lg-6">
                          <div class="quick-view__left-content">
                            <div class="tabs">
                              <div class="popup-product-thumb-box">
                                <ul>
                                  <li class="tab-nav popup-product-thumb"> <a
                                      href="#tabb1"> <img
                                      src="src/assets/images/shop/products-v6-img5.jpg"
                                      alt="" /> </a> </li>
                                  <li class="tab-nav popup-product-thumb "> <a
                                      href="#tabb2"> <img
                                      src="src/assets/images/shop/products-v6-img6.jpg"
                                      alt="" /> </a> </li>
                                  <li class="tab-nav popup-product-thumb "> <a
                                      href="#tabb3"> <img
                                      src="src/assets/images/shop/products-v6-img7.jpg"
                                      alt="" /> </a> </li>
                                </ul>
                              </div>
                              <div class="popup-product-main-image-box">
                                <div id="tabb1" class="tab-item popup-product-image">
                                  <div class="popup-product-single-image"> <img
                                      src="src/assets/images/shop/products-v6-img5.jpg"
                                      alt="" /> </div>
                                </div>
                                <div id="tabb2" class="tab-item popup-product-image">
                                  <div class="popup-product-single-image"> <img
                                      src="src/assets/images/shop/products-v6-img6.jpg"
                                      alt="" /> </div>
                                </div>
                                <div id="tabb3" class="tab-item popup-product-image">
                                  <div class="popup-product-single-image"> <img
                                      src="src/assets/images/shop/products-v6-img7.jpg"
                                      alt="" /> </div>
                                </div> <button class="prev"> <i
                                  class="flaticon-back"></i> </button> <button
                                  class="next"> <i class="flaticon-next"></i>
                              </button>
                              </div>
                            </div>
                          </div>
                        </div>
                        <div class="col-lg-6">
                          <div class="popup-right-content">
                            <h3>Brown Office Shoe</h3>
                            <div class="ratting"> <i class="flaticon-star"></i> <i
                                class="flaticon-star"></i> <i class="flaticon-star"></i>
                              <i class="flaticon-star"></i> <i class="flaticon-star"></i>
                              <span>(112)</span> </div>
                            <p class="text"> Hydrating Plumping Intense Shine Lip Colour
                            </p>
                            <div class="price">
                              <h2> $42 USD <del> $65 USD</del></h2>
                              <h6> In stuck</h6>
                            </div>
                            <div class="color-varient"> <a href="#0"
                                                           class="color-name pink"> <span>Pink</span> </a> <a
                                href="#0" class="color-name red"> <span>Red</span> </a>
                              <a href="#0" class="color-name yellow"><span>Yellow</span>
                              </a> <a href="#0" class="color-name blue"> <span>Blue</span>
                              </a> <a href="#0" class="color-name black">
                                <span>Black</span> </a> </div>
                            <div class="add-product">
                              <h6>Qty:</h6>
                              <div class="button-group">
                                <div class="qtySelector text-center"> <span
                                    class="decreaseQty"><i
                                    class="flaticon-minus"></i> </span> <input
                                    type="number" class="qtyValue" value="1" />
                                  <span class="increaseQty"> <i
                                      class="flaticon-plus"></i> </span> </div>
                                <button class="btn--primary "> Add to Cart </button>
                              </div>
                            </div>
                            <div class="payment-method"> <a href="#0"> <img
                                src="src/assets/images/payment_method/method_1.png"
                                alt=""> </a> <a href="#0"> <img
                                src="src/assets/images/payment_method/method_2.png"
                                alt=""> </a> <a href="#0"> <img
                                src="src/assets/images/payment_method/method_3.png"
                                alt=""> </a> <a href="#0"> <img
                                src="src/assets/images/payment_method/method_4.png"
                                alt=""> </a> </div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="products-three-single-content text-center"> <span>Men Shoes</span>
                    <h5><a href="shop-details-3.html"> Trendy stylish shoes </a></h5>
                    <p><del>$200.00</del> $159.00</p>
                  </div>
                </li>
                <!--End Products Six Single-->
                <!--Start Products Six Single-->
                <li class="products-three-single wow fadeInUp animated">
                  <div class="products-three-single-img">
                    <a href="shop-details-3.html" class="d-block">
                      <img src="src/assets/images/home-three/productss2-hover-2.png" class="first-img"
                           alt="" />
                      <img src="src/assets/images/home-three/productss2-2.jpg" alt=""
                           class="hover-img" />
                    </a>
                    <div class="products-grid-one__badge-box"> <span
                        class="bg_black badge discount">-70%</span> </div> <a href="cart.html"
                                                                              class="addcart btn--primary style2"> Add To Cart </a>
                    <div class="products-grid__usefull-links">
                      <ul>
                        <li><a href="wishlist.html"> <i class="flaticon-heart"> </i> <span>
                                                            wishlist</span> </a> </li>
                        <li><a href="compare.html"> <i
                            class="flaticon-left-and-right-arrows"></i> <span>
                                                            compare</span> </a> </li>
                        <li><a href="#popup6" class="popup_link"> <i
                            class="flaticon-visibility"></i> <span> quick view</span>
                        </a> </li>
                      </ul>
                    </div>
                  </div>
                  <div id="popup6" class="product-gird__quick-view-popup mfp-hide">
                    <div class="container">
                      <div class="row justify-content-between align-items-center">
                        <div class="col-lg-6">
                          <div class="quick-view__left-content">
                            <div class="tabs">
                              <div class="popup-product-thumb-box">
                                <ul>
                                  <li class="tab-nav popup-product-thumb"> <a
                                      href="#tabb11"> <img
                                      src="src/assets/images/shop/products-v6-img6.jpg"
                                      alt="" /> </a> </li>
                                  <li class="tab-nav popup-product-thumb "> <a
                                      href="#tabb22"> <img
                                      src="src/assets/images/shop/products-v6-img7.jpg"
                                      alt="" /> </a> </li>
                                  <li class="tab-nav popup-product-thumb "> <a
                                      href="#tabb33"> <img
                                      src="src/assets/images/shop/products-v6-img8.jpg"
                                      alt="" /> </a> </li>
                                </ul>
                              </div>
                              <div class="popup-product-main-image-box">
                                <div id="tabb11" class="tab-item popup-product-image">
                                  <div class="popup-product-single-image"> <img
                                      src="src/assets/images/shop/products-v6-img6.jpg"
                                      alt="" /> </div>
                                </div>
                                <div id="tabb22" class="tab-item popup-product-image">
                                  <div class="popup-product-single-image"> <img
                                      src="src/assets/images/shop/products-v6-img7.jpg"
                                      alt="" /> </div>
                                </div>
                                <div id="tabb33" class="tab-item popup-product-image">
                                  <div class="popup-product-single-image"> <img
                                      src="src/assets/images/shop/products-v6-img8.jpg"
                                      alt="" /> </div>
                                </div> <button class="prev"> <i
                                  class="flaticon-back"></i> </button> <button
                                  class="next"> <i class="flaticon-next"></i>
                              </button>
                              </div>
                            </div>
                          </div>
                        </div>
                        <div class="col-lg-6">
                          <div class="popup-right-content">
                            <h3>Brown Office Shoe</h3>
                            <div class="ratting"> <i class="flaticon-star"></i> <i
                                class="flaticon-star"></i> <i class="flaticon-star"></i>
                              <i class="flaticon-star"></i> <i class="flaticon-star"></i>
                              <span>(112)</span> </div>
                            <p class="text"> Hydrating Plumping Intense Shine Lip Colour
                            </p>
                            <div class="price">
                              <h2> $42 USD <del> $65 USD</del></h2>
                              <h6> In stuck</h6>
                            </div>
                            <div class="color-varient"> <a href="#0"
                                                           class="color-name pink"> <span>Pink</span> </a> <a
                                href="#0" class="color-name red"> <span>Red</span> </a>
                              <a href="#0" class="color-name yellow"><span>Yellow</span>
                              </a> <a href="#0" class="color-name blue"> <span>Blue</span>
                              </a> <a href="#0" class="color-name black">
                                <span>Black</span> </a> </div>
                            <div class="add-product">
                              <h6>Qty:</h6>
                              <div class="button-group">
                                <div class="qtySelector text-center"> <span
                                    class="decreaseQty"><i
                                    class="flaticon-minus"></i> </span> <input
                                    type="number" class="qtyValue" value="1" />
                                  <span class="increaseQty"> <i
                                      class="flaticon-plus"></i> </span> </div>
                                <button class="btn--primary "> Add to Cart </button>
                              </div>
                            </div>
                            <div class="payment-method"> <a href="#0"> <img
                                src="src/assets/images/payment_method/method_1.png"
                                alt=""> </a> <a href="#0"> <img
                                src="src/assets/images/payment_method/method_2.png"
                                alt=""> </a> <a href="#0"> <img
                                src="src/assets/images/payment_method/method_3.png"
                                alt=""> </a> <a href="#0"> <img
                                src="src/assets/images/payment_method/method_4.png"
                                alt=""> </a> </div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="products-three-single-content text-center"> <span>Men Shoes</span>
                    <h5><a href="shop-details-3.html">Exclusive Sneakers </a></h5>
                    <p>$159.00</p>
                  </div>
                </li>
                <!--End Products Six Single-->
                <!--Start Products Six Single-->
                <li class="products-three-single wow fadeInUp animated">
                  <div class="products-three-single-img">
                    <a href="shop-details-3.html" class="d-block">
                      <img src="src/assets/images/home-three/productss2-3.jpg" alt="" />
                    </a>

                    <a href="cart.html" class="addcart btn--primary style2">
                      Add To Cart
                    </a>
                    <div class="products-grid__usefull-links">
                      <ul>
                        <li><a href="wishlist.html"> <i class="flaticon-heart"> </i> <span>
                                                            wishlist</span> </a> </li>
                        <li><a href="compare.html"> <i
                            class="flaticon-left-and-right-arrows"></i> <span>
                                                            compare</span> </a> </li>
                        <li><a href="#popup7" class="popup_link"> <i
                            class="flaticon-visibility"></i> <span> quick view</span>
                        </a> </li>
                      </ul>
                    </div>
                    <div id="popup7" class="product-gird__quick-view-popup mfp-hide">
                      <div class="container">
                        <div class="row justify-content-between align-items-center">
                          <div class="col-lg-6">
                            <div class="quick-view__left-content">
                              <div class="tabs">
                                <div class="popup-product-thumb-box">
                                  <ul>
                                    <li class="tab-nav popup-product-thumb"> <a
                                        href="#tabb111"> <img
                                        src="src/assets/images/shop/products-v6-img7.jpg"
                                        alt="" /> </a> </li>
                                    <li class="tab-nav popup-product-thumb "> <a
                                        href="#tabb222"> <img
                                        src="src/assets/images/shop/products-v6-img8.jpg"
                                        alt="" /> </a> </li>
                                    <li class="tab-nav popup-product-thumb "> <a
                                        href="#tabb333"> <img
                                        src="src/assets/images/shop/products-v6-img9.jpg"
                                        alt="" /> </a> </li>
                                  </ul>
                                </div>
                                <div class="popup-product-main-image-box">
                                  <div id="tabb111"
                                       class="tab-item popup-product-image">
                                    <div class="popup-product-single-image"> <img
                                        src="src/assets/images/shop/products-v6-img7.jpg"
                                        alt="" /> </div>
                                  </div>
                                  <div id="tabb222"
                                       class="tab-item popup-product-image">
                                    <div class="popup-product-single-image"> <img
                                        src="src/assets/images/shop/products-v6-img8.jpg"
                                        alt="" /> </div>
                                  </div>
                                  <div id="tabb333"
                                       class="tab-item popup-product-image">
                                    <div class="popup-product-single-image"> <img
                                        src="src/assets/images/shop/products-v6-img9.jpg"
                                        alt="" /> </div>
                                  </div> <button class="prev"> <i
                                    class="flaticon-back"></i> </button> <button
                                    class="next"> <i class="flaticon-next"></i>
                                </button>
                                </div>
                              </div>
                            </div>
                          </div>
                          <div class="col-lg-6">
                            <div class="popup-right-content">
                              <h3>Brown Office Shoe</h3>
                              <div class="ratting"> <i class="flaticon-star"></i> <i
                                  class="flaticon-star"></i> <i
                                  class="flaticon-star"></i> <i
                                  class="flaticon-star"></i> <i
                                  class="flaticon-star"></i> <span>(112)</span> </div>
                              <p class="text"> Hydrating Plumping Intense Shine Lip Colour
                              </p>
                              <div class="price">
                                <h2> $42 USD <del> $65 USD</del></h2>
                                <h6> In stuck</h6>
                              </div>
                              <div class="color-varient"> <a href="#0"
                                                             class="color-name pink"> <span>Pink</span> </a> <a
                                  href="#0" class="color-name red"> <span>Red</span>
                              </a> <a href="#0"
                                      class="color-name yellow"><span>Yellow</span> </a>
                                <a href="#0" class="color-name blue"> <span>Blue</span>
                                </a> <a href="#0" class="color-name black">
                                  <span>Black</span> </a> </div>
                              <div class="add-product">
                                <h6>Qty:</h6>
                                <div class="button-group">
                                  <div class="qtySelector text-center"> <span
                                      class="decreaseQty"><i
                                      class="flaticon-minus"></i> </span>
                                    <input type="number" class="qtyValue"
                                           value="1" /> <span class="increaseQty"> <i
                                        class="flaticon-plus"></i> </span>
                                  </div> <button class="btn--primary "> Add to Cart
                                </button>
                                </div>
                              </div>
                              <div class="payment-method"> <a href="#0"> <img
                                  src="src/assets/images/payment_method/method_1.png"
                                  alt=""> </a> <a href="#0"> <img
                                  src="src/assets/images/payment_method/method_2.png"
                                  alt=""> </a> <a href="#0"> <img
                                  src="src/assets/images/payment_method/method_3.png"
                                  alt=""> </a> <a href="#0"> <img
                                  src="src/assets/images/payment_method/method_4.png"
                                  alt=""> </a> </div>
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="products-three-single-content text-center"> <span>Men Shoes</span>
                    <h5><a href="shop-details-3.html">Fashionable Sneakers </a></h5>
                    <p><del>$200.00</del> $159.00</p>
                  </div>
                </li>
                <!--End Products Six Single-->
                <!--Start Products Six Single-->
                <li class="products-three-single  wow fadeInUp animated">
                  <div class="products-three-single-img"> <a href="shop-details-3.html"
                                                             class="d-block"> <img src="src/assets/images/home-three/productss2-4.jpg"
                                                                                   alt="" />
                  </a>
                    <div class="products-grid-one__badge-box"> <span
                        class="bg_black badge discount">-10%</span> </div> <a href="cart.html"
                                                                              class="addcart btn--primary style2"> Add To Cart </a>
                    <div class="products-grid__usefull-links">
                      <ul>
                        <li><a href="wishlist.html"> <i class="flaticon-heart"> </i> <span>
                                                            wishlist</span> </a> </li>
                        <li><a href="compare.html"> <i
                            class="flaticon-left-and-right-arrows"></i> <span>
                                                            compare</span> </a> </li>
                        <li><a href="#popup8" class="popup_link"> <i
                            class="flaticon-visibility"></i> <span> quick view</span>
                        </a> </li>
                      </ul>
                    </div>
                  </div>
                  <div id="popup8" class="product-gird__quick-view-popup mfp-hide">
                    <div class="container">
                      <div class="row justify-content-between align-items-center">
                        <div class="col-lg-6">
                          <div class="quick-view__left-content">
                            <div class="tabs">
                              <div class="popup-product-thumb-box">
                                <ul>
                                  <li class="tab-nav popup-product-thumb"> <a
                                      href="#tabb1111"> <img
                                      src="src/assets/images/shop/products-v6-img9.jpg"
                                      alt="" /> </a> </li>
                                  <li class="tab-nav popup-product-thumb "> <a
                                      href="#tabb2222"> <img
                                      src="src/assets/images/shop/products-v6-img9.jpg"
                                      alt="" /> </a> </li>
                                  <li class="tab-nav popup-product-thumb "> <a
                                      href="#tabb3333"> <img
                                      src="src/assets/images/shop/products-v6-img10.jpg"
                                      alt="" /> </a> </li>
                                </ul>
                              </div>
                              <div class="popup-product-main-image-box">
                                <div id="tabb1111" class="tab-item popup-product-image">
                                  <div class="popup-product-single-image"> <img
                                      src="src/assets/images/shop/products-v6-img8.jpg"
                                      alt="" /> </div>
                                </div>
                                <div id="tabb2222" class="tab-item popup-product-image">
                                  <div class="popup-product-single-image"> <img
                                      src="src/assets/images/shop/products-v6-img9.jpg"
                                      alt="" /> </div>
                                </div>
                                <div id="tabb3333" class="tab-item popup-product-image">
                                  <div class="popup-product-single-image"> <img
                                      src="src/assets/images/shop/products-v6-img10.jpg"
                                      alt="" /> </div>
                                </div> <button class="prev"> <i
                                  class="flaticon-back"></i> </button> <button
                                  class="next"> <i class="flaticon-next"></i>
                              </button>
                              </div>
                            </div>
                          </div>
                        </div>
                        <div class="col-lg-6">
                          <div class="popup-right-content">
                            <h3>Brown Office Shoe</h3>
                            <div class="ratting"> <i class="flaticon-star"></i> <i
                                class="flaticon-star"></i> <i class="flaticon-star"></i>
                              <i class="flaticon-star"></i> <i class="flaticon-star"></i>
                              <span>(112)</span> </div>
                            <p class="text"> Hydrating Plumping Intense Shine Lip Colour
                            </p>
                            <div class="price">
                              <h2> $42 USD <del> $65 USD</del></h2>
                              <h6> In stuck</h6>
                            </div>
                            <div class="color-varient"> <a href="#0"
                                                           class="color-name pink"> <span>Pink</span> </a> <a
                                href="#0" class="color-name red"> <span>Red</span> </a>
                              <a href="#0" class="color-name yellow"><span>Yellow</span>
                              </a> <a href="#0" class="color-name blue"> <span>Blue</span>
                              </a> <a href="#0" class="color-name black">
                                <span>Black</span> </a> </div>
                            <div class="add-product">
                              <h6>Qty:</h6>
                              <div class="button-group">
                                <div class="qtySelector text-center"> <span
                                    class="decreaseQty"><i
                                    class="flaticon-minus"></i> </span> <input
                                    type="number" class="qtyValue" value="1" />
                                  <span class="increaseQty"> <i
                                      class="flaticon-plus"></i> </span> </div>
                                <button class="btn--primary "> Add to Cart </button>
                              </div>
                            </div>
                            <div class="payment-method"> <a href="#0"> <img
                                src="src/assets/images/payment_method/method_1.png"
                                alt=""> </a> <a href="#0"> <img
                                src="src/assets/images/payment_method/method_2.png"
                                alt=""> </a> <a href="#0"> <img
                                src="src/assets/images/payment_method/method_3.png"
                                alt=""> </a> <a href="#0"> <img
                                src="src/assets/images/payment_method/method_4.png"
                                alt=""> </a> </div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="products-three-single-content text-center"> <span>Men Shoes</span>
                    <h5><a href="shop-details-3.html">Summer Shoes</a></h5>
                    <p>$159.00</p>
                  </div>
                </li>
                <!--End Products Six Single-->
                <!--Start Products Six Single-->
                <li class="products-three-single   wow fadeInUp animated">
                  <div class="products-three-single-img">
                    <a href="shop-details-3.html" class="d-block">
                      <img src="src/assets/images/home-three/productss2-5.jpg" class="first-img"
                           alt="" />
                      <img src="src/assets/images/home-three/productss2-hover-5.png" alt=""
                           class="hover-img" />
                    </a>
                    <a href="cart.html" class="addcart btn--primary style2"> Add To Cart </a>
                    <div class="products-grid__usefull-links">
                      <ul>
                        <li><a href="wishlist.html"> <i class="flaticon-heart"> </i> <span>
                                                            wishlist</span> </a> </li>
                        <li><a href="compare.html"> <i
                            class="flaticon-left-and-right-arrows"></i> <span>
                                                            compare</span> </a> </li>
                        <li><a href="#popup9" class="popup_link"> <i
                            class="flaticon-visibility"></i> <span> quick view</span>
                        </a> </li>
                      </ul>
                    </div>
                  </div>
                  <div id="popup9" class="product-gird__quick-view-popup mfp-hide">
                    <div class="container">
                      <div class="row justify-content-between align-items-center">
                        <div class="col-lg-6">
                          <div class="quick-view__left-content">
                            <div class="tabs">
                              <div class="popup-product-thumb-box">
                                <ul>
                                  <li class="tab-nav popup-product-thumb"> <a
                                      href="#tabc1"> <img
                                      src="src/assets/images/shop/products-v6-img9.jpg"
                                      alt="" /> </a> </li>
                                  <li class="tab-nav popup-product-thumb "> <a
                                      href="#tabc2"> <img
                                      src="src/assets/images/shop/products-v6-img9.jpg"
                                      alt="" /> </a> </li>
                                  <li class="tab-nav popup-product-thumb "> <a
                                      href="#tabc3"> <img
                                      src="src/assets/images/shop/products-v6-img10.jpg"
                                      alt="" /> </a> </li>
                                </ul>
                              </div>
                              <div class="popup-product-main-image-box">
                                <div id="tabc1" class="tab-item popup-product-image">
                                  <div class="popup-product-single-image"> <img
                                      src="src/assets/images/shop/products-v6-img8.jpg"
                                      alt="" /> </div>
                                </div>
                                <div id="tabc2" class="tab-item popup-product-image">
                                  <div class="popup-product-single-image"> <img
                                      src="src/assets/images/shop/products-v6-img9.jpg"
                                      alt="" /> </div>
                                </div>
                                <div id="tabc3" class="tab-item popup-product-image">
                                  <div class="popup-product-single-image"> <img
                                      src="src/assets/images/shop/products-v6-img10.jpg"
                                      alt="" /> </div>
                                </div> <button class="prev"> <i
                                  class="flaticon-back"></i> </button> <button
                                  class="next"> <i class="flaticon-next"></i>
                              </button>
                              </div>
                            </div>
                          </div>
                        </div>
                        <div class="col-lg-6">
                          <div class="popup-right-content">
                            <h3>Brown Office Shoe</h3>
                            <div class="ratting"> <i class="flaticon-star"></i> <i
                                class="flaticon-star"></i> <i class="flaticon-star"></i>
                              <i class="flaticon-star"></i> <i class="flaticon-star"></i>
                              <span>(112)</span> </div>
                            <p class="text"> Hydrating Plumping Intense Shine Lip Colour
                            </p>
                            <div class="price">
                              <h2> $42 USD <del> $65 USD</del></h2>
                              <h6> In stuck</h6>
                            </div>
                            <div class="color-varient"> <a href="#0"
                                                           class="color-name pink"> <span>Pink</span> </a> <a
                                href="#0" class="color-name red"> <span>Red</span> </a>
                              <a href="#0" class="color-name yellow"><span>Yellow</span>
                              </a> <a href="#0" class="color-name blue"> <span>Blue</span>
                              </a> <a href="#0" class="color-name black">
                                <span>Black</span> </a> </div>
                            <div class="add-product">
                              <h6>Qty:</h6>
                              <div class="button-group">
                                <div class="qtySelector text-center"> <span
                                    class="decreaseQty"><i
                                    class="flaticon-minus"></i> </span> <input
                                    type="number" class="qtyValue" value="1" />
                                  <span class="increaseQty"> <i
                                      class="flaticon-plus"></i> </span> </div>
                                <button class="btn--primary "> Add to Cart </button>
                              </div>
                            </div>
                            <div class="payment-method"> <a href="#0"> <img
                                src="src/assets/images/payment_method/method_1.png"
                                alt=""> </a> <a href="#0"> <img
                                src="src/assets/images/payment_method/method_2.png"
                                alt=""> </a> <a href="#0"> <img
                                src="src/assets/images/payment_method/method_3.png"
                                alt=""> </a> <a href="#0"> <img
                                src="src/assets/images/payment_method/method_4.png"
                                alt=""> </a> </div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="products-three-single-content text-center"> <span>Men Shoes</span>
                    <h5><a href="shop-details-3.html">Outdoor Sports Shoes</a></h5>
                    <p><del>$200.00</del> $159.00</p>
                  </div>
                </li>
                <!--End Products Six Single-->

                <!--Start Products Six Single-->
                <li class="products-three-single wow fadeInUp animated">
                  <div class="products-three-single-img">
                    <a href="shop-details-3.html" class="d-block">
                      <img src="src/assets/images/home-three/productss3-1.jpg" class="first-img"
                           alt="" />
                      <img src="src/assets/images/home-three/productss3-hover-1.jpg" alt=""
                           class="hover-img" />
                    </a>
                    <div class="products-grid-one__badge-box"> <span
                        class="bg_base badge new ">New</span> <span
                        class="bg_black badge discount">-40%</span> </div> <a href="cart.html"
                                                                              class="addcart btn--primary style2"> Add To Cart </a>
                    <div class="products-grid__usefull-links">
                      <ul>
                        <li><a href="wishlist.html"> <i class="flaticon-heart"> </i> <span>
                                                            wishlist</span> </a> </li>
                        <li><a href="compare.html"> <i
                            class="flaticon-left-and-right-arrows"></i> <span>
                                                            compare</span> </a> </li>
                        <li><a href="#popup" class="popup_link"> <i
                            class="flaticon-visibility"></i> <span> quick view</span>
                        </a> </li>
                      </ul>
                    </div>
                  </div>
                  <div id="popup" class="product-gird__quick-view-popup mfp-hide">
                    <div class="container">
                      <div class="row justify-content-between align-items-center">
                        <div class="col-lg-6">
                          <div class="quick-view__left-content">
                            <div class="tabs">
                              <div class="popup-product-thumb-box">
                                <ul>
                                  <li class="tab-nav popup-product-thumb"> <a
                                      href="#tab1"> <img
                                      src="src/assets/images/shop/products-v6-img1.jpg"
                                      alt="" /> </a> </li>
                                  <li class="tab-nav popup-product-thumb "> <a
                                      href="#tab2"> <img
                                      src="src/assets/images/shop/products-v6-img2.jpg"
                                      alt="" /> </a> </li>
                                  <li class="tab-nav popup-product-thumb "> <a
                                      href="#tab3"> <img
                                      src="src/assets/images/shop/products-v6-img3.jpg"
                                      alt="" /> </a> </li>
                                </ul>
                              </div>
                              <div class="popup-product-main-image-box">
                                <div id="tab1" class="tab-item popup-product-image">
                                  <div class="popup-product-single-image"> <img
                                      src="src/assets/images/shop/products-v6-img1.jpg"
                                      alt="" /> </div>
                                </div>
                                <div id="tab2" class="tab-item popup-product-image">
                                  <div class="popup-product-single-image"> <img
                                      src="src/assets/images/shop/products-v6-img2.jpg"
                                      alt="" /> </div>
                                </div>
                                <div id="tab3" class="tab-item popup-product-image">
                                  <div class="popup-product-single-image"> <img
                                      src="src/assets/images/shop/products-v6-img3.jpg"
                                      alt="" /> </div>
                                </div> <button class="prev"> <i
                                  class="flaticon-back"></i> </button> <button
                                  class="next"> <i class="flaticon-next"></i>
                              </button>
                              </div>
                            </div>
                          </div>
                        </div>
                        <div class="col-lg-6">
                          <div class="popup-right-content">
                            <h3>Sport Sneakers</h3>
                            <div class="ratting"> <i class="flaticon-star"></i> <i
                                class="flaticon-star"></i> <i class="flaticon-star"></i>
                              <i class="flaticon-star"></i> <i class="flaticon-star"></i>
                              <span>(112)</span> </div>
                            <p class="text"> Hydrating Plumping Intense Shine Lip Colour
                            </p>
                            <div class="price">
                              <h2> $42 USD <del> $65 USD</del></h2>
                              <h6> In stuck</h6>
                            </div>
                            <div class="color-varient"> <a href="#0"
                                                           class="color-name pink"> <span>Pink</span> </a> <a
                                href="#0" class="color-name red"> <span>Red</span> </a>
                              <a href="#0" class="color-name yellow"><span>Yellow</span>
                              </a> <a href="#0" class="color-name blue"> <span>Blue</span>
                              </a> <a href="#0" class="color-name black">
                                <span>Black</span> </a> </div>
                            <div class="add-product">
                              <h6>Qty:</h6>
                              <div class="button-group">
                                <div class="qtySelector text-center"> <span
                                    class="decreaseQty"><i
                                    class="flaticon-minus"></i> </span> <input
                                    type="number" class="qtyValue" value="1" />
                                  <span class="increaseQty"> <i
                                      class="flaticon-plus"></i> </span> </div>
                                <button class="btn--primary "> Add to Cart </button>
                              </div>
                            </div>
                            <div class="payment-method"> <a href="#0"> <img
                                src="src/assets/images/payment_method/method_1.png"
                                alt=""> </a> <a href="#0"> <img
                                src="src/assets/images/payment_method/method_2.png"
                                alt=""> </a> <a href="#0"> <img
                                src="src/assets/images/payment_method/method_3.png"
                                alt=""> </a> <a href="#0"> <img
                                src="src/assets/images/payment_method/method_4.png"
                                alt=""> </a> </div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="products-three-single-content text-center"> <span>Men Shoes</span>
                    <h5><a href="shop-details-3.html">Sport Sneakers</a></h5>
                    <p>$159.00</p>
                  </div>
                </li>
                <!--End Products Six Single-->
                <!--Start Products Six Single-->
                <li class="products-three-single wow fadeInUp animated">
                  <div class="products-three-single-img"> <a href="shop-details-3.html"
                                                             class="d-block"> <img src="src/assets/images/home-three/productss3-2.jpg"
                                                                                   alt="" />
                  </a> <a href="cart.html" class="addcart btn--primary style2">
                    Add To Cart </a>
                    <div class="products-grid__usefull-links">
                      <ul>
                        <li><a href="wishlist.html"> <i class="flaticon-heart"> </i> <span>
                                                            wishlist</span> </a> </li>
                        <li><a href="#0"> <i class="flaticon-left-and-right-arrows"></i> <span>
                                                            compare</span> </a> </li>
                        <li><a href="#popup1" class="popup_link"> <i
                            class="flaticon-visibility"></i> <span> quick view</span>
                        </a> </li>
                      </ul>
                    </div>
                  </div>
                  <div id="popup1" class="product-gird__quick-view-popup mfp-hide">
                    <div class="container">
                      <div class="row justify-content-between align-items-center">
                        <div class="col-lg-6">
                          <div class="quick-view__left-content">
                            <div class="tabs">
                              <div class="popup-product-thumb-box">
                                <ul>
                                  <li class="tab-nav popup-product-thumb"> <a
                                      href="#tab11"> <img
                                      src="src/assets/images/shop/products-v6-img1.jpg"
                                      alt="" /> </a> </li>
                                  <li class="tab-nav popup-product-thumb "> <a
                                      href="#tab22"> <img
                                      src="src/assets/images/shop/products-v6-img2.jpg"
                                      alt="" /> </a> </li>
                                  <li class="tab-nav popup-product-thumb "> <a
                                      href="#tab33"> <img
                                      src="src/assets/images/shop/products-v6-img3.jpg"
                                      alt="" /> </a> </li>
                                </ul>
                              </div>
                              <div class="popup-product-main-image-box">
                                <div id="tab11" class="tab-item popup-product-image">
                                  <div class="popup-product-single-image"> <img
                                      src="src/assets/images/shop/products-v6-img1.jpg"
                                      alt="" /> </div>
                                </div>
                                <div id="tab22" class="tab-item popup-product-image">
                                  <div class="popup-product-single-image"> <img
                                      src="src/assets/images/shop/products-v6-img2.jpg"
                                      alt="" /> </div>
                                </div>
                                <div id="tab33" class="tab-item popup-product-image">
                                  <div class="popup-product-single-image"> <img
                                      src="src/assets/images/shop/products-v6-img3.jpg"
                                      alt="" /> </div>
                                </div> <button class="prev"> <i
                                  class="flaticon-back"></i> </button> <button
                                  class="next"> <i class="flaticon-next"></i>
                              </button>
                              </div>
                            </div>
                          </div>
                        </div>
                        <div class="col-lg-6">
                          <div class="popup-right-content">
                            <h3>Brown Office Shoe</h3>
                            <div class="ratting"> <i class="flaticon-star"></i> <i
                                class="flaticon-star"></i> <i class="flaticon-star"></i>
                              <i class="flaticon-star"></i> <i class="flaticon-star"></i>
                              <span>(112)</span> </div>
                            <p class="text"> Hydrating Plumping Intense Shine Lip Colour
                            </p>
                            <div class="price">
                              <h2> $42 USD <del> $65 USD</del></h2>
                              <h6> In stuck</h6>
                            </div>
                            <div class="color-varient"> <a href="#0"
                                                           class="color-name pink"> <span>Pink</span> </a> <a
                                href="#0" class="color-name red"> <span>Red</span> </a>
                              <a href="#0" class="color-name yellow"><span>Yellow</span>
                              </a> <a href="#0" class="color-name blue"> <span>Blue</span>
                              </a> <a href="#0" class="color-name black">
                                <span>Black</span> </a> </div>
                            <div class="add-product">
                              <h6>Qty:</h6>
                              <div class="button-group">
                                <div class="qtySelector text-center"> <span
                                    class="decreaseQty"><i
                                    class="flaticon-minus"></i> </span> <input
                                    type="number" class="qtyValue" value="1" />
                                  <span class="increaseQty"> <i
                                      class="flaticon-plus"></i> </span> </div>
                                <button class="btn--primary "> Add to Cart </button>
                              </div>
                            </div>
                            <div class="payment-method"> <a href="#0"> <img
                                src="src/assets/images/payment_method/method_1.png"
                                alt=""> </a> <a href="#0"> <img
                                src="src/assets/images/payment_method/method_2.png"
                                alt=""> </a> <a href="#0"> <img
                                src="src/assets/images/payment_method/method_3.png"
                                alt=""> </a> <a href="#0"> <img
                                src="src/assets/images/payment_method/method_4.png"
                                alt=""> </a> </div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="products-three-single-content text-center"> <span>Men Shoes</span>
                    <h5><a href="shop-details-3.html">Apex Sneakers </a></h5>
                    <p>$159.00</p>
                  </div>
                </li>
                <!--End Products Six Single-->
                <!--Start Products Six Single-->
                <li class="products-three-single wow fadeInUp animated">
                  <div class="products-three-single-img">
                    <a href="shop-details-3.html" class="d-block">
                      <img src="src/assets/images/home-three/productss3-3.jpg" alt="" /> </a>
                    <div class="products-grid-one__badge-box"> <span
                        class="bg_base badge new ">New</span> </div> <a href="cart.html"
                                                                        class="addcart btn--primary style2"> Add To Cart </a>
                    <div class="products-grid__usefull-links">
                      <ul>
                        <li><a href="#0"> <i class="flaticon-heart"> </i> <span> wishlist</span>
                        </a> </li>
                        <li><a href="#0"> <i class="flaticon-left-and-right-arrows"></i> <span>
                                                            compare</span> </a> </li>
                        <li><a href="#popup2" class="popup_link"> <i
                            class="flaticon-visibility"></i> <span> quick view</span>
                        </a> </li>
                      </ul>
                    </div>
                  </div>
                  <div id="popup2" class="product-gird__quick-view-popup mfp-hide">
                    <div class="container">
                      <div class="row justify-content-between align-items-center">
                        <div class="col-lg-6">
                          <div class="quick-view__left-content">
                            <div class="tabs">
                              <div class="popup-product-thumb-box">
                                <ul>
                                  <li class="tab-nav popup-product-thumb"> <a
                                      href="#tab111"> <img
                                      src="src/assets/images/shop/products-v6-img3.jpg"
                                      alt="" /> </a> </li>
                                  <li class="tab-nav popup-product-thumb "> <a
                                      href="#tab222"> <img
                                      src="src/assets/images/shop/products-v6-img4.jpg"
                                      alt="" /> </a> </li>
                                  <li class="tab-nav popup-product-thumb "> <a
                                      href="#tab333"> <img
                                      src="src/assets/images/shop/products-v6-img5.jpg"
                                      alt="" /> </a> </li>
                                </ul>
                              </div>
                              <div class="popup-product-main-image-box">
                                <div id="tab111" class="tab-item popup-product-image">
                                  <div class="popup-product-single-image"> <img
                                      src="src/assets/images/shop/products-v6-img3.jpg"
                                      alt="" /> </div>
                                </div>
                                <div id="tab222" class="tab-item popup-product-image">
                                  <div class="popup-product-single-image"> <img
                                      src="src/assets/images/shop/products-v6-img4.jpg"
                                      alt="" /> </div>
                                </div>
                                <div id="tab333" class="tab-item popup-product-image">
                                  <div class="popup-product-single-image"> <img
                                      src="src/assets/images/shop/products-v6-img5.jpg"
                                      alt="" /> </div>
                                </div> <button class="prev"> <i
                                  class="flaticon-back"></i> </button> <button
                                  class="next"> <i class="flaticon-next"></i>
                              </button>
                              </div>
                            </div>
                          </div>
                        </div>
                        <div class="col-lg-6">
                          <div class="popup-right-content">
                            <h3>Brown Office Shoe</h3>
                            <div class="ratting"> <i class="flaticon-star"></i> <i
                                class="flaticon-star"></i> <i class="flaticon-star"></i>
                              <i class="flaticon-star"></i> <i class="flaticon-star"></i>
                              <span>(112)</span> </div>
                            <p class="text"> Hydrating Plumping Intense Shine Lip Colour
                            </p>
                            <div class="price">
                              <h2> $42 USD <del> $65 USD</del></h2>
                              <h6> In stuck</h6>
                            </div>
                            <div class="color-varient"> <a href="#0"
                                                           class="color-name pink"> <span>Pink</span> </a> <a
                                href="#0" class="color-name red"> <span>Red</span> </a>
                              <a href="#0" class="color-name yellow"><span>Yellow</span>
                              </a> <a href="#0" class="color-name blue"> <span>Blue</span>
                              </a> <a href="#0" class="color-name black">
                                <span>Black</span> </a> </div>
                            <div class="add-product">
                              <h6>Qty:</h6>
                              <div class="button-group">
                                <div class="qtySelector text-center"> <span
                                    class="decreaseQty"><i
                                    class="flaticon-minus"></i> </span> <input
                                    type="number" class="qtyValue" value="1" />
                                  <span class="increaseQty"> <i
                                      class="flaticon-plus"></i> </span> </div>
                                <button class="btn--primary "> Add to Cart </button>
                              </div>
                            </div>
                            <div class="payment-method"> <a href="#0"> <img
                                src="src/assets/images/payment_method/method_1.png"
                                alt=""> </a> <a href="#0"> <img
                                src="src/assets/images/payment_method/method_2.png"
                                alt=""> </a> <a href="#0"> <img
                                src="src/assets/images/payment_method/method_3.png"
                                alt=""> </a> <a href="#0"> <img
                                src="src/assets/images/payment_method/method_4.png"
                                alt=""> </a> </div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="products-three-single-content text-center"> <span>Men Shoes</span>
                    <h5><a href="shop-details-3.html">Fashionable Sneakers </a></h5>
                    <p>$159.00</p>
                  </div>
                </li>
                <!--End Products Six Single-->
                <!--Start Products Six Single-->
                <li class="products-three-single wow fadeInUp animated">
                  <div class="products-three-single-img"> <a href="shop-details-3.html"
                                                             class="d-block"> <img src="src/assets/images/home-three/productss3-4.jpg"
                                                                                   alt="" />
                  </a> <a href="cart.html" class="addcart btn--primary style2">
                    Add To Cart </a>
                    <div class="products-grid__usefull-links">
                      <ul>
                        <li><a href="wishlist.html"> <i class="flaticon-heart"> </i> <span>
                                                            wishlist</span> </a> </li>
                        <li><a href="compare.html"> <i
                            class="flaticon-left-and-right-arrows"></i> <span>
                                                            compare</span> </a> </li>
                        <li><a href="#popup3" class="popup_link"> <i
                            class="flaticon-visibility"></i> <span> quick view</span>
                        </a> </li>
                      </ul>
                    </div>
                  </div>
                  <div id="popup3" class="product-gird__quick-view-popup mfp-hide">
                    <div class="container">
                      <div class="row justify-content-between align-items-center">
                        <div class="col-lg-6">
                          <div class="quick-view__left-content">
                            <div class="tabs">
                              <div class="popup-product-thumb-box">
                                <ul>
                                  <li class="tab-nav popup-product-thumb"> <a
                                      href="#tab1111"> <img
                                      src="src/assets/images/shop/products-v6-img4.jpg"
                                      alt="" /> </a> </li>
                                  <li class="tab-nav popup-product-thumb "> <a
                                      href="#tab2222"> <img
                                      src="src/assets/images/shop/products-v6-img5.jpg"
                                      alt="" /> </a> </li>
                                  <li class="tab-nav popup-product-thumb "> <a
                                      href="#tab3333"> <img
                                      src="src/assets/images/shop/products-v6-img6.jpg"
                                      alt="" /> </a> </li>
                                </ul>
                              </div>
                              <div class="popup-product-main-image-box">
                                <div id="tab1111" class="tab-item popup-product-image">
                                  <div class="popup-product-single-image"> <img
                                      src="src/assets/images/shop/products-v6-img4.jpg"
                                      alt="" /> </div>
                                </div>
                                <div id="tab2222" class="tab-item popup-product-image">
                                  <div class="popup-product-single-image"> <img
                                      src="src/assets/images/shop/products-v6-img5.jpg"
                                      alt="" /> </div>
                                </div>
                                <div id="tab3333" class="tab-item popup-product-image">
                                  <div class="popup-product-single-image"> <img
                                      src="src/assets/images/shop/products-v6-img6.jpg"
                                      alt="" /> </div>
                                </div> <button class="prev"> <i
                                  class="flaticon-back"></i> </button> <button
                                  class="next"> <i class="flaticon-next"></i>
                              </button>
                              </div>
                            </div>
                          </div>
                        </div>
                        <div class="col-lg-6">
                          <div class="popup-right-content">
                            <h3>Brown Office Shoe</h3>
                            <div class="ratting"> <i class="flaticon-star"></i> <i
                                class="flaticon-star"></i> <i class="flaticon-star"></i>
                              <i class="flaticon-star"></i> <i class="flaticon-star"></i>
                              <span>(112)</span> </div>
                            <p class="text"> Hydrating Plumping Intense Shine Lip Colour
                            </p>
                            <div class="price">
                              <h2> $42 USD <del> $65 USD</del></h2>
                              <h6> In stuck</h6>
                            </div>
                            <div class="color-varient"> <a href="#0"
                                                           class="color-name pink"> <span>Pink</span> </a> <a
                                href="#0" class="color-name red"> <span>Red</span> </a>
                              <a href="#0" class="color-name yellow"><span>Yellow</span>
                              </a> <a href="#0" class="color-name blue"> <span>Blue</span>
                              </a> <a href="#0" class="color-name black">
                                <span>Black</span> </a> </div>
                            <div class="add-product">
                              <h6>Qty:</h6>
                              <div class="button-group">
                                <div class="qtySelector text-center"> <span
                                    class="decreaseQty"><i
                                    class="flaticon-minus"></i> </span> <input
                                    type="number" class="qtyValue" value="1" />
                                  <span class="increaseQty"> <i
                                      class="flaticon-plus"></i> </span> </div>
                                <button class="btn--primary "> Add to Cart </button>
                              </div>
                            </div>
                            <div class="payment-method"> <a href="#0"> <img
                                src="src/assets/images/payment_method/method_1.png"
                                alt=""> </a> <a href="#0"> <img
                                src="src/assets/images/payment_method/method_2.png"
                                alt=""> </a> <a href="#0"> <img
                                src="src/assets/images/payment_method/method_3.png"
                                alt=""> </a> <a href="#0"> <img
                                src="src/assets/images/payment_method/method_4.png"
                                alt=""> </a> </div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="products-three-single-content text-center"> <span>Men Shoes</span>
                    <h5><a href="shop-details-3.html">Outdoor Sports Shoes </a></h5>
                    <p>$159.00</p>
                  </div>
                </li>
                <!--End Products Six Single-->
                <!--Start Products Six Single-->
                <li class="products-three-single wow fadeInUp animated">
                  <div class="products-three-single-img img-bg">
                    <a href="shop-details-3.html" class="d-block">
                      <img src="src/assets/images/home-three/productss2-1.jpg" alt="" />
                      <div class="products-grid-one__badge-box"> <span
                          class="bg_black badge discount">-10%</span> </div></a> <a
                      href="cart.html" class="addcart btn--primary style2"> Add To Cart </a>
                    <div class="products-grid__usefull-links">
                      <ul>
                        <li><a href="wishlist.html"> <i class="flaticon-heart"> </i> <span>
                                                                wishlist</span> </a> </li>
                        <li><a href="compare.html"> <i
                            class="flaticon-left-and-right-arrows"></i> <span>
                                                                compare</span> </a> </li>
                        <li><a href="#popup4" class="popup_link"> <i
                            class="flaticon-visibility"></i> <span> quick
                                                                view</span>
                        </a> </li>
                      </ul>
                    </div>
                    <div id="popup4" class="product-gird__quick-view-popup mfp-hide">
                      <div class="container">
                        <div class="row justify-content-between align-items-center">
                          <div class="col-lg-6">
                            <div class="quick-view__left-content">
                              <div class="tabs">
                                <div class="popup-product-thumb-box">
                                  <ul>
                                    <li class="tab-nav popup-product-thumb"> <a
                                        href="#tab11111"> <img
                                        src="src/assets/images/shop/products-v6-img5.jpg"
                                        alt="" /> </a> </li>
                                    <li class="tab-nav popup-product-thumb "> <a
                                        href="#tab22222"> <img
                                        src="src/assets/images/shop/products-v6-img6.jpg"
                                        alt="" /> </a> </li>
                                    <li class="tab-nav popup-product-thumb "> <a
                                        href="#tab33333"> <img
                                        src="src/assets/images/shop/products-v6-img7.jpg"
                                        alt="" /> </a> </li>
                                  </ul>
                                </div>
                                <div class="popup-product-main-image-box">
                                  <div id="tab11111"
                                       class="tab-item popup-product-image">
                                    <div class="popup-product-single-image">
                                      <img src="src/assets/images/shop/products-v6-img5.jpg"
                                           alt="" /> </div>
                                  </div>
                                  <div id="tab22222"
                                       class="tab-item popup-product-image">
                                    <div class="popup-product-single-image">
                                      <img src="src/assets/images/shop/products-v6-img6.jpg"
                                           alt="" /> </div>
                                  </div>
                                  <div id="tab33333"
                                       class="tab-item popup-product-image">
                                    <div class="popup-product-single-image">
                                      <img src="src/assets/images/shop/products-v6-img7.jpg"
                                           alt="" /> </div>
                                  </div> <button class="prev"> <i
                                    class="flaticon-back"></i> </button>
                                  <button class="next"> <i
                                      class="flaticon-next"></i>
                                  </button>
                                </div>
                              </div>
                            </div>
                          </div>
                          <div class="col-lg-6">
                            <div class="popup-right-content">
                              <h3>Brown Office Shoe</h3>
                              <div class="ratting"> <i class="flaticon-star"></i> <i
                                  class="flaticon-star"></i> <i
                                  class="flaticon-star"></i> <i
                                  class="flaticon-star"></i> <i
                                  class="flaticon-star"></i> <span>(112)</span>
                              </div>
                              <p class="text"> Hydrating Plumping Intense Shine Lip
                                Colour
                              </p>
                              <div class="price">
                                <h2> $42 USD <del> $65 USD</del></h2>
                                <h6> In stuck</h6>
                              </div>
                              <div class="color-varient"> <a href="#0"
                                                             class="color-name pink"> <span>Pink</span> </a>
                                <a href="#0" class="color-name red">
                                  <span>Red</span>
                                </a> <a href="#0"
                                        class="color-name yellow"><span>Yellow</span>
                                </a>
                                <a href="#0" class="color-name blue">
                                  <span>Blue</span>
                                </a> <a href="#0" class="color-name black">
                                  <span>Black</span> </a> </div>
                              <div class="add-product">
                                <h6>Qty:</h6>
                                <div class="button-group">
                                  <div class="qtySelector text-center"> <span
                                      class="decreaseQty"><i
                                      class="flaticon-minus"></i> </span>
                                    <input type="number" class="qtyValue"
                                           value="1" /> <span class="increaseQty">
                                                                                <i class="flaticon-plus"></i> </span>
                                  </div> <button class="btn--primary "> Add to
                                  Cart
                                </button>
                                </div>
                              </div>
                              <div class="payment-method"> <a href="#0"> <img
                                  src="src/assets/images/payment_method/method_1.png"
                                  alt=""> </a> <a href="#0"> <img
                                  src="src/assets/images/payment_method/method_2.png"
                                  alt=""> </a> <a href="#0"> <img
                                  src="src/assets/images/payment_method/method_3.png"
                                  alt=""> </a> <a href="#0"> <img
                                  src="src/assets/images/payment_method/method_4.png"
                                  alt=""> </a> </div>
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="products-three-single-content text-center"> <span>Men Shoes</span>
                    <h5><a href="shop-details-3.html">High Quality Sneakers</a></h5>
                    <p>$159.00</p>
                  </div>
                </li>
                <!--End Products Six Single-->
              </ul>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!--End Products Six-->

    <!-- newsLetter-one style-two Start -->
    <section class="newsLetter-one border-0 style-two pt-60 pb-60 overflow-hidden">
      <div class="container">
        <div class="row">
          <div class="col-lg-4 col-md-6">
            <div class="newsLetter-one__content-box d-flex align-items-center justify-content-md-start justify-content-center wow fadeInUp animated"
                 data-wow-delay="0.1s">
              <div class="thumb"> <img src="src/assets/images/home-two/envalop.png" alt=""> </div>
              <h3 class="t36"> <span>Sign Up For </span> Newsletter </h3>
            </div>
          </div>
          <div class="col-lg-4 col-md-6">
            <div class="newsLetter-one__content-box d-flex align-items-center justify-content-md-start justify-content-center wow fadeInUp animated "
                 data-wow-delay="0.2s">
              <h6 class="text-md-start text-center"> Subscribe to ours weekly newsletter for all the
                latest updates </h6>
            </div>
          </div>
          <div class="col-lg-4 col-md-6">
            <div class="newsLetter-one__content-box three d-flex align-items-center justify-content-md-start justify-content-center wow fadeInUp animated"
                 data-wow-delay="0.3s">
              <form action="#0" class="form">
                <div class="newsLetter-one__subscribe-box"> <input type="email"
                                                                   placeholder="Email address" name="email"> <button type="submit"
                                                                                                                     class="subscrib-btn"> Subscribe </button> </div>
              </form>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- newsLetter-one style-two End -->

    <!-- core-features Start -->
    <section class="core-features pt-120 mb-60 overflow-hidden">
      <div class="container auto-container">
        <div class="row mt--30">
          <div class="col-xxl-3 col-md-6 mt-30 wow fadeInUp animated " data-wow-delay="0.2s">
            <div class="core-features__box d-flex ms-0"> <span class="one"></span> <span class="two"></span>
              <div class="icon"> <img src="src/assets/images/icon/f-icon-1.png" alt=""> </div>
              <div class="core-features__box-content"> <a href="login.html" class="d-block">
                <h4> Secure Payment </h4>
              </a>
                <p>Everybody different which the why give offer styles for every body.</p>
              </div>
            </div>
          </div>
          <div class="col-xxl-3 col-md-6 mt-30 wow fadeInUp animated " data-wow-delay="0.3s">
            <div class="core-features__box d-flex "> <span class="one"></span> <span class="two"></span>
              <div class="icon"> <img src="src/assets/images/icon/f-icon-2.png" alt=""> </div>
              <div class="core-features__box-content"> <a href="login.html" class="d-block">
                <h4> 27/7 Fast Delivery </h4>
              </a>
                <p>Everybody different which the why give offer styles for every body.</p>
              </div>
            </div>
          </div>
          <div class="col-xxl-3 col-md-6 mt-30 wow fadeInUp animated " data-wow-delay="0.4s">
            <div class="core-features__box d-flex "> <span class="one"></span> <span class="two"></span>
              <div class="icon"> <img src="src/assets/images/icon/f-icon-3.png" alt=""> </div>
              <div class="core-features__box-content"> <a href="login.html" class="d-block">
                <h4> Return & Refund </h4>
              </a>
                <p>Everybody different which the why give offer styles for every body.</p>
              </div>
            </div>
          </div>
          <div class="col-xxl-3 col-md-6 mt-30 wow fadeInUp animated " data-wow-delay="0.5s">
            <div class="core-features__box d-flex me-0"> <span class="one"></span> <span class="two"></span>
              <div class="icon"> <img src="src/assets/images/icon/f-icon-4.png" alt=""> </div>
              <div class="core-features__box-content"> <a href="login.html" class="d-block">
                <h4> Quality Support </h4>
              </a>
                <p>Everybody different which the why give offer styles for every body.</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>


  </main>
</template>

<script>
export default {
  name: "Index",
  mounted() {
    $(document).trigger('change')
  }
}
</script>

<style scoped>

</style>