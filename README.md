# Домашнее задание к занятию 2 «Кластеризация и балансировка нагрузки» Фадеев Михаил

### Задание 1
- Запустите два simple python сервера на своей виртуальной машине на разных портах
- Установите и настройте HAProxy, воспользуйтесь материалами к лекции по [ссылке](2/)
- Настройте балансировку Round-robin на 4 уровне.
- На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy.
     
https://github.com/FadMikhail/9.2_Clustering-and-load-balancing/blob/33cbf260730f64d2a85c48649890d0556b7a5f32/1_haproxy.cfg  
     
![image](https://github.com/FadMikhail/9.2_Clustering-and-load-balancing/assets/132131230/f070f252-bf22-4e2c-8c58-c387b6a7afd3)



### Задание 2
- Запустите три simple python сервера на своей виртуальной машине на разных портах
- Настройте балансировку Weighted Round Robin на 7 уровне, чтобы первый сервер имел вес 2, второй - 3, а третий - 4
- HAproxy должен балансировать только тот http-трафик, который адресован домену example.local
- На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy c использованием домена example.local и без него.

https://github.com/FadMikhail/9.2_Clustering-and-load-balancing/blob/cc580a5d486f8b9bcd2c94b6d095d635964c9e98/2_haproxy.cfg

![image](https://github.com/FadMikhail/9.2_Clustering-and-load-balancing/assets/132131230/cc8ae347-e862-4a43-9037-9878f56071f7)

---

