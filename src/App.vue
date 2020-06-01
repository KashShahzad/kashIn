<template>
  <div id="app">
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>-->
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <router-link class="navbar-brand nav-link active" to="/"
        >Kashif Shahzad</router-link
      >
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarNavAltMarkup"
        aria-controls="navbarNavAltMarkup"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
        <div class="navbar-nav">
          <a class="nav-item nav-link" href="/Notes">Notes</a>
          <a class="nav-item nav-link" href="/Blog">Blog</a>
          <a class="nav-item nav-link" href="/Project">Project</a>
          <a class="nav-item nav-link" href="/OSS">OSS</a>
          <a class="nav-item nav-link" href="#">TheOutliers</a>
        </div>
      </div>
    </nav>
    <router-view />
    <!-- Footer -->
    <footer class="page-footer font-small blue pt-4 abc">
      <!-- Footer Links -->
      <div class="container-fluid text-center text-md-left">
        <!-- Grid row -->
        <div class="row">
          <!-- Grid column -->
          <div class="col-md-6 mt-md-0 mt-3 ab">
            <!-- Content -->
            <h5 class="text-uppercase">About this platform</h5>
            <p class="cd">
              Welcome to my website! I'm @RkashShahzad, a software developer
              from Pakistan and i love Javascript and Python.
            </p>
          </div>
          <!-- Grid column -->
          <hr class="clearfix w-100 d-md-none pb-3" />

          <!-- Grid column -->
          <div class="col-md-3 mb-md-0 mb-3">
            <!-- Links -->
            <h5 class="text-uppercase">Social endpoints</h5>

            <ul class="list-unstyled">
              <li>
                <a href="#!">View source on Github</a>
              </li>
              <li>
                <a href="#!">Follow me on Twitter</a>
              </li>
              <li>
                <a href="#!">Follow me on LinkedIn</a>
              </li>
              <li>
                <a href="#!">See my stories on Instagram</a>
              </li>
            </ul>
          </div>
          <!-- Grid column -->
        </div>
        <!-- Grid row -->
      </div>
      <!-- Footer Links -->
    </footer>
    <!-- Footer -->
  </div>
</template>

<style lang="scss" scoped>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

.ab {
  text-align: center;
}
.cd {
  padding-right: 20%;
  padding-left: 20%;
}

.abc {
  position: fixed;
  left: 0;
  bottom: 0;
  width: 100%;
  background-color: white;
  text-align: center;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
