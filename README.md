# SPRING_BOOT_GERLESSVER



<div align="center">
    <img src="https://spring.io/img/logos/spring-initializr.svg" alt="LOGO_SPRINGBOOT" width="200"/>
</div>

https://github.com/juniormesquitadandao/gerlessver

```bash
git clone ...
cd project

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
