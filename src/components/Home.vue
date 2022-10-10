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
    <h1>
      History and <br />
      Patriarcal season
    </h1>
    <h6 class="one-firstPara">
      On the other hand, we denounce with righteous <br />
      indignation and dislike men who are so beguiled and <br />
      demoralized by the charms of pleasure of the moment, <br />
      so blinded by desire
    </h6>
  </div>
  <div class="two">
    <h6 class="two-firstPara">
      But I must explain to you how all this mistaken idea of denouncing <br />
      pleasure and praising pain was born and I will give you a complete <br />
      account of the system, and expound the actual teachings of the great <br />
      explorer of the truth, the master-builder of human happiness. No that <br />
      are extremely painful
    </h6>
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

.one {
  width: 50%;
  height: 500px;
  float: left;
  font-family: Miller-Display_30501;
  text-align: left;
  padding: 50px;
}
.one-firstPara{
  color: #808086;
  padding-top: 20px;
}
h1{
  color: black;
}

.two {
  width: 50%;
  height: 500px;
  float: left;
  font-family: Miller-Display_30501;
  text-align: left;
  padding: 50px;
 
}
.two-firstPara{
  color: #808086;
  padding-top: 117px;
}

#nav-link {
  color: black;
  padding-left: 50px;
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
