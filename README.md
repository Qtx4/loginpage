# loginpage
<!doctype html>
<html>
<head>
	<meta charset="utf8">
	<title>interactive login form</title>
	<link rel="stylesheet" href="style2.css">
	<script src="login2.js"></script>
</head>
<body>
<form class="box" action="login.html"  method="POST">
<h1>
	login
</h1>
<input type="text" name=" " placeholder="enter username" id="username">
<input type="password" name=" "placeholder="enter password" id="password">
<input type="submit" name=" "value="Login" onclick="validate()">



</form>
</body>
</html>
#java script
function validate(){
	var username=document.getElementById("username").value;
	var password=document.getElementById("password").value;
	if(username=="kartik" &&  password=="user"){
		alert("login succesfully");
		return false;
	}





	else{
		alert("login failed");
	}





	
}
