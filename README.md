# MiNotes
[中文]

1. MiCode便签是小米便签的社区开源版，由MIUI团队(www.miui.com) 发起并贡献第一批代码，遵循NOTICE文件所描述的开源协议，
## XTU软件工程实践开发
小米便签项目修改傻瓜板,直接git clone后在Android studio中打开,配置好基本依赖项后导入已配置好的gradle项目即可,一键式操作

1. git clone本仓库
```bash
git clone https://github.moeyy.xyz/https://github.com/nekocatso/MiNotes-master.git
```
2. 打开Android studio后导入本项目,安装好自带的SDK与配置好环境
3. 修改本项目文件夹下~\gradle\wrapper\gradle-wrapper.properties中的
distributionUrl=file:///C:/Users/Administrator/.gradle/wrapper/dists/gradle-8.4-bin.zip
把其中的gradle文件下载后放入指定地点即可
4. 点击build后直接调试运行即可
