#Contributing to Lubimovka-21

##Памятка по работе с гитом

1. Клонируем репозиторий git clone git@github.com:kirillzhakin/lubimovka-21.git)
2. Переходим в ветку develop git checkout develop
3. Вытягиваем текущее состояние ветки git pull
4. Создаем новую ветку для работы над фичей git checkout -b 'feat/17-add-git-mini-help' (17 - номер issue, add-git-mini-help - краткое название фичи)
5. Вносим изменения и коммитим git commit -m "Сообщение о коммите #17" (17 - номер issue, чтобы github сам связал коммит с issue)
6. Пушим git push feat/17-add-git-mini-help (feat/17-add-git-mini-help - название удаленной ветки)
7. Идем в гитхаб и видим кнопку во вкладке Code Compare & pull request
8. Жмем и выбираем из какой ветки в какую делаем пулл-реквест. У нас - в develop
9. В комментарии добавляем номер фичи (#17 в этом случае)
10. Назначаем ревьюера.


Как-то так. Но я все операции с гитом делаю из VSC