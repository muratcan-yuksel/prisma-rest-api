# How to fix user myuser cannot access database error

1- check the status of postgresql service
`sudo systemctl status postgresql`

2-Stop it
`sudo systemctl stop postgresql`

3-Recompose docker
`docker-compose up -d`
