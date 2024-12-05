University: [ITMO University](https://itmo.ru/ru/)
Faculty: [FICT](https://fict.itmo.ru)
Course: [Introduction to distributed technologies](https://github.com/itmo-ict-faculty/introduction-to-distributed-technologies)
Year: 2023/2024
Group: K4110c
Author: Chizhov Nikita Alexandrovich
Lab: Lab1
Date of create: 03.12.2024
Date of finished: 03.12.2024

1. Установил Docker на рабочий компьютер с оффициального сайта через .exe
2. Установил Minikube с оффициального сайта через .exe
3. Развернул minikube cluster при помощи docker ( minikube start --driver=docker )
4. Написал манифес .yaml
5. Применил манифест ( minikube kubectl -- apply -f vault-pod.yaml )
6. Создание сервиса для доступа к поду ( minikube kubectl -- expose pod vault --type=NodePort --port=8200 )
7. Проброс порта ( minikube kubectl -- port-forward service/vault 8200:8200 )
8. Найти токен в логах ( minikube kubectl -- logs pod/vault )
9. Зайти ( http://localhost:8200 )

<image src="[lab1/part.png](https://github.com/neo-tr/2023_2024-introduction_to_distributed_technologies-k4110c_chizhov_n_a/blob/main/lab1/part.png?raw=true)" alt="Описание изображения">
