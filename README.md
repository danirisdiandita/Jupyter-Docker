# Deploying our own Jupyter Notebook from Docker


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