Ansible playbook на digital ocean droplet

## Инструкция запуска

1 Заполнить `inventory.ini`

[todo]

```server1 ansible_host=SERVER_IP ansible_user=root```

2 Запустить playbook

```cd ansible```

```ansible-playbook -i ../inventory.ini playbook.yml```

3 Проверка на сервере

```id todoapp```

```ls -ld /opt/todo-api```

```cat /opt/todo-api/app.txt```

```cat /etc/todo-api.env```

```systemctl status todo-api```

```ufw status```