<template>
    <div class="hero-section">
      <div class="container">
        <div class="row">
          <div class="col-md-6">
            <h1>Welcome to Our Website</h1>
            <p>Discover amazing features and benefits.</p>
            <p>{{ fistName  }} {{ lastName }}</p>
            <button class="btn btn-primary" @click="learnMore">Learn More</button>
          </div>
          <div class="col-md-6">
            <!-- You can add an image or any other content here -->
          </div>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'HeroSection',
    // You can add any component logic here
    methods:{
      learnMore(){
        // Add your logic for the "Learn More" button click
      alert('hello');
      }
    },
    data() {
      return {
        'fistName': 'John',
        'lastName': 'Doe'
      }
    }
  }
  </script>
  
  <style scoped>
  /* Add custom styles for the hero section */
  .hero-section {
    background-color: #f8f9fa; /* Set your desired background color */
    padding: 100px 0; /* Adjust padding as needed */
    text-align: center; /* Align content to the center */
  }
  
  .hero-section h1 {
    font-size: 3rem; /* Set the font size for the heading */
    margin-bottom: 20px; /* Add margin below the heading */
  }
  
  .hero-section p {
    font-size: 1.2rem; /* Set the font size for the paragraph */
    margin-bottom: 30px; /* Add margin below the paragraph */
  }
  </style>
  