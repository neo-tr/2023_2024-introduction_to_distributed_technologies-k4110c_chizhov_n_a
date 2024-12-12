University: [ITMO University](https://itmo.ru/ru/)
Faculty: [FICT](https://fict.itmo.ru)
Course: [Introduction to distributed technologies](https://github.com/itmo-ict-faculty/introduction-to-distributed-technologies)
Year: 2023/2024
Group: K4110c
Author: Chizhov Nikita Alexandrovich
Lab: Lab3
Date of create: 11.12.2024
Date of finished: 12.12.2024  

1. Развернул minikube cluster при помощи docker ( minikube start --driver=docker )
2. Создал configmap.yaml
3. Применил configmap.yaml ( kubectl apply -f configmap.yaml )
4. Убедился что создано ( kubectl get configmap react-app-config -o yaml )
   ![1](1.png)
5.
