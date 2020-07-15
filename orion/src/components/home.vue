<template>
  <div class="container">
    <nav class="header">
      <div><img src="../assets/img/orion-logo.svg" alt=""></div>
      <div><img src="../assets/img/menu.svg" alt=""></div>
    </nav>

    <section class="hero">
      <div><h6 style="color: #fff;">Welcome to Orion 5</h6></div>
      <div><h1><span style="color: #7842F0;">no</span> gravity</h1></div>
    </section>

    <section class="halo">
      <a href="#">WARP DRIVE</a>
    </section>




  </div>
</template>

<script>
export default {
  name: 'home',

}
</script>



<style scoped lang="scss">

  .container {
    color: #fff;
    background-color:#000;
    height: calc(100vh);
    padding: 0 6%;

    .header {
      padding: 3% 0;
      display: flex;
      justify-content: space-between;

      img {
        width: 80%;
      }

    }
    .hero {
  padding-top: 8%;
      h6 {
        font-size: 25px;
        font-weight: 100;
        margin: 0;
        letter-spacing: 2px;
      }
      h1 {
        font-size: 150px;
        margin: 0;
        margin-top: -50px;
        font-weight: 500;
      }
    }

    .halo {
      padding: 2% 0 0 0;
      a {
        color: #7842F0;
        letter-spacing: 2px;
        text-decoration: none;
        border: 2px solid #7842F0;
        border-radius: 35px;
        padding: 1.5% 4%;
        font-weight: 700;
      }
      a:hover {
        background-color: #7842F0;
        color: #fff;
      }
    }

  }

</style>
