<template>
    <footer class="footer">
        <div class="container">
            <div class="row row-grid align-items-center my-md">
                <div class="col-lg-6 custom-lg">
                    <h3 class="text-primary font-weight-light mb-2">Thank you for posting jobs.</h3>
                    <h4 class="mb-0 font-weight-light">Let's get in touch on any of these platforms.</h4>
                </div>
                <div class="col-lg-6 text-lg-center btn-wrapper">
                    <a target="_blank" href="https://twitter.com/marat_galiev"
                       class="btn btn-neutral btn-icon-only btn-twitter btn-round btn-lg" data-toggle="tooltip"
                       data-original-title="Follow us">
                        <i class="fa fa-twitter"></i>
                    </a>
                    <a target="_blank" href="https://github.com/maratgaliev/rustjobs.cc"
                       class="btn btn-neutral btn-icon-only btn-github btn-round btn-lg" data-toggle="tooltip"
                       data-original-title="Star on Github">
                        <i class="fa fa-github"></i>
                    </a>
                </div>
            </div>
            <hr>
            <div class="row align-items-center justify-content-md-between">
                <div class="col-md-6 col-6">
                    <div class="copyright">
                        &copy; {{year}}
                        <a href="https://rustjobs.cc" target="_blank" rel="noopener">RustJobs.cc</a>
                    </div>
                </div>
                <div class="col-md-6 col-6">
                    <ul class="nav nav-footer justify-content-end">
                        <li class="nav-item">
                          <router-link class="nav-link" to="about">
                            About
                          </router-link>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </footer>
</template>
<script>
export default {
  data() {
    return {
      year: new Date().getFullYear()
    }
  }
};
</script>
<style>
</style>
