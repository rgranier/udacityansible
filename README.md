# udacityansible

## Cheats

apt install -y ansible

cd
mkdir -p roles/nginx/tasks

localhost ansible_connection=local

ansible-playbook -i myinventory main.yml

## Make the directories under a roles (short)

under roles/appname

tasks
templates
vars

cd roles/<app>/

## Make the directories under a roles (large)

under roles/appname

defaults
handlers
meta
molecule
tasks
templates
vars

cd roles/<app>/

mkdir defaults handlers meta molecule tasks templates vars

## Revision History
6/19/20 A change on Ubuntu

6/19/20 Making changes to Readme on Desktop
