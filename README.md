## 如何使用swaggo和gin-swaggo实现API文档
### 需要的环境
需要安装swag命令,运行：
```bigquery
 go get -u github.com/swaggo/swag/cmd/swag
 命令在go/src/bin下，确保该路径在path变量中，不然就加载不到
```


### 如何更新api
- 参照代码中的写好注解
- 每次更新api后，本地执行swag init命令进行更新

### 查看API文档
运行程序后，访问：
http://localhost:8080/swagger/index.html

本例子参看：https://github.com/swaggo/swag