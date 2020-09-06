# Desarquivo Collection
Collection engine for Desarquivo


### Docker
Run docker-compose `docker-compose up -d` (`-d` for detached). 

Warning (Windows users): mongodb cannot create Windows volumes by default, so do one of the following:
<!-- * workaround:
  * comment mongo service in [docker-compose.yml](docker-compose.yml)
  * `docker volume create --name=mongodata`-->
* comment the mongo service from [docker-compose.yml](docker-compose.yml) and use a local version
* comment out the `volumes` line for the `mongo` service in [docker-compose.yml](docker-compose.yml)

### Locally
* Install requirements (perhaps with virtual environment `pyhton -m venv env` + `source env/bin/activate` (Linux) | `./env/Scripts/activate` (Windows)) `pip install -r requirements.txt`