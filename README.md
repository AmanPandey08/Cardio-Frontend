# Cardio-Frontend

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anshul Cardio Centre</title>
</head>
<link href="https://fonts.googleapis.com/css?family=Baloo+Bhai&display=swap" rel="stylesheet">
<link rel="stylesheet" href="css/style.css">
<style>
    body {
        font-family: 'Baloo Bhai', cursive;
        margin: 0px;
        padding: 0px;
        background-image: url(https://www.usainteanne.ca/cache/images/_DR28524_26048.jpg);
    }

    .left {
        display: inline-block;

        position: absolute;
        top: 20px;
        left: 20px;
        width: 100px;
    }

    .mid {

        display: block;
        width: 33%;
        margin: 20px auto;
    }

    .right {
        font-family: 'Baloo Bhai', cursive;
        display: inline-block;

        position: absolute;
        top: 29px;
        right: 20px;

    }

    .btn {
        font-family: 'Baloo Bhai', cursive;
        padding: 3px 14px;
        background-color: black;
        color: antiquewhite;
        margin: 0px 9px;
        border: 2px solid gray;
        border-radius: 6px;
        font-size: 15px;
    }

    .btn:hover {
        color: yellowgreen;
        text-decoration: underline;
        background-color: rgb(22, 22, 21);
    }

    .navbar {
        display: inline-block;
        width: 124%;
    }

    .navbar li {
        display: inline-block;
        padding: 5px;
        font-size: 19px;

    }

    .navbar li a {
        color: white;
        text-decoration: none;
    }

    .navbar li a:hover {
        color: gray;
        text-decoration: underline;
    }

    .left img {
        width: 87px;
    }

    .left div {
        width: 10%;
        line-height: 10px;
        text-align: center;
        top: 60px;
        left: 9px;
        position: absolute;
        color: #ddceb8;

    }

    .container {

        margin: 100px 100px;
        padding: 5px 0px;
        width: 90%;
        border-radius: 2px;
        text-align: center;
    }

    .container h1 {
        color: rgb(10 122 70);
    }

    .container button {
        font-family: 'Baloo Bhai', cursive;
        width: 320px;
        border-radius: 8px;
    }

    .formgrp input {
        font-family: 'Baloo Bhai', cursive;
        text-align: center;
        display: block;
        width: 300px;
        padding: 10px;
        border: 2px solid black;
        border-radius: 6px;
        margin: 3px auto;
    }
</style>

<body>
    <div class="left">
        <img src="https://dcassetcdn.com/design_img/3604321/574634/574634_19768052_3604321_f511501e_image.png" alt="">
        <div>Anshul Cardio</div>
    </div>
    <div class="mid">
        <ul class="navbar">
            <li> <a href="#" class="active">Home</a></li>
            <li> <a href="#">About us</a> </li>
            <li> <a href="#">Registration Form</a></li>
            <li> <a href="#">Contact Us</a></li>
        </ul>
    </div>
    <div class="right">
        <button class="btn">Call us now</button><button class="btn">Email us</button>
    </div>
    <div class="container">
        <h1>Join the best cardio Centre of Chandigarh</h1>
        <form action="anshul.php">
            <div class="formgrp">
                <input type="text" name="" placeholder="Enter Your name">
            </div>
            <div class="formgrp">
                <input type="text" name="" placeholder="Enter Your age">
            </div>
            <div class="formgrp">
                <input type="text" name="" placeholder="Enter Your Gender">
            </div>
            <div class="formgrp">
                <input type="text" name="" placeholder="Enter Your Nearest landmark">
            </div>
            <div class="formgrp">
                <input type="text" name="" placeholder="Enter Your Contact no.">
            </div>
            <button class="btn">Submit</button>
        </form>
    </div>
</body>

</html>
