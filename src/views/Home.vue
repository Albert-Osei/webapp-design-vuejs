<template>
  <div class="home">
    <nav class="navbar">
      <div class="navbar-left">
        <div class="logo">
          <img src="../assets/logo.svg" alt="" />
        </div>
        <input type="checkbox" id="nav-check">
        <div class="nav-anchor">
          <a style="color: #5e81fe">Home</a>
          <a>Blog</a>
          <a>Features</a>
          <a>Pricing</a>
          <a>Documentation</a>
        </div>
      </div>

      <label for="nav-check">
        <div class="hamburger-menu">
          <img src="../assets/newham.png" alt="menu">
        </div>
      </label>

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
    </nav>

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
            <p class="grid-topic">Files</p>
            <p class="grid-text">
              No vim nulla vitae intellegat. Ei enim error ius, solet atomorum
              conceptam ex has.
            </p>
          </div>
          <div class="features-container-item">
            <div class="features-image">
              <img src="../assets/overview-img.svg" alt="" />
            </div>
            <p class="grid-topic">Meeting Chats</p>
            <p class="grid-text">
              Vim ne tacimates neglegentur. Erat diceret omittam at est.
            </p>
          </div>
          <div class="features-container-item">
            <div class="features-image">
              <img src="../assets/overview-img.svg" alt="" />
            </div>
            <p class="grid-topic">Save events</p>
            <p class="grid-text">
              Nisl idque mel ea, nominati voluptatum.
            </p>
          </div>
        </div>
      </div>
      <div class="features-btn">
        <button class="features-btn1">Read more</button>
        <p class="btn-break">OR</p>
        <button class="features-btn2">Get started</button>
      </div>
    </section>

    <!-- Stats Section -->
    <section class="stats">
      <div class="stats-container">
        <div class="stats-item1">
          <div class="stats-image1">
            <img src="../assets/Group.svg" alt="" />
          </div>
          <p class="numeric">89%</p>
          <p class="stats-text">
            Customers who have increased their productivity
          </p>
        </div>
        <div class="stats-item2">
          <div class="stats-image2">
            <img src="../assets/Group 4.svg" alt="" />
          </div>
          <p class="numeric">3123</p>
          <p class="stats-text">Users who have used our application</p>
        </div>
      </div>
    </section>

    <!-- Blog Section -->
    <section class="blog">
      <div class="blog-heading">
        <h2>Our resources</h2>
        <h3>Start reading our blog</h3>
      </div>

      <carousel
        :per-page="1"
        :navigate-to="someLocalProperty"
        :mouse-drag="false"
      >
        <slide>
          <div class="main-blog">
            <div class="blog-container">
              <div class="blog-item1">
                <img src="../assets/blog-image.png" />
              </div>
              <div class="blog-item2">
                <h2 class="item2-heading">How to start planning</h2>
                <h3 class="item2-text">
                  Quidam vocibus eum ne, erat consectetuer voluptatibus ut nam.
                  Eu usu vidit tractatos, vero tractatos ius an, in mel diceret
                  persecuti. Natum petentium principes mei ea. Tota everti
                  periculis vis ei, quas tibique pro at, eos ut decore ...
                </h3>
                <div class="btn-all">
                  <button class="item2-btn1">Read more</button>
                  <button class="item2-btn2">Add to your bookmarks</button>
                </div>
              </div>
            </div>
          </div>
        </slide>
        <slide>
          <div class="main-blog">
            <div class="blog-container">
              <div class="blog-item1">
                <img src="../assets/blog-image.png" />
              </div>
              <div class="blog-item2">
                <h2 class="item2-heading">How to start planning</h2>
                <h3 class="item2-text">
                  Quidam vocibus eum ne, erat consectetuer voluptatibus ut nam.
                  Eu usu vidit tractatos, vero tractatos ius an, in mel diceret
                  persecuti. Natum petentium principes mei ea. Tota everti
                  periculis vis ei, quas tibique pro at, eos ut decore ...
                </h3>
                <div class="btn-all">
                  <button class="item2-btn1">Read more</button>
                  <button class="item2-btn2">Add to your bookmarks</button>
                </div>
              </div>
            </div>
          </div>
        </slide>
        <slide>
          <div class="main-blog">
            <div class="blog-container">
              <div class="blog-item1">
                <img src="../assets/blog-image.png" />
              </div>
              <div class="blog-item2">
                <h2 class="item2-heading">How to start planning</h2>
                <h3 class="item2-text">
                  Quidam vocibus eum ne, erat consectetuer voluptatibus ut nam.
                  Eu usu vidit tractatos, vero tractatos ius an, in mel diceret
                  persecuti. Natum petentium principes mei ea. Tota everti
                  periculis vis ei, quas tibique pro at, eos ut decore ...
                </h3>
                <div class="btn-all">
                  <button class="item2-btn1">Read more</button>
                  <button class="item2-btn2">Add to your bookmarks</button>
                </div>
              </div>
            </div>
          </div>
        </slide>
      </carousel>
    </section>

    <!-- Quotes section -->
    <section class="quotes">
      <div class="quotes-container">
        <div class="quotes-item1">
          <h3 class="quotes-first-header">Testimonials</h3>
          <h2 class="quotes-second-header">Customer's quotes</h2>
          <p class="quotes-text">
            Brute laoreet efficiendi id his, ea illum nonumes luptatum pro. Usu
            atqui laudem an.
          </p>
        </div>
        <div class="quotes-item2">
          <carousel
            :per-page="1"
            :navigate-to="someLocalProperty"
            :mouse-drag="false"
          >
            <slide>
              <div class="quotes-image">
                <img src="../assets/Group 72.png" alt="" />
              </div>
            </slide>
            <slide>
              <div class="quotes-image">
                <img src="../assets/Group 72.png" alt="" />
              </div>
            </slide>
            <slide>
              <div class="quotes-image">
                <img src="../assets/Group 72.png" alt="" />
              </div>
            </slide>
          </carousel>
        </div>
      </div>
    </section>

    <!-- FAQ Section -->
    <section class="faq">
      <div class="faq-heading">
        <h3 class="faq-first-header">Customer help</h3>
        <h2 class="faq-second-header">Frequently asked questions</h2>
      </div>
      <div class="question-block">
        <div class="question">
          <img src="../assets/Down-arrow.svg" alt="" />
          <p class="question-text">Reque insolens in vel?</p>
        </div>
        <div class="line-break"></div>
      </div>
      <div class="question-block">
        <div class="question">
          <img src="../assets/Down-arrow.svg" alt="" />
          <p class="question-text">
            Vis rebum error graecis ea, id sit postea accusamus?
          </p>
        </div>
        <div class="line-break"></div>
      </div>
      <div class="question-block">
        <div class="new-question">
          <div class="new-question-block">
            <img src="../assets/Up-arrow.svg" alt="" />
            <p class="question-text-title">Lorem repudiandae ne nec?</p>
          </div>
          <div class="question-text-content">
            <p>
              Quidam vocibus eum ne, erat consectetuer voluptatibus ut nam. Eu
              usu vidit tractatos, vero tractatos ius an, in mel diceret
              persecuti.
            </p>
            <button class="question-btn">Go to documentation</button>
          </div>
        </div>
        <div class="line-break"></div>
      </div>
      <div class="question-block">
        <div class="question">
          <img src="../assets/Down-arrow.svg" alt="" />
          <p class="question-text">
            Ad dicit numquam vel. Et eos iudico feugait percipitur?
          </p>
        </div>
        <div class="line-break"></div>
      </div>
      <div class="question-block">
        <div class="question">
          <img src="../assets/Down-arrow.svg" alt="" />
          <p class="question-text">
            Sea no dico percipitur. Fierent constituam definitiones id eum?
          </p>
        </div>
        <div class="line-break"></div>
      </div>
    </section>

    <!-- Get Started Section -->
    <section class="getStarted">
      <div class="getStarted-heading">
        <h3 class="getStarted-first-header">Plan your life</h3>
        <h2 class="getStarted-second-header">Get <span>started</span> now</h2>
      </div>
      <p class="getStarted-text">
        Brute laoreet efficiendi id his, ea illum nonumes luptatum pro. Usu
        atqui laudem an, insolens gubergren similique est cu. Et vel modus
        congue vituperata.
      </p>
      <div class="getStarted-allBtn">
        <button class="allBtn-one">View pricing</button>
        <button class="allBtn-two">Read documentation</button>
      </div>
    </section>

    <!-- Newsletter Section -->
    <section class="newsletter">
      <div class="newsletter-container">
        <div class="newsletter-item1">
          <h3>Sign up for newsletter</h3>
          <p>
            Cu qui soleat partiendo urbanitas. Eum aperiri indoctum eu, homero
            alterum.
          </p>
        </div>
        <div class="newsletter-item2">
          <input
            class="input-field"
            type="text"
            name="email"
            placeholder="Email address"
          />
          <button class="newsletter-btn">Save me</button>
        </div>
      </div>
    </section>
    <Footer />
  </div>
