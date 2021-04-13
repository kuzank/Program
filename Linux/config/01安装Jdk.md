
## 1、上传 jdk 解压版本然后解压
```

```

## 2、配置 jdk 环境 /etc/profile
```
vim /etc/profile
```

在文件最后添加
```
export JAVA_HOME=/root/jdk1.8.0_161
export PATH=$JAVA_HOME/bin:$PATH
export CLASSPATH=.:$JAVA_HOME/lib/dt.jar:$JAVA_HOME/lib/tools.jar 
```

## 3、生效
```
source /etc/profile
```

## 4、检查 Jdk 版本
```
java -version
```