# Docker file 

## have simple nginx server that run html site

------------------------------------------------------------

# tasks in main.yml

- check if git install or not
- get project form git reop
- built a docker image form Dockerfile located in repo
- create a docker container from image

-------------------------------------------------------------
# lanche project 

```bash
 ansible-playbook -i hosts.ini main.yml
 ```

