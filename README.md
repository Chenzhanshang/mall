# SpringBoot网上商城

## Docker镜像
### Pull image
```bash
docker pull skywa1ker/mall:latest
```
### Run
```bash
docker run -p 8081:8081 --name mall -v /data/mall/config:/data/mall/config -v /data/mall/log:/data/mall/log --restart=always -d skywa1ker/mall:latest
```
访问：http://127.0.0.1:8081/mall