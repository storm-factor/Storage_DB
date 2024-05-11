7# «ELK» - Pirogov Anton

###     Задание 1 

![ex1](./screenshots/ex1.png)

###     Задание 2

![ex2](./screenshots/ex2.png)

###     Задание 3

1. Как логи собрать в с nginx в logstash, не совсем понимаю. Как направить логи с nginx который стоит на хосте, в logstash который поднят в docker. 
   В nginx.conf сделана такая запись - access_log syslog:server=logstash:5140, Как он будет направлять туда логи если nginx не знает что такое logstash
   Возможно оно будет работать если прописать там ip контейнера, но это бред и почему высвечивается данное сообщение:

![ex3-1](./screenshots/qw1.png)
![ex3-2](./screenshots/qw2.png)
![ex3-3](./screenshots/qw3.png)
![ex3-4](./screenshots/qw4.png)
[compose.yml](./files/compose.yml)
