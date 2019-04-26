title: idea快捷键
date: 2016-11-09 15:10:43
updated: 2016-11-09 15:10:43
tags:
  - IntelliJ_IDEA
categories:
  - tools
---
# 开发工具

## IntelliJ Idea
### 实用快捷键:
- Ctrl+/ 或 Ctrl+Shift+/ 注释（// 或者/*...*/ ）
- Ctrl+D 复制行
- Ctrl+X 删除行
- 快速修复 alt+enter (modify/cast)
- 代码提示 alt+/
- ctr+G 定位某一行
- Shift+F6 重构-重命名
- Ctrl+R 替换文本
- Ctrl+F 查找文本
- Ctrl+E 最近打开的文件
- Ctrl+J 自动代码
- 组织导入 ctr+alt+O
- 格式化代码 ctr+alt+L
- 大小写转化 ctr+shift+U

### IntelliJ Idea 常用快捷键列表
- Alt+回车 导入包,自动修正
- Ctrl+N   查找类
- Ctrl+Shift+N 查找文件
- Ctrl+Alt+L  格式化代码
- Ctrl+Alt+O 优化导入的类和包
- Alt+Insert 生成代码(如get,set方法,构造函数等)
- Ctrl+E或者Alt+Shift+C  最近更改的代码
- Ctrl+R 替换文本
- Ctrl+F 查找文本
- Ctrl+Shift+Space 自动补全代码
- Ctrl+空格 代码提示
- Ctrl+Alt+Space 类名或接口名提示
- Ctrl+P 方法参数提示
- Ctrl+Shift+Alt+N 查找类中的方法或变量
- Alt+Shift+C 对比最近修改的代码
- Shift+F6  重构-重命名
- Ctrl+Shift+先上键
- Ctrl+X 删除行
- Ctrl+D 复制行
- Ctrl+/ 或 Ctrl+Shift+/  注释（// 或者/*...*/ ）
- Ctrl+J  自动代码
- Ctrl+E 最近打开的文件
- Ctrl+H 显示类结构图
- Ctrl+Q 显示注释文档
- Alt+F1 查找代码所在位置
- Alt+1 快速打开或隐藏工程面板
- Ctrl+Alt+ left/right 返回至上次浏览的位置
- Alt+ left/right 切换代码视图
- Alt+ Up/Down 在方法间快速移动定位
- Ctrl+Shift+Up/Down 代码向上/下移动。
- F2 或Shift+F2 高亮错误或警告快速定位
- 代码标签输入完成后，按Tab，生成代码。
- 选中文本，按Ctrl+Shift+F7 ，高亮显示所有该文本，按Esc高亮消失。
- Ctrl+W 选中代码，连续按会有其他效果
- 选中文本，按Alt+F3 ，逐个往下查找相同文本，并高亮显示。
- Ctrl+Up/Down 光标跳转到第一行或最后一行下
- Ctrl+B 快速打开光标处的类或方法 

### 1. IDEA内存优化
因机器本身的配置而配置：
```
\IntelliJ IDEA 8\bin\idea.exe.vmoptions  
-----------------------------------------  
-Xms64m  
-Xmx256m  
-XX:MaxPermSize=92m  
-ea  
-server  
-Dsun.awt.keepWorkingSetOnMinimize=true
```
### 2. 查询快捷键
- CTRL+N   查找类 
- CTRL+SHIFT+N  查找文件 
- CTRL+SHIFT+ALT+N 查找类中的方法或变量 
- CIRL+B   找变量的来源 
- CTRL+ALT+B  找所有的子类 
- CTRL+SHIFT+B  找变量的类 
- CTRL+G   定位行 
- CTRL+F   在当前窗口查找文本 
- CTRL+SHIFT+F  在指定窗口查找文本 
- CTRL+R   在 当前窗口替换文本 
- CTRL+SHIFT+R  在指定窗口替换文本 
- ALT+SHIFT+C  查找修改的文件 
- CTRL+E   最近打开的文件 
- F3   向下查找关键字出现位置 
- SHIFT+F3  向上一个关键字出现位置 
- F4   查找变量来源 
- CTRL+ALT+F7  选中的字符查找工程出现的地方 
- CTRL+SHIFT+O  弹出显示查找内容

