University: [ITMO University](https://itmo.ru/ru/)
Faculty: [FICT](https://fict.itmo.ru)
Course: [Introduction to distributed technologies](https://github.com/itmo-ict-faculty/introduction-to-distributed-technologies)
Year: 2023/2024
Group: K4110c
Author: Chizhov Nikita Alexandrovich
Lab: Lab2
Date of create: 04.12.2024
Date of finished: 05.12.2024

1. Развернул minikube cluster при помощи docker ( minikube start --driver=docker )
2. Создал Deployment с 2 репликами и передал переменные окружения REACT_APP_USERNAME и REACT_APP_COMPANY_NAME .yaml
3. Применил манифест ( minikube kubectl -- apply -f deployment.yaml )
4. Создал Service для получения доступа к подам .yaml
5. Применил манифест ( minikube kubectl -- apply -f service.yaml )
6. Проброс портов для доступа через браузер ( minikube service frontend-service )
7. Проверка переменных окружения на странице и какой контейнер 
8. Просмотр логов 
