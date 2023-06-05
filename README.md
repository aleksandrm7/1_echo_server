## Лабораторная работа “Эхо-сервер”

### Задания для выполнения
1. Создать простой TCP-сервер, который принимает от клиента строку (порциями
по 1 КБ) и возвращает ее. (Эхо-сервер).
2. Сервер должен выводить в консоль служебные сообщения (с пояснениями) при
наступлении любых событий:
i. Запуск сервера;
ii. Начало прослушивания порта;
iii. Подключение клиента;
iv. Прием данных от клиента;
v. Отправка данных клиенту;
vi. Отключение клиента;
vii. Остановка сервера.

![Эхо-сервер](https://github.com/aleksandrm7/1_echo_server/assets/80441149/52151f66-8dd5-4a03-a42a-f6b288b3f732)

3. Напишите простой TCP-клиент, который устанавливает соединение с сервером,
считывает строку со стандартного ввода и посылает его серверу.
4. Клиент должен выводить в консоль служебные сообщения (с пояснениями) при
наступлении любых событий:
i. Соединение с сервером;
ii. Разрыв соединения с сервером;
iii. Отправка данных серверу;
iv. Прием данных от сервера.

![Снимок экрана 2023-06-01 000409](https://github.com/aleksandrm7/1_echo_server/assets/80441149/762447fa-8d00-4327-9aa5-90d65c1ea32e)

![Снимок экрана 2023-05-31 235004](https://github.com/aleksandrm7/1_echo_server/assets/80441149/bce51554-a239-4f2d-94d2-43f5bf3714a0)


### Задания для самостоятельного выполнения


1. Проверьте возможность подключения к серверу с локальной, виртуальной и
удаленной машины.

![Снимок экрана 2023-05-31 232705](https://github.com/aleksandrm7/1_echo_server/assets/80441149/5df72512-0382-4006-aad3-7bc1a2f52bbc)

2. Модифицируйте код сервера таким образом, чтобы он читал строки в цикле до
тех пор, пока клиент не введет “exit”. Можно считать, что это команда разрыва
соединения со стороны клиента.

![Снимок экрана 2023-05-31 235628](https://github.com/aleksandrm7/1_echo_server/assets/80441149/025ba97e-fd17-46d4-9cd3-ba700c459309)
