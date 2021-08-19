<template>
  <div>
   <!-- header section strats -->
  <header class="header_section">
    <div class="container">
      <nav class="navbar navbar-expand-lg custom_nav-container ">
        <a class="navbar-brand" href="#">
          <div class="logo_box">
            <img src="/static/images/logo.png" alt="" />
          </div>
        </a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>

        <!-- <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav ml-auto mr-2">
            <li class="nav-item active">
              <a class="nav-link" href="index.html">Home <span class="sr-only">(current)</span></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="about.html">About Us </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="service.html">Services</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="blog.html">Blog</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="contact.html">Contact us</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Login </a>
            </li>
          </ul>
          <form class="form-inline my-2 my-lg-0">
            <input class="form-control nav_search-input mr-sm-2 d-none" type="search" placeholder="Search"
              aria-label="Search" value="" />
            <button class="btn  my-2 my-sm-0 nav_search-btn" type="submit"></button>
          </form>
        </div> -->
      </nav>
    </div>
  </header>
  <!-- end header section -->

  <!-- story section -->

  <section class="layout_padding story_section">
    <div class="container-fluid">
      <div class="row">
        <div class=" col-md-6">
          <div>
            <img class="img-fluid" src="/static/images/security.png" alt="" />
          </div>
        </div>
        <div class=" col-md-6">
          <div class="story_detail">
            <h3>
              产品
            </h3>
            <h2>
              《巅峰王者》
            </h2>
            <p>
              这是一款经典的游戏，一个神话般的王者穿越在危险的跑道上。积攥更多的钻石、元宝，用来提升自身强度。注意躲避路上的怪物哦，不然会被吃掉的。
            </p>
            <div class="story_detail-btn">
              <a href="">
                <span>
                  详情
                </span>
                <img src="/static/images/arrow-black.png" alt="" class="ml-2" />
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- end story section -->

  <!-- security section -->

  <section class="security_section layout_padding">
    <h3>
      产品展示

    </h3>
    <h2>

    </h2>
    <div class="security_container">
      <div class="carousel-wrap">
        <div class="owl-carousel">
          <div class="item">
            <div class="security_img-box i-box-1">
              <a href=""> 更多</a>
            </div>
          </div>
          <div class="item">
            <div class="security_img-box i-box-2">
              <a href=""> 更多</a>
            </div>
          </div>
          <div class="item">
            <div class="security_img-box i-box-3">
              <a href=""> 更多</a>
            </div>
          </div>

        </div>
      </div>
    </div>
    <div class="security_btn">
      <a href="">
        <span>
          更多
        </span>
        <img src="/static/images/arrow-black.png" alt="" class="ml-2" />
      </a>
    </div>
  </section>
  <!-- end security section -->

  <!-- info section -->
  <section class="info_section layout_padding">
    <div class="container">
      <div class="row">
        <div class=" col-md-4 info_detail">

        </div>
        <div class=" col-md-4 address_container">
          <div>
            <h3>
              联系我们:
            </h3>
            <div class="address_link-container">

              <a href="">
                <img src="/static/images/mail.png" alt="">
                <span>
                  Email: xietom96@gmail.com
                </span>
              </a>
            </div>
          </div>
        </div>
        <div class=" col-md-4 news_container">

        </div>
      </div>
    </div>
  </section>

  <!-- end info section -->

  <!-- footer section -->
  <section class="container-fluid footer_section">
    <p>Copyright &copy; 2020.Harth Technology.</p>
  </section>
  <!-- footer section -->
  </div>
</template>

<script>
// import '../../static/js/jquery-3.4.1.min.js'

import '../../static/js/owl.carousel.min.js'
import { initOwl } from '../../static/js/index.js'

export default {
  name: 'HelloWorld',
  data () {
    return {

    }
  },
  mounted: () => {
    initOwl()
  }
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
