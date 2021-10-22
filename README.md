# Deploying you own Jupyter Notebook using Docker

full tutorial is from here: https://u.group/thinking/how-to-put-jupyter-notebooks-in-a-dockerfile/

## Jupyter Notebook 
```
docker-compose up -d --build
```
and open http://localhost:8045

## Jupyter Lab 
```
docker-compose -f docker-compose-lab.yml up -d --build
```
and open http://localhost:8046