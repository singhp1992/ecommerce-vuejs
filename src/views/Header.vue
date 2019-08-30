// header here
// add search option - bootstrap
<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <router-link to="/" class="navbar-brand" href="#">Store</router-link>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav mr-auto">
      <li class="nav-item active">
        <router-link to="/" class="nav-link" href="#">Home<span class="sr-only">(current)</span></router-link>
      </li>
      <li class="nav-item active">
        <router-link to="/about" class="nav-link" href="#">About<span class="sr-only">(current)</span></router-link>
      </li>
      <li class="nav-item active">
        <router-link to="/products" class="nav-link" href="#">Products<span class="sr-only">(current)</span></router-link>
      </li>
      <li class="nav-item dropdown">
        <router-link to="/products" class="nav-link active" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
          Products
        </router-link>
      </li>
    </ul>
    <form class="form-inline my-2 my-lg-0">
      <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
      <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
    </form>
  </div>
</nav>
</template>Î

<script> 
export default {
  name: "header",
  components: {
    
  }
};
</script>

<style>
.navbar {
  padding: 1rem 1rem;
}
</style>
