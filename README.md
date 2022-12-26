# temscirep

> LaTeX **TEM**plate for a **SCI**entific **REP**ort on a grant or commercial contract in Russian according to **GOST**. Since the report is in Russian, we use this language exclusively in the repository.


## Файлы и папки

В процессе работы над отчетом могут (и должны) редактироваться следующие файлы:

- `main.tex` - основной файл проекта. При добавлении нового раздела отчета в папку `content`, ссылка на раздел должна быть добавлена в данный файл

- `content/` - папка для хранения основных разделов отчета. Ссылки на разделы должны быть указаны в файле `main.tex`. В репозитории данная папка содержит раздел с рекомендациями по оформлению (`content/99_demo.tex` и файлы с подразделами)

- `images/` - папка для хранения графических изображений. Отметим, что в latex-команде `\includegraphics` достаточно указывать только имя файла (без указания папки). В репозитории данная папка содержит несколько примеров изображений

- `biblio.bib` - файл с библиографией в bibtex-формате. Поля библиографической записи (англоязычные) автоматически приводятся к нижнему регистру. При необходимости сохранения заглавных букв, их нужно заключать в фигурные скобки

- `commands.tex` - файл содержит различные полезные команды (выделение векторов, матриц, тензоров и т.п.). В конце данного файла могут быть заданы собственные команды и сокращения

- `special/title.tex` - файл содержит титульный лист отчета. См. также титульный лист для мегагранта в файле `special/title_mega.tex` (переключение на мегагрант осуществляется посредством задания команды `\mega` в файле `main.tex`)

- `special/performers.tex` - файл содержит список исполнителей отчета

- `special/abstract.tex` - файл содержит реферат отчета

- `special/definition.tex` - файл содержит перечень обозначений и сокращений

- `special/intro.tex` - файл содержит введение к отчету

- `special/conclusion.tex` - файл содержит выводы по отчету


## Использование

Данный репозиторий (архив) может быть загружен и собран в системе `overleaf`, либо локально на компьютере при наличии стандартной сборки `tex/latex`. Вы можете свободно использовать данный шаблон для любых своих отчетов при указании в основном LaTeX файле проекта и в README файле проекта (при наличии) ссылки на данный репозиторий (https://github.com/AndreiChertkov/temscirep).


## Автор

- [Andrei Chertkov](https://github.com/AndreiChertkov)


## Комментарий

На основе данного шаблона было успешно подготовлено множество различных отчетов по коммерческим контрактам и государственным грантам, однако текущая версия шаблона в репозитории является черновой и будет в дальнейшем уточняться. Использование данного шаблона не гарантирует отсутствие замечаний заказчика по оформлению, но вероятность их отсутствия довольно высока.