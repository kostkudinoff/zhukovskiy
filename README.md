## <center> Василий Андреевич Жуковский. Реализация романтических мотивов в корпусе баллад 

### Немного о проекте 

```markdown
Это тема нашего итогового проекта за первый год обучения цифровой грамотности. Возможно, она не такая 
злободневная, как у других коллег, но мы — консерваторы и фундаменталисты. Мы считаем, что наша тема 
очень важна в контексте русской литературы XIX (и не только XIX) века.

Почему мы так считаем?

Влияние романтизма прослеживается в русскоязычных художественных текстах с начала XIX века и 
до наших дней. Жуковский — это, пожалуй, самая главная фигура в русском романтизме, а баллады — 
самый главный романтический жанр у Жуковского. Нам было интересно выявить их ключевые мотивы, 
посмотреть, как они реализуются в тексте и насколько они частотны в корпусе русского языка. 
Эта работа позволит нам (и, надеемся, нашим слушателям и читателям) в будущем при чтении
других текстов опознать эти мотивы и сравнить их с "первоисточником". Кроме того, нам кажется
очень любопытным корпусное исследование канонических текстов: оно позволяет увидеть их составные
части и показывает хорошо знакомые произведения с другой стороны.
```


### Мотивировка исследования

```markdown
Идейный вдохновитель исследования – Андрей Семенович Немзер.
Прошедший на Филологическом факультете НИУ ВШЭ курс
"Ключевые тексты русской литературы XIX века", часть которого
была посвящена анализу баллад Василия Андреевича Жуковского, 
заставил нас глубже заинтересоваться выражением романтического
течения в данных произведениях.
```

### Цель исследования

```markdown
Целью исслеования является изучение текстов баллад
В. А. Жуковского с точки зрения мотивного аспекта.
Выделенные десять основных мотивов сорока пяти баллад, y 
изучались нами в рамках корпусного исследования.

Использованные программы – mystem; НКРЯ; AntConc; Google NGrams.

Особое внимание уделялось ключевым словам, маркирующим мотивы,
и их сочетаемости с рядом стоящими словами. На основе полученных
результатов для каждого мотива мы проводили интерпретацию
с учетом характерных особенностей поэтики Жуковского и 
романтизма. 
```

### Ход исследования

```markdown
1. Мы определили подкорпус баллад Жуковского в НКРЯ и на его основе
создали файл формата .txt в кодировке UTF-8.

2. Мы лемматизировали этот файл с помощью mystem.

3. Мы загрузили текстовый файл в AntConc
и определили частотные слова, добавив к списку стоп-слов для русского языка
предлоги "ко" и "пред", частицы "ах" и "ль" и одно имя собственное - "Вадим".

4. Мы просмотрели и проанализировали конкордансы каждого выделенного мотива.

5. Нам было важно понять, насколько частотны выявленные
нами мотивы в период от начала XIX века до наших дней, поэтому мы использовали 
GoogleNgrams для каждого мотива.

6. Мы создали GitHub Pages, где изложили всё, 
что мы сделали, и подвели итог нашему исследованию.
```

### Список анализируемых баллад

![корпус1](corpus1.jpg)
![корпус2](corpus2.jpg)
![корпус3](corpus3.jpg)

### Перечень наиболее частотных мотивов

![антконк](antconc.jpg)

#### Конь

![коньконк](konconc1.jpg)
![коньграф](kongraph.jpg)

#### Небо

![небоконк1](neboconc1.jpg)
![небоконк2](neboconc2.jpg)
![небоконк3](neboconc3.jpg)
![небограф](nebograph.jpg)

#### Око

![ококонк1](okoconc1.jpg)
![ококонк2](okoconc2.jpg)
![ококонк3](okoconc3.jpg)
![окограф](okograph.jpg)

#### Взор

![взорконк1](vzorconc1.jpg)
![взорконк2](vzorconc2.jpg)
![взорконк3](vzorconc3.jpg)
![взорграф](vzorgraph.jpg)

#### Сердце

Мотив сердца – один из главных романтических мотивов, что отражено на графике. Жуковский использует союз двух сердец
как символ любовных взаимоотношений героев, поэтому используемые поэтом эпитеты (откровенное,
милое, невинное сердце) никогда не несут отрицательных коннотаций и апеллируют к чувственной
составляющей отношений. В то же время глаголы, которые часто идут в связке с «сердцем», 
характеризуют этапы развития (или, наоборот, затухания) любви: сначала сердце любит, дышит, 
верит; затем покоряется, охладевает и расстаётся с другим сердцем, что приводит к расколу союза
двух влюбленных.


![сердцеконк1](cerdceconc1.jpg)
![сердцеконк2](cerdceconc2.jpg)
![сердцеконк3](cerdceconc3.jpg)
![сердцеграф](cerdcegraph.jpg)

#### Милый

Милый – ключевое слово-сигнал для связи всех романтических образов и мотивов в балладах Жуковского.
Является частотным эпитетом для типично романтических образов: ангел, цветок, друг, душа, взор, рыцарь,
встреча. Интересно, что после издания первых баллад Жуковского (1808-...) частота употреблений слова
начала расти.


![милыйконк1](miliyconc1.jpg)
![милыйконк2](miliyconc2.jpg)
![милыйконк3](miliyconc3.jpg)
![милыйграф](miliygraph.jpg)

#### Лес

Мотив леса связан с темой романтической природы. Эпитеты, характеризующие его, отражают отношение
к лесу как к сосредоточению тёмной, не поддающейся контролю человека мистической силы (тёмный, угрюмый,
дремучий, унылый), не приносящей человеку добра. В лесу обитают невиданные звери, там темно и страшно,
лес – центр пугающих звуков. Редко возникает связь со смертью (рядом с лесом – могила). Есть и положительно
окрашенные эпитеты, возникающие при описании идиллической картины («вечнозеленый пышный лес», «мирный» - 
вместе с золотой нивой и светлым небом), но это переносит лес совершенно в иную плоскость. Лес - не 
самый частотный мотив в русской литературе начала 19 века, но характерный мотив для поэтики Жуковского.

![лесконк1](lesconc1.jpg)
![лесконк2](lesconc2.jpg)
![лесконк3](lesconc3.jpg)
![лесграф](lesgraph.jpg)

#### Святой

![святойконк1](svatoiconc1.jpg)
![святойконк2](svatoiconc2.jpg)
![святойконк3](svatoiconc3.jpg)
![святойграф](svatoigraph.jpg)

#### Бог

![богконк1](bogconc1.jpg)
![богконк2](bogconc2.jpg)
![богконк3](bogconc3.jpg)
![богграф](boggraph.jpg)

#### Волна

![волнаконк1](volnaconc1.jpg)
![волнаконк2](volnaconc2.jpg)
![волнаконк3](volnaconc3.jpg)
![волнаграф](volnagraph.jpg)

#### Итоги исследования

```markdown
Цель нашего проекта была достигнута: основные мотивы были выявлены и
проинтерпретированы, при помощи сочетаемости слов мы убедились
в их принадлежности к романтическому течению. На примере конкретных мотивов была
рассмотрена реализация романтического начала
в произведениях В. А. Жуковского.
```
