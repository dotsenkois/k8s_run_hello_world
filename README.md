k8s_run_hello_world
=========

Роль создает деплоймент hello-node образа k8s.gcr.io/echoserver:1.4

Requirements
------------



Role Variables
--------------


Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

---
- hosts: minikube
  roles:
    - install_minikube
    - k8s_run_hello_world


License
-------

BSD

Author Information
------------------
dotsenkois
Илья Доценко.
Специально для онлайн-школы netology.ru
