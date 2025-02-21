<html>
<head>
<title>Login</title>
<style>
body {
  font-family: sans-serif;
}

form {
  width: 300px;
  margin: 0 auto;
  padding: 20px;
  border: 1px solid #ccc;
  border-radius: 5px;
}

label {
  display: block;
  margin-bottom: 5px;
}

input[type="text"],
input[type="password"] {
  width: 100%;
  padding: 10px;
  margin-bottom: 10px;
  border: 1px solid #ccc;
  border-radius: 5px;
}

input[type="submit"] {
  background-color: #4CAF50;
  color: white;
  padding: 10px 15px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}
</style>
</head>
<body>

<h1>Login</h1>

<form>
  <label for="username">Username:</label>
  <input type="text" id="username" name="username">

  <label for="password">Password:</label>
  <input type="password" id="password" name="password">

  <input type="submit" value="Submit">
</form>

</body>
</html>