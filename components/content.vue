<template>
  <main id="main" class="container">
    <section id="welcome">
      <!-- Welcome -->
      <img
        id="welcome-img"
        src="https://image.freepik.com/free-vector/flat-design-world-book-day-concept_23-2148477157.jpg"
        alt=""
      >
      <div id="welcome-content">
        <h1><i class="fab fa-envira fa-2x" /><span> Welcome</span></h1>
        <p>
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Laudantium
          ipsa praesentium maxime dolores iste, illum quisquam! Iure eius
          doloremque esse consequuntur illo rerum recusandae, molestiae sequi
          dolores error quaerat nemo?
        </p>
      </div>
    </section>
    <section id="form-email">
      <!-- Form-Email -->
      <p><strong>Take news and notification from us by email</strong></p>
      <form
        id="form"
        action="https://www.freecodecamp.com/email-submit"
      >
        <label
          for="email"
        >Put My Email :</label>
        <input
          id="email"
          name="email"
          type="email"
          placeholder="Enter your email address"
          required
        >
        <input
          id="submit"
          type="submit"
          value="Get"
        >
      </form>
    </section>
    <section id="service">
      <!-- Services -->
      <div id="service-title">
        <h1>
          <i class="fas fa-feather-alt fa-2x" /><span> Services</span>
        </h1>
      </div>
      <div id="service-list">
        <div class="service-box">
          <p class="service-content">
            <strong>DK Book :</strong> will offer a wide range of book and
            magazine selections. This includes just about every conceivable
            category including fiction, non-fiction, business, science,
            children's, hobbies, collecting, and other types of books.
          </p>
          <img
            class="service-img"
            src="https://image.freepik.com/free-vector/flat-university-concept_23-2148172426.jpg"
            alt=""
          >
        </div>
        <div class="service-box">
          <img
            class="service-img"
            src="https://image.freepik.com/free-vector/distance-course-isometric_98292-7151.jpg"
            alt=""
          >
          <p class="service-content">
            <strong>In Store Hold :</strong> Shop now and pay later! Similar
            to a Reservation, you select your textbooks in the store and we
            will hold them for you!, Lorem ipsum dolor sit amet consectetur
            adipisicing elit. Deleniti maxime corrupti placeat, autem commodi
            recusandae molestiae nihil tempore ad ducimus soluta voluptates
            impedit facere culpa aperiam cum eaque! Ab, iusto!
          </p>
        </div>
        <div class="service-box">
          <p class="service-content">
            <strong>Bookstore Gift Cards :</strong> We have reloadable gift
            cards which can be purchased in store or on line. This is a great
            way to extend support to a loved one or make it more convenient
            for them to shop without you!
          </p>
          <img
            class="service-img"
            src="https://image.freepik.com/free-vector/friends-celebrating-birthday-packing-gifts_74855-4793.jpg"
            alt=""
          >
        </div>
        <div class="service-box">
          <img
            class="service-img"
            src="https://image.freepik.com/free-vector/isometric-online-education-illustration_1284-32915.jpg"
            alt=""
          >
          <p class="service-content">
            <strong>DK-store App :</strong> we have application service for
            customer which is member. Lorem ipsum, dolor sit amet consectetur
            adipisicing elit. Ad reiciendis, veritatis alias, earum sapiente
            voluptate quibusdam id tenetur explicabo quis, veniam nulla rem
            ipsa labore? Assumenda minus corporis repudiandae dicta.
          </p>
        </div>
      </div>
    </section>
    <section id="bookstore">
      <div id="bookstore-title">
        <h1><i class="fas fa-book-open" /><span> Bookstore</span></h1>
      </div>
      <div id="bookstore-video">
        <iframe
          id="video"
          src="https://www.youtube.com/embed/SKVcQnyEIT8"
          frameborder="0"
          allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"
          allowfullscreen
        />
        <p>Video: Product in Our Bookstore</p>
      </div>
      <div id="bookstore-product">
        <div id="menu-product">
          <ul>
            <li class="active">
              New
            </li>
            <li>All</li>
            <li>fiction</li>
            <li>non-fiction</li>
            <li>science</li>
            <li>education</li>
            <li>other</li>
          </ul>
        </div>
        <div id="book">
          <div class="book-box">
            <a href="#">
              <img
                class="book-img"
                src="https://image.isu.pub/191014094408-c5b72f6bbad3dc9036157fab540f76a6/jpg/page_1.jpg"
                alt=""
              ></a>
          </div>
          <div class="book-box">
            <a href="#">
              <img
                class="book-img"
                src="https://images.tandf.co.uk/common/jackets/amazon/978113836/9781138362635.jpg"
                alt=""
              ></a>
          </div>
          <div class="book-box">
            <a href="#">
              <img
                class="book-img"
                src="https://www.accessola.org/web/images/OLA/Forest/BookCovers/silverbirchfiction/2020/Royal-Guide-to-Monster-Slaying.jpg"
                alt=""
              ></a>
          </div>
        </div>
      </div>
    </section>
  </main>
