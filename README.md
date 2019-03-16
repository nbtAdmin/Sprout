# Sprout
Root repositories for docker files, client web application, api services 

## GitHub Repo Structure 
  
Client Web Application & API services Applications ---> Same repo structure for different MicroServices:
    
  Infrastucture:   
    - travis.yml (CI/CD config)   
    - Dockerrun.aws.json (aws env config)   
    - Docker-compose.yml   
    - Elastic BeanStalk
    
  DockerFiles :   
    - Web Application (angular app Directory)   
    - nginx conf dir
  
Environment variables of DataSources for config files :
  - Mongo(mlabs)
  - Redis
  - Elastic search
