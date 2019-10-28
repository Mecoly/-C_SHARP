# WPF

## APP

## 窗口
### 窗口类别
标准窗口

无边框窗口

浮动窗口

工具窗口

### 创建显示

无模式
```
MyWindow myWindow = new MyWindow();
myWindow.Show();
```

模式

```
MyWindow myWindow = new MyWindow();
myWindow.ShowDialog();
```

### 关闭
`myWindow.close()`
### 窗口关联
Owner属性
## 对话框
### 类别
消息框：MessageBox

通用对话框：OpenFileDialog SaveFileDialog PrintFileDialog

自定义对话框：实际上是特殊的窗口

## 事件
### 鼠标事件
Click MouseDown MouseUp MouseMove MouseWheel MouseEnter MouseLeave
### 键盘事件
KeyDown KeyUp GotKeyboardFocus LostKeyboardFocus
## 控件
### 布局控件
|控件|功能|
|:-:|:-:|
|Grid|网格|
|StackPanel|堆叠面板|
|Canvas|画布|
### 基本控件
|控件|功能|
|:-:|:-:|
|Button|按钮|
|TextBlock|文本块|
|Label|标签|

