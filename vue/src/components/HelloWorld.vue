
<template>

  <div id="app">
    <head>

      <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-KK94CHFLLe+nY2dmCWGMq91rCGa5gtU4mk92HdvYe+M/SXH301p5ILy+dN9+nJOZ" crossorigin="anonymous">
    </head>

    <div>
 </div>
</div>

<h1>Redcliffe</h1>
 <div class="container mt-4" id="app">

<table class="table table-bordered">
  <thead>
   
  </thead>
  <tbody>
    <tr>
      <th scope="col">RaceTitle</th>
      <th scope="col">Distance</th>
      <th scope="col">Stake</th>
      <th scope="col">Course</th>
      <th scope="col">Club</th>
      
     
    </tr>
    <tr>
<td>{{ myRacecard.races[0].title }}</td>
<td>{{ myRacecard.races[0].distance }}</td>
<td>{{ myRacecard.races[0].stake }}</td>
<td>{{ myRacecard.races[0].course }}</td>
<td>{{ myRacecard.races[0].club }}</td>
</tr>

    

     <tr>
      <th scope="col">Horse Number</th>
      <th scope="col">Horse Name</th>
      <th scope="col">Draw</th>
      <th scope="col">Jockey Name</th>
      <th scope="col">Trainer Name</th>
      <th scope="col">weight</th>
     
    </tr>
     <tr v-for="horse, index in myRacecard.races[0].horses">
      <td scope="row">{{ horse.horseNo }}</td>
      <td>{{ horse.horseName }}</td>
      <td>{{ horse.draw }}</td>
      <td>{{ horse.jockeyName }}</td>
      <td>{{ horse.trainerName }}</td>
      <td>{{ horse.weight }}</td>
     </tr>

     <tr>
      <th scope="col">RaceTitle</th>
      <th scope="col">Distance</th>
      <th scope="col">Stake</th>
      <th scope="col">Course</th>
      <th scope="col">Club</th>
      
     
    </tr>
    <tr>
<td>{{ myRacecard.races[1].title }}</td>
<td>{{ myRacecard.races[1].distance }}</td>
<td>{{ myRacecard.races[1].stake }}</td>
<td>{{ myRacecard.races[1].course }}</td>
<td>{{ myRacecard.races[1].club }}</td>
</tr>
     <tr>
      <th scope="col">Horse Number</th>
      <th scope="col">Horse Name</th>
      <th scope="col">Draw</th>
      <th scope="col">Jockey Name</th>
      <th scope="col">Trainer Name</th>
      <th scope="col">weight</th>
     
    </tr>
     <tr v-for="horse, index in myRacecard.races[1].horses">
      <td scope="row">{{ horse.horseNo }}</td>
      <td>{{ horse.horseName }}</td>
      <td>{{ horse.draw }}</td>
      <td>{{ horse.jockeyName }}</td>
      <td>{{ horse.trainerName }}</td>
      <td>{{ horse.weight }}</td>
     </tr>
     <tr>
      <th scope="col">RaceTitle</th>
      <th scope="col">Distance</th>
      <th scope="col">Stake</th>
      <th scope="col">Course</th>
      <th scope="col">Club</th>
      
     
    </tr>
    <tr>
<td>{{ myRacecard.races[2].title }}</td>
<td>{{ myRacecard.races[2].distance }}</td>
<td>{{ myRacecard.races[2].stake }}</td>
<td>{{ myRacecard.races[2].course }}</td>
<td>{{ myRacecard.races[2].club }}</td>
</tr>
     <tr>
      <th scope="col">Horse Number</th>
      <th scope="col">Horse Name</th>
      <th scope="col">Draw</th>
      <th scope="col">Jockey Name</th>
      <th scope="col">Trainer Name</th>
      <th scope="col">weight</th>
     
    </tr>
     <tr v-for="horse, index in myRacecard.races[2].horses">
      <td scope="row">{{ horse.horseNo }}</td>
      <td>{{ horse.horseName }}</td>
      <td>{{ horse.draw }}</td>
      <td>{{ horse.jockeyName }}</td>
      <td>{{ horse.trainerName }}</td>
      <td>{{ horse.weight }}</td>
     </tr>
     <tr>
      <th scope="col">RaceTitle</th>
      <th scope="col">Distance</th>
      <th scope="col">Stake</th>
      <th scope="col">Course</th>
      <th scope="col">Club</th>
      
     
    </tr>
    <tr>
