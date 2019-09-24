# dockerGhost
It's a web service which is built up by docker-compose.

This project consists of three docker images: "ghost", "nginx", "mysql:5.7.15".

效果如下
![image](ghost.png)

后台管理页:
![image](ghost2.png)

### 使用方式

```
docker-compose build // 创建容器
docker-compose up  // 启动项目，可查看输出信息
docker-compose up -d // 启动项目，后台执行
docker-compose stop // 停止容器
docker-compose rm // 删除所有容器
docker-compose logs // 观察容器的日志
docker-compose ps // 查看容器
```

网站首页：
http://localhost:80/
或
http://localhost:2368/

后台管理页：
http://localhost:80/ghost


### 参考
代码是慕课网“Docker入门” 课程的 实战代码，通过检验。

课程地址：https://www.imooc.com/learn/867
