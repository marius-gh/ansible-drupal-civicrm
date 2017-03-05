# ansible-drupal-civicrm
- **Requirements on server**
  - Debian 8
```bash
  apt update
  apt upgrade
  apt install python
  apt install aptitude
```
- **Requirements on ansible master**

  edit /etc/ansible/hosts
```bash
[drupal]
ip_address
```

edit passwords and domain inside drupal.yml

- **Start playbook**
```bash
ansible-playbook drupal.yml
```
Confiure S3 backup and migrate module inside drupal and name it s3backup because a cron job will use than name

