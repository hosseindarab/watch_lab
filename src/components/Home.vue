<template>
<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
  <div class="navbar-container">
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <a class="navbar-brand" href="#">WATCH/LAB</a>
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item">
            <a class="nav-link" id="nav-link" href="#">About us</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" id="nav-link" href="#">Brand</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" id="nav-link" href="#">Projects</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" id="nav-link" href="#">Magazine</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" id="nav-link" href="#">Press</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" id="nav-link" href="#">Contacts</a>
          </li>
        </ul>
        <input class="submit" type="search" />
      </div>
    </nav>
  </div>
  <div>
    <img id="HenryLondon" src="../assets/navBarImage.png" alt="Henry London" />
  </div>
  <div class="one responsive">
    <h1
      class="one-title responsive"
      v-motion
      :initial="{ opacity: 0, y: 100 }"
      :enter="{ opacity: 1, y: 0, scale: 1 }"
      :variants="{ custom: { scale: 2 } }"
      :hovered="{ scale: 0.8 }"
      :delay="1000"
    >
      History and <br />
      Patriarcal season
    </h1>
    <h6
      class="one-firstPara responsive"
      v-motion
      :initial="{ opacity: 0, x: 100 }"
      :enter="{ opacity: 1, x: 0, scale: 1 }"
      :variants="{ custom: { scale: 2 } }"
      :delay="1000"
    >
      On the other hand, we denounce with righteous <br />
      indignation and dislike men who are so beguiled and <br />
      demoralized by the charms of pleasure of the moment, <br />
      so blinded by desire
    </h6>
    <h6
      class="one-secondPara responsive"
      v-motion
      :initial="{ opacity: 0, x: 100 }"
      :enter="{ opacity: 1, x: 0, scale: 1 }"
      :variants="{ custom: { scale: 2 } }"
      :delay="1000"
    >
      LONDON COLLECTION SEASON
    </h6>
    <h1
      class="one-thirdPara responsive"
      v-motion
      :initial="{ opacity: 0, x: 100 }"
      :enter="{ opacity: 1, x: 0, scale: 1 }"
      :variants="{ custom: { scale: 2 } }"
      :hovered="{ scale: 1.2 }"
      :delay="1000"
    >
      Temporary Store
    </h1>
    <h6
      class="one-forthPara responsive"
      v-motion
      :initial="{ opacity: 0, x: 100 }"
      :enter="{ opacity: 1, x: 0, scale: 1 }"
      :variants="{ custom: { scale: 2 } }"
      :delay="1000"
    >
      On the other hand, we denounce with righteous <br />
      indignation and dislike men who are so beguiled and <br />
      demoralized by the charms of pleasure of the moment, <br />
      so blinded by desire
    </h6>
    <div class="vertical-center responsive">
      <button
        v-motion
        :initial="{ opacity: 0, x: 100 }"
        :enter="{ opacity: 1, x: 0, scale: 1 }"
        :variants="{ custom: { scale: 2 } }"
        :delay="1000"
        class="view"
      >
        View
      </button>
    </div>
    <div class="NewCollection responsive">
      <img
        v-motion
        :initial="{ opacity: 0, y: 100 }"
        :enter="{ opacity: 1, y: 0, scale: 1 }"
        :variants="{ custom: { scale: 2 } }"
        :hovered="{ scale: 1.2 }"
        :delay="1000"
        id="#NewCollection"
        src="../assets/NewCollection.png"
        alt="NewCollection"
      />
    </div>
  </div>
  <div
    class="two responsive"
    :initial="{ opacity: 0, y: 100 }"
    :enter="{ opacity: 1, y: 0, scale: 1 }"
    :variants="{ custom: { scale: 2 } }"
    :hovered="{ scale: 1.2 }"
    :delay="1000"
  >
    <h6
      class="two-firstPara responsive"
      v-motion
      :initial="{ opacity: 0, y: 100 }"
      :enter="{ opacity: 1, y: 0, scale: 1 }"
      :variants="{ custom: { scale: 2 } }"
      :delay="1000"
    >
      But I must explain to you how all this mistaken idea of denouncing <br />
      pleasure and praising pain was born and I will give you a complete <br />
      account of the system, and expound the actual teachings of the great <br />
      explorer of the truth, the master-builder of human happiness. No that <br />
      are extremely painful
    </h6>
    <div class="TemporaryStore responsive">
      <img
        v-motion
        :initial="{ opacity: 0, y: 100 }"
        :enter="{ opacity: 1, y: 0, scale: 1 }"
        :variants="{ custom: { scale: 2 } }"
        :hovered="{ scale: 1.2 }"
        :delay="1000"
        id="TemporaryStore"
        src="../assets/TemporaryStore.png"
        alt="TemporaryStore"
      />
    </div>
    <div class="three responsive">
      <h6
        class="three-title responsive"
        v-motion
        :initial="{ opacity: 0, y: 100 }"
        :enter="{ opacity: 1, y: 0, scale: 1 }"
        :variants="{ custom: { scale: 2 } }"
        :delay="2000"
      >
        LONDON COLLECTION SEASON
      </h6>
      <h1
        class="three-firstPara responsive"
        v-motion
        :initial="{ opacity: 0, x: 100 }"
        :enter="{ opacity: 1, x: 0, scale: 1 }"
        :variants="{ custom: { scale: 2 } }"
        :delay="2000"
        :hovered="{ scale: 1.2 }"
      >
        New Collection <br />
        Henry London
      </h1>
      <h6
        class="three-secondPara responsive"
        v-motion
        :initial="{ opacity: 0, x: 100 }"
        :enter="{ opacity: 1, x: 0, scale: 1 }"
        :variants="{ custom: { scale: 2 } }"
        :delay="2000"
      >
        On the other hand, we denounce with righteous <br />
        indignation and dislike men who are so beguiled and <br />
        demoralized by the charms of pleasure of the moment, <br />
        so blinded by desire
      </h6>
      <div class="vertical-center responsive">
        <button
          v-motion
          :initial="{ opacity: 0, x: 100 }"
          :enter="{ opacity: 1, x: 0, scale: 1 }"
          :variants="{ custom: { scale: 2 } }"
          :delay="1000"
          class="view"
        >
          View
        </button>
      </div>
    </div>
  </div>
  <div class="rowContainer responsive">
    <h1
      v-motion
      :initial="{ opacity: 0, y: 100 }"
      :enter="{ opacity: 1, y: 0, scale: 1 }"
      :variants="{ custom: { scale: 2 } }"
      :hovered="{ scale: 1.2 }"
      :delay="3000"
    >
      Press from <br />
      Watch Lab Studio
    </h1>
    <h6
      class="row-firstPara responsive"
      v-motion
      :initial="{ opacity: 0, y: 100 }"
      :enter="{ opacity: 1, y: 0, scale: 1 }"
      :variants="{ custom: { scale: 2 } }"
      :delay="3000"
    >
      On the other hand, we denounce with <br />
      righteous indignation and dislike men <br />
      who are so beguiled and demoralized<br />
      by the charms of pleasure of the<br />
      moment, so blinded by desire, that<br />
      they cannot foresee the pain trouble
    </h6>
    <div class="studio responsive">
      <img
        v-motion
        :initial="{ opacity: 0, y: 100 }"
        :enter="{ opacity: 1, y: 0, scale: 1 }"
        :variants="{ custom: { scale: 2 } }"
        :hovered="{ scale: 0.9 }"
        :delay="3000"
        id="TemporaryStore"
        src="../assets/studio.png"
        alt="studio"
      />
    </div>

    <h6
      class="detailtitle responsive"
      v-motion
      :initial="{ opacity: 0, y: 100 }"
      :enter="{ opacity: 1, y: 0, scale: 1 }"
      :variants="{ custom: { scale: 2 } }"
      :delay="3000"
    >
      PRESS <br />
      <p class="detailtitlegold responsive">18 SETTEMBRE 2015</p>
      <p class="detailtitlerow responsive">
        Most Important <br />
        Days on Watchlab
      </p>
    </h6>
  </div>
  <div
    class="row imagecollection responsive"
    v-motion
    :initial="{ opacity: 0, y: 100 }"
    :enter="{ opacity: 1, y: 0, scale: 1 }"
    :variants="{ custom: { scale: 2 } }"
    :delay="3500"
  >
    <div class="responsive">
      <img src="../assets/imagecollection.png" alt="imagecollection" />
    </div>
  </div>
  <div
    class="row getInTouch responsive"
    v-motion
    :initial="{ opacity: 0, y: 100 }"
    :enter="{ opacity: 1, y: 0, scale: 1 }"
    :variants="{ custom: { scale: 2 } }"
    :delay="3500"
  >
    <div class="responsive">
      <img src="../assets/getInTouch.png" alt="getInTouch" />
    </div>
  </div>
  <div class="row footerContainer responsive">
    <div class="column footerTitle">
      <h2 class="footerTitle">WATCH/LAB</h2>
      <p class="footerAddress">Watch/Lab Innovation brings success</p>
      <p class="footerAddress">Via Borgogna 5, Milan</p>
      <p class="footerAddress">Italy</p>
    </div>
    <div class="column">
      <p class="footerAddress linkPostionTop"><a class="links" href="#">About us</a></p>
      <p class="footerAddress"><a class="links" href="#">Brand</a></p>
      <p class="footerAddress"><a class="links" href="#">Projects</a></p>
      <p class="footerAddress linkPostionBottom">
        <a class="links" href="#">Magazine</a>
      </p>
    </div>
    <div class="column">
      <p class="footerAddress linkPostionTop"><a class="links" href="#">Press</a></p>
      <p class="footerAddress"><a class="links" href="#">Contacts</a></p>
      <p class="footerAddress"><a class="links" href="#">Privacy Polocy</a></p>
      <p class="footerAddress linkPostionBottom"><a class="links" href="#">Search</a></p>
    </div>
    <div class="column">
      <p class="footerAddress linkPostionTop">T. +39 392 9133937</p>
      <p class="footerAddress">M. info@watch-lab</p>
      <p class="footerAddress"><a class="socialLinks" href="#">FACEBOOK</a></p>
      <p class="footerAddress linkPostionBottom">
        <a class="socialLinks" href="#">INSTAGRAM</a>
      </p>
    </div>
  </div>
  <footer class="row footer">
    <div class="footerColumns footerInfo">Copyright Watch/Lab all rights reserved</div>
    <div class="footerColumns footerInfo">website by nssfactory</div>
  </footer>
