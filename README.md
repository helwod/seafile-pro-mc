# seafile-pro-mc
一个私人网盘工具docker版 

##  修改onlyoffice 服务预览
修改 容器名 seafile 路径下的文件/shared/seafile/conf/seahub_settings.py
找到下面内容并修改
```seahub_settings.py
FILE_SERVER_ROOT = "http://10.0.0.22:8083/seafhttp" #10.0.0.22修改成服务器ip
ONLYOFFICE_APIJS_URL = "http://10.0.0.22:10005/web-apps/apps/api/documents/api.js" # 10.0.0.22修改成服务器ip 注意路径是否一致
OFFICE_CONVERTOR_ROOT = 'http://10.0.0.22:10005/'    #10.0.0.22修改成服务器ip
```


# 免责声明：
此系统仅供个人学习、研究之用，请勿用于商业用途，请在下载后24小时内删除。
