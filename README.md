### Ansible
* Dar de alta usuarios: `ansible-playbook -i inventory.yml -e @user.yaml -e @secrets.yaml create.yml`
* Dar de baja usuarios: `ansible-playbook -i inventory.yml -e @user.yaml -e @secrets.yaml delete.yml`
* Reseteo de contraseñas compartidas: `ansible-playbook -i inventory.yml -e shared_passwords.yml reset_shared_passwords.yml`
