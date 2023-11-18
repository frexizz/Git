# Всем привет
Хочу рассказать о GIT
----
## Что такое GIT и зачем он нужен 
Распределённая система управления версиями и позволяет нескольким разработчикам одновременно работать над одним продуктом
----
## Ниже основные команды навигации которые помогут при работе с GIT.
pwd-покажет в какой вы папке;
--
ls-покажет файлы и папки в текущей папке ;
--
ls -a-покажет скрытые файлы,название которых начинается на .;
--
cd "имя папки"-перейти в папку "имя папки";
--
cd first-project/html-перейдет в папку html,которая находится в папке first-project;
--
cd ..-перейти на уровень выше,в родительскую папку;
--
cd ~-перейти в домашнюю директорию;
--
cd /-перейди в корневую директорию.
## Взглянем на оформление сообщение к коммитам 
### Если коммит «закрывает» или «решает» какую-то задачу, то в его сообщении удобно указывать ссылку на неё.
#### Для этого в любом месте сообщения нужно указать #<номер задачи>. Например, вот так:
$ git commit -m "Исправить #334, добавить график температуры"

----
#### Давайте взглянем на команды для создания репризиторий(хранилище кода)
 git init `папка` - превращает папку в репризиорий;
 --
 rm -rf "репризиторий" - превращает репризиторий обратно в папку; 
 --
 git add `файл` - подготавливает файл к сохранению в р;
 --
 git commit -m "Сведенья о изменениях в вресии" - команда сохраняет вресию в репризиторий. Важно в поле "Сведенья о изменениях в вресии" писать полезную информацию, а не какой-ниюудь "Фиксы";
 --
 git log - просмотреть версии сохранёные  врепризитории;
 --

##### И пока что на гит логе я остановлюсь, ведь в нём есть много разной интересной информации, например там можно увидеть дату создания версии, её автора и какой-то непонятный набор символов типа ff31b1aa8d0a32719bdb94beb518a31e255a3778, сейчас о нём и пойдёт речь.**
ХЕШ - Основной идефикатор коммита. Можно сказать это вся инфа о версии в зашифрованном виде.

~~Теперь ты знаешь все(нет)**~~

На счет git log-в самой последний версии прокта можно увидеть HEAD -> master(или main),но такая штука пишется только на последней версии и называется она HEAD(Последняя версия)

На этом с git всё, остальное можно узнать на курсе [Основы работы с гит](https://practicum.yandex.ru/profile/git-basics/?from=catalog) на яндекс практикум 
----
##### Как же делать такое красивый текст,просто!Называется такая волшебная штучка markdown-Это спецаильный язык разметки.
Давайте к примерам:
# H1 — заголовок первого уровня, самый большой
## H2 — заголовок второго уровня, поменьше
### H3
#### H4
##### H5
###### H6 — заголовок шестого уровня, самый маленький 

Текст над чертой

---

Текст под чертой 

Текст до переноса⋅⋅  
Текст после переноса <br>
Текст после второго переноса 

Курсив — это *звёздочки* или _подчёркивания_. 

Полужирный шрифт — двойные **звёздочки** или двойные __подчёркивания__.
Можно совместить выделение **звёздочки и _подчёркивания_**. 

~~Зачёркнутый текст.~~ 

1. Первый пункт нумерованного списка.
2. Второй пункт. 

* первый пункт ненумерованного списка;
* второй пункт ненумерованного списка

- первый пункт ненумерованного списка;
- второй пункт ненумерованного списка 

[Яндекс](https://www.yandex.ru "Я Yandex!") 

```bash
ls - la
```
```html
Я
Егор
```  
* Впрочем
- Я
[Всё](https://www.yandex.ru)
**Сам**
__это__
Знаю
----

Что бы просмотреть какие символы используется, рекомендуется скачать файл и открыть в блокноте

----
Спасибо за внимание
## И это все
Я дал основу,теперь в твоих интересах изучать это дальше или нет.
# Good luck buddy
