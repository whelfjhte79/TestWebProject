<template>
<div>
    <b-button v-b-modal.modal-xl variant="primary">xl modal</b-button>
    <b-modal id="modal-xl" size="xl" title="Extra Large Modal">Hello Extra Large Modal!</b-modal>
</div>
</template>
<!--
<template>

  <div>
    <b-carousel
      id="carousel-1"
      v-model="slide"
      :interval="4000"
      controls
      indicators
      background="#ababab"
      img-width="800"
      img-height="400"
      style="text-shadow: 1px 1px 2px #333;"
      @sliding-start="onSlideStart"
      @sliding-end="onSlideEnd"
    >

      <b-carousel-slide img-src="../assets/img04.png">
      <img src='../assets/img04.png'>
      </b-carousel-slide>


      <router-link to="/PortfolioList1"><b-carousel-slide img-src="https://picsum.photos/1024/480/?image=54">
        <h1>Hello world!</h1>
      </b-carousel-slide></router-link>


      <router-link to="/PortfolioList2"><b-carousel-slide img-src="./assets/logo.png">
          <img src='../assets/logo.png'>
      </b-carousel-slide></router-link>


    </b-carousel>
    







  </div>
</template>

<style>
.carousel-1{
    top: 100px;
    left: 100px;
    position: fixed;
}
</style>

-->