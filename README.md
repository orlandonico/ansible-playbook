# Ansible Test

Per prima cosa installare ansible. Per farlo eseguire il comando:
```
sudo pacman -Sy ansible
```

Fare il clone dei propri ruoli nella cartella `roles` e aggiungere il nome dei ruoli in `local.conf`
 
I ruoli seguenti vanno installati con il comando `sudo ansible-playbook local.yml`
 
* `ansible-role-docker`
* `ansible-general`
* `ansible-samba`

I ruoli seguenti vanno installati con il comando `ansible-playbook local.yml`

* `ansible-role-rust`
* `ansible-dooraim-role`
