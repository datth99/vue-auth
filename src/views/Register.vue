<template>
  <div class="container">
      <div class="row">
        <div class="col-md-3"></div>
        <div class="col-md-6">
          <form @submit="handleSubmit">
            <div class="card mt-5">
                <h5 class="card-header">Register</h5>
                <div class="card-body">
                <form>
                    <div class="form-group">
                    <label for="exampleInputEmail1">Name</label>
                    <input type="text" class="form-control">
                    </div>
                    <div class="form-group">
                    <label for="exampleInputEmail1">Email</label>
                    <input type="email" class="form-control">
                    </div>
                    <div class="form-group">
                    <label for="exampleInputPassword1">Password</label>
                    <input type="password" class="form-control">
                    </div>
                    <div class="form-group">
                    <label for="exampleInputPassword1">Confirm Password</label>
                    <input type="password" class="form-control">
                    </div>
                    <button type="button" class="btn btn-primary btn-block">Register</button>
                </form>
                </div>
            </div>
          </form>
        </div>
        <div class="col-md-3"></div>
      </div>
    </div>
</template>

<script>
export default {
    name: 'Register',
    methods: {
        handleSubmit(e){
            e.preventDefault();
            console.log('Submit');
        }
    },
}
</script>

<style>

</style>