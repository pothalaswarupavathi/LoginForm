<!DOCTYPE html>
<html>
<head>
<title>Login Page</title>
<style>
body{
background-color:lightyellow;
display:flex;
justify-content:center;
height:90vh;
align-items:center;
}
.login-box{
background-color:white;
padding:30px;
width:300px;
text-align:center;

}
input{
width:90%;
padding:10px;
border-radius:5px;
margin-bottom:10px;
border: 1px solid #ccc;
}
button{
width:90%;
padding:10px;
border-radius:5px;
border:1px solid;
background-color:lightgreen;
}
button:hover{
color:rgba(0,0,0,0.6);
}
</style>
<body>
<div class="login-box">
<h2>Login</h2>
<form>
 <input type="text" placeholder="username" required><br>
 <input type="text" placeholder="password" required><br>
 <button type="submit">Login</button>
</form>

</div>

</body>
</html>

