<template>
  <div class="root">
    <div class="navbar">
      <div class="navbar-left">
        <div class="logo">
          <img src="../assets/logo.svg" alt="" />
        </div>
        <div class="nav-anchor">
          <a style="color: #5e81fe">Home</a>
          <a>Blog</a>
          <a>Features</a>
          <a>Pricing</a>
          <a>Documentation</a>
        </div>
      </div>

      <div class="navbar-right">
        <div class="navbar-icon">
          <img src="../assets/f.svg" alt="" />
        </div>
        <div class="navbar-icon">
          <img src="../assets/Vector.svg" alt="" />
        </div>
        <div class="navbar-icon">
          <img src="../assets/Vector (1).svg" alt="" />
        </div>
        <div class="navbar-icon">
          <img src="../assets/path14.svg" alt="" />
        </div>
        <button class="navbar-btn">Get started</button>
      </div>
    </div>

    <div class="hero">
      <div class="hero-image">
        <div class="heading">
          <h2 class="first-heading">Plan your life</h2>
          <h2 class="second-heading">
            Increase your <span style="font-weight: bold">productivity</span>
          </h2>
        </div>
        <div class="subtext">
          <p class="hero-subtext">
            Brute laoreet efficiendi id his, ea illum nonumes luptatum pro. Usu
            atqui laudem an, insolens gubergren similique est cu. Et vel modus
            congue vituperata.
          </p>
        </div>
        <div class="play-btn">
          <img src="../assets/play button.png" alt="" />
        </div>
      </div>
    </div>

    <div class="customers">
      <img src="../assets/cust-logos.png" alt="" />
    </div>

    <div class="illustration-container">
      <div class="grid-item1">
        <div class="item1-contents">
          <p class="above-heading">DESKTOP AND MOBILE APP</p>
          <p class="below-heading">
            Plan <span style="font-weight: 500">and</span> manage
          </p>
          <div class="illustration-text">
            <p>
              Brute laoreet efficiendi id his, ea illum nonumes luptatum pro.
              Usu atqui laudem an, insolens gubergren similique est cu. Et vel
              modus congue vituperata. Solum patrioque no sea. Mea ex malis
              mollis oporteat. Eum an expetenda consequat.
            </p>
          </div>
          <button class="illustration-btn1">View video</button>
          <button class="illustration-btn2">See features</button>
        </div>
      </div>
      <div class="grid-item2">
        <div class="item2-image">
          <img src="../assets/illustration.png" alt="" />
        </div>
      </div>
    </div>

    <!-- Features -->
    <section class="features">
      <div class="clouds-background">
        <div class="features-heading">
          <h2 class="first-header">About Us</h2>
          <h2 class="second-header">Read about our app</h2>
        </div>
        <div class="features-container">
          <div class="features-container-item">
            <div class="features-image">
              <img src="../assets/overview-img.svg" alt="" />
            </div>
            <p class="grid-topic">Overview</p>
            <p class="grid-text">
              Brute laoreet efficiendi id his, ea illum nonumes luptatum pro.
            </p>
          </div>
          <div class="features-container-item">
            <div class="features-image">
              <img src="../assets/overview-img.svg" alt="" />
            </div>
            <p class="grid-topic">Overview</p>
            <p class="grid-text">
              Brute laoreet efficiendi id his, ea illum nonumes luptatum pro.
            </p>
          </div>
          <div class="features-container-item">
            <div class="features-image">
              <img src="../assets/overview-img.svg" alt="" />
            </div>
            <p class="grid-topic">Overview</p>
            <p class="grid-text">
              Brute laoreet efficiendi id his, ea illum nonumes luptatum pro.
            </p>
          </div>
          <div class="features-container-item">
            <div class="features-image">
              <img src="../assets/overview-img.svg" alt="" />
            </div>
            <p class="grid-topic">Overview</p>
            <p class="grid-text">
              Brute laoreet efficiendi id his, ea illum nonumes luptatum pro.
            </p>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Quicksand:wght@300;400;600;700&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,700;1,400&display=swap");
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@300;400;600;700&display=swap');

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.navbar {
  height: 80px;
  display: flex;
  align-items: center;
  justify-content: center;
  background: #ffffff;
  padding: 23px 117px;
}
.navbar-left {
  display: flex;
  align-items: center;
  justify-content: center;
}
.navbar-right {
  display: flex;
  align-items: center;
  justify-content: center;
  margin-left: auto;
}

