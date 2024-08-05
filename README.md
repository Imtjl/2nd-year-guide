<h1 align="center"> Гайд по II курсу 🐥 </h1>

# Описание

> Вашему вниманию представляется продолжение
> [гайда по I курсу](github.com/Imtjl/1st-year-guide)

# Оглавление

- [Описание](#описание)
- [Оглавление](#оглавление)
- [Сокращения](#сокращения)
- [Веб-программирование (3)](#веб-программирование)
  - [Лабораторная 1 (веб)](#лабораторная-1-веб)
    - [Деплой лабораторной 1 (веб)](#деплой-лабораторной-1-веб)
  - [Лабораторная 2 (веб)](#лабораторная-2-веб)
    - [Деплой лабораторной 2-3 (веб)](#деплой-лабораторной-2-3-веб)
  - [Лабораторная 3 (веб)](#лабораторная-3-веб)
  - [Лабораторная 4 (веб)](#лабораторная-4-веб)
    - [Деплой лабораторной 1 (веб)](#деплой-лабораторной-4-веб)
- [Теория вероятностей (3)](#теория-вероятностей)
  - [Селина (теорвер)](#селина-теорвер)
  - [Кудашов (теорвер)](#кудашов-теорвер)
- [Математика (базовый уровень) (3)](#математика-базовый-уровень)
- [Языки программирования (3)](#языки-программирования)
- [Физика (3,4)](#программирование)
  - [Физика ИВТ](#физика-ивт)
  - [Физика СППО](#физика-сппо)
    - [Боярский, Коробков, Горбенко](#боярский-коробков-горбенко)
- [Алгоритмы и структуры данных (4)](#алгоритмы-и-структуры-данных)
- [Архитектура компьютера (4)](#архитектура-компьютера)
  - [Лабораторная 1 (АК)](#лабораторная-1-ак)
  - [Лабораторная 2 (АК)](#лабораторная-2-ак)
  - [Лабораторная 3 (АК)](#лабораторная-3-ак)
  - [Лабораторная 4 (АК)](#лабораторная-4-ак)
- [Вычислительная математика (4)](#вычислительная-математика)
  - [Вычмат ИВТ](#вычмат-ивт)
  - [Вычмат СППО](#вычмат-сппо)
    - [Рубежка 1 (Вычмат)](#рубежка-1-вычмат)
    - [Рубежка 2 (Вычмат)](#рубежка-2-вычмат)
- [Математическая статистика (4)](#математическая-статистика)
- [Методы оптимизации (4)](#методы-оптимизации)
  - [Селина (метопы)](#селина-метопы)
  - [Кудашов (метопы)](#кудашов-метопы)
- [Основы программной инженерии (4)](#основы-программной-инженерии)
- [Техники публичных выступлений (4)](#техники-публичных-выступлений)
- [Особая благодарность](#особая-благодарность)

# Сокращения

- `Веб` - Веб-программирование
- `Теорвер` - Теория вероятностей
- `Матан` - Высшая математика
- `ЯП(ы)` - Языки программирования
- `Алгосы` - Алгоритмы и структуры данных
- `АК` - Архитектура компьютера
- `Вычмат` - Вычислительная математика
- `Матстат` - Математическая статистика
- `ОПИ` - Основы программной инженерии
  - (легаси) `МИСПИ` - Методы и средства программной инженерии
- `ТПВ` - Техники публичных выступлений
- `ИЭК` - Инновационная экономика и технологическое предпринимательство
- `Метопы` - Методы оптимизации
- `БМС / Модельки` - Бизнес-модели основных секторов инновационной экономики

# Веб-программирование

Курс веба представляет собой сдачу 4-х лабораторных связанных с разработкой как
фронтеда (пользовательского интерфейса), используя базовую связку HTML + CSS +
JS и фреймворки react, vue, angular, так и бэкенда (серверной части, обработка
запросов от пользователя) используя PHP, Java EE / Spring, JSP.

> [!IMPORTANT]  
> Не забывайте согласовывать требования с вашим практиком. Если в выполненной
> лабораторной что-то отличается от того, что говорит ВАШ практик - это
> нормально. Адаптируйтесь, на работе очень пригодится.

Теперь рассмотрим каждую лабораторную отдельно, кратко опишем основные моменты,
чтобы было понятно что вас ждёт и на что стоит обратить внимание:

## Лабораторная 1 (веб)

> (HTML + CSS + JS) + (PHP)

Надо сверстать простой сайтик, назначение которого - небольшая игра. Попал ты
точкой в координатную плоскость или промахнулся.

[-> Подробное описание с выполненным вариантом](https://github.com/worthant/simple-one-page-website/blob/726cfdd610064b9f9260f41cf24b76f1cd568005/README_RU.md)  
[-> Гайд на деплой, теор.вопросы se.ifmo](https://docs.google.com/document/u/0/d/13eAoOwDXg1enr3eFeawcM76AAhufZljDA4XYcNYAyDg/mobilebasic)

> Имхо: ничего зазорного в чтении гайда для educational purposes нету. Но лучше
> не опирайтесь на то, что в нём написано - перепроверяйте информацию и сами всё
> ресёрчите. Условный MDN docs более авторитетен :D

TODO: добавить showcase - гифку

- _Кратко то, что нужно сделать_: Рисуем график, табличку, а в заголовке сайта
  пишем своё ФИО, по нажатию отправляем запрос на PHP веб-сервер с координатами
  тыка, а сервер проверяет попадание и возвращает ответ. По сути в лабе
  требуется полный SSR, т.е. веб-сервер должен вернуть табличку, или строчку в
  таблице. Как практика норм, но это оверхед на ровном месте, поэтому если
  практик позволит, можете просто вернуть с сервера json {координаты +
  true/false}, а потом на клиентской части с помощью javascript это удобно
  отрисовать. Это спойлер, потому что в последующих лабах так и будете делать.

## Лабораторная 2 (веб)

> (HTML + CSS + JS) + (Servlets + JSP)

[-> Защищённая на фулл лаба (RU/EN):  
 = гифка для демонстрации,  
 = деплой лабораторной,  
 = разбор теории и сылки на полезные материалы,  
 = выполненный вариант](https://github.com/worthant/MVC-GeoValidator/tree/868f30f3819a3120080d0e98daae65f6048466e9)

## Лабораторная 3 (веб)

> (CSS + JSF) + (JSF) + (ORM: Hibernate/Eclipse Link)

JSF - зло, намучаетесь жесть. Если повезёт и аккуратно пройдёте по протоптанной
дорожке, то лаба делается супер-быстро. Зло в том что это старый фуллстак
фреймворк для веб-приложений. Лютое легаси, отвратительные доки, половина
встроенных вещей может просто не работать, потому что так надо и их придётся
обходить костыльными путями - будут конфликты устаревших версий пакетов,
рандомные ошибки и всё тому прочее. Материалы ниже были созданы в попытках
сохранить драгоценное время и нервы студентов:

[-> Видос с демонстрацией ёбнутой лабы (если есть много свободного времени)](https://www.youtube.com/watch?v=ny15aofvGCI&feature=youtu.be)  
[-> Полностью задокументированный рабочий шаблон для быстрого старта](https://github.com/worthant/web3-jsf-eclipselink-template)  
[-> Защищённая на фулл лаба (RU/EN):  
 = легко поднять в докере / гайд деплоя на гелиос  
 = ссылки на разбор теории + полезные материалы  
 = описание / требования](https://github.com/worthant/interactive-graph-ui)

> [!IMPORTANT]  
> Имхо: вообще неважно как вы тут выкрутитесь - главное найдите способ завести
> лабу, и сделайте так чтобы было очень сложно её положить. Если этого
> добьётесь - лаба сдана, больше ничего не надо. Чем меньше придётся работать с
> этим говном - тем лучше :)

## Лабораторная 4 (веб)

> (React/Vue/Angular) + (Spring/Jakarta EE) + (Hibernate/Eclipse Link)

Кто бы что ни говорил, тут всё равно что вам попадётся - лаба приятная, потому
что относительно новые фреймворки, нет конфликтов зависимостей и вас никто не
будет ограничивать. А также у многих практиков можно выпросить желаемый стэк. И
если фронтовый фреймворк достаточно просто, то на бэке могут дать Java EE и
сказать что всё, иди пиши :)

[-> Демонстрация конченной лабы, если у вас нет личной жизни  
 (все ссылки на исходники в описании)](https://www.youtube.com/watch?v=u1tMPwoMX9M)

Имхо: неважно у вас Java EE / Spring. Многим нравится спринг потому что он
простенький, и потому что на нём работы много. Я писал на Java EE, и хоть
сначала и плевался, со временем понял что фреймворк буквально проще спринга во
всём, и в этом его огромное преимущество. Придётся ручками написать большую
часть бэка, но это компенсируется тем что Java EE простая как пробка и в отличие
от спринга - на защите вам тоже должно быть сильно легче.

> [!IMPORTANT]  
> Учтите, что всех ждёт рубежка, на которой может попасться как java EE, так и
> Spring и любой фронтовый фреймворк, поэтому учить надо в любом случае всё,
> даже если практик будет вас спрашивать лояльно. Поэтому при написании лабы на
> Java EE, Spring MVC никто не отменял :D

### Деплой лабораторной 4 (веб)

Способов на самом деле много, я делал хостинг фронта на github pages и бэка на
гелиосе, а сайт был доступен через мой домен. Поэтому domain.com/api форвардился
на гелиос, а domain.com показывал фронт сайта, который раздавался бесплатным
хостингом github pages. Это сложный варик, но мне его одобрил практик. Бэк надо
в любом случае хостить на гелиосе - это дурацкое требование, но оно есть и
никуда вы не денетесь, учитите.

TODO тут надо написать про vite, npm, относительные пути, чтоб лаба работала на
se.ifmo, по-хорошему и другие сборщики в единый index.html файл

## Рубежка (веб)

TODO: ссылки на разборы рубежки, вопросы и варики рубежки

# Теория вероятностей

Курс теорвера представляет собой написания КР, небольших лаб. Основные темы:
Среднеквадратическое отклонение, Дисперсия, Математическое ожидание, коэффициент
стьюдента, проверка нулевой гипотезы и тд. Рекомендую делать решаторы так как в
следующем семе будет всё буквально то же самое на курсе матстата. Курс ведут два
преподавателя: Селина и Кудашов, так что ваше обучение зависит от того к кому
ваша группа попадёт

## Селина (теорвер)

С долгами лучше не оставаться и как следствие пропускать пары, так как в
противном случае придётся сдавать лабораторные вместе со всем потомком и
очередью из 100+ человек, в то время как скорость очереди около 10-15 минут на
человека. На лекции можно не ходить, так как они добавляют не значительные 3
балла, которые по сути бесполезны, так как закрывая все ключевые точки вовремя
вы с большой долей вероятности получите зачёт.

TODO возможно доделать описание, добавить ссылки на сливы кр, эксель
таблички-решаторы лаб, в идеале наверное вспомнить все лабы и написать их список

## Кудашов (теорвер)

Прикольный чел, забавный. К нему лучше приходить с хорошим настроением и немного
подготовленным, чтобы выходить к доске, отвечая на достаточно простые вопросы и
получая плюсики. Если будете чуть готовиться к каждой паре, курс пиво, но учтите
что лучше всю теорию хоть немного понимать, потому что потом будет мат.стат, как
и было сказано выше.

# Математика (базовый уровень)

TODO тут если честно не знаю что писать и надо ли, учитывая что у нас другая
математика нежели у них. // тру, пока так оставим

# Языки программирования

Тяжелый предмет. Дистанционный. Антиплагиат. Требует написания программ на
ассемблере и С. Так же требуется небольшие знания `Git` (`GitLab`)

TODO найти гайд по регистрации на гитлабе // камон бля, зайти на сайт, ввести
логин/пароль

TODO найти гайд по установки виртуалки // проще по факту прийти на первый
семинар и всё поставить, он лютое пиво

> [!IMPORTANT]  
> Лично я рекомендую поставить заранее линукс на дуал бут, потому что курс
> супер-интересный, семинары не сложные и вас всему научат и если что помогут,
> пользоваться линуксом, если стоят условные KDE/Gnome/другие гуи не сложно, но
> работать на семинарах будет сильно приятнее. Рекомендую поставить linux fedora
> и проблем вообще не должно быть, с убунтой будьте аккуратны, были у кого-то
> проблемы на последних семинарах. Если хотите пуститься во все тяжкие - ставьте
> neovim, в нём есть [классный дебаггер](https://github.com/worthant/nvim)

TODO Возможно не требуется разбития на лабы здесь, так как всю нужную информацию
можно найти на гитлабе, где и стырить лабу у другого студента // В целом
согласен, можно написать что этот курс даёт дохрена крутых возможностей - от
навыков код ревью до работы на низком уровне с программами и их дебагом. Но
описания лаб как будто бы за нас Жирков лучше сделал

## Лабораторная 1 (ЯП(ы))

Input/Output library in assembly

## Лабораторная 2 (ЯП(ы))

Dictionary in assembly

## Лабораторная 3 (ЯП(ы))

Image rotation

## Лабораторная 4 (ЯП(ы))

Memory allocator

## Лабораторная 5 (ЯП(ы))

Sepia filter + ускорение через SSE инструкции

# Физика

## ИВТ

Пока кратко - оба семестра нереально пивные. Больше всего баллов приносит работа на практиках, которая интересная и не особо замысловатая, а также ответы на вопросы на лекциях.

### Описание

Имхо: курс по уровню сложности ниже чем у многих было в школе, но на него интересно ходить, потому что это простые применения физики в реальной жизни - закрепите что уже знаете, либо изучите что-то новое. Отдельно было весело во втором семестре моделировать векторные поля для различных ситуаций, например нагреве фигуры необычной формы, физический смысл ротора и дивергенции на примере течений и завихрений в озёрах с проточным течением. Будет связь с музыкой и задачки на колебания, обычные задачки на грузики на пружинках, лекции про разработку промышленных устройств, будете готовить доклады про выбранные устройства или технологии. На лекциях частенько будет демонстрация физических опытов, поэтому рекомендую ходить просто ради интереса.

### Рубежка

Стот мало баллов. Если хорошо решите, ну может 5 баллов поставят, но по сути можно скипать или не писать и вообще побоку, экз всё решает в любом случае потому что весит 40 баллов. Задачи из рубежки - те же задачи с практик + дополнительные. Половина минимум из рубежки будет в экзамене.

### Экзамен

> [!IMPORTANT]  
> на практиках будете решать задачи - они не сложные, но рекомендую все конспектировать и разбирать, потому что потому 1 в 1 будут на экзамене.

Экз - просто билеты заботайте и пиво. Их не мало, но и не сильно много, половина как минимум скорее всего уже есть в голове со школы. Сначала получаете одну задачу из обязательного списка и решаете её перед преподом. Это задачи которые вы решали на практике, и они будут ещё раз разобраны накануне самого экзамена, поэтому просто не проморгайте и допуск к экзамену у вас в кармане. Затем вам дадут уже нормальные задачи и будете сидеть их решать. Как решите - тяните теор.билет, или сам препод вам его называет и потом его рассказываете. Обычный экз, достаточно простой. 


## СППО

# Алгоритмы и структуры данных

# Архитектура компьютера

> [!WARNING]  
> Не относитесь халатно к этому курсу, не пропускайте дедлайнов и согласовывайте темы докладов заранее. Может прозвучать душно, но потом просто не будет дороги назад и вы окажетесь в очень неприятной ситуации, которую можно было бы избежать, не применив слишком много усилий

В целом ggwp. Один из самых крутых курсов с точки зрения образования. С точки зрения закрытия - если организуетесь, не пропустите дедлайны, всё будете делать в срок и хорошо, то курс спокойно закрывается на 3-4 без экза. На 5 без экза надо нормально сделать 3 лабу, тут уже у кого на что сил хватит и смотря как стоят приоритеты.

# Вычислительная математика

# Математическая статистика

# Методы оптимизации

# Основы программной инженерии

# Техники публичных выступлений

# Особая благодарность

- \<T\>
- worthant
- TsenekovIT
