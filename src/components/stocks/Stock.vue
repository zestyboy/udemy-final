<template>
  <div class="card"
       style="width: 18rem;">
    <div class="card-body">
      <h5 class="card-title">{{stockName}}
        <small>Price: ${{stockPrice}}</small>
      </h5>
      <p class="card-text">Some quick example text to build on the card title and make up the bulk of
        the card's content.</p>
      <div class="pull-left">
        <input type="number"
               class="form-control"
               placeholder="Quantity">
      </div>
      <a href="#"
         class="btn btn-success">Buy</a>
    </div>
  </div>
</template>

<script>
export default {
  data: function() {
    return {
      stockName: "test",
      stockPrice: 5
    };
  }
};
</script>

<style>
</style>

