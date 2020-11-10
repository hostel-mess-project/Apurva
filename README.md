<!DOCTYPE html>
<html lang="en">
<head>
    <title>REGISTRATION</title>
    <style>
      html {
background-color:whitesmoke;
background-size: cover;
}
.topnav {
overflow: hidden;
background-color: #333;
}

.topnav a {
float: left;
color: #f2f2f2;
text-align: center;
padding: 14px 16px;
text-decoration: none;
font-size: 17px;
}

.topnav a:hover {
background-color:whitesmoke;
color:black;
}

input[type=text], input[type=password],input[type=number],input[type=email]{
 width: 25%;
 padding: 12px 20px;
 margin: 8px 0;
 display: inline-block;
 border: 1px solid #ccc;
 box-sizing: border-box;
}
button {
  background-color: #4CAF50;
  color: white;
  padding: 14px 20px;
  margin: 8px 0;
  border: none;
  cursor: pointer;
  width: 10%;
}

button:hover {
  opacity: 0.8;
}

.cancelbtn {
  width: auto;
  padding: 10px 18px;
  background-color:red;
}


img.avatar {
  width: 40%;
  border-radius: 50%;
}

.container {
  padding: 16px;
}

span.psw {
  float: right;
  padding-top: 16px;
}

/* Change styles for span and cancel button on extra small screens */
@media screen and (max-width: 300px) {
  span.psw {
     display: block;
     float: none;
  }
  .cancelbtn {
     width: 100%;
  }
}
</style>
</style>
    
</head>
<body>
<h1 align="center">SRM HOSTEL MESS MANAGEMENT</h1>
<div class="topnav">
  <a href="Home.html">HOME</a>
  
  <a href="payment.html">PAYMENT</a>
  
  <a href="menu.html">MENU</a> 
  
  <a href="rules.html">RULES</a>
  
  <a href="registration.html">REGISTRATION</a>
  
  <a href="login.html">LOGIN</a>
  
  <a href="feedback.html">FEEDBACK</a>
  
  </div>
<body align="center" >
    <form action="reg.php" method="POST">
      <h1>SIGN UP/REGISTER</h1>
  <div class="container">
    <aside>
      <div style="float:right;">
          <table>
            <tr>
         <b>   <ul align="left">
             CAMPUSES<br>
              <hr>
              <li align="left">NCR<BR>
              <li align="left">VADAPALANI<BR>
              <li align="left">RAMAPURAM<BR>
              <li>KATTANKULATHUR
            </ul></b>
            </tr>
          </table>
      </div>
          </aside>
    <label for="regno"><b>*Registration Number:<b></label>
    <input type="text" placeholder="Enter Registration Number" id="regno" name="regno" required>
    <br><br>
    <label for="fname">*First name:<b></label>
    <input type="text"placeholder="Enter First Name" id="fname" name="fname" required>
    <br><br>
    <label for="mname">Middle name:<b></b></label>
    <input type="text" id="mname" name="mname">
    <br><br>
    <label for="lname">*Last name:<b></b></label>
    <input type="text"placeholder="Enter Last Name" id="lname" name="lname" required>
    <br><br>
    <label for="email">*Email:<b></b></label>
    <input type="email" placeholder="Enter Email"id="email" name="email" required><br><br>
    <label for="phone">Mobile Number:<b></b></label>
    <input type="number" placeholder="Enter Mobile Number"id="phnno" name="phnno" required><br><br>
    <label for="cars">*Course:<b></b></label>
<select id="course" name="course">
<option value="btech">BTECH</option>
<option value="be">BE</option>
<option value="mtech">MTECH</option>
<option value="medical">MEDICAL</option>
<option value="bba">BBA</option>
<option value="mba">MBA</option>
</select>
<br><br>
Gender:<b></b>
<input type="radio" id="male" name="gender" value="male" required>
<label for="male">Male</label>
<input type="radio" id="female" name="gender" value="female" required>
<label for="female"> Female</label><br><br>

    <label for="password">*Enter password:<b></b></label>
    <input type="password" placeholder="Enter the password" id="pwd" name="pwd" required><br><br>
    <label for="password">*Re-Enter password:</label>
    <input type="password" placeholder="Re-Enter the password"id="pwd" name="pwd" required>
  </label>
  <br><br>
  <button>SUBMIT</button>
    </label>
  </div>

  <div class="container" style="background-color:#f1f1f1">
    
  </div>
        
      </form>
    
</body>
</html>
