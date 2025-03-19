# k8s-monitor-logging
## Описание
Установка сервисов мониторинга и логгинга для kubernetes с помощью ansible

Используемые сервисы:

Elasticsearch

Kibana

Fluentbit

Prometheus

NodeExporter

Оперативная система:

Rocky linux 8.0+

Almalinux 8.0+

RHEL 8.0+

## Установить модули
ansible-galaxy collection install ansible.posix

## Запуск плэйбука
ansible-playbook -i hosts.ini playbook.yml -e "elastic_address=свой адрес"
