<template>
  <header class="header">
    <div class="container">
      <div class="row align-items-center">
        <div class="col">
          <img
            class="profile-image img-fluid float-start rounded-circle"
            src="../../assets/images/profile.png"
            alt="profile image"
          />
          <div class="profile-content">
            <h1 class="name">James Lee</h1>
            <h2 class="desc">Web App Developer</h2>
            <ul class="social list-inline">
              <li class="list-inline-item">
                <a href="#"><i class="fab fa-twitter"></i></a>
              </li>
              <li class="list-inline-item">
                <a href="#"><i class="fab fa-linkedin-in"></i></a>
              </li>
              <li class="list-inline-item">
                <a href="#"><i class="fab fa-github-alt"></i></a>
              </li>
              <li class="list-inline-item">
                <a href="#"><i class="fab fa-stack-overflow"></i></a>
              </li>
              <li class="list-inline-item last-item">
                <a href="#"><i class="fab fa-codepen"></i></a>
              </li>
            </ul>
          </div>
          <!--//profile-->
        </div>
        <!--//col-->
        <div class="col-12 col-md-auto">
          <div class="dark-mode-switch d-flex">
            <div class="form-check form-switch mx-auto mx-md-0">
              <input
                type="checkbox"
                class="form-check-input me-2"
                id="darkSwitch"
              />
              <label class="custom-control-label" for="darkSwitch"
                >Dark Mode</label
              >
            </div>
          </div>
          <!--//dark-mode-switch-->
          <a
            class="btn btn-cta-primary"
            href="https://themes.3rdwavemedia.com/"
            target="_blank"
            ><i class="fas fa-paper-plane"></i> Contact Me</a
          >
        </div>
        <!--//col-->
      </div>
      <!--//row-->
    </div>
    <!--//container-->
  </header>
</template>

<script>
export default {};
</script>

<style></style>