<td>{{ myRacecard.races[3].title }}</td>
<td>{{ myRacecard.races[3].distance }}</td>
<td>{{ myRacecard.races[3].stake }}</td>
<td>{{ myRacecard.races[3].course }}</td>
<td>{{ myRacecard.races[3].club }}</td>
</tr>
     <tr>
      <th scope="col">Horse Number</th>
      <th scope="col">Horse Name</th>
      <th scope="col">Draw</th>
      <th scope="col">Jockey Name</th>
      <th scope="col">Trainer Name</th>
      <th scope="col">weight</th>
     
    </tr>
     <tr v-for="horse, index in myRacecard.races[3].horses">
      <td scope="row">{{ horse.horseNo }}</td>
      <td>{{ horse.horseName }}</td>
      <td>{{ horse.draw }}</td>
      <td>{{ horse.jockeyName }}</td>
      <td>{{ horse.trainerName }}</td>
      <td>{{ horse.weight }}</td>
     </tr>
     <tr>
      <th scope="col">RaceTitle</th>
      <th scope="col">Distance</th>
      <th scope="col">Stake</th>
      <th scope="col">Course</th>
      <th scope="col">Club</th>
      
     
    </tr>
    <tr>
<td>{{ myRacecard.races[4].title }}</td>
<td>{{ myRacecard.races[4].distance }}</td>
<td>{{ myRacecard.races[4].stake }}</td>
<td>{{ myRacecard.races[4].course }}</td>
<td>{{ myRacecard.races[4].club }}</td>
</tr>
     <tr>
      <th scope="col">Horse Number</th>
      <th scope="col">Horse Name</th>
      <th scope="col">Draw</th>
      <th scope="col">Jockey Name</th>
      <th scope="col">Trainer Name</th>
      <th scope="col">weight</th>
     
    </tr>
     <tr v-for="horse, index in myRacecard.races[4].horses">
      <td scope="row">{{ horse.horseNo }}</td>
      <td>{{ horse.horseName }}</td>
      <td>{{ horse.draw }}</td>
      <td>{{ horse.jockeyName }}</td>
      <td>{{ horse.trainerName }}</td>
      <td>{{ horse.weight }}</td>
     </tr>
     <tr>
      <th scope="col">RaceTitle</th>
      <th scope="col">Distance</th>
      <th scope="col">Stake</th>
      <th scope="col">Course</th>
      <th scope="col">Club</th>
      
     
    </tr>
    <tr>
<td>{{ myRacecard.races[5].title }}</td>
<td>{{ myRacecard.races[5].distance }}</td>
<td>{{ myRacecard.races[5].stake }}</td>
<td>{{ myRacecard.races[5].course }}</td>
<td>{{ myRacecard.races[5].club }}</td>
</tr>
     <tr>
      <th scope="col">Horse Number</th>
      <th scope="col">Horse Name</th>
      <th scope="col">Draw</th>
      <th scope="col">Jockey Name</th>
      <th scope="col">Trainer Name</th>
      <th scope="col">weight</th>
     
    </tr>
     <tr v-for="horse, index in myRacecard.races[5].horses">
      <td scope="row">{{ horse.horseNo }}</td>
      <td>{{ horse.horseName }}</td>
      <td>{{ horse.draw }}</td>
      <td>{{ horse.jockeyName }}</td>
      <td>{{ horse.trainerName }}</td>
      <td>{{ horse.weight }}</td>
     </tr>
     <tr>
      <th scope="col">RaceTitle</th>
      <th scope="col">Distance</th>
      <th scope="col">Stake</th>
      <th scope="col">Course</th>
      <th scope="col">Club</th>
      
     
    </tr>
    <tr>
