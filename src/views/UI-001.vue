<template>
  <div class="flex-center">
    <div class="home-content">
      <h2>Create a new account </h2>
      <div class="input">
    
      <input type="email" placeholder="Email" >
 
      <input type="full name" placeholder="Full name" >
  
      <input type="username" placeholder="Username">

      <input type="password" placeholder="Password"> 

      <button class="button ">Next</button>
      </div>
      <p></p>
    </div>
  </div>
</template>


<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@600&display=swap');
.input {
  display:flex;
  flex-direction: column;
  
}
 input {
  margin: 14px;
  padding: 8px;
 }
h1 {
font-size: 15px;
display: flex;
}
h2 {
  font-size:25px;
  color: rgba(36, 94, 253, 0.88);
}
.home-content {
  border: gray 2px solid;
  font-family: 'Open Sans', sans-serif;
  border-radius: 3px;
  box-shadow: 0 0 30px rgba(0, 0, 0, 0.50);
}
.button {
  color: white;
  background-color: #0095f6;
  padding: 5px;
  margin-top: 15px;
  margin-left:225px ;
  margin-right: 15px;
  font-family: 'Open Sans', sans-serif;
  border-radius: 7px;
}
</style>
