<!DOCTYPE html>                    #for index.html tab
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login Form | Codehal</title>
    <link rel="stylesheet" href="style.css">
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
</head>

<body>

    <div class="wrapper">
        <form action="">
            <h1>Welcome to Alabama</h1>
            <div class="input-box">
                <input type="text" placeholder="Username" required>
                <i class='bx  bx-user'  ></i>
            </div>
            <div class="input-box">
                <input type="password" placeholder="Password" required>
                <i class='bx bxs-lock-alt'></i>
            </div>

            <div class="remember-forgot">
                <label><input type="checkbox"> Remember me</label>
                <a href="#">Forgot password?</a>
            </div>

            <button type="submit" class="btn">Sign in</button>

            <div class="register-link">
                <p>Don't have an account? <a
                        href="#">Sign up</a></p>
            </div>
        </form>
    </div>

</body>

</html>
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800;900&display=swap"); #for style css tab

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: "Poppins", comic-sans;
}

body {
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background: url('pexels-pixabay-50594.jpg') no-repeat;
    background-size: cover;
    background-position: center;
}

.wrapper {
    width: 420px;
    border: 2px solid rgba(0, 0, 0);
    background-color: rgba(179, 255, 26, 0.5);
    backdrop-filter: blur(10px);
    -webkit-backdrop-filter: blur(10px); /* for Safari */
    padding: 2rem;
    border-radius: 1rem;
    box-shadow: 0 0 10px rgba(0, 0, 0);
    color: #996633;
    border-radius: 10px;
    padding: 30px 40px;

}

.wrapper h1 {
    font-size: 36px;
    text-align: center;
}

.wrapper .input-box {
    position: relative;
    width: 100%;
    height: 50px;
    margin: 30px 0;
}

.input-box input {
    width: 100%;
    height: 100%;
    background: transparent;
    border: none;
    outline: none;
    border: 2px solid rgba(0, 0, 0);
    border-radius: 40px;
    font-size: 16px;
    color: #996633;
    padding: 20px 45px 20px 20px;
}

.input-box input::placeholder {
    color: #004d00;
}

.input-box i {
    position: absolute;
    right: 20px;
    top: 50%;
    transform: translateY(-50%);
    font-size: 20px;
}

.wrapper .remember-forgot {
    display: flex;
    justify-content: space-between;
    font-size: 14.5px;
    margin: -15px 0 15px;
}

.remember-forgot label input {
    accent-color: #fff;
    margin-right: 3px;
}

.remember-forgot a {
    color: #fff;
    text-decoration: none;
}

.remember-forgot a:hover {
    text-decoration: underline;
}

.wrapper .btn {
    width: 100%;
    height: 45px;
    background: #fff;
    border: none;
    outline: none;
    border-radius: 40px;
    box-shadow: 0 0 10px rgba(0, 0, 0, .1);
    cursor: pointer;
    font-size: 16px;
    color: #333;
    font-weight: 600;
}

.wrapper .register-link {
    font-size: 14.5px;
    text-align: center;
    margin: 20px 0 15px;
}

.register-link p a {
    color: #fff;
    text-decoration: none;
    font-weight: 600;
}

.register-link p a:hover {
    text-decoration: underline;
}
