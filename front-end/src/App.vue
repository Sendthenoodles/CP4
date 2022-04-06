<template>
<div id="app">
  <div class="header">
    <div class="brand">
      <h1>Fluffy-Plumas Store</h1>
      <h2>Shop!</h2>
      
      <span class = "github"><a href="https://github.com/Sendthenoodles/CP4">
            <img src="github.png" height="75px" width="75px"
          /></a></span>
    </div>
  </div>
  <div class="content">
    <router-view />
  </div>
</div>
</template>

<style>
.github{
  padding-left: 70%;
  
}
body {
  margin: 0px;
  background: #F7F5F7;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}


.brand {
  display: flex;
  background: #F5CEC7;
  padding: 10px 100px;
}

.brand h1 {
  display: inline-block;
  background: #FFB284;
  padding: 10px;
  border-radius: 30px;
  font-size: 20px;
}

.brand h2 {
  font-size: 16px;
  padding: 10px;
  margin-top: 12px;
}

.main {
  padding: 20px 100px;
}

.pure-button {
  font-size: 10px;
}

h1 {
  font-size: 16px;
}

h2 {
  font-size: 12px;
}

.space-right {
  margin-right: 10px;
}


a {
  color: #ffad60;
}

.pure-button-primary {
  background-color: #ffad60;
  color: #333;
  border-radius: 30px;
}
</style>