### 3. 自动代码
- ALT+回车  导入包,自动修正 
- CTRL+ALT+L  格式化代码 
- CTRL+ALT+I  自动缩进 
- CTRL+ALT+O  优化导入的类和包 
- ALT+INSERT  生成代码(如GET,SET方法,构造函数等) 
- CTRL+E 最近更改的代码 
- CTRL+SHIFT+SPACE 自动补全代码 
- CTRL+空格  代码提示 
- CTRL+ALT+SPACE  类名或接口名提示 
- CTRL+P   方法参数提示 
- CTRL+J   自动代码 
- CTRL+ALT+T  把选中的代码放在 TRY{} IF{} ELSE{} 里

### 4. 复制快捷方式
- CTRL+D   复制行 
- CTRL+X   剪切,删除行  

### 5. 其他快捷方式
- CIRL+U   大小写切换 
- CTRL+Z   倒退 
- CTRL+SHIFT+Z  向前 
- CTRL+ALT+F12  资源管理器打开文件夹 
- ALT+F1   查找文件所在目录位置 
- SHIFT+ALT+INSERT 竖编辑模式 
- CTRL+/   注释//   
- CTRL+SHIFT+/  注释/*...*/ 
- CTRL+W   选中代码，连续按会有其他效果 
- CTRL+B   快速打开光标处的类或方法 
- ALT+ ←/→  切换代码视图 
- CTRL+ALT ←/→  返回上次编辑的位置 
- ALT+ ↑/↓  在方法间快速移动定位 
- SHIFT+F6  重构-重命名 
- CTRL+H   显示类结构图 
- CTRL+Q   显示注释文档 
- ALT+1   快速打开或隐藏工程面板 
- CTRL+SHIFT+UP/DOWN 代码向上/下移动。 
- CTRL+UP/DOWN  光标跳转到第一行或最后一行下 
- ESC   光标返回编辑框 
- SHIFT+ESC  光标返回编辑框,关闭无用的窗口 
- F1   帮助千万别按,很卡! 
- CTRL+F4   非常重要下班都用

## Eclipse
- Ctrl + 2,L  补全  自己改为Alt + q
- 选中按F4 或 Ctrl + t   进入层次视图-----体系结构
- Alt+/	内容补全
- Ctrl + 1  帮助
- Ctrl + d  删除当前行
- Ctrl + M  最大化当前的Edit或View (再按则反之)
- Ctrl + f  查找/替换
- Ctrl + 点击   进入源码
- Alt + Shift + r   改名
- Ctrl + Shift + o   快速导包
- Ctrl + Shift + r   打开源
- Ctr + Shift + f   格式化代码
- Ctrl + Shift + x   变大写
- Ctrl + Shift + x   变小写
- Ctrl + Shift + t   类查询
- syso + Alt + /   输出
- Alt + ←   前一个编辑的页面
- Alt + →   下一个编辑的页面
- Alt + 上箭头	上移
- Alt + 下箭头	下移
- Ctrl + /	单行注释
- Ctrl + Shift + /   多行注释
- Ctrl + Shift + \   取消注释
- Ctrl + Shift + c   适用于各种文档的注释
- Ctrl + Alt + 上箭头/下箭头   上复制/下复制
- Alt + Shift + s   源操作
- Alt + Shift + t   方法操作
- Alt + Shift + z   语句操作
- Alt + Shift + m   提取方法
- Alt + Shift + L	  提取本地变量
- Alt + 1   packageExporer显示
- Alt + 2   console显示
- Alt + 3   Outline显示
- 小绿圆圈------>方法
- 小绿三角------>属性
- 带土红色 s ----->静态
- Alt + 4   navigator导航显示