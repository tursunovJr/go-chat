# go-chat
Реализация TCP чата для курсовой работы по сетям

# Запуск сервера - ./go-chat

# Создание пользователей - telnet localhost 8888

# commands

- `/nick <name>` - задает имя пользователю, иначе останется anonymous.
- `/join <name>` - подключение к комнате. Если комнаты не существует, то создаётся новая. Пользователь одновременно может находиться в одной комнате.
- `/rooms` - показывает список доступных для подключения комнат.
- `/msg <msg>` - отправка сообщения каждому в группе.
- `/quit` - отключение с сервера чата.
