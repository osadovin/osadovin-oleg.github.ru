!DOCTYPE html>
<html lang="ru">
<head>
    <title>Тестовая страница</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.5.0/css/font-awesome.min.css">
    <link rel="icon" href="/img/fav/favicon-32x32.png">
    <link rel="stylesheet" type="text/css" href="../css/main.css">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <style>
 
        
        .row {
            display: flex;
            flex-wrap: wrap;
        }
        
        .side {
            flex: 30%;
            background-color: #f1f1f1;
            padding: 20px;
        }
        
        .main {
            flex: 70%;
            background-color: white;
            padding: 20px;
        }
        
        .fakeimg {
            background-color: #aaa;
            width: 100%;
            padding: 2px;
        }
        
       
        
        @media screen and (max-width: 600px) {
            .row .navbar {
                flex-direction: column;
            }
        }
     </style>
</head>
<body>
<!-- Header -->
<div class="header">
    <h1>Мое портфолио</h1>
    <p>Веб сайт построен с <b>использованием</b> технологий<br> HTML и CSS</p>
    </div>

<!-- Навигационное меню -->

<div class="navbar">
    <a href="#" class="nv-active">Главная</a>
    <a href="/pages/page1.html">Галерея</a>
    <a href="#">Проекты</a>
    <a href="#">Контакты</a>
    </div>
    
<!-- Основной блок -->
<div class="row">
    <div class="side">
    <h2>Обо мне</h2>
    <h4>Умею делать верстку CSS и программировать на языке JavaScript </h4>
    <div class="fakeimg"><img src="img/AZ8.jpg" style="width: 100%;"></div>
    <p>Немного текста обо мне</p>
    <h3>Основные проекты</h3>
    <p>Название</p>
    <div class="fakeimg" style="height: 60px;">Картинка</div><br>
    <p>Название</p>
    <div class="fakeimg" style="height: 60px;">Картинка</div><br>
    <p>Название</p>
    <div class="fakeimg" style="height: 60px;">Картинка</div><br>
   </div>
   <div class="main">
    <h2>Опыт работы</h2>
    <h4>ООО "Рога и копыта", январь 2000 - декабрь 2005</h4>
    <div class="fakeimg" style="height: 200px;">Картинка</div>
    <p>Название должности</p>
    <p>Описание лалалалалаллалалалалалалалалаа</p>
    <br>
    <hr width="100%" size="2" color="blue noshade">
    <h2>Опыт работы</h2>
    <h4>ООО "Рога и копыта", январь 2000 - декабрь 2005</h4>
    <div class="fakeimg" style="height: 200px;">Картинка</div>
    <p>Название должности</p>
    <p>Описание лалалалалаллалалалалалалалалаа</p>   
    </div> 
</div>
