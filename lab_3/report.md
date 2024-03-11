<p>University: [ITMO University](https://itmo.ru/ru/)</p>
<p>Faculty: [FICT](https://fict.itmo.ru)</p>
<p>Course: [IP-telephony](https://github.com/itmo-ict-faculty/ip-telephony)</p>
<p>Year: 2023/2024 </p>
<p>Group: K34202</p>
<p>Author: Guliaeva Alisa</p>
<p>Lab: Lab2 </p>
<p>Date of create: 01.03.2024 </p>
<p>Date of finished: 12.03.2024</p>
<h1>Отчет по лабораторной №3</h1>
<h2>"Использование Asterisk в качестве SIP proxy."</h2>

<h3>Цель:</h3>
<p> Изучить программный комплекс Asterisk. Настройка Asterisk для локальных звонков.</p>

<h3>Ход работы:</h3>

<h4>Часть 1</h4>

<p>На виртуальной машине с ОС Ubuntu была выполнена установка Asterisk</p>
<img src='img/1.png' alt=''>
<p>В файл sip.conf была добавлена информация о телефонах</p>
<img src='img/2.png' alt=''>
<p>В файл extensions.conf была добавлена информация о типе канала</p>
<img src='img/3.png' alt=''>
<p>После настройки служба Asterisk была перезагружена и проверена</p>
<img src='img/4.png' alt=''>
<p>Подключились к CLI Asterisk, проверили созданные sip peers</p>
<img src='img/5.png' alt=''>
<p>В качестве soft-телефона устанавливили Zoiper5 с официального сайта, при входе были введены данные телефона 1000, localhost</p>
<img src='img/6.png' alt=''>
<img src='img/7.png' alt=''>

<p>Проверка подключения</p>
<img src='img/8.png' alt=''>

<p>Для проверки был выполнен тестовый звонок</p>
<img src='img/9.png' alt=''>

<h3>Вывод:</h3>
<p>В результате выполнения работы был изучен и настроен программный комплекс Asterisk.</p>
