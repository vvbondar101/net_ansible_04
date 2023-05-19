# Домашняя работа к занятию 4 «Работа с roles»

1. Для выполнения плэйбуков подготавливаются три виртуальные машины в Yandex Cloud при помощи Terraform. См. директорию terraform_vms.
2. Плэйбуки:
    - Плэйбук Ansible для установки LightHouse - lighthouse.yml
    - Плэйбук Ansible для установки Vector - vector.yml
    - Плэйбук Ansible для установки clickHouse - site.yml
3. Перед запуском плэйбука необходимо:
    - выполнить установку ролей ansible-galaxy install -r requirements.yml -p roles
    - указать переменную в файле group_vars/lighthouse/vars.yml nginx_user_name - имя пользователя nginx
4. Плэйбук устанавливает Nginx, clickhouse и lighthouse.
5. После запуска плэйбука необходимо подключиться к lighthouse при помощи Web браузера.
