# Snail

body,
html {
  width: 100%;
  height: 100%;
  padding-top: 1.8%;
  margin: 0;
  background-color: #e6e6e6;
  font-family: arial;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

.title-bar {
  text-align: center;
  color: #333333;
  font-size: 30px;
  padding-bottom: 10px;
}

.info-bar {
  text-align: center;
  color: #666;
  font-size: 15px;
  padding-bottom: 50px;
}

.info-bar a {
  color: #45b3e7;
  text-decoration: none;
}

.wrap {
  background-color: #ffffff;
  padding: 2%;
  width: 25%;
  min-width:350px;
  margin: 0 auto;
  -moz-border-radius: 6px;
  -webkit-border-radius: 6px;
  box-shadow: 0 0 5px #ccc;
  border: 1px solid #fff;
}

input {
  width: 90%;
  margin-bottom: 10px;
  padding: 5%;
  -moz-border-radius: 6px;
  -webkit-border-radius: 6px;
  border: 1px solid #efefef;
  font-size: 15px;
  -webkit-transition: all .2s ease-in-out;
  -moz-transition: all .2s ease-in-out;
  transition: all .2s ease-in-out;
}

input:focus {
  outline: none;
  border-color: #9ecaed;
  box-shadow: 0 0 10px #9ecaed;
  -webkit-transition: all .2s ease-in-out;
  -moz-transition: all .2s ease-in-out;
  transition: all .2s ease-in-out;
}

input.submit {
  width: 100%;
  padding: 5%;
  -moz-border-radius: 6px;
  -webkit-border-radius: 6px;
  border: 1px solid #45b3e7;
  font-size: 15px;
  background-color: #45b3e7;
  color: #fff;
  margin-top: 25px;
  -webkit-transition: all .2s ease-in-out;
  -moz-transition: all .2s ease-in-out;
  transition: all .2s ease-in-out;
}

input.submit:hover {
  width: 100%;
  padding: 5%;
  -moz-border-radius: 6px;
  -webkit-border-radius: 6px;
  border: 1px solid #32CD32;
  font-size: 15px;
  background-color: #32CD32;
  color: #fff;
  margin-top: 25px;
  -webkit-transition: all .2s ease-in-out;
  -moz-transition: all .2s ease-in-out;
  transition: all .2s ease-in-out;
}
<div class="title-bar">
  Snail++ Login
</div>

<div class="info-bar">
  Login to the client: <a href="https://snail++.com" target="blank">Chronos</a>
</div>

<div class="wrap">
  <form method="post">
    <input type="text" id="username" placeholder="Username">
    <input type="password" id="password" placeholder="Password">
    <input type="submit" class="submit" id="login" value="Login">
  </form>
</div>


