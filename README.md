# nginx
An official read-only mirror of http://hg.nginx.org/nginx/ which is updated hourly. Pull requests on GitHub cannot be accepted and will be automatically closed. The proper way to submit changes to nginx is via the nginx development mailing list, see http://nginx.org/en/docs/contributing_changes.html

1.运行auto/configure脚本生成ngx_modules.c等源文件，不然直接阅读代码会缺少变量定义
2.make clean会删除掉Makefile，需要重新运行configure脚本
