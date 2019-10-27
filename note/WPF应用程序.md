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
### 键盘事件