</template>

<script>
import Footer from "@/components/Footer.vue";

export default {
  name: "Home",
  components: {
    Footer,
  },
};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Quicksand:wght@300;400;600;700&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,700;1,400&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Open+Sans:wght@300;400;600;700&display=swap");

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
.customers img {
  width: 100%;
  height: 100%;
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
  max-width: 900px;
  height: 700px;
  margin-top: 148px;
}
.item2-image img {
  width: 100%;
  height: 100%;
}
.features-heading {
  text-align: center;
  padding-top: 80px;
}
.first-header {
  font-family: Roboto;
  font-weight: 500;
  font-size: 10px;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  color: #3d4f9f;
}
.second-header {
  font-family: Quicksand;
  font-weight: 500;
  font-size: 24px;
  color: #3d4f9f;
  margin: 20px 0 90px;
}
.features-container {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr 1fr;
  grid-column-gap: 70px;
  width: 761px;
  height: 254px;
  margin: auto;
}
.features-image {
  width: 69px;
  height: 69px;
  margin: auto;
}
.features-image img {
  width: 100%;
  height: 100%;
}
.grid-topic {
  font-family: "Open Sans";
  font-weight: bold;
  font-size: 14px;
  text-align: center;
  margin: 33px 0 25px;
}
.grid-text {
  font-family: Open Sans;
  font-weight: 600;
  font-size: 11px;
  color: #adb3cb;
  max-width: 160px;
  text-align: center;
  margin: auto;
}
.clouds-background {
  background-image: url(../assets/clouds.png);
  min-height: 573px;
  width: 100%;
  background-repeat: no-repeat;
  background-size: 100% 100%;
  margin: auto;
}
.features-btn {
  display: flex;
  align-items: center;
  justify-content: center;
  margin-bottom: 172px;
}
.features-btn1 {
  width: 113px;
  height: 43px;
  background: #ffd7d7;
  border-radius: 2px;
  font-family: Quicksand;
  font-weight: bold;
  font-size: 13px;
  color: #d43f3f;
  border: none;
}
.features-btn2 {
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
.btn-break {
  font-family: Open Sans;
  font-weight: 600;
  font-size: 11px;
  color: #adb3cb;
  padding: 0 48px;
}

.stats-container {
  display: grid;
  grid-template-columns: 1fr 1fr;
  height: 343px;
}
.stats-item1 {
  background: linear-gradient(229.32deg, #6888ff 12.77%, #5e80ff 73.11%);
}
.stats-image1 {
  width: 65px;
  height: 66px;
  margin: 66px 0px 24px 800px;
}
.stats-image1 img {
  width: 100%;
  height: 100%;
}
.stats-image2 {
  width: 65px;
  height: 66px;
  margin: 66px 0px 24px 45px;
}
.stats-image2 img {
  width: 100%;
  height: 100%;
}
.stats-item2 {
  background: linear-gradient(101.48deg, #e9efff 41.56%, #e0e9ff 81.53%);
}
.stats-item1 .numeric {
  font-family: Quicksand;
  font-weight: normal;
  font-size: 48px;
  letter-spacing: 0.03em;
  color: #ffffff;
  margin: 24px 0px 24px 770px;
}
.stats-item2 .numeric {
  font-family: Quicksand;
  font-weight: normal;
  font-size: 48px;
  letter-spacing: 0.03em;
  color: #5e80ff;
  margin: 24px 0px 24px 43px;
}
.stats-item1 .stats-text {
  font-family: Quicksand;
  font-weight: 500;
  font-size: 18px;
  letter-spacing: 0.03em;
  color: #ffffff;
  text-align: right;
  max-width: 260px;
  margin-left: 600px;
}
.stats-item2 .stats-text {
  font-family: Quicksand;
  font-weight: 500;
  font-size: 18px;
  letter-spacing: 0.03em;
  color: #5e80ff;
  max-width: 260px;
  margin-left: 43px;
}

.blog-heading {
  text-align: center;
}
.blog-heading h2 {
  font-family: Roboto;
  font-weight: 500;
  font-size: 10px;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  color: #3d4f9f;
  margin: 104px 0 20px;
}
.blog-heading h3 {
  font-family: Quicksand;
  font-weight: 500;
  font-size: 24px;
  color: #3d4f9f;
  margin-bottom: 92px;
}
.blog-container {
  display: grid;
  grid-template-columns: 1fr 1fr;
  background: #ffffff;
  border: 1px solid #d8e3fe;
  box-sizing: border-box;
  box-shadow: 0px 15px 50px #eff4ff;
  width: 958px;
  margin: auto;
}
.blog-item1 {
  width: 480px;
  height: 357px;
  margin-top: 11px;
}
.blog-item1 img {
  width: 100%;
  height: 100%;
}
.item2-heading {
  font-family: Quicksand;
  font-weight: normal;
  font-size: 36px;
  color: #3d4f9f;
  margin: 63px 0 32px;
}
.item2-text {
  font-family: Roboto;
  font-weight: normal;
  font-size: 14px;
  letter-spacing: 0.03em;
  color: #8d96bd;
  max-width: 407px;
}
.item2-btn1 {
  width: 113px;
  height: 43px;
  background: #d2e1ff;
  border-radius: 2px;
  font-family: Quicksand;
  font-weight: bold;
  font-size: 13px;
  color: #3a79ff;
  border: none;
  margin-right: 8px;
}
.btn-all {
  display: flex;
  align-items: center;
  margin-top: 31px;
}
.item2-btn2 {
  width: 211px;
  height: 43px;
  font-family: Quicksand;
  font-weight: bold;
  font-size: 13px;
  color: #a6b6da;
  background: #ffffff;
  border-radius: 2px;
  border: none;
}

.quotes-container {
  display: grid;
  grid-template-columns: 1fr 1fr;
  min-height: 479px;
  background: linear-gradient(180deg, #eaf0ff 0%, #f6f9ff 100%);
}
.quotes-first-header {
  font-family: Roboto;
  font-weight: 500;
  font-size: 10px;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  color: #3d4f9f;
}
.quotes-second-header {
  font-family: Quicksand;
  font-weight: 500;
  font-size: 36px;
  color: #3d4f9f;
  padding: 31px 0 14px;
}
.quotes-text {
  font-family: Open Sans;
  font-weight: 600;
  font-size: 12px;
  letter-spacing: 0.03em;
  color: #a4abc8;
  max-width: 320px;
}
.quotes-image {
  width: 423px;
  margin: auto;
}
.quotes-image img {
  width: 100%;
  height: 100%;
}
.quotes-item2 {
  margin: 109px 0px 0px 132px;
}
.quotes-item1 {
  margin: auto;
}

.faq {
  background: #ffffff;
  padding: 230px 345px 120px 345px;
}
.faq-heading {
  text-align: center;
}
.faq-first-header {
  font-family: Roboto;
  font-weight: 500;
  font-size: 10px;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  color: #3d4f9f;
}
.faq-second-header {
  font-family: Quicksand;
  font-weight: 500;
  font-size: 24px;
  color: #3d4f9f;
  margin: 20px 0px 68px;
}
.question-text {
  font-family: Quicksand;
  font-weight: 500;
  font-size: 15px;
  letter-spacing: 0.03em;
  color: #8e96b7;
  margin-left: 24px;
}
.question {
  display: flex;
  align-items: center;
  justify-content: left;
  margin: 0px 0px 15px 300px;
}
.line-break {
  border: 0.5px solid #d8e3fe;
  max-width: 653px;
  margin: auto;
}
.question-block {
  margin-bottom: 17px;
}
.question-text-title {
  font-family: Quicksand;
  font-weight: bold;
  font-size: 15px;
  letter-spacing: 0.03em;
  color: #495274;
  margin-left: 24px;
}
.question-text-content {
  font-family: Roboto;
  font-weight: normal;
  font-size: 14px;
  letter-spacing: 0.03em;
  color: #8d96bd;
  margin: 16px 0px 53px 60px;
  display: flex;
}
.question-text-content > p {
  max-width: 310px;
  margin-right: 62px;
}
.question-btn {
  width: 195px;
  height: 43px;
  background: #e8ecf4;
  border-radius: 2px;
  font-family: Quicksand;
  font-weight: 500;
  font-size: 13px;
  color: #7382a3;
  border: none;
}
.new-question {
  align-items: center;
  justify-content: left;
  margin: 0px 0px 15px 300px;
}
.new-question-block {
  display: flex;
}

.getStarted {
  background-image: url(../assets/get.png);
  height: 447px;
  width: 100%;
  background-repeat: no-repeat;
  background-size: 100% 100%;
}
.getStarted-heading {
  text-align: center;
}
.getStarted-first-header {
  font-family: Roboto;
  font-weight: 500;
  font-size: 10px;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  color: #ffffff;
  padding: 91px 0px 16px 0px;
}
.getStarted-second-header {
  font-family: Quicksand;
  font-weight: 300;
  font-size: 48px;
  color: #ffffff;
}
.getStarted-second-header span {
  font-weight: bold;
}
.getStarted-text {
  font-family: Roboto;
  font-weight: normal;
  font-size: 15px;
  letter-spacing: 0.03em;
  color: #ffffff;
  text-align: center;
  max-width: 712px;
  margin: auto;
  padding: 28px 0px 80px 0px;
}
.getStarted-allBtn {
  text-align: center;
}
.allBtn-one {
  width: 130.08px;
  height: 43px;
  background: #ffffff;
  box-shadow: 0px 5px 15px #6480e8;
  border-radius: 2px;
  font-family: Quicksand;
  font-weight: bold;
  font-size: 13px;
  color: #565f82;
  border: none;
}
.allBtn-two {
  width: 155px;
  height: 43px;
  background: linear-gradient(229.32deg, #6888ff 12.77%, #5e80ff 73.11%);
  font-family: Quicksand;
  font-weight: 500;
  font-size: 13px;
  color: #c7d3ff;
  border: 1px solid #a0b4ff;
  box-sizing: border-box;
  border-radius: 2px;
}

.newsletter-container {
  display: grid;
  grid-template-columns: 1fr 1fr;
  padding: 118px 267px 119px 267px;
  border-bottom: 1px solid #d8e3fe;
}

.newsletter-item1 h3 {
  font-family: Quicksand;
  font-weight: bold;
  font-size: 18px;
  color: #3d4f9f;
}
.newsletter-item1 p {
  font-family: Roboto;
  font-weight: normal;
  font-size: 14px;
  letter-spacing: 0.03em;
  color: #8d96bd;
  max-width: 330px;
  margin-top: 18px;
}
.input-field {
  width: 279px;
  height: 59px;
  background: #efeff7;
  border-radius: 5px;
  font-family: Quicksand;
  font-weight: bold;
  font-size: 13px;
  color: #7a85ad;
  padding: 21px 0px 21px 23px;
  border: none;
  margin-right: 15px;
}
.newsletter-btn {
  width: 184px;
  height: 59px;
  background: #4d6ce1;
  box-shadow: 0px 5px 15px rgba(116, 104, 255, 0.2);
  border-radius: 5px;
  font-family: Quicksand;
  font-style: normal;
  font-weight: bold;
  color: #ffffff;
  border: none;
}

.hamburger-menu {
    display: none;
    width: 50px;
    height: 50px;
}
.hamburger-menu img {
    width: 100%;
    height: 100%;
}

#nav-check {
  display: none;
}


@media screen and (max-width: 768px) {

  .illustration-container {
    grid-template-columns: 1fr;
    padding-left: 10px;
    padding-right: 10px;
    margin: 0px;
  }
  .item1-contents {
    margin: 0;
  }

  .features-container {
    grid-template-columns: 1fr;
    padding-left: 10px;
    padding-right: 10px;
    width: 100%;
    margin: 0;
  }
  .features-container-item {
    margin: 0;
  }
  .clouds-background {
    height: 70em;
  }

  .stats-container {
    grid-template-columns: 1fr;
    padding-left: 10px;
    padding-right: 10px;
  }
  .stats-item1 .stats-text {
    text-align: left;
    margin: 0;
  }
  .stats-item2 .stats-text {
    margin: 0;
  }
  .stats-item1 .numeric {
    margin: 0;
  }
  .stats-item2 .numeric {
    margin: 0;
  }
  .stats-image1 {
    margin: 0;
  }
  .stats-image2 {
    margin: 0;
  }

  .blog-container {
    grid-template-columns: 1fr;
    padding-left: 10px;
    padding-right: 10px;
  }

  .quotes-container {
    grid-template-columns: 1fr;
    padding-left: 10px;
    padding-right: 10px;
    margin: 0;
  }
  .quotes-item1 {
    padding: 0;
    margin: 0;
  }
  .quotes-item2 {
    margin: 0;
  }
  /* .quotes-image {
    margin: 0;
  } */
  .quotes-second-header {
    padding: 0;
  }

  .faq {
    padding: 0;
  }
  .question {
    margin-left: 0;
  }
  .new-question {
    margin: 0;
  }

  .newsletter-container {
    grid-template-columns: 1fr;
    padding-left: 10px;
    padding-right: 10px;
  }

  .hamburger-menu {
    display: block;
  }

  .navbar-btn, .logo {
    display: none;
  }
  
  .nav-anchor {
    display: none;
  }

  nav #nav-check:checked ~ .nav-anchor {
    display: block;
    position: absolute;
    width: 100%;
    top: 64px;
    background-color: rgba(0, 0, 0, 0.70);
    right: 0;
    text-align: center;
    border-radius: 3px;
  }

  .nav-anchor a {
    display: block;
    text-align: center;
    margin: 0;
    padding: 25px;
    color: #fff;
  }



}






</style>
