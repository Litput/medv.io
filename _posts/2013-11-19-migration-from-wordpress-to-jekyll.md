---
layout: post
title: Переход от WordPress к Jekyll
published: true
---

Решил обновить свой блог и перейти от использования WordPress к [Jekyll](http://jekyllrb.com/). 

Как оказалось сделать это было достаточно просто (если бы не парочка новых багов в jekyll на данный момент). Для переноса постов есть куча импортеров (я воспользовался каким-то написанным на C#). 

<img src="http://instacod.es/file/83363" class="center" style="max-width: 200px;">

Самое сложное было перейти к использованию для подсветки кода `pygments`. Пришлось вручную заменить все теги на новые.

Код моего блога доступен [тут](https://github.com/elfet/elfet.github.io).

Для проверки того что блог будет успешно собираться, подключил Travis-CI. Почему-то GitHub в случае ошибки не присылает само сообщение об ошибке и непонятно что именно сломалось. 

Так же обновил дизайн блога на более простой и лаконичный. Кстати, фото Сатурна [настоящее](http://www.nasa.gov/mission_pages/cassini/whycassini/jpl/cassini20131112.html#.UovVJmTuiWU). 
<!--more-->

А так же всем советую попробовать [prose.io](http://prose.io) - приложение для редактирования контента GitHub репозитория прямо в браузере, очень удобно для управления сайтом на GitHub Pages. 