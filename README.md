# Программа обучения Android-разработчика
###### Туториал по изучению теоретических материалов:
Обозначение    | Уровень важности
--------|-------------------------------------------------------------------------------
**(\*\*\*\*)**   | Без изучения этого материала невозможно успешное прохождение темы
**(\*\*\*)**     | Материал, без которого сложно успешно завершить изучение темы
**(\*\*)**       | Важный материал, рекомендуемый к изучению
**(\*)**         | Полезная литература, улучшающая навыки
---

### Прохождение программы обучения
 Программа обучения разделена на секции. Каждая секция состоит из
 + Теоретической части;
 + Практической части;
 + Теста;

 Каждая секция начинается с выполнения практического задания. Теоретический материал изучается по мере необходимости для выполнения практики. После завершения практического задания необходимо в github создать merge request на ментора, чтобы он смог проверить задание. Если задание выполнено успешно, то ментор предоставляет тест по пройденной секции. Для успешного прохождения теста в большинстве случаев достаточно знаний, полученных в ходе выполнения практического задания и прочтения необходимой для него теории.

 Стоит отметить, что ментор в силу различных обстоятельств не всегда может оперативно проверять merge request'ы и предоставлять тесты. Поэтому, если ментор вам говорит, что сможет проверить задание/предоставить тест только через несколько часов - приступайте к выполнению следующей секции программы обучения.
 **Важно** одновременно непроверенным может быть не более одной секции программы обучения. То есть, чтобы приступить к 5ой секции, Ваше практическое задание по 3ей секции должно быть одобрено, а тест пройден.


 В случае возникновения вопросов во время выполнения практического задания, можно просить помощи у ментора. Однако не стоит подходить к ментору с недекомпозированной задачей из разряда "Я не понимаю, как сверстать экран". Декомпозируйте задачу, чтобы задать ментору более конкретный вопрос. Также не стоит сразу же спрашивать ментора, как только возникла трудность. Для начала попробуйте самостоятельно найти ответ на свой вопрос в интернете.

---
## I. Основные принципы разработки. Git. Flow проектов
---
### Теоретическая часть

