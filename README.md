# «Репликация и масштабирование. Часть 1» -Абрамов Сергей

---

### Задание 1

На лекции рассматривались режимы репликации master-slave, master-master, опишите их различия.


## Ответ


Master-slave- можно со slave клиенту только читать информации и все изменения в базе подтягиваются с master. Также можно сделать множество slave. 

Master-master с обоих серверов можно читать и записывать информацию , является более отказоустойчивой системой. Каждый сервер является  мастером и слейвом одновременно.

---

### Задание 2 

Выполните конфигурацию master-slave репликации, примером можно пользоваться из лекции.

## Ответ

![1.1](https://github.com/smabramov/Replication-and-scaling-1/blob/95d0bc35d79369563a6ab54e0ceb4e21b304418c/jpg/1.1.jpg)

![Статус slave 1](https://github.com/smabramov/Replication-and-scaling-1/blob/95d0bc35d79369563a6ab54e0ceb4e21b304418c/jpg/%D0%A1%D1%82%D0%B0%D1%82%D1%83%D1%81%20slave%201.jpg)

![Статус slave](https://github.com/smabramov/Replication-and-scaling-1/blob/95d0bc35d79369563a6ab54e0ceb4e21b304418c/jpg/%D0%A1%D1%82%D0%B0%D1%82%D1%83%D1%81%20slave.jpg)

![1.2](https://github.com/smabramov/Replication-and-scaling-1/blob/95d0bc35d79369563a6ab54e0ceb4e21b304418c/jpg/1.2.jpg)

![1.3](https://github.com/smabramov/Replication-and-scaling-1/blob/95d0bc35d79369563a6ab54e0ceb4e21b304418c/jpg/1.3.jpg)

![1.4](https://github.com/smabramov/Replication-and-scaling-1/blob/95d0bc35d79369563a6ab54e0ceb4e21b304418c/jpg/1.4.jpg)

![1.5](https://github.com/smabramov/Replication-and-scaling-1/blob/95d0bc35d79369563a6ab54e0ceb4e21b304418c/jpg/1.5.jpg)

![1.6](https://github.com/smabramov/Replication-and-scaling-1/blob/95d0bc35d79369563a6ab54e0ceb4e21b304418c/jpg/1.6.jpg)

![1.7](https://github.com/smabramov/Replication-and-scaling-1/blob/95d0bc35d79369563a6ab54e0ceb4e21b304418c/jpg/1.7.jpg)


---


### Задание 3*

Выполните конфигурацию master-master репликации. Произведите проверку.

## Ответ


![2.1](https://github.com/smabramov/Replication-and-scaling-1/blob/95d0bc35d79369563a6ab54e0ceb4e21b304418c/jpg/2.1.jpg)

![2.2](https://github.com/smabramov/Replication-and-scaling-1/blob/95d0bc35d79369563a6ab54e0ceb4e21b304418c/jpg/2.2.jpg)

![2.3](https://github.com/smabramov/Replication-and-scaling-1/blob/95d0bc35d79369563a6ab54e0ceb4e21b304418c/jpg/2.3.jpg)

![2.4](https://github.com/smabramov/Replication-and-scaling-1/blob/95d0bc35d79369563a6ab54e0ceb4e21b304418c/jpg/2.4.jpg)

![2.5](https://github.com/smabramov/Replication-and-scaling-1/blob/95d0bc35d79369563a6ab54e0ceb4e21b304418c/jpg/2.5.jpg)

![2.6](https://github.com/smabramov/Replication-and-scaling-1/blob/95d0bc35d79369563a6ab54e0ceb4e21b304418c/jpg/2.6.jpg)

![2.7](https://github.com/smabramov/Replication-and-scaling-1/blob/95d0bc35d79369563a6ab54e0ceb4e21b304418c/jpg/2.7.jpg)

![2.8](https://github.com/smabramov/Replication-and-scaling-1/blob/95d0bc35d79369563a6ab54e0ceb4e21b304418c/jpg/2.8.jpg)

![2.9](https://github.com/smabramov/Replication-and-scaling-1/blob/95d0bc35d79369563a6ab54e0ceb4e21b304418c/jpg/2.9.jpghttps://github.com/smabramov/Replication-and-scaling-1/blob/95d0bc35d79369563a6ab54e0ceb4e21b304418c/jpg/2.9.jpg)

![2.10](https://github.com/smabramov/Replication-and-scaling-1/blob/95d0bc35d79369563a6ab54e0ceb4e21b304418c/jpg/2.10.jpg)


---