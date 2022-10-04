## Stack

- docker

- mysql

- metabase

- jupyter-notebook

  

## Setup

- Docker

https://docs.docker.com/engine/install/ubuntu/

- MySQL

```
docker run -p 3307:3306 --hostname localhost --name data-science-asg -e MYSQL_ROOT_PASSWORD=root -d mysql
```

- Metabase

https://www.metabase.com/docs/latest/installation-and-operation/running-metabase-on-docker#open-source-quick-start

- Jupyter-notebook
	- install [pyenv](https://github.com/pyenv/pyenv#installation) 

```
pyenv install anaconda3-2022.05
```

