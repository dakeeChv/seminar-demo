<template>
  <header id="header">
    <!-- id="header -->
    <div id="header-logo">
      <img
        id="header-img"
        src="https://image.freepik.com/free-vector/flat-world-book-day-background_23-2148094556.jpg"
        alt=""
      ></img>
      <!-- image id="header-img" -->
      <p>DK Book</p>
      <nav id="nav-bar">
        <!-- nav element id="nav-bar" -->
        <ul>
          <li>
            <!-- class="nav-link" -->
            <nuxt-link to="/">
              <i class="fab fa-envira" /><span> Welcome</span>
            </nuxt-link>
          </li>
          <li>
            <nuxt-link to="/#service">
              <i class="fas fa-feather-alt" /><span> Services</span>
            </nuxt-link>
          </li>
          <li>
            <nuxt-link to="/#bookstore">
              <i class="fas fa-book-open" /><span> Bookstore</span>
            </nuxt-link>
          </li>
          <li>
            <nuxt-link to="/about">
              <i class="fas fa-circle" /><span> About us</span>
            </nuxt-link>
          </li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<script>
export default {}
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Quicksand&display=swap");
@import url("https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.13.0/css/all.min.css");
/* Global */
* {
  box-sizing: border-box;
}
body {
  font-family: "Quicksand", sans-serif;
  margin: 0;
  padding: 0;
  background-color: whitesmoke;
}
.container {
    margin: 0 auto;
    width: 80%;
    padding: 1.5rem;
}
section {
    margin-bottom: 6rem;
}
/* Global */

/* header start*/
#header {
  position: sticky;
  top: 0;
  left: 0;
  right: 0;
  bottom: 10px;
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  align-items: center;
  flex-wrap: wrap;
  background-color: white;
  width: 100%;
  min-height: 70px;
  box-shadow: 0px 0px 10px 0px rgba(57, 56, 61, 0.205);
}

#header-logo { /* logo */
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
}
#header-logo p {
    margin: 0 0 0 10px;
    padding: 0;
    font-weight: 500;
    font-size: 30px;
}
#header-img {
  height: 60px;
  border-radius: 40%;
}

#nav-bar ul { /* navigative */
    list-style-type: none;
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    padding: 0;
    margin: 0;
}

#nav-bar li {
    padding: 0;
    border-radius: 0;
    text-align: center;
}

#nav-bar a {
    display: block;
    width: 150px;
    padding: 5px 0;
    text-decoration: none;
    font-size: 18px;
    font-weight: 500;
}

.nav-link {
    color: rgb(136, 0, 204);
}

.nav-link span {
    color: black !important;
}

.nav-link:hover {
    color: rgba(255, 204, 0, 0.8);
}

/* header end*/

/* Reponsive */
@media (max-width: 1000px) {
    .container {
        margin: 0 auto;
        width: 90%;
        padding: 1.5rem;
    }

    /* header */
    #nav-bar a {
        width: 100%;
        padding: 5px 15px;
    }
    /* header */

    /* welcome */
    #welcome-img {
        /* border: 1px solid; */
        width: 50%;
    }
    #welcome-content {
        /* border: 1px solid; */
        width: 50%;
    }
    #welcome-content p {
        font-size: 16px;
        text-align: justify;
    }
    /* welcome */

    /* service */
    .service-content {
        height: 80%;
        width: 60%;
        padding: 0 20px;
        text-align: justify;
        font-size: 16px;
    }
    .service-img {
        height: 80%;
        border-radius: 90%;
    }
    /* service */

    /* bookstore */
    #book {
        flex-wrap: wrap;
    }
    /* bookstore */

    /* footer */
    #footer {
        flex-direction: column;
        align-items: center;
    }
    /* footer */
}

@media (max-width: 745px) {
    /* welcome */
    #welcome {
        flex-direction: column;
        height: 100%;
    }
    #welcome-img {
        /* border: 1px solid; */
        width: 95%;
    }
    #welcome-content {
        /* border: 1px solid; */
        width: 95%;
    }
    /* welcome */

    /* bookstore */
    #video {
        max-height: 350px;
        width: 100%;
    }
    /* bookstore */

    /* service */
    .service-box {
        border: 1px solid;
        height: 270px;
        margin: 0;
    }
    .service-content {
        height: 90%;
        width: 50%;
        padding: 0 10px;
        text-align: justify;
        font-size: 16px;
    }
    .service-img {
        height: 50%;
        border-radius: 90%;
    }
    /* service */

    /* Form */
    #submit {
        margin-top: 10px;
    }
    /* Form */

    /* about */
    #about-content {
        width: 95%;
    }
    /* about */
}

@media (max-width: 545px) {
    .container {
        width: 100%;
        padding: 1rem 0;
    }
    /* header */
    #header {
        flex-direction: column;
    }
    #nav-bar ul {
        flex-direction: column;
    }
    /* header */

    /* form */
    #form label {
        display: block;
        margin-bottom: 5px;
    }
    /* form */

    /* service */
    .service-box {
        height: 350px;
    }
    .service-img {
        height: 30%;
        border-radius: 90%;
    }
    .service-content {
        height: 90%;
        width: 60%;
        padding: 0 10px;
        text-align: justify;
        font-size: 15px;
    }
    /* service */

    /* footer */
    #footer div ul {
        margin: 0;
        padding: 0;
    }
    #footer div li {
        padding: 5px 10px;
    }
    #footer div p {
        padding-left: 0;
    }
    #footer a {
        font-size: 16px;
    }
    #social i {
        font-size: 20px;
        padding: 0 5px;
    }
    /* footer */
}

@media (max-width: 350px) {
    #email {
        width: 90%;
    }
    .service-img {
        height: 20%;
    }
    .service-content {
        height: 100%;
        width: 70%;
        padding: 0 2px;
    }
}
</style>
