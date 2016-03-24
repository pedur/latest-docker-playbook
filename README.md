# latest-docker-playbook
An Ansible playbook that installs the latest version of Docker on Debian 8 (Jessie) from the official Docker repo.

## How to use:
- Add your server IP in the nodes
- Run the playbook with  ansible-playbook -i nodes deploy-docker.yml -K
