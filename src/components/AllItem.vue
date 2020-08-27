<template>
  <!-- product list -->
  <div class="container">
    <div class="row justify-content-center">
      <div class="col-12">
        <!-- quote -->
        <div class="quote text-center my-4">
          <i class="fas fa-quote -left mb-3 mb-md-0"></i>
          <span>123</span>
        </div>
        <!-- products -->
        <div class="row">
          <div class="3u">
            <section>
              <header>
                <h2>Feugiat Tempus</h2>
              </header>
              <p
                class="subtitle"
              >In posuere eleifend odio. Quisque semper augue mattis maecenas ligula.</p>
              <p>
                <a href="#">
                  <img src="images/pics13.jpg" alt />
                </a>
              </p>
              <a href="#" class="button">More</a>
            </section>
          </div>
          <div class="3u">
            <section>
              <header>
                <h2>Maecenas lectus</h2>
              </header>
              <p
                class="subtitle"
              >In posuere eleifend odio. Quisque semper augue mattis maecenas ligula.</p>
              <p>
                <a href="#">
                  <img src="images/pics14.jpg" alt />
                </a>
              </p>
              <a href="#" class="button">More</a>
            </section>
          </div>
          <div class="3u">
            <section>
              <header>
                <h2>Luctus lectus</h2>
              </header>
              <p
                class="subtitle"
              >In posuere eleifend odio. Quisque semper augue mattis maecenas ligula.</p>
              <p>
                <a href="#">
                  <img src="images/pics15.jpg" alt />
                </a>
              </p>
              <a href="#" class="button">More</a>
            </section>
          </div>
          <div class="3u">
            <section>
              <header>
                <h2>Posuere eleifend</h2>
              </header>
              <p
                class="subtitle"
              >In posuere eleifend odio. Quisque semper augue mattis maecenas ligula.</p>
              <p>
                <a href="#">
                  <img src="images/pics16.jpg" alt />
                </a>
              </p>
              <a href="#" class="button">More</a>
            </section>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
</script>

<style>
* {
  position: relative;
  box-sizing: border-box;
}
/*-----------------*/
/*quote
/*-----------------*/
.quote {
  font-family: "Oxygen Mono", monospace;
  line-height: 30px;
}
.quote span {
  display: inline-block;
}
.fa-quote-left {
  color: #c3c0c0;
  font-size: 60px;
  margin-right: 20px;
}
/*-----------------*/
/*shop
/*-----------------*/
.u-item-img {
  height: 180px;
  background-size: cover;
  background-position: center;
}
.u-item-cover {
  background-color: rgba(0, 0, 0, 0.5);
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  cursor: pointer;
  visibility: hidden;
  opacity: 0;
  transition: all 0.2s;
}
.u-item-btn {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  padding: 5px 10px;
  border: 1px solid;
  color: #fff;
  text-decoration: none;
}
.u-item-img:hover .u-item-cover {
  visibility: visible;
  opacity: 1;
}
.u-item-img:hover .u-item-btn {
  color: #fff;
  text-decoration: none;
}
</style>