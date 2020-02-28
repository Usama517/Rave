<!DOCTYPE HTML>
<head>
<style>
#myVideo {
	position: fixed;
	right: 0;
	bottom: 0;
	min-width: 100%; 
	min-height: 100%;
	-o-filter: blur(15px);
}

.loginPanel {
	position: fixed;
	height: 500px;
	width: 300px;
	margin-top: 100px;
	margin-left: 600px;
	border-radius: 25px;
	background: rgb(58, 56, 56);
	box-shadow: 0px 0px 10px black;
	text-align:center;
}

.lowerPanel {
	position: fixed;
	left: 0;
	bottom: 0;
	background: rgb(58, 56, 56);
	color: rgb(58, 56, 56);
	width: 100%;
	height: 80px;
	
}

#Logo {
	position: fixed;
	margin-left: 703px;
	margin-top: 40px;
	
}

#Name {
	margin-top: 50px;
	
}

#Username {
  width: 100%;
  padding: 12px 20px;
  <!-- margin-top: 100px; -->
  display: inline-block;
  border: 1px solid #ccc;
  width: 200px;
  border-radius: 25px;

}

#Password {
  width: 100%;
  padding: 12px 20px;
  <!-- margin-top: 50px; -->
  display: inline-block;
  border: 1px solid #ccc;
  width: 200px;
  border-radius: 25px;

}

#loginButton {
  width: 100%;
  padding: 12px 20px;
  margin-top: 50px;
  display: inline-block;
  border: 1px solid green;
  width: 100px;
  border-radius: 25px;
  background-color: purple;
  color: white;
  font-style: bold;
  font-size: 20px;
  font-family: nineteenth;
  
}

#loginButton:hover {
	background-color: lightgreen;
	

}

.headers{
	margin-top:50px;
	color: white;
	font-size: 20px;
	font-family: nineteenth; 
}

</style>
</head>
<body>

<video autoplay muted loop id="myVideo">
	<source src="rave_bg.mp4" type="video/mp4">
</video>



<div class = "loginPanel">
<img src="name.png" id="Name" height="20px">
<p class="headers">Username</p>
<input type="text" id="Username" name="uname" required>
<p class="headers">Password</p>
<input type="text" id="Password" name="pass" required>
<button type="button" id="loginButton">Login</button>
</div>

<img src="logo.png" id="Logo" height="100px">

<div class = "lowerPanel"> 

</div>

</body>

