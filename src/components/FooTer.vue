<template>
    <footer class="footer bg-dark text-light py-3">
      <div class="container">
        <div class="row">
          <div class="col-md-6">
            <p>&copy; 2024 Your Company. All rights reserved.</p>
          </div>
          <div class="col-md-6 text-md-right">
            <ul class="list-inline">
              <li class="list-inline-item"><a href="#">Home</a></li>
              <li class="list-inline-item"><a href="#">About</a></li>
              <li class="list-inline-item"><a href="#">Contact</a></li>
            </ul>
          </div>
        </div>
      </div>
    </footer>
  </template>
  
  <script>
  export default {
    name: 'FooTer',
    props: {
    msg: String
  }
  }
  </script>
  

  