.nav-anchor {
  margin-left: 73px;
  font-family: Quicksand;
  font-weight: 500;
  font-size: 12px;
  color: #697ca6;
  text-shadow: 0px 0px 5px #e6e6e6;
}
a {
  margin-right: 42px;
}

.logo {
  width: 26px;
  height: 26px;
}

.logo .img {
  width: 100%;
  height: 100%;
}

.navbar-btn {
  width: 113px;
  height: 43px;
  background: #d2e1ff;
  border-radius: 2px;
  font-family: Quicksand;
  font-weight: bold;
  font-size: 13px;
  color: #3a79ff;
  border: none;
}

.navbar-icon {
  margin-right: 40px;
}

.hero-image {
  background-image: url(../assets/heroImage.png);
  height: 570px;
  width: 100%;
  background-repeat: no-repeat;
  background-size: 100% 100%;
}
.heading {
  text-align: center;
  padding-top: 90px;
}

.first-heading {
  font-family: Roboto;
  font-weight: 500;
  font-size: 10px;
  color: #3d4f9f;
  letter-spacing: 0.1em;
  text-transform: uppercase;
}
.second-heading {
  font-family: Quicksand;
  font-weight: 300;
  font-size: 48px;
  color: #3d4f9f;
  margin-top: 16px;
  margin-bottom: 28px;
}

.subtext {
  display: flex;
  align-items: center;
  justify-content: center;
}
.hero-subtext {
  font-family: Roboto;
  font-weight: normal;
  font-size: 15px;
  letter-spacing: 0.03em;
  color: #8d96bd;
  max-width: 500px;
  text-align: center;
}
.play-btn {
  width: 92px;
  height: 92px;
  margin: auto;
}
.play-btn img {
  width: 100%;
  height: 100%;
}

.customers {
  height: 145px;
  background: #ffffff;
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 58px 0;
}

.illustration-container {
  display: grid;
  grid-template-columns: 1fr 1fr;
  background: #f5f8ff;
}
.item1-contents {
  height: 352px;
  margin-left: 271px;
  margin-top: 300px;
}

.above-heading {
  font-family: Roboto;
  font-weight: 500;
  font-size: 10px;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  color: #3d4f9f;
}
.below-heading {
  font-family: Quicksand;
  font-weight: bold;
  font-size: 36px;
  color: #3d4f9f;
  margin: 27px 0;
}
.illustration-text {
  font-family: Roboto;
  font-weight: normal;
  font-size: 15px;
  letter-spacing: 0.03em;
  color: #8d96bd;
  margin-bottom: 47px;
}
.illustration-btn1 {
  width: 130.08px;
  height: 43px;
  background: #4c85ff;
  box-shadow: 0px 5px 15px rgba(188, 199, 255, 0.75);
  border-radius: 2px;
  border: none;
  font-family: Quicksand;
  font-weight: bold;
  font-size: 13px;
  color: #ffffff;
}
.illustration-btn2 {
  width: 130.08px;
  height: 43px;
  border: 1px solid #d1d1e4;
  box-sizing: border-box;
  border-radius: 2px;
  font-family: Quicksand;
  font-weight: bold;
  font-size: 13px;
  color: #8d96bd;
  background: #f5f8ff;
}

.item2-image {
  width: 900px;
  height: 700px;
  margin-top: 148px;
}
.item2-image img {
  width: 100%;
  height: 100%;
}
.features-heading {
  text-align: center;
}
.first-header {
  font-family: Roboto;
  font-weight: 500;
  font-size: 10px;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  color: #3D4F9F;
}
.second-header {
  font-family: Quicksand;
  font-weight: 500;
  font-size: 24px;
  color: #3D4F9F;
}
.features-container {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr 1fr;

}
.features-image {
  width: 69px;
  height: 69px;
}
.features image img {
  width: 100%;
  height: 100%;
}
.grid-topic {
  font-family: 'Open Sans';
  font-weight: bold;
  font-size: 14px;
}
.grid-text {
  font-family: Open Sans;
  font-weight: 600;
  font-size: 11px;
  color: #ADB3CB;
  max-width: 160px;
  text-align: center;
}


</style>