</template>

<script>
export default {
  name: "HomePage",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
#HenryLondon {
  width: 100%;
}
#NewCollection {
  width: 100%;
}
.NewCollection {
  text-align: center;
  padding-top: 120px;
}

.TemporaryStore {
  text-align: left;
  padding-top: 40px;
}

#TemporaryStore {
  padding-top: 90px;
}

.studio {
  display: inline-block;
  vertical-align: top;
  padding-left: 50px;
}

.vertical-center {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 150px;
}

.rowContainer {
  width: 100%;
  height: 100%;
  float: left;
  font-family: Miller-Display_30501;
  text-align: center;
  padding: 50px;
  position: relative;
}

.detailtitle {
  vertical-align: bottom;
  padding-left: 30px;
  display: inline-block;
  font-family: Montserrat-Bold;
  font-weight: bold;
  font-size: small;
  text-align: left;
  color: black;
}

.detailtitlegold {
  font-family: Montserrat-Bold;
  font-size: small;
  color: #cec5b7;
  padding-top: 5px;
}

.detailtitlerow {
  display: inline-block;
  font-family: Miller-Display_30501;
  text-align: left;
  font-weight: 300;
  font-size: 30px;
  padding-top: 10px;
}

.imagecollection {
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  padding-top: 40px;
}

