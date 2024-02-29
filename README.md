# sys27-mon
 ### Чусовитин Эдуард
# Домашнее задание к занятию «Система мониторинга Zabbix. Часть 2»
---

### Задание 1
Создайте свой шаблон, в котором будут элементы данных, мониторящие загрузку CPU и RAM хоста.

Процесс выполнения
Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.
В веб-интерфейсе Zabbix Servera в разделе Templates создайте новый шаблон
Создайте Item который будет собирать информацию об загрузке CPU в процентах
Создайте Item который будет собирать информацию об загрузке RAM в процентах
### Ответ:
![alt text](https://github.com/ChusovitinEduard/sys27-mon2/blob/main/1.PNG)


---

### Задание 2 

Установите Zabbix Agent на два хоста.

#### Процесс выполнения
1. Выполняя ДЗ, сверяйтесь с процессом отражённым в записи лекции.
2. Установите Zabbix Agent на 2 вирт.машины, одной из них может быть ваш Zabbix Server.
3. Добавьте Zabbix Server в список разрешенных серверов ваших Zabbix Agentов.
4. Добавьте Zabbix Agentов в раздел Configuration > Hosts вашего Zabbix Servera.
5. Проверьте, что в разделе Latest Data начали появляться данные с добавленных агентов.
 
### Ответ:
![alt text](https://github.com/ChusovitinEduard/sys27-mon/blob/main/hosts.PNG)
![alt text](https://github.com/ChusovitinEduard/sys27-mon/blob/main/zab1_mon.PNG)
![alt text](https://github.com/ChusovitinEduard/sys27-mon/blob/main/zab2_mon.PNG)
![alt text](https://github.com/ChusovitinEduard/sys27-mon/blob/main/zabb_log.PNG)

```git clone https://github.com/ChusovitinEduard/sys27-mon```

```cd sys27-mon```

```vi README.md```

```git add README.md```

```git commit -m "task1 git commands"```

```git push origin```

```![alt text](https://github.com/ChusovitinEduard/sys27-mon/blob/main/hosts.PNG)```

```![alt text](https://github.com/ChusovitinEduard/sys27-mon/blob/main/zab1_mon.PNG)```

```![alt text](https://github.com/ChusovitinEduard/sys27-mon/blob/main/zab2_mon.PNG)```

```![alt text](https://github.com/ChusovitinEduard/sys27-mon/blob/main/zabb_log.PNG)```


