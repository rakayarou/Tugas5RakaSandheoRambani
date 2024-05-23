<template>
    <div class="sidebar">
      <h3>Categories</h3>
      <ul>
        <li><a href="#all">All</a></li>
        <li><a href="#jam tangan">Jam Tangan</a></li>
        <li><a href="#baju">Baju</a></li>
        <li><a href="#celana">Celana</a></li>
        <li><a href="#sepatu">Sepatu</a></li>
        <li><a href="#sendal">Sendal</a></li>
        <li><a href="#aksesoris">Aksesoris</a></li>
        <!-- Add more categories as needed -->
      </ul>
    </div>
  </template>
  
  <script>
  export default {
    name: 'Sidebar'
  };
  </script>
  
  <style>
  .sidebar {
    width: 200px;
    padding: 20px;
    position: fixed;
    top: 60px; /* Adjust to match the height of the navbar */
    left: 0;
    height: calc(100% - 60px); /* Adjust to match the height of the navbar */
    overflow-y: auto;
    z-index: 1; /* Ensure it is above the main content */
    background: transparent; /* Remove background color */
  }
  
  .sidebar h3 {
    font-size: 22px;
    margin-bottom: 20px;
    color: brown;
  }
  
  .sidebar ul {
    list-style: none;
    padding: 0;
  }
  
  .sidebar li {
    margin-bottom: 10px;
  }
  
  .sidebar a {
    color: #fff; /* Ensure text is visible over the background */
    text-decoration: none;
    font-size: 18px;
  }
  
  .sidebar a:hover {
    color: #184205; /* Adjust hover color */
  }
  </style>
  