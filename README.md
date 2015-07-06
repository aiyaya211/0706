# 0706
css星空 原文网址 http://www.w3cfuns.com/blog-5466589-5406909.html 作者:jie4038
<!DOCTYPE html>
<html>
<head>
  <meta http-equiv="Content-Type" content="text/html;charset=utf-8" >
  <title>A beautiful night</title>
  <style type="text/css">
    html{margin:0; padding:0;}
    body{margin:0; padding:0; height:100%; font-family:"Brush Script MT"; font-size:12px; color:#666; background:black; }
    /*背景*/
    .main{height:800px; position:relative;}
    .linear{
   FILTER:progid:DXImageTransform.Microsoft.Gradient(gradientType=0,startColorStr=#000,endColorStr=#00002F); 
   background: -ms-linear-gradient(top, #000,  #00002F);
   background:{position:absolute; top:0; left:0; width:100%; height:100%; z-index:98;}
   .star{position: absolute; top: 0; left: 0; width: 100%; height: 100%; z-index: 98;}
   .star>div{position: absolute; }
   .star>div:nth-child(5n){ width:2px; height: 2px; border-radius: 2px; background:#ddd; -webkit-animation:shine 1s linear 1s     infinite; animation:shine 1s linear 1s infinite;}
   .star>div:nth-child(5n+1){ width:4px; height: 4px; border-radius: 4px; background:#fff; -webkit-animation:shine 1s linear    2s infinite; animation:shine 1s linear 2s infinite;}
   .star>div:nth-child(5n+2){ width:2px; height: 2px; border-radius: 2px; background:#fff; -webkit-animation:shine 1s linear    3s infinite; animation:shine 1s linear 3s infinite;}
   .star>div:nth-child(5n+3){ width:4px; height: 4px; border-radius: 4px; background:#fff; -webkit-animation:shine 1s linear    1.5s infinite; animation:shine 1s linear 1.5s infinite;}
   .star>div:nth-child(5n+4){ width:1px; height: 1px; border-radius: 2px; background:#fff; -webkit-animation:shine 1s linear    2.5s infinite; animation:shine 1s linear 2.5s infinite;}
   .star>div:nth-child(1){top: 20%; left: 80%;}
   .star>div:nth-child(2){top: 30%; left: 20%;}
   .star>div:nth-child(3){top: 50%; left: 40%;}
   .star>div:nth-child(4){top: 70%; left: 50%;}
   .star>div:nth-child(5){top: 10%; left: 60%;}
   .star>div:nth-child(6){top: 20%; left: 30%;}
   .star>div:nth-child(7){top: 30%; left: 10%;}
   .star>div:nth-child(8){top: 40%; left: 50%;}
  .star>div:nth-child(9){top: 60%; left: 10%;}
  .star>div:nth-child(10){top: 10%; left: 50%;}
  .star>div:nth-child(11){top: 40%; left: 30%;}
  .star>div:nth-child(12){top: 70%; left: 20%;}
  .star>div:nth-child(13){top: 20%; left: 40%;}
  .star>div:nth-child(14){top: 40%; left: 70%;}
  .star>div:nth-child(15){top: 60%; left: 60%;}
  .star>div:nth-child(16){top: 20%; left: 40%;}
  .star>div:nth-child(17){top: 50%; left: 95%;}
  .star>div:nth-child(18){top: 70%; left: 20%;}
  .star>div:nth-child(19){top: 20%; left: 40%;}
  .star>div:nth-child(20){top: 65%; left: 15%;}
  .star>div:nth-child(21){top: 35%; left: 55%;}
  .star>div:nth-child(22){top: 75%; left: 65%;}
  .star>div:nth-child(23){top: 25%; left: 25%;}
  .star>div:nth-child(24){top: 45%; left: 90%;}
  .star>div:nth-child(25){top: 25%; left: 75%;}
  .star>div:nth-child(26){top: 75%; left: 75%;}
  .star>div:nth-child(27){top: 45%; left: 65%;}
  .star>div:nth-child(28){top: 25%; left: 35%;}
  .star>div:nth-child(29){top: 65%; left: 55%;}
  .star>div:nth-child(30){top: 55%; left: 45%;}
  .star>div:nth-child(31){top: 75%; left: 75%;}
  .star>div:nth-child(32){top: 25%; left: 25%;}
  .star>div:nth-child(33){top: 35%; left: 85%;}
  .star>div:nth-child(34){top: 35%; left: 45%;}
  .star>div:nth-child(35){top: 15%; left: 25%;}
  .star>div:nth-child(36){top: 55%; left: 45%;}
  .star>div:nth-child(37){top: 75%; left: 55%;}
  .star>div:nth-child(38){top: 25%; left: 55%;}
  .star>div:nth-child(39){top: 55%; left: 65%;}
  .star>div:nth-child(40){top: 65%; left: 25%;}
@-webkit-keyframes shine{0%{opacity:0.5} 100%{opacity: 1}}
@keyframes shine{0%{opacity:0.5} 100%{opacity: 1}}
/*月亮*/
.moon{ position: absolute; top:6%; left: 10% ;width: 200px; height: 200px; border-radius: 200px; background:#fff;z-index: 99 ;}
.shadow{-moz-box-shadow:0 0 100px #fff;  -webkit-box-shadow:0 0 100px #fff;  box-shadow:0 0 100px #fff;}
/*房子*/
.house{ position: absolute;bottom: 0; left: 20%;width:300px; height: 160px; }
.house .roof{position: absolute; top: 0; left: 0; width: 0; height: 0;border-left: 150px solid transparent; border-right: 150px solid transparent;border-bottom: 100px solid black;}
.house .wall{position: absolute; bottom: 0; left:50px; width: 200px; height: 80px; background: black;}
.house .chimney{position: absolute; top: 10px; left:200px; width: 30px; height: 80px; background: black;}
.house .window{position: absolute; top: 100px; left:130px; width: 40px; height: 40px; background: yellow;}
.house .window::before{position: absolute; top: 50%; left: 0 ;content:"";width:40px; height:1px; background:#999;}
.house .window::after{position: absolute; top: 0; left: 50% ;content:"";width:1px; height:40px; background:#999;}
   
  </style>
  </head>
  <body>
   <h2>This is a beautiful night</h2>
   <div class="main linear">
   <div class="moon shadow"></div>
   <div class="star">
    <!--10-->
     <div></div>
     <div></div>
     <div></div>
     <div></div>
     <div></div>
     <div></div>
     <div></div>
     <div></div>
     <div></div>
     <div></div>
    <!--20-->
     <div></div>
     <div></div>
     <div></div>
     <div></div>
     <div></div>
     <div></div>
     <div></div>
     <div></div>
     <div></div>
     <div></div>
     <!--30-->
     <div></div>
     <div></div>
     <div></div>
     <div></div>
     <div></div>
     <div></div>
     <div></div>
     <div></div>
     <div></div>
     <div></div>
    <!--40-->
     <div></div>
     <div></div>
     <div></div>
     <div></div>
     <div></div>
     <div></div>
     <div></div>
     <div></div>
     <div></div>
     <div></div>
    </div>
    <div class="house">
       <div class="roof"></div>
       <div class="wall"></div>
       <div class="chimney"></div>
       <div class="window"></div>
    </div>
  </div>
  </body>
