# MaGK установка и конфигурация прокси vs nginx





## параметры host:<br>
*   `environments/dev/inventory_file`
  
## Сборка имеджа и конфигурация docker конетйнера.

* `ansible-playbook playbooks/playbook_app_swarm.yml`

## Деплой контейнера в docker swarm

* `ansible-playbook playbooks/playbook_update_app.yml`
