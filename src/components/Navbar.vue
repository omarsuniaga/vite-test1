<script>
export default {
  name: "Navbar",
};
</script>

<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="/">
        <img
          src="https://getbootstrap.com/docs/5.0/assets/brand/bootstrap-logo.svg"
          alt=""
          width="30"
          height="24"
        />
      </a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarText"
        aria-controls="navbarText"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarText">
        <ul class="navbar-nav me-auto  mb-lg-0">
          <li class="nav-item">
            <router-link to="/" class="nav-link active">Home</router-link>
          </li>
          <li class="nav-item">
            <router-link to="/dashboard" class="nav-link">Products</router-link>
          </li>
          <li class="nav-item">
            <router-link to="/about" class="nav-link">About</router-link>
          </li>
        </ul>
        <div class="navbar-text">
          <router-link to="/login" class="nav-link">
            <span style="font-size: 30px; color: Dodgerblue">
              <i class="bi bi-arrow-bar-right"></i>
            </span>
          </router-link>
        </div>
      </div>
    </div>
  </nav>
</template>
