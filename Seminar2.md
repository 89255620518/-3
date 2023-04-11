# Создание туториала по GIT

##  Как создать репозиторий

**Чтобы создать репозиторий, напишите след. команду в терминале:**

~~~ fix
git init
~~~

## Как добавить файл на отслеживание
**Чтобы добавить файл на отслеживаниеБ вам необходимо сделать след.:**

- Прописать команду git add (.)


# Руководство по MarkDown





## Раздел первый - заголовки

Cделаи ошибку в зоголовке
бла бла бла



## Раздел второй - Списки

Для разметки неупорядоченных списков можно использовать
или `*`, или `-`, или `+`:
- элемент 1
- элемент 2
- элемент ...
Вложенные пункты создаются четырьмя пробелами перед
маркером пункта:
* элемент 1
* элемент 2
 * вложенный элемент 2.1
 * вложенный элемент 2.2
* элемент ...
Упорядоченный список:
1. элемент 1
2. элемент 2
 1. вложенный
 2. вложенный
3. элемент 33




## Раздел третий - исходный код

Бла-бла бла, исходный текст какой-то код 
--СSS

~{
  frjhfjrjfr, щкшмкрм
}
В чистом Маркдауне блоки кода отбиваются 4 пробелами в
начале каждой строки.
Но в GitHub-Flavored Markdown (сокращенно GFM) есть
более удобный способ: ставим по три апострофа (на букве
Ё) до и после кода. Также можно указать язык исходного
кода.
```html
<nav class="nav nav-primary">
 <ul>
 <li class="tab-conversation active">
 <a href="#" data-role="post-count"
class="publisher-nav-color" data-nav="conversation">
 <span class="comment-count">0
комментариев</span>
 <span class="comment-countplaceholder">Комментарии</span>
 </a>
 </li>
 <li class="dropdown user-menu" data-role="logout">
 <a href="#" class="dropdown-toggle" datatoggle="dropdown">
89
90
91
92
93
94
95
96
97
98
99
100
101
102
103
104
105
106
107
108
109
110
111
112
<nav class="nav nav-primary">
 <ul>
 <li class="tab-conversation active">
 <a href="#" data-role="post-count" class="publ
isher-nav-color" data-nav="conversation">
 <span class="comment-count">0 комментариев</
span>
 <span class="comment-count-placeholder">Комм
ентарии</span>
 </a>
 </li>
 <li class="dropdown user-menu" data-role="logou
t">
 <a href="#" class="dropdown-toggle" data-toggl
e="dropdown">
 <span class="dropdown-toggle-wrapper">
 <span>
 Войти
 </span>
 </span>
 <span class="caret"></span>
 </a>
 </li>
 </ul>
</nav>
Самое приятное, что в коде не нужно заменять угловые скобки < >
и амперсанд & на их html-сущности.
Инлайн код
 <span class="dropdown-toggle-wrapper">
 <span>
 Войти
 </span>
 </span>
 <span class="caret"></span>
 </a>
 </li>
 </ul>
</nav>
```
Самое приятное, что в коде не нужно заменять угловые
скобки `< >` и амперсанд `&` на их html-сущности.


## Раздел четвертый - таблицы

В чистом Маркдауне нет синтаксиса для таблиц, а в GFM
есть.

First Header | Second Header
------------- | -------------
Content Cell | Content Cell
Content Cell | Content Cell

Для красоты можно и по бокам линии нарисовать:

| First Header | Second Header |
| ------------- | ------------- |
| Content Cell | Content Cell |
| Content Cell | Content Cell |

Можно управлять выравниванием столбцов при помощи
двоеточия.

| Left-Aligned | Center Aligned | Right Aligned |
|:------------- |:---------------:| -------------:|
| col 3 is | some wordy text | **$1600** |
| col 2 is | centered | $12 |
| zebra stripes | are neat | ~~$1~~ |

Внутри таблиц можно использовать ссылки, наклонный,
жирный или зачеркнутый текст.

Для всего остального есть обычный HTML

