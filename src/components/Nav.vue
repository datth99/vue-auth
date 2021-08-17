<template>
    <nav class="navbar navbar-light bg-light">
      <div class="container">
         <h5>Home</h5>
        <div>
          <router-link to="/login"><span class="btn btn-danger">Login</span></router-link> 
          <router-link to="/register"><span class="ml-2 btn btn-primary">Register</span></router-link>
        </div>
      </div>
    </nav>
</template>

<script>
export default {
    name: 'Nav'
}
</script>