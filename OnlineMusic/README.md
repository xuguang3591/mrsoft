环境：python version 3.7

安装依赖：pip install –r requirements.txt

初始化数据库：新建shop数据库

执行迁移，初始化项目表：

python  manage.py  db  init     # 创建迁移仓库,首次使用  

python  manage.py  db  migrate   # 创建迁移脚本

python  manage.py  db  upgrade   # 把迁移应用到数据库中

导入初始化数据到shop数据库中：执行music.sql

启动项目：python manage.py runserver





