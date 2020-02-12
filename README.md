python3.7.5   django2.2.6  部署?                      

### 功能：使用django-import-export  admin具有导入和导出数据库的数据功能。 
      
```
一、 运行      
1、运行：./start.sh 

二、 后台超级用户登录
用户名/密码  
admin/admin

三、用户登录
http://localhost:8000/
```

```
参考文档：
excel 文件的导入
https://www.cnblogs.com/yjlch1016/archive/2019/08/18/11373785.html   # ok
python mysite/manage.py collectstatic
此时static目录下新增了static/import_export目录  

```

```
使用其中模块 https://github.com/django-import-export/django-import-export           
django-import-export库支持多种格式，包括xls、csv、json、yaml以及tablib支持的所有其他格式。      

参考： https://django-import-export.readthedocs.io/en/latest/index.html       
```