# How to run
Docker compose needs at least 262144 memory. Run `sudo sysctl -w vm.max_map_count=262144` each time a machine is rebooted or increase permanently https://stackoverflow.com/questions/56937171/efk-elasticsearch-1-exited-with-code-78-when-install-elasticsearch.
Run `sudo docker compose up`.
Run `sudo docker compose stop` and `sudo docker compose down` to bring down the service.