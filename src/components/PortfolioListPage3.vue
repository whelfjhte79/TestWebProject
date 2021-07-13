<template>
    <div>
    <div>
        
        <b-button v-b-modal.ASDF class="ABC">
        <img src="../assets/img06.png" class="test">
        </b-button>
        <b-modal id="ASDF" title="Login">
           TEST
        </b-modal>

   
        <img src="../assets/img06.png" class="test1">
        <img src="../assets/img06.png" class="test2">
        <img src="../assets/img06.png" class="test3">
        <img src="../assets/img06.png" class="test4">
        <img src="../assets/img06.png" class="test5">
        <img src="../assets/img06.png" class="test6">
        <img src="../assets/img06.png" class="test7">
        <img src="../assets/Left.jpg" class="Left">
        <img src="../assets/Right.jpg" class="Right">
    </div>

   <div>
    <b-button v-b-toggle.sidebar-variant class="MenuButton">Menu bar</b-button>
    <b-sidebar id="sidebar-variant" title="Sidebar" bg-variant="dark" text-variant="light" shadow>
      <div class="px-3 py-2">
        <p>
          Crasasd
        </p>
        <b-img src="https://picsum.photos/500/500/?image=54" fluid thumbnail></b-img>
        <b-text class = "Lee-link">이상민 포트폴리오</b-text>
      </div>
       <div class="px-3 py-3">
        <b-img src="https://picsum.photos/500/500/?image=54" fluid thumbnail></b-img>
        <b-text class = "Lee-link">정아연 포트폴리오</b-text>
      </div>
   
       <div class="px-3 py-4">
        <b-img src="https://picsum.photos/500/500/?image=54" fluid thumbnail></b-img>
        <b-text class = "Lee-link">조하늘 포트폴리오</b-text>
      </div>
      <div class="px-3 py-5">
        <b-img src="https://picsum.photos/500/500/?image=54" fluid thumbnail></b-img>
        <b-text class = "Lee-link">박지호 포트폴리오</b-text>
      </div>
    </b-sidebar>
  </div>
</div>
</template>

<script> 
import Content from './Content.vue';
export default {
  components: { Content }, 
   name: "App", 
   data() { 
      return { 
         is_modal_viewed: false, 
      };
   },
}; 
</script>





<style>
.test{
    width: 290px;
    height: 400px;
    top: 150px;
    left: 320px;
    position:fixed;
}
.test1{
    width: 290px;
    height: 400px;
    top: 150px;
    left: 640px;
    position: fixed;
}
.test2{
    width: 290px;
    height: 400px;
    top: 150px;
    left: 960px;
    position: fixed;
}
.test3{
    width: 290px;
    height: 400px;
    top: 150px;
    left: 1280px;
    position: fixed;
}
.test4{
    width: 290px;
    height: 400px;
    top: 600px;
    left: 320px;
    position: fixed;
}
.test5{
    width: 290px;
    height: 400px;
    top: 600px;
    left: 640px;
    position: fixed;
}
.test6{
    width: 290px;
    height: 400px;
    top: 600px;
    left: 960px;
    position: fixed;
}
.test7{
    width: 290px;
    height: 400px;
    top: 600px;
    left: 1280px;
    position: fixed;
}
.Left{
    width: 100px;
    height: 200px;
    top: 480px;
    left: 100px;
    position: fixed;
}
.Right{
    width: 100px;
    height: 200px;
    top: 480px;
    left: 1625px;
    position: fixed;

}
.MenuButton{
    top: 0px;
    left:0px;
    position: fixed;
}
</style>

