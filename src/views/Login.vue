<template>
  <div class="container">
      <div class="row">
        <div class="col-md-3"></div>
        <div class="col-md-6">
          <div class="card mt-5">
            <h5 class="card-header">Login</h5>
            <div class="card-body">
              <form @submit="handleSubmit">
                <div class="form-group">
                  <label for="exampleInputEmail1">Email</label>
                  <input type="email" class="form-control">
                </div>
                <div class="form-group">
                  <label for="exampleInputPassword1">Password</label>
                  <input type="password" class="form-control">
                </div>
                <div class="form-group form-check">
                  <input type="checkbox" class="form-check-input">
                  <label class="form-check-label">Check me out</label>
                </div>
                <button type="button" class="btn btn-primary btn-block">Login</button>
              </form>
            </div>
          </div>
        </div>
        <div class="col-md-3"></div>
      </div>
    </div>
</template>

<script>
export default {
    name: 'Login',
    methods: {
        handleSubmit(e){
            e.preventDefault();
            console.log('Submited!!');
        }
    },
}
</script>

<style>

</style>