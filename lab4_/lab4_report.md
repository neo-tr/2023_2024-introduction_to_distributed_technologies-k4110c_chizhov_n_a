University: [ITMO University](https://itmo.ru/ru/)  
Faculty: [FICT](https://fict.itmo.ru)  
Course: [Introduction to distributed technologies](https://github.com/itmo-ict-faculty/introduction-to-distributed-technologies)  
Year: 2023/2024  
Group: K4110c  
Author: Chizhov Nikita Alexandrovich  
Lab: Lab4 
Date of create: 13.12.2024  
Date of finished: .12.2024   

1. Запустил Minikube с CNI плагином Calico, двумя нодами и докером как драйвером виртуализации ( minikube start --nodes=2 --cni=calico --driver=docker)
2. Проверил количество нод ( kubectl get nodes )
3. Проверил работу плагина Calico ( kubectl get pods -n kube-system )
   ![1](img/1.jpg)
4.
