<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>百度仿写</title>
    <style>
        * {
             margin: 0;
             padding: 0;
         }
             
         .top-img {
             width: 420px;
             height: 131px;
             background-color: pink;
             margin: 80px auto;
             background: url(https://www.baidu.com/img/PCtm_d9c8750bed0b3c7d089fa7d55720d6cf.png) no-repeat -60px -102px;
             zoom: .5;
         }
             
         .top-search {
             width: 680px;
             height: 45px;
             margin: 30px auto;
                
         }
             
         .search-box {
             display: flex;
             position: relative;
         }
             
         .search-left {
             width: 545px;
             height: 45px;
             border: 2px solid rgb(196, 199, 206);
             border-top-left-radius: 10px;
             border-bottom-left-radius: 10px;
             outline-color: rgb(78, 110, 242);
         }
             
         .icon-xiangji {
             position: absolute;
             right: 150px;
             top: 12px;
             font-size: 24px;
             color: rgb(196, 199, 206);
         }
             
         .search-right {
             color: #fff;
             font-size: 18px;
             width: 110px;
             height: 49px;
             border: 0px;
             border-top-right-radius: 10px;
             border-bottom-right-radius: 10px;
             background-color: rgb(78, 110, 242);
         }
     </style>
</head>
<body>
    <body>
        <div class="top-img"></div>
        <div class="top-search">
            <div class="search-box">
                <input type="text" name="search" class="search-left">
                <span class="iconfont icon-xiangji"></span>
                <input class="search-right" type="submit" name="btn" id="su" value='百度一下'>
            </div>
        </div>
    </body>
    
</body>
</html>
