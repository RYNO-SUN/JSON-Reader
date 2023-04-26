
<template>

  <div id="app">
    <head>

      <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-KK94CHFLLe+nY2dmCWGMq91rCGa5gtU4mk92HdvYe+M/SXH301p5ILy+dN9+nJOZ" crossorigin="anonymous">
    </head>

    <div>
 </div>
</div>

 
 <div class="container mt-4" id="app">

<table class="table table-bordered">
  <thead>
    <tr>
      <th scope="col">Horse Number</th>
      <th scope="col">Horse Name</th>
      <th scope="col">Draw</th>
      <th scope="col">Jockey Name</th>
      <th scope="col">Trainer Name</th>
      <th scope="col">weight</th>
     
    </tr>
  </thead>
  <tbody>
    <tr v-for="horse, index in myRacecard.races[0].horses">
      <td scope="row">{{ horse.horseNo }}</td>
      <td>{{ horse.horseName }}</td>
      <td>{{ horse.draw }}</td>
      <td>{{ horse.jockeyName }}</td>
      <td>{{ horse.trainerName }}</td>
      <td>{{ horse.weight }}</td>
     </tr>

    

    
  </tbody>
</table>
</div>






</template>

<script>
import json from "/public/RaceCard_C3R.json";

export default {
  name: "App",
  data: () => ({ RaceCard_C3R: "racecard" }),
  computed: {
    myRacecard: function () {
      return json[this.RaceCard_C3R] || {};
    },
  },
};


</script>
