# Deep Code

> AI 驱动的 CLI 编程助手 — Go 语言打造，单文件分发，一行命令即装即用。

---

## 效果预览

<img width="1518" height="873" alt="1" src="https://github.com/user-attachments/assets/bce251f3-c09b-4bca-a92b-1e3ce5f2d93c" />

---

## 安装

### 第一步：检查环境

Deep Code 通过 npm 安装，需要你的电脑有 Node.js。

先检查是否已安装——打开 **PowerShell**，输入：

```powershell
node --version
```

如果显示版本号（如 `v20.10.0`），跳到第二步。如果提示"不是内部或外部命令"，说明还没装，按下面步骤来：

1. 打开 https://nodejs.org
2. 下载 **LTS 版本**（左侧绿色按钮）
3. 运行安装包，一路点"下一步"即可
4. 安装完成后**关闭 PowerShell 重新打开**
5. 再次输入 `node --version`，看到版本号就成功了

### 第二步：安装 Deep Code

```powershell
npm install -g deep-code-xl
```

> 下载慢？先切国内镜像：
> ```powershell
> npm config set registry https://registry.npmmirror.com
> ```
> 再执行上面的安装命令。

### 第三步：启动

```powershell
deep-code
```

首次启动会自动引导你配置 API 地址和 Key，方向键选择、输入 Key 后回车即完成。

---

## 功能概览

| 类别 | 内容 |
|------|------|
| 内置工具 | Read / Write / Edit / Bash / Glob / Grep / Todo |
| 内置命令 | 19 个，`/help` 查看全部（`/plan` `/connect` `/model` `/theme` 等） |
| API 支持 | DeepSeek 官方 + OpenAI/Anthropic 双协议兼容 |
| ESC 打断 | 流式输出中按 ESC 立即中断，已生成内容保留 |
| 自动更新 | 启动时自动检查 GitHub 最新版，静默升级 |
| 平台 | Windows（PowerShell / Windows Terminal） |

---

## 基本使用

打开 Deep Code 后，像聊天一样对它说话就行：

```
> 你好，帮我写一个冒泡排序的 Go 实现
```

```
> 这个函数我没看懂，能用大白话解释一下吗
```

```
> 刚才的代码再改一版，我想要降序排列的
```

---

## 常见问题

**API 提示"余额不足"或连接失败**  
检查 Key 是否有效、额度是否用完。重新配置：`/connect login`

**模型无响应**  
尝试 `/model` 切换模型

**终端显示乱码**  
请使用 Windows Terminal 或新版 PowerShell，确保编码为 UTF-8

**隐私**  
API Key 和对话内容仅保存在本机 `%USERPROFILE%\.deep-code\` 目录，不上传

**卸载**
```powershell
npm uninstall -g deep-code-xl
```

---

## 反馈

📧 **1596761421@qq.com**

附上截图、版本号、复现步骤。

---

## 版本 · 许可证

当前版本：**v0.36.0** ｜ MIT License

**作者**：xielong ｜ **仓库**：[github.com/Violet1314/deep-code-xl](https://github.com/Violet1314/deep-code-xl)
