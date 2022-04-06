 
 <template>

 <div class="box">
    <div class="title">
      <h1>
      </h1>
    </div>

    <div class="registration">
      <div class="firstTitle">
        Registration
      </div>
      <div class="firstText">
        Not part of the community? Register for an account now!
      </div>
      <div class="firstText2">
        Enter Your Information to Sign Up!
      </div>
      <div class="container">
        <form action>

          <label for="firstName">First Name</label>
          <input type="text" name="firstname" placeholder="Enter your first name">

          <label for="LastName">Last Name</label>
          <input type="text" name="lastname" placeholder="Enter your last name">

          <label for="email">E-mail</label>
          <input type="text" name="message" placeholder="Enter your email">

          <label for="certification">Password</label>
          <input type="text" name="password" placeholder="Enter your password">
          <input type="submit" value="Submit">

        </form>
      </div>
    </div>
    <div class="login">
      <div class="rlogin">
        Login
      </div>
      <div class="secondText">
        Already signed up?
      </div>
      <div class="secondText2">
        Login now!
      </div>
      <form style>

        <label for="email">E-mail</label>
        <input type="text" name="message" placeholder="Enter your email">

        <label for="certification">Password</label>
        <input type="text" name="password" placeholder="Enter your password">

        <div class="rememberBox">
          <input type="checkbox" value="findRememberMe" id="rememberMe"> <label for="rememberMe">Remember me</label>

        </div>
        <div>
          <input type="submit" value="Sign In">
        </div>
        <div>
          or
        </div>
        <div>
          <button class="one">
            <a href="https://www.google.com/"> SIGN IN WITH GOOGLE ACCOUNT </a>
          </button>
          <div>
            <button class="two">
              <a href="https://www.facebook.com/"> SIGN IN WITH FACEBOOK </a>
            </button>
          </div>
          <div>
            <button class="three">
              <a href="https://www.byu.edu/"> SIGN IN WITH BYU ACCOUNT </a>
            </button>
            <div>
              <div>
                <button class="four">
                  <a href="https://wenderlygames.itch.io/assessment-examination"> PROCEED WITH RETICAL SCAN</a>
                </button>
                <div>
      </form>
    </div>
  </div>
</template>
  
<style scoped>
@import url('https://fonts.googleapis.com/css?family=Lora');


body {
    background-color: #FFEBD2;
  padding: 40px 20px 40px 20px;
  font-family: 'Lora', serif;
}



.box {
  background-color: white;
  padding-left: 20px;
    background-color: #FFEBD2;
}

.registration {
  background-color: #FFA364;
  float: left;
  width: 675px;
  height: 800px;
}

.login {
  background-color: #AF4F41;
  float: left;
  width: 675px;
  height: 800px;
}

.firstTitle {
  text-align: center;
  padding-top: 40px;
  font-size: 25px;
  text-decoration: underline;
}

.rlogin {
  text-align: center;
  padding-top: 40px;
  font-size: 25px;
  text-decoration: underline;
}

.firstText {
  text-align: center;
  padding-top: 30px;
}

.firstText2 {
  text-align: center;
  padding-top: 40px;
}


.container {
  padding: 20px 20px 20px 20px;
}
form {
  padding: 20px 20px 20px 20px;
}

input[type=text], select, textarea {
  width: 100%;
  padding: 10px;
  border: 1px solid #BLACK;
  border-radius: 50px;
  box-sizing: border-box;
  margin-top: 5px;
  margin-bottom: 15px;
  resize: vertical;
  font-family: 'Lora', serif;
}

input[type=submit] {
  color: black;
  padding: 15px 20px;
  border: none;
  border-radius: 50px;
  cursor: pointer;
  background-color: white;
  font-family: 'Lora', serif;
}

input[type=submit]:hover {
  background-color: grey;
  font-family: 'Lora', serif;
}

.rememberBox{
  padding-left: 20px;
  padding-bottom: 20px;
}

.one {
  background-color: #e94335;
  color: white;
  padding: 12px 20px;
  border: none;
  border-radius: 50px;
  cursor: pointer;
  width: 300px;
  font-weight: bold;
}

.two {
  background-color: #2b66f1;
  color: white;
  padding: 12px 20px;
  border: none;
  border-radius: 50px;
  cursor: pointer;
  width: 300px;
  top: 600px;
  font-weight: bold;
  margin-top: 10px;
}
.three {
  background-color: #FC7643;
  color: white;
  padding: 12px 20px;
  border: none;
  border-radius: 50px;
  cursor: pointer;
  width: 300px;
  top: 600px;
  font-weight: bold;
  margin-top: 10px;
}
.four {
  background-color: #A23334;
  color: white;
  padding: 12px 20px;
  border: none;
  border-radius: 50px;
  cursor: pointer;
  width: 300px;
  top: 600px;
  font-weight: bold;
  margin-top: 10px;
}
#footer {
  margin-top: 30%;
  margin-left: 95%;
}
</style>
