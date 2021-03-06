Приветствую вас!

# **Git** — система управления версиями с распределенной архитектурой.

***Основные команды:***

* *git init*

* *git add*

* *git status*

* *git commit -m "  "*

* *git branch*

* *git log*

* *git diff*

* *git checkout*

* *git merge*

* *git push*

* *git pull*

## git init -  

это команда создаст git репозиторий в Вашем проекте.

## git add - 

команда git add добавляет содержимое рабочей директории в индекс (staging area) для последующего коммита. 

## git status - 

команда git status показывает состояния файлов в рабочей директории и индексе: какие файлы изменены, но не добавлены в индекс; какие ожидают коммита в индексе.

## git commit -m" " - 

берёт файлы из staging area и “фиксирует” их в Ваш локальный репозиторий. В кавычки следует вставить краткое описание изменений для конкретного коммита.

## git branch - 

создает сущность, называемую branch(ветвь). Ветвь - это точная копия Ваших файлов.

## git log - 

перечисляет коммиты, сделанные в репозитории в обратном к хронологическому порядке — последние коммиты находятся вверху.

## git diff - 

команда git diff используется для вычисления разницы между любыми двумя коммитами.

## git checkout - 

позволит Вам переключить контроль над созданной Вами веткой и работать в её пределах.

## git merge - 

находясь в Master(главной) ветви, Вы можете использовать эту команду, чтобы взять коммиты из любой из ветвей и соединить их вместе.

## git push - 

команда git push используется для установления связи с удалённым репозиторием, вычисления локальных изменений отсутствующих в нём, и собственно их передачи в вышеупомянутый репозиторий.

## git pull - 

если Вы работаете над одним и тем же проектом с несколькими людьми, то эта команда позволит загрузить последнюю версию из удалённого репозитория и обновить вашу локальную версию.

Чтобы вставить изображение в текст, пишем следующее: ![Логотип Git](git.jpg)
Для обозначения цитат в языке Markdown используется знак «больше» «>». Например: 

> Никогда не ошибается тот, кто ничего не делает.
