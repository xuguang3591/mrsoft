# tequila
Tequila is a website contributed to give answers to rookies
* Using Python3
* Bulding with Tornado 5
* Using MySQL 5.7
* Using Asynchronous IO programming
* Using Multiple threading for database connection
* Using Multiple process for high performence
* Bulding a Django-like startup for project

步骤：
python version 3.7.7
pip install -r require
mysql v5.5+ 建库:create database bbs character set utf8 collate utf8_general_ci;
redis
配置conf.py DATABASE REDIS
执行数据库迁移：python manage.py migrate
运行项目：python manage.py run