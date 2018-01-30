# baseOfLinux

### 2017/09/14

peer0 如果把代码考入以后, install ,instantiate 部署了以后,   其余的peer  只需要把代码考入  cli ,  install 即可请求




```
如果想查找这个语句里的结果包含什么  就用   | grep  xxxx

docker logs -f   dev-peer0.org1.example.com-qhchaincode10-1.2 | grep ok
invoke is running showWallet
Parse json is ok.
```

grep   检索目标行命令  
ps -ef | grep 解释

-A 　显示所有程序。 
-e 　此参数的效果和指定"A"参数相同。
-f 　显示UID,PPIP,C与STIME栏位。
grep命令是查找


```
chmod +x ./test.sh  #使脚本具有执行权限
./test.sh  #执行脚本
```

### 数字对比
#### -eq	等于则为真  equal
#### -ne	不等于则为真  not equal
#### -gt	大于则为真 greater than
#### -ge	大于等于则为真  great than or equal
#### -lt	小于则为真   less than
#### -le	小于等于则为真    less than or equal




### 字符串对比

#### =	等于则为真
#### !=	不相等则为真
#### -z 字符串	字符串的长度为零则为真
#### -n 字符串	字符串的长度不为零则为真


### 关于文件
-e 文件名	如果文件存在则为真
-r 文件名	如果文件存在且可读则为真
-w 文件名	如果文件存在且可写则为真
-x 文件名	如果文件存在且可执行则为真
-s 文件名	如果文件存在且至少有一个字符则为真
-d 文件名	如果文件存在且为目录则为真
-f 文件名	如果文件存在且为普通文件则为真
-c 文件名	如果文件存在且为字符型特殊文件则为真
-b 文件名	如果文件存在且为块特殊文件则为真


与( -a )、或( -o )、非( ! )三个逻辑操作符用于将测试条件连接起来，其优先级为："!"最高，"-a"次之，"-o"最低。
