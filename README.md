# ansible-drupal-civicrm
- **Requirements on server**
  - Debian 8

apt update
apt upgrade
apt install python
apt install aptitude

- **Requirements on ansible master**

edit /etc/ansible/hosts
[drupal]
ip_address
edit passwords and domain inside drupal.yml

- **Start playbook**

ansible-playbook drupal.yml

- **Confiure S3 backup and migrate module inside drupal**