</template>

<script>
export default {

}
</script>

<style>
/* section welcome */
#welcome {
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    align-items: center;
    height: 400px;
}
#welcome-img {
    /* border: 1px solid; */
    width: 45%;
    border-radius: 20px 0 20px 0;
}
#welcome-content {
    /* border: 1px solid; */
    width: 50%;
    padding: 0 20px;
}
#welcome-content i {
    color: rgba(180, 24, 180, 0.8);
}
#welcome-content h1 {
    text-align: center;
}
#welcome-content span {
    font-size: 35px;
}
#welcome-content p {
    font-size: 18px;
    text-align: justify;
}
/* section welcome */

/* section form-email */
#form-email {
    font-size: 18px;
    text-align: center;
}
#email {
    border: 1px solid gray;
    border-radius: 5px;
    padding: 10px;
    width: 300px;
    font-size: 16px;
}
#submit {
    background-color: rgba(255, 191, 0, 1);
    border: 1px solid rgb(255, 191, 0);
    border-radius: 5px;
    padding: 10px 20px;
    font-size: 16px;
}
#submit:hover {
    background-color: whitesmoke;
}
/* section form-email */

/* section service */
#service {
    display: flex;
    flex-direction: column;
    align-items: center;
}
#service-title i {
    color: green;
}
#service-title span {
    font-size: 35px;
}
#service-list {
    display: flex;
    flex-direction: column;
}
.service-box {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    height: 180px;
    margin: 20px 0;
}

.service-content {
    height: 95%;
    width: 60%;
    padding: 0 40px;
    text-align: justify;
    font-size: 18px;
}
.service-img {
    height: 95%;
    border-radius: 90%;
}
/* section service */

/* section Bookstore */
#bookstore {
    text-align: center;
}
#bookstore i {
    color: green;
}
#bookstore span {
    font-size: 35px;
}
#video {
    height: 350px;
    width: 600px;
}
#menu-product ul {
    margin-top: 50px;
    list-style-type: none;
    display: flex;
    flex-direction: row;
    justify-content: flex-start;
    flex-wrap: wrap;
    width: 100%;
    background-color:rgba(255, 255, 51, 0.2);
}
#menu-product li {
    font-weight: 700;
    padding: 10px 20px;
}

#menu-product .active {
    background-color:rgb(153, 102, 51);
    color: whitesmoke;
}

#menu-product li:hover {
    background-color: rgb(255, 204, 153);
}
#book {
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    padding: 10px 40px;
}
.book-box {
    height: 400px;
}
.book-img {
    height: 80%;
    width: auto;
}
.book-img:hover {
    box-shadow: 0px 10px 30px rgba(57, 56, 61, 0.205);
    transform: scale(1.08);
    transition: transform .4s ease;
}

/* section Bookstore */
</style>
