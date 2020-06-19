<template>
  <div id="app">
    <img src="@/assets/mercedes-gla20-1.jpg">
    <div class="box-container">
      <div class="box-1"></div>
      <div class="box-1">
        jori me uchi na kod
      </div>
      <div class="box-1"></div>
      <div class="box-1"></div>
    </div>
    <div class="box-container">
      <div class="box-2"></div>
      <div class="box-2"></div>
      <div class="box-2">jorko</div>
      <div class="box-2"></div>
    </div>
    <div class="box-container">
      <div class="box-3"></div>
      <div class="box-3"></div>
      <div class="box-3">jorko</div>
      <div class="box-3"></div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'App',
}
</script>


<style lang="scss" scoped>
  .box-container {
    display: flex;
    justify-content: space-between;
    margin-bottom: 20px;
  }
  .box-1 {
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    height: 100px;
    width: 100px;
    background-color: red;
    border: 2px solid blue;
    border-radius: 20px;
    font-weight: bold;
  }
  .box-2 {
    display: flex;
    align-items: center;
    height: 100px;
    width: 100px;
    background-color: blue;
    border: 2px solid red;
    border-radius: 20px;
    font-weight: bold;
   
    }
    .box-3 {
    display: flex;
    align-items: center;
    height: 100px;
    width: 100px;
    background-color: green;
    border: 2px solid purple;
    border-radius: 20px;
    font-weight: bold;
    align-items: center;
    justify-content: center;
    }
    
</style>