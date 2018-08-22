# 七牛OSS文件上传工具
七牛图片上传工具，实现快速上传并返回访问链接。
使用方法:

0. 安装七牛依赖
````
    python -m pip install qiniu
````
1. 修改配置
````
    access_key = '你的AccessKey'
    secret_key = '你的SecretKey'
    bucket_name = '你的存储空间名'
    domain_name = '你的域名'
    style_code = '七牛样式代码'
````

2. 执行命令
````
    index.py image/test/ /Users/zackkkkk/img/img1.jpg
````


