# Дипломный практикум в Yandex.Cloud

1. Конфигурационные файлы terraform лежат в корне данного репозитория:  
[main.tf](./main.tf) - основной файл с описанием провайдера и s3 backend.  
[vpc.tf](./vpc.tf) - файл с описанием сетевых ресурсов.  
[kubernetes.tf](./kubernetes.tf) - файл с описанием виртуальных машин для kubernetes.  

2. 

3. Конфигурация ansible для создания кластера лежит в директории [ansible](./ansible/).

4. Ссылка на git репозиторий с Dockerfile: https://gitlab.com/Orlov-Pavel/my-simple-nginx-app  
Ссылка на dockerhub репозиторий с собранным контейнером: https://hub.docker.com/repository/docker/pavelorlov1/my-simple-nginx/general  

5. Конфигурация мониторинга kubenretes кластера лежит в директории [ansible/files/monitoring/manifests](./ansible/files/monitoring/manifests/) и применяется на этапе создания kubernetes кластера.

6. Ссылка на тестовое приложение: http://158.160.116.241:31073  
Ссылка на web-интерфейс grafana: http://158.160.116.241:32273  
Логин/пароль: admin/admin