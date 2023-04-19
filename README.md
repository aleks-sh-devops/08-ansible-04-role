## Данный плейбук подтягивает роли с помощью requirements clickhouse, vector, lighthouse и производит их установку
=========

# Команда для запуска:  
```
ansible-galaxy install -r requirements.yml -p roles

ansible-playbook -i inventory/prod.yml site.yml
```

## Примечание: playbook работает только с пакетным менеджером yum  

License
-------

MIT

Author Information
------------------

aleks sh
