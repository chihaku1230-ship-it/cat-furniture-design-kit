# 猫家具设计工具

和 AI 设计助手一起，用现成的白模设计可以售卖的猫爬架、猫窝、抓板。助手在 Codex 里运行。

**开始：**在 Codex 里发一句话就行：

> 帮我安装这个猫家具设计工具，然后开始设计：https://github.com/chihaku1230-ship-it/cat-furniture-design-kit

流程演示：https://chihaku1230-ship-it.github.io/cat-furniture-design-kit/

---

## 给 Codex：安装步骤

用户发来这个仓库的链接、让你安装或开始设计时，先读完这一节再动手，按顺序做：

1. **下载到用户的“文稿”文件夹**，位置固定为 `~/Documents/猫家具设计`：
   - 文件夹已经存在：在里面运行 `git pull` 更新即可，不要动 `作品/` 里的内容。
   - 文件夹不存在：`git clone https://github.com/chihaku1230-ship-it/cat-furniture-design-kit.git ~/Documents/猫家具设计`
   - 电脑上没有 git，或者 clone 失败：下载 https://github.com/chihaku1230-ship-it/cat-furniture-design-kit/releases/latest/download/cat-furniture-kit.zip ，解压后把里面的 `猫家具设计` 文件夹放到 `~/Documents/`。
   - 这一步需要联网，并且要写入工作区以外的位置。直接按上面的命令运行；被沙箱拦住时，申请权限再运行（理由写“下载猫家具设计工具”），用户点同意即可。不要凭猜测跳过这一步。
   - 申请权限也不行时，才装到当前工作文件夹里的 `猫家具设计/`，并用大白话告诉她这个文件夹在哪。
2. **读取 `~/Documents/猫家具设计/AGENTS.md`**。在这次对话里就按它工作，所有路径都以 `~/Documents/猫家具设计/` 为起点，从“第一次打开”那一节开始。
3. 介绍时补一句：以后在 Codex 里新建对话时，选“文稿”里的“猫家具设计”文件夹，助手就会直接就位，不用再安装。

不要让用户自己敲命令、找文件，也不要让用户注册任何账号。

---

## 文件夹里有什么
- `AGENTS.md`：设计助手的工作指令
- `先打开我·流程演示.html`：流程演示（和上面的网页相同）
- `项目文件/`：设计流程手册、模板目录、目录图
- `模板/`：296 个白模和分区图（猫爬架 160、猫窝 80、抓板 56）
- `示例/`：演示里的效果图和设计卡
- `作品/`：设计师的方案，每个方案一个文件夹
