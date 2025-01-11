# Openledger_Bot
Openledger.xyz的项目

注册地址：https://testnet.openledger.xyz/?referral_code=swpstmlzqe

## 注意事件
openledger会获取粘贴板的所有权限，请在虚拟机下安装插件，或者安装插件获取了相关信息就停用或者卸载！

为什么我们还要运行呢？撸毛我们要有不放过任何一个项目的精神去做！

## 1、教程开始
### 1.1、在运行脚本之前，设置 config.txt
``config.txt``写法
```txt
token||||identity||||uuid||||ownerAddress||||proxy
```
uuid生成地址：https://www.uuidgenerator.net/

workerID获取办法，点击打开插件，右键：检查，打开开发者功能，找到(``orch?auth...``) 点击消息(``message``),找到identity和ownerAddress

token怎么抓？
```txt
orch?authToken=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ...
```
orch?authToken=地址后面的就是token

### 1.2、生成文件说明
程序运行会生成``data.json`` ``log.txt`` ``credentials.txt``

``data.json``作用：生成矿工配置文件，可以删除，会再次生成

``log.txt``作用：群友提议保存运行日志文件。觉得可惜就干了

``credentials.txt``作用：序列号存放文件，全套脚本通用
## 2、运行脚本
### 2.1、Mac
```bash
wget url地址
unzip Openledger_Mac_1.0.zip
cd Openledger_Linux
chmod +x Openledger_Mac
./Openledger_Mac
```

### 2.2、Win
```txt
双击Openledger.exe
```

### 2.3、Linux
```bash
wget url地址
unzip Openledger_Mac_1.0.zip
cd Openledger_Linux
chmod +x Openledger_Mac
./Openledger_Mac
```
