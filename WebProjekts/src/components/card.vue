<!-- Card.vue -->
<template>
    <div class="card-container">
      <div class="card">
        <img src="https://zz.lv/wp-content/uploads/2023/09/Jelgava-scaled.jpg" alt="Jelgava">
        <div class="card-content">
          <h3>Jelgava</h3>
          <p>Jelgava ir skaista pilsēta netālu no Rīgas.</p>
          <button>Apskatīt</button>
        </div>
      </div>
  
      <div class="card">
        <img src="https://static.lsm.lv/media/2024/07/large/1/o4sa.jpg" alt="Liepaja">
        <div class="card-content">
          <h3>Liepāja</h3>
          <p>Liepāja ir trešā lielākā pilsēta Latvijā. Tā ir lielākā Kurzemes pilsēta.</p>
          <button>Apskatīt</button>
        </div>
      </div>
  
      <div class="card">
        <img src="https://www.sundaypost.com/wp-content/uploads/sites/13/2018/05/iStock-527672859.jpg.jpg" alt="Riga">
        <div class="card-content">
          <h3>Rīga</h3>
          <p>Lielākā Latvijas pilsēta un Latvijas galvaspilsēta ir Rīga.</p>
          <button>Apskatīt</button>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: "Card",
  };
  </script>
  
  <style scoped>
  @import './card.css'; /* Import external CSS file for this component */
  </style>
  