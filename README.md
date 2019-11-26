# Drone-dotnetcore-CI/CD
Drone CI/CD with .NET core Web, WebAPI, Library, and console project Example

# manual process:
```
# Build container
cd Web
docker build -t core-container .
# Run final container, mapping 8080 on the local machine to 80 on the container.
docker run -p 8080:80 --rm -it core-container
```
