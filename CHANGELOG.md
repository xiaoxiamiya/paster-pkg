# 更新记录

安装包放在 [GitHub Releases](https://github.com/xiaoxiamiya/paster-pkg/releases)，不放进代码目录。这里按版本记下每次发布改了什么。新的记录写在最上面。

## [1.4] - 2026-11-05

首次公开发布。安装包：[Paster-1.4.pkg](https://github.com/xiaoxiamiya/paster-pkg/releases/download/v1.4/Paster-1.4.pkg)

### 新增

- 菜单栏剪贴板历史。文字、图片、链接和文件留在本机，选中一条可贴回刚才的窗口。
- 底部面板。默认快捷键 **⇧⌘V**，可在设置里修改。
- 搜索、标签分组、卡片标题。
- 文本对比，以及 JSON、时间戳、Base64、URL、Cron 等文字工具。
- 设置里可调存储时长、外观、面板高度和快捷键，并支持用 JSON 导入、导出。

### 说明

- 需要 macOS 14 或更高版本，Apple Silicon（arm64）。
- 没有账号，剪贴板内容不上传。翻译使用系统翻译，只在本机处理。

## 发布下一版

1. 在本文件最上方写下版本号、日期，以及「新增」「变更」「修复」。没有的类别可以不写。
2. 提交文档后打标签，标签和版本号一致，例如 `v1.5`。
3. 用这个标签创建 [GitHub Release](https://github.com/xiaoxiamiya/paster-pkg/releases/new)，把 `Paster-1.5.pkg` 作为附件上传。
4. 安装包不要提交进仓库。本地的 `.pkg` 已被忽略。
