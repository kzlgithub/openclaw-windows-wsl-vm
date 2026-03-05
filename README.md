openclaw官方文档：https://docs.openclaw.ai/

### 先准备好大模型的api key
访问openai平台：https://platform.openai.com/api-keys
<br>
生成api key，注意生成好就好复制保存好，否则之后不可见

### 官方建议使用 WSL2，使用以下命令 `wsl -l -v` 查看版本，如图：<br>
![图片描述](pic/1.png)
<br><br>
### 用管理员模式打开powershell，进入wsl，切换到root用户，执行安装命令：
```
curl -fsSL https://openclaw.ai/install.sh | bash
```
没有安装node.js的话，会自动安装<br>
需要等待一会<br>
![图片描述](pic/2.png)
