<template>
<button class="dupe">Duplication glitch</button>

<button class="delete">Delete</button>

 
    <button id="btn1">Change the color</button>




<div class="card">
    <img src="https://variety.com/wp-content/uploads/2019/06/spongebob-battle-remaster.png?w=681&h=383&crop=1" />
    <p class="card_title title-white">Project 1 complete</p>
  
  <details>
    <summary>Details</summary>
    This card was created by David Scheer, this was a struggle but like Spongebob, we perservered and compleated it. In conclusion this wonderful picture is of spongebob with the title of Project 1 complete underneath is the details button I created that links to the required website.
</details>
 
</div>
</template>

<script setup>
import HelloWorld from './components/HelloWorld.vue'

// This starter template is using Vue 3 experimental <script setup> SFCs
// Check out https://github.com/vuejs/rfcs/blob/script-setup-2/active-rfcs/0000-script-setup.md
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

<style> 
.card {
  width: 600px;
  height: 600px;
  border: 5px solid black;
  margin: 20px;
  padding: 20px;
   background-color: rgb(120,45,99);
    text-align: center;
}

img {
  width: 100%;
}

.card_title {
  text-align: left;
  font-family: sans-serif;
  font-weight: bold;
  font-size: 25px;
}

.card_paragraph{
  Text-align: left;
  font-family: sans-serif;
  font-weight: bold; 
  font-size: 15px; 
  
}

@media screen and (max-width: 500px){
  .card {
    width: 100%;
    border: 5px solid red;
    margin: 20px;
    padding: 20px;
  }
  
 .btn {
    margin: 1px 10px 50px; 
    border: 2px solid red; 
    text-transform: uppercase; 
    padding: 8px 8px; 
   }

  .card_paragraph {
    visibility: hidden;
  }
}



</style>




  

  
 
  


