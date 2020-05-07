```sh
docker ps # list container ID
docker exec -it --user=root CONTAINER_ID LINUX_COMMAND # command
docker restart CONTAINER_ID # Restart container
```

# EXAMPLE

```sh
docker exec -it --user=root 123456 python3 -m pip install wheel
docker exec -it --user=root 123456 python3 -m pip install pipedrive-python-lib
docker exec -it --user=root 123456 apt-get update
docker exec -it --user=root 123456 apt-get install wkhtmltopdf
docker restart 123456
```