.getInTouch {
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  padding-top: 50px;
}

.footerContainer {
  background-color: #333333;
  width: 100%;
}

.footer {
  background-color: #303030;
  height: 80px;
  width: 100%;
  display: flex;
}

.footerColumns {
  float: left;
  width: 50%;
  align-self: center;
}

.footerInfo {
  font-family: Miller-Display_30501;
  color: #cdc4b5;
  font-size: small;
  text-align: center;
}

.footerTitle {
  padding-top: 60px;
  padding-bottom: 35px;
  color: white;
  font-family: Montserrat-Regular;
}

.footerAddress {
  font-family: Miller-Display_30501;
  font-size: small;
  text-align: center;
  color: #cdc4b5;
}

.links {
  color: #cdc4b5;
}
.socialLinks {
  color: #cdc4b5;
  font-family: Montserrat-Bold;
  font-size: smaller;
}

.linkPostionTop {
  margin-top: 200px;
}

.linkPostionBottom {
  margin-bottom: 200px;
}

.column {
  float: left;
  width: 25%;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

.row-firstPara {
  color: #808086;
  padding-top: 20px;
  font-family: MerriweatherRegular;
  display: inline-block;
}

.one {
  width: 50%;
  height: 100%;
  float: left;
  font-family: Miller-Display_30501;
  text-align: left;
  padding: 50px;
  position: relative;
}

.one-title {
  color: black;
  font-family: Miller-Display_30501;
  text-align: center;
  padding-top: 20px;
}

.one-firstPara {
  color: #808086;
  padding-top: 20px;
  font-family: MerriweatherRegular;
  text-align: center;
}

.one-secondPara {
  font-family: Montserrat-Bold;
  text-align: center;
  padding-top: 200px;
  font-weight: bold;
  font-size: smaller;
  color: black;
}

h1 {
  color: black;
}

.one-thirdPara {
  color: black;
  font-family: Miller-Display_30501;
  text-align: center;
  padding-top: 20px;
}

.one-forthPara {
  color: #808086;
  padding-top: 80px;
  text-align: center;
  font-family: MerriweatherRegular;
}

.view {
  border: 1px solid;
  color: #cec5b7;
  width: 230px;
  height: 45px;
  display: inline-block;
  cursor: pointer;
}

.two {
  width: 50%;
  height: 500px;
  float: left;
  font-family: Miller-Display_30501;
  text-align: center;
  padding: 50px;
}

.two-firstPara {
  color: #808086;
  padding-top: 117px;
  font-family: MerriweatherRegular;
  text-align: left;
}

.three {
  width: 50%;
  height: 100%;
  float: left;
  text-align: left;
  position: relative;
}

.three-title {
  font-family: Montserrat-Bold;
  text-align: center;
  padding-top: 100px;
  padding-bottom: 30px;
  font-weight: bold;
  font-size: smaller;
  color: black;
}

.three-firstPara {
  font-family: Miller-Display_30501;
  text-align: center;
}

.three-secondPara {
  color: #808086;
  padding-top: 50px;
  font-family: MerriweatherRegular;
  text-align: center;
}

#nav-link {
  color: black;
  padding-left: 20px;
  font-family: Montserrat-Regular;
}

