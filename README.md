# footstep-mark

> 标记记录文档中指定位置，并提供快速定位位置功能

## 插件说明

### 底部栏按钮

![](https://qiniu.img.chenkai.xyz/footstep-mark.png)

底部栏会新增两个按钮

- 按钮一：用于右侧边打开一个新的编辑页面记录你在文档上标记的所有位置和备注信息
- 按钮二：用于关闭侧边编辑页并清空所有标记记录，删除所有信息

## 快捷键

- Ctrl+Alt+M ：此快捷键会在当前文档聚焦处（即光标位置）增加高亮背景色标记，并将该处位置，文本信息记录，如果侧边操作栏处于打开状态，会在侧边操作栏渲染； 如果聚焦处已被标记，则会取消该处标记，并删除所有相关信息
- Ctrl+Alt+N：此快捷键会在当前文档聚焦处（即光标位置），如果该位置已被 Ctrl+Alt+M 标记，则会弹出输入框，输入备注信息后回车，会在该位置增加备注信息，并将该信息显示于该位置后面，如果侧边操作栏处于打开状态，会在侧边操作栏同步渲染

## 侧边栏样式说明

![](https://qiniu.img.chenkai.xyz/footstep-mark10.png)

侧边栏样式如图

- 点击文件标题（即文件路径），会跳转对应文件
- 点击文件标题右侧的删除 icon，会删除该文件下的所有标记信息
- 点击列表各项，会快速跳转对应文档, 并且对应文档的标记位置会快速定位到中间位置
- 点击各项底部的删除按钮，会删除对应的标记信息（和 Ctrl+Alt+B 的操作效果一致）

## 另外

如果 Ctrl+Alt+M 快捷键不生效，可能是快捷键存在冲突，可以通过文件 ——> 首选项 ——> 键盘快捷方式 搜索 footstepMark 修改为没冲突的快捷方式使用
