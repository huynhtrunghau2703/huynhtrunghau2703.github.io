
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
                        <p>Huỳnh Trung Hậu</p

                        <i class="fas fa-facebook-f"></i>
                        <ul>
                            <i class="fa-solid fa-circle-xmark"></i>
                            <li><a href="index3.html">thông tin cá nhân</a></li>                                                            
                            <li><a href="index7.html">web học tập</a></li>                                                       
                        </ul>
                      
                    </div>
                </div>
            </div>
            <div class="a1-image">
    
            </div>
            <div class="header-text">
                       

                 
            </div>
            <div class="topnav">
                <a class="index.html" href="index.html">Trang chủ</a>
                <a href="index7.html">website </a>
                <a href="in">Liên hệ</a>
                <input type="text" placeholder="Tìm kiếm..."/>
              </div>
        </header>
        
           <footer>
     <div class="container">
         <!--Bắt Đầu Nội Dung Giới Thiệu-->
         <div class="noi-dung about">
            
             
             <ul class="social-icon">
                 <li><a href=""><i class="fa fa-facebook"></i></a></li>
                 <li><a href=""><i class="fa fa-twitter"></i></a></li>
                 <li><a href=""><i class="fa fa-instagram"></i></a></li>
                 <li><a href=""><i class="fa fa-youtube"></i></a></li>
             </ul>
         </div>
         <!--Kết Thúc Nội Dung Giới Thiệu-->
         <!--Bắt Đầu Nội Dung Đường Dẫn-->
         <div class="noi-dung links">
             <h2>Đường Dẫn</h2>
             <ul>
                 <li><a href="index.html">Trang Chủ</a></li>
                 <li><a href="#">Về Chúng Tôi</a></li>
                 
             </ul>
         </div>
         <!--Kết Thúc Nội Dung Đường Dẫn-->
         <!--Bắt Đâu Nội Dung Liên Hệ-->
         <div class="noi-dung contact">
             <h2>Thông Tin Liên Hệ</h2>
             <ul class="info">
                 <li>
                     <span><i class="fa fa-map-marker"></i></span>
                     <span>thôn phú hậu<br />
                         xã suối hiệp Diên Khánh Khánh Hòa<br />
                         Việt Nam</span>
                 </li>
                 <li>
                     <span><i class="fa fa-phone"></i></span>
                     <p><a href="#">0764128874</a>
                         <br />
                         <a href="#">+84 987 654 321</a></p>
                 </li>
                 <li>
                     <span><i class="fa fa-envelope"></i></span>
                     <p><a href="#">hthau27@gmail.com</a></p>
                </li>
                 <li>
                     <form class="form">
                         <input type="email" class="form__field" placeholder="Đăng Ký Subscribe Email" />
                         <button type="button" class="btn btn--primary  uppercase">Gửi</button>
                     </form>
                 </li>
             </ul>
         </div>
         <!--Kết Thúc Nội Dung Liên Hệ-->
     </div>
 </footer>
               
        
        
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
                background-color: lightgreen;
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
.footer {
          background-color: burlywood;
           

     .footer .container .noi-dung{
     margin-right: 30px;
 }
 
.footer  .container .noi-dung.about{
     width:40%;
 }
 .footer .container .noi-dung.about h2{
     position: relative;
     color: #fff;
     font-weight: 500;
     margin-bottom: 15px;
 }
 .footer .container .noi-dung.about h2:before{
     content: '';
     position: absolute;
     bottom: -5px;
     left: 0;
     width: 50px;
     height: 2px;
     background: #f00;
 }
.footer .container .noi-dung.about p{
     color: #999;
 }
 /*Thiết Lập Cho Thành Phần Icon Mạng Xã Hội*/
 .social-icon{
     margin-top: 20px;
     display: flex;
 }
.social-icon li {
     list-style: none;
 }
 .social-icon li a{
     display: inline-block;
     width: 40px;
     height: 40px;
     background: #222;
     display: flex;
     justify-content: center;
     align-items: center;
     margin-right: 10px;
     text-decoration: none;
     border-radius: 4px;
 }
.social-icon li a:hover{
     background: #f00;
 }
.social-icon li a .fa{
     color: #fff;
     font-size: 20px;
 }
.links h2{
     position: relative;
     color: #fff;
     font-weight: 500;
     margin-bottom: 15px;
 }
.links h2{
     position: relative;
     color: #fff;
     font-weight: 500;
     margin-bottom: 15px;
 }
.links h2::before{
     content: '';
     position: absolute;
     bottom: -5px;
     left: 0;
     width: 50px;
     height: 2px;
     background: #f00;
 }
.links{
    position: relative;
    width: 25%;
 }
 .links ul li{
     list-style: none;
 }
 .links ul li a{
     color: #999;
     text-decoration: none;
     margin-bottom: 10px;
     display: inline-block;
 }
.links ul li a:hover{
     color: #fff;
 }
 .contact h2{
     position: relative;
     color: #fff;
     font-weight: 500;
     margin-bottom: 15px;
 }
.contact h2::before{
     content: '';
     position: absolute;
     bottom: -5px;
     left: 0;
     width: 50px;
     height: 2px;
     background: #f00;
 }
.contact{
     width: calc(35% - 60px);
     margin-right: 0 !important;
 }
.contact .info{
     position: relative;
 }
 .contact .info li{
     display: flex;
     margin-bottom: 16px;
 }
 .contact .info li span:nth-child(1) {
     color: #fff;
     font-size: 20px;
     margin-right: 10px;
 }
.contact .info li span{
     color: #999;
 }
.contact .info li a{
     color: #999;
     text-decoration: none;
 }
 .btn {
     display: inline-block;
     background: transparent;
     color: inherit;
     font: inherit;
     border: 0;
     outline: 0;
     padding: 0;
     margin-top:16px;
     transition: all 200ms ease-in;
     cursor: pointer;
 }
 .btn--primary {
     background: #222;
     color: #fff;
     box-shadow: 0 0 10px 2px rgba(0, 0, 0, .1);
     border-radius: 2px;
     padding: 8px 24px;
 }
 .btn--primary:hover {
     background: #f00;
 }
 .btn--primary:active {
     background: #f00;
     box-shadow: inset 0 0 10px 2px rgba(0, 0, 0, .2);
 }
.form__field {
     width: 90%;
     background: #fff;
     color: #a3a3a3;
     font: inherit;
     box-shadow: 0 6px 10px 0 rgba(0, 0, 0, .1);
     border: 0;
     outline: 0;
     padding: 8px 4px;
 }
 @media  (max-width: 768px){
     .footer{
         padding: 40px;
              }
    . footer .container{
         flex-direction: column;
     }
     .footer .container .noi-dung{
         margin-right: 0;
         margin-bottom: 40px;
     }
     .footer .container, .noi-dung.about, .links, .contact{
         width: 100%;
     }
 }
              </style>
    </head>
    
