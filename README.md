# WLauncher Manual
WLauncher позволяет игрокам удобно играть на серверах
МГЕ без необходимости самостоятельно следить за обновлениями
сервера и устанавливать актуальные версии модов для игры

# WLaucnher Developer
Если Вы имеете доступ к GitHub репозиторию лаунчера, значит
Вы - разработчик / администратор / доверенное лицо. Для
того, чтобы запустить процесс обновления на всех версиях
лаунчера, необходимо загрузить .zip архив главной папки
лаунчера, не изменяя структуру директории, если сам файл
лаунчера не был обновлён, затем скопировать raw ссылку архиа
и вставить в файл link.txt в главной директории репозитория,
затем необходимо установить новую версию в файле version.txt 
в главной директории репозитория. Примерно через 5 - 6 минут
любая другая версия лаунчера станет не актуальной и будет начат
процесс автообновления. Примечание: сам лаунчер также должен
быть отредактирован, и переменная $curversion должна соответствовать
версии в файле version.txt в главной директории репозитория.
Исходники лаунчера доступны только для разработчика / администратора 
/ доверенного лица по запросу к главному администратору сервера /
разработчику. Примечание 2: в главной директории лаунчера должна
находится папка .minecraft с незатронутой структурой файлов
