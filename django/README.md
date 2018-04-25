# django cmd

新建一个工程

```shell
django-admin startproject mysite
```

启动简易开发server

```shell
python manage.py runserver
python manage.py runserver 8080
python manage.py runserver 0:8000
```

创建一个应用

```shell
python manage.py startapp polls
```

数据库创建，迁移

```shell
python manage.py migrate
```

修改，生成一次迁移

```shell
python manage.py makemigrations polls
```

查看迁移sql

```shell
python manage.py sqlmigrate polls 0001
```

创建管理员

```shell
python manage.py createsuperuser
```

运行测试

```shell
python manage.py test polls
```