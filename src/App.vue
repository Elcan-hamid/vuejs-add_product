<template>
  <div class="container">
    <h1 class="text-center">Ürün Ekleme Uygulaması</h1>
    <hr>
    <NewProduct />
    <br><br>
    <Progress />
    <br><br>
    <Products />
  </div>


</template>

<script>
  import NewProduct from "./components/NewProduct";
  import Products from "./components/Products";
  import Progress from "./components/Progress";
  export default {
    components: {
      NewProduct,
      Products,
      Progress
    }
  }
</script>

<style>
  body {
    background-color: aliceblue;
    padding-top: 20px;
    padding-bottom: 20px;
  }

  .card{
    margin-right: 5px;
    margin-bottom: 5px;
  }

  .card:last-child{
    margin-right: 0px;
  }

  .col-md-2{
    max-width: 15.666667%!important;
  }

  .product-container{
    margin-left: 15px;
  }

</style>

