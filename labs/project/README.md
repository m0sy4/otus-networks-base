# Лабораторная работа - Настройка и проверка расширенных списков контроля доступа

## Топология

![alt text](topology.png)

## Таблица адресации

![alt text](address.png)

## Таблица VLAN

![alt text](vlan.png)

## Часть 1. Настройка сетей VLAN на коммутаторах.

### Шаг 1. Создание сетей VLAN на коммутаторах.

![alt text](p1/s1/1.png)

![alt text](p1/s1/2.png)

![alt text](p1/s1/3.png)

### Шаг 2. Настройка портов на коммутаторах.

![alt text](p1/s2/1.png)

![alt text](p1/s2/2.png)

![alt text](p1/s2/3.png)

### Шаг 3. Проверка.

![alt text](p1/s3/1.png)

![alt text](p1/s3/2.png)

![alt text](p1/s3/3.png)

## Часть 2. Настройка Trunk и резервирования

### Шаг 1. Настройка Trunk соединений.

![alt text](p2/s1/1.png)

![alt text](p2/s1/2.png)

![alt text](p2/s1/3.png)

### Шаг 2. Настройка режима STP.

![alt text](p2/s2/1.png)

![alt text](p2/s2/2.png)

![alt text](p2/s2/3.png)

### Шаг 3. Проверка Root Bridge и резервирования

![alt text](p2/s3/1.png)

![alt text](p2/s3/2.png)

### Шаг 4. Проверка переключения на резервный канал

![alt text](p2/s4/1.png)

![alt text](p2/s4/2.png)

![alt text](p2/s4/3.png)

### Шаг 5. Настройка PortFast на портах ПК

![alt text](p2/s5/1.png)

![alt text](p2/s5/2.png)

![alt text](p2/s5/3.png)

### Шаг 6. Включение BPDU Guard на портах ПК

![alt text](p2/s6/1.png)

![alt text](p2/s6/2.png)

![alt text](p2/s6/3.png)

### Шаг 7. Проверка итоговых конфигураций

![alt text](p2/s7/1.png)

![alt text](p2/s7/2.png)

![alt text](p2/s7/3.png)

## Часть 3. Настройка IPv4 и Router-on-a-Stick

### Шаг 1. Настройка интерфейсов на R1

![alt text](p3/s1/1.png)

### Шаг 2. Настройка интерфейсов на R2

![alt text](p3/s2/1.png)

### Шаг 3. Настройка интерфейсов на R3

![alt text](p3/s3/1.png)

### Шаг 4. Настрйока Management VLAN на коммутаторах

![alt text](p3/s4/1.png)

![alt text](p3/s4/2.png)

![alt text](p3/s4/3.png)

### Шаг 5. Проверки сетевой связанности маршрутизаторов и коммутаторов

![alt text](p3/s5/1.png)

![alt text](p3/s5/2.png)

![alt text](p3/s5/3.png)

![alt text](p3/s5/4.png)

![alt text](p3/s5/5.png)

![alt text](p3/s5/6.png)

## Часть 4. Настройка DHCPv4

![alt text](p4/1.png)

### Шаг 1. Исключение служебных адресов и создание пулов на R1

![alt text](p4/s1/1.png)

### Шаг 2. Исключение служебных адресов и создание пулов на R2

![alt text](p4/s2/1.png)

### Шаг 3. Настройка ПК

![alt text](p4/s3/1.png)

![alt text](p4/s3/2.png)

DHCP включен на PC-B — PC-G

### Шаг 4. Проверка адресов ПК

![alt text](p4/s4/1.png)

![alt text](p4/s4/2.png)

### Шаг 5. Проверка DHCP на R1 и R2

![alt text](p4/s5/1.png)

![alt text](p4/s5/2.png)

### Шаг 6. Ping шлюзов с ПК

![alt text](p4/s6/1.png)

![alt text](p4/s6/2.png)

![alt text](p4/s6/3.png)

![alt text](p4/s6/4.png)

![alt text](p4/s6/5.png)

![alt text](p4/s6/6.png)

![alt text](p4/s6/7.png)

### Шаг 7. Ping между ПК

PC-B → PC-E

VLAN30 → VLAN40

![alt text](p4/s7/1.png)


PC-F → PC-G

VLAN120 → VLAN140

![alt text](p4/s7/2.png)


## Часть 5. Настройка IPv6, SLAAC и DHCPv6

![alt text](p5/1.png)

### Шаг 1. IPv6-маршрутизация на R1 и R2

![](p5/s1/1.png)

![alt text](p5/s1/2.png)

### Шаг 2. Настройка адресов IPv6, VLAN и DHCPv6 на R1

![alt text](p5/s2/1.png)

