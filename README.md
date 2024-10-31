**Лабораторная работа "Конфигурация AP Group, WLANs на Cisco WLC"**

![alt text](https://github.com/mezhibo/wireless-elements/blob/cf6b7a5dfce7b025989b34c8e69d673385b9ee69/IMG/1.png)

Соберите аналогичную топологию в Cisco Packet Tracer.

Критерии выполнения:

1. На WLC необходимо создать дополнительные AP Group. AP1 должен быть в группе WIFI_Group1, AP2 в группе WIFI_Group2.

2. Должны быть созданы два Wireless Lans: WIFI_Default и WIFI2. Оба WLAN должны имет протокол аутентификации - WPA_PSK.

3. На AP1 должен раздавать только WIFI_Default, на AP2 - только WIFI2.

4. Один smartphone должен подключаться к WIFI_Default, другой к WIFI2.

Замечение: не забывайте про конфигурацию DHCP сервера на маршрутизаторе для раздачи адресов.

Отправьте готовый файл pkt


**Решение**

В моём случае симуляции в CPT default-group не корректно настраивалась, не сохраняла изменения. Поэтому была создана группа WIFI_Group1.

Результат выполнения:

![alt text](https://github.com/mezhibo/wireless-elements/blob/cf6b7a5dfce7b025989b34c8e69d673385b9ee69/IMG/2.png)

Настройки Wireless LANs:

![alt text](https://github.com/mezhibo/wireless-elements/blob/cf6b7a5dfce7b025989b34c8e69d673385b9ee69/IMG/3.png)

![alt text](https://github.com/mezhibo/wireless-elements/blob/cf6b7a5dfce7b025989b34c8e69d673385b9ee69/IMG/4.png)


Настройки AR Groups:


![alt text](https://github.com/mezhibo/wireless-elements/blob/cf6b7a5dfce7b025989b34c8e69d673385b9ee69/IMG/5.png)

![alt text](https://github.com/mezhibo/wireless-elements/blob/cf6b7a5dfce7b025989b34c8e69d673385b9ee69/IMG/6.png)


[РКТ-ФАЙЛ](https://github.com/mezhibo/wireless-elements/blob/cf6b7a5dfce7b025989b34c8e69d673385b9ee69/IMG/mezhib-wifi-elements.pkt)
