<template>
  <section class="hero" id="home">
    <div class="container">
      <div class="hero-content">
        <h1 class="hero-title">Your full-funnel growth agency</h1>
        <p class="hero-text">
          Capture and retrieve your lists across devices to help you stay organized at work, home, and on the go.
        </p>
        <button class="btn">Get started</button>
      </div>

      <div class="hero-banner">
        <img src="../assets/images/bg.png" alt="Background Image" class="bg-image" />
        <img src="../assets/images/hero-banner.png" alt="Hero Banner" class="hero-banner-image" />
      </div>
    </div>
  </section>
</template>


<script>
export default {
  name: "HeroSection",
};
</script>

<style scoped>
.container {
  display: flex;
  justify-content: space-around;
  align-items: center;
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 20px;
}

.hero {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  padding: 50px 20px;
  background-color: #f8f8f8;
}

.hero-content {
  max-width: 600px;
}

.hero-title {
  font-size: 45px; 
  font-weight: 700; 
  color: black; 
  margin-bottom: 20px;
}

.hero-text {
  font-size: 22px;
  font-weight: 500;
  color: black;
  margin-bottom: 20px;
  line-height: 1.6;
  font-family: "Poppins", sans-serif;
}

.btn {
  padding: 19px 31px;
  background-color: #ef4444; /* Bright red button */
  color: #ffffff; /* White text */
  font-size: 18px;
  font-weight: 600;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  transition: background-color 0.3s ease-in-out;
}

.btn:hover {
  background-color: #dc2626; 
}


.hero-banner {
  flex: 1;
  position: relative;
  justify-content: flex-end;
  text-align: right;
  z-index: 1;
}

.bg-image,
.hero-banner-image {
  position: absolute;
  right: 0; /* Stick to the right */
}

.bg-image {
  width: 100%;
  height: auto;
  max-width: 1200px;
  
  position: absolute;
  bottom: 0;
  right: 0;
  z-index: 0; 
}

.hero-banner-image {
  width: 70%;
  max-width: 600px;
  height: auto;
  position: relative;
  right:0;
  z-index: 1;
  margin-left: auto; 
  
  bottom: 20px;
}

</style>
