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