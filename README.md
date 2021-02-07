# Running Azurite (Blob Storage) in Docker
Souce: https://hub.docker.com/_/microsoft-azure-storage-azurite


### Quick Deploy
```
docker pull mcr.microsoft.com/azure-storage/azurite
docker run -p 10000:10000 mcr.microsoft.com/azure-storage/azurite azurite-blob --blobHost 0.0.0.0
```
