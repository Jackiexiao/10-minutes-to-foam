


# 序言
推荐程序员、极客、vscode用户使用Foam。Foam的[官方文档](https://foambubble.github.io/foam/)读完比较耗时，所以做了一个快速入门的指南，方便用户尝鲜。
  - [更多的使用技巧Recipes](https://foambubble.github.io/foam/recipes)
  - [中文文档-网友翻译](https://github.com/xiaoland/Foam-Chinese-Document)
# 目录
- [安装](#安装)
  - [安装Vscode](#安装vscode)
  - [安装Foam（Foam是vscode的插件）](#安装foamfoam是vscode的插件)
  - [更多](#更多)
- [快捷键](#快捷键)
- [插件教程](#插件教程)
- [常见问题](#常见问题)
  - [修改字体为微软雅黑](#修改字体为微软雅黑)
- [更新日志](#更新日志)

# 安装
下面的内容参考[Foam中文文档](https://github.com/xiaoland/Foam-Chinese-Document/blob/master/foam/gettting_started.md)
## 安装Vscode
- vscode下载链接：[Visual Studio Code](https://visual-studio-code.en.softonic.com/)
- 设置vscode的显示语言：进入vscode后，输入`Crtl+Shift+P`(或点击View>Command Palette)进入命令面板，然后输入「configure language」，选择「Configure Display Language」，然后就可以安装中文显示插件啦！

## 安装Foam（Foam是vscode的插件）
- 1、使用foam-template生成一个新的git存储库
  - 如果您已经登录github，那么你就可以点击这个链接直接创建：[Use this template](https://github.com/foambubble/foam-template/generate)
  - 请注意，如果你想保留你自己的构思，请记住把存储库设置为私有
  - 或者你压根不想在github上托管**或者没有github账户**，那么请点击此链接下载Foam模板的zip文件：[Download foam-template's zip file](https://github.com/foambubble/foam-template/archive/master.zip)
- 2、将你的git存储库克隆到本地，然后用vscode打开
  - 在vscode中，选择「File>Open...」来打开你的存储库
- 3、当出现提示安装推荐的插件时，选择[Install All]安装全部，或者点击[Show Recommendations]来选择安装插件
- 4、设置完毕以后，你可以通过在.vscode下的setting.json改变Foam的设置

# 快捷键
注意：
* foam的默认配置，注意Mac用户将`Ctrl`改为`Cmd`*

| 功能                  | 快捷键               |
| --------------------- | -------------------- |
| 打开日记              | `Alt + D `           |
| 切换文件              | `Ctrl + P`           |
| 预览markdown-新窗口   | `Ctrl + Shift + V`   |
| 预览markdown-右侧窗口 | `Ctrl + K V`         |
| 打开命令窗口          | `Ctrl + shift + P`   |
| 切换颜色主题          | `ctrl + K, ctrl + T` |

首先`Ctrl + shift + P`打开命令窗口，然后输入下面的命令

| 功能             | 命令                         | 快捷键    |
| ---------------- | ---------------------------- | --------- |
| 打开日记         | Foam: Open Daily Note        | `Alt + D` |
| 打开backlink链接 | Explorer: Focus on Backlinks | 无        |
| 打开图谱         | Show graph                   | 无        |
| 新建笔记         | new note                     | 无        |
| 创建文档目录     | toc / table of content       | 无        |

缺乏快捷键的可以自己绑定：[修改快捷键的方法](https://code.visualstudio.com/docs/getstarted/keybindings)

| Markdown快捷键     | 功能                      |
| ------------------ | ------------------------- |
| `Ctrl + B`         | 加粗                      |
| `Ctrl + I`         | 斜体                      |
| `Ctrl + Shift + ]` | 提升标题层级              |
| `Ctrl + Shift + [` | 降低标题层级              |
| `Ctrl + M `        | 开启数学模式              |
| `Alt + C`          | 标记任务todo为完成/未完成 |
| `Alt + Shift + F`  | 将表格样式规范化/美观化   |

# 插件教程
foam其实是一个插件的集合，要充分使用foam，可以看这些插件的文档
* [markdown all in one](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)

# 常见问题
## 修改字体为微软雅黑
  * `ctrl + ,`打开设置，进入`font`设置，改成`"editor.fontFamily": "Consolas, 'Courier New', monospace, '微软雅黑'",`
  
# 更新日志

2020-8-10

目前尝试下来的感受
* 优点
  * vscode的插件，而且基本功能都有（双向链接、图谱、markdown）
* 缺点
  * 对普通用户不友好
  * 没有块引用
  * 不支持插入截图
  * 我也是obsidian用户，目前数据迁移会有点问题

