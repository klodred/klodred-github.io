<template>
  <div class="d-flex">

    <div class="container mt-5">
      <div class="row">
        <div class="col-sm-4 col-xs-4 col-md-5 col-lg-5">
          <div class="input-group mb-4">
            <div class="input-group-prepend">
              <button class="btn btn-dark btn-sm" id="minus-btn"><i
                  class="fa fa-minus"></i></button>
            </div>
            <input style="text-align: center" type="number" id="qty_input"
                   class="form-control form-control-sm" value="1" min="1">
            <div class="input-group-prepend">
              <button class="btn btn-dark btn-sm" id="plus-btn"><i
                  class="fa fa-plus"></i></button>
            </div>
          </div>
        </div>
      </div>

    </div>

  </div>
</template>

<script>
export default {
  name: "Counter"
}
</script>

<style scoped>

</style>