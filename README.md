# Running Azurite (Blob Storage) in Docker
Source: https://hub.docker.com/_/microsoft-azure-storage-azurite


### Quick Deploy
```
docker pull mcr.microsoft.com/azure-storage/azurite
docker run -p 10000:10000 mcr.microsoft.com/azure-storage/azurite azurite-blob --blobHost 0.0.0.0
```

---------------------------

### Removing Docker Container
Removes a docker container (must be stopped)
- ```docker container rm <container name or id>```
  

### Renaming Docker Container
Renames a docker container.
- ```docker container rename <container name> <container name new>```
