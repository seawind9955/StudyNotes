### 常用命令

1. du: 显示目录占用的磁盘空间
   1. `du  -h --max-depth=1 /`
2. wget: 下载网站内容
   1. `wget -r -p -np -k -H --no-check-certificte <url> -D <domain> -A shtml,html`
3. crontab: 设置定时任务
   1. crontab -e -l
4. lsof: 列出打开的文件
   1. 参考地址：https://www.jianshu.com/p/a3aa6b01b2e1
5. 将windows换行符改为linux换行符：
   1. `cat -v oldfile.py | sed -e '1,$s/\^M$//g' > newfile.py`





### 系统配置

1. 源码方式安装python3：https://www.cnblogs.com/xiujin/p/11477419.html

    