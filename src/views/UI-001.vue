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

      <div class="app">Get this app </div>
      <div class="rick-roll"></div>
      <p>
             <a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ">  
            <img border="0" alt="W3Schools" class="apple" src="https://www.instagram.com/static/images/appstore-install-badges/badge_ios_english-en.png/180ae7a0bcf7.png" width="134" height="40">
        </a>
             <a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ">  
            <img border="0" alt="W3Schools" class="google" src="https://www.instagram.com/static/images/appstore-install-badges/badge_android_english-en.png/e9cd846dc748.png" width="134" height="40">
        </a>
      </p>
      </div>
    </div>
  </div>
</template>


<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Alatsi&display=swap');
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
  font-size:29px;
  color: rgba(36, 94, 253, 0.88);
}
.home-content {
  border: gray 2px solid;
  font-family: 'Alatsi', sans-serif;
  border-radius: 3px;
  background: white;
  box-shadow: 0 0 30px rgba(0, 0, 0, 0.50);
  
}
.button {
  color: white;
  background-color: #0095f6;
  padding: 5px;
  margin-top: 15px;
  margin-left:225px ;
  margin-right: 15px;
  font-family: 'Alatsi', sans-serif;
  border-radius: 7px;
  
}
.app  {
  margin-top: 2rem;
}
.rick-roll {
 margin-top:5px ;
}
p {
  display: flex;
  justify-content: center;

}
body {
  background-color: rgb(123, 76, 224);
}
.left-container {
  left: 50px;
}


</style>
