<template>
    <div class="address_search">
      <div class="spacer"></div>
      <h1>Saint Twins Addresses</h1>
      <input type="search" name="address" id="address">
      <div class="text">Test</div>
      <div class="spacer"></div>
    </div>
  </template>
  
  <style scoped>
  @media (min-width: 1024px) {
    .address_search {
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
    }
    .spacer {
        flex-grow: 1;
    }
  }
  
  
  </style>
  