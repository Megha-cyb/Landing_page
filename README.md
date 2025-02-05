# Landing_page
<!DOCTYPE html><html lang="en"><head><meta charset="UTF-8"/><meta name="viewport" content="width=device-width, initial-scale=1.0"/>
	<title>Gritstone - Login</title>
	<style type="text/css">body {
            font-family: Arial, sans-serif;
            background-color: #800000; /* Maroon Red */
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .login-container {
            background: #ffffff;
            padding: 30px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.2);
            border-radius: 10px;
            text-align: center;
            width: 350px;
            border-top: 5px solid red;
        }
        .logo {
            width: 80px;
            margin-bottom: 10px;
        }
        .company-name {
            font-size: 24px;
            font-weight: bold;
            color: black;
            margin-bottom: 20px;
        }
        .input-field {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 16px;
        }
        .login-btn {
            background-color: red;
            color: white;
            border: none;
            padding: 12px;
            width: 100%;
            font-size: 16px;
            cursor: pointer;
            border-radius: 5px;
            margin-top: 10px;
        }
        .login-btn:hover {
            background-color: darkred;
        }
	</style>
</head>
<body>
<div class="login-container"><img alt="Gritstone Logo" class="logo" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRz4HC8LIR02E9UxyrFWyZx_lWk68Iq2S_I3w&amp;s"/> <!-- Replace with actual logo -->
<div class="company-name">GRITSTONE</div>

<form action="" method="POST"><input class="input-field" name="email" placeholder="Email ID" required="" type="email"/> <input class="input-field" name="password" placeholder="Password" required="" type="password"/><button class="login-btn" type="submit">Login</button></form>
</div>


</body></html>
