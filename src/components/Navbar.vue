<template>
  <nav class="navbar navbar-expand-lg custom-navbar">
    <div class="container-fluid justify-content-center">
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-center" id="navbarNav">
        <ul class="navbar-nav align-items-center">
          <router-link to="/"><li class="nav-item"><a class="nav-link">Home</a></li></router-link>
          <router-link to="/about"><li class="nav-item"><a class="nav-link">About</a></li></router-link>
          <a class="navbar-brand" href="#">Plants by Keeks</a>
          <router-link to="/products"><li class="nav-item"><a class="nav-link">Products</a></li></router-link>
          <router-link to="/contact"><li class="nav-item"><a class="nav-link">Contact US</a></li></router-link>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'NavbarComp'
}
</script>

<style>
.custom-navbar {
  background-color: black;
}

.navbar-nav {
  display: flex;
  justify-content: center;
  width: 100%;
}

.nav-link {
  color: white !important;
  padding: 0 15px;
}

.navbar-brand {
  color: pink !important;
  font-weight: bold;
  padding: 0 15px;
}

.navbar-toggler {
  border-color: white;
}

.navbar-toggler-icon {
  background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 30 30'%3E%3Cpath stroke='rgba%28255, 255, 255, 0.5%29' stroke-width='2' d='M4 7h22M4 15h22M4 23h22'/%3E%3C/svg%3E");
}
</style>
