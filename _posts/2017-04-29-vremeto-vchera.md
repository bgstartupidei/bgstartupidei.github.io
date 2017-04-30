---
layout: post
title:  "App,  който да показва какво е било времето вчера @iapostolov"
date:   2017-04-29 09:49:00 +0200
categories: проекти
image: vremeto-vchera.png
---

<blockquote class="twitter-tweet" data-lang="en"><p lang="bg" dir="ltr">App, който показва и какво е било времето вчера, за да сравниш докато се обличаш <a href="https://twitter.com/hashtag/%D0%B1%D0%B3%D1%81%D1%82%D0%B0%D1%80%D1%82%D1%8A%D0%BF%D0%B8%D0%B4%D0%B5%D0%B8?src=hash">#бгстартъпидеи</a></p>&mdash; Ivo Apostolov (@iapostolov) <a href="https://twitter.com/iapostolov/status/851710431492263937">April 11, 2017</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>


[Времето вчера](http://vremeto-vchera.bgstartupidei.com) е Вашият нов надежден източник на остаряла информация.

Революционна технология, която помага да погледнем в миналото.

![Времето вчера](/images/vremeto-vchera.png)

Кодът е достъпен на [https://github.com/bgstartupidei/vremeto-vchera](https://github.com/bgstartupidei/vremeto-vchera).

**Backend**: bash script (sed + curl)

**Frontend**: `HTML` и `JS`, който зарежда `JSON` данните. `underscore` за шаблони и `jQuery` Slim за закачане по DOM.

Данните се генерират на всеки кръгъл час.
