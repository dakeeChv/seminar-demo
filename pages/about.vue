<template>
  <div>
    <Header />
    <section id="about-us">
      <div id="about-title">
        <h1>
          <i class="fas fa-circle" />
          <span>About us</span>
        </h1>
      </div>
      <div id="about-content">
        <p>
          Lorem, ipsum dolor sit amet consectetur adipisicing elit. Debitis
          nam voluptas, distinctio suscipit ratione alias soluta eveniet iure
          iste. Eius necessitatibus error deleniti minus, eveniet fuga!
          Suscipit veritatis minus commodi!
        </p>
        <p>
          <strong>Email:</strong> example@mail.com
        </p>
        <p>
          <strong>Call:</strong> +1111 7777-9999-8888
        </p>
      </div>
    </section>
    <Footer />
  </div>
</template>

<script>
import Header from '@/components/header'
import Footer from '@/components/footer'
export default {
  components: {
    Header,
    Footer
  }
}
</script>

<style>
/* section about-us */
#about-us {
  display: flex;
  flex-direction: column;
  align-items: center;
}
#about-title i {
  color: green;
}
#about-title span {
  font-size: 35px;
}
#about-content {
  text-indent: 30px;
  text-align: justify;
  width: 60%;
}
/* section about-us */
</style>
