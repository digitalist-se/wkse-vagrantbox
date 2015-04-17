### D8 Vagrant/Ansible template

Requirements: Ansible 1.9-dev:
sudo pip install --upgrade git+https://github.com/ansible/ansible.git@devel

Always use the latest versions of vagrant/Virtualbox if possible.

### Github OAuth token
Take make Composer install to work you need to change [put your github oauth token here] to your github OAuth token in provision/roles/composer/tasks/main.yml
If you don't have a github a token, see: https://help.github.com/articles/creating-an-access-token-for-command-line-use/
