<template>
  <div class="flex-center">
    <div class="home-content">
      <h2>create a new account </h2>
      <div class="input">
        <h1>Email</h1>
      <input type="email">
      <h1>Full name</h1>
      <input type="full name">
      <h1>Username</h1>
      <input type="username">
      <h1>Password</h1>
      <input type="password"> 
      </div>
      <p></p>
    </div>
  </div>
</template>


<style lang="scss">
.input {
  display:flex;
  flex-direction: column;
  
}
 input {
  margin: 5px;
  padding: 4px;
 }
h1 {
font-size: 15px;
display: flex;
}
h2 {
  font-size:25px;
}
</style>
