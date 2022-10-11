<template>
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
  <div class="one">
    <h1
      class="one-title"
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
      class="one-firstPara"
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
      class="one-secondPara"
      v-motion
      :initial="{ opacity: 0, x: 100 }"
      :enter="{ opacity: 1, x: 0, scale: 1 }"
      :variants="{ custom: { scale: 2 } }"
      :delay="1000"
    >
      LONDON COLLECTION SEASON
    </h6>
    <h1
      class="one-thirdPara"
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
      class="one-forthPara"
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
    <div class="vertical-center">
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
  <div
    class="two"
    :initial="{ opacity: 0, y: 100 }"
    :enter="{ opacity: 1, y: 0, scale: 1 }"
    :variants="{ custom: { scale: 2 } }"
    :hovered="{ scale: 1.2 }"
    :delay="1000"
  >
    <h6
      class="two-firstPara"
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

#TemporaryStore {
  padding-top: 90px;
}

.vertical-center {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 150px;
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

.one-firstPara {
  color: #808086;
  padding-top: 20px;
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
}

.view {
  border: 1px solid;
  color: #cec5b7;
  width: 230px;
  height: 45px;
}

.two {
  width: 50%;
  height: 500px;
  float: left;
  font-family: Miller-Display_30501;
  text-align: left;
  padding: 50px;
}

.two-firstPara {
  color: #808086;
  padding-top: 117px;
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
  font-weight: bold;
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
