
   

<html lang="en">
    <head> 
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE-edge">
    <meta name="viewport" content="width-device-width, initial-scale-1.0">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.1.1/css/fontawesome.min.css" integrity="sha384-zIaWifL2YFF1qaDiAo0JFgsmasocJ/rqu7LKYH8CoBEXqGbb9eO+Xi3s6fQhgFWM" crossorigin="anonymous">
    
    <script src="http://kit.fontawesome.com/54f0cb7e4a.js" crossorigin="amonyus"></script>
    <link rel="stylesheet" href="style.css">
    <title>web cá nhân</title>
    <html>
    </head>
    <body>
        <header>
            <div class="top">
                <div class="container">
                    <div class="header-top row">
                        <p>Huỳnh Trung Hậu</p>
                        <ul>
                            
                                <i class='fa fa-graduation-cap' style='color:#4448ca'></i>  
                            
                        </ul>
                        <i class="fas fa-facebook-f"></i>
                        <ul>
                            <li><a href="index3.html">thông tin cá nhân</a></li>                                                       
                            <li><a href="index7.html">web học tập</a></li>                                                       
                        </ul>
                       
                    </div>
                </div>
           
            <div class="topnav">
                <a class="active" href="index12.html">Trang chủ</a>
                <a href="index7.html">website </a>
                <a href="index3.html">Liên hệ</a>
                <input type="text" placeholder="Tìm kiếm..."/>
              </div>
         
         
            <div class="header-text">              
                 
            </div>
           </header>
        <body>
            <content>        
        <div id="box">
        <div class="box">
      <img src="https://ngayhevang.vn/wp-content/uploads/2021/03/thap-tram-huong-nha-trang-5.jpg" alt="ngayhevang.vn" width="250" height="200">
    <div class="section-box">
        <img src="http://thuvienhinhanh.net/wp-content/uploads/2016/05/hinh-anh-dep-ve-nha-trang-thanh-pho-bien.jpg" alt="" width="250" height="150">
    </div>
    </div>
    </div> 
            </content>
            
        </body>

  

   </div>
   </div>      
    <main>
       <!-- cuối -->
  <div id="footer">
   <div class="box">
       <div class="logo"> <h1 style="font-size: 15px;">HUỲNH TRUNG HẬU </h1> </div>
   </div>
   <div class="box">
       <h3>NỘI DUNG</h3>
       <ul class="quick-menu">
           <div class="item">
               <a href="huynhtrunghau2703/huynhtrunghau2703.github.io">Trang chủ</a>
           </div>
           <div class="item">
               <a href="https://www.facebook.com/hau.huynhtrung.2703/   ">Giới Thiệu</a>
           </div>
           <div class="item">
               <a href="mailto:huynhhau.0703349507@gmail.com">Liên hệ</a>
           </div>
       </ul>
   </div>
   <div class="box">
       <h3>LIÊN HỆ</h3>
       <form action="">
         <address>Huỳnh Trung Hậu<br />
            Email: <a href="mailto:hthau27@gmail.com">hthau27@gmail.com</a><br />
            Địa chỉ: Xã suối hiệp huyện Diên Khánh Tỉnh Khánh hòa<br />
            Điện thoại: (+84)167128874</address>
       </form>
   </div>
   <div class="box-text">
       <h4>Mạng Xã Hội</h4>
      <div>
          <ul>
            <i class='fa fa-facebook'></i>
            <i class='fa fa-instagram'></i>
            
          </ul>
      </div>
   </div>
</div>
</div>
<!-- cuối -->
    </main>
</html>
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
     .body {
            background-color: darkseagreen;
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
        background-color: darkseagreen;
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
    * {box-sizing: border-box;}
 
body {
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
}
 
.topnav {
  overflow: hidden;
  background-color: #e9e9e9;
}
 
.topnav a {
  float: left;
  display: block;
  color: black;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}
 
.topnav a:hover {
  background-color: #ddd;
  color: black;
}
 
.topnav a.active {
  background-color: #2196F3;
  color: white;
}
 
.topnav input[type=text] {
  float: right;
  padding: 6px;
  margin-top: 8px;
  margin-right: 16px;
  border: none;
  font-size: 17px;
}
 
@media screen and (max-width: 600px) {
  .topnav a, .topnav input[type=text] {
    float: none;
    display: block;
    text-align: left;
    width: 100%;
    margin: 0;
    padding: 14px;
  }
  .topnav input[type=text] {
    border: 1px solid #ccc;  
  }
}
.fa {
    padding: 20px;
    font-size: 30px;
    width: 20px;
    text-align: center;
    text-decoration: none;
    margin: 5px 2px;
    border-radius: 50%;
}
 /* cuối */
 #footer {
      width: 100%;
      background:#696969;
      height: 322px;
      margin-top:0px;
      padding-top:57px;
      display: flex;
      justify-content: space-around;
  }
  
  #footer .box {
      width: 250px;
      color: #fff;
  }
  
  #footer .box .quick-menu {
      margin-top:40px;
  
  }
  
  
  #footer .box .quick-menu .item{
      margin-bottom:12px;
  
  }
  #footer .box .quick-menu ,.item a{
      color:#fff;
      text-decoration: none;
  }
  
  
  
  #footer .box form input {
      width: 294px;
      height: 42px;
      background:transparent;
      padding-left:20px;
      color:#fff;
      margin-top:30px;
  }
  
  #footer .box form button {
      background:#362f2f;
      box-shadow: 5px 5px 4px rgba(0,0,0.25);
      width: 163px;
      height: 38px;
      margin-top:29px;
      color:#fff;
  } 
  .box-text {
    color: #063970;
  }
  .ection {
      background-color: whitesmoke;
  }
 
        </style>
    </head>
    
