<!DOCTYPE html>
<html lang="en">
<head> 
<meta charset="UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE-edge">
<meta name="viewport" content="width-device-width, initial-scale-1.0">
<script src="http://kit.fontawesome.com/54f0cb7e4a.js" crossorigin="amonyus"></script>
<link rel="stylesheet" href="style.css">
<title>web cá nhân</title>
</head>
<body>
    <header>
        <div class="top">
            <div class="container">
                <div class="header-top row">
                    <p>Huỳnh trung Hậu</p>
                    <ul>
                        <i class="fa-solid fa-circle-xmark"></i>
                        <li><a href="index3.html">thông tin cá nhân</a></li>                         
                                         
                        <li><a href="index7.html">web học tập</a></li>                                                       
                    </ul>
                    <i class="fas fa-bars"></i>
                </div>
            </div>
        </div>
        <div class="a1-image">

        </div>
        <div class="header-text">
             <h1>đây là trang web cá nhân của tôi</h1>
             <p>hãy liên hệ tôi để biết thêm thông tin</p>
             <button>nhấn vào liên hệ </button>
        </div>

    
    </header>
</body>
<head>
    <style>@import url('https://fonts.googleapis.com/css2?family=Roboto+Mono&display=swap');
        @import url('https://fonts.googleapis.com/css2?family=Roboto+Mono:ital,wght@0,400;1,200&display=swap');
        :root {
            --main-text-font:'Roboto', sans-serif;
            --logo-text-font:'Roboto Mono', monospace;
            --main-color: #063970;
        }
        body {
            background-image: url(https://tse4.mm.bing.net/th?id=OIP.WqNgq6Q5szSQM1nwCuE9EQHaFj&pid=Api&P=0&w=220&h=165);
            background-size: cover;
        }
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        a {
            text-decoration: none;
        }
        li {
            list-style: none;
        }
        .container {
            max-width: 1024px;
            margin: auto;
        }
        .row {
            display: flex;
            flex-wrap: wrap;
        }
        header {
            background-image: url("");
            ackground-position: center;
            background-repeat: no-repeat;
            background-size: cover;
           /width: 100vw;
            height: 100vh;
        }
        .navy-image {
            position: absolute;
            content: "";
            width: 100%;
            height: 100%;
            background-color: blue;
            opacity: 0.5;
        }
        .top {
            position: relative;
            width: 100%;
            z-index: 1;
        }
        .header-top p {
            font-family: var(--logo-text-font);
            font-size: 25px;
            letter-spacing: 2px;
            color: var(--main-color);
            font-weight: bold;
        }
        .header-top p span {
            font-size: 20px;
        }
        .header-top {
            justify-content: space-between;
            padding: 12px 0;
            align-items: center;
        }
        .header-top ul {
            display: flex;
        }
        .header-top ul li {
            margin-left: 12px;
            position: relative;
        }
        .header-top ul li::after {
            position: relative;
            content: "";
            display: block;
            bottom: -2px;
            height: 3px;
            width: 0%;
            left: 50%;
            transform: translate(-50%);
            background-color: var(--main-color);
            border-radius: 5px;
            transition: all 0.5s ease;
        }
        .header-top ul li:hover::after {
            width: 100%;
        
        }
        .header-top ul li a {
            font-family: var(--main-text-font);
            color: #063970;
            font-weight: bold;
        }
        .header-top ul i {
            font-size: 32px;
            color: white;
            margin: 12px 0 0 12px;
            cursor: pointer;
            margin-bottom: 150px;
        }
        .header-top> i {
            font-size: 32px;
            color: var(--main-color);
            cursor: pointer;
        }
        .header-top p {
            font-family: var(--logo-text-font);  
        }
        .header-text {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%,-50%);
            max-width: 1200px;
            min-width: 668px;
            text-align: center;
        }
        .header-text h1 {
            font-family: var(--main-text-font);
            color: #063970;
            margin-bottom: 20px;
            font-size: 32px;
        }
        .header-text p {
            font-family: var(--main-text-font);
            color: #063970;
        }
        .header-text button {
            width: 150px;
            height: 60px;
            margin-top: 20px;
            background-color: transparent;
            border: 2px solid var(--main-color);
            color: #063970
            cursor: pointer;
            font-size: 20px;
            transition: all 0.5s ease;
        }
        .header-text button:hover {
            background-color: var(--main-color);
        }
        @media (max-width: 575px) {
            .header-top ul {
                position: fixed;
                width: 200px;
                height: 100px;
                background-color: var(--main-color);
                right: 0;
                top: 0;
                flex-direction: column  ;
            }
            .header-top ul li {
                margin-bottom: 20px;
                margin-left: 50px;
            }
        }   </style>
