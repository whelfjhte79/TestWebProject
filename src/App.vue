<template>
<div>
     <h1> {{ aaa }} </h1>
    <div class="posit">
      <img src="./assets/ID.png" v-on:click= "testCk">
    </div>
    <div class="posit2">
      <img src="./assets/PW.png">
    </div>
    <div>
      <img src="./assets/Login.png">
    </div>
</div>
</template>

<script>
export default {
   name: "App",
   data() {
    return {
      aaa: 0,
    }
   },
   methods: {
        signIn () {
            this.$store.dispatch('signIn')
        },
        testCk(){
           this.aaa = this.aaa + 2;
        }
    }


}
</script>

<style scoped>
h3 {
    font-weight: 700;
}
button {
    background-color: #1dcaff;
    border: 1px solid  #1dcaff;
    
bottom: 0px;

}
div button:hover {
    background-color: #00aced;
    border: 1px solid  #00aced;
}
.posit {
  position: relative;
  left: 100px;
  top: 200px;
}
.posit2{
  position: relative;
  left: 300px;
  top: 200px;
}
</style>