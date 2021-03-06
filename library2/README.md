Создаем мультик. 

Для того чтобы создать мультипликационную историю необходимы объекты (герои  вашего мультика). 

Их можно придумать и нарисовать самим. Для этого потребуются небольшие навыки работы в графическом редакторе или даже можно нарисовать на листочке бумаги в клеточку.  

Специальная графическая библиотека "TXLib.h" позволит вам нарисовать и оживить вашего героя.

Найти ее можно на сайте Дединского И.Р. http://ded32.net.ru/,- создателя этой библиотеки. 

Там же можно найти и среду разработки для программирования на языке С++, с настройками, сделанными автором (CodeBlocks).

Процесс создания мультфильма очень увлекательный.

Чтобы научиться создавать мультфильм нужно изучить основные принципы построение графических объектов необходимо знать систему координат и геометрические фигуры.

Нужно сделать набросок из простых геометрических фигур. Для работы над мультфильмом нам понадобятся координаты ключевых точек, для того чтобы внести их в свою программу. 

Команды, которые позволят быстро создавать статические изображения на экране т.е. рисовать простые примитивы это:  линии, окружности, многоугольники, эллипсы.

txLine (x0, y0, x, y) - рисует линию

txCircle (x, y, r) - рисует круг

txPolygon (const POINT points[], intnumPoints) – рисует ломанную линию, многоугольник

txEllipse (x0, y0, x, y) - рисует эллипс

Например можно создать такие объекты как:

•	мальчик;

 ![изображение](https://user-images.githubusercontent.com/82114365/114375537-6d37ce80-9b8d-11eb-9795-8bbb8bc9d196.png)

•	девочка;
 
![изображение](https://user-images.githubusercontent.com/82114365/114375583-7c1e8100-9b8d-11eb-9d4b-e4aaabce30d1.png)

•	кот;

![изображение](https://user-images.githubusercontent.com/82114365/114375609-850f5280-9b8d-11eb-8685-ee899fb1fa62.png)

• стрекоза;

 ![изображение](https://user-images.githubusercontent.com/82114365/114375666-92c4d800-9b8d-11eb-90f8-15b741f1b3a3.png)

• тучки;

 ![изображение](https://user-images.githubusercontent.com/82114365/114375804-ba1ba500-9b8d-11eb-85e5-449374fad45c.png)

• деревья;

 ![изображение](https://user-images.githubusercontent.com/82114365/114375846-c43da380-9b8d-11eb-970c-611a7c13db0e.png)
 
 Когда объектов  становится слишком много, все они неподвижны и программа оказывается слишком  громоздкой, то в ней сложно ориентироваться и хочется разделить программу на части.
 
 На помощь приходят функции, которые позволяют разбивать большой код на отдельные блоки.
 
 А если в функцию добавить параметры (значения элементов в скобках).  Эти значения могут быть целыми числами (int) или дробными (double), а может и даже цветами. 
 
 То объекты оживут, и будут менять цвета. 
 
 ![изображение](https://user-images.githubusercontent.com/82114365/114375977-e46d6280-9b8d-11eb-93f1-207163951098.png)
 
 Когда мы создаем похожие объекты, можно использовать многократный вызов одной и той же функции с разными параметрами.
 
 ![изображение](https://user-images.githubusercontent.com/82114365/114375687-99ebe600-9b8d-11eb-92df-e3bead3beaf3.png)

Для повторения одинаковых  действий используются  циклы for и while. 
 
  ![изображение](https://user-images.githubusercontent.com/82114365/114375776-b2f49700-9b8d-11eb-8037-3da06c5e183d.png)

Движение объектов происходит за счет постоянного стирания и рисования в другом месте. Для того, чтобы увидеть движение объекта используется задержка экрана txSleep. 

 ![изображение](https://user-images.githubusercontent.com/82114365/114376049-f5b66f00-9b8d-11eb-9788-a4886191e19e.png)
 
 В цикле  создается переменная времени, которая позволяет задавать скорость движения объекта.
 
 ![изображение](https://user-images.githubusercontent.com/82114365/114376110-00710400-9b8e-11eb-9625-95245f4956e8.png)