</head>
<head>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Roboto+Mono&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Roboto+Mono:ital,wght@0,400;1,200&display=swap');
:root {
    --main-text-font:'Roboto', sans-serif;
    --logo-text-font:'Roboto Mono', monospace;
    --main-color: #063970;
}
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
a {
    text-decoration: none;
}
li {
    list-style: none;
}
.container {
    max-width: 1024px;
    margin: auto;
}
.row {
    display: flex;
    flex-wrap: wrap;
}
header {
    background-image: url("image/navy.jpg");
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    width: 100vw;
    height: 100vh;
}
/*.navy-image {
    position: absolute;
    content: "";
    width: 100%;
    height: 100%;
    background-color: blue;
    opacity: 0.5;*/
}
.top {
    position: relative;
    width: 100%;
    z-index: 1;
}
.header-top p {
    font-family: var(--logo-text-font);
    font-size: 25px;
    letter-spacing: 2px;
    color: var(--main-color);
    font-weight: bold;
}
.header-top p span {
    font-size: 20px;
}
.header-top {
    justify-content: space-between;
    padding: 12px 0;
    align-items: center;
}
.header-top ul {
    display: flex;
}
.header-top ul li {
    margin-left: 12px;
    position: relative;
}
.header-top ul li::after {
    position: relative;
    content: "";
    display: block;
    bottom: -2px;
    height: 3px;
    width: 0%;
    left: 50%;
    transform: translate(-50%);
    background-color: var(--main-color);
    border-radius: 5px;
    transition: all 0.5s ease;
}
.header-top ul li:hover::after {
    width: 100%;

}
.header-top ul li a {
    font-family: var(--main-text-font);
    color: #063970;
    font-weight: bold;
}
.header-top ul i {
    font-size: 32px;
    color: white;
    margin: 12px 0 0 12px;
    cursor: pointer;
    margin-bottom: 150px;
}
.header-top> i {
    font-size: 32px;
    color: var(--main-color);
    cursor: pointer;
}
.header-top p {
    font-family: var(--logo-text-font);  
}
.header-text {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
    max-width: 700px;
    min-width: 500px;
    text-align: center;
}
.header-text h1 {
    font-family: var(--main-text-font);
    color: #063970;
    margin-bottom: 20px;
    font-size: 32px;
}
.header-text p {
    font-family: var(--main-text-font);
    color: #063970;
}
.header-text button {
    width: 150px;
    height: 40px;
    margin-top: 20px;
    background-color: transparent;
    border: 2px solid var(--main-color);
    color: #063970
    cursor: pointer;
    font-size: 20px;
    transition: all 0.5s ease;
}
.header-text button:hover {
    background-color: var(--main-color);
}
@media (max-width: 575px) {
    .header-top ul {
        position: fixed;
        width: 200px;
        height: 100px;
        background-color: var(--main-color);
        right: 0;
        top: 0;
        flex-direction: column  ;
    }
    .header-top ul li {
        margin-bottom: 20px;
        margin-left: 50px;
    }
}  
    </style>
</head>
