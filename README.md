# Установка Git и Visual Studio Code
#### Установка Git для Windows, MAC, Linux: https://git-scm.com/downloads
#### Установка VSCode для Windows, MAC, Linux: https://code.visualstudio.com/Download
* При первом использовании Git необходимо представиться. Для 
этого нужно ввести в терминале 2 команды:
git config --global user.name «Ваше имя английскими буквами» git 
config --global user.email ваша почта@example.com 

Основные команды Git
Введение в контроль версий. Работа с Git. Составление инструкции по работе с Git.
*  git init – инициализация локального репозитория
* git status – получить информацию от git о его текущем состоянии
* git add – добавить файл или файлы к следующему коммиту
*  git commit -m “message” – создание коммита.
*  git log – вывод на экран истории всех коммитов с их хеш-кодами
*  git checkout – переход от одного коммита к другому
*  git checkout master – вернуться к актуальному состоянию и продолжить работу
*  git diff – увидеть разницу между текущим файлом и закоммиченным файлом

# Синтаксис языка Markdown
## Введение в контроль версий. Работа с Git. Составление инструкции по работе с Git. Справочник по Markdown от Microsoft: https://docs.microsoft.com/ru-ru/contribute/markdown-reference
*  Заголовок – выделение заголовков. Количество символов “#” задаёт уровень заголовка 
(поддерживается 6 уровней).
*  = или - – подчёркиванием этими символами (не менее 3 подряд) выделяют заголовки первого 
(“=”) и второго (“-”) уровней.
*  ** Полужирное начертание** или __ Полужирное начертание__
*  *Курсивное начертание* или _Курсивное начертание_
*  ***Полужирное курсивное начертание***
*  ~~Зачёркнутый текст~~
*  * Строка – ненумерованные списки, символ “*” в начале строки
*  1, 2, 3 … – нумерованные списки



# Конспект по синтаксису Markdown

## Заголовки
# Заголовок 1-го уровня
## Заголовок 2-го уровня
### Заголовок 3-го уровня
#### Заголовок 4-го уровня
##### Заголовок 5-го уровня
###### Заголовок 6-го уровня

## Стили текста
*  **Полужирное начертание** или __Полужирное начертание__
*  *Курсивное начертание* или _Курсивное начертание_
*  ***Полужирное курсивное начертание***
*  ~~Зачёркнутый текст~~

## Списки
### Ненумерованный список
- Пункт 1
- Пункт 2
- Пункт 3

или

* Пункт 1
* Пункт 2
* Пункт 3

### Нумерованный список
1. Первый пункт
2. Второй пункт
3. Третий пункт

## Цитаты
> Это цитата
>
> Многострочная цитата

## Горизонтальная линия
---
или
***
или
*

## Ссылки
[Текст ссылки](URL "Необязательное подсказка")
[Google](https://www.google.com "Поиск в Google")

## Изображения
![Альтернативный текст](URL_изображения "Необязательная подсказка")

## Код
### Инлайн-код
console.log('Пример кода');

### Блок кода
`javascript
function helloWorld() {
    console.log('Hello, world!');
}
