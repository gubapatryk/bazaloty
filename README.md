# bazaloty




# Ksiazka kucharska:


### Czyszczenie dockera
```
docker rm -f $(docker ps -a -q)
docker volume rm $(docker volume ls -q)
```
### cli psql
```
docker exec -it <id z docker ps> bash
psql -d loty_db -U loty
```
