# Woording
The main woording repository containing all submodules and docker-compose.yml

## How to Use
You'll need to have `docker`, isntalled, then just do this:
```bash
git submodule update --init --recursive
docker-compose up
```
The `woording-db` and `woording-api` containers are now both running, to connect to the API run `$ docker ps` to see the port of the `woording-api` container.  

To push commits from a submodule, use `git push origin HEAD:master`
