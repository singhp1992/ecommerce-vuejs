// header here
// add search option - bootstrap
<template>
  <div id="height"> 
    <nav class="height navbar navbar-expand-lg navbar-dark bg-dark">
    <router-link to="/" id="larger" class="navbar-brand">Store</router-link>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item active">
          <router-link to="/" class="nav-link">Home<span class="sr-only">(current)</span></router-link>
        </li>
        <li class="nav-item active">
          <router-link to="/about" class="nav-link">About<span class="sr-only">(current)</span></router-link>
        </li>
        <li class="nav-item active">
          <router-link to="/products" class="nav-link">Products<span class="sr-only">(current)</span></router-link>
        </li>
      </ul>
        <form id="search-right" class="form-inline my-2 my-lg-0">
          <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
          <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
        </form>
      </div>
    </nav>
  </div>
</template>Î

<script> 
export default {
  name: "header",
  components: {
    
  }
};
</script>

<style>
.height {
  height: 75px;
}

#height:hover {
  color: rgb(140, 140, 250);
}

#larger {
  font-size: xx-large;
  padding-right: 50px;
  padding-left: 10px;
}

#search-right {
  padding-right: 10px;
}
</style>
