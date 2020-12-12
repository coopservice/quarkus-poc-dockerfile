# quarkus-poc-dockerfile
Dockerfile multistep to test all steps: git pull/maven build/docker build

## Testing
```
docker build -f Dockerfile --no-cache -t coopservice/quarkus-poc .
```
