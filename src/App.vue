<template>
  <div id="app">
    <Product></Product>
    <hr>
    <Cart></Cart>
    <hr>
    <Dislog></Dislog>
  </div>
</template>

<script>
  import Cart from "./components/Cart"
  import Product from "./components/Product"
  import Dislog from "./components/dialog/main"

  export default{
    components: {
      Cart,
      Product,
      Dislog
    }
  }
</script>
