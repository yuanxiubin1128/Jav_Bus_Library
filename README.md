# Jav_Bus_Library

### 构成

练手项目

前端：Vue + element-ui + bootstrap-vue

后端：flask + uwsgi +nginx

爬虫：scrapy

数据库：redis

### 启动

#### 网站服务器

```bash
$ python /JBL/run_server.py
```

#### 爬虫

启动容器：

```bash
$ python /JBL/run_scrapy_docker.py
```

在容器内运行爬虫：

```bash
$ python main.py 
```
