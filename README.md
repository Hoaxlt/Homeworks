##  Столкнулся с некой проблемой. Написал первый вариант через 2 разных NetworkPolicy с 2 разными Ingress, и по сути задание выполнено, но присутствует лишний разрешенный трафик.
##    Возможно это связано с тем, что делаю через microk8s, хотя вроде тут встроенный Calico. Образец манифеста с networking-policy брал с вебинара.



##  Команды и вывод
![](https://github.com/Hoaxlt/Homeworks/blob/hw12/Screenshot_1.png)

## Схема взаимодействия подов по первому варианту через 2 ingress
![](https://github.com/Hoaxlt/Homeworks/blob/hw12/Screenshot_2.png)

## Второй вариант через 1 ingress и 1 egress, использовал другой манифест (https://github.com/Hoaxlt/Homeworks/blob/hw12/network-policy-2.yaml)

## Команды и вывод
![](https://github.com/Hoaxlt/Homeworks/blob/hw12/Screenshot_3.png)

## схема взаимодействия подов по второму варианту
![](https://github.com/Hoaxlt/Homeworks/blob/hw12/Screenshot_4.png)


# Подскажите, пожалуйста, почему так получается или где я ошибся?
