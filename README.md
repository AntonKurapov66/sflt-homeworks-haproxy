# Домашнее задание к занятию "Кластеризация и балансировка нагрузки" - `Курапов Антон`


### Задание 1
* Запустите два simple python сервера на своей виртуальной машине на разных портах
* Установите и настройте HAProxy, воспользуйтесь материалами к лекции по ссылке
* Настройте балансировку Round-robin на 4 уровне.
* На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy.

![alt text](https://github.com/AntonKurapov66/sflt-homeworks-haproxy/blob/main/img/1_1.PNG)
![alt text](https://github.com/AntonKurapov66/sflt-homeworks-haproxy/blob/main/img/1_0.PNG)

файл: https://github.com/AntonKurapov66/sflt-homeworks-haproxy/blob/main/config/haproxy_task1.cfg
### Задание 2
* Запустите три simple python сервера на своей виртуальной машине на разных портах
* Настройте балансировку Weighted Round Robin на 7 уровне, чтобы первый сервер имел вес 2, второй - 3, а третий - 4
* HAproxy должен балансировать только тот http-трафик, который адресован домену example.local
* На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy c использованием домена example.local и без него.

  ![alt text](https://github.com/AntonKurapov66/sflt-homeworks-haproxy/blob/main/img/2_0.PNG)
  ![alt text](https://github.com/AntonKurapov66/sflt-homeworks-haproxy/blob/main/img/2_1.PNG)

файл: https://github.com/AntonKurapov66/sflt-homeworks-haproxy/blob/main/config/haproxy_task2.cfg