.navbar-brand {
  background-color: #cec5b7;
  color: whitesmoke;
  font-family: Montserrat-Regular;
  font-size: 30px;
}

ul {
  list-style-type: none;
}

li {
  display: inline-block;
}

// a {
//   color: #42b983;
// }
input[type="search"] {
  border: none;
  background: transparent;
  margin: 0;
  padding: 7px 8px;
  font-size: 14px;
  color: inherit;
  border-bottom: 2px solid black;
  border-radius: inherit;
  background: transparent
    url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='16' height='16' class='bi bi-search' viewBox='0 0 16 16'%3E%3Cpath d='M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001c.03.04.062.078.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1.007 1.007 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0z'%3E%3C/path%3E%3C/svg%3E")
    no-repeat right;
  cursor: pointer;
  opacity: 0.7;
}

button[type="submit"]:hover {
  opacity: 1;
}

button[type="submit"]:focus,
input[type="search"]:focus {
  box-shadow: 0 0 3px 0 #cec5b7;
  border-color: #cec5b7;
  outline: none;
}
// input[type="search"]::placeholder {
//   color: #bbb;
// }
@font-face {
  font-family: MerriweatherRegular;
  src: url("../assets/font/Merriweather-Regular.ttf");
}

@font-face {
  font-family: Miller-Display_30501;
  src: url("../assets/font/Miller-Display_30501.ttf");
}

@font-face {
  font-family: Montserrat-Bold;
  src: url("../assets/font/Montserrat-Bold.ttf");
}

@font-face {
  font-family: Montserrat-Regular;
  src: url("../assets/font/Montserrat-Regular.ttf");
}
</style>
