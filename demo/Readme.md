## docker案例演示
1. 本地有一个nodejs项目
2. 使用docker生成镜像
3. 使用docker运行镜像
```
npm i
docker build -t docker_demo .
docker run -d -p 9000:3000 docker_demo
```