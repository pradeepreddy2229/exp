<!DOCTYPE html>
<html>
<head>
    <title>Simple Login Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #e6f2ff;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .login-box {
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 0 10px gray;
            width: 300px;
        }
        input {
            width: 100%;
            padding: 8px;
            margin: 8px 0;
        }
        button {
            width: 100%;
            padding: 10px;
            background-color: green;
            color: white;
            border: none;
            border-radius: 5px;
        }
        button:hover {
            background-color: darkgreen;
        }
    </style>
</head>
<body>

    <div class="login-box">
        <h2>Login</h2>
        <form>
            <label>Username:</label>
            <input type="text" placeholder="Enter username" required>

            <label>Password:</label>
            <input type="password" placeholder="Enter password" required>

            <button type="submit">Login</button>
        </form>
    </div>

</body>
</html>
