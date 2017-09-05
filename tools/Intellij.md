Intellij 的使用笔记


# 如何根据具体的java文件定位到具体的package中位置？
```text
在intellij快速定位当前文件所在位置
在project面板的设置中勾选： project -> autoscroll from source
```

# intellij 根据匹配条件替换内容
 ```text

目前支持根据正则匹配内容； 例如：LOGGER\.warn\((.*)param is invalid! -> 特殊字符需要进行一层转义处理；

替换的内容不支持，根据正则进行替换；
 ```

# intellij 自动移除不需要的java引用
