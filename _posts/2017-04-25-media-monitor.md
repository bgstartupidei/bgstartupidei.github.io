---
layout: post
title:  "Скрипт, който показва най-срещаната дума по български медийни сайтове @elenko"
date:   2017-04-25 17:02:00 +0200
categories: проекти
---

<blockquote class="twitter-tweet" data-lang="en"><p lang="bg" dir="ltr">Скрипт, който показва коя е най-често срещаната дума по всички бг медии на 1 страница като дашборд <a href="https://twitter.com/hashtag/%D0%B1%D0%B3%D1%81%D1%82%D0%B0%D1%80%D1%82%D1%8A%D0%BF%D0%B8%D0%B4%D0%B5%D0%B8?src=hash">#бгстартъпидеи</a></p>&mdash; Elenko (@elenko) <a href="https://twitter.com/elenko/status/856519330837778432">April 24, 2017</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

Пилотен проект, камикадзе [Медия дашборд](http://media-dashboard.bgstartupidei.com/).

![Media Dashboard](/images/media-dashboard.png)

Кодът е достъпен на [https://github.com/bgstartupidei/media-dashboard](https://github.com/bgstartupidei/media-dashboard).

**Backend**: един `PHP` файл, който сваля и анализира данните

**Frontend**: `HTML` и `JS`, който зарежда `JSON` данните. `underscore` за шаблони и `jQuery` Slim за закачане по DOM.

Данните се генерират всеки час от 7 до 22 а `JSON` файловете се архивират в data с име текущите дата и час.

Възможности за развитие:
* промяна на позицията на дума спрямо предишния час
* highlight на дума във всички колони
* по-добър анализ на страниците (само частите с новините)