### Шаг 3. Настройка адресов IPv6, VLAN и DHCPv6 на R2

![alt text](p5/s3/1.png)

### Шаг 4. Ping R1 <-> R2 по IPv6

![alt text](p5/s4/1.png)

![alt text](p5/s4/2.png)

### Шаг 5. Настройка SLAAC на ПК

PC-B
![alt text](p5/s5/1.png)


PC-C
![alt text](p5/s5/2.png)

PC-E
![alt text](p5/s5/3.png)

PC-G
![alt text](p5/s5/4.png)

### Шаг 6. Настройка DHCPv6 на ПК

PC-A
![alt text](p5/s6/1.png)

PC-D 
![alt text](p5/s6/2.png)

PC-F 
![alt text](p5/s6/3.png)

### Шаг 7. Проверка DHCPv6 на маршрутизаторах

![alt text](p5/s7/1.png)

![alt text](p5/s7/2.png)

### Шаг 8. Проверка связи ПК со шлюзом

![alt text](p5/s8/1.png)

![alt text](p5/s8/2.png)

![alt text](p5/s8/3.png)

![alt text](p5/s8/4.png)

### Шаг 9. Проверка связи между ПК из разных VLAN

PC-B → PC-A

VLAN30 → VLAN20

![alt text](p5/s9/1.png)

PC-F → PC-G

VLAN120 → VLAN140

![alt text](p5/s9/2.png)

### Шаг 10.  Проверка таблиц IPv6-маршрутизации

![alt text](p5/s10/1.png)

![alt text](p5/s10/2.png)

## Часть 6. Статическая и динамическая маршрутизация

Логика маршрутизации

               209.165.200.1
                  R3 Lo1
                    |
                    |
                   R3
              209.165.200.225
                    |
            Static Default Route
                    |
              209.165.200.230
                   R1
                    |
              10.255.0.1
                    |
                OSPF Area 0
                    |
              10.255.0.2
                   R2

### Шаг 1. Статический маршрут по умолчанию на R1

![alt text](p6/s1/1.png)

### Шаг 2. Настройка OSPF на R1

OSPF process ID = 56

Area = 0

Router ID R1 = 1.1.1.1

Router ID R2 = 2.2.2.2

![alt text](p6/s2/1.png)


###  Шаг 3. Отключение OSPF Hello-пакеты в пользовательских VLAN

![alt text](p6/s3/1.png)

###  Шаг 4. Маршрут по умолчанию через OSPF

![alt text](p6/s4/1.png)

### Шаг 5. Настройте OSPF на R2

![alt text](p6/s5/1.png)

### Шаг 6. Проверка OSPF-маршрутов на маршрутизаторах

![alt text](p6/s6/1.png)

![alt text](p6/s6/2.png)

### Шаг 7. Проверка маршрутизации на ПК

HQ → Branch

PC-B → PC-F

![alt text](p6/s7/1.png)

Branch → HQ

PC-F → PC-A

![alt text](p6/s7/2.png)

### Шаг 8. Настройка IPv6-маршрутизации на R1/R2

![alt text](p6/s8/1.png)

![alt text](p6/s8/2.png)

![alt text](p6/s8/3.png)

![alt text](p6/s8/4.png)

### Шаг 9. Проверка IPv6-маршрутизации на ПК

HQ → Branch

PC-B → PC-F

![alt text](p6/s9/1.png)

Branch → HQ

PC-F → IPv6-шлюз VLAN 30 HQ

![alt text](p6/s9/2.png)


### Шаг 10. Итоговая проверка OSPF

![alt text](p6/s10/1.png)

![alt text](p6/s10/2.png)


## Часть 7. ACL

### Шаг 1. Определение политик безопасности

| № | Источник | Назначение | Политика |
|---:|---|---|---|
| 1 | HQ Guest VLAN 40 | Все корпоративные IPv4-сети | **Deny** |
| 2 | Branch Guest VLAN 140 | Все корпоративные IPv4-сети | **Deny** |
| 3 | HQ Guest / Branch Guest | Internet | **Permit** |
| 4 | HQ Users VLAN 30 | Management VLAN 10 и 110 по SSH | **Deny TCP/22** |
| 5 | Branch Users VLAN 120 | Management VLAN 10 и 110 по SSH | **Deny TCP/22** |
| 6 | Administration VLAN 20 | Management | **Permit** |
| 7 | Остальной пользовательский трафик | Разрешённые сети | **Permit** |

### Шаг 2. ACL для HQ Guest

![alt text](p7/s2/1.png)

### Шаг 3. ACL для HQ Users

![alt text](p7/s3/1.png)

### Шаг 4. ACL для Branch Guest

![alt text](p7/s4/1.png)

### Шаг 5. ACL для Branch Users

![alt text](p7/s5/1.png)