**1. ООП:**
+ [Основные принципы](https://progstudy.ru/index.php/sm/article/ob-ektno-orientirovannoe-programmirovanie)  **(\*\*\*\*)**

**2. SOLID**
+ [Принципы SOLID](https://ru.wikipedia.org/wiki/SOLID_(%D0%BE%D0%B1%D1%8A%D0%B5%D0%BA%D1%82%D0%BD%D0%BE-%D0%BE%D1%80%D0%B8%D0%B5%D0%BD%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%BD%D0%BE%D0%B5_%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5))  **(\*\*\*)**
+ [SOLID в Java](http://blog.gauffin.org/2012/05/solid-principles-with-real-world-examples/) **(\*)**

**3. Работа с Git, gitflow**
+ [Основные команды](https://git-scm.com/book/ru/v2) : init, clone, add, status, stash, commit (-m, -am, --amend), fetch, pull, push, branch, checkout, merge **(\*\*\*\*)**
+ Что такое [git flow](https://habr.com/post/106912/) **(\*\*\*\)**
+ [Первоначальная настройка](https://git-scm.com/book/ru/v1/%D0%92%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5-%D0%9F%D0%B5%D1%80%D0%B2%D0%BE%D0%BD%D0%B0%D1%87%D0%B0%D0%BB%D1%8C%D0%BD%D0%B0%D1%8F-%D0%BD%D0%B0%D1%81%D1%82%D1%80%D0%BE%D0%B9%D0%BA%D0%B0-Git): конфигурация username и email **(\*\*\*\)**

**4. Создание проекта, среда разработки Android Studio**
+ [Установка Android Studio] (https://developer.android.com/studio/preview/index.html) **(\*\*\*\*)**
+ [Создание нового проекта](https://developer.android.com/training/basics/firstapp/index.html) **(\*\*\*\*)**
+ [Основы интерфейса Android Studio](https://developer.android.com/studio/intro/index.html) **(\*\*\*\*)**

**5. Gradle**
+ [Gradle](https://developer.android.com/studio/build/index.html) **(\*\*\*\)**


### Практическое задание
1. В GitHub создать новый репозиторий и следуя инструкциям, склонировать его к себе на компьютер. В настройках репозитория дать доступ ментору.
2.  В глобальных конфигурациях git прописать корректное имя пользователя и e-mail, которые будут использоваться для подписи коммитов.
3. Добавить `.gitignore`. Содержание файла можно взять с ресурса: https://www.gitignore.io/api/androidstudio.  Cделать коммит и запушить изменения на remote-сервер в `master` ветку
4. Переключиться на новую ветку `develop`.
5. Создать новый android-проект (Phone and Tablet -> Empty Activity).
6. Добавить в gradle-файл библиотеку retrofit http://square.github.io/retrofit/
7. Запустить проект на телефоне/симуляторе
8. Cделать коммит и запушить изменения на remote-сервер в `develop` ветку
9. После завершения работ над задением отправить ментору количество затраченного времени на практическое выполнение задачи.

---
## II. Java. Часть 1
---
### Теоретическая часть

**Основы:**  
+ [Java-платформа] (https://docs.oracle.com/javase/tutorial/getStarted/intro/definition.html) **(\*\*)**
+ [Типы данных и переменные](https://metanit.com/java/tutorial/2.1.php) **(\*\*\*\*)**
+ [Преобразования базовых типов данных] (https://metanit.com/java/tutorial/2.2.php) **(\*\*\*\*)**
+ [Операции языка Java] (https://metanit.com/java/tutorial/2.3.php) **(\*\*\*\*)**
+ [Массивы] (https://metanit.com/java/tutorial/2.4.php) **(\*\*\*)**
+ [Условные конструкции] (https://metanit.com/java/tutorial/2.5.php) **(\*\*\*\*)**
+ [Циклы] (https://metanit.com/java/tutorial/2.6.php) **(\*\*\*\*)**
+ [Методы] (https://metanit.com/java/tutorial/2.7.php) **(\*\*\*\*)**
+ [Рекурсивные функции] (https://metanit.com/java/tutorial/2.8.php) **(\*\*\*)**
+ [Введение в обработку исключений] (https://metanit.com/java/tutorial/2.10.php) **(\*\*)**
+ [Java Code Conventions - Oracle] (http://www.oracle.com/technetwork/java/codeconventions-150003.pdf) **(\*\*\*\*)**

**Отладка** 
+ [Android Studio Debugging: Базовые понятия](https://medium.com/@artem_shevchenko/android-studio-debugging-%D0%B1%D0%B0%D0%B7%D0%BE%D0%B2%D1%8B%D0%B5-%D0%BF%D0%BE%D0%BD%D1%8F%D1%82%D0%B8%D1%8F-%D0%B8-%D0%B2%D0%BE%D0%B7%D0%BC%D0%BE%D0%B6%D0%BD%D0%BE%D1%81%D1%82%D0%B8-658ee6dcc641) **(\*\*\*)**
+ [Android Studio Debugging: Продвинутый уровень](https://medium.com/@artem_shevchenko/android-studio-debugging-%D0%BF%D1%80%D0%BE%D0%B4%D0%B2%D0%B8%D0%BD%D1%83%D1%82%D1%8B%D0%B9-%D1%83%D1%80%D0%BE%D0%B2%D0%B5%D0%BD%D1%8C-e05dac22439f) **(\*\*\*)**

### Практическое задание
Все задачи должны быть выполнены в указанном репозитории в отдельной ветке, вида training/lastname_firstname_date. После выполнения должен быть создан merge request на ментора.

***Важно! Весь код должен быть написан по предоставленному Java Code Conventions***

1. [Работа с примитивными типами](javacoreTraining/ElementaryTraining.java)
2. [Работа со строками](javacoreTraining/StringsTraining.java)
3. [Работа с массивами](javacoreTraining/ArraysTraining.java)
4. Завершить task и отправить ментору затраченное время

---
## III. Java. Часть 2
---
### Теоретическая часть

**1. Классы**
+ [Классы и объекты](https://metanit.com/java/tutorial/3.1.php)  **(\*\*\*\*)**
+ [Пакеты](https://metanit.com/java/tutorial/3.2.php)  **(\*\*\*\*)**
+ [Модификаторы доступа и инкапсуляция](https://metanit.com/java/tutorial/3.3.php)  **(\*\*\*\*)**
+ [Статические члены и модификатор static](https://metanit.com/java/tutorial/3.4.php)  **(\*\*\*\*)**
+ [Объекты как параметры методов](https://metanit.com/java/tutorial/3.14.php)  **(\*\*\*\*)**
+ [Наследование, полиморфизм и ключевое слово super](https://metanit.com/java/tutorial/3.5.php)  **(\*\*\*\*)**
+ [Абстрактные классы](https://metanit.com/java/tutorial/3.6.php)  **(\*\*\*\*)**
+ [Иерархия наследования и преобразование типов](https://metanit.com/java/tutorial/3.10.php)  **(\*\*\*\*)**
+ [Внутренние классы](https://metanit.com/java/tutorial/3.12.php)  **(\*\*\*\*)**
+ [Интерфейсы](https://metanit.com/java/tutorial/3.7.php)  **(\*\*\*\*)**
+ [Интерфейсы в механизме обратного вызова](https://metanit.com/java/tutorial/3.16.php)  **(\*\*\*)**
+ [Перечисления enum](https://metanit.com/java/tutorial/3.8.php)  **(\*\*\*\*)**
+ [Класс Object и его методы](https://habrahabr.ru/post/168195/)  **(\*\*\*)**
+ [Обобщенные типы и методы](https://metanit.com/java/tutorial/3.11.php)  **(\*\*\*)**
+ [Наследование и обобщения](https://metanit.com/java/tutorial/3.15.php)  **(\*\*\*)**
+ [Типы ссылок](https://javadevblog.com/tipy-ssy-lok-v-java-strongreference-weakreference-softreference-i-phantomreference.html)  **(\*\*\*)**
+ [Ссылочные типы и клонирование объектов](https://metanit.com/java/tutorial/3.13.php) **(\*\*\*)**

**2. Обработка исключений**  
+ [Оператор throws](https://metanit.com/java/tutorial/4.1.php) **(\*\*\*\*)**
+ [Классы исключений](https://metanit.com/java/tutorial/4.2.php) **(\*\*\*\*)**
+ [try-with-resources](https://docs.oracle.com/javase/tutorial/essential/exceptions/tryResourceClose.html) **(\*\*\*\*)**
+ [Создание своих классов исключений](https://metanit.com/java/tutorial/4.3.php) **(\*\*)**

**3. Коллекции**  
+ [Введение в коллекции в Java](https://metanit.com/java/tutorial/5.1.php) **(\*\*\*\*)**
+ [Класс ArrayList и интерфейс List](https://metanit.com/java/tutorial/5.2.php) **(\*\*\*\*)**
+ [Структуры данных в картинках. ArrayList](https://habr.com/en/post/128269/) **(\*\*\*\*)**
+ [Класс LinkedList](https://metanit.com/java/tutorial/5.3.php) **(\*\*)**
+ [Структуры данных в картинках. LinkedList](https://habr.com/en/post/127864/) **(\*\*)**
+ [Класс HashSet](https://metanit.com/java/tutorial/5.4.php) **(\*\*\*\*)**
+ [Класс TreeSet](https://metanit.com/java/tutorial/5.5.php) **(\*\*\*)**
+ [Интерфейсы Comparable и Comporator. Сортировка](https://metanit.com/java/tutorial/5.6.php) **(\*\*\*)**
+ [Очереди и класс ArrayDeque](https://metanit.com/java/tutorial/5.7.php) **(\*\*)**
+ [Отображения и класс HashMap](https://metanit.com/java/tutorial/5.8.php) **(\*\*\*\*)**
+ [Структуры данных в картинках. HashMap](https://habr.com/en/post/128017/) **(\*\*\*\*)**
+ [Класс TreeMap](https://metanit.com/java/tutorial/5.9.php) **(\*\*)**
+ [Итераторы](https://metanit.com/java/tutorial/5.10.php) **(\*\*)**

**4. Работа со строками**  
+ [Введение в строки. Класс String](https://metanit.com/java/tutorial/7.1.php) **(\*\*\*\*)**
+ [Основные операции со строками](https://metanit.com/java/tutorial/7.2.php) **(\*\*\*\*)**
+ [StringBuffer и StringBuilder](https://metanit.com/java/tutorial/7.3.php) **(\*\*\*)**
+ [Регулярные выражения](https://metanit.com/java/tutorial/7.4.php) **(\*\*)**

**5. Лямбда-выражения**  
+ [Введение в лямбда-выражения](https://metanit.com/java/tutorial/9.1.php) **(\*\*\*\*)**
+ [Лямбды как параметры методов и ссылки на методы](https://metanit.com/java/tutorial/9.2.php) **(\*\*\*\*)**
+ [Встроенные функциональные интерфейсы](https://metanit.com/java/tutorial/9.3.php) **(\*\*)**
  
  
### Базовое задание
Все задачи должны быть выполнены в указанном репозитории в отдельной ветке, вида training/lastname_firstname_date. После выполнения должен быть создан merge request на ментора.

1. [Работа со списками](javacoreTraining/CollectionsBlock.java)
2. [Работа с классами](javacoreTraining/ClassesBlock.java)


### Практическое задание
Все задачи должны быть реализованы в одном файле и разделены комментариями, указывающими на номер или текст задания.

**Важно! Весь код должен быть написан по предоставленному Java Code Conventions**
1. Создать task в PS с заголовком "II. Java. Часть 2" и взять ее в работу.
2. Настроить проект для [java 8](https://developer.android.com/studio/write/java8-support.html?utm_source=android-studio)
3. Написать простое лямбда-выражение в переменной `myClosure`, лямбда-выражение должно выводить в консоль фразу "I love Java". Вызвать это лямбда-выражение. Далее написать функцию, которая будет запускать заданное лямбда-выражение заданное количество раз. Объявить функцию так: `public void repeatTask (int times, Runnable task)`. Функция должна запускать `times` раз лямбда-выражение `task` . Используйте эту функцию для печати "I love Java" 10 раз.
4. Условия: есть начальная позиция на двумерной плоскости, можно осуществлять последовательность шагов по четырем направлениям up, down, left, right. Размерность каждого шага равна 1. Задание: 
  - Создать enum `Directions` с возможными направлениями движения
  - Создать метод, принимающий координаты и одно из направлений и возвращающий координату после перехода по направлению
  - Создать метод, осуществляющий несколько переходов от первоначальной координаты и выводящий координату после каждого перехода. Для этого внутри метода следует определить переменную `location` с начальными координатами (0,0) и  массив направлений, содержащий элементы [up, up, left, down, left, down, down, right, right, down, right], и програмно вычислить какие будут координаты у переменной `location` после выполнения этой последовательности шагов. Для вычисленеия результата каждого перемещения следует использовать созданный ранее метод перемещения на один шаг.
5. Создать интерфейс Shape с двумя методами perimeter и area, выводящими периметр и площадь фигуры соответственно, после чего реализовать и использовать для вывода периметра и площади следующие классы, реализующие интерфейс Shape:
  - `Rectangle` - прямоугольник с двумя свойствами: ширина и длина
  - `Square` - квадрат с одним свойством: длина стороны
  - `Circle` - круг с одним свойством: диаметр круга
6. Завершить task и отправить ментору затраченное время
[Вернуться к содержанию](../Содержание.md)

---
## IV. Верстка
---
### Теоретическая часть

В случае если по ссылке встречается пошаговый гайд - рекомендуется его выполнить в отдельном проекте.

**1. Начало разработки под Android**
+ [Начало разаработки](https://developer.android.com/training/index.html) **(\*\*\*\*)**

**2. Верстка**
+ [Уроки верстки из курсов](http://startandroid.ru/ru/uroki/vse-uroki-spiskom.html) **(\*\*)**
+ [Создание макетов в XML и View groups](https://developer.android.com/guide/topics/ui/declaring-layout.html) **(\*\*\*)**

**3. Типы layout'ов**
+ [Frame Layout](http://developer.alexanderklimov.ru/android/layout/framelayout.php) **(\*\*\*\*)**
+ [Linear Layout](https://developer.android.com/guide/topics/ui/layout/linear.html) **(\*\*\*\*)**
+ [Relative Layout](https://developer.android.com/guide/topics/ui/layout/relative.html) **(\*\*\*\*)**

**4. Splash Screen**
+ [Как правильно реализовать](https://habr.com/ru/post/345380/) **(\*\*\*\*)**

**4. BottomNavigationView**
+ [Обзор](https://developer.android.com/reference/android/support/design/widget/BottomNavigationView.html) **(\*\*\*\*)**

**5. App Bar**
+ [Обзор](https://developer.android.com/training/appbar) **(\*\*\*\*)**

**6. RecycleView Adapter**
 [Видео-лекция Яндекса: Школа мобильной разработки – AdapterView. Владимир Тагаков](https://youtu.be/G35pcPv_tEA?list=PLQC2_0cDcSKBNCR8UWeElzCUuFkXASduz)  Лектор рассказывает про recycleView, желательно смотреть только после того, как появится уже некоторый опыт в создании компонентов RecycleView **(\*\*)**
**7. Constraint Layout**
+ [Документация](https://developer.android.com/reference/android/support/constraint/ConstraintLayout.html) **(\*\*\*\*)**
+ [Работа с различными свойствами](https://habrahabr.ru/company/touchinstinct/blog/326814/) **(\*\*\*\*)**

**8. Ресурсы**
+ [Обзор](https://developer.android.com/guide/topics/resources/providing-resources) **(\*\*\*\*)**
+ [Видео-лекция Яндекса: Школа мобильной разработки – MyFirstApp (Часть 1) Роман Григорьев](https://youtu.be/jVwGU3UJVPc) Описывает ресурсы андроид приложения, а так же различие релизной, дебажной сборки и signing config **(\*\*)**
+ [Локализация](https://developer.android.com/guide/topics/resources/localization) **(\*\*)**
+ [Типы ресурсов](https://developer.android.com/guide/topics/resources/available-resources) **(\*\*)**
+ [Шрифты в XML](https://developer.android.com/guide/topics/ui/look-and-feel/fonts-in-xml.html) **(\*\*)**
+ [Загружаемые шрифты](https://developer.android.com/guide/topics/ui/look-and-feel/downloadable-fonts.html) **(\*\*)**
+ [Поддержка разных экранов](https://developer.android.com/guide/practices/screens_support.html) **(\*\*)**
+ [Zeplin](https://habrahabr.ru/company/uteam/blog/315542/) **(\*\*\*)**

 
 **8. Анимации**
 + [Обзор доступных фреймворков](https://www.youtube.com/watch?v=N_x7SV3I3P0) **(\*\*)**
 + [Property Animation](https://developer.android.com/guide/topics/graphics/prop-animation) **(\*\*)**
 + [Transitions](https://developer.android.com/training/transitions) **(\*\*)**
 + [Animated Vector Drawable](https://developer.android.com/reference/android/graphics/drawable/AnimatedVectorDrawable) **(\*\*)**
 + [Physics Based Animation](https://android.jlelse.eu/android-physics-based-animation-cf0cc125830f) **(\*\*)**
 + [Motion Layout](https://developer.android.com/training/constraint-layout/motionlayout) **(\*\*)**

 
**9. Codelabs**
+ [Your first interactive UI](https://codelabs.developers.google.com/codelabs/android-training-layout-editor-part-a/index.html?index=..%2F..%2Fandroid-training#0) **(\*\*)**
+ [The layout editor](https://codelabs.developers.google.com/codelabs/android-training-layout-editor-part-b/index.html?index=..%2F..%2Fandroid-training#0) **(\*\*)**
+ [Text and scrolling views](https://codelabs.developers.google.com/codelabs/android-training-text-and-scrolling-views/index.html?index=..%2F..%2Fandroid-training#0) **(\*\*)**
+ [Drawables, styles, and themes](https://codelabs.developers.google.com/codelabs/android-training-drawables-styles-and-themes/index.html?index=..%2F..%2Fandroid-training#0) **(\*\*)**
+ [Clickable images](https://codelabs.developers.google.com/codelabs/android-training-clickable-images/index.html?index=..%2F..%2Fandroid-training#0) **(\*\*)**
+ [Input controls](https://codelabs.developers.google.com/codelabs/android-training-input-controls/index.html?index=..%2F..%2Fandroid-training#0) **(\*\*)**
+ [Menus and pickers](https://codelabs.developers.google.com/codelabs/android-training-menus-and-pickers/index.html?index=..%2F..%2Fandroid-training#0) **(\*\*)**
+ [User navigation](https://codelabs.developers.google.com/codelabs/android-training-provide-user-navigation/index.html?index=..%2F..%2Fandroid-training#0) **(\*\*)**
+ [Adaptive layouts](https://codelabs.developers.google.com/codelabs/android-training-adaptive-layouts/index.html?index=..%2F..%2Fandroid-training#0) **(\*\*)**


**Важно** В компании при разработке любого мобильного приложения считается правилом хорошего тона придерживаться нефункциональных требований, описанных в [данной статье](http://kb.simbirsoft/nonfunctional-support/)

### Практическое задание
Работа должна производится в созданном ранее проекте.

Все изменения должны быть закоммичены, а названия коммитов должны коротко и исчерпывающе описывать содержащие изменения. Каждый коммит должен быть рабочим, отправка некомпилирующегося кода недопустима. Для работы над этим заданием необходимо переключится на ветку `layouts` и все изменения пушить в нее. После завершения работы над задачей в gitlab необходимо создать merge request в ветку `develop`.
Код должен быть читабельным и написан согласно code-style. В системе PS также необходимо создать созвучную задачу, в которую после завершения будет залогировано время.

1. Сделать так, чтобы на домашнем экране Android отображалась иконка и название приложения "Хочу помочь". Ресурсы иконок [тут](https://zpl.io/2jkoMOp).
2. Реализовать Splash Screen согласно [макету](https://zpl.io/2jlk3Mm).
3. Реализовать экран "Профиль" согласно [макету](https://zpl.io/b6lQpZq).
 - Экран "Профиль" необходимо отображать после Splash Screen. По нажатию стрелки назад, приложение закрывается.
 - Необходимо реализовать нижний элемент навигации с помощью стандартного `BottomNavigationView`. Пункт "Помочь" визуально не должен отличаться от остальных четырех. Размеры иконок оставить стандартные для `BottomNavigationView` - 24dp.
 - В нижнем меню навигации по-умолчанию должен быть выбран пункт "Профиль".
 - Верстка должна быть реализована в xml.
 - Верстка должна быть выполнена с учетом "pixel perfect" - когда все элементы дизайна расположены и имеют размеры абсолютно идентичные макету для экрана с теми же размерами, что и макет, и адекватно масштабироваться для других размеров и разрешений.
 - Все переиспользуемые размеры в xml должны быть вынесены в dimes, цвета в colors, а строки в strings.
 - Никаких "магических чисел", все должно иметь понятные названия.

---
## V. Android OS. Activity. Fragments
---
### Теоретическая часть

**1. Android OS** 
+ [История Android](https://www.android.com/history/#/marshmallow) **(\*\*)**
+ [Архитектура Android](https://source.android.com/devices/architecture/) **(\*\*)**

**2. Application**  
+ [Application](https://developer.android.com/reference/android/app/Application.html)  **(\*\*\*)**
+ [Context](https://possiblemobile.com/2013/06/context/)  **(\*\*\*)**
+ [Файл Manifest](https://developer.android.com/guide/topics/manifest/manifest-intro.html) **(\*\*\*\*)**

**3. Activity**  
+ [Activity - основы](https://developer.android.com/guide/components/activities/intro-activities) **(\*\*\*\*)**
+ [Управление жизненным циклом Activity](https://developer.android.com/guide/components/activities/activity-lifecycle) **(\*\*\*\*)**
+ [Обработка изменений конфигурации экрана](https://developer.android.com/guide/topics/resources/runtime-changes.html) **(\*\*\*\*)**
+ [Task и Back Stack](https://habrahabr.ru/post/186434/) **(\*\*)**
+ [Передача данных между Activity. Обзор](https://developer.android.com/guide/components/activities/parcelables-and-bundles.html) **(\*\*\*\*)**
+ [Передача данных между Activity. Интерфейс Parcelable](https://metanit.com/java/android/2.13.php) **(\*\*\*\*)**
+ [Интерфейс Serializable](https://developer.android.com/reference/java/io/Serializable) **(\*\*)**
+ [Сравнение Parcelable и Serializable](https://android.jlelse.eu/parcelable-vs-serializable-6a2556d51538) **(\*\*)**

**4. Fragment**  
+ [Fragment - основы](https://developer.android.com/guide/components/fragments.html) **(\*\*\*\*)**
+ [Диалоговые окна](https://developer.android.com/guide/topics/ui/dialogs.html) **(\*\*\*\*)**
+ [Передача данных между Fragment](https://developer.android.com/training/basics/fragments/communicating) **(\*\*\*\*)**
+ [Target fragment](https://habrahabr.ru/post/259805/) **(\*\*)**
+ [Видео-лекция Яндекса: Школа мобильной разработки – Fragments (Часть 1). Денис Загаевский](https://youtu.be/3VXPsCUYioM?list=PLQC2_0cDcSKBNCR8UWeElzCUuFkXASduz) Лектор весьма неплохо описывает концепцию фрагментов и как их использовать **(\*\*)**  

**5. SearchView**
+ [Обзор](https://developer.android.com/guide/topics/search) **(\*\*\*\*)**

**6. ViewPager**
+ [Обзор](https://developer.android.com/training/implementing-navigation/lateral.html) **(\*\*\*\*)**

**7. Списки**
+ [ListView](http://developer.alexanderklimov.ru/android/views/listview.php) **(\*\*)**
+ [RecyclerView и Adapter](https://developer.android.com/training/material/lists-cards.html) **(\*\*\*\*)**

**8. Работа со сторонними приложениями и permissions**  
+ [Run-time permissions](https://developer.android.com/training/permissions/requesting.html)**(\*\*\*\*)**
+ [Intent и фильтры](https://developer.android.com/guide/components/intents-filters.html?hl=ru)**(\*\*\*\*)**
+ [Взаимодействие с другими приложениями](https://developer.android.com/training/basics/intents/index.html)**(\*\*\*\*)**
+ [Получение фото с камеры](https://developer.android.com/training/camera/photobasics)**(\*\*\*\*)**

**9. BroadcastReceiver**  
+ [BroadcastReceiver - основы](http://codetheory.in/android-broadcast-receivers/) **(\*\*\*\*)**
+ [Изменения работы с BroadcastReceiver с Android 8.0](https://developer.android.com/guide/components/broadcast-exceptions.html) **(\*\*)**

**10. Codelabs**
+ [Activities and intents](https://codelabs.developers.google.com/codelabs/android-training-create-an-activity/index.html?index=..%2F..%2Fandroid-training#0) **(\*\*)**
+ [Activity lifecycle and state](https://codelabs.developers.google.com/codelabs/android-training-activity-lifecycle-and-state/index.html?index=..%2F..%2Fandroid-training#0) **(\*\*)**
+ [Implicit intents](https://codelabs.developers.google.com/codelabs/android-training-activity-with-implicit-intent/index.html?index=..%2F..%2Fandroid-training#0) **(\*\*)**
+ [RecyclerView](https://codelabs.developers.google.com/codelabs/android-training-create-recycler-view/index.html?index=..%2F..%2Fandroid-training#0) **(\*\*)**
+ [Broadcast receivers](https://codelabs.developers.google.com/codelabs/android-training-broadcast-receivers/index.html?index=..%2F..%2Fandroid-training#0) **(\*\*)**
+ [Alarm Manager](https://codelabs.developers.google.com/codelabs/android-training-alarm-manager/index.html?index=..%2F..%2Fandroid-training#0) **(\*\*)**
+ [Fragments](https://codelabs.developers.google.com/codelabs/advanced-android-training-fragments/index.html?index=..%2F..advanced-android-training#0) **(\*\*)**
+ [Fragment communication](https://codelabs.developers.google.com/codelabs/advanced-android-training-fragment-communication/index.html?index=..%2F..advanced-android-training#0) **(\*\*)**


### Практическое задание
Работа должна производится в созданном ранее проекте.

Все изменения должны быть закоммичены, а названия коммитов должны коротко и исчерпывающе описывать содержащие изменения. Каждый коммит должен быть рабочим, отправка некомпилирующегося кода недопустима. Для работы над этим заданием необходимо переключится на ветку `fragments` и все изменения пушить в нее. После завершения работы над задачей в gitlab необходимо создать merge request в ветку `develop`.
Код должен быть читабельным и написан согласно code-style.

1. Реализовать диалог согласно [макету](https://zpl.io/brkmRYX)
 - Диалог необходимо открывать при нажатии на изображение пользователя на экране "Профиль". 
 - По нажатию на кнопку "Выбрать фото" не должно ничего происходить.
 - По нажатию на кнопку "Сделать снимок" необходимо запускать камеру устройства. Сделанное фото должно заменять текущее на экране профиля
 - По нажатию на кнопку "Удалить" необходимо удалять текущее изображение пользователя на экране профиля
2. Реализовать экран "Категории помощи" приложения согласно [макету](https://zpl.io/b6lYE9d).
 - Стрелку назад верстать не надо.
 - Экран "Категории помощи" необходимо отображать после Splash Screen. Переход на экран профиля теперь происходит при выборе пункта "Профиль" в нижнем меню.
 - В нижнем меню навигации по-умолчанию должен быть выбран пункт "Помочь".
 - Экран должен представлять из себя fragment с `RecyclerView`.
3. Реализовать экран "Поиск" согласно [макету](https://zpl.io/bAGAPj8). Переход на этот экран осуществляется при выборе пункта "Поиск" в нижнем меню
 - Экран необходимо построить с использованием `SearchView`,`ViewPager` и фрагментов.
 - У `SearchView` необходимо реализовать только верстку без логики.
 - Необходимо реализовать возможность изменять выбранную вкладку перелистыванием с плавной анимацией. 
 - В качестве названий для результатов необходимо использовать произвольные случайные строки.
 - Данные для отображения результата необходимо генерировать случайным образом при каждом перелистывании `ViewPager`.
