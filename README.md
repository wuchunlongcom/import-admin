python3.7.5   django2.2.6  部署正常                      

### 使用django-import-export
```  
功能：
admin具有导入和导出数据库的数据功能。 
导入和导出数据库,支持多种格式，包括xls、csv、json、yaml以及tablib支持的所有其他格式。
```
```
一、运行      
1、运行：./start.sh 

二、 后台超级用户登录
用户名/密码  
admin/admin
```

```
import-admin
注意：1、上传git, 删除env；
     2、./start.sh -i   要保证env在工程中；
     3、本工程的 env与requirements.txt 必须配合使用；
     4、一个工程一个虚拟环境是必须的，否则容易产生本机运行正常，部署却不正常的问题。
```

```
python mysite/manage.py collectstatic
此时static目录下新增了static/import_export目录  

```

```
使用其中模块 https://github.com/django-import-export/django-import-export           
参考： https://django-import-export.readthedocs.io/en/latest/index.html
django-import-export库支持多种格式，包括xls、csv、json、yaml以及tablib支持的所有其他格式。        
```