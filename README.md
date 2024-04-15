## 🌍 *[English](README-en.md) ∙ [简体中文](README.md)*

# 微信机器人-WechatBotCMD 🤖

微信机器人是一个基于Python 3.11开发的项目，它利用API调用微信原生能力，并与人工智能集成，以帮助用户完成一系列任务。这些任务包括但不限于：以高情商回复心仪的女生、制作头像、AI绘画、通过文字完成多个API处理（如获取天气、根据天气生成图片并自动发布到朋友圈等功能）。

<details><summary><font color="#FF0000" size="5">免责声明【必读】</font></summary>

本工具仅供学习和技术研究使用，不得用于任何商业或非法行为，否则后果自负。

本工具的作者不对本工具的安全性、完整性、可靠性、有效性、正确性或适用性做任何明示或暗示的保证，也不对本工具的使用或滥用造成的任何直接或间接的损失、责任、索赔、要求或诉讼承担任何责任。

本工具的作者保留随时修改、更新、删除或终止本工具的权利，无需事先通知或承担任何义务。

本工具的使用者应遵守相关法律法规，尊重微信的版权和隐私，不得侵犯微信或其他第三方的合法权益，不得从事任何违法或不道德的行为。

本工具的使用者在下载、安装、运行或使用本工具时，即表示已阅读并同意本免责声明。如有异议，请立即停止使用本工具，并删除所有相关文件。

</details>

## 特色功能 ✨
- **聊天画图**：结合ChatGPT模型的高级聊天和绘图能力，提供丰富的交互体验。
- **上下文记忆**：自动记忆与用户的对话上下文，如果10分钟内无回复，则忘记上下文。
- **对话历史限制**：最多记忆10条对话历史，确保交互的连贯性。
- **自动通过好友、自动拉群**
- **视频号视频下载**
- **自动发朋友圈、自动点赞**
- **直播间自动发弹幕**
- **视频号自动回复等**
- **微信防撤回（撤回消息回调）**
- **发送语音条**
- **语音转文字**

## 去水印机器在这里 
- **✨求Star✨** [全网最强去水印机器人](https://github.com/WeChatAPIs/WeChat-Video-Dewartermark)
- 支持视频号、抖音、快手、小红书、微博等各大自媒体平台

## 系统要求 💻

- **Windows操作系统** 或 **Windows云服务器**
- **Python 3.11**

## 安装 🔧

### 微信启动

- [API启动器来源](https://github.com/WeChatAPIs/WeChatAPI)

### 启动程序

1. 打开cmd，并进入 `wechatSDK` 目录，运行 `python -m venv venv`创建一个虚拟环境，并运行命令： `venv/Scripts/activate` 来开启虚拟环境。
2. 继续运行 `pip install -r requirements.txt` 将在该python虚拟环境中安装所有依赖。
3. 复制 `env_wechat_back.json` 文件并将其重命名为 `env_wechat.json`，然后修改文件内容(记得去除掉【|】以前的中文和空格，完整格式参考`env_wechat_example.json`)。
4. 运行 `python app.py` 启动程序。

## 依赖 📦

项目依赖于 [wechatAPI](https://github.com/WeChatAPIs/WeChatAPI)。请确保安装所有必要的依赖。

## 常问问题

- **JSON中的值如何填写**
  - 通过postman调用api填写json中最外层的wxid
  - 启动程序后，等待消息回调，在群内、给好友发信息接收到回调信息后填充json中其他值信息
- **ChatGPT并没有支持GPTs的API，你是如何做的**
  - 有些提供openai中转服务的厂商，他们通过破解openai的API，提供了GPTs的API服务，api价格比官方还便宜
  - 自用中转，推荐理由：稳定、价格低、售后服务好：[ChatGPT中转商](https://sourl.cn/p4JDca)
- **我不懂技术，如何才能跑起来项目**
  - 如果完全不懂，有点难，可以找身边人协助噢~
- **什么时候有界面化软件**
  - 我们新招的工程师正在开发功能界面，还请大家给实习生一些时间。
  - 如果您有兴趣一起参与功能界面的开发，欢迎联系（愿拿出部分收益作为开发维护者长期佣金）

## 如何贡献 🤝

欢迎通过Pull Requests来贡献代码。请确保您的代码符合项目的编码标准并通过所有测试。

## 效果展示 🖼️

![img_1_base.png](img%2Fimg_1_base.png)
![img_1_img.png](img%2Fimg_1_img.png)
![img_2_base.png](img%2Fimg_2_base.png)
![img_2_img.png](img%2Fimg_2_img.png)
![img_chat_base.png](img%2Fimg_chat_base.png)
![img.png](img%2Fimg.png)

## 许可证 📄

该项目根据MIT许可证授权。
