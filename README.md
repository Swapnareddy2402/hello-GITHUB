
<html lang="en">  
<head>  
<meta charset="UTF-8" />  
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>  
<title>Login Page</title>  
<style>  
body {  
background: white;  
font-family: Arial, italic;  
display: flex;  
height: 100vh;  
justify-content: center;  
align-items: center;  
margin: 0;  
}  
.login-container {  
background: pink;  
padding: 40px 30px;  
border-radius: 8px;  
box-shadow: 0 0 10px rgba(0,0,0,0.1);  
width: 100%;  
max-width: 400px;  
}  
.login-container h2 {  
text-align: center;  
margin-bottom: 20px;  
color: violet;  
}  
.login-container input[type="text"],  
.login-container input[type="password"] {  
width: 100%;  
padding: 12px;  
margin: 8px 0 20px 0;  
border: 1px solid blue;  
border-radius: 4px;  
}  
.login-container button {  
width: 100%;  
padding: 12px;  
background-color: black;  
color: white;  
border: none;  
border-radius: 4px;  
cursor: pointer;  
font-size: 16px;  
}  
.login-container button:hover {  
background-color: black;  
}  
.login-container .signup {  
margin-top: 15px;  
text-align: center;  
font-size: 14px;  
}  
.login-container .signup a {  
color: white;  
text-decoration: none;  
}  
</style>  
</head>  
<body>  
<div class="login-container">  
<h2>Login</h2>  
<form action="/login" method="post">  
<input type="text" name="username" placeholder="Username" required />  
<input type="password" name="password" placeholder="Password" required />  
<button type="submit">Login</button>  
</form>  
<div class="signup">  
Don't have an account? <a href="[https://www.instagram.com](https://www.instagram.com/)">Sign up</a>  
</div>  
</div>  
</body>  
</html>  
