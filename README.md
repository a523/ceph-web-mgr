# ceph-web-mgr
打造一个自己适用的ceph web管理平台。

### 期望目标
- 跨常见linux发行版
- 在命令行操作的时候，web同样有所反映
- 易上手
- 无任何单点故障，或可以方便组建高可用
### 开发环境：
- CentOS Linux release 7.3.1611
- python 3.4.5
- Django-2.0.5
### 借鉴资源：
- 前端模板
    1. gentelella https://github.com/puikinsh/gentelella
- 整体框架
    1. readthedocs.org
    https://github.com/rtfd/readthedocs.org
- 用户认证
    1. django-allauth
    https://github.com/pennersr/django-allauth
- ……
### 部署方法：
详细方法待补充，大致流程是这样的：
1. 获取代码
2. 安装依赖
3. 运行
    python manage.py runserver
