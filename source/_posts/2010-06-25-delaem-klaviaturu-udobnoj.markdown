---
layout: post
title: Делаем клавиатуру удобной
keywords: keyboard,tips,tricks
date: 2010-06-25 00:00
tags:
- tips
---
В то время, когда я использовал emacs, на глаза очень часто попадались статьи, посвященные переопределению клавиш. Основная задача - это перенесение клавиши Ctrl, которая используется чаще всего, в более удобное место на клавиатуре. В основном переназначают CapsLock на функцию Ctrl. Да, это гораздо удобнее, чем мизинцем тянуться влево и вниз. В данном случае Ctrl оказывается практически под самим мизинцем.

А недавно я задумался, как часто используется та или иная функциональная клавиша в программах, которые мы используем повседневно? По какому принципу выбирали ее местоположение?? А может есть возможность сделать клавиатуру более удобной??

Всего у нас на клавиатуре три наиболее часто используемых модификатора: Ctrl, Alt и Win (Super). Какой клавишей мы пользуемся чаще всего? Правильно! Ctrl! Тут и работа с буфером обмена и различные командные модификаторы, которые используются в большинстве программ. Дальше что? Конечно Alt! Он находиться на втором месте по частоте использования, тут и различные модификаторы меню и некоторые командные. Клавиша Win? Как часто вы ее используете? Не считая случаев, когда сами определили свои функции на нее? А при работе какой-либо программы? Правильно - почти не используем...

Следующий вопрос, которого необходимо коснуться, каким пальцами нам удобнее всего работать? Мизинцем или большим? Вопрос конечно сугубо индивидуальный, но мне, к примеру, куда удобнее нажимать на клавиши большим пальцем, чем тянуться мизинцем. Удобнее? А значит и уставать рука меньше будет.

Теперь рассмотрим, какие клавиши под какими пальцами находятся. Как не странно, но самый используемый модификатор Ctrl расположен под мизинцем, причем в самом неудобном положении, когда приходиться для его использования дополнительно смещать руку. В самой удобной позиции находиться Alt, но мы уже определили, что он используется менее часто, чем Ctrl, странно правда? Практически не используемая клавиша Win, располагается рядом с Alt, довольно удобная позиция, для нажатия используется большой палец. Но ведь это Win, к которому мы обращаемся очень редко!

Почему такая несправедливость? Рассматривать историю не будем, а постараемся исправить данное положение.

Мне оказалось проще всего, у меня клавиатура Apple aluminum keyboard, в которой уже частично исправлена ситуация.

<a href="http://static.juev.org/2010/06/apple-aluminum-keyboard.jpg"><img class="aligncenter size-medium wp-image-1085" title="apple-aluminum-keyboard" src="http://static.juev.org/2010/06/apple-aluminum-keyboard-300x89.jpg" alt="" width="300" height="89" /></a>

И осталось только переопределить две клавиши, фактически поменять их местами, это Cmd (Win) и Ctrl.

<a href="http://static.juev.org/2010/06/keyboard_2.jpg"><img class="aligncenter size-medium wp-image-1086" title="apple-edit" src="http://static.juev.org/2010/06/keyboard_2-300x85.jpg" alt="apple-edit" width="300" height="85" /></a>

Для совершения данной операции можно воспользоваться или <a href="http://www.autohotkey.com/" rel="nofollow">AutoHotkey</a>, или <a href="http://www.randyrants.com/sharpkeys/" rel="nofollow">sharpkeys3</a>, о чем я уже описывал в статье <a href="/2010/06/14/korrekciya-raskladki-v-windows/">Коррекция раскладки в Windows</a>. Принцип тот же самый. Используются только другие клавиши. Единственно, хотелось бы обратить внимание, что при использовании AutoHotKey бывает возникают проблемы с определением клавиш и при нажатии на Ctrl вдруг срабатывает Win. Если же использовать программу sharpkeys3, происходит правка реестра и никаких проблем не наблюдается. Именно поэтому я рекомендую использовать именно этот способ.

Пример изменения модификаторов для Linux я рассматривал в статье <a href="/2009/08/18/emacs-keymap/">Emacs keymap</a>.

Для владельцев обычной клавиатуры придется совершать чуть больше действий.

<a href="http://static.juev.org/2010/06/Mitsumi-KFK-EA4XA.jpg"><img class="aligncenter size-medium wp-image-1088" title="Mitsumi-KFK-EA4XA" src="http://static.juev.org/2010/06/Mitsumi-KFK-EA4XA-300x119.jpg" alt="" width="300" height="119" /></a>

Здесь нужно менять местами уже три клавиши.

<a href="http://static.juev.org/2010/06/keyboard-mitsumi.jpg"><img class="aligncenter size-medium wp-image-1087" title="keyboard-mitsumi" src="http://static.juev.org/2010/06/keyboard-mitsumi-300x100.jpg" alt="" width="300" height="100" /></a>

Но, опять же, с использованием sharpkeys3 это очень просто. Нажатием клавиши определяем клавишу, которую будем менять и задаем ей новый модификатор из списка. После перезагрузки системы можно будет наслаждаться новой раскладкой.

Что могу сказать? Я уже больше недели использую измененную раскладку. Руки устают намного меньше, а работать стало намного удобнее. До сих пор не понимаю, почему производители клавиатур делают Ctrl в таком не удобном месте.

Стандарты нужно менять! Попробуйте и вы!