### Шаг 6. Проверка HQ Guest

PC-E → шлюз 

![alt text](p7/s6/1.png)

PC-E → S1

![alt text](p7/s6/2.png)

PC-E → PC-A

![alt text](p7/s6/3.png)

PC-E → PC-B

![alt text](p7/s6/4.png)

PC-E → PC-F

![alt text](p7/s6/5.png)

### Шаг 7. Проверка Branch Guest

PC-G → шлюз 

![alt text](p7/s7/1.png)

PC-G → S3

![alt text](p7/s7/2.png)

PC-E → PC-F

![alt text](p7/s7/3.png)

PC-E → HQ 

![alt text](p7/s7/4.png)


### Шаг 8. Проверка Users

PC-B → Management

![alt text](p7/s8/1.png)

PC-F → Branch

![alt text](p7/s8/2.png)

## Часть 8. Настройка NAT/PAT

Логическая схема

                    INTERNET
                        |
                       R3
                        |
         209.165.200.224/29
                        |
                       R1
                NAT / PAT EDGE
                   /         \
                  /           \
      209.165.200.229       209.165.200.230
          Static NAT             PAT
              |                   |
            PC-A              остальные


### Шаг 1. Внешний NAT-интерфейс

![alt text](p8/s1/1.png)

### Шаг 2. Внутренние NAT-интерфейсы 

![alt text](p8/s2/1.png)

### Шаг 3. ACL для адресов NAT

![alt text](p8/s3/1.png)

### Шаг 4. PAT через R1

![alt text](p8/s4/1.png)

### Шаг 5. Проверка PAT

![alt text](p8/s5/2.png)

![alt text](p8/s5/3.png)

![alt text](p8/s5/4.png)

![alt text](p8/s5/5.png)

![alt text](p8/s5/6.png)

### Шаг 6. Static NAT для PC-A

![alt text](p8/s6/1.png)

![alt text](p8/s6/2.png)

![alt text](p8/s6/3.png)

![alt text](p8/s6/4.png)

## Часть 9. Настройка и проверка CDP и LLDP

### Шаг 1. Проверка работы CDP на роутерах и маршрутизаторах

![alt text](p9/s1/1.png)

![alt text](p9/s1/2.png)

![alt text](p9/s1/3.png)

![alt text](p9/s1/4.png)

![alt text](p9/s1/5.png)

### Шаг 2. Отключение CDP на всех устройствах для проверки LLDP

Отключение командой no cdp run

![alt text](p9/s2/1.png)

Аналогично на других устройствах

### Шаг 3. Проверка LLDP 

Командой lldp run запускаем LLDP на всех устройствах

Проверяем

![alt text](p9/s3/1.png)

![alt text](p9/s3/2.png)

![alt text](p9/s3/3.png)

![alt text](p9/s3/4.png)

![alt text](p9/s3/5.png)

## Часть 10. Настройка NTP 

Схема NTP

                           R1
                     NTP MASTER
                      Stratum 4
                    /     |      \
                   /      |       \
                 S1       S2       R2
                                    \
                                     \
                                      S3

### Шаг 1. Проверка и настройка R1 как NTP Master

![alt text](p10/s1/1.png)

### Шаг 2. Настройка клиентов

![alt text](p10/s2/1.png)

![alt text](p10/s2/2.png)

![alt text](p10/s2/3.png)

![alt text](p10/s2/4.png)

### Шаг 3. Проверка работы NTP

![alt text](p10/s3/1.png)

![alt text](p10/s3/2.png)

![alt text](p10/s3/3.png)

![alt text](p10/s3/4.png)

## Часть 11. Защищённое удалённое управление (SSH)

Username:    SSHadmin \
Password:    cisco123 \
Domain:      lab.com \
SSH version: 2 \
RSA:         1024 bit

### Шаг 1. Настройка SSH на R1/2 и S1/2/3

![alt text](p11/s1/1.png)

![alt text](p11/s1/2.png)

![alt text](p11/s1/3.png)

![alt text](p11/s1/4.png)

![alt text](p11/s1/5.png)

### Шаг 2. Ограничение SSH административной сетью  

![alt text](p11/s2/1.png)

![alt text](p11/s2/2.png)

![alt text](p11/s2/3.png)

![alt text](p11/s2/4.png)

### Шаг 3. Проверка SSH и ограничений

PC-A (VLAN 20 - Административный)

![alt text](p11/s3/1.png)

![alt text](p11/s3/2.png)

![alt text](p11/s3/3.png)

PC-B (VLAN 30)

![alt text](p11/s3/4.png)

PC-F (VLAN 120)

![alt text](p11/s3/5.png)

PC-E (VLAN 40)

![alt text](p11/s3/6.png)