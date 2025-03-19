# k8s-monitor-logging

# Установить модули
ansible-galaxy collection install ansible.posix

# Запуск плэйбука
ansible-playbook -i hosts.ini playbook.yml -e "elastic_address=свой адрес"
