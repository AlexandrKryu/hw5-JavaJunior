# Домашнее задание к семинару 5 Java Junior

Разобраться с написанным кодом в классах Server и Client.

1. Если в начале сообщения есть '@4' - то значит отсылаем сообщеине клиенту с идентификатором 4.
2. Если в начале сообщения нет '@' - значит, это сообщение нужно послать остальным клиентам.
3. `*` Добавить админское подключение, которое может кикать других клиентов.
    + При подключении оно посылает спец. сообщение, подтверждающее, что это - админ.
    + Теперь, если админ посылает сообщение kick 4 - то отключаем клиента с идентификатором 4.
4. `**` Подумать, как лучше структурировать программу (раскидать код по классам).