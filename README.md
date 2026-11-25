# 研阅 · YanYue

### Vibe coding 了一个文献翻译软件

**需要什么功能，加什么功能。**

本仓库仅发布 Windows 正式版下载、版本说明和更新校验信息，源代码单独维护。

[下载最新正式版](https://github.com/SHADDOCK-TREE/yanyue-downloads/releases/latest)

## 能做什么

- PDF 连续阅读、框选与按页翻译、划词查询。
- 围绕原文提问，保存关联笔记和阅读卡片。
- 整理文献、词汇与每日任务，按需记录本机时间投入。
- 本地存储、旧资料复制导入与软件内更新。

## 开始使用

1. 下载最新 Release 中的 `YanYueReader-版本号-windows-x64.zip`。
2. 完整解压，运行 `YanYueReader/YanYueReader.exe`，保留 `_internal` 文件夹。需要 Windows 10/11 x64 和 WebView2 Runtime。
3. 导入 PDF；使用翻译、问答等 AI 功能前，在「设置与备份」配置自己的 DeepSeek API。

扫描 PDF 请先 OCR。AI 请求会将相关文本发送至所配置的服务，并消耗该服务额度。

## 数据与更新

记录默认保存在本机 `%LOCALAPPDATA%/YanYueReader`，与程序目录分开；公开下载包不含用户论文、数据库或密钥。旧版资料可在设置中复制导入，原资料保留。

软件内使用「检查更新 → 下载校验 → 安装并重启」。只有本仓库发布新的稳定 Release 后，软件才会提示更新；源码提交不会直接更新已安装的软件。

每个正式 Release 包含 ZIP、`update.json` 和 `SHA256SUMS.txt`。当前程序未进行代码签名，SHA256 用于核验下载完整性。

## 反馈

欢迎在本仓库 Issues 描述具体问题或想增加的功能。请勿公开上传 API Key、私人论文或笔记数据库。
