# flask_project
该项目是使用python语言，flask框架，按照flask官网做出的简单博客。

如何部署：(WINDOW环境)
1、下载该项目代码：
git clone https://github.com/fengpengjun/flask_project.git

2、下载之后部署虚拟环境
python -m venv venv
3、激活环境
venv\Scripts\activate
4、使用 pip 在虚拟环境中安装项目
pip install -e .
可以通过 pip list 来查看项目的安装情况
pip list

Package      Version Location
------------ ------- ----------------------------------------
click        7.1.2
Flask        1.1.2
flaskr       1.0.0   d:\develop\data\flask_test\flask_project
itsdangerous 1.1.0
Jinja2       2.11.2
MarkupSafe   1.1.1
pip          18.1
setuptools   40.6.2
Werkzeug     1.0.1

5、 设置FLASK_APP
set  FLASK_APP=flaskr
6、设置开发环境
set FLASK_ENV=development
7、创建数据库表
flask init-db
8、运行
flask run
