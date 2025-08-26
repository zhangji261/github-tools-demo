# GitHub Tools Demo

这是一个展示如何使用GitHub工具的示例仓库。

## 项目结构

- `src/main/java/com/demo/Application.java` - Spring Boot主应用类
- `src/main/java/com/demo/controller/HelloController.java` - REST控制器
- `pom.xml` - Maven项目配置文件

## 功能特性

- Spring Boot Web应用
- REST API端点
- 简单的Hello World服务

## API端点

- `GET /hello` - 返回问候信息
- `GET /api/status` - 返回服务状态

## 构建和运行

```bash
mvn clean install
mvn spring-boot:run
```

## 创建目的

此仓库用于演示GitHub工具的各种功能，包括：
- 创建仓库
- 添加文件
- 创建分支
- 管理Issues和Pull Requests