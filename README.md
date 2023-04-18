# jpoint_2023_infra
Infrastructure for jpoint2023 talk

Для Windows:
1. Все файлы необходимо разместить по пути C:\\Docker\jpoint2023\
2. Для настройки метрик Prometheus необходимо в файле prometheus\prometheus.yml заменить 192.168.206.57 адрес на IP вашей машины (Либо на DNS имя с указанием суфикса. Например - epsilon.domain).
3. Выполнить из C:\\Docker\jpoint2023\ команду: docker-compose up -d
