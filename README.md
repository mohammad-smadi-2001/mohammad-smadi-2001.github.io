# mohammad-smadi-2001.github.io<!DOCTYPE html>
<html>
<link href='loginStyle.css' rel='stylesheet' type='text/css'>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
<script src="http://cdnjs.cloudflare.com/ajax/libs/gsap/1.18.0/TweenMax.min.js"></script>

<body>

    <script src="loginScript.js"></script>
    <div id="login-button">
        <img src="https://dqcgrsy5v35b9.cloudfront.net/cruiseplanner/assets/img/icons/login-w-icon.png">
        </img>
    </div>

    <!-- login Container -->
    <div id="container">
        <h1 id="loginTitle">Log In</h1>
        <span class="close-btn">
            <img src="https://cdn4.iconfinder.com/data/icons/miu/22/circle_close_delete_-128.png"></img>
        </span>

        <form>
            <input type="email" name="email" placeholder="E-mail">
            <input type="password" name="pass" placeholder="Password">
            <a href="#">Log in</a>
            <div id="remember-container">
                <span id="Register">Register</span>
            </div>
        </form>
    </div>

    <!-- Register Container -->
    <div id="register-container">
        <h1 style="font-size:170%; margin: 5%;">Register</h1>
        
        <span class="close-btn">
            <img src="https://cdn4.iconfinder.com/data/icons/miu/22/circle_close_delete_-128.png"></img>
        </span>

        <form class="form">
            <p style="color: rgb(224, 207, 207);">Please select your position:</p>

            <input type="radio" id="customer" name="type" value="1" onclick="myFunction()" >
            <label style="color: rgb(224, 207, 207,.9);" for="customer">Customer</label>

            <input type="radio" id="taxiDriver" name="type" value="2" onclick="myFunction()">
            <label style="color: rgb(224, 207, 207,.9);" for="taxiDriver">Taxi Driver</label>

            <input type="radio" id="taxiOffice" name="type" value="3" onclick="myFunction()">
            <label style="color: rgb(224, 207, 207,.9);" for="taxiOffice">Taxi Office</label>
        </form>

    </div>

</body>

<script src="loginScript.js"></script>

</html>
