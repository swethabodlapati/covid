<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body, html {
  height: 100%;
  font-family: Arial, Helvetica, sans-serif;
  background: url("covid3.jpg")
}
h1{
	text-align: center;
	color:black;
}
* {
  box-sizing: border-box;
}

.bg-img {
  /* The image used 
  background-image: url("covid3.jpg");
  min-height: 380px;
  /* Center and scale the image nicely */
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  position: relative;
}

/* Add styles to the form container */
.container {
  position: absolute;
  margin: 20px;
  max-width: 500px;
  padding: 16px;
  background-color: white;
}

/* Full-width input fields */
input[type=text], input[type=password] {
  width: 100%;
  padding: 15px;
  margin: 5px 0 22px 0;
  border: none;
  background: #f1f1f1;
}

input[type=text]:focus, input[type=password]:focus {
  background-color: #ddd;
  outline: none;
}

/* Set a style for the submit button */
.btn {
  background-color: #4CAF50;
  color: white;
  padding: 16px 20px;
  border: none;
  cursor: pointer;
  width: 100%;
  opacity: 0.9;
}

.btn:hover {
  opacity: 1;
}
</style>
</head>
<body>

<h1>Covid Samraksha(Covid test)</h1>
<div class="bg-img">
  <form action="qns.html" class="container">
    <h1>Please fill the Details</h1>
    <label for="name"><b>Name</b></label>
    <input type="text" placeholder="Enter Name" name="name" required>
    <label for="age"><b>Age</b></label>
    <input type="number"  name="age" value="" required>
    <br>
    <br>
    <label for="gender"><b>Gender</b></label>
    <select id="gender" horizantal-size="50">
    	<option  value="others">Select the gender</option>
        <option  value="Male">Male</option>
        <option  value="Female">Female</option>
    </select>
    <br>
    <br>
    <label for="email"><b>Email</b></label>
    <input type="text" placeholder="Enter Email" pattern="^([^\x00-\x20\x22\x28\x29\x2c\x2e\x3a-\x3c\x3e\x40\x5b-\x5d\x7f-\xff]+|\x22([^\x0d\x22\x5c\x80-\xff]|\x5c[\x00-\x7f])*\x22)(\x2e([^\x00-\x20\x22\x28\x29\x2c\x2e\x3a-\x3c\x3e\x40\x5b-\x5d\x7f-\xff]+|\x22([^\x0d\x22\x5c\x80-\xff]|\x5c[\x00-\x7f])*\x22))*\x40([^\x00-\x20\x22\x28\x29\x2c\x2e\x3a-\x3c\x3e\x40\x5b-\x5d\x7f-\xff]+|\x5b([^\x0d\x5b-\x5d\x80-\xff]|\x5c[\x00-\x7f])*\x5d)(\x2e([^\x00-\x20\x22\x28\x29\x2c\x2e\x3a-\x3c\x3e\x40\x5b-\x5d\x7f-\xff]+|\x5b([^\x0d\x5b-\x5d\x80-\xff]|\x5c[\x00-\x7f])*\x5d))*$" name="email" required>

    <label for="Contact"><b>Contact</b></label>
    <input type="text" placeholder="Enter Contact" maxlength="10" name="contact" required>
    <div>
    	<a href="C:\Users\DELL\Desktop\test\qns.html">
    		<button type="submit" class="btn">Proceed</button>
    	</a>
  </form>
</div>
<script src="jquery-2.1.4.min.js"></script>
  <script src="bootstrap.min.js"></script>
  <script src="script.js"></script>
</body>
</html>
