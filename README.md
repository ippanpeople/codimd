# Codimd note server

## project discription : use docker compose to build codimd server

## instructions :
- how to customize your own server ?
  1. use editor(vim, nano, etc.) to modify docker-compose.yml
- how to start service ?
  1. clone this repositories
  ```shell
  git clone https://github.com/ippanpeople/codimd.rinlink.jp.git
  ```
  2. cd into the directory
  3. use docker compose to build up the service
  ```shell
  docker-compose up -d
  ```
  4. check whether the container wa started successfully
  ```shell
  docker ps
  ```


  