<td>{{ myRacecard.races[6].title }}</td>
<td>{{ myRacecard.races[6].distance }}</td>
<td>{{ myRacecard.races[6].stake }}</td>
<td>{{ myRacecard.races[6].course }}</td>
<td>{{ myRacecard.races[6].club }}</td>
</tr>
     <tr>
      <th scope="col">Horse Number</th>
      <th scope="col">Horse Name</th>
      <th scope="col">Draw</th>
      <th scope="col">Jockey Name</th>
      <th scope="col">Trainer Name</th>
      <th scope="col">weight</th>
     
    </tr>
     <tr v-for="horse, index in myRacecard.races[6].horses">
      <td scope="row">{{ horse.horseNo }}</td>
      <td>{{ horse.horseName }}</td>
      <td>{{ horse.draw }}</td>
      <td>{{ horse.jockeyName }}</td>
      <td>{{ horse.trainerName }}</td>
      <td>{{ horse.weight }}</td>
     </tr>
     <tr>
      <th scope="col">RaceTitle</th>
      <th scope="col">Distance</th>
      <th scope="col">Stake</th>
      <th scope="col">Course</th>
      <th scope="col">Club</th>
      
     
    </tr>
    <tr>
<td>{{ myRacecard.races[7].title }}</td>
<td>{{ myRacecard.races[7].distance }}</td>
<td>{{ myRacecard.races[7].stake }}</td>
<td>{{ myRacecard.races[7].course }}</td>
<td>{{ myRacecard.races[7].club }}</td>
</tr>
     <tr>
      <th scope="col">Horse Number</th>
      <th scope="col">Horse Name</th>
      <th scope="col">Draw</th>
      <th scope="col">Jockey Name</th>
      <th scope="col">Trainer Name</th>
      <th scope="col">weight</th>
     
    </tr>
     <tr v-for="horse, index in myRacecard.races[7].horses">
      <td scope="row">{{ horse.horseNo }}</td>
      <td>{{ horse.horseName }}</td>
      <td>{{ horse.draw }}</td>
      <td>{{ horse.jockeyName }}</td>
      <td>{{ horse.trainerName }}</td>
      <td>{{ horse.weight }}</td>
     </tr>
     <tr>
      <th scope="col">RaceTitle</th>
      <th scope="col">Distance</th>
      <th scope="col">Stake</th>
      <th scope="col">Course</th>
      <th scope="col">Club</th>
      
     
    </tr>
    <tr>
<td>{{ myRacecard.races[8].title }}</td>
<td>{{ myRacecard.races[8].distance }}</td>
<td>{{ myRacecard.races[8].stake }}</td>
<td>{{ myRacecard.races[8].course }}</td>
<td>{{ myRacecard.races[8].club }}</td>
</tr>
     <tr>
      <th scope="col">Horse Number</th>
      <th scope="col">Horse Name</th>
      <th scope="col">Draw</th>
      <th scope="col">Jockey Name</th>
      <th scope="col">Trainer Name</th>
      <th scope="col">weight</th>
     
    </tr>
     <tr v-for="horse, index in myRacecard.races[8].horses">
      <td scope="row">{{ horse.horseNo }}</td>
      <td>{{ horse.horseName }}</td>
      <td>{{ horse.draw }}</td>
      <td>{{ horse.jockeyName }}</td>
      <td>{{ horse.trainerName }}</td>
      <td>{{ horse.weight }}</td>
     </tr>
     <tr>
      <th scope="col">RaceTitle</th>
      <th scope="col">Distance</th>
      <th scope="col">Stake</th>
      <th scope="col">Course</th>
      <th scope="col">Club</th>
      
     
    </tr>
    <tr>
<td>{{ myRacecard.races[9].title }}</td>
<td>{{ myRacecard.races[9].distance }}</td>
<td>{{ myRacecard.races[9].stake }}</td>
<td>{{ myRacecard.races[9].course }}</td>
<td>{{ myRacecard.races[9].club }}</td>
</tr>
     <tr>
      <th scope="col">Horse Number</th>
      <th scope="col">Horse Name</th>
      <th scope="col">Draw</th>
      <th scope="col">Jockey Name</th>
      <th scope="col">Trainer Name</th>
      <th scope="col">weight</th>
     
    </tr>
     <tr v-for="horse, index in myRacecard.races[9].horses">
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
