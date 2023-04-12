## Промежуточная аттестация

### Реализовать консольное приложение "Заметки" на языке программирования Python с сохранением, чтением, добавлением, редактированием и удалением заметок.

Заметка должна содержать идентификатор, заголовок, тело заметки и дату/время создания или последнего
изменения заметки.

Сохранение заметок необходимо сделать в формате json или csv формат (разделение полей рекомендуется
делать через точку с запятой).

Реализацию пользовательского интерфейса студент может делать как ему удобнее, можно делать как
параметры запуска программы (команда, данные), можно делать как запрос команды с консоли и
последующим вводом данных, как-то ещё, на усмотрение студента.

### Выполнено:

Консольное приложение разработано на языке программирования Python в парадигме ООП и
c использованием паттерна MVP.

Реализован следующий функционал:

* Чтение записную книжку из файла в формате csv;
* Вывод списка всех заметок в консоль;
* Вывод списка заметок, отфильтрованных по дате, в консоль;
* Добавление заметки;
* Редактирование заметки (по номеру-идентификатору);
* Удаление заметки (по номеру-идентификатору)
* Сохранение изменения (запись изменений в файл)
* Завершение работы приложения (при наличии несохраненных изменений пользователю
предлагается сохранить изменения).