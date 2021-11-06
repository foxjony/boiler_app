# Boiler Android APP Bluetooth 2.0 and 4.0 BLE
https://youtu.be/_GHYtu8T0wQ

Android APP created - https://kodular.io

* Protocol receive: {255,128,8,30,22,15,205,0,183,0,196,0} - 12 Bytes

(255,128 - START HEADER) (8,30 - Время День) (22,15 - Время Ночь) (205,0 - Температура День) (183,0 - Температура Ночь) (196,0 - Текущая температура)

* Protocol send: {2,8,30,21,00,205,0,185,0,31,10,21,8,30,1} - 15 Bytes

(2 - HEADER) (8,30 - Время День) (21,00 - Время Ночь) (205,0 - Температура День) (185,0 - Температура Ночь) (31,10,21 - Текущая Дата) (8,30 - Текущее Время) (1 - День недели 1-7, 1 - неделя)

https://community.kodular.io/t/boiler-android-app-bluetooth-2-0-and-4-0-ble/152499
