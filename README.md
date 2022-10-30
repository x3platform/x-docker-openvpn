# OpenVPN Docker

## Pull Docker
```
docker pull x3platform/openvpn
```

## Build Docker
```
# login
docker login -u [USERNAME] -p [PASSWORD]

docker buildx build --push --tag x3platform/openvpn:latest --platform linux/amd64 --file ./build/Dockerfile ./build/ 
```
