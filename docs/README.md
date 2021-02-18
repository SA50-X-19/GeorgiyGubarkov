# Требования

## Требования к репозиторию

Необходимо создать приватный репозитори в организации SA50-X-19. Это возможно сделать, если вас добавили в неё. Чтобы посмотреть добавили вас или нет - откройте таблицу, в которую необходимо было внести username от GitHub. Аккаунты выделенные зелёным - добавлены. После добавления должно прийти письмо на почту с подтверждением регистрации в организации.
Если вы были добавлены и у вас есть возможность перейти в организацию, то:

1. Откройте [GitHub](https://github.com/)
2. Перейдите в "Ваши организации"
![Организации](./asserts/organizations.png)
1. Перейдите в организацию SA50-X-19
![SA50-X-19](./asserts/SA50-x-19.png)
1. Выберите New
![New repo](./asserts/create_repo.jpg)
1. Создайте ???публичный??? репозиторий с обязательным создание README файла
1. После создания репозитория на GitHub установите его локально
1. Для скачивания используется следующая команда(откройте диск, где будете хранить репозиторий и запустите GitBush/cmd/bash)
```git
git clone {ссылка https}
```
8. В клонированном репозитории создайте ветку gh-page
---
## Требования к коммитам

1. Все задания делать в новых ветках созданных из master, если не указано иное
2. В master никаких коммтитов не делать
3. В master не мержить
### Формат коммитов

* init: - используется для начала проекта/таска. Примеры:
  * init: start youtube-task
  * init: start mentor-dashboard task

* feat: - это реализованная новая функциональность из технического задания (добавил поддержку зумирования, добавил footer, добавил карточку продукта). Примеры:
  * feat: add basic page layout
  * feat: implement search box 
  * feat: implement request to youtube API
  * feat: implement swipe for horizontal list
  * feat: add additional navigation button
  * feat: add banner
  * feat: add social links
  * feat: add physical security section
  * feat: add real social icons

* fix: - исправил ошибку в ранее реализованной функциональности. Примеры:
  * fix: implement correct loading data from youtube
  * fix: change layout for video items to fix bugs
  * fix: relayout header for firefox
  * fix: adjust social links for mobile

* refactor: - новой функциональности не добавлял / поведения не менял. Файлы в другие места положил, удалил, добавил. Изменил форматирование кода (white-space, formatting, missing semi-colons, etc). Улучшил алгоритм, без изменения функциональности. Примеры:
  * refactor: change structure of the project
  * refactor: rename vars for better readability
  * refactor: apply eslint
  * refactor: apply prettier

* docs: - используется при работе с документацией/readme проекта. Примеры:
  * docs: update readme with additional information
  * docs: update description of run() method

## Формат сдачи практических

