# USB-polygon (KiCAD)

Схема электрическая принципиальная и печатная плата отладочного устройства на базе микроконтроллера AT90USB162

## Краткое описание

Часть радиолюбительского проекта с целью создания простого устройства на микроконтроллере, имеющего возможность подключения к компьютеру по USB. Проект описан в цикле статей по адресу <http://romeogolf.github.io/tag/usb-polygon.html>.

Подробности использования платы в рамках проекта описаны в статьях цикла. Репозиторий содержит два коммита. Первый относится к статье [USB-polygon-2: Схема и плата](http://romeogolf.github.io/usb-polygon-2.html), второй --- к статье [USB-polygon-20: Мышиный энкодер](http://romeogolf.github.io/usb-polygon-20.html). Во втором коммите добавлены элементы в схему электрическую принципиальную без внесения их в печать, так как доработка выполнялась навесным монтажом, перемычками.

![Плата в KiCAD][pre_pcb]
![Вид со стороны контроллера][pre_cpu]
![Вид со стороны навесных элементов][pre_led]

[pre_pcb]: http://romeogolf.github.io/images/usb-polygon/02/preview/face-cad-small.png "Плата"
[pre_cpu]: http://romeogolf.github.io/images/usb-polygon/02/preview/cpu-small.jpg "Вид со стороны контроллера"
[pre_led]: http://romeogolf.github.io/images/usb-polygon/02/preview/led-small.jpg "Вид со стороны навесных элементов"

### Остальные части проекта:

* программа на C для микроконтроллера устройства [(ссылка)](https://github.com/RomeoGolf/usb-polygon-embedded)
* программа на C++ для взаимодействия с устройством со стороны ПК [(ссылка)](https://github.com/RomeoGolf/usb-polygon-cpp)
* программа на С++ для опроса одного из "файлов" на устройстве в непрерывном режиме (с отключением буферизации данных на ПК) [(ссылка)](https://github.com/RomeoGolf/usb-polygon-read-loop)
* программа на С++ для подготовки кадров "циферблата", отображаемого на ЖК-экране [(ссылка)](https://github.com/RomeoGolf/usb-polygon-makedial)

## Начало работы

### Зависимости

Для просмотра и внесения изменений необходим [KiCAD](http://kicad-pcb.org/).

### Получение

Для получения копии репозитория следует воспользоваться кнопкой "Clone or download" на [странице репозитория](https://github.com/RomeoGolf/usb-polygon-kicad).

При отсутствии git можно нажать кнопку "Download ZIP" и получить последнюю версию без истории коммитов.

При наличии git можно скопировать URL https://github.com/RomeoGolf/usb-polygon-kicad.git и использовать его в команде

~~~~
git clone https://github.com/RomeoGolf/usb-polygon-kicad.git
~~~~

в командной строке (git bash, например, в зависимости от ОС и настроек).

Далее можно открыть в KiCad файл "polygon.pro" и работать с проектом.

## Развитие проекта

Дальнейшее развитие проекта не предполагается, так как цель достигнута.

## Лицензия

This project is licensed under the MIT License - see the [License.txt](License.txt) file for details


