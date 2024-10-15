# SPRING_BOOT_GERLESSVER

[![CircleCI](https://dl.circleci.com/status-badge/img/gh/edinaldorodriguesceara/spring_boot_gerlessver/tree/master.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/edinaldorodriguesceara/spring_boot_gerlessver/tree/master)


<div align="center">
    <img src="https://spring.io/img/logos/spring-initializr.svg" alt="LOGO_SPRINGBOOT" width="200"/>
</div>

https://github.com/juniormesquitadandao/gerlessver

```bash
git clone git@github.com:edinaldorodriguesceara/spring_boot_gerlessver.git
cd spring_boot_gerlessver

  ARG_USER_UID=$(id -u) ARG_USER_GID=$(id -g) docker compose config
  ARG_USER_UID=$(id -u) ARG_USER_GID=$(id -g) docker compose build
  docker compose up -d
  docker compose exec app bash
    mvn spring-boot:run
    # Brower: http://localhost:8080
    # Press: CTRL+C
    git status
    git add .
    git commit -m 'update'
    git push
    exit
  docker compose down
