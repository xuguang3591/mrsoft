# examination

* Offer a platform to take a skill quizz
* Rank users who participate in the quizz and give them suggestions for career
* Help organizations to make out questions for interviewee
* Using Django 1.11.2 Python3.5 and MySQL5.7 Bootstrap3
* the site is under building http://www.quizz.cn and the source code places here



环境：python version 3.7

安装依赖：pip install –r requirements.txt

初始化数据库：新建exam数据库

安装redis

修改配置文件：config/local_settings.py和config/settings.py

执行迁移，初始化项目表：

python  manage.py  db  makemigrations    # 创建迁移仓库,首次使用  

python  manage.py  db  migrate   # 创建迁移脚本

导入初始化数据到exam数据库中：执行exam.sql

启动项目：python manage.py runserver

