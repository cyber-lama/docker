# docker
***
1) Создаем файл docker-compose.yml

**Dockerfile** - отвечает за процессы билда образа
Образ - образ линукса, с которого созадем контейнер

**Docker-compose** - инструмент, который позволяет
нам запустить множество контейнеров докера.

**Docker-compose.yml** - файл в котором мы 
пишем нашу конфигурацию

## Docker-compose.yml

```docker-compose.yml
version: '3' # версия docker-compose

#описываем все сервисы, которые docker-compose
#должен сбилдить и запустить 

services: 
    api: 
        build: ./api 
```