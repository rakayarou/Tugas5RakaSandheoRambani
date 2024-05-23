<template>
    <nav class="navbar">
      <div class="logo">IndoPride</div>
      <ul class="nav-links">
      </ul>
    </nav>
  </template>
  
  <script>
  export default {
    name: 'Navbar'
  }
  </script>
  
  <style>
  .navbar {
    display: center;
    align-items: center; /* Center items vertically */
    justify-content: space-between;
    background-color: #a15000;
    padding: 10px;
  }
  
  .logo {
    color: #fff;
    font-size: 50px;
    font-weight: bold;
    text-align: center;
  }
  
  .nav-links {
    list-style: none;
    display: flex;
  }
  
  .nav-links li {
    margin: 0 10px;
  }
  
  .nav-links a {
    color: #000000;
    text-decoration: none;
  }
  
  /* Adjust icon size */
  .nav-links a i {
    margin-right: 5px; /* Add some space between the icon and text */
    font-size: 18px; /* Adjust the icon size */
  }
  </style>
  