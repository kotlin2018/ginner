说明: 这是一个基于gin框架的后端api脚手架,思路来源于beego/bee 、gin-vue-admin
    集成了一些基础模块
    读取配置文件，
    跨域、jwt鉴权、日志打印到指定文件，
    用户注册、用户登陆、生成验证码
    输入参数验证

1、先下载该项目
````
git clone https://github.com/kotlin2019/ginner.git
````

2、编译该项目 
````
go build 
````

3、将编译后生成的可执行命令文件 ginner  放到 GOPATH/bin目录下
````
mv ginner ${GOPATH}/bin/
````

4、在任意目录下新建项目 (推荐: 在GOPATH/src目录下新建项目)
````
ginner -n 项目名称 
````
5、在新建项目根目录下初始化
````
go mod init 项目名称
````
6、编译新项目
````
go build
````
7、启动项目
````
go run main.go
````
8、默认端口 :8888
