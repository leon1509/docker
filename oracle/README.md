参数说明：
1. - /d/Downloads/oracle-setup:/install
  将下载的oracle安装文件解压到D:\Downloads\oracle-setup目录，看起来像这样：
  D
   |- Downloads
    |- oracle-setup
      |- database   -- oracle安装文件解压后的目录叫database

2. - /f/oracle/data:/u01/app/oracle
  将容器数据映射到宿主机的目录中
