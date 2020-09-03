<template>
  <footer
    id="footer"
    class="container"
  >
    <div id="social">
      <h3><strong>Social :</strong></h3>
      <i class="fab fa-instagram fa-2x" />
      <i class="fab fa-facebook-square fa-2x" />
      <i class="fab fa-twitter fa-2x" />
      <i class="fab fa-youtube fa-2x" />
      <i class="fab fa-whatsapp fa-2x" />
    </div>
    <div>
      <ul>
        <li><a href="#">Privacy</a></li>
        <li><a href="#">Terms</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
      <p><strong>Coding By Daky Chanthavong</strong></p>
    </div>
  </footer>
</template>

<script>
export default {

}
</script>

<style>
/* footer */
#footer {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    flex-wrap: wrap;
    margin-bottom: 2rem;
    background-color: white;
}

#footer div ul {
    display: flex;
    align-items: center;
    list-style-type: none;
}

#footer div li {
    padding: 10px 20px;
}
#footer div p {
    padding-left: 60px;
}
#footer a {
    text-decoration: none;
    color: black;
    font-size: 18px;
    font-weight: 700;
}
#social {
    display: flex;
    align-items: center;
}
#social i {
    padding: 10px 20px;
    color: blueviolet;
}

#social i:hover {
    color: rgba(255, 191, 0, 1);
}
/* footer */
</style>
