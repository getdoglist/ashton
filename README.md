<!DOCTYPE html>
<html>
<head>
 <title>Password</title>
 <style>
  body {
   background-color: lightblue;
   padding: 30px;
  }
 </style>
 <script>
  function checkPassword() {
   var password = document.getElementById("passwordBox");
   var passwordText = password.value;
   if(passwordText == "Marshall7644") {
    return true;
   }
   alert("Access denied! Incorrect password!");
   return false;
   }
 </script>
</head>
<body>
 <p style="font-size: 30pt;"></p>
 <p style="bg-color: red;">Please enter the password to view this website.</p>
 <p>Password:<input id="passwordBox" type="password"/></p>
 <a href="marshallstudentcouncil.weebly.com" onclick="return checkPassword();">
  Click here to submit password and view website
 </a>
</body>
</html>
