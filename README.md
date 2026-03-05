openclaw官方文档：https://docs.openclaw.ai/

### 先准备好大模型的api key
访问openai平台：https://platform.openai.com/api-keys
<br>
生成api key，注意生成好就好复制保存好，否则之后不可见
<br><br>

### 创建新的telegram机器人
机器人可以重复使用，不用每次安装openclaw都申请<br>
搜索`@botfather`，进入对话<br>
输入`/newbot`，根据提示输入名称，保存token<br>
![图片描述](pic/3.png)
<br><br>
### 官方建议使用 WSL2，使用以下命令 `wsl -l -v` 查看版本，如图：<br>
![图片描述](pic/1.png)
<br><br>

### 设置代理，让WSL可以使用windows的代理工具V2RAY
设置-参数设置-允许来自局域网的连接
![图片描述](pic/4.png)

### 用管理员模式打开powershell，进入wsl，切换到root用户，执行安装命令：
```
curl -fsSL https://openclaw.ai/install.sh | bash
```
没有安装node.js的话，会自动安装<br>
需要等待一会<br>
![图片描述](pic/2.png)
