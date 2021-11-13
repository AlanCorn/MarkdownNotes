## 原因

在默认设置下，中文文件名在工作区状态输出，中文名不能正确显示，而是显示为八进制的字符编码。

## 解决方法

在终端输入

```shell
git config --global core.quotepath false 
```

