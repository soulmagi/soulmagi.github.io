<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Konchok</title>
    <!-- <link rel="stylesheet" type="text/css" href="css/style.css" /> -->
    <style>
        *{
            padding: 0;
            margin: 0;
            font-family: "楷体";
        }
        header{
            background-image:linear-gradient(rgba(0,0,0,0.5),rgba(0,0,0,0.5)), url(https://images.pexels.com/photos/1083822/pexels-photo-1083822.jpeg?cs=srgb&dl=pexels-lisa-1083822.jpg&fm=jpg);
            height: 100vh;
            background-size: cover;
            background-position: center;
        }
    
        ul{
            float: right;
            list-style-type: none;
            margin: 15px;
        }
        ul li{
            display: inline-block;
        }
    
        ul li a{
            text-decoration: none;
            color: #fff;
            padding: 5px 20px;
            border: 1px solid transparent;
            transition: .6s ease;
            border-radius: 20px;
        }
    
        ul li a:hover{
            background-color: #fff;
            color: #000;
        }
        ul li.active a{
            background-color: #fff;
            color: #000;
        }
        .title{
            position: absolute;
            top:50%;
            left:50%;
            transform: translate(-50%,-50%);
        }
        .title h1{
            color: #fff;
            font-size: 70px;
            font-family: Century Gothic;
        }
    </style>
</head>
<body>
    <header>
        <div class="main">
            <ul>
                <li class="active"><a href="#">首页</a></li>
                <li><a href="http://www.baidu.com" target="_blank">百度</a></li>
                <li><a href="https://www.china.com" target="_blank">中华网</a></li>
                <li><a href="https://blog.csdn.net" target="_blank"><span style="color: crimson;">C</span>SDN官网</a></li>
                
            </ul>
        </div>
        <div class="title">
            <h1><span style="color: crimson;">My</span> Homepage</h1>
        </div>
    </header>
</body>
</html>
