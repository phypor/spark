#spark1.5.2的安装

###1.下载spark
```
wget http://mirrors.cnnic.cn/apache/spark/spark-1.5.2/spark-1.5.2.tgz 
tar -zxvf spark-1.5.2.tgz
mv spark-1.5.2 spark //改名字

注意：如下载不了，请到下面的网址找其他镜像地址
http://www.apache.org/dyn/closer.lua/spark/spark-1.5.2/spark-1.5.2.tgz
```
 
###2.配置文件
```
cd spark/conf
cp spark-env.sh.template spark-env.sh //创建启动脚本
```

###3.安装Scala
```
apt-get install scala
```
###4.编译运行
```
sbt/sbt update compile
```
