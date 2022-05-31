# TXT
Group_30 (Homework)

**TXT**
1. Создать внешний репозиторий c названием TXT.

	`Repositories -> New -> Repository name: TXT -> Create repository`

2. Клонировать репозиторий TXT на локальный компьютер.

	`git clone git@github.com:LazarevR/TXT.git`

3. Внутри локального TXT создать файл “new.txt”.
	```
	cd txt
	touch new.txt
	```
4. Добавить файл под гит.

	`git add new.txt`

5. Закоммитить файл.

	`git commit -m "add first new.txt file"`

6. Отправить файл на внешний GitHub репозиторий.

	`git push`

7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.
	```
	ФИО: Руслан Лазарев
	Возраст: 31
	Количество домашних животных: 0
	Будущая желаемая зарплата: $3000
	```
8. Отправить изменения на внешний репозиторий.
	```
	git status
	git checkout main
	git add new.txt
	git commit -m "edit the new.txt file"
	git push
	```
9. Создать файл preferences.txt

	`touch preferences.txt`

10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.
	```
	Любимый фильм: Вечное сияние чистого разума
	Любимый сериал: Californication
	Любимая еда: Солянка
	Любимое время года: Весна
	Страна, которую хотели бы посетить: Норвегия
	```
11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
	```
	-Базовая теория SDLC, STLC
	-Клиент-серверная архитектура
	-HTTP методы запросов на сервер
	-Коды ответов HTTP сервера
	-Структуры HTTP запросов и ответов
	-JSON
	-XML
	-Postman: тестирование API
	-Снятие и чтение логов c внешнего сервера
	-Charles и Fidler: сниффинг http web трафика, перехват мобильного трафика
	-Dev Tools веб браузеров
	-VPN
	-Мобильное тестирование
	-Особенность iOS, Android, гайдлайны
	-Android Studio: сборка android приложений
	-ADB (управление андройд девайсами)
	-Настройка прокси и vpn на iOS и Android
	-Linux Terminal
	-Основы bash скриптинг
	-Основы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join)
	-База данных Postgres
	-Нереляционная база данных Redis
	-Нагрузочное тестирование в Jmeter
	```
12. Сделать коммит в одну строку.

	`git add preferences.txt sklls.txt; git commit -m "add preferences.txt, sklls.txt"`

13. Отправить сразу 2 файла на внешний репозиторий.

	`git push`

14. На веб интерфейсе создать файл bug_report.txt.

	`Repositories -> TXT -> Add file -> Create new file -> "Name your file": bug_report.txt`

15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
	```
	Блок "Commit new file"
	В поле заголовка: create bug_report.txt
	В поле описания: create my first bug_report.txt
	Нажать на кнопку "Commit changes"
	```
16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
	```
	Repositories -> TXT -> bug_report.txt -> Edit this file (иконка карандаша)
	Приступить к редактированию файла в поле "Edit file"
	```
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
	```
	В поле заголовка: можно оставить пустым, а можно указать Update bug_report.txt
	В поле описания: "added first bug report"
	Нажать на кнопку "Commit changes"
	```
18. Синхронизировать внешний и локальный репозиторий TXT

	`git pull`
