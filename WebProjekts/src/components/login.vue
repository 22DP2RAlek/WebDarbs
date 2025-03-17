<template>
    <main>
      <p> Reģistrācija</p>
      <input 
        type="text" 
        v-model="email" 
        id="email" 
        name="email" 
        placeholder="Ievadi savu e-pastu" 
      />
      <input 
        type="password" 
        v-model="password" 
        id="password" 
        name="password" 
        placeholder="Ievadi savu paroli" 
      />
      <button @click="register">Reģistrēties</button>
    </main>
  </template>
  
  <script>
  // If you don't need logic right now, you can leave the script section empty
  export default {
    // No data or methods for now
  }
  </script>
  
  <style scoped>
  main {
    text-align: center;
    padding-top: 10%;
  }
  </style>
  